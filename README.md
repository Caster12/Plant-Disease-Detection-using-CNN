<h1> Plant Village Disease Detection </h1>

The agricultural sector has served as the backbone of The Indian economy for centuries and over the years this area has witnessed advances and growth. According to the current scenario, plant diseases is one of the main hassle affecting the modern agricultural production pattern. For assessing, analyzing and predicting the effects of plant diseases on crop production, the disease severity index is one of the key metrics. Based on the disease severity value the necessary treatment for plant disease may be recommended which is vital in reducing further yield loss. Most of the traditional approach of assessing the plant disease severity involves a trained expert visually inspecting the plant tissue or specimens, but this process turns out to be time-consuming, expensive, and less efficient. So, it's the right time to come up with disease evaluation systems that could be useful for modern agricultural production. The boom in ML, dissemination of high-quality cameras in mobile devices, and advancements in the field of computer vision allow us to digitize disease assessment techniques. In this paper we have analyzed a multi-class classification of various plant disease over 2 different datasets: PlantVillage and PlantDoc, by using various pre-trained models like VGG16, Xception, InceptionV3, ResNet152, MobileNetV2. We have also analyzed the drawbacks and effectiveness of each dataset and its producibility for using them in real-time detection systems which can be beneficial in reducing losses that we face because of disease outbreaks.

<h2> Models Used: </h2>
<ul>
  <li><b>VGG16:</b> The VGG16 model is a convolutional neural network (CNN) architecture that was developed by A. Zisserman and K. Simonyan. The model proves to achieve an accuracy of 92.7\% over the ImageNet dataset (The ImageNet dataset is a dataset consisting of more than fourteen million images, each belonging to one of the thousand classes). </li>
  <li><b>Xception:</b> Xception model is a CNN architectur. The model consists of 71 layers.  The pretrained version of this network is trained over millions of images from the ImageNet dataset. The pretrained model has the capability of classifying objects into 1000 categories and the model also provides a prolific feature representation for a variety of images.</li>
  <li><b>Inception V3:</b> Inceptionv3 is a convolutional neural network architecture which is used for object detection and image analysis,  this architecture was started as a module for the GoogLeNet architecture. This network is 48 layers deep and the pretrained version is trained over the ImageNet recognition database (consists of millions of images). The dataset can be classified into 1000 classes.</li>
  
  <li><b>ResNet152:</b> The ResNet152 model is a 152 layers deep neural network architecture, the pretrained version is trained over the ImageNet recognition database. The ResNet152 networks outrun the VGG19 network as it works on lesser parameters.</li>
  
  <li><b>MobileNet V2:</b> The MobileNet V2 is a neural network architecture which is an improved version of its predecessor and pushes the state of the art for visual recognition in mobile devices which includes semantic segmentation, object detection, and classification, etc. This architecture uses a depth-wise separable convolution network and also uses various bottlenecks in between multiple layers for image classification.</li>
  
</ul>

<h2> Dataset Used: </h2>
<ul>
  <li><b>Plant Village Dataset:</b> This dataset consists of 54303 (healthy and unhealthy) leaf images which are further divided into 38 categories by species and diseases. The diseased classes includes various bacterial, fungal and viral diseases in food crops like: tomato, potato, corn, bell-pepper, etc. The images in this dataset are taken under a controlled and sophisticated and environment (i.e. images taken using DSLR/High-quality camera with proper lighting conditions).</li>
  <li><b>Plantdoc Dataset:</b> This dataset consists 2,598 which are divided across 13 plant species and 27 classes(10-17, healthy-diseased). The diseased classes includes various bacterial, fungal and viral diseases in food crops like: tomato, potato, corn, bell-pepper, apple, etc. Unlike the PlantVillage dataset, this dataset is taken in a more un-controlled and less sophisticated environment with natural light settings (i.e. Images were taken in real-time using mobile phone cameras). The various classes available in the dataset is shown in Figure below</li>
</ul>





