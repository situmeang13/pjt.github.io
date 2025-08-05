<!DOCTYPE html>
<html lang="id">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Beranda - PJT Teknisi Listrik & Elektronik</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>

<body class="bg-gray-50 text-gray-800 font-sans">

    <header class="bg-white shadow-md p-6 sticky top-0 z-50">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="text-2xl font-bold text-blue-900">🔌 PJT Teknisi</h1>
            <nav class="space-x-4 hidden md:block">
                <a href="#beranda" class="text-gray-600 hover:text-blue-700 transition duration-300">Beranda</a>
                <a href="#tentang" class="text-gray-600 hover:text-blue-700 transition duration-300">Tentang</a>
                <a href="#layanan" class="text-gray-600 hover:text-blue-700 transition duration-300">Layanan</a>
                <a href="#kontak" class="text-gray-600 hover:text-blue-700 transition duration-300">Kontak</a>
            </nav>
            <button class="md:hidden text-gray-600 focus:outline-none">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7" />
                </svg>
            </button>
        </div>
    </header>

    <main class="container mx-auto p-8">

        <section id="beranda" class="text-center py-20 bg-blue-700 text-white rounded-xl shadow-lg relative overflow-hidden">
            <div class="absolute inset-0 bg-blue-800 opacity-20"></div>
            <div class="relative z-10">
                <h2 class="text-4xl md:text-5xl font-extrabold mb-4 animate-fade-in">Solusi Lengkap untuk Rumah dan Properti Anda ⚡</h2>
                <p class="text-lg mb-6">Layanan profesional di bidang kelistrikan, elektronik, dan perbaikan rumah.</p>
                <a href="#kontak" class="bg-yellow-400 text-blue-900 font-semibold px-8 py-3 rounded-full shadow-lg hover:bg-yellow-500 transition-all duration-300 ease-in-out transform hover:scale-105 inline-block animate-bounce-slow">Hubungi Sekarang</a>
            </div>
        </section>

        <section id="layanan" class="mt-20">
            <h3 class="text-3xl font-bold text-center mb-12 text-blue-900">Layanan Kami</h3>
            <div class="grid lg:grid-cols-3 md:grid-cols-2 gap-10">

                <div class="bg-white p-8 rounded-xl shadow-lg hover:shadow-2xl transition-shadow duration-300">
                    <div class="text-blue-700 mb-6 text-4xl text-center">
                        <i class="fas fa-blender"></i>
                    </div>
                    <h4 class="font-bold text-2xl mb-4 text-blue-900 text-center">Elektronik Rumah Tangga</h4>
                    <ul class="list-disc list-inside space-y-2 text-gray-600">
                        <li>Cuci AC, Service AC, Bongkar pasang AC</li>
                        <li>Perbaikan AC tidak dingin atau AC menetes</li>
                        <li>Perbaikan Kulkas (tidak dingin, kulkas beku, dan masalah lainnya)</li>
                        <li>Perbaikan Mesin Cuci</li>
                        <li>Perbaikan Setrika</li>
                        <li>Perbaikan Dispenser</li>
                        <li>Perbaikan Pemanas Air Mandi</li>
                        <li>Perbaikan Blender, Slow Juicer, & Juicer</li>
                        <li>Perbaikan Kipas Angin & Blower</li>
                    </ul>
                </div>

                <div class="bg-white p-8 rounded-xl shadow-lg hover:shadow-2xl transition-shadow duration-300">
                    <div class="text-blue-700 mb-6 text-4xl text-center">
                        <i class="fas fa-bolt"></i>
                    </div>
                    <h4 class="font-bold text-2xl mb-4 text-blue-900 text-center">Kelistrikan & Mesin</h4>
                    <ul class="list-disc list-inside space-y-2 text-gray-600">
                        <li>Instalasi listrik</li>
                        <li>Gulung Dinamo, Perbaiki Electro Motor, Dinamo Cas, & Dinamo Starter</li>
                        <li>Perbaikan Genset & Pasang ARP Genset</li>
                        <li>Perbaikan Pompa Air</li>
                        <li>Pasang Penangkal Petir</li>
                    </ul>
                </div>

                <div class="bg-white p-8 rounded-xl shadow-lg hover:shadow-2xl transition-shadow duration-300">
                    <div class="text-blue-700 mb-6 text-4xl text-center">
                        <i class="fas fa-tools"></i>
                    </div>
                    <h4 class="font-bold text-2xl mb-4 text-blue-900 text-center">Bangunan & Properti</h4>
                    <ul class="list-disc list-inside space-y-2 text-gray-600">
                        <li>Pemasangan Molding Ruangan </li>
                        <li>Pasang Pipa Air</li>
                        <li>Pemasangan Pintu Remote Pagar</li>
                        <li>Pengecatan (atap dan tembok rumah)</li>
                        <li>Perbaikan Closed Tersumbat</li>
                    </ul>
                </div>

            </div>
        </section>
        
        <section id="tentang" class="mt-20 text-center max-w-3xl mx-auto p-10 bg-gray-100 rounded-xl shadow-lg">
            <h3 class="text-3xl font-bold mb-4 text-blue-900">Tentang Saya</h3>
            <p class="text-gray-700 leading-relaxed">Saya adalah teknisi profesional dengan pengalaman lebih dari 5 tahun. Menguasai instalasi listrik, perbaikan alat elektronik rumah tangga, dan perbaikan bangunan sederhana. Saya siap memberikan solusi terbaik untuk kebutuhan Anda. Keamanan, kecepatan, dan kepuasan pelanggan adalah prioritas utama saya.</p>
        </section>

        <section id="kontak" class="mt-20 text-center p-10 bg-blue-900 text-white rounded-xl shadow-lg">
            <h3 class="text-3xl font-bold mb-4">Hubungi Kami</h3>
            <p class="mb-2">📞 0852-7406-2920</p>
            <p class="mb-2">📧 email@pjt-teknisi.com</p>
            <p>📍 Jl. Listrik Nasional No.99, Malang</p>
        </section>
    </main>

    <footer class="mt-20 p-6 text-center text-sm bg-gray-800 text-gray-300">
        &copy; 2025 PJT Teknisi Listrik.
    </footer>
</body>

</html>
