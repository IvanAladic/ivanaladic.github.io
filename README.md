<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ivan Aladic | Cybersecurity Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <div class="container">
        <aside class="sidebar">
            <div class="profile-section">
                <div class="profile-img-container">
                    <img src="profile.jpg" alt="Ivan Aladic" class="profile-img">
                </div>
                [cite_start]<h1 class="name">Ivan Aladic [cite: 9]</h1>
                [cite_start]<p class="tagline">Cybersecurity Analyst [cite: 10]</p>
                
                <div class="social-icons">
                    <a href="https://linkedin.com/in/ivanaladic" target="_blank"><i class="fab fa-linkedin"></i></a>
                    <a href="mailto:aladicivan2@gmail.com"><i class="fas fa-envelope"></i></a>
                    <a href="#"><i class="fab fa-github"></i></a>
                </div>
            </div>

            <nav class="nav-menu">
                <ul>
                    <li><a href="#about">About Me</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#experience">Experience</a></li>
                    <li><a href="#education">Education</a></li>
                </ul>
            </nav>

            <div class="sidebar-buttons">
                <a href="#" class="btn btn-primary">Download CV</a>
                <a href="#contact" class="btn btn-secondary">Contact Me</a>
            </div>
        </aside>

        <main class="content">
            <section id="about" class="section">
                <h2 class="section-header">About Me</h2>
                <p class="bio">
                    [cite_start]Dedicated and proactive Cybersecurity Junior with 6+ years of professional experience in highly regulated environments[cite: 11]. 
                    [cite_start]Currently specializing in digital forensics, threat hunting, and incident response[cite: 12]. 
                    [cite_start]Building job-ready skills through hands-on labs and real-world simulation platforms[cite: 13].
                </p>
                <div class="quick-stats">
                    [cite_start]<div class="stat-card"><h3>6+</h3><p>Years Exp [cite: 11]</p></div>
                    [cite_start]<div class="stat-card"><h3>30+</h3><p>SOC Labs [cite: 32]</p></div>
                    [cite_start]<div class="stat-card"><h3>C1</h3><p>English [cite: 25]</p></div>
                </div>
            </section>

            <section id="skills" class="section">
                <h2 class="section-header">Technical Skills</h2>
                <div class="skills-grid">
                    <div class="skill-group">
                        [cite_start]<p>Security Tools (Splunk, Wireshark, Nmap) [cite: 6]</p>
                        <div class="progress-bar"><div class="progress" style="width: 90%;"></div></div>
                    </div>
                    <div class="skill-group">
                        [cite_start]<p>Operating Systems (Linux, Bash, PowerShell) [cite: 6]</p>
                        <div class="progress-bar"><div class="progress" style="width: 85%;"></div></div>
                    </div>
                    <div class="skill-group">
                        <p>C / C++ & Shell (Piscine 42)</p>
                        <div class="progress-bar"><div class="progress" style="width: 80%;"></div></div>
                    </div>
                    <div class="skill-group">
                        [cite_start]<p>Network Security (TCP/IP, Firewalls) [cite: 6]</p>
                        <div class="progress-bar"><div class="progress" style="width: 75%;"></div></div>
                    </div>
                </div>
            </section>

            <section id="experience" class="section">
                <h2 class="section-header">Experience</h2>
                
                <div class="timeline">
                    <div class="timeline-item">
                        [cite_start]<span class="date">2024 - 2025 [cite: 30]</span>
                        [cite_start]<h3>Cybersecurity Analyst SOC 1 [cite: 28]</h3>
                        [cite_start]<p class="location">TryHackMe [cite: 29]</p>
                        <ul>
                            [cite_start]<li>Managed simulated SOC environments, completing 30+ defensive security paths[cite: 32].</li>
                            [cite_start]<li>Analyzed network traffic using Splunk and Wireshark to identify malware and C2 activity[cite: 33].</li>
                            [cite_start]<li>Executed containment protocols and conducted threat assessments using Nmap[cite: 34, 35].</li>
                        </ul>
                    </div>

                    <div class="timeline-item">
                        <span class="date">Special Project</span>
                        <h3>Piscine 42 Madrid</h3>
                        <p class="location">42 Madrid</p>
                        <ul>
                            <li>Intensive month-long deep dive into C and Shell programming.</li>
                            <li>Built custom shell functions and handled memory management projects.</li>
                            <li>Collaborative peer-to-peer problem solving in a high-pressure environment.</li>
                        </ul>
                    </div>

                    <div class="timeline-item">
                        [cite_start]<span class="date">2018 - 2024 [cite: 38]</span>
                        [cite_start]<h3>Contract Manager [cite: 36]</h3>
                        [cite_start]<p class="location">UHG Galway, Ireland [cite: 36]</p>
                        <ul>
                            [cite_start]<li>Enforced corporate compliance and security policies for 200+ staff[cite: 39].</li>
                            [cite_start]<li>Managed confidential records with high integrity and attention to detail[cite: 39].</li>
                        </ul>
                    </div>
                </div>
            </section>

            <section id="education" class="section">
                <h2 class="section-header">Education & Certs</h2>
                <div class="edu-grid">
                    <div class="edu-item">
                        [cite_start]<strong>SOC1 Certification [cite: 17]</strong>
                        [cite_start]<p>TryHackMe, 2025 [cite: 18, 19]</p>
                    </div>
                    <div class="edu-item">
                        [cite_start]<strong>Front-End Developer [cite: 20]</strong>
                        [cite_start]<p>Code Institute, 2022-2024 [cite: 21, 22]</p>
                    </div>
                </div>
            </section>
        </main>
    </div>
