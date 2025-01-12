
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
                        <p><strong>Description:</strong> Directed the development of a feature-rich Purchase Order solution to streamline procurement processes and enhance workflow efficiency.</p>
                        <span class="show-more" onclick="toggleDescription(this)">Show more</span>
                        <div class="full-description">
                            <p>Key Achievements:
                                <ul>
                                    <li>Streamlined Procurement Processes: Introduced one-click approval processes, simplifying Purchase Order management challenges.</li>
                                    <li>Enabled employees to issue, copy, and manage purchase orders seamlessly, including attachments and automatic email notifications for approvals.</li>
                                    <li>Multi-level Approval System: Implemented a multi-level approval system, allowing managers to approve orders from anywhere, enhancing accessibility and workflow efficiency.</li>
                                    <li>Comprehensive Functionality: Developed functionalities for Finance, enabling payment additions, data export in CSV or PDF formats, and customization options such as PO form tailoring.</li>
                                    <li>User-Friendly Interface: Utilized .NET MVC on the frontend, ensuring a seamless and user-friendly interface for Expeni.</li>
                                    <li>Team Leadership and Project Management: Led a team of 3 developers, overseeing task assignments, conducting daily status meetings, and actively participating in decision-making processes.</li>
                                </ul>
                            </p>
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
                        <p><strong>Description:</strong> An online-based Educational System with multiple modules to manage academic and administrative tasks efficiently.</p>
                        <span class="show-more" onclick="toggleDescription(this)">Show more</span>
                        <div class="full-description">
                            <p>Modules include:
                                <ul>
                                    <li>Academics Management</li>
                                    <li>Student Management</li>
                                    <li>Attendance Management</li>
                                    <li>HR Management</li>
                                    <li>Exam Management</li>
                                    <li>Fee Management</li>
                                    <li>Inventory Management</li>
                                    <li>Teacher Management</li>
                                    <li>Student/Parent Portal</li>
                                </ul>
                            </p>
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
                        <p><strong>Company:</strong> Quran Services Online</p>
                        <p><strong>Duration:</strong> 10/2022 - 08/2023</p>
                        <p><strong>Tools:</strong> .NET Core, C#, JavaScript, jQuery, HTML, CSS, Bootstrap, MS SQL</p>
                        <p><strong>Description:</strong> A web-based system serving students, teachers, admin, and parents for managing academy activities.</p>
                        <span class="show-more" onclick="toggleDescription(this)">Show more</span>
                        <div class="full-description">
                            <p>Modules:
                                <ul>
                                    <li>Admin Panel</li>
                                    <li>Student Management</li>
                                    <li>Academic Management</li>
                                    <li>Attendance Management</li>
                                    <li>Fee Management</li>
                                    <li>Staff Management</li>
                                    <li>Teacher Management</li>
                                    <li>Student Portal</li>
                                    <li>Parent Portal</li>
                                </ul>
                            </p>
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
                        <p><strong>Company:</strong> University Student</p>
                        <p><strong>Duration:</strong> 12/2022 - 08/2023</p>
                        <p><strong>Tools:</strong> Asp.net MVC 5, C#, JavaScript, JQuery, Ajax, HTML, CSS, Bootstrap, SQL</p>
                        <p><strong>Description:</strong> An application to facilitate buying and selling through auctions, enhancing reach and efficiency for users.</p>
                        <span class="show-more" onclick="toggleDescription(this)">Show more</span>
                        <div class="full-description">
                            <p>Modules:
                                <ul>
                                    <li>Admin</li>
                                    <li>Buyer</li>
                                    <li>Seller</li>
                                </ul>
                            </p>
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
                        <p><strong>Company:</strong> ISLO Technologies</p>
                        <p><strong>Duration:</strong> 03/2021 - 08/2023</p>
                        <p><strong>Tools:</strong> Asp.net MVC 5, C#, JavaScript, JQuery, Ajax, HTML, CSS, Bootstrap, SQL</p>
                        <p><strong>Description:</strong> A comprehensive system to manage various office operations effectively.</p>
                        <span class="show-more" onclick="toggleDescription(this)">Show more</span>
                        <div class="full-description">
                            <p>Modules:
                                <ul>
                                    <li>System Management</li>
                                    <li>HR Management</li>
                                    <li>Supply Chain Management</li>
                                    <li>Inventory Management</li>
                                    <li>Assets Management</li>
                                    <li>Project Management</li>
                                    <li>Work Logs Management</li>
                                    <li>Operations Management</li>
                                </ul>
                            </p>
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
                        <p><strong>Company:</strong> ISLO Technologies</p>
                        <p><strong>Duration:</strong> 03/2021 - 08/2023</p>
                        <p><strong>Tools:</strong> Asp.net MVC 5, C#, JavaScript, JQuery, Ajax, HTML, CSS, Bootstrap, SQL</p>
                        <p><strong>Description:</strong> A web-based solution to streamline gym operations and management.</p>
                        <span class="show-more" onclick="toggleDescription(this)">Show more</span>
                        <div class="full-description">
                            <p>Modules:
                                <ul>
                                    <li>Accounts Management</li>
                                    <li>Attendance Management</li>
                                    <li>Member Management</li>
                                    <li>Staff Management</li>
                                    <li>Store Management</li>
                                    <li>Admin Panel</li>
                                </ul>
                            </p>
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
