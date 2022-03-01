---
title: "Escape Sequence"
date: 2019-04-18T15:34:30-04:00
tags:
  - Student Project
---
Made by Ngou Yin Yip, Adrian Ly, Tyler Kitts over 6 weeks.
---
<script src="{{ site.baseurl }}/assets/unity/EscapeSequence/TemplateData/UnityProgress.js"></script>  
<script src="{{ site.baseurl }}/assets/unity/EscapeSequence/Build/UnityLoader.js"></script>
<script>
  var gameInstance = UnityLoader.instantiate("gameContainer", "{{ site.baseurl }}/assets/unity/EscapeSequence/Build/EscapeSequence.json",{onProgress: UnityProgress});  
</script>
<div class="webgl-content">
  <div id="gameContainer" style="width: 960px; height: 600px"></div>
</div>