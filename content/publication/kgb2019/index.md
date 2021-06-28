---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "RocketRML - A NodeJS Implementation of a
Use-Case Specific RML Mapper"
authors: ["Umutcan Simsek", "Elias Kärle", "Dieter Fensel"]
date: 2019-06-03T10:54:30Z
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-06-02T10:54:30Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Joint Proceedings of the 1st International Workshop on Knowledge Graph Building and 1st International Workshop on Large Scale RDF Analytics
co-located with 16th Extended Semantic Web Conference (ESWC 2019)"
publication_short: "KGB-LASCAR 2019@ESWC2019"

abstract: "The creation of Linked Data from raw data sources is, in
theory, no rocket science (pun intended). Depending on the nature of the
input and the mapping technology in use, it can become a quite tedious
task. For our work on mapping real-life touristic data to the schema.org
vocabulary, we used RML but soon encountered, that the existing Java
mapper implementations reached their limits and were not sufficient for
our use cases. In this system paper, we describe a new implementation of
an RML mapper. Written with the JavaScript-based NodeJS framework
it performs quite well for our use cases where we work with large XML
and JSON files. The performance testing and the execution of the RML
test cases have shown that the implementation has great potential to
perform heavy mapping tasks in reasonable time, but comes with some
limitations regarding JOINs, Named Graphs and inputs other than XML
and JSON - which is fine at the moment, due to the nature of the given
use cases."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: http://ceur-ws.org/Vol-2489/paper5.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides: https://sumutcan.github.io/kgb-workshop-presentation/#/
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["MindLab"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
