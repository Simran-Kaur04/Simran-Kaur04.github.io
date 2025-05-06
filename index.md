---
layout: default
---

<div style="font-family:'Segoe UI',sans-serif;padding:40px;background:#0f1117;color:#f1f1f1;min-height:100vh;">

  <h1 style="color:#ff9800;font-size:2.5rem;text-shadow:0 0 8px rgba(255,152,0,0.4);">👋 Simran Kaur</h1>
  <h3 style="color:#cfcfcf;font-weight:normal;margin-top:10px;">Data Scientist | Analyst | ML Enthusiast</h3>

  <p style="margin-top:15px;margin-bottom:30px;font-size:1.1rem;line-height:1.6;">
    Welcome to my portfolio. Scroll down to explore my background, projects, and certifications.
  </p>

  <hr style="border:none;border-top:1px solid #333;margin:30px 0;" />

  <!-- Navigation -->
  <nav style="margin-bottom:40px;">
    <a href="#about" style="margin-right:20px;color:#64b5f6;text-decoration:none;font-weight:bold;">About</a>
    <a href="#projects" style="margin-right:20px;color:#64b5f6;text-decoration:none;font-weight:bold;">Projects</a>
    <a href="#certifications" style="margin-right:20px;color:#64b5f6;text-decoration:none;font-weight:bold;">Certifications</a>
    <a href="#contact" style="color:#64b5f6;text-decoration:none;font-weight:bold;">Contact</a>
  </nav>

  <!-- About Section -->
  <div id="about" style="background:#1a1c23;padding:25px;border-radius:12px;box-shadow:0 2px 10px rgba(0,0,0,0.3);margin-bottom:60px;">
    {% include about.md %}
  </div>

  <!-- Projects Section -->
  <div id="projects" style="background:#1a1c23;padding:25px;border-radius:12px;box-shadow:0 2px 10px rgba(0,0,0,0.3);margin-bottom:60px;">
    {% include projects.md %}
  </div>

  <!-- Certifications Section -->
  <div id="certifications" style="background:#1a1c23;padding:25px;border-radius:12px;box-shadow:0 2px 10px rgba(0,0,0,0.3);margin-bottom:60px;">
    {% include certifications.md %}
  </div>

  <!-- Contact Section -->
  <div id="contact" style="background:#1a1c23;padding:25px;border-radius:12px;box-shadow:0 2px 10px rgba(0,0,0,0.3);">
    {% include contact.md %}
  </div>

</div>


