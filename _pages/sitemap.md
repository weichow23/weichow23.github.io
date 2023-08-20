---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}



Where am I now

<iframe width="80%" frameborder="0" allowfullscreen src="https://www.openstreetmap.org/export/embed.html?bbox=114.0894,22.2020,114.2930,22.3086&layer=mapnik"></iframe>






who have visit the web

<script type="text/javascript">
  fetch('https://api.ipstack.com/check?access_key=2c71855d088846151aee42fe8ca1d536')
    .then(response => response.json())
    .then(data => {
      console.log(data);

      // 获取经纬度
      const latitude = data.latitude;
      const longitude = data.longitude;

      // 设置边界框，使得访问者的位置处于地图中心
      const bboxLeft = longitude - 0.1;
      const bboxBottom = latitude - 0.1;
      const bboxRight = longitude + 0.1;
      const bboxTop = latitude + 0.1;
    
      // 使用获取到的经纬度更新 OpenStreetMap iframe 的 src 属性
      const iframeSrc = `https://www.openstreetmap.org/export/embed.html?bbox=${bboxLeft},${bboxBottom},${bboxRight},${bboxTop}&layer=mapnik&mlat=${latitude}&mlon=${longitude}`;
      document.getElementById("mapIframe").src = iframeSrc;

    })
    .catch(error => console.error('Error fetching IP data:', error));
</script>

<iframe id="mapIframe" width="80%" frameborder="0" allowfullscreen src="https://www.openstreetmap.org/export/embed.html?bbox=104.0894,22.2020,104.2930,22.3086&layer=mapnik"></iframe>


[查看地图](location.html)


<script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=viAfb_n-Z7dDyvH8p34mNNNqfc9VJ0srCPPTncTiQGA"></script>

<a href="https://clustrmaps.com/site/1bw4s"  title="Visit tracker"><img src="//www.clustrmaps.com/map_v2.png?d=viAfb_n-Z7dDyvH8p34mNNNqfc9VJ0srCPPTncTiQGA&cl=ffffff" /></a>