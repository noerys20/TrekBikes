<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Todo sobre la Trek Roscoe 7</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: #EDF2EF; /* Culto */
      color: #212738; /* Pasas Negras */
    }

    .rectangular-header {
      background-color: #212738; /* Pasas Negras */
      color: #EDF2EF; /* Culto */
      padding: 3em 1em;
      text-align: center;
      border-radius: 0 0 16px 16px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
      margin-bottom: 2em;
    }

    .rectangular-header h1 {
      margin: 0;
      font-size: 2.2em;
      text-transform: uppercase;
      letter-spacing: 1px;
    }

    .subtitulo {
      font-size: 1.2em;
      font-weight: 300;
      margin-top: 0.5em;
      color: #D1D646; /* Máximo Verde Amarillo */
    }

    nav ul {
      display: flex;
      justify-content: center;
      background-color: #57C4E5; /* Azul cielo vivo */
      list-style: none;
      padding: 0;
      margin: 0;
    }

    nav li {
      margin: 0 1em;
    }

    nav a {
      color: white;
      text-decoration: none;
      padding: 1em;
      display: block;
      font-weight: bold;
    }

    nav a:hover {
      background-color: #F97068; /* Agridulce */
    }

    main {
      padding: 2em;
    }

    section {
      margin-bottom: 3em;
      background-color: white;
      padding: 1.5em;
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(33, 39, 56, 0.1);
    }

    h2 {
      border-left: 8px solid #57C4E5; /* Azul cielo vivo */
      padding-left: 0.5em;
      color: #212738;
    }

    .imagen-bici {
      width: 100%;
      max-width: 400px;
      display: block;
      margin: 1em auto;
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 1em;
    }

    th, td {
      border: 1px solid #ccc;
      padding: 0.7em;
      text-align: center;
      background-color: #EDF2EF;
    }

    th {
      background-color: #212738;
      color: white;
    }

    .usos-container {
      display: flex;
      flex-wrap: wrap;
      gap: 2em;
      justify-content: space-around;
    }

    .uso {
      background: #D1D646;
      padding: 1em;
      border-radius: 12px;
      width: 100%;
      max-width: 400px;
      color: #212738;
      font-weight: bold;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }

    footer {
      background-color: #212738;
      color: white;
      text-align: center;
      padding: 1em;
      margin-top: 2em;
    }
  </style>
</head>
<body>

  <header class="rectangular-header">
    <h1>Todo sobre la Trek Roscoe 7</h1>
  </header>

  <nav>
    <ul>
      <li><a href="#roscoe">Roscoe 7</a></li>
      <li><a href="#marlin">Marlin 5</a></li>
      <li><a href="#comparacion">Comparación</a></li>
      <li><a href="#usos">Usos y Terreno</a></li>
    </ul>
  </nav>

  <main>
    <section id="roscoe">
      <h2>Trek Roscoe 7</h2>
      <img src="roscoe7.jpg" alt="Trek Roscoe 7" class="imagen-bici" />
      <p>Bicicleta diseñada para senderos técnicos. Rápida, agresiva y con componentes listos para la aventura.</p>
      <ul>
        <li>Cuadro: Aluminio Alpha Gold</li>
        <li>Suspensión: RockShox Recon Silver, 140 mm</li>
        <li>Transmisión: SRAM NX Eagle 12 velocidades</li>
        <li>Ruedas: 29”</li>
      </ul>
    </section>

    <section id="marlin">
      <h2>Trek Marlin 5</h2>
      <img src="marlin5.jpg" alt="Trek Marlin 5" class="imagen-bici" />
      <p>Una bicicleta confiable para principiantes o ciclistas urbanos. Perfecta para caminos, parques y montaña ligera.</p>
      <ul>
        <li>Cuadro: Aluminio Alpha Silver</li>
        <li>Suspensión: SR Suntour XCE 100 mm</li>
        <li>Transmisión: Shimano Altus 2x8 velocidades</li>
        <li>Ruedas: 27.5” / 29” (según talla)</li>
      </ul>
    </section>

    <section id="comparacion">
      <h2>Comparación rápida</h2>
      <table>
        <tr>
          <th>Característica</th>
          <th>Roscoe 7</th>
          <th>Marlin 5</th>
        </tr>
        <tr>
          <td>Suspensión</td>
          <td>140 mm RockShox</td>
          <td>100 mm Suntour</td>
        </tr>
        <tr>
          <td>Transmisión</td>
          <td>SRAM NX Eagle 1x12</td>
          <td>Shimano Altus 2x8</td>
        </tr>
        <tr>
          <td>Peso aprox.</td>
          <td>13.9 kg</td>
          <td>14.5 kg</td>
        </tr>
        <tr>
          <td>Precio</td>
          <td>$28,000 MXN</td>
          <td>$12,000 MXN</td>
        </tr>
      </table>
    </section>

    <section id="usos">
      <h2>¿Para qué se utilizan?</h2>
      <div class="usos-container">
        <div class="uso">
          <h3>Roscoe 7</h3>
          <p>Perfecta para:</p>
          <ul>
            <li>Senderos técnicos</li>
            <li>Terreno rocoso</li>
            <li>Descensos moderados</li>
            <li>Singletracks</li>
          </ul>
        </div>
        <div class="uso">
          <h3>Marlin 5</h3>
          <p>Perfecta para:</p>
          <ul>
            <li>Caminos de tierra</li>
            <li>Calles urbanas</li>
            <li>Montaña ligera</li>
            <li>Desplazamientos diarios</li>
          </ul>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 - Página creada por [David Reyes Reyes]</p>
  </footer>

</body>
</html>
