# Gold recovery prediction

We prepare a prototype of a machine learning model for [Zyphra](https://www.zyfra.com/). The company develops solutions for the efficient operation of industrial enterprises.

The model must predict the recovery rate of gold from gold ore

The model will help optimize production so as not to launch an enterprise with unprofitable characteristics.

# Report

Research analysis:
The concentration of gold increases as the ore is refined, the concentration of silver gradually decreases, and the concentration of lead increases slightly. 
As processing proceeds, the total concentration of chemicals has a smaller range. 
The size of raw material granules in the training and test sets are distributed approximately equally.

Model building:
For the rougher.output.recovery forecast, the random forest performed best with the regression task, whose score on the test sample was 4.28%. 
For the final.output.recovery forecast, linear regression performed worse than random forest. 
The random forest score on the test set is 6.27%. Therefore, the final score, as a weighted average, is 5.77%
