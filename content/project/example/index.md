---
title: Formal Verification Tool
summary: A tool using Z3 symbolic execution to check code security.
tags:
- Formal Verification
date: "2021-01-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/KentonJack
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Use Z3py binding to take in function parameters, analyze AST for symbolic execution and produce the function return value range for preventing math overflow or underflow. Still work in progress.
