# Question 1
## a. The testing error rise at the hight value of K because knn works on the nearest neighbour and more the neighbour we take into consideration the chances of getting an incorrect predicition are higher. For istance in our case the higher the value of k is, the chances of  inculding 9 in the prediciton of 8 increases, as a result giving a incorrect prediction.


[0.0, 0.0, 0.0, 0.0, 0.0, 0.2, 0.2, 0.4, 0.2, 0.2, 0.2, 1.0, 0.6, 0.8, 0.8, 1.2, 1.0, 1.6, 1.4000000000000001, 1.7999999999999998]
## b. As we can see that the error rate at the lowe value of k=1,5 is 0.0. i think this a reliable perfomance estimate because i also printed out the accuracy data and it justifies. Also it makes sense that the error rate is is less at lower values of k because while testing, the machine is only taking the fewer values as reference to predict which are more likely to be the same values as a result the error rate at lower value of k is lowest.

# Question 2
 
DATA DISCRIPTION# 
The data consist of behavior of people and corresponding risk to develop cancer. The data has 19 attributes, meaning 19 behavior and 76 instances
the data is used for classification and which behavior has the highest risk of having cancer.
## AUC Values
             Feature              AUC 

1              behavior_eating  0.618114
5         attitude_consistency  0.590103
6         attitude_spontaneity  0.529879
15  socialSupport_instrumental  0.417834
0          behavior_sexualRisk  0.376284
4         intention_commitment  0.339402
7       norm_significantPerson  0.328665
11         motivation_strength  0.305322
14  socialSupport_appreciation  0.303455
3        intention_aggregation  0.297852
2      behavior_personalHygine  0.282446
12      motivation_willingness  0.266573
13  socialSupport_emotionality  0.253501
8             norm_fulfillment  0.250233
9     perception_vulnerability  0.247899
18         empowerment_desires  0.226424
10         perception_severity  0.212885
16       empowerment_knowledge  0.194678
17       empowerment_abilities  0.170401
