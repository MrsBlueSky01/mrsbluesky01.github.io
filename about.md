---
layout: default
title: About / Hakkımda
---

<style>
  .about-container {
    display: flex;
    flex-direction: column;
    gap: 40px;
    padding: 20px;
  }

  .lang-section {
    border-bottom: 1px dashed rgba(253, 125, 193, 0.3);
    padding-bottom: 40px;
  }

  .lang-section:last-child {
    border-bottom: none;
  }

  h2.section-title {
    color: #fd7dc1 !important;
    text-transform: uppercase;
    letter-spacing: 2px;
    border-left: 4px solid #fd7dc1;
    padding-left: 15px;
    margin-bottom: 25px;
    font-size: 1.5rem;
  }

  .cv-text {
    line-height: 1.8;
    font-size: 1.1rem;
    color: #d9e2ec;
    margin-bottom: 20px;
  }

  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    margin-top: 20px;
  }

  .skill-item {
    background: rgba(114, 32, 110, 0.2);
    border: 1px solid rgba(253, 125, 193, 0.2);
    border-radius: 8px;
    padding: 15px;
    transition: all 0.3s ease;
  }

  .skill-item:hover {
    border-color: #fd7dc1;
    box-shadow: 0 0 15px rgba(253, 125, 193, 0.2);
    transform: scale(1.02);
  }

  .skill-item strong {
    color: #fff;
    display: block;
    margin-bottom: 5px;
    text-transform: uppercase;
    font-size: 0.9rem;
  }

  .skill-item span {
    color: #f8a5e3;
    font-family: 'Courier New', monospace;
  }

  .contact-btn {
    display: inline-block;
    margin-top: 30px;
    padding: 12px 25px;
    background: transparent;
    border: 2px solid #fd7dc1;
    color: #fd7dc1;
    text-transform: uppercase;
    font-weight: bold;
    border-radius: 50px;
    transition: all 0.3s ease;
  }

  .contact-btn:hover {
    background: #fd7dc1;
    color: #000;
    box-shadow: 0 0 20px #fd7dc1;
  }
</style>

<div class="about-container">
  
  <section class="lang-section">
    <h2 class="section-title">Hakkımda</h2>
    <div class="cv-text">
      <p>Üniversite hayatım boyunca aktif olarak yazılım kulübünde yer aldım ve üniversiteler arası oyun geliştirme projelerine hem çizim hem de yazılım alanında katkı sağladım. Mezuniyet projem kapsamında Flutter kullanarak evcil hayvan bakımına yönelik bir mobil uygulama geliştirdim ve GitHub’da barındırılan React tabanlı bir web sitesi oluşturdum.</p>
      <p>Gerçek dünya deneyimi kazanmak adına bir bankada staj yaptım ve bir kurumsal web sitesini tasarlayıp yayına aldığım freelance projem oldu.</p>
      <p>Kendimi full-stack veya mobil geliştirme alanlarında geliştirmek için motiveyim. Katkı sağlayabileceğim ve aynı zamanda kendimi geliştirebileceğim bir yazılım ekibinin parçası olmayı hedefliyorum.</p>
    </div>

    <div class="skills-grid">
      <div class="skill-item">
        <strong>Programlama Dilleri</strong>
        <span>HTML, CSS, JS, C#, SQL, Java, Python</span>
      </div>
      <div class="skill-item">
        <strong>Frameworkler</strong>
        <span>React, Flutter, .NET</span>
      </div>
      <div class="skill-item">
        <strong>Araçlar</strong>
        <span>Git, GitHub, Firebase, MySQL</span>
      </div>
    </div>

  </section>

  <section class="lang-section">
    <h2 class="section-title">About Me</h2>
    <div class="cv-text">
      <p>During my university years, I was an active member of the software club and contributed to intercollegiate game development projects in both art and programming. For my graduation project, I developed a mobile application for pet care using Flutter and created a React-based website hosted on GitHub.</p>
      <p>To gain real-world experience, I interned at a bank and completed a freelance project where I designed and launched a corporate website.</p>
      <p>I am highly motivated to improve myself in full-stack or mobile development. I aim to be part of a software team where I can contribute and grow professionally.</p>
    </div>

    <div class="skills-grid">
      <div class="skill-item">
        <strong>Programming Languages</strong>
        <span>HTML, CSS, JS, C#, SQL, Java, Python</span>
      </div>
      <div class="skill-item">
        <strong>Frameworks</strong>
        <span>React, Flutter, .NET</span>
      </div>
      <div class="skill-item">
        <strong>Tools</strong>
        <span>Git, GitHub, Firebase, MySQL</span>
      </div>
    </div>

    <a href="ayseyarenkuruy@gmail.com" class="contact-btn">Let's Connect / İletişime Geç</a>

  </section>

</div>
