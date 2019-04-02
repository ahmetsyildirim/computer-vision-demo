Welcome to the computer-vision-demo wiki!
# computer-vision-demo
Demo Images for Azure AI Computer Vision demo

In order to do this workshop, you need an Azure subscription and a resource group created.
Steps for the demo
1- Sign in to https://www.customvision.ai/
2- Create a new project
  a- Provide a name for your project
  b- Select your resource group
  c- Project Type: Classification
  d- Classification Types: Multilabel
  e- Domains: General (compact)
  f- Click Create Project
3- Click add an image.
  a- Select one of the images from the train folder.
  b- After selecting the image you will see a thumbnail.
  c- Depending on the image add one of the tags which are suitable for this image
    (forest, smoke, fire)
  d- Upload the image.
  e- Repeat the steps until you upload and tag all images under the train folder.
 4- Click Train. It will take some time the train does its work.
 5- After the training is finished, Click the test button on the top right side.
 6- In the test screen you can upload images from the test folder to see how good your model is.
 
 Exporting the model.
 Select the Performance tab from the top of the screen.
 Click Docker.
 Select Linux
 Wait for the image creation to finish.
 Download your image.
 Extract the image to a folder in your computer.
 Follow the steps README.txt file to build and run the docker image
