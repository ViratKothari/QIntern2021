## QML for Image Processing

**Mentors:** Viratkumar Kothari [![virat-kothari](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/viratkkothari/) Devang Gajjar [![devang-gajjar](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/devanggajjar/)

Image Classification in computer vision in machine learning is a very famous use case in classical computers. This may be binary or multi-class classification. In binary classification, images are classified in two categories, whereas in multi-class classification, images are classified in more than two categories. In a classical computer, we generally use the Central Processing Unit (CPU) or Graphical Processing Unit (GPU) to solve this problem. The GPU processes data faster compared to the CPU because GPU is better at image processing. Still, processing the data more quickly is always a problem in classical computing.

We want to solve the same image classification problem using quantum computing, assuming it may process the data faster than the GPU. Quantum Machine Learning, also known as QML, integrates quantum algorithms in Machine Learning programs. The QML refers to analysing classical data executed on a quantum computer, i.e. quantum-enhanced machine learning. It is assumed that the specialised algorithm may give better and quicker results on Quantum computers. A famous approach to this is to solve the problem using the Hybrid method, which involves both classical and quantum processing, where computationally difficult things are sent to a quantum device.

We have digital images, which are part of the renowned digital archive. It is envisaged to classify these images using Machine Learning or Quantum Machine Learning. Unfortunately, the archival images may be subject to copyright, so we cannot directly use them in the public domain. But the project can begin using open data available image classification problems at Kaggle, e.g., CIFAR, MNIST, Animal images or Chest X-ray images etc. Then the model obtained using open data may be implemented for the digital archival images. Of course, this may reduce the accuracy, but the model can be once again tuned for the archival images to get better accuracy.
The problem may be solved using various frameworks, including Qiskit, Pennylane, and TensorFlow etc.

### Useful links
1. https://en.wikipedia.org/wiki/Quantum_machine_learning
1. https://qiskit.org/documentation/machine-learning/index.html?highlight=quantum%20machine%20learning
1. https://pennylane.ai/qml/whatisqml.html
1. https://www.tensorflow.org/quantum/concepts
1. https://qiskit.org/textbook/ch-machine-learning/machine-learning-qiskit-pytorch.html
1. https://www.youtube.com/watch?v=OKbcJCUx6xA
1. https://www.youtube.com/watch?v=2g7wIZLbt0I
1. https://towardsdatascience.com/5-quantum-machine-learning-resources-not-to-miss-8aeff7655604
1. https://analyticsindiamag.com/exploring-the-limitations-of-quantum-machine-learning/

### QML frameworks/libraries

Following are few links that may be helpful to understand the Quantum Machine Learning concepts. This also includes few links of similar sample problem which may be useful to solve our image classification problem.

| Description | Link |
| ------ | ------ |
| Qiskit | https://qiskit.org/documentation/machine-learning/index.html?highlight=quantum%20machine%20learning |
| PennyLane | https://pennylane.ai/qml/demonstrations.html |
| Google  AI | https://ai.googleblog.com/2020/03/announcing-tensorflow-quantum-open.html |
| TensorFlow | https://github.com/tensorflow/quantum |

## Tutorials

The following are the links of a few reference projects utilitizing frameworks and libraries like Qiskit and Tensorflow.

### Quantum Machine Learning (QML)

| Title | Link |
| ------ | ------ |
| Qiskit (MNIST) | https://qiskit.org/documentation/machine-learning/tutorials/05_torch_connector.html#Part-2:-MNIST-Classification |
| Qiskit (Simple Classification and Regression) | https://qiskit.org/documentation/machine-learning/tutorials/05_torch_connector.html#Part-1:-Simple-Classification-&-Regression |
| TensorFlow (MNIST) | https://www.tensorflow.org/quantum/tutorials/mnist |

### Classical Computing

The following are the links of a few reference projects for image classification using Classical Computer. This may be useful to understand the concept of image classification.

| Dataset | Asset type | Link |
| ------ | ------ | ------ |
| CIFAR | Notebook | https://www.kaggle.com/viratkothari/image-classification-of-cifar-10-using-tensorflow |
|  | Data | http://www.cs.toronto.edu/~kriz/cifar.html |
| Animals | Notebook | https://www.kaggle.com/viratkothari/image-classification-transfer-learning-resnet50 |
|  | Data | https://www.kaggle.com/viratkothari/animal10 |
| Chest X-Ray | Notebook | https://www.kaggle.com/viratkothari/chest-x-ray-image-classification-using-vgg16 |
|  | Data | https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia |
| Monkey spieces | Notebook | https://www.kaggle.com/viratkothari/monkey-species-image-classification-transfer-vgg16 |
|  | Data | https://www.kaggle.com/slothkong/10-monkey-species |
