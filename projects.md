
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projects | Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/css/bootstrap.min.css">
    <style>
        body {
            background-color: #f8f9fa;
            font-family: Arial, sans-serif;
        }
        .project-card {
            margin-bottom: 30px;
            border: 1px solid #ddd;
            border-radius: 8px;
            background-color: #fff;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }
        .project-card img {
            max-height: 200px;
            object-fit: cover;
            width: 100%;
        }
        .project-card .card-body {
            padding: 20px;
        }
        .project-card h5 {
            color: #333;
        }
        .project-card a {
            text-decoration: none;
            color: #007bff;
        }
        .show-more {
            cursor: pointer;
            color: #007bff;
            text-decoration: underline;
        }
        .full-description {
            display: none;
            margin-top: 10px;
        }
        .achievements {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 15px;
        }
        .achievement-badge {
            background-color: #007bff;
            color: #fff;
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <div class="container py-5">
        <h1 class="text-center mb-5">My Projects</h1>
        <div class="row">
            <!-- Expeni Project -->
            <div class="col-12">
                <div class="project-card">
                    <img src="images/expeni.png" alt="Expeni Project">
                    <div class="card-body">
                        <h5>Expeni - Purchase Order Management Solution</h5>
                        <p><strong>Company:</strong> Panda Tech</p>
                        <p><strong>Duration:</strong> 04/2023 - 10/2025</p>
                        <p><strong>Tools:</strong> .NET Core, C#, SQL Server, ASP.NET MVC, Knockout.js, HTML, CSS, JavaScript, jQuery</p>
                        <p><strong>Role:</strong> Led a team of 3 developers, conducted sprint meetings, weekly planning, code reviews, and contributed to coding.</p>
                        <span class="show-more" onclick="toggleDescription(this)">Show more</span>
                        <div class="full-description">
                            <p><strong>Key Contributions:</strong></p>
                            <ul>
                                <li>Implemented multi-language translation using I18next library, adapting the entire application to user regions with full website translation, language change options, and user settings.</li>
                                <li>Developed a service to download entire company data in one click as a ZIP file.</li>
                                <li>Introduced and implemented purchase invoices, payment requests, and recurring purchase orders.</li>
                                <li>Added categories for purchase orders and budgets, custom labels for purchase orders, and budget intervals (monthly, quarterly, yearly).</li>
                                <li>Improved approval routes for all documents (PO, PR, PI).</li>
                                <li>Provided daily user support and resolved bugs.</li>
                            </ul>
                            <p><strong>Achievements:</strong></p>
                            <div class="achievements">
                                <span class="achievement-badge">Improved app efficiency by 30%</span>
                                <span class="achievement-badge">Handled 12 companies and 8k users</span>
                                <span class="achievement-badge">Streamlined processes with 40% improvement</span>
                                <span class="achievement-badge">Delivered projects on time</span>
                            </div>
                        </div>
                        <a href="https://app.expeni.com/home/login" target="_blank">View Project</a>
                    </div>
                </div>
            </div>

            <!-- CMS Project -->
            <div class="col-12">
                <div class="project-card">
                    <img src="images/cms.png" alt="CMS Project">
                    <div class="card-body">
                        <h5>Campus Management System (CMS)</h5>
                        <p><strong>Company:</strong> ISLO Technologies</p>
                        <p><strong>Duration:</strong> 03/2021 - 08/2023</p>
                        <p><strong>Tools:</strong> Asp.net MVC 5, C#, JavaScript, JQuery, Ajax, HTML, CSS, Bootstrap, SQL</p>
                        <p><strong>Role:</strong> Developer - Interacted with clients, gathered requirements, provided support and maintenance, and worked as a full-stack developer.</p>
                        <span class="show-more" onclick="toggleDescription(this)">Show more</span>
                        <div class="full-description">
                            <p><strong>Key Contributions:</strong></p>
                            <ul>
                                <li>Integrated online payment of student fees through KuickPay by building an API.</li>
                                <li>Introduced subject assignments for students and improved student promotion to the next grade.</li>
                                <li>Worked on user access rights, visitor management, and subject-wise attendance.</li>
                                <li>Integrated biometric devices for attendance.</li>
                                <li>Improved the Fee module and reporting across the app.</li>
                                <li>Introduced student and parent portals.</li>
                            </ul>
                            <p><strong>Achievements:</strong></p>
                            <div class="achievements">
                                <span class="achievement-badge">Improved app by 50%</span>
                                <span class="achievement-badge">Handled 3 schools and 5k users</span>
                                <span class="achievement-badge">Enhanced efficiency by 40%</span>
                            </div>
                        </div>
                        <a href="http://cms.islotechnologies.com" target="_blank">View Project</a>
                    </div>
                </div>
            </div>

            <!-- Quran Academy Management System -->
            <div class="col-12">
                <div class="project-card">
                    <img src="images/quran_academy.png" alt="Quran Academy Management System">
                    <div class="card-body">
                        <h5>Online Quran Academy Management System</h5>
                        <p><strong>Role:</strong> Full-stack developer - Designed database, backend, and frontend, and provided maintenance.</p>
                        <span class="show-more" onclick="toggleDescription(this)">Show more</span>
                        <div class="full-description">
                            <p><strong>Achievements:</strong></p>
                            <div class="achievements">
                                <span class="achievement-badge">Improved efficiency by 50%</span>
                                <span class="achievement-badge">Handled 1 company and 120 users</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Online Auction System -->
            <div class="col-12">
                <div class="project-card">
                    <img src="images/auction_system.png" alt="Online Auction System">
                    <div class="card-body">
                        <h5>Online Auction System</h5>
                        <p><strong>Role:</strong> Full-stack developer - Designed database, backend, and frontend, and provided maintenance.</p>
                        <span class="show-more" onclick="toggleDescription(this)">Show more</span>
                        <div class="full-description">
                            <p><strong>Achievements:</strong></p>
                            <div class="achievements">
                                <span class="achievement-badge">Improved efficiency by 50%</span>
                                <span class="achievement-badge">Handled 1 company and 90 users</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Office Management System -->
            <div class="col-12">
                <div class="project-card">
                    <img src="images/office_management.png" alt="Office Management System">
                    <div class="card-body">
                        <h5>Office Management System (OMS)</h5>
                        <p><strong>Role:</strong> Developer - Interacted with clients, gathered requirements, provided support and maintenance, and worked as a full-stack developer.</p>
                        <span class="show-more" onclick="toggleDescription(this)">Show more</span>
                        <div class="full-description">
                            <p><strong>Key Contributions:</strong></p>
                            <ul>
                                <li>Improved the app and provided maintenance.</li>
                                <li>Integrated biometric devices for attendance.</li>
                            </ul>
                            <p><strong>Achievements:</strong></p>
                            <div class="achievements">
                                <span class="achievement-badge">Improved efficiency by 50%</span>
                                <span class="achievement-badge">Handled 2 companies and 200 users</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Gym Management System -->
            <div class="col-12">
                <div class="project-card">
                    <img src="images/gym_management.png" alt="Gym Management System">
                    <div class="card-body">
                        <h5>Gym Management System (GMS)</h5>
                        <p><strong>Role:</strong> Developer - Interacted with clients, gathered requirements, provided support and maintenance, and worked as a full-stack developer.</p>
                        <span class="show-more" onclick="toggleDescription(this)">Show more</span>
                        <div class="full-description">
                            <p><strong>Key Contributions:</strong></p>
                            <ul>
                                <li>Improved the app and provided maintenance.</li>
                                <li>Integrated biometric devices for attendance.</li>
                            </ul>
                            <p><strong>Achievements:</strong></p>
                            <div class="achievements">
                                <span class="achievement-badge">Improved efficiency by 50%</span>
                                <span class="achievement-badge">Handled 2 companies and 200 users</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </div>

    <script>
        function toggleDescription(element) {
            const fullDescription = element.nextElementSibling;
            if (fullDescription.style.display === "none" || !fullDescription.style.display) {
                fullDescription.style.display = "block";
                element.textContent = "Show less";
            } else {
                fullDescription.style.display = "none";

                element.textContent = "Show more";
            }
        }
    </script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
</body>
</html>
