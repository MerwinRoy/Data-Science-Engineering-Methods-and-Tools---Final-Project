# INFO 6105 : Data Science Engineering Methods and Tools
# Final Project: IPL cricket teams performance analysis

![Cricket-amico](https://user-images.githubusercontent.com/46862684/198855800-3d690a9b-4c43-4a4d-980e-7c10a8272113.png)

## Description
In this project, **Bayesian Linear Regression** has been implemented to predict the performance of IPL (Indian Premiere League) cricket teams based on two factors: Power hitting ability and Consistency to score runs by the batsman (batter).

**Eventually, proving the hypothesis that power hitters has a greater impact on team's performance than consistency of players.**

  * Bayesian Linear Regression creates a model that maps features such as strikerate (power hitting index) and batting average (consistency index) to the target (strength of the team).
  * Instead of specifying probabilities using Bayesian, predictions were made using machine learning.
  * Bayesian Linear Regression is ideal since with the use of logical priors, a distribution of all sampled weights can be drawn from the simulation instead of a single value, which can be used to form predictions.


## Team
| **Team Members**|
| ------------- |
| Merwin Roy      |
| Nidhi Tiwari|
| Sri Sai Amulya Nittala |

## Conclusion

**Plotting Team Strength vs Strike Rate**

<img width="514" alt="Screen Shot 2022-10-29 at 6 51 02 PM" src="https://user-images.githubusercontent.com/46862684/198855386-beb47e5a-f5a8-4c8c-97f6-deb3cf338b3d.png">

**Plotting Team Strength vs Consistency**

<img width="465" alt="Screen Shot 2022-10-29 at 6 51 20 PM" src="https://user-images.githubusercontent.com/46862684/198855394-38e01413-a8f2-46a0-864c-30c223bbf9b0.png">

**The graph plot for team strength vs Strike rate has closer distribution of lines as compared to graph plot for team strength vs consistency. 
From this, we can draw conclusion that the team's strike rate (power hitting ability) is closely related to team's strength than team's consistency.**

---

Also, Using two distribution models (Student-T and Normal Distribution), distribution of the prediction can be plotted taking mean of parameters into the model.

**Student-T Distribution**

<img width="452" alt="Screen Shot 2022-10-29 at 6 52 26 PM" src="https://user-images.githubusercontent.com/46862684/198855530-c8075da2-d953-48f1-9978-df2f335dad24.png">

**Normal Distrubtion**

<img width="471" alt="Screen Shot 2022-10-29 at 6 52 36 PM" src="https://user-images.githubusercontent.com/46862684/198855543-5222a8d5-1619-4362-a61c-92efd9ada2c2.png">

**Using the above two distribution models, we can observe that the team strength is close to mean estimate.
However with the existence of slight variations, Student t-distribution and normal distribution is ideal model when working with large datasets. When working with small datasets, we can use appropriate logical priors with Bayesian methods to build better models.**
