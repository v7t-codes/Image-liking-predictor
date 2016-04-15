For training ImageData Layer has been used. It takes an input text file which contains multiple lines of
input. Each line contains an image file and an integer representing th class id, separated as a space. It can also
contain transformation parameters to modify the images read before sending them to the output blob. Two
output blobs are generated. The first output blob contains a batch of the images and the second output
blob contains a batch of the corresponding labels. Note that the layer only takes in integer labels. In case
of multidimensional labels, use the HDF5 nput layer.

Use the pycaffe interface to deploy the trained network.
Run the deploy_image_rating.prototxt file.


To learn more about installation and the use of caffe refer to the following links--
http://caffe.berkeleyvision.org/installation.html
other examples 
http://caffe.berkeleyvision.org/gathered/examples/mnist.html
