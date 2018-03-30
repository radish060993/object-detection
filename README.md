# My device
Intel® Core™ i7-7700K CPU @ 4.20GHz × 8 
GeForce GTX 1080/PCIe/SSE2
Ubuntu 16.04 LTS

# Dependencies
Tensorlow-gpu 1.6.0
OpenCV 3.4.1

# Download Links

I use [labelImg](https://github.com/tzutalin/labelImg) to label "Arduino Robot Car" & "person" images.  
You can download my custom pre-made labeled images [here](https://goo.gl/PcS5Zs).

After using transfer learning achieved by a pre-trained model for several hours, my object-detector learned my two new objects (i.e., "Arduino Robot Car" & "person"). 

Here is the [file](https://goo.gl/jfdoF2) exported from the result, includes checkpoint data, a saved_model directory, and, most importantly, the forzen_inference_graph.pb. 

NOTE: The model I'm using is "[faster_rcnn_resnet101](https://goo.gl/hYJg6z)." 

