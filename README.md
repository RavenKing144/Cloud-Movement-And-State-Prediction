# Cloud-Movement-Prediction
<pre>
    •Project is inspired from given research paper
<a href = "https://www.researchgate.net/publication/254048440_Automatically_adjusting_cloud_movement_prediction_model_from_satellite_infrared_images">    Automatically Adjusting Cloud Movement Prediction Model from Satellite .tiff Images</a>
    • Language used–python3
    • Software used–  Google Colab
    • Algorithms Used- Image Segmentation K-Means, Connected component labeling, Adjusted Mean Prediction Model,<br>      Convolutional   L.S.T.M.
    • DataSet is collected from Smart India Hackathon 2020 I.S.R.O. problem statement and are of INSAT3D satellite
    • Formation cloud cluster by image segmentation and the higher cluster center values signifies dense cloud,<br>      finding the center of mass of all the points in cloud cluster and applying the adjusted mean prediction<br>      model to predict the value of the cluster after observing the data-set, after prediction the image of the<br>      cloud cluster is predicted using ConvLSTM. 
    • Mean Square value using basic prediction model = (9.153902775733735 12.212739659131664)
    • Mean Square value using basic adjusted mean prediction model = (5.924637760625794 7.139216633193592)
    •Actual cloud image 
    <img src ="https://github.com/RavenKing144/Cloud-Movement-And-State-Prediction/blob/master/Images/dataset%20sample%20image.png"></img>
    •Actual cloud cluster image 
    <img src ="https://github.com/RavenKing144/Cloud-Movement-And-State-Prediction/blob/master/Images/image%20after%20component%20labeling.png"></img>
    •Actual cloud cluster centroid for given dataset 
    <img src ="https://github.com/RavenKing144/Cloud-Movement-And-State-Prediction/blob/master/Images/actual%20cloud%20cluster%20centroid%20pixel%20value.png"></img>
    •Actual cloud cluster center of mass of dataset
       <img src ="https://github.com/RavenKing144/Cloud-Movement-And-State-Prediction/blob/master/Images/actual%20com%20values.png"></img>
    •Cloud cluster centroid for given dataset by prediction model
    <img src ="https://github.com/RavenKing144/Cloud-Movement-And-State-Prediction/blob/master/Images/cloud%20cluster%20centroid%20image%20by%20prediction%20model.png"></img>
    •Cloud cluster center of mass of dataset by prediction model
       <img src ="https://github.com/RavenKing144/Cloud-Movement-And-State-Prediction/blob/master/Images/prediction%20model%20com%20values.png"></img>
     x-coordinate
    <img src ="https://github.com/RavenKing144/Cloud-Movement-And-State-Prediction/blob/master/Images/x%20coordinate%20comparision%20between%20original%20and%20prediction%20model.png"></img>
     y-coordinate
    <img src ="https://github.com/RavenKing144/Cloud-Movement-And-State-Prediction/blob/master/Images/y%20coordinate%20comparision%20between%20original%20and%20prediction%20model.png"></img>
     •Cloud cluster centroid for given dataset by adjusted mean prediction model
    <img src ="https://github.com/RavenKing144/Cloud-Movement-And-State-Prediction/blob/master/Images/adjusted%20mean%20prediction%20model%20centroid%20value%20of%20cluster.png"></img>
    •Cloud cluster center of mass of dataset by adjusted mean prediction model
       <img src ="https://github.com/RavenKing144/Cloud-Movement-And-State-Prediction/blob/master/Images/adjusted%20mean%20com%20values.png"></img>
     x-coordinate
    <img src ="https://github.com/RavenKing144/Cloud-Movement-And-State-Prediction/blob/master/Images/x%20coordinate%20comparision%20between%20original%20and%20adjusted%20mean%20prediction%20model.png"></img>
     y-coordinate
    <img src ="https://github.com/RavenKing144/Cloud-Movement-And-State-Prediction/blob/master/Images/y%20coordinate%20comparision%20between%20original%20and%20adjusted%20mean%20%20prediction%20model.png"></img>
    •Comparision of actual and 2 predicted model of cluster centroid pixel values
    <img src ="https://github.com/RavenKing144/Cloud-Movement-And-State-Prediction/blob/master/Images/comparision%20of%20centfroid%20of%20cloud%20cluster%5C.png"></img>
    •Comparision of actual and 2 predicted model of cluster center of mass values
    <img src ="https://github.com/RavenKing144/Cloud-Movement-And-State-Prediction/blob/master/Images/comparision%20of%20com.png"></img>
</pre>
