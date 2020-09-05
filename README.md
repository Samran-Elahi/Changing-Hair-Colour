# Changing-Hair-Colour
 Our goal was to use conditional GANs to create a model that changes the hair colours.
 
 
 ## Abstract :
 Generative Adversarial Networks (GANs) have been used in many different tasks of
 image to image translation. Our goal was to use conditional GANs to create a model
 that changes the hair colour. We did analysis on Hair GAN[1] and found that it was
 not generalizing well and not giving good results on asian’s so,
 we created our own dataset by using this model and tried different configurations of
 swish activation (introduced by google in 2017) on pix2pix GAN [2] and compared the
 results.
 
 ## Results :
 We found that the best approach is to use swish in the generator of the model pix2pix as it gives more sharp and better results. Following is a comparison of all approaches. 
 The results of simple pix2pix GAN and pix2pix with swish in generator are almost the same and are better then other approaches. 
 
 ![benchmark](https://github.com/Samran-Elahi/Changing-Hair-Colour/blob/master/Capture.PNG)

 
 ## DLP project report :
 contains a detailed description of the project such as the experimental setup , literature review and conclusion.
 
 
 
 
