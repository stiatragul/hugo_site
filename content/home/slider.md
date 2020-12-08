+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 2  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "300px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Welcome!"
  content = "This is my new website!"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "header/gecko_head.jpg"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.2  # Darken the image. Value in range 0-1.

[[item]]
  title = "Blog"
  content = "All my blog posts are now hosted on this website"
  align = "center"  # Choose `center`, `left`, or `right`.
   cta_label = "Read here"
  cta_url = "https://sarintiatragul.com/post/"

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "header/gecko_head.jpg"   # Image path relative to your `static/media/` folder.
  overlay_filter = 0.2  # Darken the image. Value in range 0-1.


  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.

 # cta_url = "https://sourcethemes.com/academic/"
 # cta_icon_pack = "fas"
 # cta_icon = "graduation-cap"

#[[item]]
#  title = "Left"
#  content = "I am left aligned :smile:"
#  align = "left"

#  overlay_color = "#555"  # An HTML color value.
#  overlay_img = ""  # Image path relative to your `static/media/` folder.
#  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

#[[item]]
#  title = "Right"
#  content = "I am right aligned :smile:"
#  align = "right"

#  overlay_color = "#333"  # An HTML color value.
#  overlay_img = ""  # Image path relative to your `static/media/` folder.
#  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
+++