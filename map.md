---
layout: page
title: Map
---
 <html>
<head>
    <title>Simple Leaflet Map</title>
    <meta charset="utf-8" />
    <link rel="stylesheet" href="leaflet.css" />
</head>
<body>
    <script src="leaflet.js"></script>

<div id="map" style="width: 600px; height: 400px"></div>

<script>
        var map = L.map('map').setView([0.3076, 32.5985], 12);
        mapLink = 
            '<a href="http://openstreetmap.org">OpenStreetMap</a>';
        L.tileLayer(
            'http://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
            attribution: '&copy; ' + mapLink + ' Contributors',
            maxZoom: 18,
            }).addTo(map);
    </script>
</body>
</html>