# Idea2.HowManyDatasetWeNeed

Dataset: MNIST fashion dataset    
(60000, 28, 28), labels: (10, 60000) 0~9, 6000 images each class    

Hypothesis: there is an optimal number for training the model    
+@: checking the result of accuracy and loss,    
it would be gaussian distribution.    
so, we could estimate that best performance.    

experiment1. 10 images for each class    
5:5
6:4
7:3
8:2
9:1

experiment2. 20 images for each class    
10:10
12:8
14:6
16:4
18:2

experiment3. 50 images for each class
25:25
30:20
35:15
40:10
45:5

experiment4. 100 images for each class    
50:50
60:40
70:30
80:20
90:10
