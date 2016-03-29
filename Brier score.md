Brier-score
======================
The Brier score is a proper score function that measures the accuracy of probabilistic predictions. 
It is applicable to tasks in which predictions must assign probabilities to a set of mutually exclusive discrete outcomes.
The set of possible outcomes can be either binary or categorical in nature, and the probabilities assigned to this set of outcomes 
must sum to one (where each individual probability is in the range of 0 to 1). 

The Brier score can be thought of as either a measure of the "calibration" of a set of probabilistic predictions, or as a "cost function". More precisely, across all items i = {1...N} in a set N predictions, the Brier score measures the mean squared difference between:

• The predicted probability assigned to the possible outcomes for item *i*

• The actual outcome O**i**

Therefore, the lower the Brier score is for a set of predictions, the better the predictions are calibrated. Note that the Brier score, in its most common formulation, takes on a value between zero and one, since this is the largest possible difference between a predicted probability (which must be between zero and one) and the actual outcome (which can take on values of only 0 and 1).

The Brier score is appropriate for binary and categorical outcomes that can be structured as true or false, but is inappropriate for ordinal variables which can take on three or more values (this is because the Brier score assumes that all possible outcomes are equivalently "distant" from one another).

Applications of brier score in football
=============================================

Football is unpredictable. That unpredictability gives the sport its appeal inspires the fans and also gives betting punters a headache week in, week out. Using a verification measure like the Brier Score gives betters a more systematic point of view as to what is happening in the league right now

One of the best available predictors for an outcome, especially if you believe in efficient markets, are betting odds. Hence, teams that perform differently than what predicted are either over-performers or under-performers.


As probabilities implied by betting markets add up to more than 100%, we first adjust the odds pro-rata to determine the probabilities of each outcome for a match.

Brier Score = (Actual Result - Probability Assigned to Actual Result)^2
 
• Brier score  
 
Also known as Quadratic Loss (Hvattum & Arntzen, 2010), the Brier Score measures the average
squared deviation between predicted probabilities for a set of their events and their outcomes. For an
individual match the score is  (Brier, 1950) 



random stuff dhsfdhadfh
c
fsdhsdhsdfhgdfg 

 
 -item1 `functionname(hello)`
 -item2 `functionname(Hello)`
 


Disadvantages of the Brier score

Rare diseases. It is difficult to see differences in populations with
small prevalence

Intuition. It does not penalise very small forecasted probabilities
when they should be giving larger probabilities to the same extent
that we penalise such forecasts with our intuition. Intuition
apparently uses fractional or logarithmic rather than differences in
probability. 

For binary and continuous and right censored outcome the Brier score can be used  to ﬁnd predictive or diagnostic markers ◮ to assess the predictive performance of a traditional statistical model ◮ to assess an algorithmic (black box) model ◮ to detect overﬁtting ◮ to compare simple to complex models ◮ for focussed and automated model selection.

Decompositions
=============

There are several decompositions of the Brier score which provide a deeper insight on the behavior of a binary classifier.
