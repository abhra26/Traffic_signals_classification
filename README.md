# Traffic_signals_prediction

**Versiion 1.0.0**
**Traffic signals prediction using a CNN model**
*(Computer Vision)*

**MOTIVATION*
Computer vision is a field of artificial intelligence (AI) that enables computers and systems to derive meaningful information from digital images, videos and other visual inputs — and take actions or make recommendations based on that information. If AI enables computers to think, computer vision enables them to see, observe and understand.

Computer vision works much the same as human vision, except humans have a head start. Human sight has the advantage of lifetimes of context to train how to tell objects apart, how far away they are, whether they are moving and whether there is something wrong in an image.

Computer vision trains machines to perform these functions, but it has to do it in much less time with cameras, data and algorithms rather than retinas, optic nerves and a visual cortex. Because a system trained to inspect products or watch a production asset can analyze thousands of products or processes a minute, noticing imperceptible defects or issues, it can quickly surpass human capabilities.

Here a Convulational Neural Network(CNN) has been made to predict which type of traffic signal is the given image showing to a decent accuracy(around 86%). I have here utilized the architechture of VGG19 model(from tensorflow keras). All images used to train the model are of .jpg or of .png format. These images have been convered into a 224 X 224 X 3 numpy array and fed into the model as input.

OUTPUT FORMAT: we obtain an array for each image fed to the model. Each such array contains probabilities of the image being the respective traffic sign. 
