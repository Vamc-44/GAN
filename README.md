# GAN
Generative adversarial networks (GANs) are an exciting recent innovation in machine learning. 
GANs are generative models: they createnew data instances that resemble your training data. For example, GANs can create images that look like photographs of human faces, even thoughthe faces don't belong to any real person. 
GANs achieve this level of realism by pairing a generator, which learns to produce the target output, with a discriminator, which learns to distinguish true data from the output of the generator. The generator tries to fool the discriminator, and the discriminator tries to keep from being fooled.

#Generative – To learn a generative model, which describes how data is generated in terms of a probabilistic model. In simple words, it explains how data is generated visually. 

#Adversarial – The training of the model is done in an adversarial setting. 

#Networks – use deep neural networks for training purposes.

![image](https://user-images.githubusercontent.com/91316387/175880242-cd809f8d-1afe-4708-be35-6b8dc8c7d5d6.png)

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



