+++
# Date this page was created.
date = "2017-06-02"

# Project title.
title = "GestBall/GestLib"

# Project summary to display on homepage.
summary = "GestBall was my Final year undergrad project. We made a 2D sidescroller where you play as a Ball and you perform actions using hand gestures"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "gestballthumb.jpeg"

# Tags: can be used for filtering projects.
tags = ["prototypes"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "gestballthumb.jpeg"
caption = ""

+++

GestLib was a OpenCV based implementation of hand tracking with pose recognition.We tested with a total of 4 poses.

To test the GestLib we also made a game called GestBall, where certain poses like 1-Finger,2-Finger triggered certain actions on the player character which was a bouncing ball.
Rendering was done using a spriterenderer on the DirectX API.

Here are some screenshots from the project:

Break-out game using GestLib. The player would use his hand as a paddle.
![GestLib](/img/gestball1.jpg)

GestBall uses gestures to control the ball. 
<br>
* 1-Finger pose made the ball jump.
<br>
* Closed hand pose made the ball move.
<br>
* Open hand pose made the ball stop.

The player had to use the gestures to evade the shrapenel.
![GestLib](/img/GestBall2.png)
![GestLib](/img/GestBall3.png)
![GestLib](/img/GestBall4.png)
