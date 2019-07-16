# GenderNet
<h1>gender detection and labeling</h1>

  Gender detection and labeling through deep CNN. Here ,I used MTCNN face detector  to obtain the location of the faces in the test image. For further details about MTCNN you can go through https://pypi.org/project/mtcnn/
  
  
![GitHub](/download.png)

<h2>Requirements:</h2>

    1. timesnewarial.ttf file for font in labeling and its path should be (content/timesnewarial.ttf). You can download from http://www.fonts101.com/fonts/view/Fancy/64998/Times_New_Arial
    
    2. Set of images for training and validation.I took
              training images = 1400(man = 700 + woman = 700)
              validation images = 200(man = 100 + woman = 100)
              
    3. Other requirements such as mtcnn , opencv can be installed instantly in our program.
<h3>GenderNet.ipynb</h3>

    1. Installing requirements
    
    2. create directories and uploading images of training and validation set
    
    3. Training
    
    4. upload a new image and predict    
      4.a. upload a new image
      4.b. crop the faces from the new image through mtcnn() face detector and save it
      4.c. predict the faces of two classes(man / woman)
      4.d. draw boundary boxes , label and save it as duplicate image.jpg


