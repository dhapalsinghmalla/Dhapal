<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modern Portfolio | 6n6 Style</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; background-color: #0f172a; color: #f8fafc; }
        .bento-card {
            background: rgba(30, 41, 59, 0.7);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .bento-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.3);
            border-color: rgba(255, 255, 255, 0.2);
        }
        .gradient-text {
            background: linear-gradient(to right, #38bdf8, #818cf8);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
    </style>
</head>
<body class="p-4 md:p-8 lg:p-12">

    <!-- Navigation -->
    <nav class="flex justify-between items-center mb-12">
        <div class="text-2xl font-bold tracking-tighter">6n6<span class="text-sky-400">.</span></div>
        <div class="space-x-6 text-sm font-medium text-slate-400">
            <a href="#" class="hover:text-white transition">Work</a>
            <a href="#" class="hover:text-white transition">About</a>
            <a href="#" class="hover:text-white transition">Contact</a>
        </div>
    </nav>

    <!-- Bento Grid Layout -->
    <main class="max-w-6xl mx-auto grid grid-cols-1 md:grid-cols-4 gap-4">
        
        <!-- Hero Section -->
        <div class="md:col-span-3 bento-card rounded-3xl p-8 flex flex-col justify-center min-h-[300px]">
            <h1 class="text-4xl md:text-6xl font-bold mb-4">I create <span class="gradient-text">digital experiences</span> that matter.</h1>
            <p class="text-slate-400 text-lg max-w-xl">Creative Developer & Designer specializing in building clean, functional, and aesthetic web solutions.</p>
        </div>

        <!-- Profile/Availability -->
        <div class="md:col-span-1 bento-card rounded-3xl p-8 flex flex-col items-center justify-center text-center">
            <div class="w-24 h-24 bg-gradient-to-br from-sky-400 to-indigo-500 rounded-full mb-4 shadow-lg shadow-sky-500/20"></div>
            <div class="flex items-center gap-2 text-xs font-semibold text-emerald-400 bg-emerald-400/10 px-3 py-1 rounded-full mb-2">
                <span class="w-2 h-2 bg-emerald-400 rounded-full animate-pulse"></span> Available for work
            </div>
            <p class="font-bold">Based in Earth</p>
        </div>

        <!-- Project 1 -->
        <div class="md:col-span-2 bento-card rounded-3xl overflow-hidden group">
            <div class="h-48 bg-slate-800 flex items-center justify-center group-hover:bg-slate-700 transition">
                <span class="text-slate-500 font-mono">Project Preview 01</span>
            </div>
            <div class="p-6">
                <h3 class="font-bold text-xl mb-1">Brand Identity</h3>
                <p class="text-slate-400 text-sm">Visual design for a tech startup.</p>
            </div>
        </div>

        <!-- Project 2 -->
        <div class="md:col-span-2 bento-card rounded-3xl overflow-hidden group">
            <div class="h-48 bg-slate-800 flex items-center justify-center group-hover:bg-slate-700 transition">
                <span class="text-slate-500 font-mono">Project Preview 02</span>
            </div>
            <div class="p-6">
                <h3 class="font-bold text-xl mb-1">Mobile App UI</h3>
                <p class="text-slate-400 text-sm">Minimalist interface for a fitness app.</p>
            </div>
        </div>

        <!-- Skills -->
        <div class="md:col-span-2 bento-card rounded-3xl p-8">
            <h3 class="text-xl font-bold mb-4">Stack</h3>
            <div class="flex flex-wrap gap-2">
                <span class="bg-slate-800 px-4 py-2 rounded-xl text-sm border border-slate-700">React</span>
                <span class="bg-slate-800 px-4 py-2 rounded-xl text-sm border border-slate-700">Tailwind</span>
                <span class="bg-slate-800 px-4 py-2 rounded-xl text-sm border border-slate-700">Figma</span>
                <span class="bg-slate-800 px-4 py-2 rounded-xl text-sm border border-slate-700">Node.js</span>
                <span class="bg-slate-800 px-4 py-2 rounded-xl text-sm border border-slate-700">Python</span>
            </div>
        </div>

        <!-- Contact/Socials -->
        <div class="md:col-span-2 bento-card rounded-3xl p-8 flex flex-col justify-between">
            <h3 class="text-xl font-bold">Let's connect</h3>
            <div class="flex gap-4 mt-6">
                <a href="#" class="w-12 h-12 bg-slate-800 rounded-2xl flex items-center justify-center hover:bg-sky-500 transition">𝕏</a>
                <a href="#" class="w-12 h-12 bg-slate-800 rounded-2xl flex items-center justify-center hover:bg-pink-500 transition">IG</a>
                <a href="#" class="w-12 h-12 bg-slate-800 rounded-2xl flex items-center justify-center hover:bg-indigo-600 transition">LI</a>
                <a href="mailto:hello@6n6.com" class="flex-1 bg-white text-black font-bold rounded-2xl flex items-center justify-center hover:bg-slate-200 transition">Email Me</a>
            </div>
        </div>

    </main>

    <footer class="text-center mt-12 text-slate-500 text-sm">
        &copy; 2026 6n6 Portfolio. Inspired by Canva Design.
    </footer>

</body>
</html>
