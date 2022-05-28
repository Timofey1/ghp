---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Face Recognition"
summary: "Face Recognition using mtcnn detection and facenet model"
authors: [admin]
tags: [face recognition]
categories: [cv]
date: 2022-05-28T18:08:29+03:00

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
Clone this repo : [Face Recognition demo github page](https://github.com/Timofey1/faceRecognitionDemo)

# Face Recognition Demo uses
 - facenet(trained on vggface2 dataset)
 - MTCNN face detector
 - mongoDB for storing facial embeddings
 - spotify annoy for indexing faces and finding simular faces 
 - Flask framework + Flask-RESTful for REST API

### Installation and startup
    pip install -r requirements.txt
### Run
    python app.py 
###### or
    flask run 

### Options
    - Detector only
    - Compare two loaded faces
    - Add/Find face in DataBase (install mongoDB first)