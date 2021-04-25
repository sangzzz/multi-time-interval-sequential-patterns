ON MINING MULTI-TIME-INTERVAL SEQUENTIAL PATTERNS
-------------------------------------------------    

The paper talks about two algorithm: MI-Apriori and MI-PrefixSpan.
We have made a few runtime optimizations to the two algorithms. The goal of these optimizations is to produce slight  changes in the implementation 
of the algorithms which can drastically affect the runtime and memory utilization of the algorithms as the problem is scaled.

The .ipynb file contains three implementations:
	1. MI-Apriori Implementation based on the Original Paper

	2. MI-Apriori Algorithm - Optimized Implementation based on our Modification 
		This is MI-Apriori with the pruning and candidate generation steps done simultaneously.

	3. MI-PrefixSpan Algorithm - Optimized Implementation based on our Modification
		This replaces the expensive table-generation step by simply iterating through the projected databases.

The .ipynb file has been included in the code folder.
We use synthetic datasets and the algorithm and code for it has been included in the dataset folder.