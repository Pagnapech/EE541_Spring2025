Major files:
- DataPreprocessing.ipynb
  - unzip and resize the image 
- Custom_CNN.ipynb
  - contains training/validating/testing code 
  - contains preload model for testing
- ResNet34.ipynb 
  - contains fine-tuning/training/validating/testing code
  - generates the best model from the training
- AlexNet.ipynb 
  - contains fine-tuning/training/validating/testing code
  - generates the best model.
  - A function for testing all the images in test set, which visualizes and compares these models'classiyfing performance.


Note: 
- Custom CNN Model file size: 585MB 
- ResNet34 Model file size: 85MB
- AlexNet Model file size: 223MB

Steps for running the model
1. Download traffic sign detection zip folder from Kaggle (https://www.kaggle.com/datasets/pkdarabi/cardetection/data)
2. Run DataPreprocessing.ipynb 
3. For Custom CNN model, run Custom_CNN.ipynb
   - Inside the Custom CNN file, there are a pre-load code that calls custom_cnn.pt for testing 
4. For ResNet34 model, run ResNet34.ipynb 
   - There is only a code for training and generating model
5. For AlexNet model, run AlexNet.ipynb
   - Inside the AlexNet file, there is a pre-load code that calls both A_best_model.pt and R_best_mdoel.pt for testing ResNet and Alexnet.