---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: crdc-cloud-shifted.jpg

widget1:
  title: "Open community"
  image: friends3.jpg
  text: 'IDC will host publicly available datasets, extensible with the annotations and analysis results
  contributed by the community, integrated with the data from other domains.'
widget2:
  title: "Metadata"
  image: catalog.jpg
  text: 'IDC will aim to implement best practices for managing metadata associated with the images to support
  integration and interoperability.'
widget3:
  title: "Open source"
  image: widget-github-303x182.jpg
  text: 'IDC will leverage the strengths of the existing open source projects, and will share all of the new
  software tools developed as open source.'
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
  url: https://forms.gle/kWpebkVphimJanv77
  text: Join Imaging Data Commons community ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true

preamble:
  text: We are the consortium building the National Cancer Institute (NCI) Imaging Data Commons (IDC) - a cloud-based resource within NCI Cancer Research Data Commons (CRDC) that connects researchers with cancer imaging datasets, resources for exploring those datasets and identifying relevant cohorts, and other components of CRDC that will host additional data types and support computation on the defined cohorts.
---
