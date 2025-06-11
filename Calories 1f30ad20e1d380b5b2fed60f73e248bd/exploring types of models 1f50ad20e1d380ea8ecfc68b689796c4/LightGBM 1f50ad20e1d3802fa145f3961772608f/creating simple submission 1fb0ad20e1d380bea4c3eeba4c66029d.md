# creating simple submission

![image.png](creating%20simple%20submission%201fb0ad20e1d380bea4c3eeba4c66029d/image.png)

we can see that the regression model actally trained on the data (or at least that’s what it looks like)

going to try and predict the test dataset

![image.png](creating%20simple%20submission%201fb0ad20e1d380bea4c3eeba4c66029d/image%201.png)

and we can see that it actually predicted the data!

going to copy other functions from my other notebook and create an submissoin

![image.png](creating%20simple%20submission%201fb0ad20e1d380bea4c3eeba4c66029d/image%202.png)

yep, and the submission looks like, with the correct column names and no -ve calories, going to submit it and see what happens

![image.png](creating%20simple%20submission%201fb0ad20e1d380bea4c3eeba4c66029d/image%203.png)

oh wow! it’s actually pretty good

![image.png](creating%20simple%20submission%201fb0ad20e1d380bea4c3eeba4c66029d/image%204.png)

oh despite, the top score being 0.56xx, we’re still 2622, clearly the progression is logathmic

![image.png](creating%20simple%20submission%201fb0ad20e1d380bea4c3eeba4c66029d/image%205.png)

i was trying to edit the .fit parameters and it’s actually part of sklearn

![image.png](creating%20simple%20submission%201fb0ad20e1d380bea4c3eeba4c66029d/image%206.png)

yep, it looks like we actually dont define epochs here

![image.png](creating%20simple%20submission%201fb0ad20e1d380bea4c3eeba4c66029d/image%207.png)

[https://stackoverflow.com/questions/57046862/what-is-the-difference-between-model-lgbmregressor-fitx-train-y-train-and-lig](https://stackoverflow.com/questions/57046862/what-is-the-difference-between-model-lgbmregressor-fitx-train-y-train-and-lig)

![image.png](creating%20simple%20submission%201fb0ad20e1d380bea4c3eeba4c66029d/image%208.png)

going to try again with a high learning rate, since we can’t define epochs here

- can confirm that it did create slightly different results

and yeah it was worse lol

![image.png](creating%20simple%20submission%201fb0ad20e1d380bea4c3eeba4c66029d/image%209.png)

looks like the standard way is not a bad way to go

i want to add in features engerring next