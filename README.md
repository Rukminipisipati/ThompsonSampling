# ThompsonSampling
# Algorithm implementation on Ads_CTR_Optimisation.csv.
# The algorithm follows the following steps:
# Step-1: At each round n, we consider two terms for each ad i.
# a. Ni1(n): The number of times the ad i got reward 1 upto the round n.
# b. Ni0(n): The number of times the ad i got reward 0 upto the round n.
# Step-2: For each ad i, we take a random draw from the distribution random_draw(n) = Betavariate(Ni1(n)+1, Ni0(n)+1)
# Step-3: Finally, we select the ad that has the highest randon_draw among all the ads at each round.
# Thompson Sampling is the probabilistic algorithm in most of the cases and the best results are obtained in least possible rounds.
