<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>موقعي الشخصي</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    body {
      background-color: #000;
      color: #fff;
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 20px;
    }
    .profile-pic {
      max-width: 250px;
      border-radius: 10px;
      margin-bottom: 20px;
    }
    .contact-list {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 15px;
    }
    .contact-item {
      display: flex;
      align-items: center;
      gap: 10px;
      background: #111;
      padding: 10px 15px;
      border-radius: 8px;
      width: fit-content;
    }
    .contact-item a, .contact-item span {
      color: #fff;
      text-decoration: none;
      font-size: 18px;
    }
    .contact-item i {
      font-size: 22px;
      color: #1db954;
    }
    .contact-item.instagram i {
      color: #e1306c;
    }
  </style>
</head>
<body>
  <img src="uploaded_image.jpg" alt="Profile Picture" class="profile-pic">
  <div class="contact-list">
    <div class="contact-item instagram">
      <i class="fab fa-instagram"></i>
      <a href="https://www.instagram.com/2m.oot" target="_blank">2m.oot</a>
    </div>
    <div class="contact-item whatsapp">
      <i class="fab fa-whatsapp"></i>
      <a href="https://wa.me/201154290220" target="_blank">01154290220</a>
    </div>
    <div class="contact-item whatsapp">
      <i class="fab fa-whatsapp"></i>
      <a href="https://wa.me/201154354411" target="_blank">01154354411 - أعمال</a>
    </div>
  </div>
</body>
</html>
