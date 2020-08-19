# Sketch-Based-Image-Retrieval : Harkishan Singh (2017233)
Using DenseNet-121, Sketch Based Image Retrival System (SBIR) is implemented. The objective of this project is to retrieve the image which is most similar to the provided sketch from the database. I have choosed to train DenseNet-121 model because of its compatible size (when comparing with other models). **Siamese Network** is delveloped using the model. To train the model, we feed in a triplet to the model : (s, p, n) where s is the sketch, p is the positive photo (which matches with sketch) and n is a negative photo. Model is trained on 10000 such triplets. It is advisable to have GPU on your computer (or you can use online free GPU's : kaggle)

Main components of the project could be found at:
- DataSet : https://www.eecs.qmul.ac.uk/~qian/Project_cvpr16.html
- Model I have trained for this project : https://drive.google.com/file/d/1hZ7mZpXMP1hcyN2oD5XrmEYM2RZC9Dvg/view?usp=sharing

Full project with all the components can be found at : https://www.kaggle.com/harkishansinghkambo/sketch-based-image-retrieval?scriptVersionId=35382246&select=final_model_4.h5
