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
  text: 'Find out more about my interests, background and experience.'
  
widget2:
  title: "Research"
  url: '/research/'
  image: research.jpg  
  text: 'View my current and previous research projects.'

widget3:
  title: "Analytical Web Apps"
  image: software.jpg  
  url: '/research/'
  text: 'View analytical web applications that I developed as part of my
  research. Coming soon.'


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
  url: https://www.dropbox.com/s/vo0q9kjsycom69w/JCizel%20--%20Curriculum%20Vitae.pdf?dl=0
  text: Download my Curriculum Vitae›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<!-- <div id="videoModal" class="reveal-modal large" data-reveal=""> -->
<!--   <div class="flex-video widescreen vimeo" style="display: block;"> -->
<!--     <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe> -->
<!--   </div> -->
<!--   <a class="close-reveal-modal">&#215;</a> -->
<!-- </div> -->
