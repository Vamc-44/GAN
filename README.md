# GAN
Generative adversarial networks (GANs) are an exciting recent innovation in machine learning. 
GANs are generative models: they createnew data instances that resemble your training data. For example, GANs can create images that look like photographs of human faces, even thoughthe faces don't belong to any real person. 
GANs achieve this level of realism by pairing a generator, which learns to produce the target output, with a discriminator, which learns to distinguish true data from the output of the generator. The generator tries to fool the discriminator, and the discriminator tries to keep from being fooled.

#Generative – To learn a generative model, which describes how data is generated in terms of a probabilistic model. In simple words, it explains how data is generated visually. 

#Adversarial – The training of the model is done in an adversarial setting. 

#Networks – use deep neural networks for training purposes.

![e169d77e-b6e8-4955-8532-a316baaad637](https://user-images.githubusercontent.com/91316387/175883213-736e77b3-f351-4e64-a727-47d671a6159c.jpg =250x250)

We use GANs to make images with flat shading that resemble cartoon styles, a variety of
methods have been devised. Image filtering or formulations in optimization
problems are used in these strategies. However, capturing complex aesthetic styles
with simple mathematical methods is difficult.Applying uniform filtering or
optimization to the entire image, for example, does not achieve the high-level
abstraction that an artist would achieve, such as making object borders evident


Alternative methods rely on image/video segmentation to increase outcomes, however this comes at the cost of some user interaction. For portraits, dedicated
methods have been developed, in which semantic segmentation can be produced
automatically by detecting facial component

A GAN framework consists of two CNNs. One is the generator G which is
trained to produce output that fools the discriminator. The other is the
discriminator D which classifies whether the image is from the real target
manifold or synthetic. We design the generator and discriminator networks to suit
the particularity of cartoon images

##GENERATOR
<img src= "https://user-images.githubusercontent.com/91316387/175880633-e984bb2c-e011-49e9-9620-9484f3f8e2ef.png" =250x250>

##DISCRIMINATOR
![image](https://user-images.githubusercontent.com/91316387/175880712-1c39d4bf-c7d1-45ee-94a6-0aad09b71714.png =250x250)

RESULTS

sample output of model!
![image](https://user-images.githubusercontent.com/91316387/175880931-472d1882-5437-4ff3-a771-0567ea6b1313.png =250x250)

Results folder will be generated in the process of training the model. What we
have observed in the training process is that the similarity between the animated
image and real image would decrease as the training iterations increase. By increasing the number of iterations the quality of the image also get
increased, which can be observed in the below image samples. The model
randomly pics the images and gives the output of few samples. We expected a
good quality image after 100000 iterations and obtained as well.

Generated image after 10K iterations!
![image](https://user-images.githubusercontent.com/91316387/175881904-70a222fc-e580-413c-995b-de1174aa1759.png =250x250)

Generated image after 100K iterations!
![image](https://user-images.githubusercontent.com/91316387/175881947-98dadab7-0b80-492f-9e69-54f2495d40aa.png =250x250)


#CONCLUSION

We suggested CartoonGAN, a Generative Adversarial Network, in this study
to convert real-world pictures into high-quality cartoon style graphics. Attempting
to recreate We present (1) a method for capturing the faithful properties of cartoon
images.for clear edges, a unique edge-promoting adversarial loss, and
(2) high-level feature maps with a l1 sparse regularisationfor content loss in the
VGG network, which provides enough flexibility for replicating smooth shading
We also present a straightforward but effective initialization phase to assist
enhance convergence. The results reveal that CartoonGAN can learn a model that converts photos of
real-world scenes into cartoon-style images with great quality and efficiency, exceeding state-of-the-art stylization approaches by a wide margin

