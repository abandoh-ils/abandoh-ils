<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Joseph Ahor Abandoh-Sam - Backend Engineer & Problem Solver</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc; /* Lightest gray */
            color: #334155; /* Slate 700 */
            line-height: 1.6;
        }
        .container {
            max-width: 960px;
            margin: 2rem auto;
            padding: 2rem;
            background-color: #ffffff;
            border-radius: 1rem;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
        }
        h1, h2, h3 {
            font-weight: 700;
            color: #1e293b; /* Slate 900 */
        }
        h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        h2 {
            font-size: 2rem;
            border-bottom: 2px solid #e2e8f0; /* Gray 200 */
            padding-bottom: 0.5rem;
            margin-bottom: 1.5rem;
        }
        h3 {
            font-size: 1.5rem;
            margin-top: 1.5rem;
            margin-bottom: 1rem;
        }
        .section-content {
            margin-bottom: 2rem;
        }
        .tag {
            display: inline-block;
            background-color: #e0e7ff; /* Indigo 100 */
            color: #4338ca; /* Indigo 700 */
            padding: 0.3rem 0.8rem;
            border-radius: 0.5rem;
            font-size: 0.85rem;
            font-weight: 600;
            margin-right: 0.5rem;
            margin-bottom: 0.5rem;
        }
        .icon {
            display: inline-block;
            vertical-align: middle;
            margin-right: 0.5rem;
            width: 20px;
            height: 20px;
        }
        .link-button {
            display: inline-flex;
            align-items: center;
            background-color: #4f46e5; /* Indigo 600 */
            color: white;
            padding: 0.6rem 1.2rem;
            border-radius: 0.75rem;
            text-decoration: none;
            font-weight: 600;
            transition: background-color 0.3s ease;
        }
        .link-button:hover {
            background-color: #4338ca; /* Indigo 700 */
        }
        .project-card {
            background-color: #f9fafb; /* Gray 50 */
            border-radius: 0.75rem;
            padding: 1.5rem;
            border: 1px solid #e2e8f0; /* Gray 200 */
            margin-bottom: 1rem;
            transition: transform 0.2s ease, box-shadow 0.2s ease;
        }
        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.05);
        }
        .project-title {
            font-weight: 600;
            color: #1e293b;
            font-size: 1.125rem; /* text-lg */
            margin-bottom: 0.5rem;
        }
        .profile-picture {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #4f46e5; /* Indigo 600 */
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            margin-bottom: 1.5rem;
        }
    </style>
