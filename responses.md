# Question 1
## a. The testing error rise at the hight value of K because knn works on the nearest neighbour and more the neighbour we take into consideration the chances of getting an incorrect predicition are higher. For istance in our case the higher the value of k is, the chances of  inculding 9 in the prediciton of 8 increases, as a result giving a incorrect prediction.


[0.0, 0.0, 0.0, 0.0, 0.0, 0.2, 0.2, 0.4, 0.2, 0.2, 0.2, 1.0, 0.6, 0.8, 0.8, 1.2, 1.0, 1.6, 1.4000000000000001, 1.7999999999999998]
## b. As we can see that the error rate at the lowe value of k=1,5 is 0.0. i think this a reliable perfomance estimate because i also printed out the accuracy data and it justifies. Also it makes sense that the error rate is is less at lower values of k because while testing, the machine is only taking the fewer values as reference to predict which are more likely to be the same values as a result the error rate at lower value of k is lowest.

# Question 2
 
DATA DISCRIPTION# 
The data consist of behavior of people and corresponding risk to develop cancer. The data has 19 attributes, meaning 19 behavior and 76 instances
the data is used for classification and which behavior has the highest risk of having cancer.
## AUC Value
|    | Feature                    |   AUC |
|---:|:---------------------------|------:|
| 17 | empowerment_abilities      | 0.17  |
| 16 | empowerment_knowledge      | 0.195 |
| 10 | perception_severity        | 0.213 |
| 18 | empowerment_desires        | 0.226 |
|  9 | perception_vulnerability   | 0.248 |
|  8 | norm_fulfillment           | 0.25  |
| 13 | socialSupport_emotionality | 0.254 |
| 12 | motivation_willingness     | 0.267 |
|  2 | behavior_personalHygine    | 0.282 |
|  3 | intention_aggregation      | 0.298 |
