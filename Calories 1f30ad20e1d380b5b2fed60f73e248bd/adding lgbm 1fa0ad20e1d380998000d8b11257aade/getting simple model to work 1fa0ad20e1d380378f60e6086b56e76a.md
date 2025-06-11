# getting simple model to work

looking at other kaggle notebooks, looks like we can just import

![image.png](../exploring%20types%20of%20models%201f50ad20e1d380ea8ecfc68b689796c4/LightGBM%201f50ad20e1d3802fa145f3961772608f/image%201.png)

i reckon im going to create a new copy of the current notebook and move over to lgbm

![image.png](getting%20simple%20model%20to%20work%201fa0ad20e1d380378f60e6086b56e76a/image.png)

looks like we can just define a simple model that might work with our dataset

![image.png](getting%20simple%20model%20to%20work%201fa0ad20e1d380378f60e6086b56e76a/image%201.png)

yep. this just ran

- think this is because all the parameters are optional

but this doesn’t work fitting

![image.png](getting%20simple%20model%20to%20work%201fa0ad20e1d380378f60e6086b56e76a/image%202.png)

[https://www.kaggle.com/code/lasmith/house-price-regression-with-lightgbm#Light-GBM](https://www.kaggle.com/code/lasmith/house-price-regression-with-lightgbm#Light-GBM)

![image.png](getting%20simple%20model%20to%20work%201fa0ad20e1d380378f60e6086b56e76a/image%203.png)

[https://www.geeksforgeeks.org/regression-using-lightgbm/](https://www.geeksforgeeks.org/regression-using-lightgbm/)

im seeing in a few ways that other notebooks use a regressor model, i can try that

![image.png](getting%20simple%20model%20to%20work%201fa0ad20e1d380378f60e6086b56e76a/image%204.png)

yep, and it bloody works super quickly

- going to have to come back to this since geoff will be calling soon