---
layout: default
title: Projects
---

# Projects

Here are some of my key technical projects that demonstrate my skills in computer architecture, systems programming, and security.

<div class="projects-container">


  <div class="project-card">
    <div class="project-header">
      <h2>GPIO Device Driver - Raspberry Pi</h2>
      <!-- <div class="project-links">
        <a href="https://github.com/yourusername/secure-iot-gateway" target="_blank">GitHub</a>
        <a href="https://yourprojectdemo.com" target="_blank">Demo</a>
      </div> -->
    </div>
    <div class="project-content">
      <img src="assets/img/projects/raspi_driver.jpg" alt="IoT Security Gateway" class="project-image">
      <div class="project-description">
        <p>Developed a Linux kernel-mode GPIO driver in C that exposes a procfs interface for GPIO control.</p>
        <p>Directly manipulated the Raspberry Pi's GPIO registers via memory-mapped I/O.</p>
        <p>Employed Debug logging via printk and dmesg to ensure reliable operation and facilitate troubleshooting.</p>
        <div class="project-tech">
          <span>C</span>
          <span>Embedded Linux</span>
          <span>Drivers</span>
          <span>dmesg</span>
        </div>
      </div>
    </div>
  </div>

  <div class="project-card">
    <div class="project-header">
      <h2>RISC-V Out Of Order Processor Implementation</h2>
      <!-- <div class="project-links">
        <a href="https://github.com/yourusername/riscv-processor" target="_blank">GitHub</a>
      </div> -->
    </div>
    <div class="project-content">
      <img src="assets\img\projects\cpu.jpg" alt="RISC-V Processor Design" class="project-image">
      <div class="project-description">
        <p>Implemented a 4-stage Out Of Order RISC-V Core in SystemVerilog, supporting the RV32IM instruction set.</p>
        <p>The design includes a GShare branch predictor, Early Branch Recovery, line-buffered instruction and data caches, and passes all test benchmarks with correct execution.</p>
        <p>Reached 450 mHz and achieved top 20% in design competition hosted by Optiver</p>
        <div class="project-tech">
          <span>SystemVerilog</span>
          <span>Synopsys</span>
          <span>Computer Architecture</span>
          <span>Digital Design</span>
        </div>
      </div>
    </div>
  </div>

  <div class="project-card">
    <div class="project-header">
      <h2>TCP over UDP Implementation</h2>
      <!-- <div class="project-links">
        <a href="https://github.com/yourusername/kernel-memory" target="_blank">GitHub</a>
      </div> -->
    </div>
    <div class="project-content">
      <img src="assets/img/projects/TCP.jpg" alt="Memory Allocator" class="project-image">
      <div class="project-description">
        <p>Developed a reliable transport protocol over UDP, replicating core TCP features such as packet sequencing, acknowledgments, retransmissions, and congestion control.</p>
        <p>Handled connection setup and teardown, timeout management, and sliding window-based flow control to ensure reliable end-to-end communication.</p>
        <div class="project-tech">
          <span>C/C++</span>
          <span>Docker</span>
          <span>Wireshark</span>
          <span>Socket Programming</span>
        </div>
      </div>
    </div>
  </div>

  <div class="project-card">
    <div class="project-header">
      <h2>391 Operating System</h2>
      <!-- <div class="project-links">
        <a href="https://github.com/yourusername/gpu-crypto" target="_blank">GitHub</a>
      </div> -->
    </div>
    <div class="project-content">
      <img src="assets/img/projects/391os.png" alt="391os" class="project-image">
      <div class="project-description">
        <p>Collaborated within a team to architect and develop a ground-up operating system.</p>
        <p>Leveraged skills in C programming, x86 assembly, and utilized a QEMU emulator for development</p>
        <p>Implemented paging, terminal switching, filesystem, mouse and keyboard drivers, and PID support for up to 6 additional programs.</p>
        <div class="project-tech">
          <span>C (Programming Language)</span>
          <span>x86 Assembly</span>
          <span>git</span>
          <span>Operating System Design</span>
        </div>
      </div>
    </div>
  </div>

  <div class="project-card">
    <div class="project-header">
      <h2>Mailing List Generator</h2>
      <!-- <div class="project-links">
        <a href="https://github.com/yourusername/gpu-crypto" target="_blank">GitHub</a>
      </div> -->
    </div>
    <div class="project-content">
      <img src="assets/img/projects/mail.png" alt="Mailing List Generator" class="project-image" style="height: 20%; width:20%; justify-content:center; align-content:center;">
      <div class="project-description">
        <p>Re-engaged with CloudBYZ to streamline and automate mailing list generation.
        Developed a pair of Google Apps Scripts that extract and deduplicate contact information from Google Calendar events and Gmail threads. The scripts generate organized mailing lists by parsing attendee and sender data, then writing results to Google Sheets.
        Optimized for reliability and ease-of-use, the solution is actively used by CloudBYZ’s business and marketing teams to reduce manual overhead and improve outreach efficiency.</p>
        <div class="project-tech">
          <span>C (Programming Language)</span>
          <span>x86 Assembly</span>
          <span>git</span>
          <span>Operating System Design</span>
        </div>
      </div>
    </div>
  </div>

</div>

<style>
  .projects-container {
    display: flex;
    flex-direction: column;
    gap: 2.5rem;
    margin-top: 2rem;
  }
  
  .project-card {
    border: 1px solid #e0e0e0;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 3px 6px rgba(0,0,0,0.1);
  }
  
  .project-header {
    background-color: #f5f5f5;
    padding: 1rem 1.5rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 1px solid #e0e0e0;
  }
  
  .project-header h2 {
    margin: 0;
    font-size: 1.5rem;
    color: #333;
  }
  
  .project-links a {
    display: inline-block;
    margin-left: 10px;
    text-decoration: none;
    color: #0066cc;
    font-weight: 500;
    padding: 4px 10px;
    border-radius: 4px;
    border: 1px solid #0066cc;
    font-size: 0.9rem;
  }
  
  .project-links a:hover {
    background-color: #0066cc;
    color: white;
  }
  
  .project-content {
    display: flex;
    padding: 1.5rem;
  }
  
  .project-image {
    width: 200px;
    height: auto;
    margin-right: 1.5rem;
    border-radius: 4px;
    object-fit: cover;
  }
  
  .project-description {
    flex: 1;
  }
  
  .project-tech {
    margin-top: 1rem;
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
  }
  
  .project-tech span {
    background-color: #e9f2fd;
    color: #0066cc;
    padding: 4px 10px;
    border-radius: 20px;
    font-size: 0.8rem;
    font-weight: 500;
  }
  
  @media (max-width: 768px) {
    .project-content {
      flex-direction: column;
    }
    
    .project-image {
      width: 100%;
      margin-right: 0;
      margin-bottom: 1rem;
    }
    
    .project-header {
      flex-direction: column;
      align-items: flex-start;
    }
    
    .project-links {
      margin-top: 0.5rem;
    }
    
    .project-links a {
      margin-left: 0;
      margin-right: 10px;
    }
  }
</style>