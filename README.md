<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Irum Shahzadi - Frontend Developer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            background: linear-gradient(135deg, #1e3a8a 0%, #6b7280 100%);
        }
        .profile-img {
            border: 4px solid white;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
        }
        .card {
            background: linear-gradient(45deg, #3b82f6 0%, #7e22ce 100%);
            color: white;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.4);
        }
        .stats-card {
            background: linear-gradient(45deg, #1e40af 0%, #4b0082 100%);
        }
        .tools-card {
            background: linear-gradient(45deg, #4c1d95 0%, #1e3a8a 100%);
        }
        .social-icon:hover, .tool-icon:hover {
            transform: scale(1.2);
            transition: transform 0.3s ease;
        }
        #back-to-top {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #1e40af;
            color: white;
            padding: 10px 15px;
            border-radius: 50%;
            cursor: pointer;
            display: none;
        }
        #back-to-top:hover {
            background-color: #2563eb;
        }
        @media (max-width: 640px) {
            .profile-img {
                width: 100%;
                max-width: 300px;
            }
            h1 {
                font-size: 2rem;
            }
            h3 {
                font-size: 1.25rem;
            }
            .container {
                padding-left: 1rem;
                padding-right: 1rem;
            }
        }
        @media (max-width: 768px) {
            .stats-card img {
                width: 100%;
                max-width: 400px;
            }
        }
    </style>
</head>
<body class="flex flex-col items-center min-h-screen text-white font-sans">
    <div class="container max-w-5xl mx-auto px-4 sm:px-6 lg:px-8 py-8">
        <!-- Header Section -->
        <header class="text-center mb-12">
            <div class="flex justify-center items-center gap-4 mb-4">
                <h1 class="text-3xl sm:text-4xl lg:text-5xl font-bold">Irum Shahzadi</h1>
                <img src="https://upload.wikimedia.org/wikipedia/commons/3/32/Flag_of_Pakistan.svg" alt="Pakistan Flag" class="h-10 w-16 sm:h-12 sm:w-20">
            </div>
            <h3 class="text-lg sm:text-xl lg:text-2xl text-gray-200">A passionate Frontend Developer from Pakistan</h3>
            <img class="mt-6 mx-auto rounded-lg profile-img" alt="Coding" width="500" src="https://cdn.dribbble.com/users/1668950/screenshots/3863114/rodoshi.gif">
        </header>

        <section class="flex flex-col sm:flex-row justify-center gap-4 mb-8">
            <img src="https://komarev.com/ghpvc/?username=irum-shah78&label=Profile%20views&color=0e75b6&style=flat" alt="irum-shah78" class="max-w-full" />
            <img src="https://github-profile-trophy.vercel.app/?username=irum-shah78&theme=darkhub&margin-w=15" alt="irum-shah78" class="max-w-full" />
        </section>

        <!-- About Me Section -->
        <section class="card rounded-lg shadow-lg p-6 mb-8">
            <h3 class="text-2xl font-semibold mb-4">About Me</h3>
            <ul class="space-y-2">
                <li>🔭 I’m currently working as <span class="font-bold">Associate Software Engineer</span>.</li>
                <li>🌱 I’m currently learning <span class="font-bold">Angular, Backend & MERN Stack</span>.</li>
                <li>👨‍💻 All of my projects are available at <a href="https://github.com/irum-shah78" class="text-blue-200 hover:underline">github.com/irum-shah78</a>.</li>
                <li>💬 Ask me about <span class="font-bold">Software Engineering, Frontend Development, and Cyber Security</span>.</li>
                <li>📫 How to reach me: <a nbr="mailto:irums.dev@gmail.com" class="text-blue-200 hover:underline">irums.dev@gmail.com</a>.</li>
            </ul>
        </section>

        <!-- Connect With Me -->
        <section class="card rounded-lg shadow-lg p-6 mb-8">
            <h3 class="text-2xl font-semibold mb-4 text-center">Connect with Me</h3>
            <div class=" personally flex justify-center gap-4 flex-wrap">
                <a href="https://twitter.com/irum_shah12" target="_blank" class="social-icon">
                    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="Twitter" class="h-10 w-10" />
                </a>
                <a href="https://www.linkedin.com/in/irum-shahzadi-i9182113s/" target="_blank" class="social-icon">
                    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" class="h-10 w-10" />
                </a>
                <a href="https://www.facebook.com/profile.php?id=100051186189990" target="_blank" class="social-icon">
                    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="Facebook" class="h-10 w-10" />
                </a>
                <a href="https://www.instagram.com/_.irum_shah._/" target="_blank" class="social-icon">
                    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram" class="h-10 w-10" />
                </a>
            </div>
        </section>

        <!-- Languages and Tools -->
        <section class="tools-card card rounded-lg shadow-lg p-6 mb-8">
            <h3 class="text-2xl font-semibold mb-4">Languages and Tools</h3>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="https://getbootstrap.com" target="_blank" class="tool-icon">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="Bootstrap" class="h-10 w-10" />
                </a>
                <a href="https://www.w3schools.com/css/" target="_blank" class="tool-icon">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" class="h-10 w-10" />
                </a>
                <a href="https://git-scm.com/" target="_blank" class="tool-icon">
                    <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" class="h-10 w-10" />
                </a>
                <a href="https://www.w3.org/html/" target="_blank" class="tool-icon">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" class="h-10 w-10" />
                </a>
                <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" class="tool-icon">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" class="h-10 w-10" />
                </a>
                <a href="https://www.linux.org/" target="_blank" class="tool-icon">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux" class="h-10 w-10" />
                </a>
                <a href="https://reactjs.org/" target="_blank" class="tool-icon">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React" class="h-10 w-10" />
                </a>
            </div>
        </section>

        <!-- GitHub Stats -->
        <section class="stats-card card rounded-lg shadow-lg p-6 mb-8">
            <h3 class="text-2xl font-semibold mb-4">My GitHub Stats</h3>
            <div class="flex flex-col sm:flex-row gap-4 justify-center flex-wrap">
                <img src="https://github-readme-stats.vercel.app/api/top-langs?username=irum-shah78&show_icons=true&locale=en&layout=compact&theme=dark" alt="Top Languages" class="max-w-full w-full sm:w-auto" />
                <img src="https://github-readme-stats.vercel.app/api?username=irum-shah78&show_icons=true&locale/en&theme=dark" alt="GitHub Stats" class="max-w-full w-full sm:w-auto" />
                <img src="https://github-readme-streak-stats.herokuapp.com/?user=irum-shah78&theme=dark" alt="GitHub Streak" class="max-w-full w-full sm:w-auto" />
            </div>
        </section>

        <!-- Footer -->
        <footer class="text-center py-6 border-t border-gray-400">
            <div class="flex justify-center items-center gap-4 mb-4">
                <p class="text-gray-200">© 2025 Irum Shahzadi | Frontend Developer | Pakistan</p>
                <img src="https://upload.wikimedia.org/wikipedia/commons/3/32/Flag_of_Pakistan.svg" alt="Pakistan Flag" class="h-8 w-12">
            </div>
            <p class="text-gray-200">Reach out at <a href="mailto:irums.dev@gmail.com" class="text-blue-200 hover:underline">irums.dev@gmail.com</a></p>
        </footer>
    </div>

    <!-- Back to Top Button -->
    <button id="back-to-top" onclick="window.scrollTo({top: 0, behavior: 'smooth'})">↑</button>

    <script>
        window.addEventListener('scroll', () => {
            const button = document.getElementById('back-to-top');
            button.style.display = window.scrollY > 300 ? 'block' : 'none';
        });
    </script>
</body>
</html>
