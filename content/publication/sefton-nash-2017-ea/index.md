---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Diviner lunar radiometer gridded brightness temperatures from geodesic binning
  of modeled fields of view
subtitle: ''
summary: ''
authors:
- E Sefton-Nash
- J-P Williams
- B T Greenhagen
- K-M Aye
- D A Paige
tags: [Effective field of view, Diviner, Remote sensing, Planetary mapping]
categories: []
date: '2017-12-01'
lastmod: 2021-09-07T09:52:49-06:00
featured: false
draft: false

url_pdf: https://paperpile.com/shared/mG2imJ
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
projects: [diviner]
publishDate: '2021-09-07T15:52:48.919201Z'
publication_types:
- '2'
abstract: An approach is presented to efficiently produce high quality gridded data
  records from the large, global point-based dataset returned by the Diviner Lunar
  Radiometer Experiment aboard NASA's Lunar Reconnaissance Orbiter. The need to minimize
  data volume and processing time in production of science-ready map products is increasingly
  important with the growth in data volume of planetary datasets. Diviner makes on
  average >1400 observations per second of radiance that is reflected and emitted
  from the lunar surface, using 189 detectors divided into 9 spectral channels. Data
  management and processing bottlenecks are amplified by modeling every observation
  as a probability distribution function over the field of view, which can increase
  the required processing time by 2--3 orders of magnitude. Geometric corrections,
  such as projection of data points onto a digital elevation model, are numerically
  intensive and therefore it is desirable to perform them only once. Our approach
  reduces bottlenecks through parallel binning and efficient storage of a pre-processed
  database of observations. Database construction is via subdivision of a geodesic
  icosahedral grid, with a spatial resolution that can be tailored to suit the field
  of view of the observing instrument. Global geodesic grids with high spatial resolution
  are normally impractically memory intensive. We therefore demonstrate a minimum
  storage and highly parallel method to bin very large numbers of data points onto
  such a grid. A database of the pre-processed and binned points is then used for
  production of mapped data products that is significantly faster than if unprocessed
  points were used. We explore quality controls in the production of gridded data
  records by conditional interpolation, allowed only where data density is sufficient.
  The resultant effects on the spatial continuity and uncertainty in maps of lunar
  brightness temperatures is illustrated. We identify four binning regimes based on
  trades between the spatial resolution of the grid, the size of the FOV and the on-target
  spacing of observations. Our approach may be applicable and beneficial for many
  existing and future point-based planetary datasets.
publication: '*Icarus*'
doi: 10.1016/j.icarus.2017.04.007
---
