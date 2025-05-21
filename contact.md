---
layout: default
title: Contact
---

# Contact Me

I'm always interested in discussing new projects, opportunities, or just connecting with fellow professionals in the field.

## Get In Touch

<div class="contact-container">
  <div class="contact-info">
    <div class="contact-item">
      <i class="fas fa-envelope"></i>
      <p><a href="mailto:akaashkashyap@example.com">akaashkashyap@example.com</a></p>
    </div>
    
    <div class="contact-item">
      <i class="fas fa-map-marker-alt"></i>
      <p>Champaign-Urbana, Illinois</p>
    </div>
    
    <div class="contact-social">
      <h3>Connect With Me</h3>
      <div class="social-links">
        <a href="https://github.com/akaash-kashyap" target="_blank" title="GitHub">
          <i class="fab fa-github"></i>
        </a>
        <a href="https://linkedin.com/in/akaashkashyap" target="_blank" title="LinkedIn">
          <i class="fab fa-linkedin"></i>
        </a>
      </div>
    </div>
  </div>
  
  <div class="contact-form">
    <h3>Send Me a Message</h3>
    <form action="https://formsubmit.co/akaashkashyap@gmail.com" method="POST">
      <div class="form-group">
        <label for="name">Name</label>
        <input type="text" id="name" name="name" required>
      </div>
      
      <div class="form-group">
        <label for="email">Email</label>
        <input type="email" id="email" name="email" required>
      </div>
      
      <div class="form-group">
        <label for="subject">Subject</label>
        <input type="text" id="subject" name="subject" required>
      </div>
      
      <div class="form-group">
        <label for="message">Message</label>
        <textarea id="message" name="message" rows="5" required></textarea>
      </div>
      <input type="hidden" name="_captcha" value="false">
      <input type="text" name="_honey" style="display:none">
      <button type="submit">Send Message</button>
    </form>
  </div>
</div>

<style>
  .contact-container {
    display: flex;
    flex-wrap: wrap;
    gap: 2rem;
    margin-top: 2rem;
  }
  
  .contact-info {
    flex: 1;
    min-width: 300px;
  }
  
  .contact-form {
    flex: 1.5;
    min-width: 300px;
  }
  
  .contact-item {
    display: flex;
    align-items: center;
    margin-bottom: 1rem;
  }
  
  .contact-item i {
    font-size: 1.2rem;
    color: #0066cc;
    margin-right: 1rem;
    width: 20px;
    text-align: center;
  }
  
  .social-links {
    display: flex;
    gap: 1rem;
    margin-top: 0.5rem;
  }
  
  .social-links a {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    background-color: #f5f5f5;
    color: #333;
    text-decoration: none;
    transition: all 0.3s ease;
  }
  
  .social-links a:hover {
    background-color: #0066cc;
    color: white;
  }
  
  .form-group {
    margin-bottom: 1.2rem;
  }
  
  label {
    display: block;
    margin-bottom: 0.5rem;
    font-weight: 500;
  }
  
  input, textarea {
    width: 100%;
    padding: 0.75rem;
    border: 1px solid #ddd;
    border-radius: 4px;
    font-family: inherit;
    font-size: 1rem;
  }
  
  button {
    background-color: #0066cc;
    color: white;
    border: none;
    padding: 0.75rem 1.5rem;
    border-radius: 4px;
    font-size: 1rem;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }
  
  button:hover {
    background-color: #0055aa;
  }
  
  @media (max-width: 768px) {
    .contact-container {
      flex-direction: column;
    }
  }
</style>

<!-- Add Font Awesome for icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">