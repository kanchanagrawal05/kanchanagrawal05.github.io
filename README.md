<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kanchan Agrawal - Portfolio</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        /* Custom styles */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc; /* slate-50 */
        }
        .section-title {
            font-size: 1.875rem; /* text-3xl */
            font-weight: 700; /* font-bold */
            color: #1e293b; /* slate-800 */
            margin-bottom: 2rem;
            text-align: center;
        }
        .card {
            background-color: white;
            border-radius: 0.75rem; /* rounded-xl */
            box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            overflow: hidden;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);
        }
    </style>
</head>
<body class="text-slate-700">

    <!-- Header & Hero Section -->
    <header class="bg-slate-800 text-white">
        <div class="container mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 py-16">
            <div class="flex flex-col md:flex-row items-center justify-between">
                <div class="md:w-2/3 text-center md:text-left mb-8 md:mb-0">
                    <h1 class="text-4xl md:text-6xl font-bold tracking-tight text-white">Kanchan Agrawal</h1>
                    <p class="mt-4 text-lg md:text-xl text-slate-300">Enthusiastic Learner & Aspiring Developer</p>
                    <div class="mt-6 flex justify-center md:justify-start space-x-6 text-slate-300">
                        <a href="mailto:kanchanagrawal0505@gmail.com" class="hover:text-cyan-400 transition-colors"><i class="fas fa-envelope mr-2"></i>kanchanagrawal0505@gmail.com</a>
                        <a href="#" class="hover:text-cyan-400 transition-colors"><i class="fas fa-phone mr-2"></i>+91-6266090362</a>
                        <a href="https://www.linkedin.com/in/kanchan-agrawal/" target="_blank" class="hover:text-cyan-400 transition-colors"><i class="fab fa-linkedin mr-2"></i>kanchan-agrawal</a>
                    </div>
                </div>
                <div class="md:w-1/3 flex justify-center">
                    <img src="https://i.imgur.com/gY8g21p.jpeg" alt="Kanchan Agrawal" class="h-48 w-48 md:h-56 md:w-56 rounded-full object-cover border-4 border-cyan-400 shadow-lg">
                </div>
            </div>
        </div>
    </header>

    <main class="container mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 py-12">

        <!-- About Me Section -->
        <section id="about" class="py-12">
            <h2 class="section-title">About Me</h2>
            <div class="max-w-3xl mx-auto text-center text-lg text-slate-600 p-8 bg-white rounded-xl shadow-md">
                <p>An enthusiastic learner with a strong work ethic, ready to work in an environment where I can grow my technical skills and contribute to company goals. Eager to work in a team and find innovative solutions to help the organization succeed.</p>
            </div>
        </section>

        <!-- Education Section -->
        <section id="education" class="py-12">
            <h2 class="section-title">Education</h2>
            <div class="max-w-4xl mx-auto space-y-6">
                <div class="card p-6">
                    <h3 class="text-xl font-bold text-slate-800">Bachelors of Technology (B.Tech)</h3>
                    <p class="text-md text-cyan-600 font-semibold">Jaipur Engineering College and Research Centre, Jaipur</p>
                    <p class="text-sm text-slate-500 mt-1">2021 - 2025</p>
                    <p class="mt-2">Current CGPA: <strong>9.29</strong></p>
                </div>
                 <div class="card p-6">
                    <h3 class="text-xl font-bold text-slate-800">12th Grade (Senior Secondary)</h3>
                    <p class="text-md text-cyan-600 font-semibold">City Monteswari Public School, Morena (M.P)</p>
                     <p class="text-sm text-slate-500 mt-1">2020 - 2021</p>
                    <p class="mt-2">Percentage: <strong>89%</strong></p>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="py-12">
            <h2 class="section-title">Skills</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-4xl mx-auto">
                <div class="card p-6">
                    <h3 class="text-xl font-bold text-center text-slate-800 mb-4">Technical Skills</h3>
                    <div class="flex flex-wrap justify-center gap-3">
                        <span class="bg-cyan-100 text-cyan-800 text-sm font-medium px-4 py-2 rounded-full">C</span>
                        <span class="bg-cyan-100 text-cyan-800 text-sm font-medium px-4 py-2 rounded-full">C++</span>
                        <span class="bg-cyan-100 text-cyan-800 text-sm font-medium px-4 py-2 rounded-full">OOPS</span>
                        <span class="bg-cyan-100 text-cyan-800 text-sm font-medium px-4 py-2 rounded-full">DBMS</span>
                        <span class="bg-cyan-100 text-cyan-800 text-sm font-medium px-4 py-2 rounded-full">SQL</span>
                        <span class="bg-cyan-100 text-cyan-800 text-sm font-medium px-4 py-2 rounded-full">Machine Learning</span>
                        <span class="bg-cyan-100 text-cyan-800 text-sm font-medium px-4 py-2 rounded-full">Power BI</span>
                    </div>
                </div>
                <div class="card p-6">
                    <h3 class="text-xl font-bold text-center text-slate-800 mb-4">Soft Skills</h3>
                    <div class="flex flex-wrap justify-center gap-3">
                        <span class="bg-slate-100 text-slate-800 text-sm font-medium px-4 py-2 rounded-full">Teamwork</span>
                        <span class="bg-slate-100 text-slate-800 text-sm font-medium px-4 py-2 rounded-full">Communication</span>
                        <span class="bg-slate-100 text-slate-800 text-sm font-medium px-4 py-2 rounded-full">Event Management</span>
                        <span class="bg-slate-100 text-slate-800 text-sm font-medium px-4 py-2 rounded-full">Adaptability</span>
                        <span class="bg-slate-100 text-slate-800 text-sm font-medium px-4 py-2 rounded-full">Content Writing</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="py-12">
            <h2 class="section-title">Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-5xl mx-auto">
                <div class="card p-6 flex flex-col">
                    <h3 class="text-xl font-bold text-slate-800">House Price Predictor</h3>
                    <p class="text-sm text-cyan-600 font-semibold mb-2">Machine Learning</p>
                    <p class="text-slate-600 flex-grow">This project employs machine learning to predict real estate values and inform house pricing strategies. It includes data preprocessing, feature engineering, and model training with various regression algorithms to achieve accurate predictions.</p>
                    <p class="text-sm text-slate-400 mt-4">Aug 2023 - Sep 2023</p>
                </div>
                <div class="card p-6 flex flex-col">
                    <h3 class="text-xl font-bold text-slate-800">Line Follower with Obstacle Detection</h3>
                    <p class="text-sm text-cyan-600 font-semibold mb-2">Embedded Systems & Robotics</p>
                    <p class="text-slate-600 flex-grow">This project integrates expertise in electronics, programming, and robotics. The robot uses IR sensors, a microcontroller, and motor drivers to follow a designated path while using ultrasonic sensors to safely dodge obstacles in its way.</p>
                     <p class="text-sm text-slate-400 mt-4">Jul 2022 - Aug 2022</p>
                </div>
            </div>
        </section>
        
        <!-- Internships & Training Section -->
        <section id="experience" class="py-12">
            <h2 class="section-title">Internships & Training</h2>
            <div class="max-w-4xl mx-auto space-y-6">
                <div class="card p-6">
                    <h3 class="text-xl font-bold text-slate-800">Machine Learning-Deep Learning and Artificial Intelligence</h3>
                    <p class="text-md text-cyan-600 font-semibold">Upflairs Pvt. Ltd.</p>
                    <p class="text-sm text-slate-500 mt-1">Jul 2023 - Sep 2023</p>
                    <p class="mt-2 text-slate-600">Successfully completed 45 days of intensive training, where I acquired practical skills in data analysis, model building, and implementing ML/DL algorithms.</p>
                </div>
                 <div class="card p-6">
                    <h3 class="text-xl font-bold text-slate-800">Embedded Systems and Robotics</h3>
                    <p class="text-md text-cyan-600 font-semibold">Upflairs Pvt. Ltd.</p>
                     <p class="text-sm text-slate-500 mt-1">Jul 2022 - Aug 2022</p>
                    <p class="mt-2 text-slate-600">Undergone a 15-day training program where I gained practical experience in building embedded hardware and software solutions, including sensor integration and microcontroller programming.</p>
                </div>
            </div>
        </section>

        <!-- Achievements & Certifications Section -->
        <section id="achievements" class="py-12">
            <h2 class="section-title">Achievements & Certifications</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 max-w-6xl mx-auto">
                <!-- Certification 1 -->
                <div class="card p-6 text-center">
                    <div class="text-4xl text-cyan-500 mb-3"><i class="fas fa-award"></i></div>
                    <h3 class="text-lg font-bold text-slate-800">Certified Application Developer</h3>
                    <p class="text-sm text-slate-500">ServiceNow</p>
                </div>
                <!-- Certification 2 -->
                <div class="card p-6 text-center">
                    <div class="text-4xl text-cyan-500 mb-3"><i class="fas fa-award"></i></div>
                    <h3 class="text-lg font-bold text-slate-800">Data Analyst with PowerBI</h3>
                    <p class="text-sm text-slate-500">TechnoGlobe</p>
                </div>
                <!-- Certification 3 -->
                <div class="card p-6 text-center">
                    <div class="text-4xl text-cyan-500 mb-3"><i class="fas fa-award"></i></div>
                    <h3 class="text-lg font-bold text-slate-800">Machine Learning Workshop</h3>
                    <p class="text-sm text-slate-500">ShapeMySkills Pvt. Ltd.</p>
                </div>
                <!-- Achievement 1 -->
                <div class="card p-6 text-center">
                    <div class="text-4xl text-yellow-500 mb-3"><i class="fas fa-star"></i></div>
                    <h3 class="text-lg font-bold text-slate-800">Event Coordinator</h3>
                    <p class="text-sm text-slate-500">Coordinated "Zarurat- Celebrating Innocence" for 300+ children.</p>
                </div>
                <!-- Achievement 2 -->
                <div class="card p-6 text-center">
                    <div class="text-4xl text-yellow-500 mb-3"><i class="fas fa-star"></i></div>
                    <h3 class="text-lg font-bold text-slate-800">Core Organizer</h3>
                    <p class="text-sm text-slate-500">Core team member for GDSC WOW'23 Jaipur (500+ participants).</p>
                </div>
                <!-- Achievement 3 -->
                <div class="card p-6 text-center">
                    <div class="text-4xl text-yellow-500 mb-3"><i class="fas fa-star"></i></div>
                    <h3 class="text-lg font-bold text-slate-800">Art Exhibition Manager</h3>
                    <p class="text-sm text-slate-500">Organized and managed Blendspace 2.0 art exhibition.</p>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-slate-800 text-white">
        <div class="container mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 py-8 text-center">
            <p>&copy; 2024 Kanchan Agrawal. All Rights Reserved.</p>
            <p class="text-sm text-slate-400 mt-2">Built with HTML & Tailwind CSS.</p>
        </div>
    </footer>

</body>
</html>
