# AI-For-Healthcare
### Proposed a framework for harnessing ML to create Wearable Medical Technology

AI has emerged as a revolutionary force in healthcare, revolutionising the business in a variety of ways. Its incorporation into numerous aspects of healthcare has the potential to improve patient outcomes, streamline operations, and increase overall care quality.

Monitoring and quantifying jaw movements is critical in clinical diagnosis and the evaluation of temporomandibular function and masticatory muscle activity. Nonetheless, present approaches for examining jaw movement sometimes rely on expensive tools, limiting their availability in a variety of geographical areas. This paper describes a novel and cost-effective equipment for measuring the kinematics involved with jaw opening/closing, protrusion, and laterotrusion. The goal of this study is to address the need for low-cost alternatives in clinical evaluations. The suggested device uses an MPU-6050 sensor and a program based on the Arduino Uno platform to precisely collect and recreate the path travelled by a reflective marker affixed to the jaw. The trajectory data is subsequently employed to classify jaw movements into discrete categories. Three machine learning techniques, namely Liquid Neural Network (LNN), K-Nearest Neighbors (KNN), and Long Short-Term Memory (LSTM) are applied for classification applications.



## Project Overview

We conducted clinical research in this project to analyse and categorise mandibular (jaw) motions during the act of eating. The major goal was to use machine learning approaches to increase the accuracy of these categorizations, which could have consequences for a variety of healthcare applications such as dietary assessments, speech therapy, and oral health monitoring.


## Key Highlights

- **Data Enhancement**: We ran into data constraints, but we overcame them by using Generative Adversarial Networks (GANs) to expand our dataset. We were able to improve the resilience and performance of our models as a result of this.

- **Machine Learning Models**: We experimented with various ML algorithms to categorize mandibular motions during eating. Our results were as follows:
    - Liquid Neural Networks (LNN): Achieved an accuracy of %.
    - Long Short-Term Memory (LSTM): Achieved an accuracy of %.
    - k-Nearest Neighbors (KNN): Achieved an accuracy of %.
 
      
The measurement of the chewing movement is conducted by the utilisation of a motion processing unit 6050 motion sensor. A motion sensor is affixed to the surgical mask in the shape of a band. The individual will don the facial covering, and their actions will be captured and afterwards processed by a computer algorithm with the ability to autonomously discern the articulation of the mandible during the act of mastication. The implementation also incorporates the utilisation of a microcontroller and a Bluetooth module. The device exhibited consistent performance for a duration exceeding 18 hours. An Android smartphone was utilised for the purposes of data gathering, annotation, and visualisation.


To mitigate the constraint of a restricted sample dataset, we implemented Generative Adversarial Networks (GANs) as a method of data augmentation. Generative Adversarial
Networks (GANs) represent a category of machine learning models specifically devised to produce synthetic data that exhibits a high degree of similarity to the underlying distribution of the original dataset. Through the utilisation of Generative Adversarial Networks (GANs), we successfully augmented the effective magnitude of our dataset by producing supplementary data instances that exhibit statistical coherence with the original samples. The utilisation of this methodology not only bolstered the resilience of our model but also facilitated the exploration of a broader spectrum of data patterns and variations, ultimately enhancing the efficacy and adaptability of our machine-learning system.

## Conclusion
In our study, we conducted a thorough examination of three different machine learning algorithms utilised for the purpose of classifying jaw movements using trajectory data. Our findings indicate that the Liquid Neural Network (LNN) algorithm demonstrated the highest performance, followed by the Long Short-Term Memory (LSTM) algorithm, and finally the K-Nearest Neighbours (KNN) algorithm.

The Liquid Neural Network (LNN) exhibited remarkable precision and efficacy in the classification of jaw motions, thereby highlighting its capacity to capture complex patterns and temporal relationships inherent in trajectory data. The success of this algorithm underscores its potential for accurate clinical assessments and the examination of dietary patterns, placing it as a promising option for applications that use sequential data.
