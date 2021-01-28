---
# this is your Home page
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: homeusingpage
title: Home
# you need this title here so that it shows up in the navigation bar (in header_pages in config.yml)
permalink: /
---



<!-- home photo style with hover text -->
<style>
.responsivevertical {
  max-height: 100%;
  width: auto;
  vertical-align: middle;
}
</style>



<!-- overlay title style -->
<style>
.homephotocontainer {
  position: relative;
  width: 100%;
}

.overlay {
  position: absolute;
  bottom: 0;
  background: rgb(0, 0, 0);
  background: rgba(0, 0, 0, 0.5); /* Black see-through */
  color: #f1f1f1;
  width: 100%;
  transition: .5s ease;
  opacity:0;
  color: white;
  font-size: 15px;
  padding: 0px;
  text-align: left;
}

.homephotocontainer:hover .overlay {
  opacity: 1;
}
</style>


<!-- overlay title
<div class="homephotocontainer">
  <img src="/assets/HomePhoto.jpg" alt="Avatar" class="image">
  <div class="overlay">
  <div style="padding:20px;">
  Intel ISEF Awards Ceremony (with Shree Bose)
  </div>
  </div>
</div>
-->


<!-- hover text method using overlay -->
<div class="homephotocontainer">

<img src="/assets/HomePhoto.jpg" title="Intel ISEF in Los Angeles (with Shree Bose)" class="responsivevertical" class="hover">

<div class="overlay">
<div style="padding:20px;">
Intel ISEF Awards Ceremony (with Shree Bose)
</div>
</div>

</div>



<!-- hover text original
<div id="hovertext">

<img src="/assets/HomePhoto.jpg" title="Intel ISEF in Los Angeles (with Shree Bose)" class="responsivevertical" class="hover">

<p class="hover text">Intel ISEF Awards Ceremony (with Shree Bose)</p>

</div>
-->











<!--
![HomePhoto](/assets/HomePhoto.jpg){:class="img-responsive"}
-->
