# NgramPredictor-MapReduceJob
We write three MapReduce jobs to 1. Extract Ngram from WikiPedia data 2. Predict N+1 gram based on N gram  3. Predict words based on prefix

# File explanation:
Aggregate.java: Extract Ngram words and phrases from wiki pedia data from s3://p41-dataset/wiki-dataset. Split words with
non-alphabetic characters. Count the appearence of each Ngram

Predictor.java: Caculate the probability of appearence of each Ngram. The probability is calculated by 
