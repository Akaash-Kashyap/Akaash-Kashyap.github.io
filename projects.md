---
layout: default
title: Projects
---

<div class="page-header">
  <h1>Projects</h1>
  <p class="subtitle">Systems programming, hardware design, and automation</p>
</div>

<div class="projects-list">

  <div class="project-card">
    <div class="project-card-header">
      <h2>GPIO Device Driver &mdash; Raspberry Pi</h2>
    </div>
    <div class="project-card-body">
      <img src="/assets/img/projects/raspi_driver.jpg" alt="Raspberry Pi GPIO Driver" class="project-img">
      <div class="project-desc">
        <p>Developed a Linux kernel-mode GPIO driver in C that exposes a procfs interface for user-space GPIO control.</p>
        <p>Directly manipulated the Raspberry Pi's GPIO registers via memory-mapped I/O without relying on any library abstraction.</p>
        <p>Used <code>printk</code> and <code>dmesg</code> for debug logging to ensure reliable operation and simplify troubleshooting.</p>
        <div class="tag-list">
          <span class="tag">C</span>
          <span class="tag">Embedded Linux</span>
          <span class="tag">Kernel Modules</span>
          <span class="tag">dmesg</span>
        </div>
      </div>
    </div>
  </div>

  <div class="project-card">
    <div class="project-card-header">
      <h2>RISC-V Out-of-Order Processor</h2>
    </div>
    <div class="project-card-body">
      <img src="/assets/img/projects/cpu.jpg" alt="RISC-V OoO Processor" class="project-img">
      <div class="project-desc">
        <p>Implemented a 4-stage out-of-order RISC-V core in SystemVerilog supporting the RV32IM instruction set.</p>
        <p>Includes a GShare branch predictor, early branch recovery, and line-buffered instruction and data caches. Passes all test benchmarks with correct execution.</p>
        <p>Reached <strong>450 MHz</strong> and placed in the <strong>top 20%</strong> of an Optiver-hosted design competition.</p>
        <div class="tag-list">
          <span class="tag">SystemVerilog</span>
          <span class="tag">Synopsys</span>
          <span class="tag">Computer Architecture</span>
          <span class="tag">Digital Design</span>
        </div>
      </div>
    </div>
  </div>

  <div class="project-card">
    <div class="project-card-header">
      <h2>TCP over UDP</h2>
    </div>
    <div class="project-card-body">
      <img src="/assets/img/projects/TCP.jpg" alt="TCP over UDP" class="project-img">
      <div class="project-desc">
        <p>Built a reliable transport protocol on top of UDP, replicating core TCP mechanisms: packet sequencing, acknowledgments, retransmissions, and congestion control.</p>
        <p>Handled full connection setup and teardown, timeout management, and sliding window-based flow control for reliable end-to-end communication.</p>
        <div class="tag-list">
          <span class="tag">C/C++</span>
          <span class="tag">Socket Programming</span>
          <span class="tag">Docker</span>
          <span class="tag">Wireshark</span>
        </div>
      </div>
    </div>
  </div>

  <div class="project-card">
    <div class="project-card-header">
      <h2>391 Operating System</h2>
    </div>
    <div class="project-card-body">
      <img src="/assets/img/projects/391os.png" alt="391 OS" class="project-img">
      <div class="project-desc">
        <p>Collaborated with a team to architect and develop a ground-up operating system from scratch.</p>
        <p>Implemented paging, terminal switching, a filesystem, mouse and keyboard drivers, and PID support for up to 6 concurrent programs.</p>
        <p>Developed in C and x86 assembly; tested and run on QEMU.</p>
        <div class="tag-list">
          <span class="tag">C</span>
          <span class="tag">x86 Assembly</span>
          <span class="tag">QEMU</span>
          <span class="tag">Operating Systems</span>
          <span class="tag">Git</span>
        </div>
      </div>
    </div>
  </div>

  <div class="project-card">
    <div class="project-card-header">
      <h2>Mailing List Generator</h2>
    </div>
    <div class="project-card-body">
      <img src="/assets/img/projects/mail.png" alt="Mailing List Generator" class="project-img">
      <div class="project-desc">
        <p>Developed a pair of Google Apps Scripts that extract and deduplicate contact information from Google Calendar events and Gmail threads.</p>
        <p>Parses attendee and sender data, then writes organized mailing lists directly to Google Sheets. Optimized for reliability and ease-of-use.</p>
        <p>Actively used by CloudBYZ's business and marketing teams to reduce manual overhead and improve outreach efficiency.</p>
        <div class="tag-list">
          <span class="tag">Google Apps Script</span>
          <span class="tag">JavaScript</span>
          <span class="tag">Google Sheets API</span>
          <span class="tag">Gmail API</span>
        </div>
      </div>
    </div>
  </div>

</div>
