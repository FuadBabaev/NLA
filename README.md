# Advanced Numerical Linear Algebra Projects

This repository contains advanced projects related to numerical linear algebra methods, with both analytical and numerical implementations.

## Project Descriptions

### Advanced NLA Problems 1
This notebook contains analytical and numerical implementations of methods that accelerate QR decomposition.

### Advanced NLA Problems 2
This notebook contains:
- Analysis of PLU decomposition
- Implementation and analysis of the Anderson acceleration technique

### Fast SVD
This notebook contains the implementation of a fast SVD update algorithm.

It is assumed that using the fast SVD update technique will significantly reduce the time required to integrate new information and improve the scalability of recommendation systems. We used the MovieLens 10M dataset, which consists of recorded user interactions with movies offered by the service. Our goal was to learn how to create recommendations for new users or recommend new movies without recalculating the full SVD decomposition.

## References
- Brand, M. (2006). Fast low-rank modifications of the thin singular value decomposition. *Linear Algebra and its Applications, 415*, 20–30. [doi: 10.1016/j.laa.2005.07.021](https://doi.org/10.1016/j.laa.2005.07.021)
- Gu, M. & Eisenstat, S. C. (1993). A Stable and Fast Algorithm for Updating the Singular Value Decomposition. *Yale University*.
- Stange, P. (2009). On the Efficient Update of the Singular Value Decomposition Subject to Rank-One Modifications. *PAMM*, [doi: 10.1002/pamm.200810827](https://doi.org/10.1002/pamm.200810827)
- Zhou, X., He, J., Huang, G., & Zhang, Y. (2015). SVD-based incremental approaches for recommender systems. *Journal of Computer and System Sciences, 81(4)*, 717–733. [doi: 10.1016/j.jcss.2014.11.016](https://doi.org/10.1016/j.jcss.2014.11.016)