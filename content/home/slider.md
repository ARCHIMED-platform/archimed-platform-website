+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = false

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = ""

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "ARCHIMED"
  content = "The modelling platform for 3D plants :deciduous_tree:"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "coffee_animation.gif"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # # Call to action button (optional).
  # #   Activate the button by specifying a URL and button label below.
  # #   Deactivate by commenting out parameters, prefixing lines with `#`.
  # cta_label = "Get Started"
  # cta_url = "https://archimed-platform.github.io/archimed-phys-user-doc/"
  # cta_icon_pack = "fas"
  # cta_icon = "graduation-cap"

[[item]]
  title = "ARCHIMED-φ"
  content = "Biophysics modeling of 3D scenes."
  align = "center"
  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Get Started"
  cta_url = "https://archimed-platform.github.io/archimed-phys-user-doc/"
  cta_icon_pack = "fas"
  cta_icon = "graduation-cap"
  overlay_color = "#555"  # An HTML color value.
  overlay_img = "palm2.png"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.2  # Darken the image. Value in range 0-1.

[[item]]
  title = "ARCHIMED-γ"
  subtitle = "Test"
  content = "Growth, yield and development modeling of 3D plants."
  align = "center"
  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Coming soon"
  cta_url = "#"
  cta_icon_pack = "fas"
  cta_icon = "hammer"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "growing-tree-svg-animation-recut.gif"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
+++
