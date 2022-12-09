# Machine Learning and Complex Network applied to Sensor Data

This page is about the postdoctoral research project “Learning representations using artificial neural networks and complex networks with applications”. This project aimed to develop new computational approaches for image characterization using machine learning (artificial neural networks) and complex networks with direct application to biosensor and sensor data. This project received funding from São Paulo Research Foundation (FAPESP), grant 2021/07289-2.

## Publications 
Machine learning and image processing to monitor strain and tensile forces with mechanochromic sensors
Reference: LDC de Castro, L Scabini, LC Ribas, OM Bruno, ON Oliveira Jr. Machine learning and image processing to monitor strain and tensile forces with mechanochromic sensors. Expert Systems with Applications 212, 118792

 ![image_mecanossensor](https://user-images.githubusercontent.com/32531959/206627682-b7a3f954-7e93-46aa-a6ff-b7bf4b6e5cb3.png)

 A computer vision (CV) system is proposed for real-time prediction of strain by monitoring the color-changing feature of mechanochromic sensors. Pictures of the sensors subjected to calibration tensile tests were treated with standard image processing methods and analyzed using supervised machine learning (ML) algorithms. Visual strain sensing was demonstrated by linear regression models capable of learning a relation between the applied strain and the reflected structural color. The ElasticNet regression model provided the highest accuracy in the strain prediction task, with a remarkable performance in monitoring real-time strain variation of sensors during a tensile-relaxion cycle. Using calibration curves, the predicted strain can also be employed for estimating the tensile force applied on the mechanochromic sensors. Taken together these results point to potential intelligent systems for noninvasive in-situ visual monitoring of deformations and tensions.


### Data

* The static images are present in this repositoy (folder ‘cropped_images’), as well as the obtained segmentation masks (folder ‘new_masks’). The segmentation process is implemented on “pre_processing.py”. We also make the source code of the machine learning procedure available at: ‘machine_learning.py”.

* The folder 'videos' can be downloaded from the following link: https://drive.google.com/drive/folders/1d0MOzHKdnrv6gAbhlg8sOJOd3puwxmnR?usp=sharing
