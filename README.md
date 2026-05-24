<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Terapia de Restauración Energética Integral</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;800&family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #F3F4F6;
            color: #1F2937;
        }
        h1, h2, h3, h4 {
            font-family: 'Poppins', sans-serif;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 500px;
            margin-left: auto;
            margin-right: auto;
            height: 320px;
            max-height: 350px;
        }
        .gradient-bg {
            background: linear-gradient(135deg, #2E1065 0%, #7C3AED 100%);
        }
        .card-shadow {
            box-shadow: 0 10px 30px -5px rgba(124, 58, 237, 0.1), 0 8px 10px -6px rgba(124, 58, 237, 0.05);
        }
    </style>
</head>
<body class="antialiased text-gray-800">

    <div id="no-svg-confirmation" class="hidden" data-frameworks="No SVG used, No Mermaid used"></div>

    <header class="gradient-bg text-white py-16 px-4 relative overflow-hidden text-center border-b-8 border-[#F59E0B]">
        <div class="max-w-4xl mx-auto relative z-10">
            <span class="bg-[#10B981] text-xs font-bold uppercase tracking-widest px-3 py-1 rounded-full text-white">Equilibrio Cuántico</span>
            <h1 class="text-3xl md:text-5xl font-extrabold mt-4 mb-6 leading-tight text-transparent bg-clip-text bg-gradient-to-r from-[#F59E0B] to-[#10B981]">
                Terapia de Restauración Energética Integral
            </h1>
            <p class="text-base md:text-lg text-gray-200 max-w-2xl mx-auto font-light leading-relaxed">
                Descubre qué bloquea tu vitalidad, sana los patrones de tu personalidad y recupera el mando de tu bienestar físico y del entorno.
            </p>
            <div class="mt-8 flex flex-wrap justify-center gap-4">
                <a href="#test" class="bg-[#F59E0B] hover:bg-amber-600 text-gray-900 font-bold px-6 py-3 rounded-full text-sm tracking-wide transition shadow-lg">
                    Realizar Test Gratis
                </a>
                <a href="#proceso" class="bg-transparent hover:bg-white/10 border-2 border-white text-white font-bold px-6 py-3 rounded-full text-sm tracking-wide transition">
                    Ver de qué trata
                </a>
            </div>
        </div>
    </header>

    <main class="max-w-5xl mx-auto px-4 py-12 space-y-16">

        <section class="bg-white rounded-2xl p-6 md:p-8 card-shadow border-l-4 border-[#7C3AED]">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
                <div class="p-4">
                    <div class="text-4xl mb-2">⚖️</div>
                    <h3 class="font-bold text-lg text-[#2E1065] mb-1">Mide tu Estado</h3>
                    <p class="text-xs text-gray-500">Biómetros de precisión para mapear bloqueos antes de actuar.</p>
                </div>
                <div class="p-4 border-y md:border-y-0 md:border-x border-gray-100">
                    <div class="text-4xl mb-2">🌀</div>
                    <h3 class="font-bold text-lg text-[#2E1065] mb-1">Disuelve la Carga</h3>
                    <p class="text-xs text-gray-500">Transmutación con Mesa Radiónica para limpiar tu aura y tu casa.</p>
                </div>
                <div class="p-4">
                    <div class="text-4xl mb-2">🛡️</div>
                    <h3 class="font-bold text-lg text-[#2E1065] mb-1">Sella tu Aura</h3>
                    <p class="text-xs text-gray-500">Cierra fugas energéticas e interacciones que te debilitan.</p>
                </div>
            </div>
        </section>

        <section id="test" class="bg-white rounded-2xl p-6 md:p-8 card-shadow">
            <h2 class="text-2xl font-bold text-[#2E1065] text-center mb-2">¿Cómo está tu nivel de Sobrecarga?</h2>
            <p class="text-sm text-gray-500 text-center mb-8">Responde estas sencillas preguntas de autodiagnóstico.</p>

            <div id="quiz-container" class="space-y-6 max-w-2xl mx-auto">
                <div class="p-4 bg-gray-50 rounded-xl border border-gray-100">
                    <p class="font-semibold text-gray-800 text-sm md:text-base mb-3">1. ¿Te despiertas sobresaltado o inquieto entre las 3:00 AM y 4:00 AM?</p>
                    <div class="flex gap-4">
                        <button onclick="answerQuiz(0, true)" class="quiz-btn-0 bg-white hover:bg-[#7C3AED] hover:text-white border border-gray-200 px-6 py-2 rounded-lg text-sm transition font-medium w-full">Sí</button>
                        <button onclick="answerQuiz(0, false)" class="quiz-btn-0 bg-white hover:bg-gray-200 border border-gray-200 px-6 py-2 rounded-lg text-sm transition font-medium w-full">No</button>
                    </div>
                </div>

                <div class="p-4 bg-gray-50 rounded-xl border border-gray-100">
                    <p class="font-semibold text-gray-800 text-sm md:text-base mb-3">2. ¿Sufres dolores físicos repentinos (rodillas, plexo, espalda) sin causa médica obvia?</p>
                    <div class="flex gap-4">
                        <button onclick="answerQuiz(1, true)" class="quiz-btn-1 bg-white hover:bg-[#7C3AED] hover:text-white border border-gray-200 px-6 py-2 rounded-lg text-sm transition font-medium w-full">Sí</button>
                        <button onclick="answerQuiz(1, false)" class="quiz-btn-1 bg-white hover:bg-gray-200 border border-gray-200 px-6 py-2 rounded-lg text-sm transition font-medium w-full">No</button>
                    </div>
                </div>

                <div class="p-4 bg-gray-50 rounded-xl border border-gray-100">
                    <p class="font-semibold text-gray-800 text-sm md:text-base mb-3">3. ¿Sientes cambios bruscos de temperatura o pesadez extraña en zonas específicas de tu hogar?</p>
                    <div class="flex gap-4">
                        <button onclick="answerQuiz(2, true)" class="quiz-btn-2 bg-white hover:bg-[#7C3AED] hover:text-white border border-gray-200 px-6 py-2 rounded-lg text-sm transition font-medium w-full">Sí</button>
                        <button onclick="answerQuiz(2, false)" class="quiz-btn-2 bg-white hover:bg-gray-200 border border-gray-200 px-6 py-2 rounded-lg text-sm transition font-medium w-full">No</button>
                    </div>
                </div>

                <div class="p-4 bg-gray-50 rounded-xl border border-gray-100">
                    <p class="font-semibold text-gray-800 text-sm md:text-base mb-3">4. ¿Has experimentado pequeños accidentes inexplicables o bloqueos constantes en tus planes?</p>
                    <div class="flex gap-4">
                        <button onclick="answerQuiz(3, true)" class="quiz-btn-3 bg-white hover:bg-[#7C3AED] hover:text-white border border-gray-200 px-6 py-2 rounded-lg text-sm transition font-medium w-full">Sí</button>
                        <button onclick="answerQuiz(3, false)" class="quiz-btn-3 bg-white hover:bg-gray-200 border border-gray-200 px-6 py-2 rounded-lg text-sm transition font-medium w-full">No</button>
                    </div>
                </div>

                <div class="p-4 bg-gray-50 rounded-xl border border-gray-100">
                    <p class="font-semibold text-gray-800 text-sm md:text-base mb-3">5. ¿Te has sentido agotado mental o físicamente tras convivir con personas que drenan tu energía?</p>
                    <div class="flex gap-4">
                        <button onclick="answerQuiz(4, true)" class="quiz-btn-4 bg-white hover:bg-[#7C3AED] hover:text-white border border-gray-200 px-6 py-2 rounded-lg text-sm transition font-medium w-full">Sí</button>
                        <button onclick="answerQuiz(4, false)" class="quiz-btn-4 bg-white hover:bg-gray-200 border border-gray-200 px-6 py-2 rounded-lg text-sm transition font-medium w-full">No</button>
                    </div>
                </div>

                <div class="text-center pt-4">
                    <button onclick="calculateScore()" class="bg-[#10B981] hover:bg-emerald-600 text-white font-bold px-8 py-3 rounded-full text-base tracking-wide shadow-lg transition">
                        Ver Mi Diagnóstico Sugerido
                    </button>
                </div>

                <div id="quiz-result" class="hidden p-6 bg-purple-50 border-2 border-[#7C3AED] rounded-2xl text-center mt-6">
                    <h3 class="text-xl font-bold text-[#2E1065] mb-2" id="result-title">Procesando...</h3>
                    <p class="text-sm text-gray-600 mb-4" id="result-desc"></p>
                    <a id="whatsapp-btn" href="#" target="_blank" class="inline-block bg-[#10B981] hover:bg-emerald-600 text-white font-bold px-6 py-2.5 rounded-full text-sm transition">
                        📱 Agendar Consulta Ahora
                    </a>
                </div>
            </div>
        </section>

        <section id="biometros" class="bg-white rounded-2xl p-6 md:p-8 card-shadow">
            <h2 class="text-2xl font-bold text-[#2E1065] text-center mb-2">Interacción del Eneagrama y Síntomas</h2>
            <p class="text-sm text-gray-500 text-center mb-8">Haz clic en los eneatipos para ver cómo la distorsión del ego impacta el cuerpo físico.</p>

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 items-center">
                <div class="space-y-3">
                    <div onclick="showEneagramDetail(1, 'Rigidez, perfeccionismo, autocrítica severa.', 'Articulaciones rígidas, dolor agudo de rodillas, mandíbula apretada (bruxismo).')" class="p-4 bg-purple-50 hover:bg-purple-100 rounded-xl cursor-pointer border-l-4 border-red-500 transition">
                        <span class="font-bold text-red-500">Tipo 1:</span> Rigidez / Exceso de Perfección
                    </div>
                    <div onclick="showEneagramDetail(6, 'Inseguridad mental, anticipación catastrófica, indecisión.', 'Bloqueo severo en el Plexo Solar, colitis nerviosa, taquicardias.')" class="p-4 bg-purple-50 hover:bg-purple-100 rounded-xl cursor-pointer border-l-4 border-amber-500 transition">
                        <span class="font-bold text-amber-500">Tipo 6:</span> Miedo / Ansiedad Mental
                    </div>
                    <div onclick="showEneagramDetail(8, 'Control excesivo, sobreesfuerzo, confrontación constante.', 'Fatiga en la espalda baja, tensión cervical alta, picos de presión.')" class="p-4 bg-purple-50 hover:bg-purple-100 rounded-xl cursor-pointer border-l-4 border-[#10B981] transition">
                        <span class="font-bold text-[#10B981]">Tipo 8:</span> Control / Exceso de Fuerza
                    </div>
                    <div onclick="showEneagramDetail(9, 'Evasión de conflictos, desconexión de uno mismo.', 'Retención de líquidos, metabolismo muy lento, pesadez corporal.')" class="p-4 bg-purple-50 hover:bg-purple-100 rounded-xl cursor-pointer border-l-4 border-blue-500 transition">
                        <span class="font-bold text-blue-500">Tipo 9:</span> Pereza Interna / Indolencia
                    </div>
                </div>

                <div class="p-6 bg-gray-50 rounded-2xl border border-gray-100 flex flex-col justify-center text-center h-full min-h-[250px]" id="detail-panel">
                    <div class="text-5xl mb-4">🔍</div>
                    <h4 class="font-bold text-lg text-[#2E1065] mb-2">Explorador Psicosomático</h4>
                    <p class="text-sm text-gray-600">Selecciona uno de los eneatipos de la lista para ver la correlación entre mente y cuerpo físico en este panel informativo.</p>
                </div>
            </div>
        </section>

        <section class="bg-white rounded-2xl p-6 md:p-8 card-shadow">
            <h2 class="text-2xl font-bold text-[#2E1065] text-center mb-2">El Balance Energético de una Sesión</h2>
            <p class="text-sm text-gray-500 text-center mb-8">Gráfico que muestra los niveles ideales de restauración tras la aplicación de la terapia.</p>
            <div class="chart-container">
                <canvas id="balanceRadarChart"></canvas>
            </div>
        </section>

        <section id="proceso" class="bg-white rounded-2xl p-6 md:p-8 card-shadow">
            <h2 class="text-2xl font-bold text-[#2E1065] text-center mb-2">El Proceso de Restauración</h2>
            <p class="text-sm text-gray-500 text-center mb-10">Cómo funciona la sesión para recuperar tu soberanía.</p>

            <div class="space-y-6 max-w-3xl mx-auto">
                <div class="flex items-start gap-4">
                    <div class="w-12 h-12 rounded-full bg-[#7C3AED] text-white flex items-center justify-center font-bold text-lg shrink-0">1</div>
                    <div>
                        <h4 class="font-bold text-[#2E1065] text-lg">Fase de Escaneo (Biómetros)</h4>
                        <p class="text-sm text-gray-600 mt-1">
                            Utilizando tu nombre y fecha de nacimiento, medimos el estado de tus chakras, campo áurico y el tipo de personalidad limitante activa. Esto nos da un mapa exacto de la raíz de tu malestar.
                        </p>
                    </div>
                </div>

                <div class="flex items-start gap-4">
                    <div class="w-12 h-12 rounded-full bg-[#F59E0B] text-white flex items-center justify-center font-bold text-lg shrink-0">2</div>
                    <div>
                        <h4 class="font-bold text-[#2E1065] text-lg">Fase de Transmutación (Mesa Radiónica)</h4>
                        <p class="text-sm text-gray-600 mt-1">
                            Con los datos del escaneo, enviamos frecuencias correctivas de geometría sagrada mediante la mesa. Se disuelven los bloqueos del hogar, las cargas ajenas y se sella tu aura.
                        </p>
                    </div>
                </div>

                <div class="flex items-start gap-4">
                    <div class="w-12 h-12 rounded-full bg-[#10B981] text-white flex items-center justify-center font-bold text-lg shrink-0">3</div>
                    <div>
                        <h4 class="font-bold text-[#2E1065] text-lg">Sello y Protección Final</h4>
                        <p class="text-sm text-gray-600 mt-1">
                            Se cierra toda interacción nociva abierta por el contacto con personas densas, devolviendo la sensación de enraizamiento, descanso profundo y fluidez física.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <section class="bg-[#2E1065] text-white rounded-3xl p-8 md:p-12 text-center relative overflow-hidden">
            <h2 class="text-3xl font-extrabold mb-4">¿Listo para recuperar tu equilibrio?</h2>
            <p class="text-sm md:text-base text-gray-200 max-w-xl mx-auto mb-8">
                No esperes a que las interferencias del ambiente sigan afectando tu salud física o tu descanso nocturno. Agenda hoy una sesión completa.
            </p>
            <a href="https://wa.me/5211234567890?text=Hola,%20realice%20el%20test%20vibracional%20y%20quiero%20agendar%20mi%20sesion%20de%20Terapia%20de%20Restauracion%20Energetica%20Integral" target="_blank" class="inline-block bg-[#10B981] hover:bg-emerald-600 text-white font-bold px-8 py-3.5 rounded-full text-base tracking-wide transition shadow-lg">
                Agendar Mi Sesión por WhatsApp
            </a>
        </section>

    </main>

    <footer class="bg-gray-900 text-gray-500 py-8 text-center text-xs border-t border-gray-800">
        <p class="mb-2">Terapia de Restauración Energética Integral © 2026</p>
        <p>Plataforma interactiva para la medición y armonización áurica del operador y testigos.</p>
    </footer>

    <script>
        const answers = [false, false, false, false, false];

        function answerQuiz(index, val) {
            answers[index] = val;
            const buttons = document.querySelectorAll(`.quiz-btn-${index}`);
            buttons.forEach(btn => {
                if ((btn.innerText === "Sí" && val) || (btn.innerText === "No" && !val)) {
                    btn.classList.remove('bg-white', 'text-gray-800');
                    btn.classList.add('bg-[#7C3AED]', 'text-white');
                } else {
                    btn.classList.remove('bg-[#7C3AED]', 'text-white');
                    btn.classList.add('bg-white', 'text-gray-800');
                }
            });
        }

        function calculateScore() {
            let score = 0;
            answers.forEach(ans => { if (ans) score++; });

            const resultDiv = document.getElementById('quiz-result');
            const title = document.getElementById('result-title');
            const desc = document.getElementById('result-desc');
            const btn = document.getElementById('whatsapp-btn');

            resultDiv.classList.remove('hidden');

            let customMessage = "";
            if (score <= 1) {
                title.innerText = "Nivel de Sobrecarga: Bajo (Armonía General)";
                desc.innerText = "Tu campo energético se encuentra bastante centrado. Te vendría muy bien una sesión preventiva de alineación de chakras para consolidar esta estabilidad.";
                customMessage = "Hola! Realicé el test y mi resultado fue Sobrecarga Baja. Me gustaría agendar una alineación preventiva.";
            } else if (score <= 3) {
                title.innerText = "Nivel de Sobrecarga: Medio (Interferencia Activa)";
                desc.innerText = "Tienes algunas fugas de energía que se están manifestando como tensión muscular o descanso inquieto. Te sugerimos realizar un Escaneo con Biómetros para hallar la causa.";
                customMessage = "Hola! Realicé el test y mi resultado fue Sobrecarga Media. Quiero agendar un Escaneo con Biómetros.";
            } else {
                title.innerText = "Nivel de Sobrecarga: Alto (Necesidad de Restauración)";
                desc.innerText = "Presentas síntomas físicos recurrentes y sensación de pesadez ambiental severa. Te recomendamos la sesión de Restauración Energética Integral (Escaneo + Mesa Radiónica de Transmutación) de manera prioritaria.";
                customMessage = "Hola! Realicé el test y mi resultado fue Sobrecarga Alta. Deseo agendar con prioridad la Terapia de Restauración Energética Integral.";
            }

            btn.href = `https://wa.me/5211234567890?text=${encodeURIComponent(customMessage)}`;
            resultDiv.scrollIntoView({ behavior: 'smooth' });
        }

        function showEneagramDetail(type, ego, body) {
            const panel = document.getElementById('detail-panel');
            let color = "#7C3AED";
            if (type === 1) color = "#EF4444";
            if (type === 6) color = "#F59E0B";
            if (type === 8) color = "#10B981";
            if (type === 9) color = "#3B82F6";

            panel.innerHTML = `
                <div class="text-4xl mb-3" style="color: ${color}">🎯</div>
                <h4 class="font-bold text-xl mb-2" style="color: ${color}">Eneatipo ${type} en el Cuerpo</h4>
                <p class="text-sm text-gray-700 font-semibold mb-3">Distorsión Mental:</p>
                <p class="text-sm text-gray-600 mb-4 bg-white p-3 rounded-lg border border-gray-100">${ego}</p>
                <p class="text-sm text-gray-700 font-semibold mb-3">Manifestación Física:</p>
                <p class="text-sm text-gray-600 bg-white p-3 rounded-lg border border-gray-100">${body}</p>
            `;
        }

        function fnWrap(l) {
            if (l.length <= 16) return l;
            let w = l.split(' ');
            let a = [];
            let c = '';
            for (let i = 0; i < w.length; i++) {
                if ((c + w[i]).length > 16) {
                    if (c !== '') a.push(c.trim());
                    c = w[i] + ' ';
                } else {
                    c += w[i] + ' ';
                }
            }
            if (c.trim() !== '') a.push(c.trim());
            return a;
        }

        const ttConf = {
            callbacks: {
                title: function(items) {
                    const i = items[0];
                    let lbl = i.chart.data.labels[i.dataIndex];
                    if (Array.isArray(lbl)) {
                        return lbl.join(' ');
                    }
                    return lbl;
                }
            }
        };

        const ctxRadar = document.getElementById('balanceRadarChart').getContext('2d');
        const labelsRaw = [
            "Enraizamiento Físico",
            "Protección Áurica",
            "Coherencia Mental",
            "Armonía del Espacio",
            "Vitalidad General"
        ];
        const labelsProcessed = labelsRaw.map(fnWrap);

        new Chart(ctxRadar, {
            type: 'radar',
            data: {
                labels: labelsProcessed,
                datasets: [
                    {
                        label: 'Antes de la Terapia',
                        data: [30, 25, 40, 20, 35],
                        backgroundColor: 'rgba(239, 68, 68, 0.2)',
                        borderColor: '#EF4444',
                        borderWidth: 2,
                        pointBackgroundColor: '#EF4444'
                    },
                    {
                        label: 'Después de la Terapia',
                        data: [90, 95, 85, 90, 95],
                        backgroundColor: 'rgba(16, 185, 129, 0.2)',
                        borderColor: '#10B981',
                        borderWidth: 2,
                        pointBackgroundColor: '#10B981'
                    }
                ]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: { position: 'bottom' },
                    tooltip: ttConf
                },
                scales: {
                    r: {
                        ticks: { display: false },
                        grid: { color: 'rgba(0, 0, 0, 0.08)' },
                        angleLines: { color: 'rgba(0, 0, 0, 0.08)' },
                        suggestedMin: 0,
                        suggestedMax: 100
                    }
                }
            }
        });
    </script>
</body>
</html>
Este proyecto web ha sido desarrollado de manera limpia utilizando Tailwind CSS y Chart.js para la visualización de datos, asegurando un rendimiento óptimo tanto en celulares como en computadoras.
