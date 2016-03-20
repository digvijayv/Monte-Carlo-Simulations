# Monte-Carlo-Simulations
Monte Carlo simulations are rudementry tests of various outcome probabilities. It also underlines all the risks involved and potential outcomes of your experiment. Once such experiment that is accesed in this repo is the gamblers fallacy.

Gambler's Fallacy also called Monte Carlo fallacy is a naive "trap" in which even at times professioanl gamblers fall prey to. Humans interpret that if something happens more frequently, it will happen less frequently in the future. Such as a coin toss, but that is not the truth each time you flip a coin the probability of "tails" to be registered will always be equal to that of "heads" no matter how many heads or tails preceeded previously in a row.

Results - 
DAlembert approach - is to increase the wager each time you lose and decrease it each time you win.

#######################
sample size = 1000
startingFunds = 100000
wagerSize = 100
wagerCount = 1000
#######################
#######################
Total invested: 100000000
Total return : 102267100
R-I: 2267100
Bust Rate: 17.7
Profit rate: 66.6
lost money:  33.4
#######################
Making money huh $$ ;)

3D scatter plot of this approach plotted

Monte Carlo strategy can even be used to predict the value of "PI".Consider a circle inside a square the area of that circle will be pi*r^2/4 and the are of square is r^2. 
Strategy - Choose a large number of sample points inside the square randomly, each of them will have a probability of pi/4 to be inside the circle. Hence the program calculate whether the point is inside the circle or not and multiple the probability by 4 to get the approx. value of PI.

Results:
side = 800
samples = 640000
pts_in_circle = 502748
pts_out_circle 137252
predicted_value:  3.142175
expected_value:  3.14159265359
error percent:  0.000185366619552