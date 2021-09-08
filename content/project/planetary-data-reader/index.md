---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Planetary Data Reader"
summary: "NASA PDART project to create a unified reader for all PDS data"
authors: []
tags: [Co-I]
categories: []
date: 2021-09-07T23:08:18-06:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/MillionConcepts/pdr"
url_pdf: "https://www.hou.usra.edu/meetings/planetdata2021/pdf/7096.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
We are developing the Planetary
Data Reader (pdr), an open-source, Python-based tool
for the ingestion of planetary observational data into
planetary science workflows. This project seeks to
solve a well-known pain point for planetary data users:
simply figuring out how to read the data. This is a
particular problem for data archived under the Version
3 standards of the Planetary Data System (PDS); the
PDS is in the process of migrating archives to the
stricter PDS4 standard, but the timeline is uncertain.
pdr provides a stopgap solution and future-proofs
research workflows while also supplementing the
migration effort.
The software is currently available in an alpha
stage with functional support for a large fraction of
PDS3-compliant image and table data, as well as all
PDS4-compliant data. We are actively using it on a
number of current and recently completed projects and
are ready to accept more users and community
feedback.
I am a funded Co-I in this project.
