---

## Neural Collaborative Filtering Model with Content-based Support

### Overview

A book recommendation system that harnesses the power of Neural Collaborative Filtering (NCF) complemented by content-based filtering to tackle the cold-start problem. Additionally, this model has the capability to recommend books based on external text queries, enhancing the versatility of the recommendations.

### Features

1. **Neural Collaborative Filtering (NCF)**: Predicts user-book ratings by learning from implicit interactions.
2. **Content-based Filtering**: Provides recommendations based on content similarity, helping to handle scenarios where collaborative data might be sparse.
3. **Cold-start Solution**: For new users or items, the system smartly leverages content-based recommendations ensuring a seamless experience.
4. **Text Query Recommendations**: Users can input textual queries to get book recommendations that align with their immediate interests.

### Implementation

- The NCF model captures the latent factors from implicit user-book interactions.
- Content-based filtering uses keyBert, TF-IDF and cosine similarity to recommend books similar to a given book.
- Hybrid recommendation combines both the NCF and content-based increase reliability.


### Citing

The Neural Collaborative Filtering (NCF) model is based on the following research paper:

```
He, X., Liao, L., Zhang, H., Nie, L., Hu, X., & Chua, T. S. (2017, April). Neural collaborative filtering. In Proceedings of the 26th international conference on world wide web (pp. 173-182).
```
