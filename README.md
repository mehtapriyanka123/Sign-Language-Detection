# Sign-Language-Detection
Being amateurs we have made a very basic sign language detector, which may not be as good as the other complex and advanced sign language detection project present on the internet but is very easy to understand. A person who has even basic knowledge of machine learning can easily understand what is being done in our code.

In our project we are trying to detect what the person is trying to convey using sign language in a video. The first thing our code does is of shooting a video using webcam from which we save the frames containing the perfect hand gesture are saved in a folder named ‘data’. The folder if not present is being automatically generated (through the code written) at the default PC location.

We further import all the required libraries and the dataset which is also present in the zipped file containing this README word file. We further segregate the dependent and independent variable and get training and testing set using sklearn and then call KNeighborsClassifier algorithm for training and testing. We then train the data and do the predictions. We then do predictions of alphabets in the frames that were saved in the folder called ‘data’.
