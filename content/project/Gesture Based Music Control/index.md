---
title: Gesture Based Music Control
summary: Using Convolutional Neual Networks to control music with hand gestures.
tags:
  - Machine Learning
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    url: https://github.com/anuj1501/Gesture-music-controller
url_code: 'https://github.com/anuj1501/Gesture-music-controller'
# url_pdf: 'https://drive.google.com/file/d/10E6-9GZ60cl4KyA1aFWeJqnAg1HtH2Fq/view?usp=sharing'
# url_slides: ''
# url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

An application that controls music player based on a set of predefined static hand gestures which is made customizable for the user to add as per his or her choice. Use the Convolutional Neural Networks to recognize the real time gesture and direct the control using the Pygame library. Created a functionality which can help a person create his own custom dataset, making the application more generalized
The model has been trained on GPU power so as to improve the overall training time. Tried to improve the accuracy of the model using few object localization techniques like using the palm detector XML file, or using background cancellation techniques. Currently working on the inclusion of real-time detection using 3D CNNs and LSTMs and add more gestures to the dataset to make the overall performance user friendly.
Worked on deploying the model using the Flask Web API, to render the video screen on a webpage, only shortcoming was the image quality getting deteriorated, yet the overall performance was quite satisfiable. Salient features include playing the playlist on loop and if no gesture is done, the music either wont start or it wont be played.
