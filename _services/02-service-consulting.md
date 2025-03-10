---
title: 'Short-Term Consulting'
thumbnail: 'assets/images/red-phone.png'
summary: 'Short-Term (one quarter) relationships engaging The AI Clinic for ongoing support.'
---

The AI Clinic engages in short-term (one academic quarter) relationships that provide ongoing support for projects that would benefit from AI. For each project we commit to, we schedule up to two hours of regular weekly office hours dedicated to providing advice to help the project succeed. A designated representative for your project would consistently attend these office hours and form an ongoing relationship with clinic experts.

We are pleased to be able to offer short-term consulting support entirely free of charge. Please note that for this free tier of support, clinic experts are not expected to work on the project outside of the designated weekly office hours. If more involved support outside of office hours is needed, or the project is expected to run for longer than one academic quarter, our [long-term consulting services]('/03-service-long-term.md) are likely more appropriate for your project.

To inquire about engaging the AI Clinic in a short-term relationship, please complete the form below, and we'll get back to you as soon as possible.

<div class="form-body">
<form
  action="https://formspree.io/f/mqaeryde"
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
        event.preventDefault();
        this.style.display = "none";
        document.getElementById("confirmation").style.display = "block";
    });
</script>
</div>