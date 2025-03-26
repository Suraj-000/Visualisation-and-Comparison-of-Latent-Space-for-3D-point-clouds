# Learning-Representation-of-Point-Clouds-Towards-Classification

In this paper, we look at geometric data represented
as point clouds. Unsupervised point cloud representation
learning, which aims to learn efficient and compact point
cloud representations from unlabelled point cloud data,
and use them for downstream tasks including 3D points
generation, reconstruction, compression, and clustering.
We propose a Variational Latent Classifier(VLC) for Point
Clouds to learn unsupervised latent representations cap-
turing high-dimensional global geometric vectors and use
them for the task of classification. VLC encodes each input
point cloud as a distribution over the latent space. Point
clouds with similar geometric features typically display re-
semblant latent distributions. We show the impact of these
distributions on pointcloud classification as downstream
task using a simple classifier network. We demonstrate our
analysis on ModelNet40 a benchmark dataset, and compare
with state-of-the-art techniques.
