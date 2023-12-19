# LSE
Project repository for CMPE691-CV project

#### Requrements
* OpenCV
* torch
* matplotlib
* numpy
* pandas
* ultralytics
* sklearn
* Nuscenes

#### Usage
* ```AE_Nuscene_dataset.ipynb```: Import Nuscene-mini-v1.0 dataset and generates the training and testing loss after processing the RADAR point cloud using an autoencoder.
* ```AE_custom_dataset.ipynb```: Generates training and testing loss using the same autoencoder but using the custom collected data-set from Raspi_data directory.
* ```Extract_image_coodinates.ipynb```: Extracts image bounding boxes from the collected data-set and stores them to ```image_xy.csv``` file.
* ```Extract_RADAR_coordinates.ipynb```: Extracts RADAR coordinates from the collected data-set and stores them to ```radar_xy.csv``` file.
* ```Least_squares_custom_dataset.ipynb```: Computes correlation and mean square error among true image x,y coordinates and reconstructed one using least squares estimation.
* ```Least_squares_evaluation.ipynb```: Overlaps the reconstructed image x,y coordinates on landmark images after reading them from ```reconstructed_image_xy.csv``` file.
