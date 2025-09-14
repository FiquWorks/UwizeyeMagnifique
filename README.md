<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Magnifique UWIZEYE - Professional Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #0d1117;
            color: #c9d1d9;
            line-height: 1.6;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        .container {
            background: linear-gradient(145deg, #161b22, #0d1117);
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.4);
            overflow: hidden;
            margin: 20px 0;
        }
        
        .gradient-banner {
            width: 100%;
            height: 120px;
            background: linear-gradient(90deg, #4facfe 0%, #00f2fe 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 30px;
        }
        
        .gradient-footer {
            width: 100%;
            height: 80px;
            background: linear-gradient(90deg, #43e97b 0%, #38f9d7 100%);
            margin-top: 30px;
            border-radius: 0 0 15px 15px;
        }
        
        .header {
            text-align: center;
            padding: 30px;
        }
        
        .header h1 {
            font-size: 3rem;
            color: #4facfe;
            margin-bottom: 10px;
            font-weight: 700;
        }
        
        .header h2 {
            font-size: 1.8rem;
            color: #00f2fe;
            margin-bottom: 20px;
            font-weight: 500;
        }
        
        .typing-animation {
            font-size: 1.5rem;
            background: linear-gradient(90deg, #43e97b, #38f9d7);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin: 20px 0;
            font-weight: 600;
        }
        
        .stats {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 20px 0;
        }
        
        .stat-item {
            background: #161b22;
            padding: 15px 25px;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        
        .section {
            padding: 30px;
            margin: 20px 0;
            background: #161b22;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        
        .section-title {
            font-size: 2rem;
            color: #4facfe;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid #4facfe;
        }
        
        .two-column {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
        }
        
        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        
        .tech-category {
            background: #21262d;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        
        .tech-category h3 {
            color: #00f2fe;
            margin-bottom: 15px;
            font-size: 1.3rem;
        }
        
        .badges {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        
        .badge {
            background: #30363d;
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            color: #c9d1d9;
            display: inline-block;
            margin: 5px;
        }
        
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin: 20px 0;
        }
        
        .project {
            background: #21262d;
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease;
        }
        
        .project:hover {
            transform: translateY(-5px);
        }
        
        .project h3 {
            color: #43e97b;
            margin-bottom: 15px;
            font-size: 1.4rem;
        }
        
        .project-features {
            margin: 15px 0;
            padding-left: 20px;
        }
        
        .project-features li {
            margin-bottom: 8px;
        }
        
        .github-stats {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin: 20px 0;
        }
        
        .stat-card {
            background: #21262d;
            padding: 20px;
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        
        .achievements {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        
        .achievement {
            background: #21262d;
            padding: 20px;
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        
        .achievement h3 {
            color: #38f9d7;
            margin-bottom: 10px;
        }
        
        .connect {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 30px 0;
        }
        
        .connect a {
            background: linear-gradient(90deg, #4facfe, #00f2fe);
            color: white;
            padding: 15px 30px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: 600;
            transition: transform 0.3s ease;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .connect a:hover {
            transform: translateY(-3px);
        }
        
        .code-block {
            background: #21262d;
            padding: 20px;
            border-radius: 15px;
            margin: 20px 0;
            overflow-x: auto;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        
        .code-block pre {
            color: #38f9d7;
            font-family: 'Fira Code', monospace;
        }
        
        .footer {
            text-align: center;
            padding: 30px;
            color: #8b949e;
        }
        
        @media (max-width: 768px) {
            .two-column {
                grid-template-columns: 1fr;
            }
            
            .github-stats {
                grid-template-columns: 1fr;
            }
            
            .header h1 {
                font-size: 2.2rem;
            }
            
            .header h2 {
                font-size: 1.4rem;
            }
            
            .connect {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="gradient-banner">
            <svg width="100%" height="120" xmlns="http://www.w3.org/2000/svg">
                <defs>
                    <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="0%">
                        <stop offset="0%" style="stop-color:#4facfe;stop-opacity:1" />
                        <stop offset="100%" style="stop-color:#00f2fe;stop-opacity:1" />
                    </linearGradient>
                </defs>
                <rect width="100%" height="120" fill="url(#grad1)" />
            </svg>
        </div>
        
        <div class="header">
            <h1>Hello, I'm Magnifique UWIZEYE</h1>
            <h2>Full-Stack Software Engineer | Problem Solver | Innovation Driver</h2>
            <div class="typing-animation">
                Full-Stack Software Engineer • Java & Spring Specialist • React & Node.js Expert
            </div>
            
            <div class="stats">
                <div class="stat-item">
                    <h3>Profile Views</h3>
                    <p>1,247</p>
                </div>
                <div class="stat-item">
                    <h3>GitHub Followers</h3>
                    <p>86</p>
                </div>
                <div class="stat-item">
                    <h3>Projects</h3>
                    <p>12</p>
                </div>
            </div>
        </div>
        
        <div class="section">
            <h2 class="section-title">Professional Overview</h2>
            <p>I'm a passionate <strong>Full-Stack Software Engineer</strong> and <strong>IT Professional</strong> dedicated to architecting scalable, secure, and innovative software solutions. With comprehensive expertise spanning both front-end and back-end technologies, I specialize in building enterprise-grade applications that solve real-world challenges and drive digital transformation.</p>
            
            <div class="two-column">
                <div>
                    <h3>🎓 Academic Excellence</h3>
                    <ul>
                        <li><strong>Information Technology Student</strong> specializing in Software Engineering & Data Analytics</li>
                        <li>Advancing expertise in cutting-edge technologies and industry best practices</li>
                        <li>Strong foundation in computer science fundamentals and software architecture</li>
                    </ul>
                </div>
                <div>
                    <h3>💼 Professional Focus</h3>
                    <ul>
                        <li>Building <strong>high-impact, scalable applications</strong> using modern frameworks</li>
                        <li>Expert in enterprise-level software architecture and database optimization</li>
                        <li>Specialized in cloud-native solutions and microservices architecture</li>
                    </ul>
                </div>
            </div>
        </div>
        
        <div class="section">
            <h2 class="section-title">Technology Mastery</h2>
            
            <div class="tech-grid">
                <div class="tech-category">
                    <h3>Programming Languages</h3>
                    <div class="badges">
                        <span class="badge">Java</span>
                        <span class="badge">Python</span>
                        <span class="badge">JavaScript</span>
                        <span class="badge">TypeScript</span>
                        <span class="badge">SQL</span>
                        <span class="badge">HTML5</span>
                        <span class="badge">CSS3</span>
                    </div>
                </div>
                
                <div class="tech-category">
                    <h3>Frontend Technologies</h3>
                    <div class="badges">
                        <span class="badge">React</span>
                        <span class="badge">Next.js</span>
                        <span class="badge">TailwindCSS</span>
                        <span class="badge">Bootstrap</span>
                    </div>
                </div>
                
                <div class="tech-category">
                    <h3>Backend Technologies</h3>
                    <div class="badges">
                        <span class="badge">Spring Boot</span>
                        <span class="badge">Node.js</span>
                        <span class="badge">Express.js</span>
                        <span class="badge">Hibernate</span>
                    </div>
                </div>
                
                <div class="tech-category">
                    <h3>Database & Analytics</h3>
                    <div class="badges">
                        <span class="badge">MySQL</span>
                        <span class="badge">PostgreSQL</span>
                        <span class="badge">MongoDB</span>
                        <span class="badge">Power BI</span>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="section">
            <h2 class="section-title">Featured Projects</h2>
            
            <div class="projects">
                <div class="project">
                    <h3>🩸 Blood Donation Management System</h3>
                    <p><strong>Enterprise-grade healthcare solution</strong> featuring distributed architecture with Java RMI, secure OTP authentication, and real-time donor management.</p>
                    
                    <h4>Key Features:</h4>
                    <ul class="project-features">
                        <li>Secure OTP-based authentication system</li>
                        <li>Real-time donor and inventory management</li>
                        <li>Automated PDF report generation</li>
                        <li>Multi-hospital network integration</li>
                        <li>Advanced analytics and reporting dashboard</li>
                    </ul>
                    
                    <div class="badges">
                        <span class="badge">Java</span>
                        <span class="badge">RMI</span>
                        <span class="badge">Hibernate</span>
                        <span class="badge">MySQL</span>
                    </div>
                </div>
                
                <div class="project">
                    <h3>📊 Business Intelligence Dashboard</h3>
                    <p><strong>Advanced analytics platform</strong> processing large datasets with interactive visualizations and predictive analytics.</p>
                    
                    <h4>Key Features:</h4>
                    <ul class="project-features">
                        <li>Real-time data processing and visualization</li>
                        <li>Predictive analytics and machine learning integration</li>
                        <li>Interactive dashboards with drill-down capabilities</li>
                        <li>Automated data pipeline and ETL processes</li>
                    </ul>
                    
                    <div class="badges">
                        <span class="badge">Python</span>
                        <span class="badge">Pandas</span>
                        <span class="badge">Power BI</span>
                        <span class="badge">SQL Server</span>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="section">
            <h2 class="section-title">GitHub Analytics & Metrics</h2>
            
            <div class="github-stats">
                <div class="stat-card">
                    <h3>Contribution Statistics</h3>
                    <p>Detailed overview of commits, contributions, and activity</p>
                </div>
                
                <div class="stat-card">
                    <h3>Top Languages</h3>
                    <p>Java, Python, JavaScript, TypeScript, SQL</p>
                </div>
            </div>
            
            <div class="stat-card">
                <h3>Contribution Streak</h3>
                <p>Consistent coding activity and project contributions</p>
            </div>
        </div>
        
        <div class="section">
            <h2 class="section-title">Professional Achievements</h2>
            
            <div class="achievements">
                <div class="achievement">
                    <h3>🚀 Projects Completed</h3>
                    <p>5+</p>
                </div>
                
                <div class="achievement">
                    <h3>💼 Years Experience</h3>
                    <p>1+</p>
                </div>
                
                <div class="achievement">
                    <h3>🛠️ Technologies Mastered</h3>
                    <p>7+</p>
                </div>
                
                <div class="achievement">
                    <h3>📊 Success Rate</h3>
                    <p>80%</p>
                </div>
            </div>
        </div>
        
        <div class="section">
            <h2 class="section-title">Connect With Me</h2>
            
            <div class="connect">
                <a href="https://www.linkedin.com/in/uwizeyemagnifiquee/">
                    <span>LinkedIn</span>
                </a>
                <a href="mailto:uwizeyemagnifique@gmail.com">
                    <span>Email</span>
                </a>
                <a href="https://github.com/FiquWorks">
                    <span>GitHub</span>
                </a>
            </div>
        </div>
        
        <div class="section">
            <h2 class="section-title">Current Focus & Learning</h2>
            
            <div class="code-block">
                <pre>
const currentlyLearning = {
    technologies: ['Kubernetes', 'GraphQL', 'TensorFlow'],
    certifications: ['AWS Solutions Architect'],
    projects: ['AI-Powered Code Review Tool'],
    goals: ['Contribute to Open Source', 'Tech Leadership', 'Mentoring']
};

const lifeMotto = "Code with purpose, build with passion, impact with innovation";
                </pre>
            </div>
        </div>
        
        <div class="footer">
            <h3>✨ "Always Learning • Always Building • Always Innovating"
