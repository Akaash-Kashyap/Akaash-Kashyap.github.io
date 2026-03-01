---
layout: default
title: Contact
---

<div class="page-header">
  <h1>Contact</h1>
  <p class="subtitle">Open to new opportunities and conversations</p>
</div>

<div class="contact-layout">

  <div class="contact-sidebar">
    <span class="section-label">Get in touch</span>

    <div class="contact-item">
      <i class="fas fa-map-marker-alt"></i>
      Champaign-Urbana, Illinois
    </div>

    <span class="section-label" style="margin-top: 1.5rem;">Elsewhere</span>
    <div class="social-links">
      <a class="social-link" href="https://github.com/akaash-kashyap" target="_blank" title="GitHub">
        <i class="fab fa-github"></i>
      </a>
      <a class="social-link" href="https://linkedin.com/in/akaashkashyap" target="_blank" title="LinkedIn">
        <i class="fab fa-linkedin"></i>
      </a>
    </div>
  </div>

  <div class="contact-form-section">
    <span class="section-label">Send a message</span>
    <form action="https://formspree.io/f/xwpokwzr" method="POST">
      <div class="form-group">
        <label for="name">Name</label>
        <input type="text" id="name" name="name" placeholder="Your name" required>
      </div>
      <div class="form-group">
        <label for="email">Email</label>
        <input type="email" id="email" name="email" placeholder="your@email.com" required>
      </div>
      <div class="form-group">
        <label for="subject">Subject</label>
        <input type="text" id="subject" name="subject" placeholder="What's this about?" required>
      </div>
      <div class="form-group">
        <label for="message">Message</label>
        <textarea id="message" name="message" rows="5" placeholder="Your message..." required></textarea>
      </div>
      <input type="hidden" name="_captcha" value="false">
      <input type="text" name="_honey" style="display:none">
      <button type="submit" class="btn btn-primary" style="margin-top: 0.5rem; width: 100%; justify-content: center;">
        Send Message
      </button>
    </form>
  </div>

</div>
