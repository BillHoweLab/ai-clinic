---
title: 'Long-Term Consulting'
thumbnail: 'assets/images/red-calendar.png'
summary: 'Opportunities to establish a long-term relationship with The AI Clinic and its faculty.'
---

Faculty, organizations, and other members of the UW community can form a long-term consulting relationship with The AI Clinic that provides ongoing
access to the Center's expertise, students, and resources. Situations in which a long-term relationship might be appropriate include those
that are likely to last longer than three months or which may require the purchase of new resources to support the relationship.

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