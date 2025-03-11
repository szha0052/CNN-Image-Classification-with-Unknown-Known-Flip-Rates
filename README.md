# CNN-Image-Classification-with-Unknown-Known-Flip-Rates
CNN-Image Classification with Unknown/Known Flip Rates. 
For each dataset, the training and validation
data contains class-conditional random label noise, whereas the test data is clean.
You need to build at least two different classifiers trained and validated on
the noisy data, which can have a good classification accuracy on the clean test
data. You are required to compare the robustness of the two algorithms to label
noise.
For the first two datasets, the transition matrices are provided. You can directly
use the given transition matrices for designing classifiers that are robust to label
noise.
For the last dataset, the transition matrix is not provided. You are required to
build a transition matrix estimator to estimate the transition matrix. Then,
employ your estimated transition matrix for classification. Your estimated transition matrix must be included in your final report. Note that to validate the
effectiveness of your transition matrix estimator, you could use your estimator on
the first two datasets and compare your estimation to the given transition matrices. 
