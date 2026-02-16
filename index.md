---
layout: null
---
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rushikesh Palnitkar | Data Engineer</title>
    <meta name="description" content="Data Engineer with experience building enterprise data pipelines. Hands-on with SQL, Python, Snowflake, AWS-based ETL/ELT pipelines.">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        html { scroll-behavior: smooth; }
        body { font-family: 'Inter', sans-serif; background: #fff; color: #1e293b; line-height: 1.6; }
        
        /* Navigation */
        nav { position: fixed; top: 0; left: 0; right: 0; z-index: 50; background: rgba(255,255,255,0.9); backdrop-filter: blur(10px); border-bottom: 1px solid #e2e8f0; }
        .nav-container { max-width: 100%; margin: 0 auto; padding: 0 5%; display: flex; align-items: center; justify-content: space-between; height: 64px; }
        .nav-logo { font-size: 1.25rem; font-weight: 700; color: #2563eb; text-decoration: none; }
        .nav-links { display: none; gap: 32px; }
        .nav-links a { font-size: 0.875rem; font-weight: 500; color: #64748b; text-decoration: none; transition: color 0.2s; }
        .nav-links a:hover { color: #2563eb; }
        .btn { display: inline-flex; align-items: center; gap: 8px; padding: 8px 16px; border-radius: 8px; font-size: 0.875rem; font-weight: 500; text-decoration: none; transition: all 0.2s; }
        .btn-primary { background: #2563eb; color: #fff; border: none; }
        .btn-primary:hover { background: #1d4ed8; }
        .btn-outline { border: 1px solid #e2e8f0; background: #fff; color: #1e293b; }
        .btn-outline:hover { border-color: #2563eb; color: #2563eb; }
        
        @media (min-width: 768px) { .nav-links { display: flex; } }
        
        /* Sections */
        section { padding: 80px 24px; }
        .container { max-width: 100%; margin: 0 auto; padding: 0 5%; }
        .section-title { font-size: 2rem; font-weight: 700; margin-bottom: 12px; }
        .section-bar { width: 80px; height: 4px; background: #2563eb; margin-bottom: 48px; }
        
        /* Hero */
        #home { min-height: 100vh; display: flex; align-items: center; padding-top: 64px; }
        .hero-grid { display: grid; gap: 48px; align-items: center; }
        .hero-label { color: #2563eb; font-weight: 500; margin-bottom: 16px; }
        .hero-name { font-size: 2.5rem; font-weight: 700; margin-bottom: 16px; }
        .hero-title { font-size: 1.25rem; color: #64748b; margin-bottom: 24px; }
        .hero-desc { color: #64748b; font-size: 1.125rem; margin-bottom: 32px; line-height: 1.8; }
        .hero-buttons { display: flex; flex-wrap: wrap; gap: 16px; margin-bottom: 32px; }
        .social-links { display: flex; gap: 16px; }
        .social-links a { width: 48px; height: 48px; border: 1px solid #e2e8f0; border-radius: 50%; display: flex; align-items: center; justify-content: center; color: #64748b; transition: all 0.2s; }
        .social-links a:hover { border-color: #2563eb; color: #2563eb; }
        .hero-image-container { display: flex; justify-content: center; }
        .hero-image { width: 280px; height: 280px; border-radius: 50%; object-fit: cover; object-position: top; border: 4px solid #dbeafe; box-shadow: 0 25px 50px -12px rgba(0,0,0,0.15); }
        
        @media (min-width: 1024px) { 
            .hero-grid { grid-template-columns: 1fr 1fr; }
            .hero-name { font-size: 3.5rem; }
            .hero-image { width: 380px; height: 380px; }
        }
        
        /* About */
        #about { background: #f8fafc; }
        .about-grid { display: grid; gap: 48px; }
        .about-text p { color: #64748b; margin-bottom: 16px; }
        .about-highlight { padding: 16px; background: #eff6ff; border-left: 4px solid #2563eb; border-radius: 8px; margin-top: 32px; }
        .about-highlight strong { color: #1e293b; }
        .about-highlight p { color: #64748b; font-size: 0.875rem; margin-top: 8px; margin-bottom: 0; }
        .highlight-cards { display: grid; grid-template-columns: 1fr; gap: 16px; }
        .highlight-card { background: #fff; padding: 24px; border-radius: 12px; border: 1px solid #e2e8f0; }
        .highlight-icon { width: 48px; height: 48px; background: #eff6ff; border-radius: 8px; display: flex; align-items: center; justify-content: center; margin-bottom: 16px; color: #2563eb; }
        .highlight-card h4 { font-weight: 600; margin-bottom: 8px; }
        .highlight-card p { font-size: 0.875rem; color: #64748b; }
        
        @media (min-width: 640px) { .highlight-cards { grid-template-columns: 1fr 1fr; } }
        @media (min-width: 1024px) { .about-grid { grid-template-columns: 1fr 1fr; } }
        
        /* Experience */
        .exp-card { background: #fff; border-radius: 12px; padding: 32px; border: 1px solid #e2e8f0; margin-bottom: 24px; }
        .exp-header { display: flex; flex-direction: column; gap: 16px; margin-bottom: 24px; }
        .exp-title-row { display: flex; align-items: flex-start; gap: 16px; }
        .exp-icon { width: 48px; height: 48px; background: #eff6ff; border-radius: 8px; display: flex; align-items: center; justify-content: center; color: #2563eb; flex-shrink: 0; }
        .exp-title { font-size: 1.25rem; font-weight: 600; }
        .exp-company { color: #2563eb; font-weight: 500; }
        .exp-meta { font-size: 0.875rem; color: #64748b; }
        .exp-list { list-style: none; margin-bottom: 24px; }
        .exp-list li { display: flex; gap: 12px; color: #64748b; margin-bottom: 12px; }
        .exp-list li::before { content: ''; width: 6px; height: 6px; background: #2563eb; border-radius: 50%; margin-top: 8px; flex-shrink: 0; }
        .tags { display: flex; flex-wrap: wrap; gap: 8px; }
        .tag { padding: 4px 12px; background: #eff6ff; color: #2563eb; font-size: 0.75rem; font-weight: 500; border-radius: 9999px; }
        
        @media (min-width: 640px) { .exp-header { flex-direction: row; justify-content: space-between; align-items: flex-start; } }
        
        /* Projects */
        #projects { background: #f8fafc; }
        .project-card { background: #fff; border-radius: 12px; padding: 32px; border: 1px solid #e2e8f0; margin-bottom: 24px; }
        .project-header { display: flex; gap: 16px; margin-bottom: 24px; }
        .project-icon { width: 56px; height: 56px; border-radius: 12px; display: flex; align-items: center; justify-content: center; color: #fff; flex-shrink: 0; }
        .project-icon.orange { background: linear-gradient(135deg, #f97316, #ef4444); }
        .project-icon.blue { background: linear-gradient(135deg, #3b82f6, #06b6d4); }
        .project-icon.green { background: linear-gradient(135deg, #22c55e, #10b981); }
        .project-title { font-size: 1.25rem; font-weight: 600; margin-bottom: 8px; }
        .project-goal { color: #64748b; }
        .project-goal strong { color: #475569; }
        .project-section h4 { font-weight: 600; margin-bottom: 12px; }
        .project-section { margin-bottom: 24px; }
        .project-impact { padding: 16px; background: #f0fdf4; border-left: 4px solid #22c55e; border-radius: 8px; color: #166534; }
        .project-impact strong { font-weight: 600; }
        .tag-outline { padding: 4px 12px; border: 1px solid #e2e8f0; color: #64748b; font-size: 0.75rem; border-radius: 9999px; }
        
        /* Skills */
        .skills-grid { display: grid; gap: 24px; }
        .skill-card { background: #f8fafc; padding: 24px; border-radius: 12px; border: 1px solid #e2e8f0; }
        .skill-header { display: flex; align-items: center; gap: 12px; margin-bottom: 16px; }
        .skill-icon { width: 40px; height: 40px; border-radius: 8px; display: flex; align-items: center; justify-content: center; color: #fff; }
        .skill-icon.purple { background: #a855f7; }
        .skill-icon.blue { background: #3b82f6; }
        .skill-icon.green { background: #22c55e; }
        .skill-icon.orange { background: #f97316; }
        .skill-icon.cyan { background: #06b6d4; }
        .skill-icon.rose { background: #f43f5e; }
        .skill-icon.indigo { background: #6366f1; }
        .skill-card h3 { font-weight: 600; }
        .skill-tags { display: flex; flex-wrap: wrap; gap: 8px; }
        .skill-tag { padding: 6px 12px; background: #fff; border: 1px solid #e2e8f0; color: #475569; font-size: 0.875rem; border-radius: 9999px; }
        
        @media (min-width: 640px) { .skills-grid { grid-template-columns: repeat(2, 1fr); } }
        @media (min-width: 1024px) { .skills-grid { grid-template-columns: repeat(3, 1fr); } }
        
        /* Contact */
        #contact { background: #f8fafc; }
        .contact-grid { display: grid; gap: 48px; }
        .contact-info h3 { font-size: 1.25rem; font-weight: 600; margin-bottom: 24px; }
        .contact-item { display: flex; align-items: center; gap: 16px; margin-bottom: 24px; }
        .contact-icon { width: 48px; height: 48px; background: #eff6ff; border-radius: 8px; display: flex; align-items: center; justify-content: center; color: #2563eb; }
        .contact-label { font-size: 0.875rem; color: #64748b; }
        .contact-value { font-weight: 500; color: #1e293b; }
        .contact-value a { color: inherit; text-decoration: none; }
        .contact-value a:hover { color: #2563eb; }
        .connect-title { font-size: 1.125rem; font-weight: 600; margin: 32px 0 16px; }
        .connect-links { display: flex; gap: 16px; }
        .connect-links a { width: 48px; height: 48px; background: #e2e8f0; border-radius: 8px; display: flex; align-items: center; justify-content: center; color: #64748b; transition: all 0.2s; }
        .connect-links a:hover { color: #fff; }
        .connect-links a.linkedin:hover { background: #2563eb; }
        .connect-links a.github:hover { background: #1e293b; }
        .connect-links a.email:hover { background: #ef4444; }
        .cta-card { background: linear-gradient(135deg, #2563eb, #1d4ed8); border-radius: 16px; padding: 32px; color: #fff; }
        .cta-card h3 { font-size: 1.5rem; font-weight: 700; margin-bottom: 16px; }
        .cta-card p { color: #bfdbfe; margin-bottom: 24px; line-height: 1.8; }
        .cta-buttons { display: flex; flex-direction: column; gap: 12px; }
        .btn-white { background: #fff; color: #2563eb; border: none; width: 100%; justify-content: center; padding: 12px 24px; }
        .btn-white:hover { background: #eff6ff; }
        .btn-ghost { background: transparent; border: 1px solid #fff; color: #fff; width: 100%; justify-content: center; padding: 12px 24px; }
        .btn-ghost:hover { background: rgba(255,255,255,0.1); }
        
        @media (min-width: 768px) { .contact-grid { grid-template-columns: 1fr 1fr; } }
        
        /* Footer */
        footer { padding: 32px 24px; background: #fff; border-top: 1px solid #e2e8f0; text-align: center; color: #64748b; }
        
        /* SVG Icons */
        .icon { width: 20px; height: 20px; }
        .icon-lg { width: 28px; height: 28px; }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav>
        <div class="nav-container">
            <a href="#home" class="nav-logo">Rushikesh</a>
            <div class="nav-links">
                <a href="#home">Home</a>
                <a href="#about">About</a>
                <a href="#experience">Experience</a>
                <a href="#projects">Projects</a>
                <a href="#skills">Skills</a>
                <a href="#contact">Contact</a>
            </div>
            <a href="https://qtrypzzcjebvfcihiynt.supabase.co/storage/v1/object/public/base44-prod/public/6989435e0824366d47ee3f6b/6141c6d19_RUSHIKESH-PALNITKAR-RESUME.pdf" target="_blank" class="btn btn-outline">
                <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path></svg>
                Resume
            </a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home">
        <div class="container">
            <div class="hero-grid">
                <div>
                    <p class="hero-label">Hello, I'm</p>
                    <h1 class="hero-name">Rushikesh Palnitkar</h1>
                    <h2 class="hero-title">Data Engineer | AWS, Snowflake, Event-Driven ETL</h2>
                    <p class="hero-desc">I build cloud-native data platforms and ETL pipelines on AWS that turn raw, high-volume data into reliable, analytics-ready datasets — cutting processing time from hours to minutes.</p>
                    <div class="hero-buttons">
                        <a href="#contact" class="btn btn-primary">Get in Touch</a>
                        <a href="#projects" class="btn btn-outline">View My Work</a>
                    </div>
                    <div class="social-links">
                        <a href="https://www.linkedin.com/in/rushikesh-palnitkar/" target="_blank" aria-label="LinkedIn">
                            <svg class="icon" fill="currentColor" viewBox="0 0 24 24"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
                        </a>
                        <a href="https://github.com/rushikesh2842" target="_blank" aria-label="GitHub">
                            <svg class="icon" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/></svg>
                        </a>
                        <a href="mailto:rushi142019@gmail.com" aria-label="Email">
                            <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                        </a>
                    </div>
                </div>
                <div class="hero-image-container">
                    <img src="https://qtrypzzcjebvfcihiynt.supabase.co/storage/v1/object/public/base44-prod/public/6989435e0824366d47ee3f6b/de0111c76_Gemini_Generated_Image_kziee5kziee5kzie1.png" alt="Rushikesh Palnitkar" class="hero-image">
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <div class="container">
            <h2 class="section-title">About Me</h2>
            <div class="section-bar"></div>
            <div class="about-grid">
                <div class="about-text">
                    <h3 style="font-size: 1.5rem; font-weight: 600; margin-bottom: 24px;">My Journey</h3>
                    <p>I'm a Data Engineer with experience building enterprise data pipelines that ingest, transform, and deliver data for analytics and reporting. Currently pursuing my MS in Computer Science at The University of Texas at Arlington with a GPA of 3.78.</p>
                    <p>My expertise lies in designing and building batch and event-driven ETL pipelines on AWS, architecting data lakes and warehouses using Delta Lake medallion patterns and Snowflake for low-latency analytics.</p>
                    <p>I'm passionate about automating infrastructure and deployments with Terraform and CI/CD (GitHub Actions) to keep systems reliable and easy to evolve, while enabling stakeholders with clean, queryable datasets and dashboards.</p>
                    <div class="about-highlight">
                        <strong>Currently:</strong> MS in Computer Science at UT Arlington (Aug 2024 - May 2026)
                        <p>Coursework: Database Systems, Cloud Computing & Big Data, Data Analysis & Modelling, Data Mining, Machine Learning</p>
                    </div>
                </div>
                <div class="highlight-cards">
                    <div class="highlight-card">
                        <div class="highlight-icon">
                            <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 7v10c0 2.21 3.582 4 8 4s8-1.79 8-4V7M4 7c0 2.21 3.582 4 8 4s8-1.79 8-4M4 7c0-2.21 3.582-4 8-4s8 1.79 8 4"></path></svg>
                        </div>
                        <h4>Data Engineering</h4>
                        <p>ETL/ELT pipelines, Data Lakes, Medallion architecture, Data Warehousing</p>
                    </div>
                    <div class="highlight-card">
                        <div class="highlight-icon">
                            <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 15a4 4 0 004 4h9a5 5 0 10-.1-9.999 5.002 5.002 0 10-9.78 2.096A4.001 4.001 0 003 15z"></path></svg>
                        </div>
                        <h4>Cloud & Infrastructure</h4>
                        <p>AWS (Lambda, Step Functions, Glue, EMR, Redshift, S3), Terraform, CI/CD</p>
                    </div>
                    <div class="highlight-card">
                        <div class="highlight-icon">
                            <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"></path></svg>
                        </div>
                        <h4>Programming</h4>
                        <p>Python, SQL, Bash, PowerShell, PySpark</p>
                    </div>
                    <div class="highlight-card">
                        <div class="highlight-icon">
                            <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"></path></svg>
                        </div>
                        <h4>Analytics & Visualization</h4>
                        <p>Snowflake, Power BI, Grafana, QuickSight</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section id="experience">
        <div class="container">
            <h2 class="section-title">Experience</h2>
            <div class="section-bar"></div>
            
            <div class="exp-card">
                <div class="exp-header">
                    <div class="exp-title-row">
                        <div class="exp-icon">
                            <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                        </div>
                        <div>
                            <h3 class="exp-title">Data Engineer Intern</h3>
                            <p class="exp-company">Axisray</p>
                        </div>
                    </div>
                    <div class="exp-meta">
                        <p>Sept 2023 – June 2024</p>
                        <p>Ahmedabad, Gujarat, India</p>
                    </div>
                </div>
                <ul class="exp-list">
                    <li>Led the development and maintenance of ETL/ELT data pipelines from disparate sources (RDS, third party APIs, flat files on S3), processing 5M+ records daily for analytics and reporting</li>
                    <li>Integrated Snowflake as the enterprise data warehouse and Delta Lake medallion layers on S3, reducing time series query latency by 40%</li>
                    <li>Implemented data quality checks and validations (null checks, referential integrity, reconciliation queries), reducing data inconsistencies by 20%</li>
                    <li>Reduced end-to-end daily load time from 1-2 hours to under 15 minutes via automated Bash scripts</li>
                    <li>Assisted with building and maintaining dimensional data models in Snowflake, including fact and dimension tables</li>
                    <li>Maintained 99%+ uptime and high data quality using Grafana dashboards for real-time monitoring</li>
                    <li>Built dynamic, real-time dashboards in Power BI with intuitive visualizations</li>
                    <li>Automated infrastructure provisioning and deployments on AWS using Terraform and GitHub Actions CI/CD pipelines, reducing recovery time by 50%</li>
                </ul>
                <div class="tags">
                    <span class="tag">Snowflake</span>
                    <span class="tag">AWS</span>
                    <span class="tag">Python</span>
                    <span class="tag">SQL</span>
                    <span class="tag">Delta Lake</span>
                    <span class="tag">Terraform</span>
                    <span class="tag">Power BI</span>
                    <span class="tag">Grafana</span>
                    <span class="tag">GitHub Actions</span>
                </div>
            </div>
            
            <div class="exp-card">
                <div class="exp-header">
                    <div class="exp-title-row">
                        <div class="exp-icon">
                            <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                        </div>
                        <div>
                            <h3 class="exp-title">ML Intern</h3>
                            <p class="exp-company">BISAG-N</p>
                        </div>
                    </div>
                    <div class="exp-meta">
                        <p>Jan 2023 – May 2023</p>
                        <p>Gandhinagar, India</p>
                    </div>
                </div>
                <ul class="exp-list">
                    <li>Used Python, TensorFlow and PyTorch to build a sound classification pipeline, improving model accuracy from 70% to 91%</li>
                    <li>Implemented data preprocessing, feature extraction (Mel spectrograms, MFCCs), and data ingestion workflows for large audio datasets</li>
                    <li>Ran experiments across local and cloud GPU environments, optimizing training time and documenting results</li>
                </ul>
                <div class="tags">
                    <span class="tag">Python</span>
                    <span class="tag">TensorFlow</span>
                    <span class="tag">PyTorch</span>
                    <span class="tag">Mel Spectrograms</span>
                    <span class="tag">MFCCs</span>
                    <span class="tag">GPU Computing</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <div class="container">
            <h2 class="section-title">Featured Projects</h2>
            <div class="section-bar"></div>
            
            <div class="project-card">
                <div class="project-header">
                    <div class="project-icon orange">
                        <svg class="icon-lg" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                    </div>
                    <div>
                        <h3 class="project-title">Serverless Time-Series Extraction</h3>
                        <p class="project-goal"><strong>Goal:</strong> Turn 100 GB of multidimensional satellite weather data (netCDF) into queryable time-series datasets per location.</p>
                    </div>
                </div>
                <div class="project-section">
                    <h4>Solution:</h4>
                    <ul class="exp-list">
                        <li>Orchestrated 365 concurrent AWS Lambda functions via Step Functions, each processing a day of data</li>
                        <li>Containerized Lambdas with netCDF4 and Pandas to parse netCDF and write Parquet to S3</li>
                        <li>Used AWS Glue to consolidate daily files and re-partition by geographical point ID</li>
                    </ul>
                </div>
                <div class="project-impact">
                    <strong>Impact:</strong> Reduced processing time from 7 hours to ~2 minutes while staying fully serverless and scalable.
                </div>
                <div class="tags" style="margin-top: 24px;">
                    <span class="tag-outline">AWS S3</span>
                    <span class="tag-outline">AWS Lambda</span>
                    <span class="tag-outline">Step Functions</span>
                    <span class="tag-outline">AWS Glue</span>
                    <span class="tag-outline">AWS ECR</span>
                    <span class="tag-outline">Docker</span>
                    <span class="tag-outline">Python</span>
                    <span class="tag-outline">Pandas</span>
                </div>
            </div>
            
            <div class="project-card">
                <div class="project-header">
                    <div class="project-icon blue">
                        <svg class="icon-lg" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 12h14M5 12a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v4a2 2 0 01-2 2M5 12a2 2 0 00-2 2v4a2 2 0 002 2h14a2 2 0 002-2v-4a2 2 0 00-2-2m-2-4h.01M17 16h.01"></path></svg>
                    </div>
                    <div>
                        <h3 class="project-title">Event-Driven ETL Pipeline</h3>
                        <p class="project-goal"><strong>Goal:</strong> Build an event-driven pipeline with a 20-minute end-to-end SLA for analytics-ready data.</p>
                    </div>
                </div>
                <div class="project-section">
                    <h4>Solution:</h4>
                    <ul class="exp-list">
                        <li>Configured EventBridge to trigger Step Functions state machine on each S3 object creation</li>
                        <li>Orchestrated Lambda and PySpark jobs on EMR for aggregations and Redshift manifest files</li>
                        <li>Used Redshift stored procedures for automated upserts from staging to core tables</li>
                        <li>Built partitioned S3 Data Lake optimized for data scientists</li>
                    </ul>
                </div>
                <div class="project-impact">
                    <strong>Impact:</strong> Achieved 20-minute refresh SLA and reduced data scientists' preprocessing time by 50%.
                </div>
                <div class="tags" style="margin-top: 24px;">
                    <span class="tag-outline">AWS CDK</span>
                    <span class="tag-outline">S3</span>
                    <span class="tag-outline">EventBridge</span>
                    <span class="tag-outline">Step Functions</span>
                    <span class="tag-outline">Lambda</span>
                    <span class="tag-outline">EMR</span>
                    <span class="tag-outline">Athena</span>
                    <span class="tag-outline">Glue</span>
                    <span class="tag-outline">PySpark</span>
                    <span class="tag-outline">Redshift</span>
                    <span class="tag-outline">SNS</span>
                </div>
            </div>
            
            <div class="project-card">
                <div class="project-header">
                    <div class="project-icon green">
                        <svg class="icon-lg" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"></path></svg>
                    </div>
                    <div>
                        <h3 class="project-title">Microservices E-commerce Platform</h3>
                        <p class="project-goal"><strong>Goal:</strong> Deploy a microservices-based ecommerce application with scalable, automated infrastructure.</p>
                    </div>
                </div>
                <div class="project-section">
                    <h4>Solution:</h4>
                    <ul class="exp-list">
                        <li>Containerized 22 microservices with Docker and orchestrated using Kubernetes on AWS EC2</li>
                        <li>Automated infrastructure with Terraform and CI/CD with GitHub Actions</li>
                        <li>Implemented rolling updates and zero-downtime deployments</li>
                    </ul>
                </div>
                <div class="project-impact">
                    <strong>Impact:</strong> Reduced time to deploy infrastructure by 85% and shortened release cycle time by 35%.
                </div>
                <div class="tags" style="margin-top: 24px;">
                    <span class="tag-outline">AWS EC2</span>
                    <span class="tag-outline">Docker</span>
                    <span class="tag-outline">Kubernetes</span>
                    <span class="tag-outline">Terraform</span>
                    <span class="tag-outline">GitHub Actions</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <div class="container">
            <h2 class="section-title">Skills & Technologies</h2>
            <div class="section-bar"></div>
            <div class="skills-grid">
                <div class="skill-card">
                    <div class="skill-header">
                        <div class="skill-icon purple">
                            <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"></path></svg>
                        </div>
                        <h3>Programming & Scripting</h3>
                    </div>
                    <div class="skill-tags">
                        <span class="skill-tag">SQL</span>
                        <span class="skill-tag">Python</span>
                        <span class="skill-tag">Bash</span>
                        <span class="skill-tag">PowerShell</span>
                        <span class="skill-tag">PySpark</span>
                    </div>
                </div>
                <div class="skill-card">
                    <div class="skill-header">
                        <div class="skill-icon blue">
                            <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 7v10c0 2.21 3.582 4 8 4s8-1.79 8-4V7M4 7c0 2.21 3.582 4 8 4s8-1.79 8-4M4 7c0-2.21 3.582-4 8-4s8 1.79 8 4"></path></svg>
                        </div>
                        <h3>Data Engineering</h3>
                    </div>
                    <div class="skill-tags">
                        <span class="skill-tag">ETL/ELT</span>
                        <span class="skill-tag">Data Pipelines</span>
                        <span class="skill-tag">Data Quality</span>
                        <span class="skill-tag">Dimensional Modeling</span>
                        <span class="skill-tag">Star Schema</span>
                    </div>
                </div>
                <div class="skill-card">
                    <div class="skill-header">
                        <div class="skill-icon green">
                            <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 7v10c0 2.21 3.582 4 8 4s8-1.79 8-4V7M4 7c0 2.21 3.582 4 8 4s8-1.79 8-4M4 7c0-2.21 3.582-4 8-4s8 1.79 8 4"></path></svg>
                        </div>
                        <h3>Databases</h3>
                    </div>
                    <div class="skill-tags">
                        <span class="skill-tag">Snowflake</span>
                        <span class="skill-tag">Redshift</span>
                        <span class="skill-tag">MySQL</span>
                        <span class="skill-tag">PostgreSQL</span>
                        <span class="skill-tag">MongoDB</span>
                        <span class="skill-tag">DynamoDB</span>
                    </div>
                </div>
                <div class="skill-card">
                    <div class="skill-header">
                        <div class="skill-icon orange">
                            <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 15a4 4 0 004 4h9a5 5 0 10-.1-9.999 5.002 5.002 0 10-9.78 2.096A4.001 4.001 0 003 15z"></path></svg>
                        </div>
                        <h3>Cloud (AWS)</h3>
                    </div>
                    <div class="skill-tags">
                        <span class="skill-tag">S3</span>
                        <span class="skill-tag">Lambda</span>
                        <span class="skill-tag">Glue</span>
                        <span class="skill-tag">EMR</span>
                        <span class="skill-tag">Athena</span>
                        <span class="skill-tag">Step Functions</span>
                        <span class="skill-tag">EventBridge</span>
                    </div>
                </div>
                <div class="skill-card">
                    <div class="skill-header">
                        <div class="skill-icon cyan">
                            <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20 7l-8-4-8 4m16 0l-8 4m8-4v10l-8 4m0-10L4 7m8 4v10M4 7v10l8 4"></path></svg>
                        </div>
                        <h3>Containerization</h3>
                    </div>
                    <div class="skill-tags">
                        <span class="skill-tag">Docker</span>
                        <span class="skill-tag">Kubernetes</span>
                        <span class="skill-tag">AWS ECR</span>
                        <span class="skill-tag">GCR</span>
                        <span class="skill-tag">ACR</span>
                    </div>
                </div>
                <div class="skill-card">
                    <div class="skill-header">
                        <div class="skill-icon rose">
                            <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 9l3 3-3 3m5 0h3M5 20h14a2 2 0 002-2V6a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"></path></svg>
                        </div>
                        <h3>DevOps & Tools</h3>
                    </div>
                    <div class="skill-tags">
                        <span class="skill-tag">Git</span>
                        <span class="skill-tag">GitHub Actions</span>
                        <span class="skill-tag">Terraform</span>
                        <span class="skill-tag">CI/CD</span>
                    </div>
                </div>
                <div class="skill-card">
                    <div class="skill-header">
                        <div class="skill-icon indigo">
                            <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"></path></svg>
                        </div>
                        <h3>Data Visualization</h3>
                    </div>
                    <div class="skill-tags">
                        <span class="skill-tag">Grafana</span>
                        <span class="skill-tag">Power BI</span>
                        <span class="skill-tag">Power Query</span>
                        <span class="skill-tag">QuickSight</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2 class="section-title" style="text-align: center;">Get In Touch</h2>
            <div class="section-bar" style="margin: 0 auto 24px;"></div>
            <p style="text-align: center; color: #64748b; max-width: 600px; margin: 0 auto 48px;">I'm currently open to internships and data engineer roles. Feel free to reach out if you'd like to discuss opportunities or just want to connect!</p>
            
            <div class="contact-grid">
                <div class="contact-info">
                    <h3>Contact Information</h3>
                    <div class="contact-item">
                        <div class="contact-icon">
                            <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                        </div>
                        <div>
                            <p class="contact-label">Email</p>
                            <p class="contact-value"><a href="mailto:rushi142019@gmail.com">rushi142019@gmail.com</a></p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon">
                            <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path></svg>
                        </div>
                        <div>
                            <p class="contact-label">Phone</p>
                            <p class="contact-value"><a href="tel:+16823405836">+1 (682) 340-5836</a></p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon">
                            <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
                        </div>
                        <div>
                            <p class="contact-label">Location</p>
                            <p class="contact-value">Dallas-Fort Worth, TX</p>
                        </div>
                    </div>
                    <h4 class="connect-title">Connect With Me</h4>
                    <div class="connect-links">
                        <a href="https://www.linkedin.com/in/rushikesh-palnitkar/" target="_blank" class="linkedin" aria-label="LinkedIn">
                            <svg class="icon" fill="currentColor" viewBox="0 0 24 24"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
                        </a>
                        <a href="https://github.com/rushikesh2842" target="_blank" class="github" aria-label="GitHub">
                            <svg class="icon" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/></svg>
                        </a>
                        <a href="mailto:rushi142019@gmail.com" class="email" aria-label="Email">
                            <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                        </a>
                    </div>
                </div>
                <div class="cta-card">
                    <h3>Let's Work Together</h3>
                    <p>I'm passionate about building scalable data solutions and would love to contribute to impactful projects. Whether you have a question or just want to say hi, I'll do my best to get back to you!</p>
                    <div class="cta-buttons">
                        <a href="mailto:rushi142019@gmail.com" class="btn btn-white">
                            <svg class="icon" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 19l9 2-9-18-9 18 9-2zm0 0v-8"></path></svg>
                            Send Me an Email
                        </a>
                        <a href="https://qtrypzzcjebvfcihiynt.supabase.co/storage/v1/object/public/base44-prod/public/6989435e0824366d47ee3f6b/6141c6d19_RUSHIKESH-PALNITKAR-RESUME.pdf" target="_blank" class="btn btn-ghost">Download Resume</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2024 Rushikesh Palnitkar. Built with passion.</p>
    </footer>
</body>
</html>
