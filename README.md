<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rangos de Pago - KaliumRango</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Open+Sans:wght@300;400&display=swap');

        body {
            font-family: 'Open Sans', sans-serif;
            background-color: #0f1c2d; /* Negro azulado muy oscuro para el fondo */
            color: #e0e0e0; /* Texto claro */
            margin: 0;
            padding: 20px;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            background-color: #1a2a3a; /* Azul oscuro para el contenedor principal */
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.4);
        }

        h1 {
            font-family: 'Montserrat', sans-serif;
            text-align: center;
            color: #5b9bd5; /* Azul medio para el título principal */
            margin-bottom: 40px;
            font-size: 2.8em;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.5);
        }

        .rank-section {
            background-color: #2a3d52; /* Azul grisáceo para las tarjetas de rango */
            border-radius: 8px;
            padding: 25px;
            margin-bottom: 30px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .rank-section:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.5);
        }

        .rank-section h2 {
            font-family: 'Montserrat', sans-serif;
            color: #d0e7ff; /* Color por defecto para los títulos de rango */
            font-size: 2.2em;
            margin-top: 0;
            border-bottom: 2px solid rgba(208, 231, 255, 0.5);
            padding-bottom: 10px;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .rank-section h2 .cost {
            font-size: 0.7em;
            background-color: #5b9bd5; /* Fondo azul para el coste por defecto */
            color: #0f1c2d; /* Texto oscuro para el coste */
            padding: 5px 15px;
            border-radius: 5px;
            font-weight: bold;
        }

        .rank-section ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        .rank-section ul li {
            background-color: #3b5066; /* Azul más oscuro para los ítems de la lista */
            padding: 12px 15px;
            margin-bottom: 10px;
            border-radius: 5px;
            display: flex;
            align-items: flex-start;
        }

        .rank-section ul li:last-child {
            margin-bottom: 0;
        }

        .rank-section ul li::before {
            content: '✅'; /* Checkmark icon for list items */
            margin-right: 10px;
            color: #9cd55b; /* Verde claro para el checkmark */
            font-size: 1.2em;
            line-height: 1.5; /* Align with text */
        }

        .rank-section p {
            font-size: 1.1em;
            color: #c0c0c0;
            margin-bottom: 15px;
        }

        /* Colores específicos para cada rango */
        .vip h2 { color: #a4d8ff; border-color: rgba(164, 216, 255, 0.5); } /* Azul clarito para VIP */
        .vip h2 .cost { background-color: #a4d8ff; color: #0f1c2d; }
        .vip ul li { background-color: #4a5c6d; } /* Fondo para ítems VIP */
        .vip ul li::before { content: '👑'; color: #f2e200; } /* Corona dorada para VIP */


        .lunar h2 { color: #c0c0c0; border-color: rgba(192, 192, 192, 0.5); } /* Gris clarito para Lunar */
        .lunar h2 .cost { background-color: #c0c0c0; color: #0f1c2d; }
        .lunar ul li { background-color: #5d6d7e; } /* Fondo para ítems Lunar */
        .lunar ul li::before { content: '🌙'; color: #b0c4de; } /* Luna para Lunar */


        .kalium h2 { color: #3b8bc1; border-color: rgba(59, 139, 193, 0.5); } /* Azul un poco más oscuro para Kalium */
        .kalium h2 .cost { background-color: #3b8bc1; color: #fff; }
        .kalium ul li { background-color: #2d455b; } /* Fondo para ítems Kalium */
        .kalium ul li::before { content: '✨'; color: #e0e0e0; } /* Chispa para Kalium */


        .obtain-info {
            font-style: italic;
            color: #b0b0b0;
            margin-top: 20px;
            padding-top: 15px;
            border-top: 1px dashed #4a5c6d;
        }

        footer {
            text-align: center;
            margin-top: 50px;
            padding-top: 20px;
            border-top: 1px solid #2a3d52;
            color: #808080;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>✨ Rangos de Pago de KALIUM ✨</h1>

        <p>¡Bienvenido a la página de rangos de pago de KaliumRango! Aquí encontrarás todos los detalles y beneficios exclusivos de nuestros rangos premium. ¡Mejora tu experiencia de juego hoy mismo!</p>

        ---

        <div class="rank-section vip">
            <h2>
                👑 Rango VIP 👑
                <span class="cost">Coste: 5€</span>
            </h2>
            <p>El rango VIP es perfecto para aquellos que buscan una ventaja inicial y beneficios esenciales para su aventura en el servidor.</p>
            <ul>
                <li>Prefijo en el tabulador en cualquier modalidad.</li>
                <li>Prefijo en el chat en cualquier modalidad.</li>
                <li>Canal Privado con miembros de su mismo rango.</li>
                <li>Survival Kit Vip (puedes ver qué contiene con /kit), se reclama cada 2 meses.</li>
                <li>Una fila más de espacio en la mochila.</li>
                <li>BoxPvP: Se consigue directamente el kit de la segunda mina.</li>
                <li>¡Próximamente más mejoras!</li>
            </ul>
            <p class="obtain-info">Este rango se puede conseguir pagando o boosteando el servidor de Discord de Kalium (cada boosteo es un mes de rango).</p>
        </div>

        ---

        <div class="rank-section lunar">
            <h2>
                🌙 Rango Lunar 🌙
                <span class="cost">Coste: 8€</span>
            </h2>
            <p>El rango Lunar te eleva a un nuevo nivel con más privilegios y una experiencia de juego aún más fluida y gratificante.</p>
            <ul>
                <li>Prefijo en el tabulador en cualquier modalidad.</li>
                <li>Prefijo en el chat en cualquier modalidad.</li>
                <li>Canal Privado con miembros de su mismo rango.</li>
                <li>Survival Kit Lunar (puedes ver qué contiene con /kit), se reclama cada 2 meses.</li>
                <li>Dos filas más de espacio en la mochila.</li>
                <li>BoxPvP: Se consigue directamente el kit de la cuarta mina.</li>
                <li>¡Próximamente más mejoras!</li>
            </ul>
            <p class="obtain-info">Este rango se puede conseguir pagando o boosteando el servidor de Discord de Kalium 3 veces (cada boosteo es un mes de rango).</p>
        </div>

        ---

        <div class="rank-section kalium">
            <h2>
                ✨ Rango KALIUM ✨
                <span class="cost">Coste: 12€</span>
            </h2>
            <p>El rango KALIUM es para los jugadores más dedicados, ofreciendo la máxima cantidad de beneficios y la mejor experiencia premium disponible en el servidor.</p>
            <ul>
                <li>Prefijo en el tabulador en cualquier modalidad.</li>
                <li>Prefijo en el chat en cualquier modalidad.</li>
                <li>Canal Privado con miembros de su mismo rango.</li>
                <li>Survival Kit Kalium (puedes ver qué contiene con /kit), se reclama cada 2 meses.</li>
                <li>Acceso a una segunda mochila.</li>
                <li>Puedes cambiarte el nombre con `/nick` (esto no aparecerá en el tabulador, pero sí cuando hagas tpa o trade).</li>
                <li>BoxPvP: Se consigue directamente el kit de la sexta mina.</li>
                <li>¡Próximamente más mejoras!</li>
            </ul>
            <p class="obtain-info">Este rango solo se puede conseguir pagando.</p>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 KaliumRango. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
