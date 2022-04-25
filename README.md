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
First, I performed a simulation analysis to assess weither the statistical power was sufficient, given the data and under the assumption that the causal models in the original paper were correct. This seemed necessary as structural equation models usually require more datapoints and to get a better judgement about non-significant results. As you can see in the figure below, the power value of "percieved susceptibility" is low. Later in the analysis it turned out to be not significant. 
![grafik](https://user-images.githubusercontent.com/75476085/165175747-b833757a-af7c-48f2-a2c7-ad164532efa1.png)


## Measurement Models
In a second step I analyzed weither the question items provided plausible measurement models of the latent variables - something the original authors simply assumed. For example I tested if the measurements were equally reliable in the two treatment groups. Some modifications were made, but generally the question items were useful to construct latent factors. 

## Structural Modeling  
Only now I tested the causal mechanisms with structural equation modeling, which allows to take the measurement models into account and model complex causal relationships. 

### Predictors of vaccine mandate support  

![grafik](https://user-images.githubusercontent.com/75476085/165178953-bec8b125-9eee-4129-b388-0a659422b1a5.png)

