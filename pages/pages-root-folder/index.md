---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: nycbnw.jpg

widget1:
  title: "Introduction"
  url: '/intro/'
  image: personalphoto2.jpg
  <!-- image: widget-1-302x182.jpg -->
  text: 'Find out more about my interests, background, and research.'
  
widget2:
  title: "Research"
  url: '/research/'
  image: research.jpg  
  text: 'View my current and previous research projects.'

widget3:
  title: "Analytical Web Apps"
  image: software.jpg  
  url: '/software/webapps/'
  text: 'View analytical web applications that I developed as part of my research.'


#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#

callforaction:
  url: https://tinyletter.com/feeling-responsive
  text: Download my Curriculum Vitae and Job Market Paper ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
