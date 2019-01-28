# Gallery_Redefined

The condition of our phone gallery is really unappetizing as everything is so jumbled up. It is really difficult for us to search for our notes in our gallery, and deleting them becomes even more annoying. This problem can be solved using deep learning. This project divides all the existing images in a folder in two categories notes and others. I have implemented this in python, using OpenCV for pre-processing of data and Keras library (using Tensorflow backend) for training the model.

You can use your own test and train data which should be labelled as notes.1,notes.2, others.1,others.2 and so on.

For final testing on a folder you just need to mention the path of the folder and create 2 new paths which will be just the same as the previous path only the name of the folder in this path will be changed to notes_new for the first new path and others_new for the second new path.
