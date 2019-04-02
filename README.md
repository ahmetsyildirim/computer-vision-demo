# computer-vision-demo
Demo Images for Azure AI Computer Vision demo

In order to do this workshop you need an azure subscription and a resource group created.
Steps for the demo
1- Sign in to https://www.customvision.ai/
2- Create a new project
  a- Provide a name for your project
  b- Select your resource group
  c- Project Type: Classification
  d- Classification Types: Multilabel
  e- Domains : General (compact)
  f- Click Create Project
3- Click add image.
  a- Select one of the images from the train folder.
  b- After selecting the image you will se a thumbnail.
  c- Depending on the image add one of the tags which are suitable for this image
    (forest, smoke, fire)
  d- Upload the image.
  e- Repeate the steps until you upload and tag all images under the train folder.
 4- Click Train. It will take sometime the train does its work.
 5- After the training is finished, Click test button on the top right side.
 6- In the test screen you can upload images from test folder to see how good your model is.
 
 Exporting the model.
 Select the perofmance tab fromt he top of the screen.
 Click Docker.
 Select Linux
 Wait for the image creation to finish.
 Download your image.
 Extract the image to a folder in your computer.
 Follow the steps README.txt file to build and run the docker image
