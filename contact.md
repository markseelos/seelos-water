---
layout: default
title: Contact
permalink: /contact/
---

<section class="contact-page">

  <div class="contact-content">
    <h1>Contact</h1>

    <p class="lead">
      For project inquiries, technical support, or potential collaboration, please use the form below.
      I typically respond within a few business days.
    </p>

    <form action="https://formspree.io/f/mrenvwnk" method="POST" class="contact-form">
      <label for="name">Name</label>
      <input type="text" id="name" name="name" autocomplete="name" required>

      <label for="email">Email</label>
      <input type="email" id="email" name="email" autocomplete="email" required>

      <label for="organization">Organization</label>
      <input type="text" id="organization" name="organization" autocomplete="organization">

      <label for="project-type">Project Type</label>
      <select id="project-type" name="project_type">
        <option value="">Select one</option>
        <option value="TMDL implementation or regulatory support">TMDL Implementation / Regulatory Support</option>
        <option value="Water quality monitoring">Water Quality Monitoring</option>
        <option value="Groundwater or SGMA">Groundwater / SGMA</option>
        <option value="Production wells or well planning">Production Wells / Well Planning</option>
        <option value="Reservoir or surface water quality">Reservoir / Surface Water Quality</option>
        <option value="GIS or statistical analysis">GIS / Statistical Analysis</option>
        <option value="Utility project planning">Utility Project Planning</option>
        <option value="Other">Other</option>
      </select>

      <label for="message">Message</label>
      <textarea id="message" name="message" rows="7" required></textarea>

      <input type="hidden" name="_subject" value="New inquiry from Seelos Water website">
      <input type="text" name="_gotcha" class="form-honeypot" tabindex="-1" autocomplete="off">

      <button type="submit">Send Message</button>
    </form>
  </div>

</section>
