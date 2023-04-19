# Here I choose letter recognition dataset from UCI library. I used this dataset to optimize parameters of SVM. In this assignment I divide dataset to 10 different samples and use these samples to find best parameters that give best accuracy.

## About dataset


1. It is a multiclass dataset with 19999 rows and 17 columns.


2. Out of 17 attributes 16 primitive numerical attributes (statistical moments and edge counts) which were then scaled to fit into a range of integer values from 0 through 15


3. There are 26 classes in dataset i.e alphabets(A-Z)

## Attribute Information:

1. lettr capital letter (26 values from A to Z)
2. x-box horizontal position of box (integer)
3. y-box vertical position of box (integer)
4. width width of box (integer)
5. high height of box (integer)
6. onpix total # on pixels (integer)
7. x-bar mean x of on pixels in box (integer)
8. y-bar mean y of on pixels in box (integer)
9. x2bar mean x variance (integer)
10. y2bar mean y variance (integer)
11. xybar mean x y correlation (integer)
12. x2ybr mean of x * x * y (integer)
13. xy2br mean of x * y * y (integer)
14. x-ege mean edge count left to right (integer)
15. xegvy correlation of x-ege with y (integer)
16. y-ege mean edge count bottom to top (integer)
17. yegvx correlation of y-ege with x (integer)

## Data Analytics

1. Checking whether data is balanced or not

![image](https://user-images.githubusercontent.com/79744977/233181503-1c2a82c0-ff4e-4e94-8022-089c7464bf88.png)

As we can see from histogram data for all the classes are almost equal in number. So the dataset is balanced

2. Statistical summary

![image](https://user-images.githubusercontent.com/79744977/233182801-ef3297cb-bef6-49df-9478-c8dc802a37e3.png)

3. Null values

There is no null value in dataset

## Result

![image](https://user-images.githubusercontent.com/79744977/233186104-ee32d6c9-600b-485a-bb00-4b4891e63062.png)

Best accuracy : 88.166667


Best Model : rbf


Best nu : 0.029818


Best epsilon: 0.010533

