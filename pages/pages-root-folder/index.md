---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: Raum_sw.jpg
widget1:
  title: "Konzept"
  url: 'http://hundertneun.net/konzept/'
  image: Kuche_sw_320x180.jpg
  text: 'Das Konzept der 109 mit Infos zu <em>Struktur, Raumgestaltung, Prinzipien, Öffnungskonzept und dem Finanzierungsplan</em>'
widget2:
  title: "Media"
  url: 'http://hundertneun.net/media/'
  text: 'Radiobeiträge, Videos, Flyer, Sticker und viel mehr rundum von <em>Fuck! Die 109 ist weg</em>'
  video: '<a href="#" data-reveal-id="videoModal"><img src="https://raw.githubusercontent.com/reclaim109/reclaim109-website/master/images/video_thumb.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Socialmedia"
  url: 'https://facebook.com/politischesWohnzimmer'
  image: hundertneun_fenster_klein_320x180.jpg
  text: 'Folge <em>Fuck! Die 109 ist weg</em> auf Facebook um Workshops, Ausstellungen, Hörbeiträge und andere Neugkeiten nicht zu verpassen'

permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen youtube" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/J-5FgVnZhdQ" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
