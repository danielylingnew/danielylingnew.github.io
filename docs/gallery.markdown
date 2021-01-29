---
layout: page
title: Gallery
permalink: /gallery
images:
  - image_path: /images/sheldonwhitehouse.jpg
    title: With Senator Sheldon Whitehouse.
  - image_path: /images/jackreed.jpeg
    title: With Senator Jack Reed.
  - image_path: /images/senatorscybele.jpg
    title: Myself, Cybele Greenberg, Sheldon, and Jack. During the pres. scholar events in DC.
  - image_path: /images/senatorsparents.jpg
    title: Me, my lovely parents, and the two U.S. Senators representing Rhode Island.
  - image_path: /images/dudley1.jpg
    title: With Professor Dudley Herschbach in Los Angeles.
  - image_path: /images/dudley2.jpg
    title: After Dudley judged my project.
---


*A few selections in no particular order...*

<center>
  {% for image in page.images %}

			<img src="{{ image.image_path }}" alt="{{ image.title}}"/>
			<br>
			{{ image.title}}
			<br>
			<br>

  {% endfor %}
</center>



{% comment %}
<ul class="gallery">

</ul>
{% endcomment %}
