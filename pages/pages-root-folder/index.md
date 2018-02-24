---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
widget1:
  title: "Call Ahead"
  text: '<b>Telephone:</b><br/> 856-596-8990<br/> 856-596-8895<br/>'
widget2:
  title: "Open 7 Days a Week"
  text: '<b>Monday - Thursday:</b> 11:00 am - 9:30 pm<br/><b>Friday & Saturday:</b> 11:00 am - 10:30 pm<br/>
  <b>Sunday:</b> 12:00 pm - 9:00 pm'
widget3:
  title: "By the Shops at Elmwood"
  text: '795 Rt. 70 Suite B<br/>Marlton, NJ 08053'
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
  text: Inform me about new updates and features ›
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
