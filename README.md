# Hydrometeor-Classification-using-Machine-Learning
The hydrometeors in a cloud are classified into 11 categories: <br>
0=Unclassified, 1=Drizzle, 2=Rain, 4=Ice Crystals, 5=Wet Snow, 6=Vertical Ice, 7=Low Density Graupel, 8=High Density Graupel, 9=Hail, 10=Big Drops <br>
The problem at hand is to classify the same based on six features: <br>
'Combined (max) Reflectivity', 'Zonal wind (U)', 'Meridional wind (V)', 'Convergence', 'Vorticity', 'Vertical Wind (w)', 'Precipitation Fall Speed' <br>
Preliminary analysis involves analysing 4 algorithms: Random guess, Gaussian Naive Bayes, Decision Tree, KNN.<br>
Basic calculation:<br><br>
![Accuracy for baseline model](https://github.com/yashgokhale/Hydrometeor-Classification-using-Machine-Learning/blob/master/acc.png) <br>
Based on the results, deeper neural networks will be built.

