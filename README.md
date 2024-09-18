# Dropout-prediction-models
With the use of the classification models, we derived that the possibility of a dropout can be approached early on during the admission process.

### Conclusion
To make a conclusion about the model that is the most efficient for predicting whether a student will dropout or stay enrolled we will first look at the error rates of each model:

CART algorithm has MSE = 0.217 ,
C5.0 algorithm has MSE = 0.218 ,
Random Forest algorithm has MSE = 0.218 ,
Logistic Regression has MSE = 1.219.

Random Forest algorithm produces results with the least error thus making it the best predictor.

With the use of the classification models, we derived that the possibility of a dropout can be approached early on during the admission process. The fact that the most powerful predictor of students’ dropout is the payment of the tuition is very intuitive, as those students, who are planning on dropping out will not prepay their tuition in advance. One of the key determinants was the course that the student is applying to, as some courses are a lot more academically challenging than others. Additionally, the age of enrollment has high predictive power, these finding suggests that the university’s administration should acknowledge the difficulties that might incentivize older students to drop out. For example, the difficulty to establish social relations with people, who are a lot younger than themselves. The fact that the previous grades and admission grades have a high impact on the student’s choice to drop out is also very intuitive, as it suggests whether the student can have high performance in an academically rigorous environment. Our findings also imply that the choice to drop out is highly related to the student’s social background (Father’s and Mother’s occupation). Surprisingly, we do not have enough statistical evidence that the student’s choice to drop out is related to the state of the economy, the student is experiencing, although economic theories suggest that, for example, high unemployment rates would incentivize people to stay in the universities. However, we have not found any association between the unemployment rate and inflation rate with dropout. The GDP showed some association with the target variable, however, it was not classified very high on the importance of predicting dropout.

### Appendix
This project was developed by Miras Kanatzhanov with the assistance of Dr. Reza Mohammadi as a part of Data Science and AI minor at UvA
