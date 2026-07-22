[index.html](https://github.com/user-attachments/files/30261264/index.html)
<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Albert Refandi Turnip - Portofolio Hukum & Legal</title>
    <!-- Tailwind CSS via CDN -->
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased selection:bg-indigo-950 selection:text-white">

    <!-- NAVIGATION BAR -->
    <nav class="sticky top-0 z-50 bg-white/80 backdrop-blur-md border-b border-slate-100">
        <div class="max-w-5xl mx-auto px-6 h-16 flex items-center justify-between">
            <a href="#" class="font-bold text-lg tracking-tight text-slate-900">ART<span class="text-indigo-600">.</span></a>
            <div class="flex gap-6 text-sm font-medium text-slate-600">
                <a href="#about" class="hover:text-slate-900 transition-colors">Tentang</a>
                <a href="#experience" class="hover:text-slate-900 transition-colors">Pengalaman</a>
                <a href="#skills" class="hover:text-slate-900 transition-colors">Keahlian</a>
                <a href="#contact" class="hover:text-slate-900 transition-colors">Kontak</a>
            </div>
        </div>
    </nav>

    <!-- HERO SECTION -->
    <section class="max-w-5xl mx-auto px-6 pt-20 pb-16 md:py-32 flex flex-col-reverse md:flex-row items-center justify-between gap-12">
        <div class="flex-1 space-y-6 text-center md:text-left">
            <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-indigo-50 border border-indigo-100 text-xs font-medium text-indigo-950">
                <span class="w-2 h-2 rounded-full bg-emerald-500 animate-pulse"></span>
                Terbuka untuk Magang & Entry-Level
            </div>
            <h1 class="text-4xl md:text-5xl font-extrabold tracking-tight text-slate-900 leading-tight">
                Albert Refandi Turnip, <span class="text-indigo-950 font-semibold text-3xl md:text-4xl block mt-1 text-slate-600">S.H.</span>
            </h1>
            <p class="text-lg text-slate-600 max-w-xl mx-auto md:mx-0">
                Lulusan S1 Hukum Universitas Trisakti yang berfokus pada hukum bisnis, tata kelola perusahaan, dan kepatuhan regulasi.
            </p>
            <div class="flex flex-wrap gap-4 justify-center md:justify-start pt-2">
                <a href="#contact" class="px-6 py-3 rounded-xl bg-slate-900 text-white font-medium shadow-sm hover:bg-indigo-950 transition-all text-sm">
                    Hubungi Saya
                </a>
                <a href="#experience" class="px-6 py-3 rounded-xl bg-white border border-slate-200 text-slate-700 font-medium hover:bg-slate-50 transition-all text-sm">
                    Lihat Pengalaman
                </a>
            </div>
        </div>
        <div class="w-48 h-48 md:w-64 md:h-64 rounded-2xl overflow-hidden shadow-xl border-4 border-white bg-slate-200 shrink-0">
            <!-- Ganti placeholder dengan foto asli jika sudah di-host -->
            <img src="./profil.jpg" alt="Albert Refandi Turnip" class="w-full h-full object-cover">
        </div>
    </section>

    <!-- ABOUT ME SECTION -->
    <section id="about" class="bg-white border-y border-slate-100 py-20">
        <div class="max-w-5xl mx-auto px-6">
            <h2 class="text-xs font-bold tracking-widest text-indigo-950 uppercase mb-3">Tentang Saya</h2>
            <div class="grid md:grid-cols-3 gap-8 items-start">
                <div class="md:col-span-2 space-y-4 text-slate-600 leading-relaxed">
                    <p>
                        Saya memiliki motivasi tinggi untuk berkembang di lingkungan profesional yang serba cepat. Berbekal latar belakang akademis dari Universitas Trisakti, saya memiliki ketertarikan kuat dalam melakukan penelitian hukum, serta penyusunan dan peninjauan kontrak bisnis.
                    </p>
                    <p>
                        Saat ini, saya aktif mencari kesempatan untuk berkontribusi dan belajar lebih dalam melalui posisi tingkat awal atau magang di bidang Hukum Perusahaan (Corporate Law), Firma Hukum (Law Firm), maupun Urusan Regulasi (Regulatory Affairs).
                    </p>
                </div>
                <div class="bg-slate-50 p-6 rounded-2xl border border-slate-100 space-y-4">
                    <h3 class="font-semibold text-slate-900 text-sm tracking-wide uppercase">Pendidikan</h3>
                    <div>
                        <p class="font-bold text-slate-900 text-base">Universitas Trisakti</p>
                        <p class="text-sm text-slate-600">S1 Hukum (2021 - 2026)</p>
                        <div class="mt-2 inline-block px-2.5 py-0.5 text-xs font-semibold bg-indigo-50 border border-indigo-100 text-indigo-950 rounded-md">
                            IPK: 3.04
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- EXPERIENCE & PROJECTS SECTION -->
    <section id="experience" class="max-w-5xl mx-auto px-6 py-20">
        <h2 class="text-xs font-bold tracking-widest text-indigo-950 uppercase mb-10">Pengalaman Kerja & Organisasi</h2>
        
        <div class="grid md:grid-cols-2 gap-6">
            <!-- Kerja 1 -->
            <div class="bg-white p-6 rounded-2xl border border-slate-100 shadow-xs flex flex-col justify-between hover:border-slate-200 transition-all">
                <div>
                    <span class="text-xs font-semibold text-indigo-600">Jul 2024 - Agu 2024</span>
                    <h3 class="font-bold text-lg text-slate-900 mt-1">Magang Kerja</h3>
                    <p class="text-sm font-medium text-slate-500 mb-4">Pengadilan Negeri Tangerang Kelas 1 A Khusus</p>
                    <p class="text-slate-600 text-sm leading-relaxed">
                        Melakukan pendaftaran dan pencatatan berkas sidang serta membantu penyelesaian tugas-tugas administratif kepaniteraan hukum lainnya secara akurat.
                    </p>
                </div>
            </div>

            <!-- Kerja 2 -->
            <div class="bg-white p-6 rounded-2xl border border-slate-100 shadow-xs flex flex-col justify-between hover:border-slate-200 transition-all">
                <div>
                    <span class="text-xs font-semibold text-indigo-600">Jan 2025 - Sep 2025</span>
                    <h3 class="font-bold text-lg text-slate-900 mt-1">Legal & Visual Specialist</h3>
                    <p class="text-sm font-medium text-slate-500 mb-4">PT Eksplorasi Visual Naralas</p>
                    <ul class="text-slate-600 text-sm space-y-1 list-disc list-inside">
                        <li>Membantu penyusunan dan peninjauan dokumen kerja sama (MoU dan surat perjanjian kerja sama).</li>
                        <li>Membantu melakukan editing foto visual untuk mendukung operasional dan branding perusahaan.</li>
                    </ul>
                </div>
            </div>

            <!-- Kerja 3 -->
            <div class="bg-white p-6 rounded-2xl border border-slate-100 shadow-xs flex flex-col justify-between hover:border-slate-200 transition-all">
                <div>
                    <span class="text-xs font-semibold text-indigo-600">Mar 2024 - Apr 2025</span>
                    <h3 class="font-bold text-lg text-slate-900 mt-1">Admin Sosial Media (Paruh Waktu)</h3>
                    <p class="text-sm font-medium text-slate-500 mb-4">HIPMI Universitas Trisakti</p>
                    <p class="text-slate-600 text-sm leading-relaxed">
                        Bertanggung jawab dalam menciptakan, mengelola, dan menyebarkan konten yang relevan serta menarik kepada audiens target melalui berbagai platform media sosial resmi organisasi.
                    </p>
                </div>
            </div>

            <!-- Organisasi 1 -->
            <div class="bg-white p-6 rounded-2xl border border-slate-100 shadow-xs flex flex-col justify-between hover:border-slate-200 transition-all">
                <div>
                    <span class="text-xs font-semibold text-indigo-600">Feb 2023 - Agu 2023</span>
                    <h3 class="font-bold text-lg text-slate-900 mt-1">Deputi Kementerian Aparatur</h3>
                    <p class="text-sm font-medium text-slate-500 mb-4">Kepresidenan Mahasiswa Universitas Trisakti</p>
                    <p class="text-slate-600 text-sm leading-relaxed">
                        Bertanggung jawab dalam pengawasan dan peninjauan seluruh kegiatan internal kabinet dengan menyusun SOP Kabinet, mengoordinasikan recruitment anggota, serta mengelola sistem absensi.
                    </p>
                </div>
            </div>

            <!-- Organisasi 2 -->
            <div class="bg-white p-6 rounded-2xl border border-slate-100 shadow-xs flex flex-col justify-between hover:border-slate-200 transition-all md:col-span-2">
                <div>
                    <span class="text-xs font-semibold text-indigo-600">Okt 2023 - Apr 2024</span>
                    <h3 class="font-bold text-lg text-slate-900 mt-1">Staff Biro Penelitian dan Pengembangan Organisasi</h3>
                    <p class="text-sm font-medium text-slate-500 mb-4">Badan Eksekutif Mahasiswa Universitas Trisakti</p>
                    <p class="text-slate-600 text-sm leading-relaxed">
                        Bertindak sebagai administrator utama yang bertanggung jawab penuh terhadap pengelolaan dokumen, data organisasi, serta alur komunikasi dan informasi eksternal maupun internal biro.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- SKILLS SECTION (BADGE) -->
    <section id="skills" class="bg-white border-y border-slate-100 py-20">
        <div class="max-w-5xl mx-auto px-6">
            <h2 class="text-xs font-bold tracking-widest text-indigo-950 uppercase mb-8">Keahlian & Kompetensi</h2>
            
            <div class="space-y-6">
                <div>
                    <h3 class="text-sm font-semibold text-slate-400 uppercase tracking-wider mb-3">Teknikal & Perangkat Lunak</h3>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-3 py-1.5 bg-slate-50 border border-slate-200 rounded-lg text-sm font-medium text-slate-700">Microsoft Office</span>
                        <span class="px-3 py-1.5 bg-slate-50 border border-slate-200 rounded-lg text-sm font-medium text-slate-700">Google Suite</span>
                        <span class="px-3 py-1.5 bg-slate-50 border border-slate-200 rounded-lg text-sm font-medium text-slate-700">Google Forms</span>
                        <span class="px-3 py-1.5 bg-slate-50 border border-slate-200 rounded-lg text-sm font-medium text-slate-700">Canva</span>
                        <span class="px-3 py-1.5 bg-slate-50 border border-slate-200 rounded-lg text-sm font-medium text-slate-700">Adobe Lightroom</span>
                        <span class="px-3 py-1.5 bg-slate-50 border border-slate-200 rounded-lg text-sm font-medium text-slate-700">PicsArt</span>
                    </div>
                </div>

                <div>
                    <h3 class="text-sm font-semibold text-slate-400 uppercase tracking-wider mb-3">Kemampuan Personal</h3>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-3 py-1.5 bg-indigo-50 border border-indigo-100 rounded-lg text-sm font-medium text-indigo-950">Komunikasi Efektif</span>
                        <span class="px-3 py-1.5 bg-indigo-50 border border-indigo-100 rounded-lg text-sm font-medium text-indigo-950">Kerjasama Tim</span>
                        <span class="px-3 py-1.5 bg-indigo-50 border border-indigo-100 rounded-lg text-sm font-medium text-indigo-950">Kemampuan Beradaptasi</span>
                        <span class="px-3 py-1.5 bg-indigo-50 border border-indigo-100 rounded-lg text-sm font-medium text-indigo-950">Kreativitas</span>
                    </div>
                </div>

                <div>
                    <h3 class="text-sm font-semibold text-slate-400 uppercase tracking-wider mb-3">Bahasa</h3>
                    <div class="flex flex-wrap gap-4">
                        <div class="text-sm"><span class="font-semibold text-slate-800">Bahasa Indonesia</span> <span class="text-slate-400">(Native)</span></div>
                        <div class="text-sm"><span class="font-semibold text-slate-800">Bahasa Inggris</span> <span class="text-slate-400">(Passive)</span></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CONTACT SECTION -->
    <section id="contact" class="max-w-5xl mx-auto px-6 py-20 text-center">
        <h2 class="text-xs font-bold tracking-widest text-indigo-950 uppercase mb-3">Hubungi Saya</h2>
        <h3 class="text-2xl font-bold text-slate-900 mb-6">Mari Terkoneksi & Bekerjasama</h3>
        <p class="text-slate-600 max-w-md mx-auto mb-10 text-sm">
            Silakan hubungi saya melalui salah satu kontak di bawah ini untuk mendiskusikan peluang karir, magang, atau kolaborasi hukum lainnya.
        </p>

        <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-4 max-w-3xl mx-auto">
            <a href="mailto:albertrefandi7@gmail.com" class="p-4 bg-white rounded-xl border border-slate-100 shadow-2xs hover:border-slate-300 transition-all flex flex-col items-center">
                <span class="text-xs font-semibold text-slate-400 mb-1">Email Resmi</span>
                <span class="text-sm font-medium text-indigo-950 break-all">albertrefandi7@gmail.com</span>
            </a>
            <a href="https://wa.me/6287872273223" target="_blank" class="p-4 bg-white rounded-xl border border-slate-100 shadow-2xs hover:border-slate-300 transition-all flex flex-col items-center">
                <span class="text-xs font-semibold text-slate-400 mb-1">WhatsApp</span>
                <span class="text-sm font-medium text-indigo-950">+62 878-7227-3223</span>
            </a>
            <div class="p-4 bg-white rounded-xl border border-slate-100 shadow-2xs sm:col-span-2 md:col-span-1 flex flex-col items-center justify-center">
                <span class="text-xs font-semibold text-slate-400 mb-1">Lokasi Domisili</span>
                <span class="text-sm font-medium text-slate-700 text-center">Grogol, Jakarta Barat, DKI Jakarta</span>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="border-t border-slate-100 py-8 bg-white text-center text-xs text-slate-400">
        <div class="max-w-5xl mx-auto px-6">
            <p>&copy; 2026 Albert Refandi Turnip, S.H. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>