</head>
<body class="p-4 sm:p-6 lg:p-8">
    <div class="container">
        <!-- Profile Header -->
        <div class="flex flex-col items-center text-center mb-8">
            <img class="profile-picture" src="https://placehold.co/120x120/a78bfa/ffffff?text=JA" alt="Joseph Ahor Abandoh-Sam Profile Picture">
            <h1 class="text-indigo-700">Joseph Ahor Abandoh-Sam</h1>
            <p class="text-lg text-gray-600">Software Engineer | Cybersecurity/Lecturer | ALX Backend Programs Student</p>
            <p class="mt-2 text-gray-500">Passionate about building robust, scalable backend systems and solving practical real-world problems.</p>
        </div>

        <!-- About Me Section -->
        <div class="section-content">
            <h2>
                <!-- SVG Icon for About Me -->
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="icon">
                    <path d="M19 21v-2a4 4 0 0 0-4-4H9a4 4 0 0 0-4 4v2"></path>
                    <circle cx="12" cy="7" r="4"></circle>
                </svg>
                About Me
            </h2>
            <p>I am an Experienced Software Engineer with a background spanning the educational sector, currently enhancing my skills through the **ALX Backend Engineering** and **Backend Pro Development Programs**. My extensive experience includes serving as a Dean and Head of Department, supervising over **100+ student projects**, and contributing to numerous publications and professional associations.</p>
            <p class="mt-2">My journey into software engineering is driven by a deep desire to build powerful, efficient, and scalable backend applications. I am committed to solving practical real-world challenges through code and continuously developing hands-on software engineering skills that are directly applicable to industry needs.</p>
        </div>

        <!-- What I'm Learning / Passionate About Section -->
        <div class="section-content">
            <h2>
                <!-- SVG Icon for Passion -->
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="icon">
                    <path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"></path>
                </svg>
                What Inspires Me & My Learning Goals
            </h2>
            <p>My inspiration stems from the transformative power of software engineering to solve complex problems and create tangible impact. I thrive on the challenge of designing and implementing robust backend architectures that ensure performance, reliability, and security. Specifically, I am driven by:</p>
            <ul class="list-disc pl-5 mt-2">
                <li>**Developing impactful personal projects:** Translating innovative concepts into working applications that address real-world needs.</li>
                <li>**Solving practical real-world problems:** Applying my engineering and cybersecurity expertise to create solutions that directly benefit users and organizations.</li>
                <li>**Developing practical software engineering skills:** Continuously learning and mastering cutting-edge backend technologies, architectural patterns, and best practices from the ALX programs and beyond.</li>
            </ul>
            <p class="mt-2">My aim is to continually enrich my repository with projects that not only demonstrate these practical skills but also showcase my dedication to building effective, real-world solutions.</p>
        </div>

        <!-- Skills Section -->
        <div class="section-content">
            <h2>
                <!-- SVG Icon for Skills -->
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="icon">
                    <path d="M2 12s3-7 10-7 10 7 10 7-3 7-10 7-10-7-10-7Z"></path>
                    <circle cx="12" cy="12" r="3"></circle>
                </svg>
                Skills & Areas of Expertise
            </h2>
            <h3 class="text-indigo-600">Programming Languages:</h3>
            <div class="flex flex-wrap gap-2">
                <span class="tag">Python</span>
                <span class="tag">C</span>
                <span class="tag">C++</span>
                <span class="tag">Java</span>
                <span class="tag">C#</span>
                <span class="tag">VB.Net</span>
                <span class="tag">JavaScript</span>
                <span class="tag">Go (Learning)</span>
            </div>

            <h3 class="text-indigo-600">Backend & Web Technologies:</h3>
            <div class="flex flex-wrap gap-2">
                <span class="tag">Flask</span>
                <span class="tag">Django</span>
                <span class="tag">Node.js</span>
                <span class="tag">Express.js</span>
                <span class="tag">REST APIs</span>
                <span class="tag">PHP</span>
                <span class="tag">Apache</span>
                <span class="tag">WebSockets</span>
            </div>

            <h3 class="text-indigo-600">Databases:</h3>
            <div class="flex flex-wrap gap-2">
                <span class="tag">SQL (PostgreSQL, MySQL)</span>
                <span class="tag">NoSQL (MongoDB, Redis)</span>
                <span class="tag">SQLite</span>
            </div>

            <h3 class="text-indigo-600">DevOps & System Admin:</h3>
            <div class="flex flex-wrap gap-2">
                <span class="tag">Docker</span>
                <span class="tag">Kubernetes (Basic)</span>
                <span class="tag">Linux/Bash</span>
                <span class="tag">Git & GitHub</span>
                <span class="tag">CI/CD (Basic)</span>
                <span class="tag">Deployment Servers</span>
            </div>

            <h3 class="text-indigo-600">Cybersecurity & Networking:</h3>
            <div class="flex flex-wrap gap-2">
                <span class="tag">Network Security Monitoring</span>
                <span class="tag">Vulnerability Assessment</span>
                <span class="tag">Incident Response</span>
                <span class="tag">Cryptography Impact Analysis</span>
                <span class="tag">IT Network Infrastructure (LAN/WAN/WLAN)</span>
                <span class="tag">VOIP Security</span>
                <span class="tag">Computer Hardware Troubleshooting</span>
            </div>

            <h3 class="text-indigo-600">Methodologies & Tools:</h3>
            <div class="flex flex-wrap gap-2">
                <span class="tag">Software Project Management</span>
                <span class="tag">System Modeling & Testing (Formal methods)</span>
                <span class="tag">Requirements Analysis</span>
                <span class="tag">Agile Development</span>
                <span class="tag">Unit Testing</span>
                <span class="tag">Data Structures & Algorithms</span>
            </div>
        </div>

        <!-- Projects Section -->
        <div class="section-content">
            <h2>
                <!-- SVG Icon for Projects -->
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="icon">
                    <path d="M15 10l4.553-2.276A1 1 0 0 1 21 8.667v6.666a1 1 0 0 1-1.447.888L15 14v2a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v2l4.553-2.276A1 1 0 0 1 21 4.667v6.666a1 1 0 0 1-1.447.888L15 10z"></path>
                </svg>
                Featured Projects
            </h2>
            <p class="mb-4">Here are some key projects and contributions where I've applied my backend engineering and problem-solving skills:</p>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                <!-- Project 1: Book Digitization System -->
                <div class="project-card">
                    <h4 class="project-title">
                        <a href="YOUR_PROJECT_REPO_LINK" target="_blank" class="text-indigo-600 hover:underline">Book Digitization & Management System</a>
                    </h4>
                    <p class="text-gray-600 text-sm mb-2">Designed, developed, and implemented a system for managing and scheduling book digitization tasks, including scanning and image processing. Integrated existing Python scripts using Jython for batch processing and image migration.</p>
                    <p class="text-gray-500 text-xs"><strong>Technologies:</strong> Java, Jython, Python (scripts), Database (implied)</p>
                </div>

                <!-- Project 2: Management Systems (Gym, Stores, Bakery) -->
                <div class="project-card">
                    <h4 class="project-title">
                        <a href="YOUR_PROJECT_REPO_LINK" target="_blank" class="text-indigo-600 hover:underline">Campus Management Systems</a>
                    </h4>
                    <p class="text-gray-600 text-sm mb-2">Collaborated with students to successfully develop and implement three management systems for university units: a gymnasium, stores, and a bakery, streamlining their operations.</p>
                    <p class="text-gray-500 text-xs"><strong>Technologies:</strong> Software Engineering principles, Database (implied), (specific languages depend on implementation)</p>
                </div>

                <!-- Project 3: Due Diligence System for Microfinance -->
                <div class="project-card">
                    <h4 class="project-title">
                        <a href="YOUR_PROJECT_REPO_LINK" target="_blank" class="text-indigo-600 hover:underline">Due Diligence System (MFI-Plus)</a>
                    </h4>
                    <p class="text-gray-600 text-sm mb-2">Developed a comprehensive due diligence system specifically designed for microfinance institutes, aimed at enhancing operational efficiency and risk assessment.</p>
                    <p class="text-gray-500 text-xs"><strong>Technologies:</strong> (Specific technologies not specified, but implies backend development and database interaction)</p>
                </div>

                <!-- Project 4: Clustered Distributed System -->
                <div class="project-card">
                    <h4 class="project-title">
                        <a href="YOUR_PROJECT_REPO_LINK" target="_blank" class="text-indigo-600 hover:underline">Clustered Distributed System with Rocks Base OS</a>
                    </h4>
                    <p class="text-gray-600 text-sm mb-2">Led a class project to build a clustered distributed system using Rocks base OS, demonstrating practical application of distributed computing concepts.</p>
                    <p class="text-gray-500 text-xs"><strong>Technologies:</strong> Rocks OS, Distributed Systems, C/C++ (implied)</p>
                </div>

                <!-- Add more projects as you develop them within ALX programs -->
                 <div class="project-card">
                    <h4 class="project-title">
                        <a href="YOUR_PROJECT_REPO_LINK" target="_blank" class="text-indigo-600 hover:underline">1GHC 4 DEV NGO Project (Ongoing)</a>
                    </h4>
                    <p class="text-gray-600 text-sm mb-2">Currently contributing to a 1GHC 4 DEV NGO project, focused on developing practical solutions for non-governmental organizations.</p>
                    <p class="text-gray-500 text-xs"><strong>Technologies:</strong> (To be updated as project progresses)</p>
                </div>

                <div class="project-card">
                    <h4 class="project-title">
                        <a href="YOUR_PROJECT_REPO_LINK" target="_blank" class="text-indigo-600 hover:underline">MOOC for Senior High School Subjects (Ongoing)</a>
                    </h4>
                    <p class="text-gray-600 text-sm mb-2">Involved in the development of a Massive Open Online Course (MOOC) platform for selected Senior High School subjects, targeting adult and remedial students.</p>
                    <p class="text-gray-500 text-xs"><strong>Technologies:</strong> (To be updated as project progresses)</p>
                </div>
            </div>
            <p class="mt-4 text-center text-gray-600">
                <a href="https://github.com/abandoh" target="_blank" class="text-indigo-600 hover:underline link-button mx-auto">
                    View My Student Projects on GitHub
                    <!-- SVG for external link -->
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="ml-2">
                        <path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"></path>
                        <polyline points="15 3 21 3 21 9"></polyline>
                        <line x1="10" y1="14" x2="21" y2="3"></line>
                    </svg>
                </a>
            </p>
        </div>

        <!-- Certifications & Awards Section -->
        <div class="section-content">
            <h2>
                <!-- SVG Icon for Certifications -->
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="icon">
                    <path d="M4 14.899A7 7 0 1 1 15.71 8h1.79a4.5 4.5 0 0 1 2.5 8.242"></path>
                    <path d="M12 12v6"></path>
                    <path d="m15 15-3 3-3-3"></path>
                </svg>
                Certifications & Awards
            </h2>
            <ul class="list-disc pl-5 mt-2">
                <li>**ISC2 Certified Cyber Security** (April 2024)</li>
                <li>**Cisco CyberOps Associate** (May 2023)</li>
                <li>**Udacity Nanodegree: AI Programming with Python** (2022)</li>
                <li>**Udacity Nanodegree: AWS Machine Learning Foundations** (2022)</li>
                <li>**Certificate: Cybersecurity: Technology, Application and Policy** (MIT Professional Education, 2015)</li>
                <li>**Ghana National Petroleum Company Foundation Scholarship** (PhD, 2019 Cohorts)</li>
                <li>**National Collegiate of Inventors and Innovators Alliance (NCIIA) VentureLab Phase I Grant** ($5,000)</li>
                <li>**Sponsored trip to Switzerland** (International Students' Committee Symposium, 2004)</li>
            </ul>
        </div>

        <!-- Publications Section -->
        <div class="section-content">
            <h2>
                <!-- SVG Icon for Publications -->
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="icon">
                    <path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"></path>
                    <polyline points="14 2 14 8 20 8"></polyline>
                    <line x1="16" y1="13" x2="8" y2="13"></line>
                    <line x1="16" y1="17" x2="8" y2="17"></line>
                    <polyline points="10 9 9 9 8 9"></polyline>
                </svg>
                Selected Publications
            </h2>
            <ul class="list-disc pl-5 mt-2 text-sm">
                <li>**BIOMETRIC AUTHENTICATION SCHEMES AND METHODS ON MOBILE DEVICES: A SYSTEMATIC REVIEW.** (Ekpezu, A. O., Umoh, E. E., Koranteng, F. N., & Abandoh-Sam, J. A., 2020)</li>
                <li>**EXPLORING CHALLENGES FACED BY INTERNATIONAL STUDENTS IN COMPUTER SCIENCE PROGRAMS: TOWARDS UNDERSTANDING THE STUDENT PERSPECTIVE.** (Oudshoorn, M. J. et al., Abandoh-Sam, J. A., 2019)</li>
                <li>**An international investigation into student concerns regarding transition into higher education.** (Zarb, M., Abandoh-Sam, J. A. et al., 2018)</li>
                <li>**Proposing Android Unlocking Pin (AUP) as an Alternative to Traditional Alphanumeric Password.** (Abandoh-Sam, J. A., Damoah, D. et al., 2013)</li>
            </ul>
            <p class="mt-2 text-center text-gray-600 text-sm">
                For a complete list of publications, please refer to my <a href="YOUR_FULL_PUBLICATIONS_LIST_URL" target="_blank" class="text-indigo-600 hover:underline">full portfolio/CV</a>.
            </p>
        </div>

        <!-- Connect with Me Section -->
        <div class="section-content">
            <h2>
                <!-- SVG Icon for Connect -->
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="icon">
                    <path d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 4.7 8.38 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 0 1-.9-3.8 8.5 8.5 0 0 1 4.7-7.6 8.38 8.38 0 0 1 3.8-.9h.5a8.48 8.48 0 0 1 8 8v.5z"></path>
                </svg>
                Connect With Me
            </h2>
            <div class="flex flex-wrap gap-4 mt-4 justify-center">
                <a href="https://www.linkedin.com/in/joseph-abandoh-sam-142b8532" target="_blank" class="link-button">
                    <!-- LinkedIn Icon SVG -->
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="currentColor" class="mr-2">
                        <path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path>
                        <rect x="2" y="9" width="4" height="12"></rect>
                        <circle cx="4" cy="4" r="2"></circle>
                    </svg>
                    LinkedIn
                </a>
                <a href="YOUR_TWITTER_URL" target="_blank" class="link-button bg-blue-500 hover:bg-blue-600">
                    <!-- Twitter/X Icon SVG (simplified) -->
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="currentColor" class="mr-2">
                        <path d="M22 4.01c-.72.32-1.5.53-2.32.62.82-.49 1.45-1.27 1.75-2.23-.77.46-1.63.79-2.54.97-.73-.78-1.77-1.27-2.92-1.27-2.2 0-3.99 1.8-3.99 4 0 .31.04.61.1.89-3.32-.16-6.27-1.75-8.24-4.14-.34.58-.53 1.25-.53 1.96 0 1.38.7 2.6 1.77 3.32-.65-.02-1.27-.2-1.81-.5v.05c0 1.95 1.38 3.58 3.2 3.96-.3.08-.6.13-.9.13-.22 0-.43-.02-.64-.06.5 1.6 1.97 2.77 3.69 2.8-.75.59-1.7 1-2.73 1-1.77 0-3.4-.94-4.55-2.48.56.09 1.15.14 1.75.14 2.13 0 3.9-1.12 4.83-2.78 1.05-1.75 1.63-3.78 1.63-5.94 0-.17-.01-.33-.02-.5.18-.16.35-.33.51-.5z"></path>
                    </svg>
                    Twitter / X
                </a>
                <a href="mailto:abandoh@gmail.com" class="link-button bg-gray-600 hover:bg-gray-700">
                    <!-- Email Icon SVG -->
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-2">
                        <rect x="2" y="4" width="20" height="16" rx="2"></rect>
                        <path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"></path>
                    </svg>
                    Email Me
                </a>
            </div>
        </div>

        <!-- Footer -->
        <div class="text-center text-gray-500 text-sm mt-8 pt-4 border-t border-gray-200">
            <p>&copy; 2025 Joseph Ahor Abandoh-Sam. All rights reserved.</p>
        </div>
    </div>
</body>
</html>


<!--
**abandoh-ils/abandoh-ils** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
