# Word embeddings by SVD

- Final Project -- MATH308 McGill University

## Description
- perform the rank-100 SVD approximation on the normalized co-occurrence matrxi $\tilde{M}$
- represents words in vectors
- capture the semantic and syntactic menaing by the singular vectors $u_i/v_i$ in $U/V$
- project some word embedding vectors into some interesting direction
  - e.g. $V = V_{woman} - V_{man}$
- matigate the gender bias of original word embeddings 
- find the most similar word by measuring the cosine-similarity of two words by

$$
d(V_1, V_2) = \frac{V_1^{\top}V_2}{\|V_1\|_2 \|V_2\|_2}
$$

- based on cosine-similaroty, complete the tasks that fills missing words
  - e.g. “man is to woman as king is to ? ”
  - ans: queen
- report the accuracy
- improve the accurancy
 
  
  
