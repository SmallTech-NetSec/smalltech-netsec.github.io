<html><head><base href="https://smalltech-networks.eg/" />
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SmallTech: Networking & Cybersecurity | Maadi, Cairo</title>
<style>
  :root {
    --primary-color: #2c3e50;
    --secondary-color: #34495e;
    --text-color: #333;
    --bg-color: #f5f5f5;
    --accent-color: #3498db;
  }
  
  body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    color: var(--text-color);
    background-color: var(--bg-color);
    margin: 0;
    padding: 0;
    transition: all 0.3s ease;
  }
  
  body.rtl {
    direction: rtl;
    font-family: 'Cairo', sans-serif;
  }
  
  header {
    background-color: #ecf0f1;
    color: var(--primary-color);
    padding: 1rem 0;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1000;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  }
  
  nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 1rem;
  }
  
  .logo {
    font-size: 1.5rem;
    font-weight: bold;
    color: var(--primary-color);
    text-decoration: none;
    display: flex;
    align-items: center;
  }
  
  .logo svg {
    width: 30px;
    height: 30px;
    margin-right: 10px;
    fill: var(--accent-color);
  }
  
  body.rtl .logo svg {
    margin-right: 0;
    margin-left: 10px;
  }
  
  nav ul {
    display: flex;
    list-style: none;
    margin: 0;
    padding: 0;
  }
  
  nav ul li {
    margin-left: 1.5rem;
  }
  
  body.rtl nav ul li {
    margin-left: 0;
    margin-right: 1.5rem;
  }
  
  nav ul li a {
    color: var(--primary-color);
    text-decoration: none;
    transition: color 0.3s ease;
    font-weight: 600;
  }
  
  nav ul li a:hover {
    color: var(--accent-color);
  }
  
  main {
    max-width: 1200px;
    margin: 6rem auto 2rem;
    padding: 0 1rem;
  }
  
  .hero {
    background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
    color: white;
    text-align: center;
    padding: 4rem 1rem;
    border-radius: 10px;
    margin-bottom: 3rem;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  }
  
  .hero h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
  }
  
  .hero p {
    font-size: 1.2rem;
    max-width: 700px;
    margin: 0 auto 2rem;
  }
  
  .cta-button {
    display: inline-block;
    background-color: var(--accent-color);
    color: white;
    padding: 0.8rem 2rem;
    border-radius: 5px;
    text-decoration: none;
    font-weight: bold;
    transition: all 0.3s ease;
  }
  
  .cta-button:hover {
    background-color: #2980b9;
    transform: translateY(-3px);
    box-shadow: 0 4px 10px rgba(0,0,0,0.2);
  }
  
  .services, .technologies {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
    margin-top: 3rem;
  }
  
  .service-card, .tech-card {
    background-color: white;
    border-radius: 10px;
    padding: 2rem;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    transition: all 0.3s ease;
  }
  
  .service-card:hover, .tech-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0,0,0,0.15);
  }
  
  .service-card h3, .tech-card h3 {
    color: var(--primary-color);
    margin-bottom: 1rem;
  }
  
  .service-icon, .tech-icon {
    font-size: 2.5rem;
    color: var(--accent-color);
    margin-bottom: 1rem;
  }
  
  .about, .contact {
    margin-top: 3rem;
    background-color: white;
    border-radius: 10px;
    padding: 2rem;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  }
  
  footer {
    background-color: var(--primary-color);
    color: white;
    text-align: center;
    padding: 1.5rem 0;
    margin-top: 3rem;
  }
  
  .language-switch {
    background-color: var(--accent-color);
    color: white;
    border: none;
    padding: 0.5rem 1rem;
    border-radius: 5px;
    cursor: pointer;
    transition: all 0.3s ease;
  }
  
  .language-switch:hover {
    background-color: #2980b9;
  }
  
  @media (max-width: 768px) {
    nav {
      flex-direction: column;
    }
    
    nav ul {
      margin-top: 1rem;
    }
    
    nav ul li {
      margin: 0 0.5rem;
    }
    
    body.rtl nav ul li {
      margin: 0 0.5rem;
    }
  }
