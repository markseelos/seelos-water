---
layout: default
title: Contact
permalink: /contact/
---

<section class="contact-page">

  <div class="contact-card">
    <h1>Contact</h1>

    <p class="lead">
      For inquiries, please use the form below.
      I typically respond within a few business days.
    </p>

    <form action="https://formspree.io/f/mrenvwnk" method="POST" class="contact-form">

      <div class="form-field">
        <label for="name">Name</label>
        <input type="text" id="name" name="name" autocomplete="name" required>
      </div>

      <div class="form-field">
        <label for="email">Email</label>
        <input type="email" id="email" name="email" autocomplete="email" required>
      </div>

      <div class="form-field">
        <label for="organization">Organization</label>
        <input type="text" id="organization" name="organization" autocomplete="organization">
      </div>

      <div class="form-field">
        <label for="subject">Subject</label>
        <input type="text" id="subject" name="subject" autocomplete="off" required>
      </div>

      <div class="form-field">
        <label for="message">Message</label>
        <textarea id="message" name="message" rows="7" required></textarea>
      </div>

      <input type="hidden" name="_subject" value="New inquiry from Seelos Water website">
      <input type="text" name="_gotcha" class="form-honeypot" tabindex="-1" autocomplete="off">

      <button type="submit">Send Message</button>
    </form>
  </div>

</section>
