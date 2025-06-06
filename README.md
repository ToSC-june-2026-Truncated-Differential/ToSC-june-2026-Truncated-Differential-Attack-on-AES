# ToSC-june-2026-Truncated-Differential-Attack-on-AES

For Proposition 1; 
Before running this code, adjust a random permutation value in the "double compute_divisor()" section according to your desired j using the formula from Remark 1 in the paper.

For Theorem 1;
Before running this code, adjust a random permutation value in the "double compute_divisor()" section according to your desired j using the formula from Remark 1 in the paper.

For Corollary 1;
Before running this code, adjust a random permutation value in the "double compute_divisor()" section according to your desired j using the formula 
(2^{32j-126})*((1-2^{-32})^{j})*((1-2^{-128})^{-1}).

For Theorem 2;
Using the code in this section, you can compute the values of $P^6_{m,2}$ for your chosen m values. Then, using the code in the Corollary1 file, find the corresponding Pr[m->_{6}3] ratio for the same m values. Finally, apply the formula given in Theorem 2 to calculate Pr[m->_{6}2] for each m. 

