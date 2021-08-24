# Image-classification-projects


this code is a general pathway to approach any dataset problem concerned with tensorflow
when you have a basic list in python , how to convert it into a pandas dataset. after getting the dataset how to filter, how to scale up or scale down. do we need to batch those huge data sets to smaller ones to handle them within our system specifications.

then comes the herculian task for image reading. its my first image processing project and there may be many efficient way to do that but what i did was i used fatkun batch image downloader extension for chrome and downloaded around 200 cat and dog images. kept them in two separate folders. and placed the folder in the same directory where jupyter notebook code was saved.

then its pretty much same i guess.... spliting the file paths for every images and noting the labels for each image (label here is folder name). then 80% of data was reserved for training our model and remaining 20% was kept for testing purpose.

in the end i have tried to decode jpeg format images ti redable matrix format for computer or python. then to scale down after dividing each number (0-255) by 255 we got numbers (0-1) in the matrix which makes it easy to handle the files.




difficulties i faced : frankly being new to these environments(jupyter notebook) it took me a while to get started. like i had to install tensorflow first to my jupyternotbook.

for that i used "pip install tensorflow". it took a while then it showed some error to install some visual studio and website link was there in the error window. so i installed and restarted my system. then it was fine.





credit - CodeBasics Youtube Channel




