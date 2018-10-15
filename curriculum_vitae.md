# Satyavrat Wagle
200 E. Dana Street, Mountain View, CA 94041 <br />
satyavrat.wagle@west.cmu.edu <br />
+1 650 933 6418 
****
## Profile
Systems Engineer passionate about designing large applications in the domains of Machine Learning and Deep Learning, with a proven ability to work in teams and act as technical lead.

## Education
**Carnegie Mellon University** - Silicon Valley, California <br />
*MS in Electrical and Computer Engineering : 2017 - 2018* <br />
*GPA : 3.7* <br />
 <br />
 **Vishwakarma Institute of Technology** - Pune, India <br />
 *BTech Instrumentation and Control Engineering : 2011 - 2015* <br />
 *GPA : 3.75*
  <br />
  
## Skills
Python (PyTorch, TensorFlow, Keras, Pandas), C/C++ (FreeRTOS, Micropython), Java, R, MatLab, MongoDB

## Work Experience
### Graduate Researcher
*Carnegie Mellon University : Jan 2018 - May 2018 (Moffett Field, CA)*  <br />
* Research Focus : Model Compression of Deep Network Architectures
* Study of compression techniques used on deep learning models for compute gains during inferencing and training
* Implementation of stochastic quantization and encoding of weights to reduce model size by a factor of x5 while sacrificing 3% accuracy (99% - 96%)

<br />

### Graduate Research Assistant
*Carnegie Mellon University - Computations and Communications Group : Jan 2018 - May 2018 (Moffett Field, CA)* <br />
* Worked as part of a team of 3 to design and develop a unified sensing framework for environmental sensors deployed by the US Geological Survey
* Developed a modular dataflow based sensing library in Micropython for real time embedded applications. The Micropython library was then incorporated into FreeRTOS as a callable function which was sensor agnostic.
* Framework was developed and tested on I2C and SDI-12 sensors real time for concurrent sampling up to a frequency of 1 KHz

<br />

### Technical intern
*SciCom Software Pvt Ltd : Jun 2015 - Jul 2016 (Pune Area, India)* <br />
* Worked as part of a team of 3 to design and develop a unified sensing framework for environmental sensors deployed by the US Geological Survey
* Developed a modular dataflow based sensing library in Micropython for real time embedded applications. The Micropython library was then incorporated into FreeRTOS as a callable function which was sensor agnostic.
* Framework was developed and tested on I2C and SDI-12 sensors real time for concurrent sampling up to a frequency of 1 KHz 

## Projects
### Compressed Convolutional Networks for Automobile Speed and Type Identification
  * Quantized CNN architecture to identify automobile speed and type from magnetometer data
  * Dataset : 381 samples, each containing 3 axes of magnetometer data, each of variable length
  * Preprocessing : Dataset augmentation, Filtering, Event detection and windowing
  * Model : Explored convolutional and recurrent models, fixed two networks, each [ 3 Convolutional , 1 Softmax ], also used a network which shared weights up to the second layer with separate embedding layers and sofmax layers for speed and type.
  * Compression : Used stochastic compression to encode the weights to 8-bits
  * Results : 99% Accuracy on full precision models, 96% on stochastically quantized models
  * Future work : Pruning techniques for network, Expand dataset and generalize model
  
### Distributed Neural Networks for Resource Constrained Devices
  * Distributed Neural Network Architecture to separate training and inferencing devices for resource efiicient operation
  * Dataset : 562 samples, each containing 1 temperature and 1 ambient light value
  * Preprocessing : Data smoothening ,window selection ,downsampling
  * Architecture : Remote server for training, weights shared on MQTT broker, ESP8266 for inferencing
  * Model : 4 Layer Fully Connected Network 
  * Results : Finite Response System for dependencies up to 2 days in the past
  * Future work : Accuracy over long term memory, using recurrent models

## Academics
#### Carnegie Mellon University
* 11-785 : Introduction to Deep Learning
* 18-661 : Machine Learning for Engineers
* 18-647 : Cnnected Embedded Systems Architecture
* 18-843 : Mobile and Pervasive Computing
* 18-847 : Wireless Software Systems Architecture
* 18-747 : Wireless Device Architecture
* 18-652 : Foundations of Software Engineering
* 18-990 : Graduate Project

#### Online
* Microsoft : Data Science and Machine Learning Essentials
* UC San Diego : Internet of Things Specialization
* UT Austin : Real Time Networks
* UT Austin : Embedded Systems
* Purdue University : Signal Processing for Embedded Systems

## Interests
