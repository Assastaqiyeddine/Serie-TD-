<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>خريطة الطرق الوطنية في الجزائر</title>
<link rel="stylesheet" href="https://unpkg.com/leaflet/dist/leaflet.css"/>
<style>
  #map { height: 90vh; width: 100%; }
</style>
</head>
<body>
<h2 style="text-align:center;">خريطة الطرق الوطنية في الجزائر</h2>
<div id="map"></div>

<script src="https://unpkg.com/leaflet/dist/leaflet.js"></script>
<script>
  // إنشاء الخريطة
  var map = L.map('map').setView([28, 3], 5);

  // إضافة خريطة أساسية
  L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
    maxZoom: 19
  }).addTo(map);

  // مثال لولاية الجزائر
  var alger = L.polygon([[36.7,3.0],[36.7,3.5],[36.4,3.5],[36.4,3.0]], {
    color: 'blue',
    fillColor: 'lightblue',
    fillOpacity: 0.5
  }).addTo(map);

  alger.bindPopup("<b>ولاية الجزائر</b><br>الطرق الوطنية: 2");

  // مثال طريق وطني
  var route1 = L.polyline([[36.5,3.1],[36.6,3.4]], {color:'green'}).addTo(map);
  route1.bindPopup("<b>طريق وطني 1</b><br>الحالة: جاهز<br>Km: 10-50<br>الميزانية: 500,000,000 دج");
</script>
</body>
</html>
