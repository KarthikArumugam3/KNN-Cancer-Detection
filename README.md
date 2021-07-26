# KNN-Cancer-Detection

This project has a simple dataset representing gene expression levels. Gene expression levels are calculated by the ratio between the expression of the target gene (i.e., the gene of interest) and the expression of one or more reference genes (often household genes). This dataset is synthetic and specifically designed to show some of the strengths and limitations of using KNN for Classification.

I have used 3 ways to demonstrate how KNN works:-
1. First I have just used 1 as the nearest neighbors value 
2. Next I have used the Elbow method to find out the best possible value of K for higher accuracy, which is more sort of a manual way.
3. Finally I have used Gridsearch with cross-validation to find out the most accurate K value possible to attain maximum accuracy.

I have also used the pipeline concept to demonstrate how the repititive tasks can be put all together inside the pipeline and can be used whenever we need, this can be found alongside the Gridsearch with cross-validation method where I have combied both.
