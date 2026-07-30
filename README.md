# EPP_EOI_FinalProject_Franke

Welcome to the GitHub Repository the deep learning portion of the EOI Final Project from Spring/Summer 2026. Within this repository are two Google Colab notebooks which train and run predictions on NAIP imagery using the HRPlanes dataset as training data and utilizing a YOLOv11 (medium) model architecture. The purpose of these notebooks were to employ YOLOv11 to detect aircraft objects in closed airports throughout the Northeastern United States of America. 

The HRPlanes and OurAirports datasets that were used for this analysis are required to be uploaded into the users Google Drive for the Google Colab notebooks to work properly. Additionally, the notebooks utilize the GEE/Colab connection, requiring the replicator to have a Google Earth Engine account and active project. 

To summarize what the two notebooks create, the first one unpacks the HRPlanes dataset, trains on the training data, and runs validation tests and predictions on the test split. The second notebook uploads the weights from the training process and uses the pretrained model to make predictions on several NAIP chips which are at the locations of closed airports in the Northeastern United States. The goal of the model was to identify abandoned aircraft at the closed airports, in which there are not many. 

Credit to HRPlanes and OurAirports for the data, and their websites are linked below. 
https://github.com/TolgaBkm/HRPlanes
https://ourairports.com/
