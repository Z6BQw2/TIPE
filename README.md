The project was corrupted during my transition towards Ubuntu, this slideshow which was saved on Beamer is the only remnant of its existence, results, as well as the technics used.
<br>
<br>
The goal was to predict the trajectory of a ball in real-time. It tackles the detection of the ball via a CNN, but in the cases when the ball is hidden, it switches to ultrasonic detection. I used ultrasounds because the emitters are cheap, but it would be more practical with higher frequency waves.
<br>
The latter system works by having trained a detector to determine the difference between skin and textile from the texture of a ball. In order to do this, I collected a good amount of ultrasonic data in different context, achieving the very high results displayed on the slideshow.
<br>
To determine the position of the ball, with the CNNs, I simply used a formula derivated from the inverse square law, whose radius comes from the box created by the CNN to find the distance from 3 different camera and used trilateration to get the position.
<br>
However, with the ultrasonic waves, I first proved the possibility of using a process similar to that of bats by placing receptors at various angles from the emitter with respect to the ball. But since the data collection with this method, while possible, would be difficult and require yet another ML model, I simply calculated, from the infl
