*COVID vs NonCOVID Image Classification using deep learning techniques*

During my educational pursuit, I had the incredible opportunity to partake in a 120-hour internship at a well-known Artificial Intelligence company. This immersive experience centered around the captivating realm of utilizing Deep Learning-Based Networks to diagnose COVID-19 through CT Scan Images. During the internship, I acquired invaluable knowledge and a profound understanding of the cutting-edge advancements in Machine Learning (ML) and Deep Learning (DL) technologies. 

# Methodology:

As illustrated in the figure below, the workflow for the early diagnosis of coronavirus through the analysis of lung CT scan images comprises three primary stages: data collection and description (Stage 1), data preparation (Stage 2), and the implementation (training) and evaluation of the proposed intelligent models (Stage 3).

![7](https://github.com/miladmasroor/COVID-19-detection/assets/79324919/7802bede-3e7c-41b0-9558-1d9b506526e2)

# Data preparation (Stage 2)

Before applying deep learning and machine learning algorithms, it is crucial to preprocess lung CT scan images. This preprocessing stage aims to prepare the data for training using deep artificial neural networks. In this research, a fundamental step involves the application of edge detection to a collection of lung CT scan images.

Edge detection in CT scan images involves the identification of areas within the image where there are significant changes in light intensity or color. This process is considered a critical and integral step in the realm of CT scan image processing and holds significant importance in various medical applications. Given the pivotal role of edge detection in CT scan images, numerous algorithms have been developed to address this specific task. It is noteworthy to mention that, in this study, we employed Prewitt's algorithm to process the collection of lung CT scan images. The outcomes of applying this algorithm to the set of lung CT scan images are visually presented in the following figure.

![8](https://github.com/miladmasroor/COVID-19-detection/assets/79324919/e5973378-124a-4c4b-a2df-37c7c6a4c127)

# The architectural framework of the straightforward CNN utilized in this project is as follows:

![9](https://github.com/miladmasroor/COVID-19-detection/assets/79324919/76593ef0-1843-4fda-9846-fbf8970e6d37)

