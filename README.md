# car_nueralnetwork_javascript

Example project while following along to https://www.youtube.com/watch?v=Rs_rAxEsAvI&t 

4/23 0:00 - 23:16 - Modified some of how he handled the friction.  In the video, the speed will bounce back and forth if not a perfect multiple of the friction.  

I wrote it to check if speed difference from 0 is less than the friction value; if so then set speed to 0.

EXAMPLE__________________________________________________________________

speed = .2
friction = .03

old -> .2, .17, .14, .11, .08, .05, .02, -.01, .02, -.01, .02, etc...
new -> .2, .17, .14, .11, .08, .05, .02, 0, 0, 0, 0, 0
________________________________________________________________________


4/28 23:16 - 49:51 - Turns out what I thought he messed up in last section he want back through and showed the correct way which was they was I did it.  

