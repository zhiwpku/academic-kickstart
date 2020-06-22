---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "ProcData: An R package for process data analysis"
authors: ["Xueying Tang", "Susu Zhang", "Zhi Wang", "Jingchen Liu", "Zhiliang Ying"]
date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-21"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Statistical Software"
publication_short: ""

abstract: "Process data refer to data recorded in the log files of computer-based items. These data, represented as timestamped action sequences, keep track of respondents’ response processes of solving the items. Process data analysis aims at enhancing educational as- sessment accuracy and serving other assessment purposes by utilizing the rich information contained in response processes. The R package ProcData presented in this article is de- signed to provide tools for processing, describing, and analyzing process data. We define an S3 class ‘proc’ for organizing process data and extend generic methods summary and print for ‘proc’. Two feature extraction methods for process data are implemented in the package for compressing information in the irregular response processes into regular nu- meric vectors. ProcData also provides functions for fitting and making predictions from a neural-network-based sequence model. These functions call relevant functions in package keras for constructing and training neural networks. In addition, several response process generators and a real dataset of response processes of the climate control item in the 2012 Programme for International Student Assessment are included in the package."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: ["R package"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2006.05061.pdf
url_code: http://www.scientifichpc.com/processdata/download.html
url_dataset:
url_poster:
url_project:
url_slides:
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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
