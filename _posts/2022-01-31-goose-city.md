---
title: "Goose City"
date: 2019-04-18T15:34:30-04:00
unity_dir: GooseCity
categories:
  - Blog
tags:
  - Student Project
---
Made by Tyler Kitts, Dora Song, Elizabeth Childs and Alex Richman over 3 weeks.
---
<script src="{{ site.baseurl }}/assets/unity/GooseCity/TemplateData/UnityProgress.js"></script>  
<script src="{{ site.baseurl }}/assets/unity/GooseCity/Build/UnityLoader.js"></script>
<script>
  var gameInstance = UnityLoader.instantiate("gameContainer", "{{ site.baseurl }}/assets/unity/GooseCity/Build/goose web build.json",{onProgress: UnityProgress});  
</script>
<div class="webgl-content">
  <div id="gameContainer" style="width: 960px; height: 600px"></div>
</div>
