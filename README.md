# Feature-Selection
Deciding, which feature(Predcitor/Variable) is important(relevant) for our model.


Feature Selection is a process in which we decide which feature is relevant for our model.
We calculate devide the regression into sub regressions for each feature, and calculate the p-value for each. If p value is >0.05 then, that feature(variable) is not required for our model. 

NOTE: If adj R^2< R^2 then, any of the features described in our model is irrelevant.

In the model described by me, the P-value of feauture Rand 1,2,3 is more than 0.05, so this feature is not relevant. This was also notified by the value of adj R^2 whicih is greater than R^2.
