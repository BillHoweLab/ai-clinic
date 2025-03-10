---
title: 'Long-Term Consulting'
thumbnail: 'assets/images/red-calendar.png'
summary: 'Opportunities to establish a long-term relationship with The AI Clinic and its faculty.'
---

The AI Clinic can provide in-depth support for projects that are well-aligned with its mission. In addition to the two hours of weekly office hours support provided in short-term consulting engagements, long-term engagements include approximately twenty hours per week of support from a clinic expert. The clinic maintains its own research computing infrastructure, including a GPU array, which may be utilized to support long-term engagements. Long-term consulting projects can extend for longer than a single academic quarter, though progress made on the project and the state of the consulting relationship will be evaluated at the end of each quarter, and continuation of the project will be at the discretion of both parties. 

To support long-term consulting, we collect an up-front fee equivalent to the cost of a research assistantship at the University of Washington, which enables us to adequately fund the time of the expert supporting the project. Long-term consulting projects typically need to be well-aligned with the background and interests at least one clinic expert, to ensure that we can provide meaningful guidance as the project evolves.

To inquire about a long-term consulting relationship, please complete the form below, and we'll get back to you as soon as possible.

<div class="form-body">
<form
  action="https://formspree.io/f/myzkrndw"
  method="POST"
>
    <label for="name">Full Name:</label>
    <input type="text" id="name" name="name" required>
    
    <label for="email">Email Address:</label>
    <input type="email" id="email" name="email" required>
    
    <label for="organization">Organization Type:</label>
    <select id="service" name="service" required>
        <option value="">Select</option>
        <option value="academic">Academic</option>
        <option value="public">Public Sector</option>
        <option value="nonprofit">Nonprofit</option>
        <option value="other">Other</option>
    </select>
    
    <label for="message">Project Details:</label>
    <textarea id="message" name="message" rows="4" placeholder="Please tell us in 3-5 sentences about the project for which you'd like to engage us."></textarea>

    <label for="data-details">Data Details:</label>
    <textarea id="message" name="message" rows="2" placeholder="Please tell us in 1-2 sentences about the data needed for the project. Do you have the data in hand, or will it need to be collected? Can the data be shared publicly after the project is complete?"></textarea>

    <label for="need">Project Need:</label>
    <textarea id="message" name="message" rows="2" placeholder="Please tell us in 1-2 sentences why the project is underserved by traditional market forces."></textarea>

    <label for="people">Clinic Experts:</label>
    <textarea id="message" name="message" rows="1" placeholder="Are there any clinic experts you're specifically interested in working with?."></textarea>

    <label for="referral">If we are not able to help with your project, can we refer your message to our University partners (such as the eScience Institute)?:</label>
    <select id="refer-pref" name="refer-pref" required>
        <option value="">Select</option>
        <option value="yes">Yes</option>
        <option value="no">No</option>
    </select>

    <button type="submit">Submit</button>
</form>

<p id="confirmation" style="display:none; color: green; font-weight: bold;">Thank you for reaching out. We will contact you soon.</p>

<script>
    document.getElementById("consultingForm").addEventListener("submit", function(event) {
        event.preventDefault(); // Prevent actual form submission
        
        // Hide form and show confirmation message
        this.style.display = "none";
        document.getElementById("confirmation").style.display = "block";
    });
</script>
</div>