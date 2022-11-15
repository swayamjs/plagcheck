# plagcheck

We all know that computers are good with numbers, therefore to compute the similarity between two textual information, the raw text data is processed into vectors, which are simply arrays of numbers, and from there, we will deploy a basic knowledge vector.

# Dependencies

Before you start running with the source code you might need to install dependencies as shown below;

`pip3 install -r requirements.txt`

The dependencies include:

1. **scikit-learn**: *A free software machine learning library in Python prgramming language. It supports clasification, regression and clustering algorithms including support-vector machines, random forests, gradient-boosting, k-learn and DBSCAN, and is designed to interoperate with the Python numerical and scientific libraries NumPy and SciPy.*

2. **TfidVectorizer**: *This is imported from scikit-learn library. It converts a collection of raw documents into a matrix of TF-IDF features.*

3. **cosine_similarity**: *This is also imported from scikit-learn library. It is used as a measure of similarity between two sequences of numbers. The sequences are viewed as vectors in inner product space and cosine similarity is the cosine of the angle between the two vectors.*
