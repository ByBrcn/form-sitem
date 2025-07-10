<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>Tanıtım Teması</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fefefe;
      color: #333;
    }
    header {
      background: linear-gradient(135deg, #004d40, #00695c);
      color: white;
      padding: 40px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 32px;
    }
    .section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .section img {
      max-width: 100%;
      border-radius: 12px;
      margin: 20px 0;
    }
    .section h2 {
      margin-top: 0;
      font-size: 24px;
    }
    .section p {
      font-size: 16px;
      line-height: 1.6;
    }
    .form-section {
      background-color: #f4f4f4;
      border-radius: 10px;
      padding: 30px;
      margin-top: 30px;
    }
    input, textarea {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    button {
      background-color: #00796b;
      color: white;
      padding: 12px;
      width: 100%;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }
    button:hover {
      background-color: #004d40;
    }
    footer {
      background-color: #eeeeee;
      padding: 20px;
      text-align: center;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Tanıtım Sayfası Başlığı</h1>
  </header>

  <div class="section">
    <h2>Ürün veya Hizmet Başlığı</h2>
    <p>Buraya ürününüz veya hizmetiniz hakkında kısa ve etkileyici bir açıklama yazabilirsiniz. İstediğiniz zaman bu metni değiştirebilir veya silebilirsiniz.</p>
    <img src="https://via.placeholder.com/900x400?text=G%C3%B6rsel+Buraya" alt="Ürün Görseli">
  </div>

  <div class="section">
    <h2>İkinci Bölüm Başlığı</h2>
    <p>Bu bölümde müşterilerinize sağladığınız faydaları ya da neden sizi tercih etmeleri gerektiğini anlatabilirsiniz.</p>
  </div>

  <div class="section form-section">
    <h2>İletişim Formu</h2>
    <form name="contact" method="POST" data-netlify="true">
      <input type="text" name="adsoyad" placeholder="Ad Soyad" required>
      <input type="email" name="email" placeholder="E-posta" required>
      <textarea name="mesaj" rows="5" placeholder="Mesajınız" required></textarea>
      <button type="submit">Gönder</button>
    </form>
  </div>

  <footer>
    © 2025 Tüm Hakları Saklıdır. Tasarım: Senin Markan
  </footer>

</body>
</html>
