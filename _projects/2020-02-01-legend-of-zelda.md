---
title: "Customized Legend of Zelda"
collection: projects
permalink: /projects/2020-02-01-legend-of-zelda
start_date: 2020-01-01
end_date: 2020-02-01
location: "Ann Arbor, Michigan"
---

Test for unity game

<html lang="en-us">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <title>Unity WebGL Player | p1</title>
    <link rel="shortcut icon" href="../_pages/legend-of-zelda/TemplateData/favicon.ico">
    <link rel="stylesheet" href="../_pages/legend-of-zelda/TemplateData/style.css">
    <script src="../_pages/legend-of-zelda/TemplateData/UnityProgress.js"></script>
    <script src="../_pages/legend-of-zelda/Build/UnityLoader.js"></script>
    <script>
      var unityInstance = UnityLoader.instantiate("unityContainer", "Build/p1-webgl.json", {onProgress: UnityProgress});
    </script>
  </head>
  <body>
    <div class="webgl-content">
      <div id="unityContainer" style="width: 1025px; height: 835px"></div>
      <div class="footer">
        <div class="webgl-logo"></div>
        <div class="fullscreen" onclick="unityInstance.SetFullscreen(1)"></div>
        <div class="title">p1</div>
      </div>
    </div>
  </body>
</html>
