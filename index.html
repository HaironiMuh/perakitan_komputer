<!doctype html>
<html lang="id">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perakitan Komputer Interaktif</title>
    <script src="/_sdk/element_sdk.js"></script>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            background-attachment: fixed;
        }

        * {
            box-sizing: border-box;
        }

        .gradient-bg {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            position: relative;
            overflow: hidden;
        }

        .gradient-bg::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255, 255, 255, 0.1) 0%, transparent 70%);
            animation: float 20s infinite ease-in-out;
        }

        @keyframes float {

            0%,
            100% {
                transform: translate(0, 0) rotate(0deg);
            }

            33% {
                transform: translate(30px, -30px) rotate(120deg);
            }

            66% {
                transform: translate(-20px, 20px) rotate(240deg);
            }
        }

        .component-card {
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            cursor: grab;
            position: relative;
            overflow: hidden;
        }

        .component-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.3), transparent);
            transition: left 0.5s;
        }

        .component-card:hover::before {
            left: 100%;
        }

        .component-card:hover {
            transform: translateY(-10px) scale(1.05);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
        }

        .component-card:active {
            cursor: grabbing;
            transform: scale(0.95);
        }

        .drop-zone {
            transition: all 0.4s ease;
            border: 3px dashed #cbd5e0;
            position: relative;
            background: linear-gradient(145deg, #ffffff, #f3f4f6);
        }

        .drop-zone::after {
            content: '↓';
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 48px;
            opacity: 0;
            color: #48bb78;
            transition: all 0.3s ease;
        }

        .drop-zone.highlight {
            border-color: #48bb78;
            background: linear-gradient(145deg, rgba(72, 187, 120, 0.1), rgba(72, 187, 120, 0.2));
            transform: scale(1.05);
            box-shadow: 0 10px 30px rgba(72, 187, 120, 0.3);
        }

        .drop-zone.highlight::after {
            opacity: 1;
            animation: bounce 0.6s infinite;
        }

        @keyframes bounce {

            0%,
            100% {
                transform: translate(-50%, -50%) translateY(0);
            }

            50% {
                transform: translate(-50%, -50%) translateY(10px);
            }
        }

        .drop-zone.filled {
            border-color: #48bb78;
            border-style: solid;
            background: linear-gradient(145deg, #d1fae5, #a7f3d0);
            animation: successPulse 0.6s ease;
        }

        @keyframes successPulse {
            0% {
                transform: scale(1);
            }

            50% {
                transform: scale(1.1);
            }

            100% {
                transform: scale(1);
            }
        }

        .pulse-animation {
            animation: pulse 2s infinite;
        }

        @keyframes pulse {

            0%,
            100% {
                opacity: 1;
                transform: scale(1);
            }

            50% {
                opacity: 0.8;
                transform: scale(1.05);
            }
        }

        .tab-button {
            transition: all 0.3s ease;
            position: relative;
        }

        .tab-button::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 0;
            height: 3px;
            background: #667eea;
            transition: width 0.3s ease;
        }

        .tab-button:hover::after {
            width: 100%;
        }

        .tab-button.active::after {
            width: 100%;
        }

        .tab-button.active {
            color: #667eea;
        }

        .info-card {
            transition: all 0.3s ease;
            background: linear-gradient(145deg, #ffffff, #f9fafb);
        }

        .info-card:hover {
            transform: translateY(-5px) rotate(1deg);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.15);
        }

        .step-card {
            transition: all 0.3s ease;
            animation: slideIn 0.5s ease backwards;
        }

        .step-card:hover {
            transform: translateX(10px);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
        }

        @keyframes slideIn {
            from {
                opacity: 0;
                transform: translateX(-30px);
            }

            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        .step-card:nth-child(1) {
            animation-delay: 0.1s;
        }

        .step-card:nth-child(2) {
            animation-delay: 0.2s;
        }

        .step-card:nth-child(3) {
            animation-delay: 0.3s;
        }

        .step-card:nth-child(4) {
            animation-delay: 0.4s;
        }

        .step-card:nth-child(5) {
            animation-delay: 0.5s;
        }

        .step-card:nth-child(6) {
            animation-delay: 0.6s;
        }

        .step-card:nth-child(7) {
            animation-delay: 0.7s;
        }

        .step-card:nth-child(8) {
            animation-delay: 0.8s;
        }

        .step-card:nth-child(9) {
            animation-delay: 0.9s;
        }

        .celebration {
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%) scale(0);
            background: white;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            z-index: 1000;
            display: none;
            transition: transform 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }

        .celebration.show {
            display: block;
            animation: popIn 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275) forwards;
        }

        @keyframes popIn {
            to {
                transform: translate(-50%, -50%) scale(1);
            }
        }

        .overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.7);
            z-index: 999;
            display: none;
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        .overlay.show {
            display: block;
            animation: fadeIn 0.3s ease forwards;
        }

        @keyframes fadeIn {
            to {
                opacity: 1;
            }
        }

        .confetti {
            position: fixed;
            width: 10px;
            height: 10px;
            background: #f39c12;
            z-index: 1001;
            animation: confettiFall 3s ease-out forwards;
        }

        @keyframes confettiFall {
            to {
                transform: translateY(100vh) rotate(360deg);
                opacity: 0;
            }
        }

        .progress-bar {
            height: 8px;
            background: #e5e7eb;
            border-radius: 10px;
            overflow: hidden;
            position: relative;
        }

        .progress-fill {
            height: 100%;
            background: linear-gradient(90deg, #667eea, #48bb78);
            transition: width 0.5s ease;
            position: relative;
            overflow: hidden;
        }

        .progress-fill::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.3), transparent);
            animation: shimmer 1.5s infinite;
        }

        @keyframes shimmer {
            0% {
                transform: translateX(-100%);
            }

            100% {
                transform: translateX(100%);
            }
        }

        .floating {
            animation: floating 3s ease-in-out infinite;
        }

        @keyframes floating {

            0%,
            100% {
                transform: translateY(0px);
            }

            50% {
                transform: translateY(-20px);
            }
        }

        .glow {
            box-shadow: 0 0 20px rgba(102, 126, 234, 0.5);
            animation: glow 2s ease-in-out infinite;
        }

        @keyframes glow {

            0%,
            100% {
                box-shadow: 0 0 20px rgba(102, 126, 234, 0.5);
            }

            50% {
                box-shadow: 0 0 30px rgba(102, 126, 234, 0.8);
            }
        }
    </style>
    <style>
        @view-transition {
            navigation: auto;
        }
    </style>
    <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
</head>

