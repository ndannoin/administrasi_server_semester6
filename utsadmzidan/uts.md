<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portofolio - Zaidan Alif Firdaus</title>

<script src="https://cdn.tailwindcss.com"></script>

<!-- AOS -->
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>

<script>
tailwind.config = {
    theme: {
        extend: {
            colors: {
                primary: '#3b82f6',
                secondary: '#1f2937',
                dark: '#020617'
            }
        }
    }
}
</script>

<style>
::-webkit-scrollbar { width: 8px; }
::-webkit-scrollbar-thumb { background: #3b82f6; }
</style>

</head>

<body class="bg-dark text-white font-sans">

<!-- NAVBAR -->
<nav class="fixed w-full bg-dark/90 border-b border-gray-800 z-50" data-aos="fade-down">
    <div class="container mx-auto px-6 py-4">
        <h1 class="font-bold">portfolio</h1>
    </div>
</nav>

<!-- HERO -->
<header class="min-h-screen flex items-center pt-20">
<div class="container mx-auto px-6 grid md:grid-cols-2 gap-10 items-center">
    <!-- FOTO -->
    <div class="flex justify-center" data-aos="zoom-in">
        <img src="aWhatsApp Image 2026-04-15 at 16.05.46.jpeg"
        class="rounded-full w-60 h-60 border-4 border-primary shadow-xl hover:scale-110 transition duration-500">
    </div>
    <!-- INFO -->
    <div data-aos="fade-left">
        <h1 class="text-5xl font-bold mb-2">
            Zaidan <br>
            <span class="text-primary">Firdaus</span>
        </h1>
        <p class="text-gray-400 mb-4">Social Media</p>
        <p class="text-gray-400">@phileyoudan</p>
        <p class="text-gray-400 mb-6">Subang, Jawa Barat</p>
        <a href="#" class="bg-primary px-6 py-3 rounded-lg hover:bg-blue-600 transition">
            Contact Me
        </a>
    </div>

</div>
</header>

<!-- ABOUT -->
<section class="py-20 bg-secondary/50 text-center" data-aos="fade-up">
<div class="container mx-auto px-6">
<h2 class="text-3xl font-bold mb-6">About Me</h2>

<p class="text-gray-400 max-w-2xl mx-auto">
Saya adalah lulusan SMK Darul Ma'arif yang memiliki minat dalam bidang sosial media dan teknologi.
Mampu bekerja secara individu maupun tim serta memiliki komunikasi yang baik.
</p>
</div>
</section>

<!-- GRID -->
<section class="py-20 px-6">
<div class="grid md:grid-cols-3 gap-8">

<!-- Pendidikan -->
<div class="bg-gray-900 p-6 rounded-xl shadow-lg hover:scale-105 transition" data-aos="zoom-in">
<h3 class="text-xl font-bold text-primary mb-3">Pendidikan</h3>
<ul class="text-gray-400">
<li>SDN Margaluyu</li>
<li>SMPN 1 Pamanukan</li>
<li>SMK Darul Ma'arif</li>
</ul>
</div>

<!-- Skill -->
<div class="bg-gray-900 p-6 rounded-xl shadow-lg hover:scale-105 transition" data-aos="zoom-in" data-aos-delay="100">
<h3 class="text-xl font-bold text-primary mb-3">Keterampilan</h3>
<ul class="text-gray-400">
<li>Olahraga</li>
<li>Bersosialisasi</li>
<li>Berorganisasi</li>
</ul>
</div>

<!-- Sertifikat -->
<div class="bg-gray-900 p-6 rounded-xl shadow-lg hover:scale-105 transition" data-aos="zoom-in" data-aos-delay="200">
<h3 class="text-xl font-bold text-primary mb-3">Sertifikat</h3>
<ul class="text-gray-400">
<li>Microsoft Office</li>
<li>Word & Excel</li>
<li>PKL</li>
</ul>
</div>

</div>
</section>

<!-- EXTRA -->
<section class="py-20 bg-secondary/50 px-6">
<div class="grid md:grid-cols-2 gap-8">

<div class="bg-dark p-6 rounded-xl border border-gray-800" data-aos="fade-right">
<h3 class="text-xl font-bold text-primary mb-3">Organisasi</h3>
<p class="text-gray-400">Futsal</p>
</div>

<div class="bg-dark p-6 rounded-xl border border-gray-800" data-aos="fade-left">
<h3 class="text-xl font-bold text-primary mb-3">Hobi</h3>
<p class="text-gray-400">Musik, Game, Futsal</p>
</div>

</div>
</section>

<!-- FOOTER -->
<footer class="text-center py-10 border-t border-gray-800" data-aos="fade-up">
<p class="text-gray-400">Zaidan Alif Firdaus</p>
<p class="text-primary font-bold">NIM: 2388010038</p>
</footer>

<script>
AOS.init({
    duration: 1000,
    once: true
});
</script>

</body>
</html>