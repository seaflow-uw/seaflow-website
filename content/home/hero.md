+++
# Hero widget.
widget = "hero"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10  # Order that this section will appear.

title = "Download SeaFlow data v1"

# Hero image (optional). Enter filename of an image in the `static/img/` folder.
# hero_media = "seaFlow-logo.png"

[cta]
  url = "https://doi.org/10.5281/zenodo.2678021"
  label = "Zenodo"
  icon_pack = "fas"
  icon = "download"

[cta_alt]
  url = "https://simonscmap.com/"
  label = "available at Simons CMAP"

[cta_note]
  label = "The data set consists of SeaFlow-based cell abundance, cell size (equivalent spherical diameter), cellular carbon content and total carbon biomass for picophytoplankton populations, namely the cyanobacteria Prochlorococcus, Synechococcus and small-sized Crocosphaera (2-5 um), and picoeukayotes phytoplankton and nanophytoplankton (2-5 μm ESD), collected during oceanographic cruises since 2010 in the North Pacific Ocean. See data description at [Scientifc Data: Nature Publishing Group](https://doi.org/10.1038/s41597-019-0292-2) for more information."

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "grey"
  
  # Background gradient.
  gradient_start = "#585858"
  gradient_end = "#848484"


  # Background image.
  # image = "SeaFlowAnalysis-logo.png"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  image_position = "center"  # Options include `left`, `center` (default), or `right`.
  image_parallax = false  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = true

# Call to action links (optional).
#   Display link(s) by specifying a URL and label below. Icon is optional for `[cta]`.
#   Remove a link/note by deleting a cta/note block.

# Note. An optional note to show underneath the links.
+++