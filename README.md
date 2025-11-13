<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Série TD n°1 - Cinématique du point matériel</title>
  <style>
    body {
      font-family: "Segoe UI", Arial, sans-serif;
      margin: 40px;
      background-color: #f8f9fa;
      color: #333;
      line-height: 1.6;
    }
    h1, h2, h3 {
      color: #004080;
    }
    .exercice {
      background-color: #ffffff;
      border: 2px solid #d3d3d3;
      border-radius: 8px;
      padding: 20px;
      margin-bottom: 25px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    code, pre {
      background-color: #f0f0f0;
      padding: 3px 6px;
      border-radius: 4px;
    }
    .corrige {
      background-color: #e6f3ff;
      border-left: 4px solid #0078d4;
      padding: 10px 15px;
      margin-top: 10px;
    }
  </style>
</head>
<body>

  <h1>🧮 Série TD n°1 – Cinématique du point matériel</h1>
  <p><strong>Objectifs du TD :</strong> Décrire le mouvement d’un point matériel dans différents systèmes de coordonnées, calculer la vitesse et l’accélération, et interpréter les composantes tangentielle et normale.</p>

  <div class="exercice">
    <h2>Exercice 1 – Mouvement rectiligne non uniforme</h2>
    <p>Un point matériel M se déplace sur une droite selon la loi :</p>
    <pre>x(t) = 4t² - 3t &nbsp;&nbsp;&nbsp; (en mètres, t en secondes)</pre>
    <ol>
      <li>Déterminer la vitesse instantanée <em>v(t)</em>.</li>
      <li>Déterminer l’accélération <em>a(t)</em>.</li>
      <li>Donner les valeurs de <em>v</em> et <em>a</em> à t = 2 s.</li>
      <li>Interpréter le signe de l’accélération.</li>
    </ol>

    <div class="corrige">
      <strong>Corrigé :</strong><br>
      v(t) = dx/dt = 8t - 3<br>
      a(t) = dv/dt = 8<br>
      À t = 2 s → v = 13 m/s et a = 8 m/s².<br>
      Accélération constante et positive ⇒ mouvement uniformément accéléré.
    </div>
  </div>

  <div class="exercice">
    <h2>Exercice 2 – Mouvement circulaire uniforme</h2>
    <p>Un point M décrit un cercle de rayon R = 0,5 m avec une vitesse angulaire constante ω = 10 rad/s.</p>
    <ol>
      <li>Donner les expressions du vecteur position, vitesse et accélération.</li>
      <li>Calculer les valeurs de la vitesse et de l’accélération.</li>
    </ol>

    <div class="corrige">
      <strong>Corrigé :</strong><br>
      r(t) = R(cos(ωt) i + sin(ωt) j)<br>
      v(t) = Rω(-sin(ωt) i + cos(ωt) j)<br>
      a(t) = -Rω²(cos(ωt) i + sin(ωt) j)<br>
      |v| = Rω = 5 m/s &nbsp;&nbsp; |a|


 
