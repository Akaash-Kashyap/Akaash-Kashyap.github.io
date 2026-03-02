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
      San Diego, California
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

    <div id="form-success" class="form-feedback form-feedback--success" style="display:none;">
      Message sent — I'll get back to you soon.
    </div>
    <div id="form-error" class="form-feedback form-feedback--error" style="display:none;">
      Something went wrong. Please try again or reach out via LinkedIn.
    </div>

    <form id="contact-form">
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
      <button type="submit" id="submit-btn" class="btn btn-primary" style="margin-top: 0.5rem; width: 100%; justify-content: center;">
        Send Message
      </button>
    </form>
  </div>

</div>

<script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@4/dist/email.min.js"></script>
<script>
  emailjs.init('KSpIiipF_P_OEtt4b');

  document.getElementById('contact-form').addEventListener('submit', function(e) {
    e.preventDefault();

    var btn     = document.getElementById('submit-btn');
    var success = document.getElementById('form-success');
    var error   = document.getElementById('form-error');

    btn.disabled    = true;
    btn.textContent = 'Sending\u2026';
    success.style.display = 'none';
    error.style.display   = 'none';

    emailjs.sendForm('service_zo2u7sm', 'template_e1bejg8', this)
      .then(function() {
        success.style.display = 'block';
        document.getElementById('contact-form').reset();
        btn.disabled    = false;
        btn.textContent = 'Send Message';
      }, function() {
        error.style.display = 'block';
        btn.disabled    = false;
        btn.textContent = 'Send Message';
      });
  });
</script>
