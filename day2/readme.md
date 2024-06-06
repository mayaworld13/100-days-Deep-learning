# Types of neural network:


## 1. MLP (Multilayer Perceptron)

   - **Structure**: Consists of an input layer, one or more hidden layers, and an output layer.
   - **Function**: Used for tasks like classification and regression.
   - **Type**: Feedforward, meaning data flows in one direction, from input to output.


     <p>
            <img src="https://github.com/mayaworld13/100-days-Deep-learning/assets/127987256/7a68f146-ed2f-4e3c-b56a-aff71ea4f4b7" 
            alt="architecture Diagram" width="500" height="300" />
        </p>


## 2. CNN (Convolutional Neural Network)

- **Structure**: Includes layers like convolutional layers, pooling layers, and fully connected layers.
- **Function**: Primarily used for image and video processing (e.g., object detection, image recognition).
- **Type**: Feedforward, data moves from input to output in a single direction.
      <p>
            <img src="https://github.com/mayaworld13/100-days-Deep-learning/assets/127987256/85b214c9-6d50-4a90-9a2c-e083c0550826" 
            alt="architecture Diagram" width="600" height="200" />
        </p>

## 3. RNN (Recurrent Neural Network)

- **Structure**: Similar to MLP but with connections that loop back, creating cycles.
- **Function**: Good for sequential data like time series, speech, and text.
- **Type**: Recurrent, meaning it can use information from previous time steps (has memory).
  
     <p>
            <img src="https://github.com/mayaworld13/100-days-Deep-learning/assets/127987256/5508635b-5338-4fdc-8b9e-7df50d0db658" 
            alt="architecture Diagram" width="600" height="300" />
        </p>

## 4. Autoencoder

- **Structure**: An encoder network compresses data into a smaller representation, and a decoder network reconstructs the original data from this compressed version.
- **Function**: Used for tasks like data compression and denoising.
- **Special Feature**: The number of nodes in the middle layer (bottleneck) is less than in the input and output layers, forcing the network to learn efficient encodings.
    <p>
            <img src="https://github.com/mayaworld13/100-days-Deep-learning/assets/127987256/cf756148-a088-4d68-bb9a-8daa5cc4d6d9" 
            alt="architecture Diagram" width="600" height="300" />
        </p>
        
## 5. GAN (Generative Adversarial Network)

- **Structure**: Consists of two networks, a generator and a discriminator, which compete against each other.
- **Function**: The generator creates fake data, and the discriminator tries to distinguish between real and fake data. Used for generating realistic data, like images or music.
- **Special Feature**: Known for its ability to "imagine" or create new, realistic data based on training data.
  
  <p>
            <img src="https://github.com/mayaworld13/100-days-Deep-learning/assets/127987256/9e39f096-ac6f-4771-b15a-bde61596de19" 
            alt="architecture Diagram" width="600" height="300" />
        </p>
