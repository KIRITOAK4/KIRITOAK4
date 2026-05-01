<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kirito | Portfolio</title>
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;700&family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #3b82f6;
            --bg-dark: #0f172a;
            --card-bg: #1e293b;
        }
        body {
            background-color: var(--bg-dark);
            color: #f8fafc;
            font-family: 'Inter', sans-serif;
        }
        .mono { font-family: 'JetBrains Mono', monospace; }
        .glass {
            background: rgba(30, 41, 59, 0.7);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        .glow:hover {
            box-shadow: 0 0 20px rgba(59, 130, 246, 0.4);
        }
        .animate-float {
            animation: float 3s ease-in-out infinite;
        }
        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }
    </style>
</head>
<body class="selection:bg-blue-500 selection:text-white">

    <!-- Progress Bar -->
    <div class="fixed top-0 left-0 w-full h-1 bg-blue-600 z-50"></div>

    <main class="max-w-4xl mx-auto px-6 py-12">
        
        <!-- Header Section -->
        <header class="text-center mb-16 animate-float">
            <a href="https://github.com/kiritoak4/Kiritoak4" target="_blank" class="inline-block">
                <h1 class="text-4xl md:text-6xl font-extrabold tracking-tighter mb-4">
                    Hᴇʏ Tʜᴇʀᴇ, Tʜɪs Is <span class="text-blue-500 mono">𝙆𝙄𝙍𝙄𝙏𝙊</span>
                </h1>
            </a>
            
            <div class="flex flex-col items-center gap-4">
                <div class="glass px-4 py-2 rounded-full text-sm flex items-center gap-3">
                    <span class="font-semibold text-blue-400">ᴠɪsɪᴛᴏʀs</span>
                    <img src="https://profile-counter.glitch.me/Kiritoak4/count.svg" alt="Visitor Count" class="h-6" />
                </div>
                
                <a href="https://t.me/YUITOAKASH" target="_blank" class="hover:scale-105 transition-transform">
                    <img src="https://img.shields.io/badge/ʏᴜɪᴛᴏᴀᴋᴀsʜ-Channel-blue?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Channel" />
                </a>
            </div>
        </header>

        <hr class="border-slate-800 mb-16">

        <!-- About Me Section -->
        <section class="mb-16">
            <div class="flex items-center gap-4 mb-8 justify-center">
                <div class="h-[1px] w-12 bg-blue-500"></div>
                <h2 class="text-2xl font-bold uppercase tracking-widest mono text-blue-400">ᴀʙᴏᴜᴛ ᴍᴇ</h2>
                <div class="h-[1px] w-12 bg-blue-500"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="glass p-8 rounded-2xl border-l-4 border-blue-500 hover:bg-slate-800/80 transition-all">
                    <ul class="space-y-4 text-lg">
                        <li class="flex items-center gap-3">
                            <span class="text-2xl">😁</span>
                            <span>A lazy person...</span>
                        </li>
                        <li class="flex items-center gap-3">
                            <span class="text-2xl">☹️</span>
                            <span>Nothing special...</span>
                        </li>
                        <li class="flex items-center gap-3">
                            <span class="text-2xl">❌</span>
                            <span class="text-red-400 font-semibold">DON'T KNOW CODING YET</span>
                        </li>
                    </ul>
                </div>
                <div class="glass p-8 rounded-2xl border-l-4 border-purple-500 hover:bg-slate-800/80 transition-all">
                    <ul class="space-y-4 text-lg">
                        <li class="flex items-center gap-3">
                            <span class="text-2xl">😎</span>
                            <span>Wants to learn coding...</span>
                        </li>
                        <li class="flex items-center gap-3">
                            <span class="text-2xl">😊</span>
                            <span>Interested in watching animes</span>
                        </li>
                        <li class="flex items-center gap-3">
                            <span class="text-2xl">💤</span>
                            <span>Sleeping often</span>
                        </li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- GitHub Stats Section -->
        <section class="mb-16">
            <div class="flex items-center gap-4 mb-8 justify-center">
                <div class="h-[1px] w-12 bg-green-500"></div>
                <h2 class="text-2xl font-bold uppercase tracking-widest mono text-green-400">GitHub Activity</h2>
                <div class="h-[1px] w-12 bg-green-500"></div>
            </div>

            <div class="flex flex-col gap-6 items-center">
                <img src="https://github-readme-stats.vercel.app/api?username=kiritoak4&show_icons=true&theme=tokyonight&hide_border=true&bg_color=1e293b" alt="GitHub Stats" class="w-full max-w-lg rounded-xl shadow-lg glow" />
                
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6 w-full">
                    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kiritoak4&layout=compact&theme=tokyonight&hide_border=true&bg_color=1e293b" alt="Top Languages" class="rounded-xl shadow-lg glow h-full object-cover" />
                    <img src="https://github-readme-streak-stats.herokuapp.com/?user=kiritoak4&theme=tokyonight&hide_border=true&background=1e293b" alt="GitHub Streak" class="rounded-xl shadow-lg glow h-full object-cover" />
                </div>
            </div>
        </section>

        <!-- Featured Projects Section -->
        <section class="mb-16">
            <div class="flex items-center gap-4 mb-8 justify-center">
                <div class="h-[1px] w-12 bg-pink-500"></div>
                <h2 class="text-2xl font-bold uppercase tracking-widest mono text-pink-400">Featured Projects</h2>
                <div class="h-[1px] w-12 bg-pink-500"></div>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-4 place-items-center">
                <img src="https://github-readme-stats.vercel.app/api/pin/?username=kiritoak4&repo=Kiritoak4&theme=tokyonight&bg_color=1e293b&hide_border=true" alt="Repo Card 1" class="w-full rounded-xl glow" />
                <a href="https://github.com/kiritoak4" class="glass w-full h-full flex items-center justify-center rounded-xl p-8 hover:bg-slate-800 transition-all border-dashed border-2 border-slate-700">
                    <div class="text-center">
                        <i class="fas fa-plus mb-2 text-2xl text-slate-500"></i>
                        <p class="text-slate-400 font-semibold">View More Repositories</p>
                    </div>
                </a>
            </div>
        </section>

        <!-- Skills Section -->
        <section class="mb-16">
            <div class="flex items-center gap-4 mb-8 justify-center">
                <div class="h-[1px] w-12 bg-yellow-500"></div>
                <h2 class="text-2xl font-bold uppercase tracking-widest mono text-yellow-400">✨ Skills & Interests ✨</h2>
                <div class="h-[1px] w-12 bg-yellow-500"></div>
            </div>

            <div class="flex flex-wrap justify-center gap-4">
                <!-- Tech Icons -->
                <div class="glass p-4 rounded-xl flex items-center gap-2 hover:text-orange-500 transition-colors">
                    <i class="fab fa-html5 text-2xl"></i> <span>HTML5</span>
                </div>
                <div class="glass p-4 rounded-xl flex items-center gap-2 hover:text-blue-400 transition-colors">
                    <i class="fab fa-css3-alt text-2xl"></i> <span>CSS3</span>
                </div>
                <div class="glass p-4 rounded-xl flex items-center gap-2 hover:text-yellow-400 transition-colors">
                    <i class="fab fa-js text-2xl"></i> <span>JavaScript</span>
                </div>
                <div class="glass p-4 rounded-xl flex items-center gap-2 hover:text-blue-500 transition-colors">
                    <i class="fab fa-python text-2xl"></i> <span>Python</span>
                </div>
                <div class="glass p-4 rounded-xl flex items-center gap-2 hover:text-purple-500 transition-colors">
                    <i class="fab fa-github text-2xl"></i> <span>GitHub Ops</span>
                </div>
                <div class="glass p-4 rounded-xl flex items-center gap-2 hover:text-red-500 transition-colors">
                    <i class="fas fa-tv text-2xl"></i> <span>Anime Tracking</span>
                </div>
            </div>
        </section>

        <!-- Footer -->
        <footer class="text-center text-slate-500 pt-8 border-t border-slate-800">
            <p class="mono text-sm">Designed with 💙 for Kiritoak4</p>
            <div class="mt-4 flex justify-center gap-6">
                <a href="https://github.com/kiritoak4" class="hover:text-white transition-colors"><i class="fab fa-github text-xl"></i></a>
                <a href="https://t.me/YUITOAKASH" class="hover:text-white transition-colors"><i class="fab fa-telegram text-xl"></i></a>
            </div>
        </footer>

    </main>

    <script>
        // Optional: Add a simple scroll animation or interactive elements
        document.querySelectorAll('a').forEach(anchor => {
            anchor.addEventListener('mouseenter', () => {
                // Interaction logic could go here
            });
        });
    </script>
</body>
</html>
