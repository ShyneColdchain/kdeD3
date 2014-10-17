Interactive Kernel Density Estimation (KDE) + histogram in D3. 

Largely taken from KDE from examples. 

http://bl.ocks.org/mbostock/4341954#faithful.json

Including D3-tip for interactivity. 

http://bl.ocks.org/Caged/6476579

--Learning D3!-- 

1. allAge is 5000 simulated individuals of different ages representing the population - *Gray histogram*
2. sampleAge is 500 randomly choosen individuals from the population  - *Purple histogram*
3. kdeD3 creates interactive histogram with kernel density estimation - *black line with red fill* 
4. kde for sample can be compared to real values from population for statistical inference 


Goals: 

1. further interactivity!
2. metadata appear with mouse over (ex. % female / male) - *INCOMPLETE! Error with logic*
3. both sampleAge and allAge histograms on single plot - *DONE* 

Not sure how to incorporate metadata (gender) with bins. Histogram is built off of the .age of the data. But data also has a respective .gender (each age has a corresponding gender, either 0 or 1, male or female). I want to calculate the percent male and percent female for each bin in the histogram - in other words, number of 0s vs. number of 1s *OR* number of 0s/1s in each bin divided by total number of 0s/1s in data. NEED HELP HERE! 
