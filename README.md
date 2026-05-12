<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lolpop | Sweet Projects</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        .lollipop-gradient {
            background: linear-gradient(45deg, #ff9a9e 0%, #fad0c4 99%, #fad0c4 100%);
        }
        .float { animation: floating 3s ease-in-out infinite; }
        @keyframes floating {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }
    </style>
</head>
<body class="lollipop-gradient min-h-screen flex flex-col items-center justify-center text-white font-sans">
    
    <div class="text-center p-10 bg-white/20 backdrop-blur-md rounded-3xl shadow-2xl border border-white/30 float">
        <h1 class="text-6xl font-black mb-4 drop-shadow-lg">🍭 lolpop</h1>
        <p class="text-xl font-medium mb-8">Making the web a little bit sweeter.</p>
        
        <div class="flex gap-4 justify-center">
            <button class="bg-white text-pink-500 px-8 py-3 rounded-full font-bold hover:bg-pink-100 transition-all shadow-lg">
                Explore Dex
            </button>
            <button class="bg-transparent border-2 border-white px-8 py-3 rounded-full font-bold hover:bg-white hover:text-pink-500 transition-all">
                Documentation
            </button>
        </div>
    </div>

    <footer class="absolute bottom-10 text-white/70 text-sm">
        © 2026 Lolpop Project • Built with ✨
    </footer>

</body>
</html># lolpop
