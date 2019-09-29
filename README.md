# Automatic-Number-Plate-Recognition-System
You can train your own model using the framework.

Folder Structure:
+ annotations: done using labelimg tool contains the xml files in PASCAL VOC format
+ data: contains the input file for the TF object detection API and the label files (csv)
+ images: contains the image data in jpg format
+ training: contains the pipeline configuration file, frozen model and labelmap
- a few handy scripts: generate_tfrecord.py is used to generate the input files
for the TF API and xml_to_csv.py is used to convert the xml files into one csv
- a few jupyter notebooks: draw boxes is used to plot some of the data and
split labels is used to split the full labels into train and test labels
