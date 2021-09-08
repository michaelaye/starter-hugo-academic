---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'SpiceyPy: a Pythonic Wrapper for the SPICE Toolkit'
subtitle: ''
summary: ''
authors:
- Andrew Annex
- Ben Pearson
- Benoı̂t Seignovert
- Brian Carcich
- Helge Eichhorn
- Jesse Mapel
- Johan von Forstner
- Jonathan McAuliffe
- Jorge del Rio
- Kristin Berry
- K.-Michael Aye
- Marcel Stefko
- Miguel de Val-Borro
- Shankar Kulumani
- Shin-Ya Murakami
tags: [python, SPICE]
categories: [software]
date: '2020-01-01'
lastmod: 2021-09-07T09:52:47-06:00
featured: false
draft: false

url_pdf: https://paperpile.com/shared/ogrSjR
url_code: https://github.com/AndrewAnnex/SpiceyPy

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-09-07T15:52:47.404711Z'
publication_types:
- '2'
abstract: Operating in space necessitates quantifying the positions, velocities,    
  geometries, and other
  properties of spacecraft and planetary bodies through time. Scientists and engineers working
  with robotic planetary spacecraft missions use the Spacecraft, Planet, Instrument, Cameramatrix, Events (SPICE) Toolkit (Acton, Bachman, Semenov, & Wright, 2018) to help plan
  observations and to quantify the positions of planetary bodies and spacecraft through time.
  SPICE is developed at the Jet Propulsion Laboratory by NASA’s Navigation and Ancillary
  Information Facility (NAIF). Scientists also use SPICE to analyze data returned by these
  missions and to plan hypothetical orbital trajectories for future missions (Acton et al., 2018).
  For example, SPICE can calculate future occultations of planets relative to a camera on a
  rover or spacecraft. The NAIF provides SPICE in Fortran 77, C, and they also provide Matlab
  and IDL wrappers; however, as of 2014, they did not offer a Python interface. The growth
  of Python and movement away from proprietary interpreted languages (Burrell et al., 2018)
  motivated the development of SpiceyPy so that planetary scientists and engineers can use
  SPICE within Python.

publication: '*Journal of Open Source Software*'
doi: 10.21105/joss.02050
---
