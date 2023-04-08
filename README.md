# Ball Pitch Detection
* The Problem Statement is to find the quadrant at which ball is pitched and the exact timeframe when the ball is pitched, in a video which shows ball being thrown at different speeds at different quadrants. 

* We solved this by mapping the quadrants in OpenCV, and then plotting the movement of ball and then using a simple logic to find the pitching point.

* The Logic is that, the pitching point makes the lowest angle with respect to previous and next points of movement compared to all the other angles.

* By using this we get the quadrant of pitching and the timeframe when it is pitched.
<br />

## Problem Statement
Video Link : [Click Here](https://drive.google.com/file/d/16smC_RuoFHRlaTnUcjZmPF-SYugXwORz/view). <br /><br />
Now, We've to find the quadrant at which ball is pitched and the exact timeframe when the ball is pitched, in a video which shows ball being thrown at different speeds at different quadrants.
<br />


## How we solved
We solved this by mapping the quadrants in OpenCV, and then plotting the movement of ball and then using a simple logic to find the pitching point. The Logic is that, the pitching point makes the lowest angle with respect to previous and next points of movement compared to all the other angles.

Solution Video Link : [Click Here](https://drive.google.com/file/d/1g79CMvOCCYTAIqnjS4ipebn2pYBwEs4G/view?usp=share_link).

Output CSV File Link : [Click Here](https://github.com/shobhanoffl/Ball-Pitch-Detection/blob/main/ball_bounce_output.csv).
