# Anomaly-Detection-in-Wafer-manufacturing

In wafer production Industry, the main goal is to ensure the creation of flawless, high-quality wafers. Imperfect wafers can lead to a range of issues, such as reduced output, increased costs, and potential harm to subsequent processes. Swift identification and resolution of anomalies in the manufacturing process, particularly defects in wafers, are essential for maintaining top-notch products and efficient operations. This task involves detecting faulty wafers in a data-rich production process, often referred to as Industrial Internet of Things (IIoT) data. The complexity of this task is amplified by the rarity of anomalies.


### DATA USED:
(Taken from Kaggle: https://www.kaggle.com/datasets/arbazkhan971/anomaly-detection/data)

Dataset Description:
Train.csv - 1763 rows x 1559 columns
Test.csv - 756 rows x 1558 columns
Attribute Description:
Feature_1 - Feature_1558 - Represents the various attributes that were collected from the
manufacturing machine
Class - (0 or 1) - Represents Good/Anomalous class labels for the products


### APPROACH TAKEN:
In addressing the challenge of anomaly detection in wafer manufacturing, we have chosen to
employ Quantum Neural Networks (QNNs) and Generative Adversarial Networks (GANs) to
explore novel and effective solutions. The rationale behind this choice lies in the unique
capabilities offered by these models in handling complex, high-frequency, and imbalanced
datasets, as well as their potential to mitigate biases inherent in labeled datasets.

### Quantum Neural Networks (QNNs):
QNNs leverage the principles of quantum computing to process information. In the context of
anomaly detection, QNNs offer the advantage of processing vast amounts of high-frequency data
simultaneously, exploiting quantum parallelism. The inherent parallelism of quantum computing
can potentially enhance the model's ability to identify subtle patterns indicative of anomalies in
the manufacturing process. Additionally, QNNs have shown promise in capturing complex
relationships in datasets, making them well-suited for the intricate nature of wafer manufacturing
data.
### Generative Adversarial Networks (GANs):
GANs, consisting of a generator and a discriminator trained in tandem through adversarial
learning, are known for their capability to generate realistic data. In the context of anomaly
detection, GANs can be employed to learn the underlying data distribution and generate
synthetic samples representative of non-anomalous conditions in the manufacturing process. The
discriminator is then tasked with distinguishing between real and generated samples, helping
identify anomalies by recognizing deviations from the learned distribution. GANs provide a
unique perspective on anomaly detection by creating a dynamic interplay between generative and
discriminative processes.

