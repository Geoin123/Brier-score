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

Calculating brier scores
=========================
As probabilities implied by betting markets add up to more than 100%, we first adjust the odds pro-rata to determine the probabilities of each outcome for a match.

The Brier Score per match is the sum of the square difference of the probability and actual results. Let’s take the match Man City vs Leicester on February the 6th. The bookmakers implied that Man City had a 62% chance of winning a 25% chance of a draw and a 17% chance of losing to leicester.

The probabilities for Win:Draw:Loss were 0.62:0.25:0.17 with the actual result being 0:0:1, where one stands for the actual outcome. The differences are 0.62:0.25:0.17 . The sum of the square differences are 0.62^2 + 0.25^2+ 0.83 = 1.1358. This is the Brier Score for this match

The Brier score can range from 0, if odds guessed the outcome directly by stating there is 100% chance of only one outcome to be correct, to 2, if odds implied that one outcome is certain and that did not occur.

However, if we had to just throw outcomes at random and say that a home win, draw or away win are equally likely, then our Brier score would be 0.667, irrespective of the outcome.

The table below shows the Brier score per team in the Premiership. What we note is that some of the surprises are actually vindicated in the stats: Chelsea, Liverpool and West Ham are not performing as expected while for Arsenal and Manchester City it is business as usual.

![Image](http://www.pinnaclesports.com/Cms_Data/Contents/Guest/Media/betting-articles/soccer/premier-league/2015-16-September-Premier-League/brier-score-table.jpg?raw=true)


Teams with high Brier Score
===========================

Who would have ever thought that mighty Chelsea from last year would implode months after winning the league rather easily? One can never fully predict such a thing even though this is exactly what we are supposedly most familiar with: the human factor.

It is the human factor that gels a bunch of random human beings into a well-oiled machine. And this is what Chelsea seems to have lost this year. On the flipside, who could have predicted that Leicester would have such brilliant runs and be league leaders?

One could argue that almost every year an averagely sized team packs up a far greater punch than what is expected of them. New manager Slaven Bilic probably was a deciding factor in this no-nonsense away conquering West Ham side. Such a thing is easy to say in hindsight but what the clever pundit strives to do is see things in foresight and this is once again where the human factor comes in.


Advantages of the Brier score
=========================

1. **General**: It can be used to assess predictions by any model for binary and continuous and right censored response variables.

2. **Mathematical**: It estimates a well-defined parameter in the population

3. **Philosophical**: It is a strictly proper scoring rule, thus the true model would win any comparison.

4. **Practical**: It has an interpretation for a single patient.

5. **Reliable**: Easily implemented with validation procedures.




