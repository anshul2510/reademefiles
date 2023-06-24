

**Plant-Disease-Detection using Convolutional neural networks:-**
Plant Disease is necessary for every farmer so we are created Plant disease detection using Deep learning. In which we are using Convoluitona neural Netowork for classifying Leaf images into 39 Different Categories. The Convolutional Neural Code build in Pytorch Framework. For Training we are using Plant village dataset. Dataset is in train_data folder.


**Run Project in your Machine:-**


1. You must have python install in your machine.
2. Create a Python Virutal Environment & Activate Virutal Environment Link
3. We have uploaded a requirements.txt for training the models if you want to run training on your device or modify it.training files are alexnet.ipynb, final densenet training.ipynb, final googlenet.ipynb,final resnet.ipynb, Xception.ipynb.
4. Go to the webapp folder.
5. Install all the dependencies using below command pip install -r requirements.txt. make sure you downloading requiremnts.txt that is inside webapp folder.
6. Run python manage.py runserver in command shell to start project on localhost.
7. If you want to change training file and deploy it on huggingface .
8. create a huggingface space and paste git clone https://huggingface.co/spaces/username/space where you want to create your folder.
9. Put your trained model there . put a requirements.txt like done in alexnet,resnet34 folders.
10. create a app.py folder and modify it accordingly.
11. push it to git and interface will be built on your space link
12. testing data is inside /train_data/test folder and test coding is included in training files.

**Deployed web app link:**
https://finalapp-1p8k.onrender.com/