</body>
</html>
/* Color Palette: Deep Blue & Cyber Cyan */
:root {
    --bg-main: #0a192f;        /* Deep Navy */
    --bg-sidebar: #112240;     /* Lighter Navy */
    --accent: #64ffda;         /* Cyber Cyan/Mint */
    --text-bright: #e6f1ff;    /* Off-white */
    --text-dim: #8892b0;       /* Muted Blue-Grey */
    --card-bg: #1d2d50;        /* Deep Blue Card */
}

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: 'Inter', 'Segoe UI', sans-serif;
    background-color: var(--bg-main);
    color: var(--text-dim);
    line-height: 1.6;
}

.container {
    display: flex;
}

/* Sidebar */
.sidebar {
    width: 350px;
    height: 100vh;
    background-color: var(--bg-sidebar);
    position: fixed;
    display: flex;
    flex-direction: column;
    padding: 40px;
    text-align: center;
    border-right: 1px solid #233554;
}

.profile-img-container {
    width: 150px;
    height: 150px;
    margin: 0 auto 20px;
    border: 3px solid var(--accent);
    border-radius: 10px;
    overflow: hidden;
}

.profile-img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.name { color: var(--text-bright); font-size: 1.8rem; margin-bottom: 5px; }
.tagline { color: var(--accent); font-weight: 600; font-size: 0.9rem; text-transform: uppercase; letter-spacing: 1px; }

.social-icons { margin: 25px 0; }
.social-icons a { color: var(--text-bright); font-size: 1.5rem; margin: 0 10px; transition: 0.3s; }
.social-icons a:hover { color: var(--accent); }

.nav-menu ul { list-style: none; margin-top: 30px; }
.nav-menu li { margin: 15px 0; }
.nav-menu a { color: var(--text-dim); text-decoration: none; font-weight: 500; transition: 0.3s; }
.nav-menu a:hover { color: var(--accent); padding-left: 10px; }

.sidebar-buttons { margin-top: auto; }
.btn {
    display: block;
    padding: 12px;
    margin: 10px 0;
    text-decoration: none;
    border-radius: 5px;
    font-weight: 600;
    transition: 0.3s;
}
.btn-primary { background-color: var(--accent); color: var(--bg-main); }
.btn-secondary { border: 1px solid var(--accent); color: var(--accent); }
.btn-secondary:hover { background: rgba(100, 255, 218, 0.1); }

/* Main Content */
.content {
    margin-left: 350px;
    padding: 80px 10%;
    width: calc(100% - 350px);
}

.section { margin-bottom: 80px; }
.section-header {
    color: var(--text-bright);
    font-size: 2rem;
    margin-bottom: 30px;
    position: relative;
}
.section-header::after {
    content: "";
    display: block;
    width: 60px;
    height: 3px;
    background: var(--accent);
    margin-top: 10px;
}

.bio { font-size: 1.1rem; color: var(--text-bright); }

.quick-stats {
    display: flex;
    gap: 20px;
    margin-top: 30px;
}

.stat-card {
    background: var(--card-bg);
    padding: 20px;
    border-radius: 8px;
    flex: 1;
    text-align: center;
}
.stat-card h3 { color: var(--accent); font-size: 1.8rem; }

/* Skills Progress Bars */
.skills-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 30px; }
.skill-group p { color: var(--text-bright); margin-bottom: 8px; font-size: 0.9rem; }
.progress-bar { background: #233554; height: 8px; border-radius: 10px; }
.progress { background: var(--accent); height: 100%; border-radius: 10px; box-shadow: 0 0 10px var(--accent); }

/* Timeline */
.timeline { border-left: 2px solid #233554; padding-left: 30px; }
.timeline-item { position: relative; margin-bottom: 40px; }
.timeline-item::before {
    content: "";
    position: absolute;
    left: -39px;
    top: 5px;
    width: 15px;
    height: 15px;
    background: var(--accent);
    border-radius: 50%;
}
.timeline-item h3 { color: var(--text-bright); }
.timeline-item .date { color: var(--accent); font-weight: bold; font-size: 0.8rem; }
.timeline-item ul { margin-top: 10px; padding-left: 20px; }

/* Responsive */
@media (max-width: 900px) {
    .container { flex-direction: column; }
    .sidebar { width: 100%; height: auto; position: relative; }
    .content { margin-left: 0; width: 100%; padding: 40px 20px; }
}-
