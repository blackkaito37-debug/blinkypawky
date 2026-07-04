<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0" />
    <title>Blinky Pawky - Panduan Shooting & Video Gallery</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
    
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap');
      
      body {
        font-family: 'Plus Jakarta Sans', 'Segoe UI', sans-serif;
        background-color: #fff8f8;
      }
      
      .pink-gradient-bg {
        background: linear-gradient(135deg, #fff5f5 0%, #ffeef1 100%);
      }
      
      .card-rekomendasi {
        border-top: 4px solid #10b981;
      }
      
      .card-hindari {
        border-top: 4px solid #ef4444;
      }

      /* Kustomisasi scrollbar tipis untuk HP */
      ::-webkit-scrollbar {
        width: 4px;
      }
      ::-webkit-scrollbar-track {
        background: #fff5f5;
      }
      ::-webkit-scrollbar-thumb {
        background: #ffb8c6;
        border-radius: 4px;
      }
    </style>
  </head>
  <body class="text-slate-700 antialiased min-h-screen flex flex-col overflow-x-hidden">

    <!-- Header / Hero Section -->
    <header class="pink-gradient-bg py-10 px-4 text-center border-b border-rose-100 relative overflow-hidden">
      <!-- Ornamen Dekoratif -->
      <div class="absolute -top-10 -left-10 w-32 h-32 bg-pink-200 rounded-full mix-blend-multiply filter blur-xl opacity-30 animate-pulse"></div>
      <div class="absolute -bottom-10 -right-10 w-32 h-32 bg-rose-200 rounded-full mix-blend-multiply filter blur-xl opacity-30 animate-pulse"></div>

      <div class="max-w-4xl mx-auto relative z-10">
        <span class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full text-[11px] font-bold bg-rose-100 text-rose-600 mb-3 uppercase tracking-wider">
          <i data-lucide="sparkles" class="w-3.5 h-3.5"></i> Panduan Kreator
        </span>
        <h1 class="text-2xl sm:text-3xl md:text-5xl font-extrabold text-rose-600 tracking-tight leading-snug mb-3">
          PANDUAN SHOOTING VIDEO BULU MATA ✨
        </h1>
        <p class="text-slate-500 max-w-2xl mx-auto text-xs sm:text-sm md:text-base leading-relaxed">
          Ikuti standar produksi video ini untuk menghasilkan konten promosi bulu mata yang estetik dan meningkatkan penjualan.
        </p>
      </div>
    </header>

    <!-- Main Content Container -->
    <main class="max-w-7xl mx-auto px-4 py-8 flex-grow w-full">
      
      <!-- Section 1: Instruksi & Panduan -->
      <section class="mb-12">
        <div class="flex items-center gap-2 mb-5 justify-center sm:justify-start">
          <i data-lucide="book-open" class="text-rose-500 w-5 h-5"></i>
          <h2 class="text-xl sm:text-2xl font-bold text-slate-800">Petunjuk Pelaksanaan</h2>
        </div>
        
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-6">
          
          <!-- Card 1: Bagian Awal -->
          <div class="bg-white p-5 sm:p-6 rounded-2xl shadow-sm border border-rose-50">
            <div class="flex items-center gap-3 mb-3">
              <div class="w-9 h-9 rounded-xl bg-emerald-50 text-emerald-600 flex items-center justify-center font-bold text-sm shrink-0">
                01
              </div>
              <h3 class="font-bold text-slate-800 text-sm sm:text-base">BAGIAN AWAL 3 DETIK (WAJIB)</h3>
            </div>
            <ul class="space-y-2 text-xs sm:text-sm text-slate-600">
              <li class="flex gap-2 items-start">
                <span class="text-emerald-500 font-bold shrink-0">✓</span>
                <span><strong>Visual:</strong> Close-up fokus area mata & alis, latar belakang bersih dan rapi.</span>
              </li>
              <li class="flex gap-2 items-start">
                <span class="text-emerald-500 font-bold shrink-0">✓</span>
                <span><strong>Gerakan:</strong> Berkedip perlahan, angkat pandangan, tunjukkan kelenturan bulu mata.</span>
              </li>
              <li class="flex gap-2 items-start">
                <span class="text-emerald-500 font-bold shrink-0">✓</span>
                <span><strong>Narasi:</strong> "Bulu mata ini sangat cantik saat terpasang! Mata langsung terlihat lebih besar."</span>
              </li>
            </ul>
          </div>

          <!-- Card 2: Standar Visual -->
          <div class="bg-white p-5 sm:p-6 rounded-2xl shadow-sm border border-rose-50">
            <div class="flex items-center gap-3 mb-3">
              <div class="w-9 h-9 rounded-xl bg-amber-50 text-amber-600 flex items-center justify-center font-bold text-sm shrink-0">
                02
              </div>
              <h3 class="font-bold text-slate-800 text-sm sm:text-base">STANDAR VISUAL VIDEO</h3>
            </div>
            <ul class="space-y-2 text-xs sm:text-sm text-slate-600">
              <li class="flex gap-2 items-start">
                <span class="text-amber-500 font-bold shrink-0">✓</span>
                <span><strong>Cahaya:</strong> Gunakan pencahayaan depan yang lembut agar tekstur bulu mata jelas.</span>
              </li>
              <li class="flex gap-2 items-start">
                <span class="text-amber-500 font-bold shrink-0">✓</span>
                <span><strong>Makeup:</strong> Natural & simpel. Hindari eyeliner tebal agar fokus tetap pada produk.</span>
              </li>
              <li class="flex gap-2 items-start">
                <span class="text-amber-500 font-bold shrink-0">✓</span>
                <span><strong>Watermark:</strong> Letakkan teks di sisi layar, jangan menghalangi mata.</span>
              </li>
            </ul>
          </div>

          <!-- Card 3: Alur Shooting -->
          <div class="bg-white p-5 sm:p-6 rounded-2xl shadow-sm border border-rose-50">
            <div class="flex items-center gap-3 mb-3">
              <div class="w-9 h-9 rounded-xl bg-blue-50 text-blue-600 flex items-center justify-center font-bold text-sm shrink-0">
                03
              </div>
              <h3 class="font-bold text-slate-800 text-sm sm:text-base">ALUR DETIK KE DETIK</h3>
            </div>
            <ul class="space-y-2 text-xs sm:text-sm text-slate-600">
              <li class="flex gap-2 items-start">
                <span class="text-blue-500 font-bold shrink-0">⏱</span>
                <span><strong>Detik 3–8:</strong> Close-up satu mata secara detail. Jelaskan kenyamanan seharian.</span>
              </li>
              <li class="flex gap-2 items-start">
                <span class="text-blue-500 font-bold shrink-0">⏱</span>
                <span><strong>Detik 8–15:</strong> Ubah sudut pandang depan dan samping penuh. Tunjukkan kelayakan selfie.</span>
              </li>
            </ul>
          </div>

          <!-- Card 4: Penutup & CTA -->
          <div class="bg-white p-5 sm:p-6 rounded-2xl shadow-sm border border-rose-50">
            <div class="flex items-center gap-3 mb-3">
              <div class="w-9 h-9 rounded-xl bg-purple-50 text-purple-600 flex items-center justify-center font-bold text-sm shrink-0">
                04
              </div>
              <h3 class="font-bold text-slate-800 text-sm sm:text-base">PENUTUP & AJAKAN BELI</h3>
            </div>
            <ul class="space-y-2 text-xs sm:text-sm text-slate-600">
              <li class="flex gap-2 items-start">
                <span class="text-purple-500 font-bold shrink-0">✓</span>
                <span><strong>Visual:</strong> Tampilkan seluruh wajah dengan percaya diri & senyum ramah.</span>
              </li>
              <li class="flex gap-2 items-start">
                <span class="text-purple-500 font-bold shrink-0">✓</span>
                <span><strong>Pesan:</strong> Tekankan keunggulan produk yang mudah dipasang oleh pemula sekalipun.</span>
              </li>
              <li class="flex gap-2 items-start">
                <span class="text-purple-500 font-bold shrink-0">✓</span>
                <span><strong>CTA:</strong> Ajak penonton langsung klik keranjang kuning atau tombol beli!</span>
              </li>
            </ul>
          </div>

          <!-- Card 5: Hal yang Dilarang -->
          <div class="bg-white p-5 sm:p-6 rounded-2xl shadow-sm border border-rose-50 md:col-span-1 lg:col-span-2">
            <div class="flex items-center gap-3 mb-3">
              <div class="w-9 h-9 rounded-xl bg-red-50 text-red-600 flex items-center justify-center font-bold text-sm shrink-0">
                05
              </div>
              <h3 class="font-bold text-slate-800 text-sm sm:text-base">❌ LARANGAN UTAMA SHOOTING</h3>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-4 text-xs sm:text-sm text-slate-600">
              <div class="space-y-2.5">
                <div class="flex gap-2 items-start">
                  <span class="text-red-500 font-bold shrink-0">❌</span>
                  <span><strong>Hindari Jarak Jauh:</strong> Jangan sering mengambil rekaman seluruh badan. Fokus di area mata.</span>
                </div>
                <div class="flex gap-2 items-start">
                  <span class="text-red-500 font-bold shrink-0">❌</span>
                  <span><strong>Kamera Tidak Stabil:</strong> Hindari menggerakkan kamera terlalu cepat agar tidak buram.</span>
                </div>
              </div>
              <div class="p-3.5 bg-rose-50/70 rounded-xl border border-rose-100">
                <p class="font-bold text-rose-700 text-[11px] uppercase mb-1 flex items-center gap-1">
                  <i data-lucide="mic" class="w-3 h-3"></i> Narasi Cadangan:
                </p>
                <p class="italic text-slate-700 text-xs leading-relaxed">
                  "Lihat bulu mata ini! Pas dipakai langsung bikin mata keliatan lebih besar, super lembut, nggak gampang turun seharian, dan pas banget buat pemula!"
                </p>
              </div>
            </div>
          </div>

        </div>
      </section>

      <!-- Section 2: Galeri Video Kreatif -->
      <section class="border-t border-rose-100 pt-10">
        <div class="text-center max-w-xl mx-auto mb-8">
          <h2 class="text-2xl sm:text-3xl font-extrabold text-slate-800 tracking-tight">
            Galeri Referensi Video
          </h2>
          <p class="text-slate-500 text-xs sm:text-sm mt-1.5">
            Gunakan filter di bawah untuk mengelompokkan kategori video.
          </p>

          <!-- Filter Buttons -->
          <div class="flex flex-wrap justify-center gap-2 mt-5">
            <button onclick="filterVideos('all')" id="btn-all" class="px-4 py-2.5 rounded-full text-xs font-semibold bg-rose-500 text-white shadow-sm transition active:scale-95">
              Semua Video
            </button>
            <button onclick="filterVideos('rekomendasi')" id="btn-rekomendasi" class="px-4 py-2.5 rounded-full text-xs font-semibold bg-white text-slate-600 border border-slate-200 hover:bg-slate-50 transition active:scale-95">
              👍 Direkomendasikan
            </button>
            <button onclick="filterVideos('hindari')" id="btn-hindari" class="px-4 py-2.5 rounded-full text-xs font-semibold bg-white text-slate-600 border border-slate-200 hover:bg-slate-50 transition active:scale-95">
              ❌ Hindari
            </button>
          </div>
        </div>

        <!-- Video Grid Container (Optimasi Pas di HP/Vertikal) -->
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6" id="gallery-grid">
          
          <!-- Video 1 -->
          <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-100 card-rekomendasi flex flex-col" data-category="rekomendasi">
            <!-- Wadah tinggi h-[420px] + object-contain membuat video vertikal pas -->
            <div class="relative w-full h-[420px] sm:h-[480px] bg-black flex items-center justify-center">
              <video class="w-full h-full object-contain" controls playsinline webkit-playsinline preload="metadata">
                <source src="https://files.catbox.moe/5bvzl0.mp4" type="video/mp4">
              </video>
              <div class="absolute top-2.5 left-2.5 bg-emerald-500 text-white text-[10px] uppercase font-bold tracking-wider px-2.5 py-1 rounded-full shadow flex items-center gap-1 pointer-events-none z-10">
                <span class="w-1.5 h-1.5 bg-white rounded-full animate-ping"></span> ✨ Rekomendasi
              </div>
            </div>
            <div class="p-4 sm:p-5 flex-grow">
              <h3 class="font-bold text-slate-800 text-sm sm:text-base mb-1">✨ VT Rekomendasi Utama</h3>
              <p class="text-slate-500 text-xs leading-relaxed">Sudut pengambilan, pencahayaan, dan kejelasan visual yang sangat direkomendasikan.</p>
            </div>
          </div>

          <!-- Video 2 -->
          <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-100 card-rekomendasi flex flex-col" data-category="rekomendasi">
            <div class="relative w-full h-[420px] sm:h-[480px] bg-black flex items-center justify-center">
              <video class="w-full h-full object-contain" controls playsinline webkit-playsinline preload="metadata">
                <source src="https://files.catbox.moe/hwc6m9.mp4" type="video/mp4">
              </video>
              <div class="absolute top-2.5 left-2.5 bg-emerald-500 text-white text-[10px] uppercase font-bold tracking-wider px-2.5 py-1 rounded-full shadow flex items-center gap-1 pointer-events-none z-10">
                <span class="w-1.5 h-1.5 bg-white rounded-full animate-ping"></span> ✨ Hasil Bagus
              </div>
            </div>
            <div class="p-4 sm:p-5 flex-grow">
              <h3 class="font-bold text-slate-800 text-sm sm:text-base mb-1">✨ VT Hasil Sempurna</h3>
              <p class="text-slate-500 text-xs leading-relaxed">Menunjukkan kualitas detail bulu mata yang jelas dengan pencahayaan yang stabil.</p>
            </div>
          </div>

          <!-- Video 3 -->
          <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-100 card-rekomendasi flex flex-col" data-category="rekomendasi">
            <div class="relative w-full h-[420px] sm:h-[480px] bg-black flex items-center justify-center">
              <video class="w-full h-full object-contain" controls playsinline webkit-playsinline preload="metadata">
                <source src="https://files.catbox.moe/i1glku.mp4" type="video/mp4">
              </video>
              <div class="absolute top-2.5 left-2.5 bg-indigo-500 text-white text-[10px] uppercase font-bold tracking-wider px-2.5 py-1 rounded-full shadow flex items-center gap-1 pointer-events-none z-10">
                <span class="w-1.5 h-1.5 bg-white rounded-full animate-ping"></span> ✨ Try On
              </div>
            </div>
            <div class="p-4 sm:p-5 flex-grow">
              <h3 class="font-bold text-slate-800 text-sm sm:text-base mb-1">✨ VT Try On & Review</h3>
              <p class="text-slate-500 text-xs leading-relaxed">Fokus dekat pada hasil akhir pemasangan produk di mata. Transisi mulus.</p>
            </div>
          </div>

          <!-- Video 4 -->
          <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-100 card-hindari flex flex-col" data-category="hindari">
            <div class="relative w-full h-[420px] sm:h-[480px] bg-black flex items-center justify-center">
              <video class="w-full h-full object-contain filter grayscale-[10%]" controls playsinline webkit-playsinline preload="metadata">
                <source src="https://files.catbox.moe/n1dddf.mp4" type="video/mp4">
              </video>
              <div class="absolute top-2.5 left-2.5 bg-red-500 text-white text-[10px] uppercase font-bold tracking-wider px-2.5 py-1 rounded-full shadow flex items-center gap-1 pointer-events-none z-10">
                ❌ Kurang Sesuai
              </div>
            </div>
            <div class="p-4 sm:p-5 flex-grow">
              <h3 class="font-bold text-slate-800 text-sm sm:text-base mb-1">❌ Kurang Direkomendasikan</h3>
              <p class="text-slate-500 text-xs leading-relaxed">Contoh yang sebaiknya dihindari karena jarak pengambilan gambar terlalu jauh.</p>
            </div>
          </div>

          <!-- Video 5 -->
          <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-100 card-hindari flex flex-col" data-category="hindari">
            <div class="relative w-full h-[420px] sm:h-[480px] bg-black flex items-center justify-center">
              <video class="w-full h-full object-contain filter grayscale-[10%]" controls playsinline webkit-playsinline preload="metadata">
                <source src="https://files.catbox.moe/qm09z8.mp4" type="video/mp4">
              </video>
              <div class="absolute top-2.5 left-2.5 bg-red-500 text-white text-[10px] uppercase font-bold tracking-wider px-2.5 py-1 rounded-full shadow flex items-center gap-1 pointer-events-none z-10">
                ❌ Sudut Buruk
              </div>
            </div>
            <div class="p-4 sm:p-5 flex-grow">
              <h3 class="font-bold text-slate-800 text-sm sm:text-base mb-1">❌ Sudut Kurang Tepat</h3>
              <p class="text-slate-500 text-xs leading-relaxed">Contoh angle kamera yang membelakangi cahaya sehingga detail kurang jelas.</p>
            </div>
          </div>

          <!-- Video 6 -->
          <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-slate-100 card-hindari flex flex-col" data-category="hindari">
            <div class="relative w-full h-[420px] sm:h-[480px] bg-black flex items-center justify-center">
              <video class="w-full h-full object-contain filter grayscale-[10%]" controls playsinline webkit-playsinline preload="metadata">
                <source src="https://files.catbox.moe/v4joba.mp4" type="video/mp4">
              </video>
              <div class="absolute top-2.5 left-2.5 bg-red-500 text-white text-[10px] uppercase font-bold tracking-wider px-2.5 py-1 rounded-full shadow flex items-center gap-1 pointer-events-none z-10">
                ❌ Dibawah Standar
              </div>
            </div>
            <div class="p-4 sm:p-5 flex-grow">
              <h3 class="font-bold text-slate-800 text-sm sm:text-base mb-1">❌ Tidak Sesuai Kriteria</h3>
              <p class="text-slate-500 text-xs leading-relaxed">Gerakan kamera terlalu cepat dan ketidakstabilan fokus merusak pandangan visual.</p>
            </div>
          </div>

        </div>
      </section>

      <!-- Section 3: Call to Action -->
      <section class="mt-12 bg-gradient-to-r from-rose-500 to-pink-500 text-white p-6 sm:p-10 rounded-3xl text-center shadow-lg relative overflow-hidden">
        <div class="relative z-10 max-w-xl mx-auto">
          <h3 class="text-xl sm:text-3xl font-extrabold mb-2 leading-tight">Siap Membuat Video Terbaik Anda?</h3>
          <p class="text-rose-50 text-xs sm:text-sm mb-6 leading-relaxed">
            Tingkatkan engagement konten Anda dengan menerapkan tips-tips sederhana di atas!
          </p>
          <a href="#" class="w-full sm:w-auto inline-flex justify-center items-center gap-2 bg-white text-rose-600 px-6 py-3.5 rounded-full font-bold text-sm shadow-md hover:bg-rose-50 active:scale-95 transition duration-200">
            <i data-lucide="download" class="w-4 h-4"></i> Unduh Panduan PDF
          </a>
        </div>
      </section>

    </main>

    <!-- Footer -->
    <footer class="bg-white border-t border-rose-100 py-6 text-center mt-8">
      <div class="max-w-7xl mx-auto px-4 flex flex-col items-center justify-center gap-1 sm:flex-row sm:justify-between">
        <div class="flex items-center gap-2">
          <span class="text-rose-500 font-bold tracking-wider text-sm">BLINKY PAWKY</span>
          <span class="text-[11px] text-slate-400">Lash Studio</span>
        </div>
        <p class="text-[11px] text-slate-400">&copy; 2026 Blinky Pawky Lash Studio. All rights reserved.</p>
      </div>
    </footer>

    <!-- JavaScript Filter & Icons -->
    <script>
      lucide.createIcons();

      function filterVideos(category) {
        const cards = document.querySelectorAll('#gallery-grid > div');
        const btnAll = document.getElementById('btn-all');
        const btnRekomendasi = document.getElementById('btn-rekomendasi');
        const btnHindari = document.getElementById('btn-hindari');

        [btnAll, btnRekomendasi, btnHindari].forEach(btn => {
          btn.classList.remove('bg-rose-500', 'text-white', 'shadow-sm');
          btn.classList.add('bg-white', 'text-slate-600', 'border', 'border-slate-200', 'hover:bg-slate-50');
        });

        const activeBtn = document.getElementById(`btn-${category}`);
        activeBtn.classList.remove('bg-white', 'text-slate-600', 'border', 'border-slate-200', 'hover:bg-slate-50');
        activeBtn.classList.add('bg-rose-500', 'text-white', 'shadow-sm');

        cards.forEach(card => {
          if (category === 'all' || card.getAttribute('data-category') === category) {
            card.style.display = 'flex';
          } else {
            card.style.display = 'none';
          }
        });
      }
    </script>
  </body>
</html>
