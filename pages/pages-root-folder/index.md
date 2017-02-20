---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: headerhome.jpg
widget1:
  title: "About Roya"
  url: '/blog'
  image: royabio.jpg
  text: 'Roya Sabeti is an Evangelist for female entrepreneurs, Photographer, DIY vintage lover, & Contest Queen. Her mission is to empower women in entrepreneurship by providing a place to share their stories, and advance their careers and companies. She is happiest when eating, creating something from nothing, or sharing experiences with others. She currently lives in San Francisco and when she’s not planning her next event supporting entrepreneurial women or scheming about how to win the latest contest, she can be found planning her next photoshoot.'
widget2:
  title: "Portfolio"
  url: '/portfolio'
  image: gallerypreview.jpg
  text: 'Selected photography and portrait work. This is updated often so check back for more later.'
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
  text: Get occasional updates from Roya ›
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
