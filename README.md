# Ado
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BLUE ROSE • ADO</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');
        
        body {
            font-family: 'Press Start 2P', system-ui;
            background: linear-gradient(to bottom, #0a1428, #1a2a4a, #0f172a);
            color: #e0f2fe;
        }
        
        .neon-blue {
            text-shadow: 
                0 0 10px #60a5fa,
                0 0 20px #60a5fa,
                0 0 40px #3b82f6;
        }
        
        .rose-bg {
            background-image: 
                radial-gradient(circle at 25% 25%, rgba(74, 158, 255, 0.25) 0%, transparent 50%),
                radial-gradient(circle at 75% 75%, rgba(74, 158, 255, 0.18) 0%, transparent 50%);
        }
        
        .card {
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 0 40px rgba(96, 165, 250, 0.5);
        }
        
        .fact-item {
            position: relative;
        }
        .fact-item::before {
            content: '🌹';
            position: absolute;
            left: -30px;
            color: #60a5fa;
            opacity: 0.8;
            filter: hue-rotate(200deg) saturate(1.8);
        }
    </style>
</head>
<body class="overflow-x-hidden">
    <!-- Navbar -->
    <nav class="bg-black/90 backdrop-blur-md border-b border-blue-500/30 py-5 sticky top-0 z-50">
        <div class="max-w-6xl mx-auto px-6 flex items-center justify-between">
            <div class="flex items-center gap-3">
                <span class="text-4xl">🌹</span>
                <h1 class="text-3xl font-bold tracking-widest neon-blue">BLUE ROSE</h1>
            </div>
            <div class="flex gap-8 text-sm uppercase tracking-widest">
                <a href="#home" class="hover:text-blue-400 transition-colors">Inicio</a>
                <a href="#facts" class="hover:text-blue-400 transition-colors">Datos Curiosos</a>
                <a href="#career" class="hover:text-blue-400 transition-colors">Trayectoria</a>
                <a href="#gallery" class="hover:text-blue-400 transition-colors">Visuales</a>
            </div>
        </div>
    </nav>

    <!-- Hero -->
    <section id="home" class="min-h-screen flex items-center relative rose-bg">
        <div class="max-w-6xl mx-auto px-6 py-24 text-center">
            <div class="inline-flex items-center gap-3 bg-blue-950 border border-blue-400 px-6 py-3 mb-8 rounded-full">
                <span class="text-blue-400">🌹 OFFICIAL INSPIRED</span>
            </div>
            <h2 class="text-7xl md:text-8xl font-bold leading-none neon-blue mb-6">
                ADO
            </h2>
            <p class="text-2xl text-blue-200 max-w-2xl mx-auto">
                La voz que rompe el silencio.<br>
                La rosa azul que florece en la oscuridad.
            </p>
            <div class="mt-12 flex justify-center gap-6">
                <a href="https://www.universal-music.co.jp/ado/" target="_blank" 
                   class="bg-blue-600 hover:bg-blue-700 px-10 py-5 text-sm tracking-widest transition-all border border-blue-400">
                    SITIO OFICIAL
                </a>
            </div>
        </div>
        
        <div class="absolute bottom-12 left-1/2 text-blue-400 animate-bounce text-3xl">
            ↓
        </div>
    </section>

    <!-- Datos Curiosos -->
    <section id="facts" class="py-24 bg-black/70">
        <div class="max-w-6xl mx-auto px-6">
            <h2 class="text-center text-5xl mb-16 neon-blue">DATOS CURIOSOS</h2>
            
            <div class="grid md:grid-cols-2 gap-8">
                <div class="card bg-zinc-900/80 border border-blue-500/30 p-8 rounded-3xl fact-item">
                    <p class="text-blue-100">Su comida favorita es el <strong>sushi</strong>. Es una gran foodie y le encanta compartir fotos de sus comidas.</p>
                </div>
                
                <div class="card bg-zinc-900/80 border border-blue-500/30 p-8 rounded-3xl fact-item">
                    <p class="text-blue-100">A pesar de ser una gran estrella, es fanática de <strong>McDonald's</strong> y la comida rápida.</p>
                </div>
                
                <div class="card bg-zinc-900/80 border border-blue-500/30 p-8 rounded-3xl fact-item">
                    <p class="text-blue-100">En Minecraft le puso a su perro el nombre de <strong>"Michael Jackson"</strong>.</p>
                </div>
                
                <div class="card bg-zinc-900/80 border border-blue-500/30 p-8 rounded-3xl fact-item">
                    <p class="text-blue-100">Trabajó como <strong>barista</strong> antes de dedicarse 100% a la música.</p>
                </div>
                
                <div class="card bg-zinc-900/80 border border-blue-500/30 p-8 rounded-3xl fact-item">
                    <p class="text-blue-100">Es una gran fanática de las <strong>maid cafés</strong>. Le encantan las maids, colecciona figuras y juega dating sims de ese estilo.</p>
                </div>
                
                <div class="card bg-zinc-900/80 border border-blue-500/30 p-8 rounded-3xl fact-item">
                    <p class="text-blue-100">Toca <strong>piano y guitarra</strong>, aunque rara vez lo muestra públicamente.</p>
                </div>
                
                <div class="card bg-zinc-900/80 border border-blue-500/30 p-8 rounded-3xl fact-item">
                    <p class="text-blue-100">Mide <strong>157 cm</strong> y a veces bromea sobre su estatura.</p>
                </div>
                
                <div class="card bg-zinc-900/80 border border-blue-500/30 p-8 rounded-3xl fact-item">
                    <p class="text-blue-100">Es su propia crítica más dura: suele sentir mucha vergüenza al ver sus presentaciones en vivo.</p>
                </div>
                
                <div class="card bg-zinc-900/80 border border-blue-500/30 p-8 rounded-3xl fact-item">
                    <p class="text-blue-100">Le gusta la música de <strong>Bruno Mars</strong> y también escucha mucho K-pop en su tiempo libre.</p>
                </div>
                
                <div class="card bg-zinc-900/80 border border-blue-500/30 p-8 rounded-3xl fact-item">
                    <p class="text-blue-100">Produce un grupo de idols con temática de horror llamado <strong>Phantom Siita</strong> (empezó como broma de April Fools).</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Career -->
    <section id="career" class="py-24 bg-gradient-to-b from-transparent via-blue-950/30 to-transparent">
        <div class="max-w-6xl mx-auto px-6">
            <h2 class="text-center text-5xl mb-16 neon-blue">TRAYECTORIA</h2>
            
            <div class="space-y-12 max-w-3xl mx-auto">
                <div class="flex gap-8">
                    <div class="w-28 text-right text-blue-400 shrink-0">2017</div>
                    <div>
                        <p class="text-lg">Debut como utaite en Niconico con 14 años.</p>
                    </div>
                </div>
                <div class="flex gap-8">
                    <div class="w-28 text-right text-blue-400 shrink-0">2020</div>
                    <div>
                        <p class="text-lg">Debut mayor con <strong>"Usseewa"</strong>. Fenómeno viral.</p>
                    </div>
                </div>
                <div class="flex gap-8">
                    <div class="w-28 text-right text-blue-400 shrink-0">2022</div>
                    <div>
                        <p class="text-lg">Voz de Uta en <strong>One Piece Film: Red</strong>. Éxito mundial.</p>
                    </div>
                </div>
                <div class="flex gap-8">
                    <div class="w-28 text-right text-blue-400 shrink-0">2024-2026</div>
                    <div>
                        <p class="text-lg">Giras mundiales con sold-outs en grandes arenas.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Gallery -->
    <section id="gallery" class="py-24 bg-black/70">
        <div class="max-w-6xl mx-auto px-6">
            <h2 class="text-center text-5xl mb-16 neon-blue">VISUALES OFICIALES</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="card bg-zinc-900 border border-blue-500/30 rounded-3xl overflow-hidden">
                    <img src="https://via.placeholder.com/800x600/1e40af/bae6fd?text=ADO+Official+Art" alt="Ado Official" class="w-full h-80 object-cover">
                    <div class="p-6 text-center text-blue-200 text-sm">Ilustración oficial</div>
                </div>
                <div class="card bg-zinc-900 border border-blue-500/30 rounded-3xl overflow-hidden">
                    <img src="https://via.placeholder.com/800x600/172554/93c5fd?text=ADO+Silhouette" alt="Silhouette" class="w-full h-80 object-cover">
                    <div class="p-6 text-center text-blue-200 text-sm">Escenario con silueta</div>
                </div>
                <div class="card bg-zinc-900 border border-blue-500/30 rounded-3xl overflow-hidden">
                    <img src="https://via.placeholder.com/800x600/1e3a8a/cbd5e1?text=BLUE+ROSE" alt="Blue Rose" class="w-full h-80 object-cover">
                    <div class="p-6 text-center text-blue-200 text-sm">Motivo Rosa Azul</div>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-black py-16 border-t border-blue-500/30 text-center">
        <p class="text-blue-300">Fan page inspirada en Ado • Solo uso ilustrativo • Respeta los derechos de autor</p>
        <p class="mt-4 text-sm text-blue-400">🌹 La rosa azul florece en silencio 🌹</p>
    </footer>

    <script>
        console.log('%cBLUE ROSE 🌹 ADO', 'color: #60a5fa; font-size: 18px; font-family: monospace');
    </script>
</body>
</html>
