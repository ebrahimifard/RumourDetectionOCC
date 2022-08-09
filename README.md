## Computational Rumour Detection without Non-rumour: A One-Class Classification Approach
This repository pertains to the paper "Computational Rumor Detection Without Non-Rumor: A One-Class Classification Approach", published in the journal of IEEE Transactions on Computational Social Systems. 

## Summary
Rumour spreading in online social networks can inflict serious damages on individual, organisational, and societal levels. This problem has been addressed via computational approach in recent years. The dominant computational technique for the identification of rumours is the binary classification which uses rumour and non-rumour for the training. In this method, the way of annotating training data-points determines how each class is defined for the classifier. Unlike rumour samples which often are annotated similarly, non-rumours get their labels arbitrarily based on annotators' volition. Such an approach leads to unreliable classifiers which cannot distinguish rumour from non-rumour consistently. In this research, we tackle this problem via a novel classification approach, called one-class classification (OCC). In this approach, the classifier is trained with only rumours, which means that we do not need the non-rumour data-points at all. For this study, we use two primary Twitter datasets in this field and extract 86 features from each tweet. We then apply seven once-class classifiers from three different paradigms and compare their performance. Our results show that this approach can recognise rumours with a high level of F1-score. This approach may influence the predominant mentality of scholars about computational rumour detection and puts forward a new research path toward dealing with this problem. 

## Results
The following figure displays the impact of training sample size on the performance of classifiers in the Zubiagaset and Kwonset.
![1](https://user-images.githubusercontent.com/70349945/183776375-6036290f-4794-4b82-b2ee-fad7c4384a81.JPG)

The following figure displays the classifiers performance in different feature categories in the Zubiagaset and Kwonset.
![2](https://user-images.githubusercontent.com/70349945/183776436-4182e71d-8f1d-4606-9dd8-2843da43d19e.JPG)

The following figure displays the execution time of classifiers in the Zubiagaset and Kwonset.
![3](https://user-images.githubusercontent.com/70349945/183776490-62611cff-6916-41a2-8543-aaf23e8ce56e.JPG)

## Access
To get access to the full paper, please visit [paper webpage](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6570650), or contact the main author. 

## Citation
A. Ebrahimi Fard, M. Mohammadi, Y. Chen and B. Van de Walle, "Computational Rumor Detection Without Non-Rumor: A One-Class Classification Approach," in IEEE Transactions on Computational Social Systems, vol. 6, no. 5, pp. 830-846, Oct. 2019, doi: 10.1109/TCSS.2019.2931186.
