# PCA-UASE-
Source paper: Gallagher, Ian, Andrew Jones, and Patrick Rubin-Delanchy. "Spectral embedding for dynamic networks with stability guarantees." Advances in Neural Information Processing Systems 34 (2021): 10158-10170.

Let Q1=A1+A2+A3+A4, Q2=cbind(A1,A2,A3,A4), we do SVD on Q1=U1%*%diag(d1)%*%V1 and Q2=U2%*%diag(d2)%*%V2, and the PCs for Q1 is P1=U1%*%diag(sqrt(d1)), for Q2 is P2=U2%*%diag(sqrt(d2)). This paper shows that P1 and P2 show the same clusters and have similar predictive performance (similar as PCA regression).
