# Finding Textually Similar Documents using Jaccard similarity, Shingling, Minhashing and LSH

<p align="justify">I implemented the stages of finding textually similar documents based on Jaccard similarity using the shingling, minhashing, and locality-sensitive hashing (LSH) techniques and corresponding algorithms. The algorithm was implemented in the following steps:

<b>Step 1: </b> Shingling was implemented that constructs k–shingles of a given length k (e.g., 10) from a given document, computes a hash value for each unique shingle, and represents the document in the form of an ordered set of its hashed k-shingles.

<b>Step 2: </b> CompareSets that computes the Jaccard similarity of two sets of integers–two sets of hashed shingles.

<b>Step 3: </b> MinHashing that builds a minHash signature (in the form of a vector or a set) of a given length n from a given set of integers (a set of hashed shingles).

<b>Step 4: </b> CompareSignatures that estimates similarity of two integer vectors – minhash signatures – as a fraction of components, in which they agree. (Optional task for extra 2 bonus) A class LSH that implements the LSH technique: given a collection of minhash signatures (integer vectors) and a similarity threshold t, the LSH class (using banding and hashing) finds candidate pairs of signatures agreeing on at least fraction t of their components.

</p>

![](https://github.com/alexanderbea/Finding-Textually-Similar-Documents-using-Jaccard-similarity-shingling-minhashing-and-LSH/blob/main/Images/Figure%201.PNG)
