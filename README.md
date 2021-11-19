# K-means-clustering-clothing-design-center

# Introduction

k-means clustering is one of the simplest and most commonly used clustering algorithms. It tries to find cluster centers that are representative of certain regions of the data. The algorithm alternates between two steps: assigning each data point to the closest cluster center, and then setting each cluster center as the mean of the data points that are assigned to it. The algorithm is finished when the assignment of instances to clusters no longer changes.

# Objective

Let's design some shorts, but how ???? Les use K means clustering to figure out the best sizes for the population

# Data

Body Measurement dataset from https://data.world/rhoyt/body-measurements. This dataset has 27 columns and 9338. The cvs file ad jupyter notebook of the code is found in this repository.


Two columns are most important:

BMXWAIST: Waist Circumference (cm)
BMXLEG: Upper Leg Length (cm)

# K- means (K=2)

■■ Waist 77.8 cm, upper leg length 37.7 cm

■■ Waist 107.9 cm, upper leg length 38.8 cm

# K- means ( K=4)

■■ Waist 67.3 cm, upper leg length 36.0 cm

■■ Waist 85.1 cm, upper leg length 38.7 cm

■■ Waist 102.2 cm, upper leg length 38.9 cm

■■ Waist 124.1 cm, upper leg length 38.6 cm


# Conclusion

Unsupervised learning is a type of machine learning technique that allows you to find patterns in data. In unsupervised learning, the data that is used by the algorithm (for example, K-Means) is not labeled, and our role is to discover its hidden structures and assign labels to them.

Ok! great, let’s open our design fashion center, start sewing the best sizes found and conquer the market!
