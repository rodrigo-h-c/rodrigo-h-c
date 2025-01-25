<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rodrigo Hernández Cervantes</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/alpinejs@3.x.x/dist/cdn.min.js" defer></script>
    <style>
        /* [Previous CSS remains the same] */
        .cv-section {
            margin-top: 1rem;
        }
        .cv-section h3 {
            color: var(--accent);
            margin-bottom: 0.5rem;
        }
        .cv-section p, .cv-section ul {
            color: var(--text-secondary);
            margin-bottom: 1rem;
        }
        .contact-info {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            margin-bottom: 1rem;
        }
        .contact-link {
            color: var(--text-primary);
            text-decoration: none;
            transition: color 0.3s ease;
        }
        .contact-link:hover {
            color: var(--accent);
        }
    </style>
</head>
<body>
    <div x-data="{ activeTab: 'inicio' }" class="container">
        <!-- [Previous header remains the same] -->

        <!-- [Previous navigation tabs remain the same] -->

        <div class="content-section">
            <div x-show="activeTab === 'inicio'">
                <h2 class="text-2xl font-bold mb-4">Professional Profile</h2>
                
                <div class="contact-info">
                    <a href="mailto:rohrc14@gmail.com" class="contact-link">📧 rohrc14@gmail.com</a>
                    <a href="tel:+525533647101" class="contact-link">📱 +52 55 33 647 101</a>
                    <a href="https://www.linkedin.com/in/rodrigo-h-cervantes-9110b22ab/" target="_blank" class="contact-link">LinkedIn</a>
                    <a href="https://github.com/rhc14" target="_blank" class="contact-link">GitHub</a>
                </div>

                <div class="cv-section">
                    <h3>Professional Summary</h3>
                    <p>Economics undergraduate student with experience in research, academic management, and student organization. Interested in economic policy analysis, technological development, and food security.</p>
                </div>

                <div class="cv-section">
                    <h3>Education</h3>
                    <p><strong>National Autonomous University of Mexico (UNAM)</strong><br>
                    Bachelor's in Economics | August 2022 - Present</p>
                    <ul>
                        <li>Current GPA: 9.48</li>
                        <li>Relevant Courses: Econometrics, Economic Theory, Data Analysis, Industrial Policy</li>
                    </ul>
                </div>

                <div class="cv-section">
                    <h3>Research Experience</h3>
                    <p><strong>Research Fellow, Institute of Economic Research, UNAM</strong><br>
                    November 2022 - Present</p>
                    <ul>
                        <li>Research Assistant to Dr. Marcia Solorza Luna</li>
                        <li>Collaborated on research projects about international financial system, monetary policy, financial intermediation, and economic development</li>
                    </ul>
                </div>

                <div class="cv-section">
                    <h3>Leadership</h3>
                    <p><strong>President, National Association of Economics Students</strong><br>
                    February 2024 – January 2024</p>
                    <ul>
                        <li>Led and coordinated academic activities</li>
                        <li>Managed projects, events, and student representation</li>
                    </ul>
                </div>

                <div class="cv-section">
                    <h3>Projects</h3>
                    <p><strong>OBIVU - University Inequality and Violence Observatory 2025</strong></p>
                    <ul>
                        <li>Collaborated with Young Scholar Initiative to develop a Latin American-level observatory</li>
                        <li>Conducted data analysis on inequality and violence in university contexts</li>
                    </ul>
                </div>

                <div class="cv-section">
                    <h3>Publications</h3>
                    <p>La Mano Visible Economic Magazine: Analysis of food security and sovereignty in the context of neoliberalism in Mexico, focusing on corn as a case study.</p>
                </div>
            </div>

            <!-- [Rest of the previous template remains the same] -->
        </div>
    </div>
</body>
</html>
