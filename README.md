# Sketch-Based-Image-Retrieval : Harkishan Singh (2017233)
Using DenseNet-121, have implemented Sketch Based Image Retrival System (SBIR). The objective of this project is to retrieve the image which is most similar to the provided sketch from the database. I have choosed to DenseNet-121 model because of its compatible size (when comparing with other models). **Siamese Network** is delveloped using the model. To train the model, we feed in a triplet to the model : (s, p, n) where s is for sketch, p is the positive photo (which matches with sketch) and n is a negative photo. Model is trained on 10000 such triplets. Main components of the project could be found at:
- DataSet : https://www.eecs.qmul.ac.uk/~qian/Project_cvpr16.html
- Model I have trained for this project : 

Full project with all the components can be found at : https://www.kaggle.com/harkishansinghkambo/sketch-based-image-retrieval?scriptVersionId=35382246&select=final_model_4.h5
