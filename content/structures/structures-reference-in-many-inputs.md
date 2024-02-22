---
_enabled_editors:
  - visual
  - content
_inputs:
  header_social_media:
    type: array
    label: Hero Image
    comment: Appears at the top of the page
    options:
      structures: _structures.links
      preview:
        icon: support_agent
  footer_affliate_links:
    type: array
    options:
      structures: _structures.links
      preview:
        icon: shopping_bag
  logo:
    type: image
_structures:
  links:
    values:
      - value:
          url:
          logo:
          text:
header_social_media:
  - url:
    logo:
    text:
footer_affliate_links: []
---
