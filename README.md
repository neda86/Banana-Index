# Banana-Index
The banana index measures the greenhouse gas emissions of different foods, comparing them to bananas. It looks at the emissions based on weight, calorie, or protein, and uses CO2-equivalents to account for different types of gases and their impact over 100 years. Essentially, it's a way to compare how efficient different foods are in terms of emissions. For example, strawberries emit 5.18 kilograms of CO2-equivalents for every 1000 calories, while bananas emit 0.88 kilograms per 1000 calories. So, the banana score for strawberries (based on calories) is 5.18 divided by 0.88, which is about 6. This means strawberries have six times the emissions of bananas per calorie.

- Data for this question comes from:
https://www.kaggle.com/datasets/joebeachcapital/banana-index
a novel metric for CO2 emissions using bananas as a reference.

• Loadthedata,and remove unnecessary columns and missing/NA.

• Select a subset of 2 columns useful for clustering.

• Produce a scatter plot of the data, and a scatter plot of the log of the data (eg base 10), discuss whether you should use the log or non-log transformed data for clustering.
Perform k-medoids clustering and choose a suitable number for k and discuss why (explore
• Usingyourchoicefork,plotthepoitnswithacolorforeachclusterlabelandplaceamarker in the center of each cluster, and put the name of the food for that medoid (exemplar center) as an annotation label.
• Look at the separation of the foods based on clusters, and discuss any major differences in the cluster assignments for the names of the foods by printing the food labels for each cluster.
b.
the key change for different k). 
• For each point find the distance to each medoid (cluster center which is an exemplar) for each point (food). This should produce 2 distance values. Produce the absolute difference between those distances and display the set of distances on a histogram.
• Findthe3closesttozeroonthatdistributionandcommentonthefoodsselected.Plotthose foods as annotations on the scatter plot and discuss the findings for any pattern which can be speculated.

e. Find the 6 most ’extreme’ of the foods by distances from the medoids. You may construct your own metric for that distance based on medoid distance. Print the names of the foods and plot as
text annotations on the scatter plot.
