# Image-prject
Extraction of Blood vessel in retina
Diabetic retinopathy is a disease, which forms a severe threat on sight. It may reach to blindness among working age people.
By analysing and detecting of vasculature structures in retinal images, we can early detect the diabetes in advanced stages by comparison of its states of retinal blood vessels.
we present blood vessel segmentation approach, which can be used in computer based retinal image analysis to extract the retinal image vessels.
Mathematical morphology and K-means clustering are used to segment the vessels.
To enhance the blood vessels and suppress the background information, we perform smoothing operation on the retinal image using mathematical morphology. 
Then the enhanced image is segmented using K-means clustering algorithm.
The proposed approach is tested on the DRIVE dataset and is compared with alternative approaches.  
  
  

In this project we have applied various techniques for extraction of the blood vessels from the provided image. Eye is one of the most vital organ of human body and any damage or abnormality in it should immediately detected with great efficiency to avoid any technical mistake.  
 	 
So as we can see in the above images the veins are visible in all the extracted images but not all are different:   
•	In Green Channel method we can see a well-defined boundary with sharp edges and no blurs.   
•	In Normal Morphological operation we can see that the number of vessels extracted is more but the sharpness is deteriorated and the image isn’t giving a perfect idea of the vessels   
•	In Kirsch's Templates, we can see that it does a great job at extracting all the boundaries but in turn if even extract unwanted parts of the eye and the sharpness is also decreased  
  
So we can conclude that all the methods have application in various fields but the most appropriate for eye vessel extraction would be the green channel methods as its sole job is too extract only the vein which is red in colour and elliptical in shape which gives it a perfect texture and exact properly  
