<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Berna'ya</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #fffaf6;
      color: #333;
      padding: 30px;
      max-width: 700px;
      margin: auto;
      line-height: 1.6;
    }
    h1 {
      color: #b35f5f;
      text-align: center;
      margin-bottom: 20px;
    }
    .section {
      margin-bottom: 40px;
    }
    .button {
      display: block;
      width: fit-content;
      margin: 30px auto;
      background-color: #b35f5f;
      color: white;
      border: none;
      padding: 12px 24px;
      border-radius: 8px;
      cursor: pointer;
      font-size: 16px;
    }
    .hidden {
      display: none;
      text-align: center;
      font-weight: bold;
      margin-top: 20px;
      color: #2e7d32;
    }
  </style>
</head>
<body>
  <h1>Özür Dilerim <3</h1>

  <div class="section">
    <p>Sana bir şeyler söylemiştim ve farkında olmadan sana <strong>değersizmişsin</strong> gibi hissettirdim. Bu cümle bile içimi acıtıyor çünkü senin kendini böyle hissetmen, benim istemediğim en son şeydi.</p>
  </div>

  <div class="section">
    <p>Sen kırıldığında konuşmazsın… Sessizleşirsin. İçine atarsın, affetmeye çalışırsın ama yara orada kalır. Ve ben… o yarayı açan kişi olduğum için kendimden utandım.</p>
  </div>

  <div class="section">
    <p>Barıştık, evet. Ama senin kalbin hâlâ tam iyileşmedi, biliyorum. Bu sayfa, sadece ‘özür diledim’ demek değil… Sana değer verdiğimi, bunu tekrar tekrar hatırlatmak için. Kırılan şey tamir olur ama özen ister. Ben o özeni göstermek istiyorum.</p>
  </div>

  <div class="section">
    <p>Seninle konuşmak, gülmek, paylaşmak güzeldi. Hâlâ öyle. Sadece kırgınlık değil, <strong>değer</strong> de kalsın istiyorum içimizde. Ve ben bunun için elimden geleni yapacağım. Sadece bil istedim…</p>
  </div>

  <button class="button" onclick="showMessage()">Gönlümü Almana İzin Veriyorum</button>
  <div id="message" class="hidden">Demek ki hâlâ bir şansım var. Teşekkür ederim... İyi geceler mesajını bekliyorum 🌱</div>

  <script>
    function showMessage() {
      document.getElementById('message').style.display = 'block';
    }
  </script>
</body>
</html>

<!-- Açılışta gösterilecek tam ekran görsel -->
<div class="overlay" id="overlay">
  <span class="close-btn" onclick="closeOverlay()">×</span>
  <img src="eşek ömer.png" alt="Özür Görseli">
</div>

<style>
  .overlay {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0,0,0,0.9);
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: 9999;
  }

  .overlay img {
    max-width: 90%;
    max-height: 90%;
    border-radius: 16px;
    box-shadow: 0 0 20px rgba(255,255,255,0.3);
  }

  .close-btn {
    position: absolute;
    top: 20px;
    right: 30px;
    font-size: 36px;
    color: white;
    cursor: pointer;
    font-weight: bold;
  }
</style>

<script>
  function closeOverlay() {
    document.getElementById('overlay').style.display = 'none';
  }
</script>
