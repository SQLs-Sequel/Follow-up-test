<!DOCTYPE html>
<html>
<head>
    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.6.0/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_75fb3774c8bbaa6194d248260d0a9423 {

                        position: relative;
                        width: 85.0%;
                        height: 100.0%;
                        left: 5.0%;
                        top: 0.0%;  
                    }
                    h1 {
                        padding-top: 0px;
                    }
                    hr {
                        position: relative;
                        top: 10px;
                        border: none;
                        height: 12px;
                        background: rgb(54, 52, 52);
                        margin-bottom: 50px;
                    }
                    body {
                        width: 95vw;
                        height: 100vh;
                    }

                </style>
</head>
<body>
  <h2 style="text-align:center;" style ="font-family: Arial"><b>P170<br/>67 Marshall St - B67 7NB<br/>Logger type: HWM</b></h2>
  <hr>
<div class="folium-map" id="map_75fb3774c8bbaa6194d248260d0a9423" ></div>
  <hr>
  <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfNHqY9LZnNvHeROFVMCX5W3L8ARKeZ5SnWqeIe6Dz6FG5q7g/viewform?usp=pp_url&entry.1392452401=P170" embedded=False id="form" width="100%" height="900px" frameborder="0" marginheight="5%" marginwidth="2%">Loading…</iframe>
</body>
<script>
    
    
            var map_75fb3774c8bbaa6194d248260d0a9423 = L.map(
                "map_75fb3774c8bbaa6194d248260d0a9423",
                {
                    center: [52.4999149930421, -1.98630888015032],
                    crs: L.CRS.EPSG3857,
                    zoom: 18,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var tile_layer_cfe76d489b87ed202f70722adab5190c = L.tileLayer(
                "https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png",
                {"attribution": "Data by \u0026copy; \u003ca href=\"http://openstreetmap.org\"\u003eOpenStreetMap\u003c/a\u003e, under \u003ca href=\"http://www.openstreetmap.org/copyright\"\u003eODbL\u003c/a\u003e.", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_75fb3774c8bbaa6194d248260d0a9423);
        
    
            var tile_layer_276225f7e56dc6e7bcda46796d387a08 = L.tileLayer(
                "https://stamen-tiles-{s}.a.ssl.fastly.net/terrain/{z}/{x}/{y}.jpg",
                {"attribution": "Map tiles by \u003ca href=\"http://stamen.com\"\u003eStamen Design\u003c/a\u003e, under \u003ca href=\"http://creativecommons.org/licenses/by/3.0\"\u003eCC BY 3.0\u003c/a\u003e. Data by \u0026copy; \u003ca href=\"http://openstreetmap.org\"\u003eOpenStreetMap\u003c/a\u003e, under \u003ca href=\"http://creativecommons.org/licenses/by-sa/3.0\"\u003eCC BY SA\u003c/a\u003e.", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_75fb3774c8bbaa6194d248260d0a9423);
        
    
            var marker_922fa47242be5c71084030dc436d2ad0 = L.marker(
                [52.4999149930421, -1.98630888015032],
                {}
            ).addTo(map_75fb3774c8bbaa6194d248260d0a9423);
        
    
        var custom_icon_18e48fd91ffb0b534137fb06c677ab49 = L.icon({"iconSize": [12, 12], "iconUrl": "https://www.zonescan.net/assets/markers/dot_red_med.png"});
        marker_922fa47242be5c71084030dc436d2ad0.setIcon(custom_icon_18e48fd91ffb0b534137fb06c677ab49);
        
</script>
</html>
