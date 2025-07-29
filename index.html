<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Office Quiz</title>
    <style>
        /* Grundlegende Styles für die Seite */
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: #f0f2f5;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            color: #1c1e21;
        }

        /* Der Container für das Quiz */
        #quiz-container {
            background-color: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
            width: 90%;
            max-width: 500px;
            text-align: center;
        }

        h2 {
            margin-top: 0;
            color: #333;
        }

        /* Die Antwort-Buttons */
        #answers {
            display: grid;
            grid-template-columns: 1fr;
            gap: 10px;
            margin-top: 20px;
        }

        .answer-btn {
            padding: 15px;
            font-size: 1rem;
            border: 2px solid #ddd;
            border-radius: 8px;
            background-color: #f8f8f8;
            cursor: pointer;
            transition: background-color 0.3s, border-color 0.3s;
        }

        .answer-btn:hover {
            background-color: #e9e9e9;
            border-color: #ccc;
        }

        /* Styles für die Erfolgs-Animation */
        #success-animation {
            display: none; /* Standardmäßig versteckt */
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(255, 255, 255, 0.8);
            justify-content: center;
            align-items: center;
            z-index: 1000;
        }

        .checkmark-container {
            width: 150px;
            height: 150px;
            position: relative;
        }

        .checkmark__circle {
            stroke-dasharray: 166;
            stroke-dashoffset: 166;
            stroke-width: 5;
            stroke-miterlimit: 10;
            stroke: #4CAF50;
            fill: none;
            animation: stroke 0.6s cubic-bezier(0.65, 0, 0.45, 1) forwards;
        }

        .checkmark__check {
            transform-origin: 50% 50%;
            stroke-dasharray: 48;
            stroke-dashoffset: 48;
            stroke-width: 5;
            stroke: #4CAF50;
            fill: none;
            animation: stroke 0.3s cubic-bezier(0.65, 0, 0.45, 1) 0.8s forwards;
        }

        @keyframes stroke {
            100% {
                stroke-dashoffset: 0;
            }
        }
        
        #next-step {
            margin-top: 20px;
            font-size: 1.2rem;
            font-weight: bold;
            opacity: 0; /* Versteckt bis die Animation fertig ist */
            transition: opacity 0.5s ease-in-out 1.5s; /* Erscheint nach 1.5s */
        }
    </style>
</head>
<body>

    <div id="quiz-container">
        <h2>Welcher Charakter ist der "Assistant to the Regional Manager"?</h2>
        <div id="answers">
            <button class="answer-btn">Jim Halpert</button>
            <button class="answer-btn" data-correct="true">Dwight Schrute</button>
            <button class="answer-btn">Pam Beesly</button>
            <button class="answer-btn">Michael Scott</button>
        </div>
        <div id="next-step">
            Super! Der nächste Hinweis ist am alten Wasserturm.
            <!-- Hier könnten Sie auch ein Bild einfügen: <img src="URL_ZUM_BILD" alt="Nächster Ort"> -->
        </div>
    </div>

    <!-- Die Erfolgs-Animation (Häkchen) -->
    <div id="success-animation">
        <div class="checkmark-container">
            <svg class="checkmark" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 52 52">
                <circle class="checkmark__circle" cx="26" cy="26" r="25" fill="none"/>
                <path class="checkmark__check" fill="none" d="M14.1 27.2l7.1 7.2 16.7-16.8"/>
            </svg>
        </div>
    </div>

    <script>
        // Der JavaScript-Teil, der die Logik steuert
        document.addEventListener('DOMContentLoaded', () => {
            const answerButtons = document.querySelectorAll('.answer-btn');
            const successAnimation = document.getElementById('success-animation');
            const nextStepMessage = document.getElementById('next-step');

            answerButtons.forEach(button => {
                button.addEventListener('click', () => {
                    // Überprüfen, ob der geklickte Button das Attribut data-correct="true" hat
                    if (button.dataset.correct === 'true') {
                        // Richtige Antwort
                        successAnimation.style.display = 'flex'; // Animations-Overlay anzeigen
                        nextStepMessage.style.opacity = '1'; // Nachricht für nächsten Schritt einblenden

                        // Alle Buttons deaktivieren
                        answerButtons.forEach(btn => btn.disabled = true);
                    } else {
                        // Falsche Antwort
                        button.style.backgroundColor = '#ff8a80'; // Button rot färben
                        button.disabled = true; // Falschen Button deaktivieren, damit man nicht nochmal rät
                        
                        // Optional: Farbe nach kurzer Zeit zurücksetzen, aber deaktiviert lassen
                        setTimeout(() => {
                           button.style.backgroundColor = '#f8f8f8';
                        }, 800);
                    }
                });
            });
        });
    </script>

</body>
</html>
