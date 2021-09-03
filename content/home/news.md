---

widget: slider
headless: true  # This file represents a page section.

# ... Put Your Section Options Here (section position etc.) ...
weight: 30

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: false

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 400px


item:
  - title: Mind Mappings Open Source Release Available!
    content: 'Mind Mappings is a first-of-its-kind tool for mapping space search for hardware accelerators using gradient descent. '
    # Choose `center`, `left`, or `right` alignment.
    align: center
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    overlay_color: '#333'  # An HTML color value.
    overlay_img: bubbles.jpg  # Image path relative to your `static/media/` folder
    overlay_filter: 0.5  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: Open Source Release
    cta_url: 'https://github.com/kartik-hegde/mindmappings'
    cta_icon_pack: fas
    cta_icon: graduation-cap
  - title: I will be at NVIDIA Research during Summer 2021!
    align: center
    overlay_color: '#333'
    overlay_img: ''
    overlay_filter: 0.5
  - title: ExTensor Accepted to MICRO 2019!
    content: 'ExTensor is an accelerator for Sparse Tensor Algebra'
    align: center
    overlay_color: '#333'
    overlay_img: ''
    overlay_filter: 0.5
  - title: Received the Facebook Ph.D. Fellowship!
    content: 'Hardware and Software Infrastructure for Machine Learning group'
    align: center
    overlay_color: '#333'
    overlay_img: ''
    overlay_filter: 0.5

---