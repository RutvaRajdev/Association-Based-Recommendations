# Association-Based-Recommendations

The goal of the project was to suggest recommendations and changes in a grocery store's setup using association rules. The dataset used was of a grocery store containing 9835 of its transactions. First of all, candidate itemset was generated in order to get all the potential frequent itemsets. Frequent-1 itemsets were then generated via support-based pruning. All the frequent itemsets were generated from this, once using Apriori algorithm, and then using FP-growth algorithm. These were used to then generate association rules. The support and confidence thresholds were decided based on trial-and-error in order to gain the maximum insight. All the rules were studied, analysed and then some recommendations were suggested in the setup of the grocery store in order to generate maximum revenue.
