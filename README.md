<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TopUpGamer | Cepat, Murah, Aman</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        body { background-color: #0f172a; color: white; }
        .game-card:hover { transform: translateY(-5px); transition: 0.3s; }
    </style>
</head>
<body>

    <nav class="bg-slate-900 border-b border-slate-800 p-4 sticky top-0 z-50">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl font-bold text-blue-500 tracking-tighter">TOPUP<span class="text-white">GAMER</span></h1>
            <div class="space-x-6 hidden md:flex">
                <a href="#" class="hover:text-blue-400">Home</a>
                <a href="#" class="hover:text-blue-400">Cek Pesanan</a>
                <a href="#" class="hover:text-blue-400">Promo</a>
            </div>
            <button class="bg-blue-600 hover:bg-blue-700 px-5 py-2 rounded-lg font-semibold">Login</button>
        </div>
    </nav>

    <header class="container mx-auto mt-10 px-4 text-center">
        <div class="bg-gradient-to-r from-blue-600 to-purple-600 p-10 rounded-3xl shadow-2xl">
            <h2 class="text-4xl md:text-5xl font-extrabold mb-4">Top Up Game Tercepat di Jagat Raya</h2>
            <p class="text-lg opacity-90">Dapatkan harga termurah untuk game favoritmu. Open 24 Jam!</p>
        </div>
    </header>

    <main class="container mx-auto my-12 px-4">
        <h3 class="text-2xl font-bold mb-8 flex items-center">
            <i class="fas fa-fire text-orange-500 mr-3"></i> Game Populer
        </h3>
        
        <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-5 gap-6">
            
            <div class="game-card bg-slate-800 rounded-2xl overflow-hidden shadow-lg cursor-pointer">
                <img src="https://via.placeholder.com/300x400/2563eb/ffffff?text=Mobile+Legends" alt="MLBB" class="w-full h-48 object-cover">
                <div class="p-4">
                    <h4 class="font-bold text-center">Mobile Legends</h4>
                    <p class="text-xs text-slate-400 text-center mt-1">Moonton</p>
                    <button class="w-full mt-4 bg-slate-700 hover:bg-blue-600 py-2 rounded-lg text-sm transition">Top Up</button>
                </div>
            </div>

            <div class="game-card bg-slate-800 rounded-2xl overflow-hidden shadow-lg cursor-pointer">
                <img src="https://via.placeholder.com/300x400/dc2626/ffffff?text=Free+Fire" alt="FF" class="w-full h-48 object-cover">
                <div class="p-4">
                    <h4 class="font-bold text-center">Free Fire</h4>
                    <p class="text-xs text-slate-400 text-center mt-1">Garena</p>
                    <button class="w-full mt-4 bg-slate-700 hover:bg-blue-600 py-2 rounded-lg text-sm transition">Top Up</button>
                </div>
            </div>

            <div class="game-card bg-slate-800 rounded-2xl overflow-hidden shadow-lg cursor-pointer">
                <img src="https://via.placeholder.com/300x400/10b981/ffffff?text=Genshin+Impact" alt="Genshin" class="w-full h-48 object-cover">
                <div class="p-4">
                    <h4 class="font-bold text-center">Genshin Impact</h4>
                    <p class="text-xs text-slate-400 text-center mt-1">HoYoverse</p>
                    <button class="w-full mt-4 bg-slate-700 hover:bg-blue-600 py-2 rounded-lg text-sm transition">Top Up</button>
                </div>
            </div>

            <div class="game-card bg-slate-800 rounded-2xl overflow-hidden shadow-lg cursor-pointer">
                <img src="https://via.placeholder.com/300x400/f59e0b/ffffff?text=PUBG+Mobile" alt="PUBGM" class="w-full h-48 object-cover">
                <div class="p-4">
                    <h4 class="font-bold text-center">PUBG Mobile</h4>
                    <p class="text-xs text-slate-400 text-center mt-1">Tencent</p>
                    <button class="w-full mt-4 bg-slate-700 hover:bg-blue-600 py-2 rounded-lg text-sm transition">Top Up</button>
                </div>
            </div>

            <div class="game-card bg-slate-800 rounded-2xl overflow-hidden shadow-lg cursor-pointer">
                <img src="https://via.placeholder.com/300x400/6366f1/ffffff?text=Valorant" alt="Valorant" class="w-full h-48 object-cover">
                <div class="p-4">
                    <h4 class="font-bold text-center">Valorant</h4>
                    <p class="text-xs text-slate-400 text-center mt-1">Riot Games</p>
                    <button class="w-full mt-4 bg-slate-700 hover:bg-blue-600 py-2 rounded-lg text-sm transition">Top Up</button>
                </div>
            </div>

        </div>
    </main>

    <footer class="bg-slate-900 border-t border-slate-800 mt-20 py-10">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-xl font-bold text-blue-500 mb-4">TOPUPGAMER</h2>
            <p class="text-slate-400 text-sm mb-6">Metode pembayaran terlengkap: QRIS, E-Wallet, & Bank Transfer.</p>
            <div class="flex justify-center space-x-4 mb-6">
                <i class="fab fa-instagram text-2xl hover:text-pink-500 cursor-pointer"></i>
                <i class="fab fa-whatsapp text-2xl hover:text-green-500 cursor-pointer"></i>
                <i class="fab fa-tiktok text-2xl hover:text-white cursor-pointer"></i>
            </div>
            <p class="text-slate-500 text-xs">&copy; 2026 TopUpGamer. All Rights Reserved.</p>
        </div>
    </footer>

</body>
</html>
