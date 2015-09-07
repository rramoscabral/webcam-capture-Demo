# webcam-capture-Demo
Demo using Webcam Capture API from Bartosz Firyn (http://webcam-capture.sarxos.pl/)



##Webcam Capture API
This library allows you to use your build-in or external webcam directly from Java. It's designed to abstract commonly used camera features and support multiple capturing farmeworks.


##Webcam Capture API History
Sarxos (Bartosz Firyn) initially started working on Webcam Capture as a simple proof-of-concept after he read Andrew Davison's fantastic book entitled Killer Game Programming (which is also available online). "Thank you Andrew!" Later he found that there is a complete mess in Java APIs allowing you to capture images from webcams. Once you choose specific API you cannot change it without modifying large parts of the code. He decided to change this situation and write general purpose wrapper for various different APIs (like JMF, OpenCV, OpenIMAJ, LTI-CIVIL, VLC). In such a way, Webcam Capture as we know it today, was brought to life. Today you can change underlying frameworks just by replacing webcam driver (one line code change). If there is no driver for particular framework, it's very easy to write it yourself.
