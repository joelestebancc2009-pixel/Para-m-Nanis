<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Un Regalito Especial 💛</title>
  <style>
    /* Estilos Generales / Colores Pasteles */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background-color: #FFFDF0; /* Amarillo pastel muy claro */
      color: #5A5030;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      overflow-x: hidden;
      text-align: center;
    }

    /* PANTALLA 1: PREGUNTA */
    #step1 {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 20px;
      padding: 20px;
      animation: fadeIn 1s ease-in-out;
    }

    h1 {
      font-size: 2rem;
      color: #7A6B32;
    }

    .btn-container {
      display: flex;
      gap: 15px;
      flex-wrap: wrap;
      justify-content: center;
    }

    .btn {
      background-color: #FFE699; /* Amarillo pastel suave */
      border: 2px solid #F5D061;
      color: #5A5030;
      padding: 12px 24px;
      font-size: 1.1rem;
      font-weight: bold;
      border-radius: 25px;
      cursor: pointer;
      transition: all 0.3s ease;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    }

    .btn:hover {
      background-color: #FCE082;
      transform: scale(1.05);
    }

    /* PANTALLA 2: ÁRBOL DE CORAZÓN */
    #step2 {
      display: none;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      width: 100vw;
      height: 100vh;
      position: relative;
      cursor: pointer;
    }

    .instruction {
      position: absolute;
      top: 10%;
      font-size: 1.2rem;
      background-color: rgba(255, 253, 240, 0.8);
      padding: 10px 20px;
      border-radius: 20px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
      animation: pulse 2s infinite;
    }

    /* Contenedor del Árbol */
    .tree-container {
      position: relative;
      width: 300px;
      height: 350px;
      display: flex;
      justify-content: center;
      align-items: flex-end;
    }

    /* Tronco del árbol */
    .trunk {
      width: 24px;
      height: 140px;
      background-color: #D2B48C; /* Marrón pastel */
      border-radius: 10px 10px 0 0;
      position: relative;
      z-index: 1;
    }

    /* Ramas suaves */
    .trunk::before, .trunk::after {
      content: '';
      position: absolute;
      width: 12px;
      height: 50px;
      background-color: #D2B48C;
      border-radius: 5px;
    }
    .trunk::before {
      top: 30px;
      left: -15px;
      transform: rotate(-35deg);
    }
    .trunk::after {
      top: 20px;
      right: -15px;
      transform: rotate(35deg);
    }

    /* Copa del Árbol en forma de Corazón con Flores */
    .heart-crown {
      position: absolute;
      top: 20px;
      width: 240px;
      height: 220px;
      z-index: 2;
    }

    .heart-flower {
      position: absolute;
      font-size: 22px;
      animation: float 3s ease-in-out infinite alternate;
    }

    /* Lluvia de Flores (Efecto explosión) */
    .falling-flower {
      position: fixed;
      font-size: 25px;
      user-select: none;
      pointer-events: none;
      z-index: 999;
      animation: fall 3s linear forwards;
    }

    /* PANTALLA 3: PLANETA, GIRASOL Y RAMOS */
    #step3 {
      display: none;
      flex-direction: column;
      align-items: center;
      padding: 40px 20px;
      min-height: 100vh;
      width: 100%;
    }

    /* Animación del Planeta convirtiéndose en Girasol */
    .transform-container {
      width: 160px;
      height: 160px;
      border-radius: 50%;
      position: relative;
      display: flex;
      justify-content: center;
      align-items: center;
      margin-bottom: 30px;
      transition: all 2.5s ease-in-out;
      background: #A3C9A8; /* Verde/Azul pastel (Planeta) */
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
      font-size: 80px;
    }

    /* Clase que se activa con JS para transformarlo */
    .transform-container.sunflower {
      background: #F4C430; /* Amarillo Girasol */
      transform: rotate(360deg) scale(1.1);
      box-shadow: 0 0 25px #FCE082;
    }

    /* Ramos de Flores / Mensajes */
    .bouquets-grid {
      display: flex;
      flex-direction: column;
      gap: 20px;
      width: 100%;
      max-width: 500px;
    }

    .bouquet-card {
      background-color: #FFF9D6;
      border: 2px dashed #F3D368;
      border-radius: 15px;
      padding: 15px 20px;
      display: flex;
      align-items: center;
      gap: 15px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.03);
      opacity: 0;
      transform: translateY(20px);
      transition: all 0.8s ease;
    }

    .bouquet-card.show {
      opacity: 1;
      transform: translateY(0);
    }

    .bouquet-icon {
      font-size: 2.2rem;
    }

    .bouquet-text {
      font-size: 1.1rem;
      font-weight: 600;
      color: #6B5B28;
      text-align: left;
    }

    /* ANIMACIONES */
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes pulse {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.05); }
    }

    @keyframes float {
      0% { transform: translateY(0px); }
      100% { transform: translateY(-5px); }
    }

    @keyframes fall {
      0% {
        opacity: 1;
        transform: translateY(0) rotate(0deg);
      }
      100% {
        opacity: 0;
        transform: translateY(100vh) rotate(360deg);
      }
    }
  </style>
