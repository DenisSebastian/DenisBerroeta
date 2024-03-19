---
title: "Poster: Simposio Internacional de Clima y la Resiliencia"

event: Simposio Internacional de Clima y la Resiliencia
event_url: https://simposio.cr2.cl/

location: NOVOTEL
address:
  street: 6 Norte 745
  city: Viña del Mar
  region: Valparaíso
  # postcode: '94305'
  country: CL

summary: SAR Change Detection with CNN
abstract: 'In the context of climate change, peatlands emerge as critical ecosystems due to their capacity to store carbon. To protect and monitor these ecosystems, synthetic aperture radar (SAR) satellite data are used due to their ability to cover large areas and operate in various atmospheric conditions. In this thesis, an unsupervised approach based on convolutional neural networks is proposed to detect changes in the territory. This approach allows identifying areas potentially affected by natural or human factors. The results obtained show that this method is more efficient and accurate than conventional change detection methods. As a conclusion, the feasibility of detecting changes even in adverse atmospheric conditions using SAR images and Deep Learning techniques is highlighted. These findings represent a significant contribution to the monitoring and conservation of peatlands, and contribute to the understanding and mitigation of climate change.'



# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-09-06T13:00:00Z'
date_end: '2023-09-07T15:00:00Z'
all_day: true

# Schedule page publish date (NOT talk date).
# publishDate: '2017-01-01T00:00:00Z'

authors: [admin]
tags: [SAR, Remote Sensing]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Solution'
  focal_point: Right

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/denis_berr
  - icon: linkedin
    icon_pack: fab
    link: https://www.linkedin.com/in/denis-berroeta
url_code: ''
url_pdf: files/poster_dbg_seminario.pdf
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
#   - example
---

### Descripción del Poster:

In today's world, the degradation of natural systems represents one of the greatest challenges, and their conservation is crucial to protect them from human intervention. Given the diversity and climatic adversity of the geographical areas under study, Synthetic Aperture Radar (SAR) images will be used.

In Chile, the Superintendencia del Medio Ambiente (SMA) is responsible for ensuring compliance with environmental regulations. It faces a major challenge in trying to monitor all protected natural ecosystems, such as the peatlands in Chiloé.

The proposed solution involves the use of satellite imagery. SAR satellites can provide images during the day and night, regardless of weather conditions.

<img src="Sentinel_1.jpeg" alt = "Sentinel 1. Synthetic Aperture Radar (SAR)" width="200" height="200" />


Since a monitoring system requires constantly capturing information and contrasting it with a historical record, computational efficiency and expert supervision are needed. Therefore, an unsupervised change detection algorithm is chosen in the first stage.

![Solution Diagram](solution.png)

It is expected that, at the end of the first stage, a change detection system will be available for SAR satellite images using unsupervised convolutional neural networks. The resulting images (changes) will be evaluated using similarity or intersection metrics with real images of human intervention in natural ecosystems (Ground Truth). In addition, the results will be compared with other conventional change detection techniques.
