
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tablas y Repartos Mágicos</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;600;700&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        fredoka: ['Fredoka', 'sans-serif'],
                    },
                    colors: {
                        sunYellow: '#FFD166',
                        leafGreen: '#06D6A0',
                        skyBlue: '#118AB2',
                        coralOrange: '#EF476F',
                        darkNavy: '#073B4C',
                        purpleMagic: '#8338EC'
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'Fredoka', sans-serif;
            background: linear-gradient(135deg, #8338EC 0%, #3A86FF 50%, #06D6A0 100%);
            min-height: 100vh;
        }
        @keyframes float {
            0% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-6px) rotate(1deg); }
            100% { transform: translateY(0px) rotate(0deg); }
        }
        .floating-avatar {
            animation: float 3s ease-in-out infinite;
        }
        @keyframes bounceIn {
            0% { transform: scale(0.9); opacity: 0; }
            100% { transform: scale(1); opacity: 1; }
        }
        .bounce-in {
            animation: bounceIn 0.3s ease-out;
        }
    </style>
</head>
<body class="flex flex-col items-center justify-between p-4 md:p-6 min-h-screen">

    <header class="w-full max-w-2xl bg-white/95 backdrop-blur rounded-3xl shadow-xl p-4 mb-4 flex flex-wrap items-center justify-between border-4 border-sunYellow">
        <div class="flex items-center space-x-3">
            <button onclick="goBack()" class="bg-gray-100 hover:bg-gray-200 text-darkNavy p-2.5 rounded-2xl shadow transition-all flex items-center justify-center font-bold text-lg" title="Atrás">
                ⬅️
            </button>
            <div>
                <h1 class="text-lg md:text-2xl font-bold text-darkNavy">Tablas y Repartos Mágicos</h1>
                <p class="text-xs md:text-sm text-purpleMagic font-semibold">Multiplicaciones y Divisiones</p>
            </div>
        </div>
        <div class="flex items-center space-x-2 sm:space-x-4 mt-2 sm:mt-0">
            <div class="bg-sunYellow px-3 py-1.5 rounded-2xl shadow-inner text-darkNavy font-bold text-xs sm:text-sm flex items-center space-x-1">
                <span>⭐ Reto:</span>
                <span id="current-question-num">1</span>/<span>20</span>
            </div>
            <div class="bg-leafGreen text-white px-3 py-1.5 rounded-2xl shadow-inner font-bold text-xs sm:text-sm flex items-center space-x-1">
                <span>🏆 Puntos:</span>
                <span id="score-display">0</span>
            </div>
        </div>
    </header>

    <main class="w-full max-w-2xl flex flex-col items-center relative flex-grow justify-center mb-6">
        
        <!-- Robot Avatar Banner (Non-intrusive top position above game card) -->
        <div id="avatar-container" class="w-full bg-white/90 backdrop-blur border-2 border-coralOrange rounded-2xl p-3 shadow-lg mb-4 flex items-center space-x-3 floating-avatar">
            <div class="text-3xl md:text-4xl bg-coralOrange/20 rounded-2xl p-2 shrink-0">🤖</div>
            <div id="avatar-speech" class="text-xs md:text-sm font-semibold text-darkNavy leading-relaxed">
                ¡Hola explorador! Soy tu copiloto robot. ¿Listo para dominar las tablas?
            </div>
        </div>

        <div id="game-card" class="w-full bg-white/95 backdrop-blur-md rounded-3xl shadow-2xl p-6 md:p-10 border-4 border-skyBlue flex flex-col items-center relative z-10 bounce-in">
            
            <!-- Progress Bar -->
            <div class="w-full bg-gray-200 rounded-full h-4 mb-6 overflow-hidden border-2 border-gray-300">
                <div id="progress-bar" class="bg-leafGreen h-full transition-all duration-500 rounded-full" style="width: 5%"></div>
            </div>

            <!-- Question & Visual Assets -->
            <div id="question-area" class="w-full flex flex-col items-center">
                <div id="visual-assets" class="flex flex-wrap justify-center gap-2 mb-4 max-h-28 overflow-y-auto p-2">
                    <!-- Dynamic visual aids rendered via JS -->
                </div>
                
                <div id="equation-box" class="text-3xl md:text-5xl font-extrabold text-darkNavy mb-6 tracking-wider bg-sunYellow/30 px-6 py-3 rounded-3xl border-2 border-sunYellow">
                    <!-- 4 × 5 = ? -->
                </div>

                <!-- Answer Options Grid -->
                <div id="options-container" class="grid grid-cols-2 gap-4 w-full max-w-md">
                    <!-- Dynamic buttons -->
                </div>
            </div>

            <!-- Feedback Message Box -->
            <div id="feedback-box" class="hidden mt-4 text-center text-base md:text-lg font-bold py-3 px-4 rounded-2xl w-full animate-pulse">
            </div>

            <!-- In-game Action Buttons -->
            <div class="flex flex-wrap justify-center gap-3 mt-6 w-full pt-4 border-t border-gray-200">
                <button onclick="restartGame()" class="bg-amber-500 hover:bg-amber-600 text-white font-bold text-sm py-2.5 px-5 rounded-2xl shadow transition-all flex items-center space-x-1">
                    <span>🔄</span>
                    <span>Reiniciar Juego</span>
                </button>
                <button onclick="openShareModal()" class="bg-skyBlue hover:bg-skyBlue/90 text-white font-bold text-sm py-2.5 px-5 rounded-2xl shadow transition-all flex items-center space-x-1">
                    <span>📤</span>
                    <span>Compartir Juego</span>
                </button>
            </div>

        </div>

        <div id="end-screen" class="hidden w-full bg-white/95 backdrop-blur-md rounded-3xl shadow-2xl p-8 border-4 border-leafGreen flex flex-col items-center text-center z-10 bounce-in">
            <div class="text-6xl mb-4">🌟</div>
            <h2 id="end-title" class="text-3xl font-bold text-darkNavy mb-2">¡Misión Completada!</h2>
            <p id="end-message" class="text-lg text-gray-700 mb-6 max-w-md">
                <!-- Final encouragement message -->
            </p>
            <div class="bg-purpleMagic text-white text-2xl font-bold py-3 px-8 rounded-3xl shadow-lg mb-6">
                Puntaje Final: <span id="final-score">0</span> / 100
            </div>
            <div class="flex flex-wrap justify-center gap-4">
                <button onclick="restartGame()" class="bg-coralOrange hover:bg-coralOrange/90 text-white font-bold text-lg py-3 px-8 rounded-full shadow-lg transform hover:scale-105 transition-all flex items-center space-x-2 border-4 border-white">
                    <span>🔄</span>
                    <span>¡Jugar de Nuevo!</span>
                </button>
                <button onclick="openShareModal()" class="bg-skyBlue hover:bg-skyBlue/90 text-white font-bold text-lg py-3 px-8 rounded-full shadow-lg transform hover:scale-105 transition-all flex items-center space-x-2 border-4 border-white">
                    <span>📤</span>
                    <span>Compartir</span>
                </button>
            </div>
        </div>

    </main>

    <div id="share-modal" class="hidden fixed inset-0 bg-black/50 backdrop-blur-sm z-50 flex items-center justify-center p-4">
        <div class="bg-white rounded-3xl max-w-md w-full p-6 shadow-2xl border-4 border-purpleMagic text-center bounce-in">
            <div class="text-4xl mb-2">🎁</div>
            <h3 class="text-2xl font-bold text-darkNavy mb-2">¡Comparte la Aventura!</h3>
            <p class="text-sm text-gray-600 mb-4">Invita a tus amigos a practicar multiplicaciones y divisiones.</p>
            
            <div class="bg-gray-100 p-3 rounded-2xl flex items-center justify-between mb-4 border border-gray-200">
                <input type="text" id="share-link-input" readonly class="bg-transparent text-xs text-gray-700 w-full outline-none px-2" value="">
                <button onclick="copyShareLink()" class="bg-purpleMagic text-white text-xs font-bold px-3 py-2 rounded-xl hover:bg-purpleMagic/90 transition">Copiar</button>
            </div>

            <div class="flex flex-col items-center justify-center mb-6">
                <div class="bg-white p-2 rounded-2xl border-2 border-dashed border-gray-300 shadow-inner">
                    <img id="qr-code-img" src="" alt="Código QR del Juego" class="w-36 h-36 object-contain">
                </div>
                <span class="text-xs text-gray-500 mt-2">Escanea el código QR con tu celular</span>
            </div>

            <button onclick="closeShareModal()" class="w-full bg-coralOrange hover:bg-coralOrange/90 text-white font-bold py-3 rounded-2xl shadow transition">
                Cerrar
            </button>
        </div>
    </div>

    <script>
        const audioCtx = new (window.AudioContext || window.webkitAudioContext)();

        function playSound(type) {
            if (audioCtx.state === 'suspended') {
                audioCtx.resume();
            }
            const osc = audioCtx.createOscillator();
            const gainNode = audioCtx.createGain();
            osc.connect(gainNode);
            gainNode.connect(audioCtx.destination);
            const now = audioCtx.currentTime;

            if (type === 'correct') {
                osc.type = 'triangle';
                osc.frequency.setValueAtTime(350, now);
                osc.frequency.exponentialRampToValueAtTime(700, now + 0.15);
                osc.frequency.exponentialRampToValueAtTime(1050, now + 0.3);
                gainNode.gain.setValueAtTime(0.3, now);
                gainNode.gain.exponentialRampToValueAtTime(0.01, now + 0.4);
                osc.start(now);
                osc.stop(now + 0.4);
            } else if (type === 'incorrect') {
                osc.type = 'sawtooth';
                osc.frequency.setValueAtTime(160, now);
                osc.frequency.linearRampToValueAtTime(90, now + 0.3);
                gainNode.gain.setValueAtTime(0.2, now);
                gainNode.gain.exponentialRampToValueAtTime(0.01, now + 0.3);
                osc.start(now);
                osc.stop(now + 0.3);
            } else if (type === 'click') {
                osc.type = 'sine';
                osc.frequency.setValueAtTime(450, now);
                gainNode.gain.setValueAtTime(0.1, now);
                gainNode.gain.exponentialRampToValueAtTime(0.01, now + 0.05);
                osc.start(now);
                osc.stop(now + 0.05);
            }
        }

        let questions = [];
        let currentQuestionIndex = 0;
        let score = 0;
        let correctAnswersCount = 0;
        const totalQuestions = 20;

        const assetPools = {
            star: ['⭐', '🌟', '✨', '🌠'],
            sweet: ['🍬', '🍭', '🍫', '🍪'],
            gem: ['💎', '🔮', '🎈', '🎁']
        };

        function getRandomElement(arr) {
            return arr[Math.floor(Math.random() * arr.length)];
        }

        function getRandomNumber(min, max) {
            return Math.floor(Math.random() * (max - min + 1)) + min;
        }

        // Generate 20 randomized multiplication and division questions
        function generateQuestions() {
            let generated = [];
            for (let i = 0; i < totalQuestions; i++) {
                const isMultiplication = Math.random() > 0.45; 
                let num1, num2, answer, symbol;

                if (isMultiplication) {
                    num1 = getRandomNumber(2, 10);
                    num2 = getRandomNumber(2, 10);
                    answer = num1 * num2;
                    symbol = '×';
                } else {
                    num2 = getRandomNumber(2, 10); 
                    let quotient = getRandomNumber(2, 10);
                    num1 = num2 * quotient; 
                    answer = quotient;
                    symbol = '÷';
                }

                const themeKeys = Object.keys(assetPools);
                const chosenThemeKey = getRandomElement(themeKeys);
                const chosenEmoji = getRandomElement(assetPools[chosenThemeKey]);

                generated.push({
                    num1,
                    num2,
                    answer,
                    symbol,
                    emoji: chosenEmoji
                });
            }
            return generated;
        }

        function initGame() {
            questions = generateQuestions();
            currentQuestionIndex = 0;
            score = 0;
            correctAnswersCount = 0;
            document.getElementById('end-screen').classList.add('hidden');
            document.getElementById('game-card').classList.remove('hidden');
            loadQuestion();
        }

        function loadQuestion() {
            if (currentQuestionIndex >= totalQuestions) {
                endGame();
                return;
            }

            const q = questions[currentQuestionIndex];
            document.getElementById('current-question-num').innerText = currentQuestionIndex + 1;
            document.getElementById('score-display').innerText = score;
            
            const progressPercent = ((currentQuestionIndex) / totalQuestions) * 100;
            document.getElementById('progress-bar').style.width = `${progressPercent}%`;

            document.getElementById('equation-box').innerText = `${q.num1} ${q.symbol} ${q.num2} = ?`;

            // Render visual aids
            const visualContainer = document.getElementById('visual-assets');
            visualContainer.innerHTML = '';
            
            let visualHTML = `<div class="flex flex-wrap gap-1 items-center justify-center bg-purpleMagic/10 p-2.5 rounded-2xl border border-purpleMagic/30">`;
            const displayCount = Math.min(q.num1, 24);
            for (let i = 0; i < displayCount; i++) {
                visualHTML += `<span class="text-xl">${q.emoji}</span>`;
            }
            if (q.num1 > 24) visualHTML += `<span class="text-xs font-bold text-gray-500">(+${q.num1 - 24})</span>`;
            visualHTML += `</div>`;
            visualContainer.innerHTML = visualHTML;

            // Generate options
            let options = [q.answer];
            while (options.length < 4) {
                let offset = getRandomNumber(-4, 4);
                let wrongAnswer = q.answer + offset;
                if (wrongAnswer >= 0 && !options.includes(wrongAnswer)) {
                    options.push(wrongAnswer);
                }
            }
            options.sort(() => Math.random() - 0.5);

            const optionsContainer = document.getElementById('options-container');
            optionsContainer.innerHTML = '';
            options.forEach(opt => {
                const btn = document.createElement('button');
                btn.className = "bg-purpleMagic hover:bg-purpleMagic/90 text-white font-bold text-xl py-3 px-5 rounded-2xl shadow-lg transform hover:scale-105 transition-all border-b-4 border-indigo-900 active:translate-y-1";
                btn.innerText = opt;
                btn.onclick = () => checkAnswer(opt, q.answer, btn);
                optionsContainer.appendChild(btn);
            });

            const avatarSpeech = document.getElementById('avatar-speech');
            const phrases = [
                "¡Calculando con circuitos de sabiduría!",
                "¿Cuántas veces cabe este grupo, amigo?",
                "¡Procesando multiplicación óptima!",
                "¡Tú puedes resolverlo campeón!"
            ];
            avatarSpeech.innerText = getRandomElement(phrases);

            document.getElementById('feedback-box').classList.add('hidden');
        }

        function checkAnswer(selected, correct, buttonElement) {
            const buttons = document.querySelectorAll('#options-container button');
            buttons.forEach(b => b.disabled = true);

            const feedbackBox = document.getElementById('feedback-box');
            feedbackBox.classList.remove('hidden');

            const avatarSpeech = document.getElementById('avatar-speech');

            if (selected === correct) {
                playSound('correct');
                buttonElement.classList.remove('bg-purpleMagic', 'border-indigo-900');
                buttonElement.classList.add('bg-leafGreen', 'border-green-800');
                
                score += 5; // 20 * 5 = 100 points max
                correctAnswersCount++;
                document.getElementById('score-display').innerText = score;

                feedbackBox.className = "mt-4 text-center text-base md:text-lg font-bold py-2.5 px-4 rounded-2xl w-full bg-leafGreen/20 text-leafGreen border-2 border-leafGreen";
                feedbackBox.innerText = "🌟 ¡Excelente! ¡Respuesta correcta! 🌟";
                avatarSpeech.innerText = "¡Increíble! ¡Sistema operativo aprobado!";
            } else {
                playSound('incorrect');
                buttonElement.classList.remove('bg-purpleMagic', 'border-indigo-900');
                buttonElement.classList.add('bg-coralOrange', 'border-red-800');

                buttons.forEach(b => {
                    if (parseInt(b.innerText) === correct) {
                        b.classList.remove('bg-purpleMagic');
                        b.classList.add('bg-leafGreen');
                    }
                });

                feedbackBox.className = "mt-4 text-center text-base md:text-lg font-bold py-2.5 px-4 rounded-2xl w-full bg-coralOrange/20 text-coralOrange border-2 border-coralOrange";
                feedbackBox.innerText = `❌ Oh no, la respuesta correcta era ${correct}. ¡Sigue intentando!`;
                avatarSpeech.innerText = "¡Recalibrando! La práctica hace al maestro.";
            }

            setTimeout(() => {
                currentQuestionIndex++;
                loadQuestion();
            }, 1800);
        }

        function endGame() {
            document.getElementById('game-card').classList.add('hidden');
            const endScreen = document.getElementById('end-screen');
            endScreen.classList.remove('hidden');
            document.getElementById('final-score').innerText = score;

            const endTitle = document.getElementById('end-title');
            const endMessage = document.getElementById('end-message');
            const avatarSpeech = document.getElementById('avatar-speech');

            if (correctAnswersCount === totalQuestions) {
                endTitle.innerText = "🏆 ¡Perfecto! ¡Eres un Maestro de las Tablas! 🏆";
                endMessage.innerText = "¡Has respondido todas las multiplicaciones y divisiones sin equivocarte! Tu agilidad mental es deslumbrante.";
                avatarSpeech.innerText = "¡Impresionante! ¡Lograste el 100% de eficiencia!";
                playSound('correct');
            } else if (correctAnswersCount >= 14) {
                endTitle.innerText = "🌟 ¡Gran Trabajo! ¡Lo hiciste muy bien! 🌟";
                endMessage.innerText = `¡Acertaste ${correctAnswersCount} de ${totalQuestions} ejercicios! Tienes un talento fantástico para los números.`;
                avatarSpeech.innerText = "¡Excelente desempeño en mis sensores!";
            } else {
                endTitle.innerText = "💡 ¡Buen Esfuerzo! ¡A Seguir Practicando! 💡";
                endMessage.innerText = `Acertaste ${correctAnswersCount} de ${totalQuestions} ejercicios. Las tablas de multiplicar requieren práctica constante. ¡Vuelve a intentarlo!`;
                avatarSpeech.innerText = "¡Cada intento optimiza tu aprendizaje!";
            }
        }

        function restartGame() {
            playSound('click');
            initGame();
        }

        function goBack() {
            playSound('click');
            window.history.back();
        }

        function openShareModal() {
            playSound('click');
            const currentUrl = window.location.href;
            document.getElementById('share-link-input').value = currentUrl;
            
            const qrImg = document.getElementById('qr-code-img');
            qrImg.src = `https://api.qrserver.com/v1/create-qr-code/?size=180x180&data=${encodeURIComponent(currentUrl)}`;
            
            document.getElementById('share-modal').classList.remove('hidden');
        }

        function closeShareModal() {
            playSound('click');
            document.getElementById('share-modal').classList.add('hidden');
        }

        function copyShareLink() {
            playSound('click');
            const linkInput = document.getElementById('share-link-input');
            linkInput.select();
            linkInput.setSelectionRange(0, 99999);
            document.execCommand('copy');
            
            // Temporary visual feedback
            const btn = event.target;
            const originalText = btn.innerText;
            btn.innerText = '¡Copiado!';
            setTimeout(() => btn.innerText = originalText, 1500);
        }

        window.onload = function() {
            initGame();
        };
    </script>
</body>
</html>
