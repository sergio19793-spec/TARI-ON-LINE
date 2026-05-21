<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TARI Online</title>

  <style>
    body{
      font-family: Arial, sans-serif;
      background:#f3f4f6;
      margin:0;
      padding:0;
    }

    header{
      background:#166534;
      color:white;
      padding:30px;
    }

    h1{
      margin:0;
    }

    .container{
      max-width:1200px;
      margin:auto;
      padding:40px 20px;
    }

    .hero{
      background:white;
      padding:40px;
      border-radius:20px;
      margin-bottom:30px;
    }

    .cards{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:20px;
    }

    .card{
      background:white;
      padding:30px;
      border-radius:20px;
      box-shadow:0 5px 15px rgba(0,0,0,0.1);
    }

    .card h3{
      margin-top:10px;
    }

    button{
      background:#166534;
      color:white;
      border:none;
      padding:12px 20px;
      border-radius:10px;
      cursor:pointer;
      width:100%;
      margin-top:20px;
      font-size:16px;
    }

    button:hover{
      background:#14532d;
    }
  </style>
</head>

<body>

<header>
  <h1>Comune di Inzago</h1>
  <p>Portale Servizi TARI Online</p>
</header>

<div class="container">

  <div class="hero">
    <h2>Gestione TARI Online</h2>

    <p>
      Presenta online dichiarazioni, variazioni e richieste relative alla Tassa Rifiuti.
    </p>
  </div>

  <div class="cards">

    <div class="card">
      <h2>🏠</h2>
      <h3>Apertura Utenza Domestica</h3>

      <p>
        Nuova iscrizione TARI per abitazioni private.
      </p>

      <button>Avvia pratica</button>
    </div>

    <div class="card">
      <h2>🏢</h2>
      <h3>Apertura Utenza Non Domestica</h3>

      <p>
        Nuova iscrizione TARI per aziende e attività.
      </p>

      <button>Avvia pratica</button>
    </div>

    <div class="card">
      <h2>✏️</h2>
      <h3>Modifica / Chiusura</h3>

      <p>
        Modifica o chiusura posizione TARI.
      </p>

      <button>Avvia pratica</button>
    </div>

    <div class="card">
      <h2>📧</h2>
      <h3>Invio Avvisi via Email</h3>

      <p>
        Richiedi recapito digitale degli avvisi TARI.
      </p>

      <button>Avvia pratica</button>
    </div>

  </div>

</div>

</body>
</html>
