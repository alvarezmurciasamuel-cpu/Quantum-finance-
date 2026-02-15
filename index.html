<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quantum Finance Pro | IB Elite Project</title>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;600;800&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #00ffa3; --secondary: #00d4ff; --accent: #7000ff;
            --dark-bg: #030712; --card-bg: #111827; --text-main: #f9fafb;
            --text-dim: #9ca3af; --error: #ef4444;
        }

        * { box-sizing: border-box; transition: all 0.2s ease; }

        body { 
            font-family: 'Plus Jakarta Sans', sans-serif; margin: 0; 
            background: var(--dark-bg); color: var(--text-main); line-height: 1.6;
            background-image: 
                radial-gradient(at 0% 0%, rgba(112, 0, 255, 0.15) 0px, transparent 50%),
                radial-gradient(at 100% 100%, rgba(0, 255, 163, 0.1) 0px, transparent 50%);
        }

        /* Navegación */
        nav { 
            background: rgba(3, 7, 18, 0.8); backdrop-filter: blur(12px);
            padding: 1rem 5%; position: sticky; top: 0; z-index: 1000;
            display: flex; justify-content: space-between; align-items: center;
            border-bottom: 1px solid rgba(255,255,255,0.1);
        }
        .logo { font-size: 1.5rem; font-weight: 800; background: linear-gradient(to right, var(--primary), var(--secondary)); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .nav-links { display: flex; gap: 1rem; }
        .nav-btn { 
            background: transparent; border: 1px solid transparent; color: var(--text-dim); 
            padding: 0.6rem 1.2rem; border-radius: 10px; cursor: pointer; font-weight: 600;
        }
        .nav-btn:hover { color: white; background: rgba(255,255,255,0.05); }
        .nav-btn.active { color: var(--primary); border-color: rgba(0, 255, 163, 0.3); background: rgba(0, 255, 163, 0.05); }

        .container { max-width: 1200px; margin: 2rem auto; padding: 0 1.5rem; }
        .view { display: none; animation: fadeIn 0.4s ease-out; }
        .view.active { display: block; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; transform: translateY(0); } }

        /* Hero */
        .hero { text-align: center; padding: 4rem 1rem; }
        .hero h1 { font-size: clamp(2.5rem, 5vw, 4.5rem); margin: 0; font-weight: 800; letter-spacing: -2px; }
        .hero p { color: var(--text-dim); font-size: 1.25rem; max-width: 700px; margin: 1.5rem auto; }

        /* Cards */
        .card { background: var(--card-bg); border: 1px solid rgba(255,255,255,0.05); border-radius: 24px; padding: 2rem; margin-bottom: 2rem; }
        
        /* Grid Academia */
        .academy-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 1.5rem; }
        .lesson-card { background: #1f2937; padding: 2rem; border-radius: 20px; border-top: 4px solid var(--accent); }
        .lesson-card img { width: 100%; height: 200px; object-fit: cover; border-radius: 12px; margin-bottom: 1.5rem; }

        /* Calculadora */
        .calc-grid { display: grid; grid-template-columns: 380px 1fr; gap: 2rem; }
        .input-sidebar { background: #1f2937; padding: 2rem; border-radius: 20px; display: flex; flex-direction: column; gap: 1.2rem; }
        .input-field { display: flex; flex-direction: column; gap: 0.5rem; }
        label { font-size: 0.85rem; font-weight: 700; color: var(--text-dim); text-transform: uppercase; }
        input, select { 
            background: #030712; border: 1px solid #374151; padding: 1rem; border-radius: 12px; 
            color: white; font-size: 1rem; outline: none;
        }
        input:focus { border-color: var(--primary); }
        .main-btn { 
            background: var(--primary); color: #000; border: none; padding: 1.2rem; border-radius: 12px; 
            font-weight: 800; font-size: 1rem; cursor: pointer; margin-top: 1rem;
        }
        .main-btn:hover { transform: translateY(-2px); box-shadow: 0 10px 20px rgba(0, 255, 163, 0.2); }

        /* Quiz */
        .quiz-header { display: flex; justify-content: space-between; align-items: center; margin-bottom: 2rem; }
        .progress-bar { width: 100%; height: 8px; background: #374151; border-radius: 10px; margin-bottom: 2rem; overflow: hidden; }
        .progress-fill { height: 100%; background: var(--primary); width: 0%; }
        .option-btn { 
            width: 100%; text-align: left; padding: 1.2rem; margin-bottom: 1rem; border-radius: 15px;
            background: #1f2937; border: 1px solid #374151; color: white; cursor: pointer; font-size: 1rem;
        }
        .option-btn:hover { border-color: var(--secondary); background: #374151; }

        @media (max-width: 900px) { .calc-grid { grid-template-columns: 1fr; } }
    </style>
</head>
<body>

<nav>
    <div class="logo">QUANTUM <span style="font-weight:300; color:white">FINANCE</span></div>
    <div class="nav-links">
        <button class="nav-btn active" onclick="showView('inicio', this)">Inicio</button>
        <button class="nav-btn" onclick="showView('academia', this)">Academia</button>
        <button class="nav-btn" onclick="showView('simulador', this)">Simulador</button>
        <button class="nav-btn" onclick="showView('quiz-section', this)">Desafío</button>
    </div>
</nav>

<div class="container">

    <div id="inicio" class="view active">
        <div class="hero">
            <h1>Domina tu Destino <br><span style="color:var(--primary)">Financiero.</span></h1>
            <p>La diferencia entre la riqueza y la deuda es entender las matemáticas antes de que ellas te entiendan a ti.</p>
        </div>
        <div class="academy-grid">
            <div class="lesson-card">
                <img src="https://images.unsplash.com/photo-1579621970563-ebec7560ff3e?auto=format&fit=crop&q=80&w=800">
                <h3>El Interés Compuesto</h3>
                <p>Descubre por qué empezar 5 años antes puede duplicar tu riqueza final. El tiempo es más importante que el capital.</p>
            </div>
            <div class="lesson-card" style="border-top-color: var(--secondary);">
                <img src="https://images.unsplash.com/photo-1611974717525-58a45722d640?auto=format&fit=crop&q=80&w=800">
                <h3>Gestión de Riesgos</h3>
                <p>Aprende a protegerte de la inflación y a diversificar como un profesional del Wall Street.</p>
            </div>
        </div>
    </div>

    <div id="academia" class="view">
        <h2 style="font-size: 2.5rem; text-align:center; margin-bottom: 3rem;">Biblioteca de Inteligencia</h2>
        <div class="academy-grid">
            <div class="lesson-card">
                <h3>1. Inflación: El Impuesto Silencioso</h3>
                <p>Si la inflación es del 5%, un billete de $100 valdrá $95 el próximo año en términos de lo que puedes comprar. Tu meta es siempre rendir por encima de esta cifra.</p>
            </div>
            <div class="lesson-card">
                <h3>2. Activos vs Pasivos</h3>
                <p>Un activo pone dinero en tu bolsillo (acciones, renta). Un pasivo saca dinero de tu bolsillo (deudas, lujos innecesarios). La clave es coleccionar activos.</p>
            </div>
            <div class="lesson-card">
                <h3>3. Fondos Indexados</h3>
                <p>En lugar de intentar adivinar qué empresa ganará, compras un pedazo de las 500 empresas más grandes del mundo (como el S&P 500).</p>
            </div>
        </div>
    </div>

    <div id="simulador" class="view">
        <div class="calc-grid">
            <div class="input-sidebar">
                <div class="input-field">
                    <label>Moneda de Análisis</label>
                    <select id="currency">
                        <option value="$">Dólar (USD)</option>
                        <option value="€">Euro (EUR)</option>
                        <option value="MXN$">Peso Mexicano</option>
                        <option value="COP$">Peso Colombiano</option>
                    </select>
                </div>
                <div class="input-field">
                    <label>Inversión Inicial</label>
                    <input type="number" id="init-p" value="5000">
                </div>
                <div class="input-field">
                    <label>Aporte Mensual</label>
                    <input type="number" id="monthly-a" value="500">
                </div>
                <div class="input-field">
                    <label>Rendimiento Anual (%)</label>
                    <input type="number" id="rate" value="10">
                </div>
                <div class="input-field">
                    <label>Inflación Esperada (%)</label>
                    <input type="number" id="infl" value="4">
                </div>
                <div class="input-field">
                    <label>Tiempo (Años)</label>
                    <input type="number" id="years" value="20">
                </div>
                <button class="main-btn" onclick="quantumCalc()">Generar Proyección</button>
            </div>
            <div class="card">
                <canvas id="mainChart" style="max-height: 400px;"></canvas>
                <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; margin-top: 2rem;">
                    <div style="background: rgba(0,255,163,0.1); padding: 1.5rem; border-radius: 15px; text-align:center;">
                        <small style="color:var(--primary)">Capital Final Bruto</small>
                        <div id="final-bruto" style="font-size: 1.8rem; font-weight: 800;">$0</div>
                    </div>
                    <div style="background: rgba(0,212,255,0.1); padding: 1.5rem; border-radius: 15px; text-align:center;">
                        <small style="color:var(--secondary)">Valor Real (Ajustado)</small>
                        <div id="final-real" style="font-size: 1.8rem; font-weight: 800;">$0</div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div id="quiz-section" class="view">
        <div class="card" style="max-width: 800px; margin: 0 auto;">
            <div class="quiz-header">
                <h3 id="category-name" style="color:var(--secondary)">Categoría: Inversiones</h3>
                <span id="q-counter">Pregunta 1/10</span>
            </div>
            <div class="progress-bar"><div class="progress-fill" id="p-bar"></div></div>
            <div id="quiz-container">
                <h2 id="question-text" style="margin-bottom: 2rem;">Cargando desafío...</h2>
                <div id="options-grid"></div>
            </div>
            <div id="quiz-results" style="display:none; text-align:center;">
                <h1 id="score-text" style="font-size: 4rem; color: var(--primary);">0/10</h1>
                <p id="feedback-text" style="font-size: 1.2rem; margin-bottom: 2rem;"></p>
                <button class="main-btn" onclick="restartQuiz()">Reintentar Desafío</button>
            </div>
        </div>
    </div>

</div>

<script>
    // Navegación
    function showView(id, btn) {
        document.querySelectorAll('.view').forEach(v => v.classList.remove('active'));
        document.querySelectorAll('.nav-btn').forEach(b => b.classList.remove('active'));
        document.getElementById(id).classList.add('active');
        if(btn) btn.classList.add('active');
    }

    // Calculadora Quantum
    let myChart;
    function quantumCalc() {
        const curr = document.getElementById('currency').value;
        const p = parseFloat(document.getElementById('init-p').value) || 0;
        const m = parseFloat(document.getElementById('monthly-a').value) || 0;
        const r = (parseFloat(document.getElementById('rate').value)/100)/12;
        const inf = (parseFloat(document.getElementById('infl').value)/100)/12;
        const t = parseInt(document.getElementById('years').value) || 0;

        let labels = [], dataBruto = [], dataReal = [], dataAhorro = [];
        let saldoBruto = p, saldoReal = p, totalAhorro = p;

        for(let i=0; i<=t; i++) {
            labels.push("Año " + i);
            dataBruto.push(Math.round(saldoBruto));
            dataReal.push(Math.round(saldoReal));
            dataAhorro.push(Math.round(totalAhorro));

            for(let j=0; j<12; j++) {
                saldoBruto = (saldoBruto * (1 + r)) + m;
                saldoReal = (saldoReal * (1 + (r - inf))) + m;
                totalAhorro += m;
            }
        }

        document.getElementById('final-bruto').innerText = curr + Math.round(saldoBruto).toLocaleString();
        document.getElementById('final-real').innerText = curr + Math.round(saldoReal).toLocaleString();

        const ctx = document.getElementById('mainChart').getContext('2d');
        if(myChart) myChart.destroy();
        myChart = new Chart(ctx, {
            type: 'line',
            data: {
                labels: labels,
                datasets: [
                    { label: 'Crecimiento Bruto', data: dataBruto, borderColor: '#00ffa3', backgroundColor: 'rgba(0,255,163,0.1)', fill: true, tension: 0.4 },
                    { label: 'Ajustado Inflación', data: dataReal, borderColor: '#00d4ff', borderDash: [5,5], tension: 0.4 },
                    { label: 'Solo Ahorro', data: dataAhorro, borderColor: '#4b5563', tension: 0 }
                ]
            },
            options: {
                responsive: true,
                plugins: { legend: { labels: { color: '#fff' } } },
                scales: {
                    y: { grid: { color: 'rgba(255,255,255,0.05)' }, ticks: { color: '#9ca3af' } },
                    x: { ticks: { color: '#9ca3af' } }
                }
            }
        });
    }

    // Quiz Dinámico
    const quizData = [
        { c: "Inversión", q: "¿Qué es el S&P 500?", o: ["Una criptomoneda", "Las 500 empresas más grandes de EE.UU.", "Un banco europeo"], a: 1 },
        { c: "Macroeconomía", q: "Si la inflación es mayor al rendimiento de tu banco...", o: ["Ganas dinero", "Mantienes tu valor", "Pierdes poder de compra"], a: 2 },
        { c: "Ahorro", q: "¿Qué es un fondo de emergencia?", o: ["Dinero para vacaciones", "Ahorro de 3-6 meses de gastos", "Dinero para apostar"], a: 1 },
        { c: "Inversión", q: "La diversificación ayuda a...", o: ["Ganar siempre", "Reducir el riesgo", "Evitar pagar impuestos"], a: 1 },
        { c: "Estrategia", q: "¿Qué es el Interés Compuesto?", o: ["Interés sobre el capital inicial + intereses", "Un interés simple anual", "Una penalización bancaria"], a: 0 },
        { c: "Inversión", q: "¿Cuál es el activo más líquido?", o: ["Bienes Raíces", "Efectivo", "Oro"], a: 1 },
        { c: "Macroeconomía", q: "¿Qué pasa con los precios cuando hay alta inflación?", o: ["Bajan", "Se mantienen", "Suben"], a: 2 },
        { c: "Estrategia", q: "¿Qué es un Activo?", o: ["Algo que quita dinero", "Algo que genera ingresos", "Una deuda"], a: 1 },
        { c: "Inversión", q: "¿Qué significa 'Bear Market'?", o: ["Mercado al alza", "Mercado estable", "Mercado a la baja"], a: 2 },
        { c: "Estrategia", q: "Factor más importante para el interés compuesto:", o: ["Monto inicial", "El Tiempo", "El Banco"], a: 1 }
    ];

    let currentQ = 0; let score = 0;

    function loadQuestion() {
        const q = quizData[currentQ];
        document.getElementById('p-bar').style.width = ((currentQ + 1) / quizData.length * 100) + "%";
        document.getElementById('category-name').innerText = "Categoría: " + q.c;
        document.getElementById('q-counter').innerText = `Pregunta ${currentQ + 1}/${quizData.length}`;
        document.getElementById('question-text').innerText = q.q;
        
        const grid = document.getElementById('options-grid');
        grid.innerHTML = "";
        q.o.forEach((opt, i) => {
            const btn = document.createElement('button');
            btn.className = "option-btn";
            btn.innerText = opt;
            btn.onclick = () => checkAnswer(i);
            grid.appendChild(btn);
        });
    }

    function checkAnswer(idx) {
        if(idx === quizData[currentQ].a) score++;
        currentQ++;
        if(currentQ < quizData.length) loadQuestion();
        else showQuizResults();
    }

    function showQuizResults() {
        document.getElementById('quiz-container').style.display = "none";
        const res = document.getElementById('quiz-results');
        res.style.display = "block";
        document.getElementById('score-text').innerText = `${score}/${quizData.length}`;
        document.getElementById('feedback-text').innerText = score > 7 ? "¡Excelente! Tienes mentalidad de inversor profesional." : "Buen intento. Te recomiendo revisar la sección de Academia.";
    }

    function restartQuiz() {
        currentQ = 0; score = 0;
        document.getElementById('quiz-container').style.display = "block";
        document.getElementById('quiz-results').style.display = "none";
        loadQuestion();
    }

    window.onload = () => { quantumCalc(); loadQuestion(); };
</script>

</body>
</html>
