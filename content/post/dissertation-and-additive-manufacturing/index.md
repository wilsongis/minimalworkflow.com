---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Barriers and Issues in Additive Manufacturing"
subtitle: "A White Paper"
summary: "A brief summary of issues I am trying to identify a a dissertation topic."
authors: [wilsonm]
tags: [additive manufacturing]
categories: [dissertation]
date: 2019-07-28T20:43:25-0500
lastmod: 2019-07-28T20:43:34-0500
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "John Adams Library"
  focal_point: "smart"
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [my-dissertation]
---

# Barriers and Issues in Additive Manufacturing

In reviewing various literature regarding additive manufacturing, there are several issues regarding wide-spread adoption in the aerospace, automotive and biomedical industries. The key issues can be summarized as making, material, metrology, and market (Tofail et al., 2018).

Of particular interest is metrology. According to (Muelaner, 2017), metrology is defined as the science of measurement. The literature refers to metrology as the various measurements required for quality control and assurance (Townsend, Senin, Blunt, Leach, & Taylor, 2016).

At present, the metrology processes can be classified as two types, in situ and off line. In situ measurements are those collected and analyzed in the build chamber. Off line measurements are those that are collected in the chamber and analyzed off site. Generally, in situ analysis is non-destructive but is not as thorough as the more comprehensive and destructive off site measurements (Tofail et al., 2018). Basically in situ is instant but limited and off site is slow, destructive, and comprehensive.

According to the literature, the metrology issues that are barriers to widespread adoption (Tofail et al., 2018) can be summarized as:

• Need for real time in line quality control and assurance
• Process monitoring and control towards optimization
• High level of customization of the techniques for in-situ measurements
• High accuracy and measurement processing speeds

Based on the outlined issues, I believe that there are two possible paths for my dissertation, machine learning and image rectification. In the current process, imagery is captured in situ and analyzed off site. Machine learning, more specifically, image recognition, offered a possible path to quick, near real-time analysis. A project would include the development of a training datasets, ML model selection, model tuning, and experimentation. A more expansive and detailed proposal can be developed if data is available.

A second possible project would be based on the GIS process of image rectification. In GIS, image rectification is the process of manipulating aerial or satellite imagery to accurately represent the Earth[’s surface. Basically, a pixel on an image represents a discrete point (coordinate) on the Earth. I believe that is might be interesting to look at the possibility of using similar techniques to capture images of the additive build process and be able to take measurements as the item is being printed. The experimental part of the project would be the development of a camera configuration and rectification process to take the level of accurate images needed for additive manufacturing. This idea is very speculative. I do believe that I could accomplish much of the data collection needed with the prosumer 3D printers that I have access to on a daily basis. Cameras maybe an issue, although I would be tempted to try a mobile device as a camera system.

Of the two ideas, I am more drawn to the first. I feel that this project could have concrete implications for additive manufacturing. Although interesting, I believe the second project is entirely speculative on my part.

References:

Muelaner, J. (2017). An Introduction to Metrology and Quality in Manufacturing. https://new.engineering.com/story/an-introduction-to-metrology-and-quality-in-manufacturing.

Tofail, S. A. M., Koumoulos, E. P., Bandyopadhyay, A., Bose, S., O’Donoghue, L., & Charitidis, C. (2018). Additive manufacturing: scientific and technological challenges, market uptake and opportunities. Materials Today, 21(1), 22-37

Townsend, A., Senin, N., Blunt, L., Leach, R. K., & Taylor, J. S. (2016). Surface texture metrology for metal additive manufacturing: a review. Precision Engineering, 46, 34-47.
