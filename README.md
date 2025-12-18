# Apriori-vs-Brute-Force
Project Summary
This project implements two association rule mining methods—Apriori and brute force—to identify frequent itemsets and generate association rules from transactional data. The system is fully coded from scratch in Python and supports user-controlled dataset selection, minimum support thresholds, and minimum confidence thresholds.

The pipeline loads one of five transaction databases, cleans and sorts the data, extracts the universe of items, and then computes itemset frequencies. Users may select the Apriori algorithm, which employs iterative candidate generation and pruning based on the Apriori property, or a brute-force approach, which evaluates all itemset combinations without pruning. Both methods calculate frequent itemsets at increasing sizes and measure support directly from the transaction set.

Association rules are produced for itemsets containing more than one item. For every valid rule, the program evaluates support and confidence values and outputs only those that meet user-defined thresholds. Execution time is recorded to allow efficiency comparisons between Apriori and brute force.

This project demonstrates end-to-end data mining implementation without external machine learning libraries, covering dataset ingestion, itemset generation logic, pruning strategies, rule construction, and performance benchmarking.