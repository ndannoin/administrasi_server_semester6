<!DOCTYPE html>

<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio - Zaidan Alif Firdaus</title>

```
<meta name="description" content="Portofolio Zaidan Alif Firdaus">

<script src="https://cdn.tailwindcss.com"></script>

<script>
    tailwind.config = {
        theme: {
            extend: {
                colors: {
                    primary: '#22c55e', 
                    secondary: '#1e293b',
                    dark: '#0f172a',
                    light: '#f8fafc',
                }
            }
        }
    }
</script>

<style>
    ::-webkit-scrollbar { width: 8px; }
    ::-webkit-scrollbar-track { background: #0f172a; }
    ::-webkit-scrollbar-thumb { background: #334155; border-radius: 4px; }
    ::-webkit-scrollbar-thumb:hover { background: #22c55e; }
</style>
```

</head>

<body class="bg-dark text-light font-sans antialiased">

<!-- Navbar -->

<nav class="fixed w-full z-50 bg-dark/90 backdrop-blur-md border-b border-slate-800">
    <div class="container mx-auto px-6 py-4 flex justify-between items-center">
        <h1 class="text-xl font-bold text-white">zaidan.portfolio</h1>
        <ul class="hidden md:flex space-x-8 text-sm text-slate-400">
            <li><a href="#about" class="hover:text-primary">About</a></li>
            <li><a href="#skills" class="hover:text-primary">Skills</a></li>
            <li><a href="#education" class="hover:text-primary">Education</a></li>
        </ul>
    </div>
</nav>

<!-- Hero -->

<header class="min-h-screen flex items-center justify-center pt-20">
    <div class="text-center">
        <img src="zaidan.jpg" class="rounded-full mx-auto mb-6 border-4 border-slate-800">
        <h1 class="text-4xl md:text-5xl font-bold mb-3">Zaidan Alif Firdaus</h1>
        <p class="text-slate-400 mb-2">Mahasiswa & Pecinta Olahraga ⚽</p>
        <p class="text-primary font-mono">NIM: 2388010038</p>
        <p class="text-slate-500 mt-2">📍 Subang, Jawa Barat</p>
    </div>
</header>

<!-- About -->

<section id="about" class="py-16 text-center bg-secondary/50">
    <h2 class="text-3xl font-bold mb-6">Biodata</h2>
    <p class="max-w-2xl mx-auto text-slate-300">
        Saya adalah mahasiswa dengan minat di bidang olahraga dan game. 
        Saya menyukai permainan sepak bola baik secara langsung maupun digital seperti eFootball dan Mobile Legends.
        Selain itu, saya juga senang bermain game offline seperti PS2, PS3, dan PS4 khususnya game bola (PES/eFootball).
    </p>
</section>

<!-- Skills -->

<section id="skills" class="py-16 text-center">
    <h2 class="text-3xl font-bold mb-10">Keahlian</h2>

```
<div class="flex flex-wrap justify-center gap-6">
    <div class="bg-dark p-6 rounded border">⚽ Olahraga (Sepak Bola)</div>
    <div class="bg-dark p-6 rounded border">🎮 Mobile Legends</div>
    <div class="bg-dark p-6 rounded border">🎮 eFootball</div>
    <div class="bg-dark p-6 rounded border">🕹️ PS2 / PS3 / PS4 (Game Bola)</div>
</div>
```

</section>

<!-- Education -->

<section id="education" class="py-16 bg-secondary/50 text-center">
    <h2 class="text-3xl font-bold mb-10">Riwayat Pendidikan</h2>

```
<div class="space-y-4 text-slate-300">
    <p>🏫 SDN Margaluyu, Kec. Subang</p>
    <p>🏫 SMPN 1 Pamanukan, Subang</p>
    <p>🏫 SMK Darul Ma'arif, Pamanukan</p>
    <p>🎓 UIN SSC (Saat ini)</p>
</div>
```

</section>

<!-- Footer -->

<footer class="py-10 text-center border-t border-slate-800">
    <p class="text-slate-400 mb-2">Zaidan Alif Firdaus</p>
    <p class="text-primary font-mono mb-2">NIM: 2388010038</p>
    <p class="text-slate-500 text-sm">© 2026</p>
</footer>

</body>
</html>
