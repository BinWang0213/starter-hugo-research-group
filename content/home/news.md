---
widget: pages
headless: true  # This file represents a page section.

# Activate this widget? true/false
active: true

# ... Put Your Section Options Here (title etc.) ...
title: News
subtitle: ''

# Position of this section on the page
weight: 40

content:
  # Filter content to display
  filters:
    # The folders to display content from
    folders:
      - event
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    exclude_featured: false
    exclude_future: false
    exclude_past: false
  # Choose how many pages you would like to display (0 = all pages)
  count: 3
  # Choose how many pages you would like to offset by
  # Useful if you wish to show the first item in the Featured widget
  offset: 0
  # Field to sort by, such as Date or Title
  sort_by: 'Date'
  sort_ascending: false
design:
  # Choose a listing view, list, compact, card
  view: list
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'

  spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
    padding: ["20px", "20px", "10px", "20px"]
  
  font_size_min: 1.0
  font_size_max: 0.9
---