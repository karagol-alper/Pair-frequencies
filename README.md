# Pair-frequencies
The "wave function" in this context is not a quantum mechanical wave function, but rather a plot of entropy values: 
WaveFunction = {(i, H(i)) | i = 1 to L}
where L is the length of the sequences. 

Shannon entropy, calculated for each position i:
H(i) = -∑[f(a,i) * log2(f(a,i))]
where H(i) is the entropy at position i, and the sum is taken over all characters a present at that position [1]. 


The representation with Gaussian smoothing offers a continuous view of the frequency distribution, potentially revealing trends that might be less apparent in discrete frequency plots.

# Please cite:
1)	Shannon, C.E. (1948) A Mathematical Theory of Communication. Bell System Technical Journal, 27, 379-423. http://dx.doi.org/10.1002/j.1538-7305.1948.tb01338.x
