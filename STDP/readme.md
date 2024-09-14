In this project, we aim to classify handwritten digits from the N-MNIST dataset, an event-based variant of the traditional MNIST dataset. The N-MNIST dataset contains asynchronous events captured by event-based vision sensors, which record changes in pixel intensity. We implement a Spiking Neural Network (SNN) using the BindsNET framework and employ two learning algorithms: spike-timing-dependent plasticity (STDP) and Reward-modulated STDP (R-STDP).

In this specific Colab implementation, we are focusing exclusively on STDP to train and evaluate the network. The comparison between STDP and R-STDP will be conducted using the same network architecture, and the results will be included in our final paper.

The models will be evaluated using key metrics such as accuracy and F1-score. This project aims to explore the potential of SNNs in real-time, event-driven tasks, particularly in the classification of handwritten digits.
