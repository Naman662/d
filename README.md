<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Happy Birthday Mam</title>
        <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script> <!-- Include jQuery -->
        <style>
            body {
                background-color: black;
                font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
                text-align: center;
                color: white;
            }
            .birthday-message {
                font-size: 36px;
                color: darkslategray;
                margin-top: 100px;
                display: none;
            }
            .confetti {
                font-size: 24px;
                color: aqua;
                animation: confetti 2s infinite;
            }
            @keyframes confetti {
                0% {
                    transform: translateY(0);
                }
                100% {
                    transform: translateY(-100px);
                }
            }
        </style>
    </head>
    <body>
        <h1 class="birthday-message">Happy Birthday Mam</h1>
        <div class="confetti">
            <div>
                <p>Wishing you a day filled with love and laughter.</p>
                <p>From Naman Maurya</p>
            </div>
        </div>
        <script>
            $(document).ready(function() {
                $(".birthday-message").fadeIn(2000); // Apply the fadeIn effect to the message
            });
        </script>
    </body>
</html>
