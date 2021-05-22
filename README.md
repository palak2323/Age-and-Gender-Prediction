# Age-and-Gender-Prediction
A model to predict age and gender
INTRODUCTION 

 

 

Although a new technological advancement, the scope of Deep Learning is expanding exponentially. Deep Learning technology aims to imitate the biological neural network, that is, of the human brain. While the origins of Deep Learning dates back to the 1950s, it is only with the advancement and adoption of Artificial Intelligence and Machine Learning that it came to the limelight. While traditional learning models analyse data using a linear approach, the hierarchical function of Deep Learning systems is designed to process and analyse data in a nonlinear approach. 

Deep Learning architectures like deep neural networks, recurrent neural networks, and deep belief networks have found applications in various fields including natural language processing, computer vision, bioinformatics, speech recognition, audio recognition, machine translation, social network filtering, drug design, and even board game programs. As new advances are being made in this domain, it is helping ML and Deep Learning experts to design innovative and functional Deep Learning projects. 

Automatic age and gender classification has become relevant to an increasing amount of applications, particularly since the rise of social platforms and social media.. With the advancement of technologies new features are added to our current using applications. One of such fun feature is to detect gender and age of a person who faces the camera at any instance. With the help of this project we tried to create a similar experience. In this project an Age and Gender prediction model is build. The basic idea behind this project was to be able to understand the concepts of deep learning and neural networks. 

 For basic training of the model we have used the VGG16 neural network architecture. VGG16 is a convolution neural net (CNN ) architecture which was used to win ILSVR(Imagenet) competition in 2014. It is considered to be one of the excellent vision model architecture till date. Most unique thing about VGG16 is that instead of having a large number of hyper-parameter they focused on having convolution layers of 3x3 filter with a stride 1 and always used same padding and maxpool layer of 2x2 filter of stride 2. It follows this arrangement of convolution and max pool layers consistently throughout the whole architecture. In the end it has 2 FC(fully connected layers) followed by a softmax for output. The 16 in VGG16 refers to it has 16 layers that have weights.
 This network is a pretty large network and it has about 138 million (approx) parameters. 
 

The Adience dataset, published in 2014, contains 26,580 photos across 2,284 subjects with a binary gender label and one label from eight different age groups, partitioned into five splits. The key principle of the data set is to capture the images as close to real world conditions as possible, including all variations in appearance, pose, lighting condition and image quality, to name a few. The dataset was taken from kaggle. Initially there were five text files which were merged during pre-processing. 



STEPS INVOLVED 

 

Importing libraries and dataset:- We need various libraries in order to work in python. Hence loading them is the first step. Also loading our dataset in order to proceed. 

Getting to know the data : Before actually working on a dataset it is very important to know about the data it holds. Various functions are used to find the distribution of data in our dataset. 

Data pre-processing : It is very important to pre-process our data and convert it into a format that can be used in order to continue with our project. 

Splitting dataset : It is important to split data into train and test data in order to minimize the effects of data discrepancies and for better understanding of model. 

Applying VGG16 model for Gender: Then we took a VGG16 model and trained our gender data using this model.  

Applying VGG16 model for Age : Then we took a VGG16 model and trained our age data using this model.  

 Model evaluation: We calculated the accuracy for both models. 

Open CV: For capturing live photos we have used open cv. 

 Creation of GUI: We created a GUI for user to input their images and get a prediction for age and gender of given image.

 


 

CONCLUSION 

 

As we say “What we learn with pleasure, we never forget”, and the joy we had making this project was boundless. 

Our objective to take on this project was to fabricate a working age and gender prediction model. We used VGG16 model in order to make predictions on a given image. Further with the help of GUI we created an interactive page where the user can give inputs (image) and our model foretells the age and gender of the person in that image. Accuracy for our model came out to be 90% for Gender and 59% for Age. Other models were used for the training purpose but accuracy did not came out well. For ResNet to be 40% and Efficient Net to be 50%. So decided to stick to VGG Net only.  

By the end of this project we were able to have a good understanding of how images are processed in neural networks. With the means of this project we also learned how to make a GUI using HTML and further connect it with our python model. With all the knowledge we gained from this project, we now can easily make many more image processing projects.  


 

FUTURE STUDY 

 

As it is said “Knowledge is power - never stop learning”, we aim to do the same. With the means of this project we gained plenty of knowledge, but there is yet a lot to learn. In future we would like to use different models like ResNet, AlexNet, inception model, etc. By using different models our main aim would be to increase the accuracy.  

Another major step we wish to add to our project is to deploy our model on web. 

 
