# Real-Time American Sign Language (ASL) Interpreter
This project uses Python, OpenCV, and TensorFlow to implement and train an unsupervised Real-Time Object Detection Model that can identify and translate American Sign Language (ASL) signs in real-time with up to 91% precision. 

So far, the model has been trained to detect 5 ASL signs: Hello, Thank You, Yes, No, and I Love You. I'm currently working on adding more ASL signs and increasing the number of images per sign to increase the accuracy and precision of the model. 

## Implementation
### Image Collection and Labelling
This project uses OpenCV to capture images and detect signs in real time. The labelImg annotation tool (cloned from `https://github.com/HumanSignal/labelImg` has been used to label and annotate the captured images. To collect and label more images and/or signs, use `Step 1 - Capture and Label Images using OpenCV and labelImg`.
### Training and Testing the Model
The collected and labelled images have been manually split into the `train` and `test` folders. The TensorFlow Model Zoo (cloned from `https://github.com/tensorflow/models`) has been used to train the model. 

## How to Use
1. Clone this repository (`git clone https://github.com/ahorna-c/real-time-ASL-interpreter.git`)
2. Activate the `venv` virtual environment (`source venv/bin/activate`)
3. Execute `Step 2 - Training Model using TensorFlow.ipynb` through Jupyter Notebook. This will enable you to interact with the model through your webcam.  
