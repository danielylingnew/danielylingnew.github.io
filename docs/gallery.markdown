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
    title: Myself, Cybele Greenberg, Sen. Whitehouse, and Sen. Reed. During the pres. scholar events in DC.
  - image_path: /images/senatorsparents.jpg
    title: Me, my lovely parents, and the two U.S. Senators representing Rhode Island.
  - image_path: /images/dudley1.jpg
    title: With Professor Dudley Herschbach in Los Angeles.
  - image_path: /images/dudley2.jpg
    title: After Dudley judged my project.
  - image_path: /images/angusdeaton.jpeg
    title: On the day Professor Deaton won the Nobel Prize in Economics for his work on welfare and global poverty. He initially suggested a selfie. Cecilia Rouse behind us.
  - image_path: /images/sheldonsigned.jpeg
    title: Senator Sheldon Whitehouse
  - image_path: /images/jacksigned.jpeg
    title: Senator Jack Reed
  - image_path: /images/arneduncan.jpg
    title: Arne Duncan
  - image_path: /images/dadti.jpeg
    title: During parents weekend at Tiger Inn.
  - image_path: /images/dadoliverhart.jpeg
    title: This isn’t a photo of me, but it’s my Dad meeting Oliver Hart in Stockholm in 2016. Congrats to Professor Hart (for his contributions to contract theory)!
  - image_path: /images/cybele.jpg
    title: Representing Rhode Island at the Presidential Scholar ceremonies in Washington, D.C.
  - image_path: /images/parents.jpg
    title: Leaving the nest (and the last chance to wear my CPW shirt)
  - image_path: /images/ivyday.jpg
    title: Ivy Day ceremonies (East Greenwich, Rhode Island)
  - image_path: /images/speech.jpg
    title: Saying a few words at grad (East Greenwich, RI).
  - image_path: /images/elizabethrob.jpg
    title: Some good Block Island fun with Rob Kraft and Elizabeth Kerin.
  - image_path: /images/taylor.jpg
    title: No caption necessary (with Taylor Knoop).
  - image_path: /images/cybelejames.jpg
    title: Myself, Cybele Greenberg, James Lim in Washington, D.C.
  - image_path: /images/siemens.jpg
    title: Competing in the Siemens Competition (MIT).
  - image_path: /images/blackwatch.jpg
    title: Soccer teammates (BW Premier, New England).
  - image_path: /images/kosterlitz.jpg
    title: 'Final edits to Professor Kosterlitz’ Nobel lecture in Stockholm. Also not a picture of me. (Fun fact: My applied math research and Prof. Kosterlitz’ groundbreaking paper on two-dimensional phase transitions were both published in the Journal of Physics: Condensed Matter! His in 1972 and mine in 2013.)'
  - image_path: /images/familyholland.jpg
    title: With the family in Holland.
  - image_path: /images/familyholland2.jpg
    title: (Growling) with the family at (the?) Keukenhof.
  - image_path: /images/familyholland3.jpg
    title: Slightly less growl-y.
  - image_path: /images/zoo.jpg
    title: Early contemplations.
  - image_path: /images/zoo2.jpg
    title: Sharing is caring.
  - image_path: /images/townhall.jpg
    title: Town Hall in East Greenwich, Rhode Island (after winning the Rhode Island Science Fair).
  - image_path: /images/newport.jpg
    title: Mom and Dad in Newport, RI. Center is my brother, Oliver.
  - image_path: /images/doug.jpg
    title: With Prof. Douglas Osheroff in Los Angeles, behind us is J. Michael Bishop.
  - image_path: /images/isefshree.jpg
    title: Intel ISEF Awards Ceremony (with Shree Bose)
  - image_path: /images/posterboard.jpg
    title: '<a href="https://www.independentri.com/local/article_3c6a91d7-4cda-5152-a160-26bb648666ee.html">Photo by Michael Derr (The Independent)</a>'
  - image_path: /images/johnbtaylor.jpeg
    title: John B. Taylor and I at Reunions.
  - image_path: /images/jshs1.jpg
    title: National JSHS (3rd Place), San Diego, CA
  - image_path: /images/jshs2.jpg
    title: National JSHS (3rd Place), San Diego, CA
  - image_path: /images/ollie.jpeg
    title: My brother and I in New York.
  - image_path: /images/ollie2.jpg
    title: Soaking it all in (Leiden, Holland).
  - image_path: /images/toddler.jpg
    title: Getting used to life and such (East Greenwich, RI).
  - image_path: /images/baby.jpg
    title: Learning the basics.
---


*A few selections in no particular order...*

<center>
  {% for image in page.images %}

			<img src="{{ image.image_path }}"/>
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