</style>
</head>
<body>
  <header>
    <nav>
      <a href="#" class="logo">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
          <path d="M12 0C5.373 0 0 5.373 0 12s5.373 12 12 12 12-5.373 12-12S18.627 0 12 0zm0 22c-5.523 0-10-4.477-10-10S6.477 2 12 2s10 4.477 10 10-4.477 10-10 10zm-3-9H7v-2h2v2zm4 0h-2v-2h2v2zm4 0h-2v-2h2v2z"/>
        </svg>
        <span class="logo-text">SmallTech</span>
      </a>
      <ul>
        <li><a href="#home" class="nav-home">Home</a></li>
        <li><a href="#services" class="nav-services">Services</a></li>
        <li><a href="#technologies" class="nav-technologies">Technologies</a></li>
        <li><a href="#about" class="nav-about">About</a></li>
        <li><a href="#contact" class="nav-contact">Contact</a></li>
        <li><button class="language-switch">عربي</button></li>
      </ul>
    </nav>
  </header>
  
  <main>
    <section id="home" class="hero">
      <h1 class="hero-title">SmallTech: Networking & Cybersecurity</h1>
      <p class="hero-subtitle">Professional IT solutions for Maadi's businesses</p>
      <a href="#contact" class="cta-button">Get a Consultation</a>
    </section>
    
    <section id="services" class="services">
      <div class="service-card">
        <div class="service-icon">🖥️</div>
        <h3>Network Infrastructure</h3>
        <p>Design, implementation, and maintenance of robust network systems tailored to your business needs.</p>
        <ul>
          <li>LAN/WAN design and setup</li>
          <li>Network performance optimization</li>
          <li>VPN configuration</li>
          <li>Wireless network deployment</li>
        </ul>
      </div>
      <div class="service-card">
        <div class="service-icon">🔒</div>
        <h3>Cybersecurity</h3>
        <p>Comprehensive security solutions to protect your digital assets from evolving threats.</p>
        <ul>
          <li>Firewall implementation and management</li>
          <li>Intrusion Detection and Prevention Systems (IDS/IPS)</li>
          <li>End-point protection</li>
          <li>Security awareness training</li>
        </ul>
      </div>
      <div class="service-card">
        <div class="service-icon">☁️</div>
        <h3>Cloud Services</h3>
        <p>Seamless cloud integration and management for enhanced flexibility and scalability.</p>
        <ul>
          <li>Cloud migration strategies</li>
          <li>Hybrid cloud solutions</li>
          <li>Cloud security and compliance</li>
          <li>SaaS, PaaS, and IaaS implementations</li>
        </ul>
      </div>
      <div class="service-card">
        <div class="service-icon">🛠️</div>
        <h3>IT Consulting</h3>
        <p>Expert advice on IT strategy and implementation to align technology with your business goals.</p>
        <ul>
          <li>IT infrastructure assessment</li>
          <li>Technology roadmap development</li>
          <li>Vendor selection and management</li>
          <li>IT budgeting and cost optimization</li>
        </ul>
      </div>
    </section>
    
    <section id="technologies" class="technologies">
      <h2>Technologies We Support</h2>
      <div class="tech-card">
        <h3>Networking</h3>
        <ul>
          <li>Cisco (Routers, Switches, ASA Firewalls)</li>
          <li>Juniper Networks</li>
          <li>Aruba Wireless</li>
          <li>Ubiquiti UniFi</li>
        </ul>
      </div>
      <div class="tech-card">
        <h3>Cybersecurity</h3>
        <ul>
          <li>Fortinet FortiGate</li>
          <li>Palo Alto Networks Firewalls</li>
          <li>Symantec Endpoint Protection</li>
          <li>Splunk SIEM</li>
        </ul>
      </div>
      <div class="tech-card">
        <h3>Cloud Platforms</h3>
        <ul>
          <li>Microsoft Azure</li>
          <li>Amazon Web Services (AWS)</li>
          <li>Google Cloud Platform (GCP)</li>
          <li>Oracle Cloud Infrastructure</li>
        </ul>
      </div>
      <div class="tech-card">
        <h3>Virtualization</h3>
        <ul>
          <li>VMware vSphere</li>
          <li>Microsoft Hyper-V</li>
          <li>Citrix Hypervisor</li>
          <li>KVM</li>
        </ul>
      </div>
      <div class="tech-card">
        <h3>Backup & Recovery</h3>
        <ul>
          <li>Veeam Backup & Replication</li>
          <li>Acronis Cyber Protect</li>
          <li>Commvault</li>
          <li>Dell EMC Data Protection Suite</li>
        </ul>
      </div>
      <div class="tech-card">
        <h3>Productivity & Collaboration</h3>
        <ul>
          <li>Microsoft 365</li>
          <li>Google Workspace</li>
          <li>Slack</li>
          <li>Zoom</li>
        </ul>
      </div>
    </section>
    
    <section id="about" class="about">
      <h2 class="about-title">About SmallTech</h2>
      <p>SmallTech, founded by Islam Mohammed Adel AbouShady, is Maadi's leading provider of professional networking and cybersecurity solutions. We specialize in delivering enterprise-grade technology tailored for small to medium-sized businesses.</p>
      <p>Our team of certified professionals brings years of experience in IT infrastructure, security, and cloud technologies. We're committed to helping local businesses leverage cutting-edge technology to drive growth and ensure robust digital security.</p>
      <p>With a deep understanding of the unique challenges faced by businesses in Maadi and greater Cairo, we provide personalized solutions that address specific needs while adhering to international best practices and standards.</p>
    </section>
    
    <section id="contact" class="contact">
      <h2 class="contact-title">Contact Us</h2>
      <p>For professional IT consultations and services, reach out to us:</p>
      <p>Islam Mohammed Adel AbouShady<br>
      Founder & Lead Consultant<br>
      Main Office: 01040871120<br>
      Direct Line: 01272778532<br>
      Email: islam.aboushady@smalltech-networks.eg</p>
      <p>Office Address: 14 Road 233, Maadi, Cairo, Egypt</p>
    </section>
  </main>
  
  <footer>
    <p>&copy; 2023 SmallTech: Networking & Cybersecurity. All rights reserved.</p>
  </footer>

  <script>
    // Smooth scrolling for anchor links
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
          behavior: 'smooth'
        });
      });
    });

    // Simple animation for service cards
    const cards = document.querySelectorAll('.service-card, .tech-card');
    
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.style.opacity = '1';
          entry.target.style.transform = 'translateY(0)';
        }
      });
    }, { threshold: 0.1 });

    cards.forEach(card => {
      card.style.opacity = '0';
      card.style.transform = 'translateY(20px)';
      card.style.transition = 'opacity 0.5s ease, transform 0.5s ease';
      observer.observe(card);
    });

    // Language switch functionality
    const languageSwitch = document.querySelector('.language-switch');
    const body = document.body;
    const rtlTexts = {
      'logo-text': 'سمول تك',
      'nav-home': 'الرئيسية',
      'nav-services': 'الخدمات',
      'nav-technologies': 'التقنيات',
      'nav-about': 'عن الشركة',
      'nav-contact': 'اتصل بنا',
      'hero-title': 'سمول تك: شبكات وأمن سيبراني',
      'hero-subtitle': 'حلول تكنولوجيا المعلومات المهنية لشركات المعادي',
      'cta-button': 'احصل على استشارة',
      'about-title': 'عن سمول تك',
      'contact-title': 'اتصل بنا'
    };

    languageSwitch.addEventListener('click', () => {
      body.classList.toggle('rtl');
      if (body.classList.contains('rtl')) {
        languageSwitch.textContent = 'English';
        document.title = 'سمول تك: شبكات وأمن سيبراني | المعادي، القاهرة';
        Object.keys(rtlTexts).forEach(key => {
          const element = document.querySelector(`.${key}`);
          if (element) {
            element.textContent = rtlTexts[key];
          }
        });
        // Translate service and technology cards
        document.querySelectorAll('.service-card h3, .tech-card h3').forEach(header => {
          switch(header.textContent) {
            case 'Network Infrastructure':
              header.textContent = 'البنية التحتية للشبكات';
              break;
            case 'Cybersecurity':
              header.textContent = 'الأمن السيبراني';
              break;
            case 'Cloud Services':
              header.textContent = 'خدمات السحابة';
              break;
            case 'IT Consulting':
              header.textContent = 'استشارات تكنولوجيا المعلومات';
              break;
            case 'Networking':
              header.textContent = 'الشبكات';
              break;
            case 'Cloud Platforms':
              header.textContent = 'منصات السحابة';
              break;
            case 'Virtualization':
              header.textContent = 'الافتراضية';
              break;
            case 'Backup & Recovery':
              header.textContent = 'النسخ الاحتياطي والاستعادة';
              break;
            case 'Productivity & Collaboration':
              header.textContent = 'الإنتاجية والتعاون';
              break;
          }
        });
        // Translate footer
        document.querySelector('footer p').textContent = '© 2023 سمول تك: شبكات وأمن سيبراني. جميع الحقوق محفوظة.';
      } else {
        languageSwitch.textContent = 'عربي';
        document.title = 'SmallTech: Networking & Cybersecurity | Maadi, Cairo';
        // Reset to original English text
        document.querySelector('.logo-text').textContent = 'SmallTech';
        document.querySelector('.nav-home').textContent = 'Home';
        document.querySelector('.nav-services').textContent = 'Services';
        document.querySelector('.nav-technologies').textContent = 'Technologies';
        document.querySelector('.nav-about').textContent = 'About';
        document.querySelector('.nav-contact').textContent = 'Contact';
        document.querySelector('.hero-title').textContent = 'SmallTech: Networking & Cybersecurity';
        document.querySelector('.hero-subtitle').textContent = 'Professional IT solutions for Maadi\'s businesses';
        document.querySelector('.cta-button').textContent = 'Get a Consultation';
        document.querySelector('.about-title').textContent = 'About SmallTech';
        document.querySelector('.contact-title').textContent = 'Contact Us';
        // Reset service and technology cards
        document.querySelectorAll('.service-card h3, .tech-card h3').forEach(header => {
          switch(header.textContent) {
            case 'البنية التحتية للشبكات':
              header.textContent = 'Network Infrastructure';
              break;
            case 'الأمن السيبراني':
              header.textContent = 'Cybersecurity';
              break;
            case 'خدمات السحابة':
              header.textContent = 'Cloud Services';
              break;
            case 'استشارات تكنولوجيا المعلومات':
              header.textContent = 'IT Consulting';
              break;
            case 'الشبكات':
              header.textContent = 'Networking';
              break;
            case 'منصات السحابة':
              header.textContent = 'Cloud Platforms';
              break;
            case 'الافتراضية':
              header.textContent = 'Virtualization';
              break;
            case 'النسخ الاحتياطي والاستعادة':
              header.textContent = 'Backup & Recovery';
              break;
            case 'الإنتاجية والتعاون':
              header.textContent = 'Productivity & Collaboration';
              break;
          }
        });
        // Reset footer
        document.querySelector('footer p').textContent = '© 2023 SmallTech: Networking & Cybersecurity. All rights reserved.';
      }
    });
  </script>
</body>
</html>
