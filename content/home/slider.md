+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = false  # Activate this widget? true/false
weight = 100  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = "5000"

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "300px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "<sub>Tokyo Bay</sub>"
  content = "Source: [ESA](http://www.esa.int/spaceinimages/Images/2018/03/Tokyo)"
  align = "left"

  overlay_color = "#000000"  # An HTML color value.
  overlay_img = "headers/Tokyo.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.1  # Darken the image. Value in range 0-1.

[[item]]
  title = "<sub>Easter Island</sub>"
  content = "Source: [ESA](http://www.esa.int/spaceinimages/Images/2019/04/Easter_Island)"
  align = "right"

  overlay_color = "#000000"  # An HTML color value.
  overlay_img = "headers/Easter_Island.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.1  # Darken the image. Value in range 0-1.

[[item]]
  title = "<sub>Snow-covered Etna</sub>"
  content = "Source: [ESA](http://www.esa.int/spaceinimages/Images/2018/11/Snow-covered_Etna)"

  overlay_color = "#000000"  # An HTML color value.
  overlay_img = "headers/etna.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.3  # Darken the image. Value in range 0-1.
+++
