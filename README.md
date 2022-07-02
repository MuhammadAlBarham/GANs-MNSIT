# GANs-MNSIT

In this project, we'll be building a generative adversarial network (GAN) trained on the MNIST dataset. From this, we'll be able to generate new handwritten digits!

GANs were [first reported](https://arxiv.org/abs/1406.2661) on in 2014 from Ian Goodfellow and others in Yoshua Bengio's lab. Since then, GANs have exploded in popularity. Here are a few examples to check out:

- [Pix2Pix](https://affinelayer.com/pixsrv/)
- [CycleGAN & Pix2Pix in PyTorch, Jun-Yan Zhu](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)
- [A list of generative models](https://github.com/wiseodd/generative-models)
    

The idea behind GANs is that you have two networks, a generator 𝐺
and a discriminator 𝐷, competing against each other. The generator makes "fake" data to pass to the discriminator. The discriminator also sees real training data and predicts if the data it's received is real or fake.


### GAN pipeline that is used in this project: 
![gan_pipeline](https://github.com/MuhammadAlBarham/GANs-MNSIT/blob/main/assets/gan_pipeline.png)

### GAN network that is used in this project: 

![GAN_Network](https://github.com/MuhammadAlBarham/GANs-MNSIT/blob/main/assets/gan_network.png)

### Lose of the gradiants output:

![Lose of Generator and Discreminator](https://github.com/MuhammadAlBarham/GANs-MNSIT/blob/main/assets/lose_graph.png)

### The output of the Generator

![Generator Output](https://github.com/MuhammadAlBarham/GANs-MNSIT/blob/main/assets/G_output.png)
