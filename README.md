# Link_sara
<!DOCTYPE html>
<html>
<head>
  <title>Dra. Sara Silveira</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      background-color: #CF6759;
      font-family: Arial, sans-serif;
      color: #ffffff;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }

    .container {
      flex: 1;
      max-width: 600px;
      margin: 0 auto;
      padding: 20px;
    }

    .profile {
      text-align: center;
      margin-bottom: 20px;
    }

    .profile img {
      width: 100%;
      max-width: 150px;
      height: auto;
      border-radius: 50%;
      object-fit: cover;
    }

    .name {
      font-size: 24px;
      font-weight: bold;
      margin-bottom: 10px;
    }

    .links {
      display: flex;
      flex-direction: column;
      gap: 10px;
    }

    .link {
      background-color: #D68675;
      padding: 10px;
      border-radius: 5px;
      text-align: center;
      text-decoration: none;
      color: #ffffff;
      transition: background-color 0.3s;
    }

    .link:hover {
      background-color: #B66B5B;
    }

    footer {
      background-color: #D68675;
      color: #ffffff;
      padding: 10px;
      text-align: center;
      font-size: 14px;
      position: fixed;
      bottom: 0;
      left: 0;
      width: 100%;
    }

    .footer-content {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 5px;
    }

    .footer-text {
      font-size: 12px;
    }

    .footer-copyright {
      font-size: 10px;
    }

    .footer-border {
      border-top: 1px solid #ffffff;
      margin-top: 10px;
      padding-top: 10px;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="profile">
      <img src="profile.jpeg" alt="Foto da Dra. Sara Silveira">
      <div class="name">Dra. Sara Silveira</div>
    </div>

    <div class="links">
      <a href="botox.html" class="link">Botox <span>- Tratamento para rejuvenescimento facial</span></a>
      <a href="preenchimento.html" class="link">Preenchimento</a>
      <a href="procedimento3.html" class="link">Procedimento 3</a>
      <a href="procedimento4.html" class="link">Procedimento 4</a>
      <!-- Adicione mais links aqui -->
    </div>
  </div>

  <footer>
    <div class="footer-content">
      <div class="footer-text">Direitos Reservados para</div>
      <div class="footer-copyright">Sara Silveira</div>
    </div>
    <div class="footer-border"></div>
  </footer>
</body>
</html>
