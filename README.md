# Reactance in the context of Covid-19 vaccines 

## Introduction
Reactance is the "_aversive motivation state that energizes individuals to restore their threatened or lost freedom in a way of asserting their autonomy_" (Quick and Stephenson 2007). This concept becomes relevant as governments are considering or are already implementing vaccine mandates to face the challenges of the covid-19 pandemic. Taking into account the possibility of reactance, one might expect that imposing vaccine mandates could lead to a lower willingness to get vaccinated.  

Sprengholz et al. used sum scores and multivariate regression to investigate this question in their study. After measuring a few variables, which they hypothesided would influence the support for a vaccine mandate, they randomly seperated the participants into two scenarios: 
- A vaccine mandate against Covid-19 for all adults
- A vaccine mandate only for health care professionals
Thereafter they measured the participants' reactance levels and planed future behavior. 
They were able to verify all of their hypotheses (see picture below). I applied Structural Equation Modeling, a more complex modeling technique, to replicate their results.  
![grafik](https://user-images.githubusercontent.com/75476085/161846721-088bc36e-dcec-4b02-b76c-06aa2bdaefdf.png)


## Power Analysis  
First, I performed a simulation analysis to assess weither the statistical power was sufficient, given the data and under the assumption that the causal models in the original paper were correct. This seemed necessary as structural equation models usually require more datapoints and to get a better judgement about non-significant results. As you can see in the figure below, the power value of "percieved susceptibility" is low. 
![grafik](https://user-images.githubusercontent.com/75476085/165175747-b833757a-af7c-48f2-a2c7-ad164532efa1.png)


## Measurement Models
In a second step I analyzed weither the question items provided plausible measurement models of the latent variables - something the original authors simply assumed. For example I tested if the measurements were equally reliable in the two treatment groups. Some modifications were made, but generally the question items were useful to construct latent factors. 

## Structural Modeling  
Only now I tested the causal mechanisms with structural equation modeling, which allows to take the measurement models into account and model complex causal relationships. 

### Predictors of vaccine mandate support  
As expected from the power analysis, the susceptibility was non-significant. Except for libertarian vaules, all the other predictors were as hypothesized. 
![grafik](https://user-images.githubusercontent.com/75476085/165178953-bec8b125-9eee-4129-b388-0a659422b1a5.png)

### Predictors of Reactance  
The only hypothesized predictor of reactance was the attitude towards vaccine mandates. Indeed a positive attitude towards vaccine mandates had a negative impact on reactance levels, and even more so when they were presented with the scenario of a limited vaccine mandate. 
![grafik](https://user-images.githubusercontent.com/75476085/167301402-c3fa70cc-03d6-449a-932b-2e3dc3a39f75.png)

But since structural equation modeling allows for more complex dependencies in the model, any non specified relationships are estimated as zero. Now one advantage of SEM is that it allows to estimate model modifications. In this case these estimates pointed towards an direct effect from Collective Responsibility on reactance levels. Allowing for this direct effect to be estimated, provided a model with a better fit and greater explanatory power.
![grafik](https://user-images.githubusercontent.com/75476085/167301711-a13c05ae-f7e8-43cb-a505-aeb257cd4758.png)

### Predictors of behavioral intentions
Then Reactance as a predictor of future behavior was tested. Again the hypothesis could be confirmed, but the analysis of the model showed some important cross-loading of items. Therefore the results are to be taken with caution. 
![grafik](https://user-images.githubusercontent.com/75476085/167301945-bf9b32f7-4382-40d3-9f97-06a4e8bc1dc9.png)

### Full model 
The specification of a model which included all specifications mentioned above didn't provide any new results concerning the results of interest. But some interesting modifications were proposed, which didn't get included in the originally hypothesized model. For example the avoidance of the Covid vaccine was better predicted when taking into account direct effects from Collective Responsibilty and confidence in vaccines. Taking these modification into account again didn't change sinificantly the original effects, but provided a better model fit and possibly a more coherent model. 

### Additional hypothesis 
An additional hypothesis, which came from Betsch and Böhm, was replicated. Here the goal was to explain the relationship between vaccine policy, reactance and the flu vaccine. 
![grafik](https://user-images.githubusercontent.com/75476085/167302292-61b6d3fb-f50b-4912-b494-f575550a0894.png)

Here again the strength of SEM showed by allowing for additional paths and providing ideas for model modifications. One modification was made through which the attitude towards vaccine mandates had a direct influence on the intention to take the vaccine against flu. The new model showed a complete mediation of the effect from the vaccine policy. 
![grafik](https://user-images.githubusercontent.com/75476085/167302456-bf3ab4a3-238e-4b91-b07a-066738c00663.png)

