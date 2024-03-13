# Market Basket Analysis in Python Using the Apriori Algorithm

## Overview
When you step into a supermarket, you've likely observed how items like baby diapers and wipes, bread and butter, pizza ingredients, beer, and chips are strategically placed together to stimulate sales. Market basket analysis delves into the correlations between products that customers purchase simultaneously. It serves as a valuable tool for brick-and-mortar retail stores to promote related products and for online retailers to suggest items based on customers' typical purchasing habits. The Apriori and FP-Growth algorithms are widely employed for this analysis, aiding in deciphering customer shopping behaviors and preferences.

## Apriori Algorithm
The Apriori algorithm, devised by R. Agrawal and R. Srikant in 1994, aims to identify frequent itemsets in a dataset for boolean association rule mining. Named "Apriori" due to its utilization of prior knowledge regarding frequent itemset properties, this algorithm employs an iterative or level-wise search approach, where k-frequent itemsets are utilized to identify k+1 itemsets.

To enhance the efficiency of the level-wise generation of frequent itemsets, the Apriori property is leveraged, which reduces the search space.

**Apriori Property:** All non-empty subsets of a frequent itemset must also be frequent. The fundamental concept of the Apriori algorithm revolves around the anti-monotonicity of the support measure. Apriori assumes that:

1. All subsets of a frequent itemset must be frequent (Apriori property).
2. If an itemset is infrequent, all of its supersets will also be infrequent.

*Source: GeeksforGeeks*
