---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "WASA"
summary: "Web API Annotations with Schema.org Actions. The specification developed part of my PhD research."
authors: ["admin"]
tags: ["research"]
categories: []
date: 2020-10-16T17:35:47Z

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
links:
- name: Go to the specification
  url: http://wasa.cc
  icon_pack: fas
  icon: link

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

The schema.org vocabulary is a de facto industrial standard for creating semantically annotated data. The vocabulary with its actions subset that allows to describe not only entities on the web, but also actions that can be taken on them. The Web Service Annotation with Schema.org (WASA) language puts schema.org actions into a Web API perspective by restricting and extending it with the help of the domain specification process for the creation of WASA APIs.

The WASA language sees Web APIs as a collection of actions that can be taken on a graph resources. These actions can be linked explicitly, allowing clients to achieve certain goals without hardcoding the orchestration of these actions (i.e. order of action invocation). As a domain model to describe input and output parameters, we use domain-specific patterns that restrict and extend the schema.org vocabulary. An API publisher can define constraints over the input and output of an action via these pattern that are defined with SHACL shapes.