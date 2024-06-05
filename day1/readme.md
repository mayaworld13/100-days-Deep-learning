# Introduction to Deep Learning

Deep learning is a subfield of artificial intelligence (AI) and machine learning that is inspired by the structure and functioning of the human brain. It focuses on using artificial neural networks to learn from data and make predictions or decisions.

### Machine Learning:

- **Definition:** A subfield of AI where systems learn from data to improve their performance on a specific task.

- **Techniques:** Depends on statistical methods and algorithms to find patterns in data.

### Deep Learning:

   - **Definition:** A specialized form of machine learning based on artificial neural networks, which are inspired by the human brain's 
       structure.

   - **Techniques:** Uses multiple layers of neural networks to automatically extract features from raw data.

### Structure of Neural Networks

A typical neural network consists of:

 - Input Layer: Where data is fed into the network.
 - Output Layer: Where the network provides its predictions or classifications.
 - Hidden Layers: Multiple layers between the input and output layers that transform the input into something the output layer can use.

   <p>
            <img src="https://github.com/mayaworld13/100-days-Deep-learning/assets/127987256/d6327031-b88b-43a1-a053-f65198b8a1a9" 
            alt="architecture Diagram" width="700" height="300" />
        </p>


### Types of Neural Networks

1. Artificial Neural Networks (ANNs): General-purpose networks used for various tasks.
2. Convolutional Neural Networks (CNNs): Specialized for image processing.
3. Recurrent Neural Networks (RNNs): Designed for sequential data like speech and text.
4. Generative Adversarial Networks (GANs): Used to generate new data, such as images and text.

### Why Deep Learning is Popular ?
1. Applicability: Deep learning can be applied to a wide range of domains, including computer vision, speech recognition, and chemical analysis.
2. Performance: Often outperforms human experts and has strong support from major software companies.

### How Deep Learning Works
Deep learning algorithms use multiple layers to progressively extract higher-level features from raw input.

For example, in image processing:
- Lower layers might detect edges.
- Higher layers might recognize objects like faces or letters.

### Differences Between Machine Learning and Deep Learning

1. Data Dependency:

    - Deep learning requires a large amount of data to perform well.
    - Machine learning can work effectively with smaller datasets.

       <p>
            <img src="https://github.com/mayaworld13/100-days-Deep-learning/assets/127987256/ead9ccfe-f92d-4610-9823-3f889907b7b0" 
            alt="architecture Diagram" width="700" height="300" />
        </p>

2. Hardware Dependency:

     - Deep learning often requires GPUs (Graphics Processing Units) for training.
     - Machine learning models can run on CPUs (Central Processing Units).

3. Training Time:

      - Deep learning models typically require more training time, sometimes weeks or months.
      - Machine learning models generally train faster.

4. Feature Selection:

   -  Machine learning often requires manual feature selection and engineering.
   -  Deep learning automatically extracts features from raw data.


      <p>
            <img src="https://github.com/mayaworld13/100-days-Deep-learning/assets/127987256/eb7f50fc-ea88-4428-b066-b1507e47e087" 
            alt="architecture Diagram" width="700" height="200" />
        </p>


5. Feature Interpretation:

     - Deep learning models are often seen as "black boxes" and can be difficult to interpret.
     - Machine learning models are usually more interpretable.

### Factors Driving Deep Learning's Popularity

1. Availability of Large Datasets:

   -  The rise of smartphones and internet usage has resulted in an abundance of data.
   -  Public datasets for research, such as Microsoft COCO (images), YouTube (videos), SQuAD (text), and Google Audioset (audio).

2. Advances in Hardware:

    - GPUs and specialized hardware like TPUs (Tensor Processing Units) and NPUs (Neural Processing Units) reduce training time.
    - Application-specific integrated circuits (ASICs) like Edge TPUs for mobile and wearable devices.

3. Frameworks and Libraries:

    - TensorFlow: Developed by Google, powerful but complex.
    - Keras: Simplifies TensorFlow, user-friendly.
    - PyTorch: Developed by Facebook, popular in research for its ease of use.

4. Deep Learning Architectures:

Pre-existing architectures for various tasks, such as ResNet for image classification, BERT for text classification, UNet for image segmentation, and YOLO for object detection.

Starting with Deep Learning

   - Beginner: Use CPU for small-scale projects.
   - Intermediate: Move to GPU or TPU for larger projects.
   - Mobile: Use mobile CPUs, GPUs, DSPs (Digital Signal Processors), or NPUs for smartphone applications.
   - Wearable: Use Edge TPUs or NPUs for smartwatches or smart glasses.

Moore's Law:

The observation that the number of transistors on a microchip doubles approximately every two years, leading to continuous improvements in computing power and efficiency.

Conclusion: 

Both machine learning and deep learning are crucial in AI development, each with its unique strengths and applications. Deep learning has gained significant traction in the past decade due to its ability to handle large datasets, leverage advanced hardware, and utilize robust frameworks and architectures.
