---
title: University Rover Challenge
summary: |2-
  Lead engineer of autonomous navigation for the BYU Mars Rover Team: the only team to complete the final, fully autonomous navigation portion of task. 
  
  I was a primary operator of the rover in the competition and throughout development, and I wrote the navigation and sensing software that guided the rover to the goal markers.
tags:
- Robotics
date: "2018-06-02"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Our rover
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Lead engineer of autonomous navigation for the BYU Mars Rover Team, a team of 23 individuals.

Our rover successfully traversed the final, fully autonomous stage of the task, which no other rover of the 35 international teams was able to do.

I was a primary operator of the rover in the competition and throughout development, and I wrote the navigation and sensing software that guided the rover to the goal markers. I wrote the code for nearly all UI involved in rover operation, including the networking backend.

Programmed a potential field algorithm for obstacle detection and avoidance using a laser scanner which was successful during the competition.

I trained a deep neural network to detect goal markers and adapted it for real-time inference on the rover. I took the pictures which became the training dataset and I got inference working on an Nvidia Jetson TX2. It achieved nearly perfect accuracy in the competition.

Implemented GPS waypoint following and vision-based controllers which ran on the rover to fulfill the requirement of arriving within 2-meter radius of the goal marker.

## Video
See this video showing the final detection, approach, and recognition of arrival for the goal marker during the purely autonomous stage of the task, which no other rover acheived.

{{< youtube cOX-QPgbB50 >}}
