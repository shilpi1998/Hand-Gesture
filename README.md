# Hand-Gesture

A gesture is a form of non verbal communication or non vocal communication in which visible bodily actions communicate particular messages, either in place of, or in conjunction with, speech. Gestures include movement of the hands, face, or other parts of the body. Gestures differ from physical non-verbal communication that does not communicate specific messages, such as purely expressive displays, proxemics, or displays of joint attention. Gestures allow individuals to communicate a variety of feelings and thoughts, from contempt and hostility to approval and affection, often together with body language in addition to words when they speak.
<br>
The general technique for hand gesture recognition involves a sequence of image
processing steps. The first major step is image segmentation where the hand region is identified from the image. <br>

First, the hand is detected using the background subtraction method and the result of hand detection is transformed to a binary image. Then, the fingers and palm are segmented so as to facilitate the finger recognition. Moreover, the fingers are detected and recognized. Last, hand gestures are recognized using a simple rule classifier.
<br>
The hand gesture is predicted according to the number and content of fingers detected.
