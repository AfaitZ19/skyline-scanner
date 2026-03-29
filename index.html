<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Skyline Scanner</title>

  <script src="https://unpkg.com/html5-qrcode"></script>

  <style>
    body {
      font-family: Arial;
      text-align: center;
      padding: 20px;
      background: #f5f7fa;
    }
    #reader {
      width: 300px;
      margin: 20px auto;
    }
    button {
      padding: 12px 20px;
      font-size: 16px;
      border: none;
      border-radius: 10px;
      background: #1a4fa0;
      color: white;
      cursor: pointer;
    }
  </style>
</head>

<body>

<h2>📦 Skyline Scanner</h2>

<button onclick="startScan()">📷 เปิดกล้อง</button>

<div id="reader"></div>

<script>
let scanner;

function startScan() {
  if (scanner) return;

  scanner = new Html5Qrcode("reader");

  scanner.start(
    { facingMode: "environment" },
    {
      fps: 10,
      qrbox: 250
    },
    (decodedText) => {
      alert("สแกนได้: " + decodedText);

      // ยิงเข้า Apps Script
      fetch("https://script.google.com/macros/s/AKfycbwXPMj_QZdNFbKSaL69xqXoH7iXVaZeO5hRgWMTbYoSXm1T-AYMrvajOAPtt9evg40sfA/exec", {
        method: "POST",
        body: JSON.stringify({
          action: "in",
          code: decodedText
        })
      });
    }
  ).catch(err => {
    alert("เปิดกล้องไม่ได้: " + err);
  });
}
</script>

</body>
</html>
