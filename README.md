## Image Dataset Toolkit
If you work with image datasets and need to perform augmentation and management tasks, this application can significantly simplify your workflow.

I found this application on the GitHub of Yassir Zardoua. You can check out his repository here [Yassir Zardoua GitHub](https://github.com/Zardoua-Yassir/Image-Crops-Annotation__-A-GUI-Application), where he also provides an explanation on how it works through his YouTube channel. It’s a very useful tool for dataset augmentation.

While using it in one of my own projects, I made several improvements and added practical functionalities to enhance usability and efficiency.

**Below are the main enhancements I implemented:**

**Fixed Navigation Issues**
Resolved problems related to the image browsing functionality (Back and Next buttons).

**Generate Patch Button**
Added a button that slides a window over the image (similar to convolution), crops patches, and saves them automatically to a selected destination folder.

**Batch Patch Generation**
Added another button that generates patches for all images in a selected folder and saves them automatically to a selected destination folder — very useful for large datasets.

**Image Flipping**
Added buttons to automatically generate horizontal and vertical flips of selected images and save the results.

**Image Rotation**
Included a feature that allows rotating selected images by a user-defined angle and automatically save the output to a selected destination folder.

**Random Dataset Split**
Added a function to randomly move a selection of images from one folder to another,  helpful for creating random training/testing splits.

This application will save you a lot of time and make your work significantly easier.


## Note on Implementation:

These additional functionalities build upon Yassir Zardoua original implementation, and this repository is published with his express consent
