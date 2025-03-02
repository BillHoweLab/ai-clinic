---
title: 'Short-Term Consulting'
thumbnail: 'assets/images/red-phone.png'
summary: 'Short-Term (3 months or fewer) relationships engaging The AI Clinic for ongoing research support.'
---

The AI Clinic offers short-term consulting relationships that can provide ongoing support for projects that would benefit from AI-driven analysis. Beyond
simply answering questions, we can assist in writing research code, selecting or designing appropriate methods for using LLMs in research, and
providing support in describing those methods during the authorship of research publications.

Short-term consulting relationships require a fee equal to the cost of supporting one graduate student for a single quarter. While this affords you
the 20 hours per week that typically come with a graduate RA-ship, you also receive the full support of the center's faculty, and access to our on-premises
computing resources.

To inquire about a long-term consulting relationship, please complete the form below, and we'll get back to you as soon as possible.

<div class="form-body">
<form id="short-consultingForm">
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