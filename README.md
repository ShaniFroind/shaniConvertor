#shaniConvert project

 This is a python application which gets images and creates a PDF file in a folder called “output” with all the images printed in it.
 
 ## Build

 docker build -t pythonproject11 .

 ##Run

docker run --name CONTAINER_NAME -v $PWD/images:/app/images -v $PWD/output:/app/output --rm pythonproject11 -e PDF_NAME=YOUR_PDF_NAME pythonproject11