<body>
    <div id="app" style="width: 100%; min-height: 100%;"><!-- Header -->
        <header class="gradient-bg text-white py-8 px-6">
            <div class="max-w-6xl mx-auto">
                <h1 id="main-title" class="text-5xl font-bold mb-3">🖥️ Perakitan Komputer Interaktif</h1>
                <p id="subtitle" class="text-xl opacity-90">Belajar Merakit Komputer dengan Cara yang Menyenangkan!</p>
            </div>
        </header><!-- Tab Navigation -->
        <div class="bg-white shadow-md">
            <div class="max-w-6xl mx-auto px-6">
                <div class="flex flex-wrap gap-4"><button class="tab-button active py-4 px-2 text-lg font-semibold" data-tab="materi"> 📚 Materi </button> <button class="tab-button py-4 px-2 text-lg font-semibold" data-tab="langkah"> 🔧 Langkah Perakitan </button> <button class="tab-button py-4 px-2 text-lg font-semibold" data-tab="tips"> ⚠️ Tips &amp; K3LH </button> <button class="tab-button py-4 px-2 text-lg font-semibold" data-tab="game"> 🎮 Game Perakitan </button>
                </div>
            </div>
        </div><!-- Content Area -->
        <main class="max-w-6xl mx-auto px-6 py-8"><!-- Materi Tab -->
            <div id="materi-tab" class="tab-content">
                <div class="grid md:grid-cols-2 gap-6"><!-- Komponen 1 -->
                    <div class="info-card bg-white rounded-xl shadow-lg p-6 hover:shadow-xl cursor-pointer border-2 border-transparent hover:border-purple-400">
                        <div class="text-5xl mb-4 floating">
                            💾
                        </div>
                        <h3 class="text-2xl font-bold mb-3 text-gray-800">Motherboard</h3>
                        <p class="text-gray-600 mb-3">Papan sirkuit utama yang menghubungkan semua komponen komputer. Motherboard adalah fondasi dari sistem komputer.</p>
                        <ul class="text-sm text-gray-600 space-y-1">
                            <li>• Socket CPU untuk prosesor</li>
                            <li>• Slot RAM untuk memori</li>
                            <li>• Slot PCIe untuk kartu ekspansi</li>
                        </ul>
                    </div><!-- Komponen 2 -->
                    <div class="info-card bg-white rounded-xl shadow-lg p-6 hover:shadow-xl cursor-pointer border-2 border-transparent hover:border-blue-400">
                        <div class="text-5xl mb-4 floating" style="animation-delay: 0.5s;">
                            ⚡
                        </div>
                        <h3 class="text-2xl font-bold mb-3 text-gray-800">Processor (CPU)</h3>
                        <p class="text-gray-600 mb-3">Otak komputer yang memproses semua instruksi dan perhitungan. Kecepatan CPU diukur dalam GHz.</p>
                        <ul class="text-sm text-gray-600 space-y-1">
                            <li>• Menjalankan program dan aplikasi</li>
                            <li>• Multi-core untuk multitasking</li>
                            <li>• Membutuhkan pendingin</li>
                        </ul>
                    </div><!-- Komponen 3 -->
                    <div class="info-card bg-white rounded-xl shadow-lg p-6 hover:shadow-xl cursor-pointer border-2 border-transparent hover:border-green-400">
                        <div class="text-5xl mb-4 floating" style="animation-delay: 1s;">
                            🎴
                        </div>
                        <h3 class="text-2xl font-bold mb-3 text-gray-800">RAM (Memory)</h3>
                        <p class="text-gray-600 mb-3">Memori sementara untuk menyimpan data yang sedang diproses. Lebih besar RAM = lebih cepat multitasking.</p>
                        <ul class="text-sm text-gray-600 space-y-1">
                            <li>• DDR4 atau DDR5</li>
                            <li>• Kapasitas 8GB, 16GB, 32GB</li>
                            <li>• Frekuensi tinggi = performa baik</li>
                        </ul>
                    </div><!-- Komponen 4 -->
                    <div class="info-card bg-white rounded-xl shadow-lg p-6 hover:shadow-xl cursor-pointer border-2 border-transparent hover:border-yellow-400">
                        <div class="text-5xl mb-4 floating" style="animation-delay: 1.5s;">
                            💿
                        </div>
                        <h3 class="text-2xl font-bold mb-3 text-gray-800">Storage (HDD/SSD)</h3>
                        <p class="text-gray-600 mb-3">Penyimpanan permanen untuk sistem operasi, program, dan file. SSD lebih cepat dari HDD.</p>
                        <ul class="text-sm text-gray-600 space-y-1">
                            <li>• SSD: Cepat, tanpa suara</li>
                            <li>• HDD: Kapasitas besar, murah</li>
                            <li>• NVMe: SSD tercepat</li>
                        </ul>
                    </div><!-- Komponen 5 -->
                    <div class="info-card bg-white rounded-xl shadow-lg p-6 hover:shadow-xl cursor-pointer border-2 border-transparent hover:border-red-400">
                        <div class="text-5xl mb-4 floating" style="animation-delay: 2s;">
                            🎨
                        </div>
                        <h3 class="text-2xl font-bold mb-3 text-gray-800">VGA Card (GPU)</h3>
                        <p class="text-gray-600 mb-3">Kartu grafis untuk rendering gambar, video, dan gaming. GPU punya memori VRAM sendiri.</p>
                        <ul class="text-sm text-gray-600 space-y-1">
                            <li>• Penting untuk gaming dan editing</li>
                            <li>• NVIDIA atau AMD</li>
                            <li>• VRAM 4GB, 8GB, 12GB+</li>
                        </ul>
                    </div><!-- Komponen 6 -->
                    <div class="info-card bg-white rounded-xl shadow-lg p-6 hover:shadow-xl cursor-pointer border-2 border-transparent hover:border-orange-400">
                        <div class="text-5xl mb-4 floating" style="animation-delay: 2.5s;">
                            🔌
                        </div>
                        <h3 class="text-2xl font-bold mb-3 text-gray-800">Power Supply (PSU)</h3>
                        <p class="text-gray-600 mb-3">Menyuplai daya listrik ke semua komponen. Wattage harus cukup untuk semua komponen.</p>
                        <ul class="text-sm text-gray-600 space-y-1">
                            <li>• 80+ Bronze, Silver, Gold</li>
                            <li>• Modular atau Non-modular</li>
                            <li>• 500W, 650W, 750W+</li>
                        </ul>
                    </div>
                </div>
            </div><!-- Langkah Perakitan Tab -->
            <div id="langkah-tab" class="tab-content" style="display: none;">
                <div class="bg-white rounded-xl shadow-lg p-6 mb-6">
                    <h2 class="text-3xl font-bold mb-4 text-gray-800">🔧 Langkah-Langkah Perakitan Komputer</h2>
                    <p class="text-gray-600 mb-6">Ikuti langkah-langkah berikut dengan teliti untuk merakit komputer dengan benar dan aman.</p>
                </div>
                <div class="space-y-6"><!-- Langkah 1 -->
                    <div class="step-card bg-white rounded-xl shadow-lg p-6 border-l-4 border-purple-500">
                        <div class="flex items-start">
                            <div class="bg-purple-500 text-white rounded-full w-12 h-12 flex items-center justify-center font-bold text-xl mr-4 flex-shrink-0">
                                1
                            </div>
                            <div class="flex-1">
                                <h3 class="text-2xl font-bold mb-3 text-gray-800">Persiapan dan Peralatan</h3>
                                <ul class="space-y-2 text-gray-700">
                                    <li class="flex items-start"><span class="text-purple-500 mr-2">✓</span> <span>Siapkan meja kerja yang bersih, luas, dan memiliki pencahayaan yang cukup</span></li>
                                    <li class="flex items-start"><span class="text-purple-500 mr-2">✓</span> <span>Gunakan gelang anti-statis atau sentuh permukaan logam untuk membuang muatan listrik statis</span></li>
                                    <li class="flex items-start"><span class="text-purple-500 mr-2">✓</span> <span>Siapkan obeng (+) dan (-), tang, thermal paste, dan kabel ties</span></li>
                                    <li class="flex items-start"><span class="text-purple-500 mr-2">✓</span> <span>Baca manual motherboard dan komponen lainnya</span></li>
                                    <li class="flex items-start"><span class="text-purple-500 mr-2">✓</span> <span>Pastikan semua komponen kompatibel (socket CPU, tipe RAM, ukuran casing)</span></li>
                                </ul>
                            </div>
                        </div>
                    </div><!-- Langkah 2 -->
                    <div class="step-card bg-white rounded-xl shadow-lg p-6 border-l-4 border-blue-500">
                        <div class="flex items-start">
                            <div class="bg-blue-500 text-white rounded-full w-12 h-12 flex items-center justify-center font-bold text-xl mr-4 flex-shrink-0">
                                2
                            </div>
                            <div class="flex-1">
                                <h3 class="text-2xl font-bold mb-3 text-gray-800">Pasang Power Supply (PSU)</h3>
                                <ul class="space-y-2 text-gray-700">
                                    <li class="flex items-start"><span class="text-blue-500 mr-2">✓</span> <span>Pasang PSU di bagian bawah atau atas casing sesuai desain casing</span></li>
                                    <li class="flex items-start"><span class="text-blue-500 mr-2">✓</span> <span>Posisikan kipas PSU menghadap ke luar untuk sirkulasi udara yang baik</span></li>
                                    <li class="flex items-start"><span class="text-blue-500 mr-2">✓</span> <span>Kencangkan dengan 4 baut yang disediakan</span></li>
                                    <li class="flex items-start"><span class="text-blue-500 mr-2">✓</span> <span>Pastikan switch PSU dalam posisi OFF (O) selama perakitan</span></li>
                                </ul>
                            </div>
                        </div>
                    </div><!-- Langkah 3 -->
                    <div class="step-card bg-white rounded-xl shadow-lg p-6 border-l-4 border-green-500">
                        <div class="flex items-start">
                            <div class="bg-green-500 text-white rounded-full w-12 h-12 flex items-center justify-center font-bold text-xl mr-4 flex-shrink-0">
                                3
                            </div>
                            <div class="flex-1">
                                <h3 class="text-2xl font-bold mb-3 text-gray-800">Pasang I/O Shield dan Motherboard</h3>
                                <ul class="space-y-2 text-gray-700">
                                    <li class="flex items-start"><span class="text-green-500 mr-2">✓</span> <span>Pasang I/O shield (pelat logam) di bagian belakang casing dengan menekan hingga klik</span></li>
                                    <li class="flex items-start"><span class="text-green-500 mr-2">✓</span> <span>Pasang standoff (tiang penyangga) pada casing sesuai lubang motherboard</span></li>
                                    <li class="flex items-start"><span class="text-green-500 mr-2">✓</span> <span>Letakkan motherboard dengan hati-hati, sejajarkan dengan I/O shield</span></li>
                                    <li class="flex items-start"><span class="text-green-500 mr-2">✓</span> <span>Kencangkan baut motherboard secara menyilang (jangan terlalu kencang)</span></li>
                                    <li class="flex items-start"><span class="text-green-500 mr-2">✓</span> <span><strong>PENTING:</strong> Jangan paksa motherboard, pastikan tidak ada standoff yang salah posisi</span></li>
                                </ul>
                            </div>
                        </div>
                    </div><!-- Langkah 4 -->
                    <div class="step-card bg-white rounded-xl shadow-lg p-6 border-l-4 border-yellow-500">
                        <div class="flex items-start">
                            <div class="bg-yellow-500 text-white rounded-full w-12 h-12 flex items-center justify-center font-bold text-xl mr-4 flex-shrink-0">
                                4
                            </div>
                            <div class="flex-1">
                                <h3 class="text-2xl font-bold mb-3 text-gray-800">Pasang Processor (CPU)</h3>
                                <ul class="space-y-2 text-gray-700">
                                    <li class="flex items-start"><span class="text-yellow-500 mr-2">✓</span> <span>Buka pengunci socket CPU (tuas/lever di samping socket)</span></li>
                                    <li class="flex items-start"><span class="text-yellow-500 mr-2">✓</span> <span>Pegang CPU dari pinggiran, jangan sentuh pin atau kontak emas</span></li>
                                    <li class="flex items-start"><span class="text-yellow-500 mr-2">✓</span> <span>Perhatikan tanda segitiga di CPU dan socket untuk orientasi yang benar</span></li>
                                    <li class="flex items-start"><span class="text-yellow-500 mr-2">✓</span> <span>Letakkan CPU dengan lembut (jangan ditekan), CPU akan masuk sendiri jika posisi benar</span></li>
                                    <li class="flex items-start"><span class="text-yellow-500 mr-2">✓</span> <span>Turunkan pengunci socket hingga terkunci dengan klik</span></li>
                                    <li class="flex items-start"><span class="text-yellow-500 mr-2">✓</span> <span>Oleskan thermal paste tipis dan merata di atas CPU (seukuran beras)</span></li>
                                    <li class="flex items-start"><span class="text-yellow-500 mr-2">✓</span> <span>Pasang heatsink/cooler CPU, kencangkan secara diagonal</span></li>
                                    <li class="flex items-start"><span class="text-yellow-500 mr-2">✓</span> <span>Hubungkan kabel power cooler ke header CPU_FAN di motherboard</span></li>
                                </ul>
                            </div>
                        </div>
                    </div><!-- Langkah 5 -->
                    <div class="step-card bg-white rounded-xl shadow-lg p-6 border-l-4 border-orange-500">
                        <div class="flex items-start">
                            <div class="bg-orange-500 text-white rounded-full w-12 h-12 flex items-center justify-center font-bold text-xl mr-4 flex-shrink-0">
                                5
                            </div>
                            <div class="flex-1">
                                <h3 class="text-2xl font-bold mb-3 text-gray-800">Pasang RAM (Memory)</h3>
                                <ul class="space-y-2 text-gray-700">
                                    <li class="flex items-start"><span class="text-orange-500 mr-2">✓</span> <span>Buka klip pengunci di kedua sisi slot RAM</span></li>
                                    <li class="flex items-start"><span class="text-orange-500 mr-2">✓</span> <span>Perhatikan takik (notch) di RAM harus sesuai dengan tonjolan di slot</span></li>
                                    <li class="flex items-start"><span class="text-orange-500 mr-2">✓</span> <span>Untuk dual channel: pasang di slot 2 dan 4 (atau sesuai manual motherboard)</span></li>
                                    <li class="flex items-start"><span class="text-orange-500 mr-2">✓</span> <span>Tekan RAM dengan kedua ibu jari secara bersamaan hingga klip mengunci otomatis</span></li>
                                    <li class="flex items-start"><span class="text-orange-500 mr-2">✓</span> <span>Pastikan RAM terpasang rata dan kuat, tidak miring</span></li>
                                </ul>
                            </div>
                        </div>
                    </div><!-- Langkah 6 -->
                    <div class="step-card bg-white rounded-xl shadow-lg p-6 border-l-4 border-red-500">
                        <div class="flex items-start">
                            <div class="bg-red-500 text-white rounded-full w-12 h-12 flex items-center justify-center font-bold text-xl mr-4 flex-shrink-0">
                                6
                            </div>
                            <div class="flex-1">
                                <h3 class="text-2xl font-bold mb-3 text-gray-800">Pasang Storage (SSD/HDD)</h3>
                                <ul class="space-y-2 text-gray-700">
                                    <li class="flex items-start"><span class="text-red-500 mr-2">✓</span> <span><strong>M.2 NVMe SSD:</strong> Masukkan ke slot M.2 dengan sudut 30°, tekan, lalu kencangkan dengan baut</span></li>
                                    <li class="flex items-start"><span class="text-red-500 mr-2">✓</span> <span><strong>2.5" SSD/HDD:</strong> Pasang di drive bay/bracket dengan baut</span></li>
                                    <li class="flex items-start"><span class="text-red-500 mr-2">✓</span> <span><strong>3.5" HDD:</strong> Pasang di drive cage dengan baut atau rail system</span></li>
                                    <li class="flex items-start"><span class="text-red-500 mr-2">✓</span> <span>Hubungkan kabel SATA data ke motherboard dan kabel SATA power dari PSU (untuk 2.5"/3.5")</span></li>
                                </ul>
                            </div>
                        </div>
                    </div><!-- Langkah 7 -->
                    <div class="step-card bg-white rounded-xl shadow-lg p-6 border-l-4 border-pink-500">
                        <div class="flex items-start">
                            <div class="bg-pink-500 text-white rounded-full w-12 h-12 flex items-center justify-center font-bold text-xl mr-4 flex-shrink-0">
                                7
                            </div>
                            <div class="flex-1">
                                <h3 class="text-2xl font-bold mb-3 text-gray-800">Pasang VGA Card (GPU)</h3>
                                <ul class="space-y-2 text-gray-700">
                                    <li class="flex items-start"><span class="text-pink-500 mr-2">✓</span> <span>Lepas bracket/cover di slot PCIe x16 bagian belakang casing</span></li>
                                    <li class="flex items-start"><span class="text-pink-500 mr-2">✓</span> <span>Buka pengunci di slot PCIe x16 (biasanya slot pertama dari atas)</span></li>
                                    <li class="flex items-start"><span class="text-pink-500 mr-2">✓</span> <span>Sejajarkan VGA card dengan slot, tekan dengan lembut hingga klik dan pengunci mengunci</span></li>
                                    <li class="flex items-start"><span class="text-pink-500 mr-2">✓</span> <span>Kencangkan bracket VGA card ke casing dengan baut</span></li>
                                    <li class="flex items-start"><span class="text-pink-500 mr-2">✓</span> <span>Hubungkan kabel power PCIe 6-pin/8-pin dari PSU ke VGA card (jika diperlukan)</span></li>
                                </ul>
                            </div>
                        </div>
                    </div><!-- Langkah 8 -->
                    <div class="step-card bg-white rounded-xl shadow-lg p-6 border-l-4 border-indigo-500">
                        <div class="flex items-start">
                            <div class="bg-indigo-500 text-white rounded-full w-12 h-12 flex items-center justify-center font-bold text-xl mr-4 flex-shrink-0">
                                8
                            </div>
                            <div class="flex-1">
                                <h3 class="text-2xl font-bold mb-3 text-gray-800">Hubungkan Kabel Power dan Front Panel</h3>
                                <ul class="space-y-2 text-gray-700">
                                    <li class="flex items-start"><span class="text-indigo-500 mr-2">✓</span> <span><strong>ATX 24-pin:</strong> Kabel power utama motherboard (konektor terbesar)</span></li>
                                    <li class="flex items-start"><span class="text-indigo-500 mr-2">✓</span> <span><strong>CPU 8-pin (4+4):</strong> Kabel power CPU di pojok atas motherboard</span></li>
                                    <li class="flex items-start"><span class="text-indigo-500 mr-2">✓</span> <span><strong>Front Panel:</strong> Hubungkan kabel power button, reset, LED, USB, audio sesuai manual</span></li>
                                    <li class="flex items-start"><span class="text-indigo-500 mr-2">✓</span> <span><strong>Case Fans:</strong> Hubungkan kipas casing ke header CHA_FAN/SYS_FAN</span></li>
                                    <li class="flex items-start"><span class="text-indigo-500 mr-2">✓</span> <span>Rapikan kabel dengan cable ties dan manfaatkan cable management di casing</span></li>
                                </ul>
                            </div>
                        </div>
                    </div><!-- Langkah 9 -->
                    <div class="step-card bg-white rounded-xl shadow-lg p-6 border-l-4 border-teal-500">
                        <div class="flex items-start">
                            <div class="bg-teal-500 text-white rounded-full w-12 h-12 flex items-center justify-center font-bold text-xl mr-4 flex-shrink-0">
                                9
                            </div>
                            <div class="flex-1">
                                <h3 class="text-2xl font-bold mb-3 text-gray-800">Testing dan Power On</h3>
                                <ul class="space-y-2 text-gray-700">
                                    <li class="flex items-start"><span class="text-teal-500 mr-2">✓</span> <span>Cek ulang semua koneksi kabel dan komponen</span></li>
                                    <li class="flex items-start"><span class="text-teal-500 mr-2">✓</span> <span>Pastikan tidak ada baut atau kabel yang terjepit</span></li>
                                    <li class="flex items-start"><span class="text-teal-500 mr-2">✓</span> <span>Hubungkan kabel power PSU ke stop kontak</span></li>
                                    <li class="flex items-start"><span class="text-teal-500 mr-2">✓</span> <span>Nyalakan switch PSU (posisi I / ON)</span></li>
                                    <li class="flex items-start"><span class="text-teal-500 mr-2">✓</span> <span>Tekan tombol power di casing</span></li>
                                    <li class="flex items-start"><span class="text-teal-500 mr-2">✓</span> <span>Masuk ke BIOS (tekan Del/F2) untuk mengecek semua komponen terdeteksi</span></li>
                                    <li class="flex items-start"><span class="text-teal-500 mr-2">✓</span> <span>Install sistem operasi jika POST berhasil</span></li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </div><!-- Tips & K3LH Tab -->
            <div id="tips-tab" class="tab-content" style="display: none;">
                <div class="bg-white rounded-xl shadow-lg p-6 mb-6">
                    <h2 class="text-3xl font-bold mb-4 text-gray-800">⚠️ Tips Penting &amp; Keselamatan Kerja (K3LH)</h2>
                    <p class="text-gray-600 mb-6">Perhatikan hal-hal berikut untuk memastikan proses perakitan aman dan hasil maksimal.</p>
                </div>
                <div class="grid md:grid-cols-2 gap-6"><!-- K3 Section -->
                    <div class="bg-red-50 rounded-xl shadow-lg p-6 border-2 border-red-200">
                        <div class="text-4xl mb-4">
                            🛡️
                        </div>
                        <h3 class="text-2xl font-bold mb-4 text-red-800">Keselamatan Kerja (K3)</h3>
                        <div class="space-y-4">
                            <div>
                                <h4 class="font-bold text-red-700 mb-2">Bahaya Listrik Statis (ESD)</h4>
                                <ul class="space-y-1 text-gray-700 text-sm">
                                    <li>• Gunakan gelang anti-statis atau sentuh permukaan logam yang di-ground</li>
                                    <li>• Hindari bekerja di atas karpet atau permukaan yang menghasilkan statis</li>
                                    <li>• Jangan menyentuh pin/kontak emas pada komponen</li>
                                    <li>• Simpan komponen dalam kemasan anti-statis</li>
                                </ul>
                            </div>
                            <div>
                                <h4 class="font-bold text-red-700 mb-2">Keselamatan Listrik</h4>
                                <ul class="space-y-1 text-gray-700 text-sm">
                                    <li>• Pastikan PSU dalam posisi OFF saat merakit</li>
                                    <li>• Cabut kabel power dari stop kontak saat bekerja</li>
                                    <li>• Gunakan stop kontak dengan ground yang baik</li>
                                    <li>• Jangan bekerja dengan tangan basah</li>
                                    <li>• Hindari minuman/makanan di dekat area kerja</li>
                                </ul>
                            </div>
                            <div>
                                <h4 class="font-bold text-red-700 mb-2">Ergonomi Kerja</h4>
                                <ul class="space-y-1 text-gray-700 text-sm">
                                    <li>• Bekerja di meja dengan ketinggian yang nyaman</li>
                                    <li>• Pastikan pencahayaan cukup untuk melihat detail</li>
                                    <li>• Istirahat sejenak jika merasa lelah</li>
                                    <li>• Jaga postur tubuh yang baik saat bekerja</li>
                                </ul>
                            </div>
                            <div>
                                <h4 class="font-bold text-red-700 mb-2">Alat Pelindung Diri (APD)</h4>
                                <ul class="space-y-1 text-gray-700 text-sm">
                                    <li>• Gelang anti-statis (wrist strap ESD)</li>
                                    <li>• Sarung tangan kain (opsional, untuk pegangan)</li>
                                    <li>• Kacamata safety (untuk melindungi dari debu)</li>
                                </ul>
                            </div>
                        </div>
                    </div><!-- Lingkungan Hidup -->
                    <div class="bg-green-50 rounded-xl shadow-lg p-6 border-2 border-green-200">
                        <div class="text-4xl mb-4">
                            🌱
                        </div>
                        <h3 class="text-2xl font-bold mb-4 text-green-800">Lingkungan Hidup (LH)</h3>
                        <div class="space-y-4">
                            <div>
                                <h4 class="font-bold text-green-700 mb-2">Pengelolaan Limbah Elektronik</h4>
                                <ul class="space-y-1 text-gray-700 text-sm">
                                    <li>• Simpan kemasan komponen untuk garansi/penjualan kembali</li>
                                    <li>• Daur ulang kardus dan bahan kemasan</li>
                                    <li>• Komponen rusak: bawa ke pusat daur ulang e-waste</li>
                                    <li>• Jangan buang komponen elektronik ke tempat sampah biasa</li>
                                </ul>
                            </div>
                            <div>
                                <h4 class="font-bold text-green-700 mb-2">Efisiensi Energi</h4>
                                <ul class="space-y-1 text-gray-700 text-sm">
                                    <li>• Pilih PSU dengan sertifikasi 80+ (Bronze/Gold/Platinum)</li>
                                    <li>• Aktifkan fitur power saving di BIOS</li>
                                    <li>• Matikan komputer jika tidak digunakan</li>
                                    <li>• Gunakan mode sleep/hibernate untuk jeda singkat</li>
                                </ul>
                            </div>
                            <div>
                                <h4 class="font-bold text-green-700 mb-2">Area Kerja Bersih</h4>
                                <ul class="space-y-1 text-gray-700 text-sm">
                                    <li>• Bersihkan area kerja sebelum dan sesudah merakit</li>
                                    <li>• Pisahkan sampah organik dan anorganik</li>
                                    <li>• Gunakan compressed air untuk membersihkan debu</li>
                                    <li>• Simpan baut dan part kecil dalam wadah terpisah</li>
                                </ul>
                            </div>
                        </div>
                    </div><!-- Tips Penting -->
                    <div class="bg-yellow-50 rounded-xl shadow-lg p-6 border-2 border-yellow-200">
                        <div class="text-4xl mb-4">
                            💡
                        </div>
                        <h3 class="text-2xl font-bold mb-4 text-yellow-800">Tips Penting yang Harus Diperhatikan</h3>
                        <div class="space-y-4">
                            <div>
                                <h4 class="font-bold text-yellow-700 mb-2">Kompatibilitas Komponen</h4>
                                <ul class="space-y-1 text-gray-700 text-sm">
                                    <li>• Cek socket CPU sesuai dengan motherboard (LGA 1700, AM5, dll)</li>
                                    <li>• Pastikan RAM sesuai tipe (DDR4/DDR5) dan frekuensi yang didukung</li>
                                    <li>• VGA card muat di casing (perhatikan panjang)</li>
                                    <li>• Wattage PSU cukup untuk semua komponen + 20% buffer</li>
                                    <li>• Motherboard form factor sesuai casing (ATX, mATX, ITX)</li>
                                </ul>
                            </div>
                            <div>
                                <h4 class="font-bold text-yellow-700 mb-2">Thermal Management</h4>
                                <ul class="space-y-1 text-gray-700 text-sm">
                                    <li>• Jangan gunakan thermal paste terlalu banyak (seukuran beras)</li>
                                    <li>• Pastikan heatsink terpasang rata dan kencang</li>
                                    <li>• Atur aliran udara: depan = intake, belakang/atas = exhaust</li>
                                    <li>• Cable management yang baik membantu sirkulasi udara</li>
                                    <li>• Monitor suhu CPU/GPU setelah perakitan</li>
                                </ul>
                            </div>
                            <div>
                                <h4 class="font-bold text-yellow-700 mb-2">Troubleshooting Umum</h4>
                                <ul class="space-y-1 text-gray-700 text-sm">
                                    <li>• <strong>Tidak nyala:</strong> Cek kabel power 24-pin dan 8-pin CPU</li>
                                    <li>• <strong>Nyala tapi no display:</strong> Cek RAM terpasang dengan benar</li>
                                    <li>• <strong>Beep berulang:</strong> Lihat kode beep di manual motherboard</li>
                                    <li>• <strong>Kipas CPU tidak berputar:</strong> Cek koneksi ke CPU_FAN header</li>
                                    <li>• <strong>Overheat:</strong> Cek thermal paste dan pemasangan cooler</li>
                                </ul>
                            </div>
                        </div>
                    </div><!-- Hal yang Harus Dihindari -->
                    <div class="bg-purple-50 rounded-xl shadow-lg p-6 border-2 border-purple-200">
                        <div class="text-4xl mb-4">
                            🚫
                        </div>
                        <h3 class="text-2xl font-bold mb-4 text-purple-800">Hal yang HARUS DIHINDARI</h3>
                        <div class="space-y-4">
                            <div>
                                <h4 class="font-bold text-purple-700 mb-2">Kesalahan Pemasangan</h4>
                                <ul class="space-y-1 text-gray-700 text-sm">
                                    <li>• ❌ Memasang standoff di tempat yang salah (short circuit!)</li>
                                    <li>• ❌ Memaksa komponen masuk (CPU, RAM, VGA)</li>
                                    <li>• ❌ Lupa memasang I/O shield sebelum motherboard</li>
                                    <li>• ❌ Menyentuh pin CPU atau kontak emas RAM</li>
                                    <li>• ❌ Mengencangkan baut terlalu kencang (retak PCB)</li>
                                    <li>• ❌ Lupa menghubungkan power CPU 8-pin</li>
                                </ul>
                            </div>
                            <div>
                                <h4 class="font-bold text-purple-700 mb-2">Kerusakan Komponen</h4>
                                <ul class="space-y-1 text-gray-700 text-sm">
                                    <li>• ❌ Tidak menggunakan gelang anti-statis</li>
                                    <li>• ❌ Menjatuhkan komponen ke lantai keras</li>
                                    <li>• ❌ Membengkokkan pin CPU atau RAM</li>
                                    <li>• ❌ Thermal paste mengenai socket atau pin</li>
                                    <li>• ❌ Mencolok kabel dengan orientasi terbalik</li>
                                </ul>
                            </div>
                            <div>
                                <h4 class="font-bold text-purple-700 mb-2">Kebiasaan Buruk</h4>
                                <ul class="space-y-1 text-gray-700 text-sm">
                                    <li>• ❌ Merakit sambil makan/minum</li>
                                    <li>• ❌ Bekerja di lantai berkarpet</li>
                                    <li>• ❌ Terburu-buru tanpa membaca manual</li>
                                    <li>• ❌ Tidak dokumentasi proses perakitan</li>
                                    <li>• ❌ Menyalakan PC tanpa cek ulang semua koneksi</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div><!-- Checklist Final -->
                <div class="bg-gradient-to-r from-blue-500 to-purple-600 rounded-xl shadow-lg p-6 mt-6 text-white">
                    <h3 class="text-2xl font-bold mb-4">✅ Checklist Sebelum Power On</h3>
                    <div class="grid md:grid-cols-2 gap-4">
                        <div>
                            <ul class="space-y-2">
                                <li>☐ Semua komponen terpasang dengan benar</li>
                                <li>☐ Kabel power 24-pin dan 8-pin CPU terhubung</li>
                                <li>☐ RAM terkunci dengan sempurna</li>
                                <li>☐ VGA card terpasang dan kabel power terhubung</li>
                                <li>☐ Storage terhubung (SATA/M.2)</li>
                            </ul>
                        </div>
                        <div>
                            <ul class="space-y-2">
                                <li>☐ CPU cooler terpasang dan fan terhubung</li>
                                <li>☐ Front panel connector terpasang</li>
                                <li>☐ Tidak ada baut/part yang tertinggal</li>
                                <li>☐ Cable management rapi</li>
                                <li>☐ PSU switch dalam posisi ON</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div><!-- Game Tab -->
            <div id="game-tab" class="tab-content" style="display: none;">
                <div class="bg-white rounded-xl shadow-lg p-6 mb-6">
                    <h2 id="game-title" class="text-3xl font-bold mb-3 text-gray-800">🎮 Game Rakit Komputer</h2>
                    <p id="game-instruction" class="text-gray-600 mb-4">Seret dan lepaskan komponen ke casing komputer sesuai urutan yang benar!</p>
                    <div class="bg-blue-50 border-l-4 border-blue-500 p-4 mb-6">
                        <p class="font-semibold text-blue-800">Urutan Perakitan yang Benar:</p>
                        <p class="text-blue-700">1️⃣ Power Supply → 2️⃣ Motherboard → 3️⃣ Processor → 4️⃣ RAM → 5️⃣ Storage → 6️⃣ VGA Card</p>
                    </div>
                    <div class="mb-6">
                        <div class="flex items-center justify-between mb-3">
                            <div class="text-lg"><span class="font-semibold">Progres:</span> <span id="progress" class="text-purple-600 font-bold ml-2">0/6</span>
                            </div><button id="reset-btn" class="bg-red-500 hover:bg-red-600 text-white px-6 py-2 rounded-lg font-semibold transition-all transform hover:scale-105"> 🔄 Reset Game </button>
                        </div>
                        <div class="progress-bar">
                            <div id="progress-fill" class="progress-fill" style="width: 0%"></div>
                        </div>
                    </div>
                </div>
                <div class="grid lg:grid-cols-2 gap-8"><!-- Komponen yang tersedia -->
                    <div>
                        <h3 class="text-xl font-bold mb-4 text-gray-800">Komponen Tersedia:</h3>
                        <div id="components-list" class="space-y-3">
                            <div class="component-card bg-gradient-to-r from-purple-500 to-purple-600 text-white rounded-lg p-4 shadow-md" draggable="true" data-component="psu">
                                <div class="flex items-center">
                                    <div class="text-3xl mr-3">
                                        🔌
                                    </div>
                                    <div>
                                        <div class="font-bold text-lg">
                                            Power Supply
                                        </div>
                                        <div class="text-sm opacity-90">
                                            Sumber daya listrik
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="component-card bg-gradient-to-r from-blue-500 to-blue-600 text-white rounded-lg p-4 shadow-md" draggable="true" data-component="motherboard">
                                <div class="flex items-center">
                                    <div class="text-3xl mr-3">
                                        💾
                                    </div>
                                    <div>
                                        <div class="font-bold text-lg">
                                            Motherboard
                                        </div>
                                        <div class="text-sm opacity-90">
                                            Papan sirkuit utama
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="component-card bg-gradient-to-r from-green-500 to-green-600 text-white rounded-lg p-4 shadow-md" draggable="true" data-component="cpu">
                                <div class="flex items-center">
                                    <div class="text-3xl mr-3">
                                        ⚡
                                    </div>
                                    <div>
                                        <div class="font-bold text-lg">
                                            Processor
                                        </div>
                                        <div class="text-sm opacity-90">
                                            Otak komputer
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="component-card bg-gradient-to-r from-yellow-500 to-yellow-600 text-white rounded-lg p-4 shadow-md" draggable="true" data-component="ram">
                                <div class="flex items-center">
                                    <div class="text-3xl mr-3">
                                        🎴
                                    </div>
                                    <div>
                                        <div class="font-bold text-lg">
                                            RAM
                                        </div>
                                        <div class="text-sm opacity-90">
                                            Memori sementara
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="component-card bg-gradient-to-r from-orange-500 to-orange-600 text-white rounded-lg p-4 shadow-md" draggable="true" data-component="storage">
                                <div class="flex items-center">
                                    <div class="text-3xl mr-3">
                                        💿
                                    </div>
                                    <div>
                                        <div class="font-bold text-lg">
                                            Storage
                                        </div>
                                        <div class="text-sm opacity-90">
                                            Penyimpanan data
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="component-card bg-gradient-to-r from-red-500 to-red-600 text-white rounded-lg p-4 shadow-md" draggable="true" data-component="vga">
                                <div class="flex items-center">
                                    <div class="text-3xl mr-3">
                                        🎨
                                    </div>
                                    <div>
                                        <div class="font-bold text-lg">
                                            VGA Card
                                        </div>
                                        <div class="text-sm opacity-90">
                                            Kartu grafis
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div><!-- Area Casing Komputer -->
                    <div>
                        <h3 class="text-xl font-bold mb-4 text-gray-800">Casing Komputer:</h3>
                        <div class="bg-gray-100 rounded-xl p-6 border-4 border-gray-300">
                            <div class="space-y-3">
                                <div class="drop-zone bg-white rounded-lg p-4 text-center" data-slot="1" data-component="psu">
                                    <div class="text-gray-400 font-semibold">
                                        Slot 1: Power Supply
                                    </div>
                                    <div class="text-sm text-gray-400">
                                        🔌 Pasang PSU dulu
                                    </div>
                                </div>
                                <div class="drop-zone bg-white rounded-lg p-4 text-center" data-slot="2" data-component="motherboard">
                                    <div class="text-gray-400 font-semibold">
                                        Slot 2: Motherboard
                                    </div>
                                    <div class="text-sm text-gray-400">
                                        💾 Papan utama
                                    </div>
                                </div>
                                <div class="drop-zone bg-white rounded-lg p-4 text-center" data-slot="3" data-component="cpu">
                                    <div class="text-gray-400 font-semibold">
                                        Slot 3: Processor
                                    </div>
                                    <div class="text-sm text-gray-400">
                                        ⚡ CPU socket
                                    </div>
                                </div>
                                <div class="drop-zone bg-white rounded-lg p-4 text-center" data-slot="4" data-component="ram">
                                    <div class="text-gray-400 font-semibold">
                                        Slot 4: RAM
                                    </div>
                                    <div class="text-sm text-gray-400">
                                        🎴 Memory slot
                                    </div>
                                </div>
                                <div class="drop-zone bg-white rounded-lg p-4 text-center" data-slot="5" data-component="storage">
                                    <div class="text-gray-400 font-semibold">
                                        Slot 5: Storage
                                    </div>
                                    <div class="text-sm text-gray-400">
                                        💿 Drive bay
                                    </div>
                                </div>
                                <div class="drop-zone bg-white rounded-lg p-4 text-center" data-slot="6" data-component="vga">
                                    <div class="text-gray-400 font-semibold">
                                        Slot 6: VGA Card
                                    </div>
                                    <div class="text-sm text-gray-400">
                                        🎨 PCIe slot
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </main><!-- Overlay dan Celebration -->
        <div class="overlay" id="overlay"></div>
        <div class="celebration" id="celebration">
            <div class="text-center">
                <div class="text-6xl mb-4">
                    🎉
                </div>
                <h2 class="text-3xl font-bold mb-3 text-gray-800">Selamat!</h2>
                <p class="text-xl text-gray-600 mb-6">Kamu berhasil merakit komputer dengan benar!</p>
                <div class="bg-green-50 border-2 border-green-500 rounded-lg p-4 mb-6">
                    <p class="text-green-800 font-semibold">✅ Semua komponen terpasang dengan urutan yang tepat!</p>
                </div><button id="close-celebration" class="bg-purple-600 hover:bg-purple-700 text-white px-8 py-3 rounded-lg font-bold text-lg transition-all"> Main Lagi </button>
            </div>
        </div>
    </div>
    <script>
        const defaultConfig = {
            main_title: "🖥️ Perakitan Komputer Interaktif",
            subtitle: "Belajar Merakit Komputer dengan Cara yang Menyenangkan!",
            game_title: "🎮 Game Rakit Komputer",
            game_instruction: "Seret dan lepaskan komponen ke casing komputer sesuai urutan yang benar!",
            background_color: "#667eea",
            surface_color: "#ffffff",
            text_color: "#1a202c",
            primary_action_color: "#667eea",
            secondary_action_color: "#ef4444"
        };

        let config = {
            ...defaultConfig
        };
        let draggedElement = null;
        let completedSlots = 0;

        async function onConfigChange(newConfig) {
            config = {
                ...defaultConfig,
                ...newConfig
            };

            const mainTitle = document.getElementById('main-title');
            const subtitle = document.getElementById('subtitle');
            const gameTitle = document.getElementById('game-title');
            const gameInstruction = document.getElementById('game-instruction');

            if (mainTitle) mainTitle.textContent = config.main_title;
            if (subtitle) subtitle.textContent = config.subtitle;
            if (gameTitle) gameTitle.textContent = config.game_title;
            if (gameInstruction) gameInstruction.textContent = config.game_instruction;

            const header = document.querySelector('header');
            if (header) {
                header.style.background = `linear-gradient(135deg, ${config.background_color} 0%, ${config.primary_action_color} 100%)`;
            }

            const tabButtons = document.querySelectorAll('.tab-button.active');
            tabButtons.forEach(btn => {
                btn.style.borderBottomColor = config.primary_action_color;
                btn.style.color = config.primary_action_color;
            });

            const resetBtn = document.getElementById('reset-btn');
            if (resetBtn) {
                resetBtn.style.backgroundColor = config.secondary_action_color;
            }
        }

        function mapToCapabilities(config) {
            return {
                recolorables: [{
                        get: () => config.background_color || defaultConfig.background_color,
                        set: (value) => {
                            config.background_color = value;
                            if (window.elementSdk) {
                                window.elementSdk.setConfig({
                                    background_color: value
                                });
                            }
                        }
                    },
                    {
                        get: () => config.surface_color || defaultConfig.surface_color,
                        set: (value) => {
                            config.surface_color = value;
                            if (window.elementSdk) {
                                window.elementSdk.setConfig({
                                    surface_color: value
                                });
                            }
                        }
                    },
                    {
                        get: () => config.text_color || defaultConfig.text_color,
                        set: (value) => {
                            config.text_color = value;
                            if (window.elementSdk) {
                                window.elementSdk.setConfig({
                                    text_color: value
                                });
                            }
                        }
                    },
                    {
                        get: () => config.primary_action_color || defaultConfig.primary_action_color,
                        set: (value) => {
                            config.primary_action_color = value;
                            if (window.elementSdk) {
                                window.elementSdk.setConfig({
                                    primary_action_color: value
                                });
                            }
                        }
                    },
                    {
                        get: () => config.secondary_action_color || defaultConfig.secondary_action_color,
                        set: (value) => {
                            config.secondary_action_color = value;
                            if (window.elementSdk) {
                                window.elementSdk.setConfig({
                                    secondary_action_color: value
                                });
                            }
                        }
                    }
                ],
                borderables: [],
                fontEditable: undefined,
                fontSizeable: undefined
            };
        }

        function mapToEditPanelValues(config) {
            return new Map([
                ["main_title", config.main_title || defaultConfig.main_title],
                ["subtitle", config.subtitle || defaultConfig.subtitle],
                ["game_title", config.game_title || defaultConfig.game_title],
                ["game_instruction", config.game_instruction || defaultConfig.game_instruction]
            ]);
        }

        if (window.elementSdk) {
            window.elementSdk.init({
                defaultConfig,
                onConfigChange,
                mapToCapabilities,
                mapToEditPanelValues
            });
        }

        // Tab functionality
        const tabButtons = document.querySelectorAll('.tab-button');
        const tabContents = document.querySelectorAll('.tab-content');

        tabButtons.forEach(button => {
            button.addEventListener('click', () => {
                const targetTab = button.getAttribute('data-tab');

                tabButtons.forEach(btn => btn.classList.remove('active'));
                button.classList.add('active');

                tabContents.forEach(content => {
                    content.style.display = 'none';
                });

                document.getElementById(`${targetTab}-tab`).style.display = 'block';
            });
        });

        // Drag and Drop functionality
        const components = document.querySelectorAll('.component-card');
        const dropZones = document.querySelectorAll('.drop-zone');

        components.forEach(component => {
            component.addEventListener('dragstart', (e) => {
                draggedElement = e.target;
                e.target.style.opacity = '0.5';
            });

            component.addEventListener('dragend', (e) => {
                e.target.style.opacity = '1';
            });
        });

        dropZones.forEach(zone => {
            zone.addEventListener('dragover', (e) => {
                e.preventDefault();
                zone.classList.add('highlight');
            });

            zone.addEventListener('dragleave', () => {
                zone.classList.remove('highlight');
            });

            zone.addEventListener('drop', (e) => {
                e.preventDefault();
                zone.classList.remove('highlight');

                if (!draggedElement) return;

                const componentType = draggedElement.getAttribute('data-component');
                const expectedType = zone.getAttribute('data-component');
                const slotNumber = parseInt(zone.getAttribute('data-slot'));

                if (componentType === expectedType && !zone.classList.contains('filled')) {
                    const componentClone = draggedElement.cloneNode(true);
                    componentClone.draggable = false;
                    componentClone.classList.remove('component-card');
                    componentClone.classList.add('cursor-default');

                    zone.innerHTML = '';
                    zone.appendChild(componentClone);
                    zone.classList.add('filled');

                    draggedElement.style.display = 'none';

                    completedSlots++;
                    document.getElementById('progress').textContent = `${completedSlots}/6`;

                    // Update progress bar
                    const progressFill = document.getElementById('progress-fill');
                    const percentage = (completedSlots / 6) * 100;
                    progressFill.style.width = percentage + '%';

                    if (completedSlots === 6) {
                        setTimeout(() => {
                            showCelebration();
                        }, 500);
                    }
                } else if (componentType !== expectedType) {
                    showToast('❌ Komponen salah! Perhatikan urutan perakitan yang benar.');
                }
            });
        });

        function showCelebration() {
            const overlay = document.getElementById('overlay');
            const celebration = document.getElementById('celebration');

            overlay.classList.add('show');
            celebration.classList.add('show');

            // Create confetti
            createConfetti();
        }

        function hideCelebration() {
            const overlay = document.getElementById('overlay');
            const celebration = document.getElementById('celebration');

            overlay.classList.remove('show');
            celebration.classList.remove('show');

            setTimeout(() => {
                overlay.style.display = 'none';
                celebration.style.display = 'none';
            }, 300);
        }

        function createConfetti() {
            const colors = ['#f39c12', '#e74c3c', '#9b59b6', '#3498db', '#2ecc71', '#f1c40f'];
            for (let i = 0; i < 50; i++) {
                setTimeout(() => {
                    const confetti = document.createElement('div');
                    confetti.className = 'confetti';
                    confetti.style.left = Math.random() * 100 + '%';
                    confetti.style.background = colors[Math.floor(Math.random() * colors.length)];
                    confetti.style.animationDelay = Math.random() * 0.5 + 's';
                    document.body.appendChild(confetti);

                    setTimeout(() => confetti.remove(), 3000);
                }, i * 30);
            }
        }

        document.getElementById('close-celebration').addEventListener('click', () => {
            hideCelebration();
            resetGame();
        });

        document.getElementById('reset-btn').addEventListener('click', resetGame);

        function resetGame() {
            completedSlots = 0;
            document.getElementById('progress').textContent = '0/6';

            // Reset progress bar
            const progressFill = document.getElementById('progress-fill');
            progressFill.style.width = '0%';

            components.forEach(component => {
                component.style.display = 'flex';
            });

            dropZones.forEach(zone => {
                zone.classList.remove('filled');
                const slotNumber = zone.getAttribute('data-slot');
                const componentType = zone.getAttribute('data-component');

                let emoji = '';
                let label = '';
                let description = '';

                switch (componentType) {
                    case 'psu':
                        emoji = '🔌';
                        label = 'Power Supply';
                        description = 'Pasang PSU dulu';
                        break;
                    case 'motherboard':
                        emoji = '💾';
                        label = 'Motherboard';
                        description = 'Papan utama';
                        break;
                    case 'cpu':
                        emoji = '⚡';
                        label = 'Processor';
                        description = 'CPU socket';
                        break;
                    case 'ram':
                        emoji = '🎴';
                        label = 'RAM';
                        description = 'Memory slot';
                        break;
                    case 'storage':
                        emoji = '💿';
                        label = 'Storage';
                        description = 'Drive bay';
                        break;
                    case 'vga':
                        emoji = '🎨';
                        label = 'VGA Card';
                        description = 'PCIe slot';
                        break;
                }

                zone.innerHTML = `
                    <div class="text-gray-400 font-semibold">Slot ${slotNumber}: ${label}</div>
                    <div class="text-sm text-gray-400">${emoji} ${description}</div>
                `;
            });
        }

        function showToast(message) {
            const toast = document.createElement('div');
            toast.textContent = message;
            toast.style.cssText = `
                position: fixed;
                top: 20px;
                right: 20px;
                background: #ef4444;
                color: white;
                padding: 16px 24px;
                border-radius: 8px;
                box-shadow: 0 4px 12px rgba(0,0,0,0.2);
                z-index: 10000;
                font-weight: 600;
            `;
            document.body.appendChild(toast);

            setTimeout(() => {
                toast.remove();
            }, 3000);
        }
    </script>
    <script>
        (function() {
            function c() {
                var b = a.contentDocument || a.contentWindow.document;
                if (b) {
                    var d = b.createElement('script');
                    d.innerHTML = "window.__CF$cv$params={r:'9aa23072477e4ab2',t:'MTc2NTA5MTI4MC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";
                    b.getElementsByTagName('head')[0].appendChild(d)
                }
            }
            if (document.body) {
                var a = document.createElement('iframe');
                a.height = 1;
                a.width = 1;
                a.style.position = 'absolute';
                a.style.top = 0;
                a.style.left = 0;
                a.style.border = 'none';
                a.style.visibility = 'hidden';
                document.body.appendChild(a);
                if ('loading' !== document.readyState) c();
                else if (window.addEventListener) document.addEventListener('DOMContentLoaded', c);
                else {
                    var e = document.onreadystatechange || function() {};
                    document.onreadystatechange = function(b) {
                        e(b);
                        'loading' !== document.readyState && (document.onreadystatechange = e, c())
                    }
                }
            }
        })();
    </script>
</body>

</html>