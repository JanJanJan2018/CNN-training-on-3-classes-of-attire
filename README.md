# CNN-training-on-3-classes-of-attire
uses the photos in the trainCNN and testCNN repositories of this account FOR ORIGINALS
AND FOR THE resized images of 28x42 pixels use the testCNN_resized and the trainCNN_resized
An R script to access the resized to use 


for(i in seq_along(x)){
    download.file(x[i], y[i], mode = "wb")
  }
where x is the vector of file names and x is the vector of new file names to place, there is a limit beyond 60 downloads. The script, SelectPhotosTrainingTestingSetsAutomation.R, in this folder has this function pulled from web with source, but didn't use because of the 429 too many request error.

