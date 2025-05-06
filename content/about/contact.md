---
# An instance of the Contact widget.
# Documentation: https://docs.hugoblox.com/getting-started/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: Get in touch
subtitle:

content:
  autolink: true
  form:
    provider: formspree
    formspree:
      id: manoozdp  # Este es el ID que ya tienes
    netlify:
      captcha: false

design:
  columns: '1'
---