</head>
<body>

  <!-- PANTALLA 1 -->
  <div id="step1">
    <h1>¿Quieres ver tu regalito linda? 💛</h1>
    <div class="btn-container">
      <button class="btn" onclick="goToStep2()">Sí quieroo</button>
      <button class="btn" onclick="goToStep2()">Obvio que sí</button>
    </div>
  </div>

  <!-- PANTALLA 2 -->
  <div id="step2" onclick="burstFlowers()">
    <div class="instruction">✨ Haz click en el corazón ✨</div>
    <div class="tree-container">
      <div id="heartCrown" class="heart-crown"></div>
      <div class="trunk"></div>
    </div>
  </div>

  <!-- PANTALLA 3 -->
  <div id="step3">
    <div id="planet" class="transform-container">🌍</div>
    
    <div class="bouquets-grid">
      <div class="bouquet-card">
        <span class="bouquet-icon">💐</span>
        <span class="bouquet-text">FELIZ DIA DE LAS FLORES AMARILLAS</span>
      </div>
      <div class="bouquet-card">
        <span class="bouquet-icon">🌻</span>
        <span class="bouquet-text">TE QUIEROOOOOOOOO</span>
      </div>
      <div class="bouquet-card">
        <span class="bouquet-icon">🌼</span>
        <span class="bouquet-text">ERES MUUUY TIERNAAAAA</span>
      </div>
      <div class="bouquet-card">
        <span class="bouquet-icon">💐</span>
        <span class="bouquet-text">¿Eres muy linda lo sabías?</span>
      </div>
      <div class="bouquet-card">
        <span class="bouquet-icon">🌻</span>
        <span class="bouquet-text">Tus ojitos son hermosísimos</span>
      </div>
    </div>
  </div>

  <script>
    // Ir de la Pantalla 1 a la 2
    function goToStep2() {
      document.getElementById('step1').style.display = 'none';
      document.getElementById('step2').style.display = 'flex';
      buildHeartTree();
    }

    // Dibujar las flores formando la silueta de un corazón
    function buildHeartTree() {
      const heartCrown = document.getElementById('heartCrown');
      const totalFlowers = 35;
      
      for (let i = 0; i < totalFlowers; i++) {
        const flower = document.createElement('span');
        flower.className = 'heart-flower';
        flower.innerHTML = '🌼';

        // Ecuación paramétrica de un corazón
        const t = (Math.PI * 2 / totalFlowers) * i;
        const x = 16 * Math.pow(Math.sin(t), 3);
        const y = -(13 * Math.cos(t) - 5 * Math.cos(2*t) - 2 * Math.cos(3*t) - Math.cos(4*t));

        // Escalar y posicionar en el contenedor
        const posX = 110 + (x * 6.5);
        const posY = 90 + (y * 6.5);

        flower.style.left = `${posX}px`;
        flower.style.top = `${posY}px`;
        flower.style.animationDelay = `${Math.random() * 2}s`;

        heartCrown.appendChild(flower);
      }
    }

    let isExploding = false;

    // Lluvia masiva de flores y paso a la Pantalla 3
    function burstFlowers() {
      if (isExploding) return;
      isExploding = true;

      // Crear múltiples flores amarillas cayendo
      for (let i = 0; i < 70; i++) {
        setTimeout(() => {
          const flower = document.createElement('div');
          flower.className = 'falling-flower';
          
          // Variedad de flores amarillas
          const icons = ['💛', '🌻', '🌼', '✨'];
          flower.innerHTML = icons[Math.floor(Math.random() * icons.length)];
          
          flower.style.left = Math.random() * 100 + 'vw';
          flower.style.top = '-50px';
          flower.style.animationDuration = (Math.random() * 2 + 2) + 's';
          
          document.body.appendChild(flower);

          // Limpiar el HTML después de que caigan
          setTimeout(() => flower.remove(), 3000);
        }, i * 40);
      }

      // Pasar a la tercera pantalla tras la explosión
      setTimeout(() => {
        document.getElementById('step2').style.display = 'none';
        document.getElementById('step3').style.display = 'flex';
        startPlanetTransformation();
      }, 2500);
    }

    // Transformación del Planeta a Girasol y aparición de los ramos
    function startPlanetTransformation() {
      const planet = document.getElementById('planet');
      
      // Transformar poco a poco a girasol
      setTimeout(() => {
        planet.classList.add('sunflower');
        planet.innerHTML = '🌻';
      }, 600);

      // Mostrar los 5 ramos de manera progresiva
      const cards = document.querySelectorAll('.bouquet-card');
      cards.forEach((card, index) => {
        setTimeout(() => {
          card.classList.add('show');
        }, 2200 + (index * 600)); // Aparecen suavemente uno por uno
      });
    }
  </script>
</body>
</html>
