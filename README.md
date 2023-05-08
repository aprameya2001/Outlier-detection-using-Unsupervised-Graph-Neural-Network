# Outlier-detection-using-Unsupervised-Graph-Neural-Network
Using unsupervised custom GraphSAGE based neural networks to perform outlier detection

## Overview
Outlier detection plays an important part in various statistical technologies; thus,
accurate outlier detection is necessary for statistics and mathematics. Outliers are
defined as noisy data, and often ignoring the behaviour of such noisy data can cause
statistical models to make wrong decisions in various situations. Thus, there is an
urgent need to devise methodologies to identify and label such data points accu-
rately. Although there are different outlier detection algorithms, such as clustering
algorithms, these algorithms often fail to detect outliers located nearby dense clusters
or hidden among normal data points or objects. Thus, to identify such difficult-to-
find data objects, this paper proposes a novel methodology that employs a graph
neural network model based on GraphSAGE and trained in an unsupervised method.
The proposed methodology creates a graph based on the similarity of data objects
with their neighbourhood and then uses weighted information from the neighbour-
hood in order to learn newer embeddings of the data objects. These new embeddings
learned via unsupervised training make it easier to highlight and identify outliers that
are generally unidentifiable using conventional means. The proposed methodology is
evaluated using eight different datasets from the Outlier Detection DataSets (ODDS)
and results reveal that the proposed methodology outperforms the existing method-
ologies in seven of the eight datasets and sets a new milestone in the field of outlier
detection.
