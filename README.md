# Generative Adversarial Networks (GANs) for Image Generation and CycleGANs for Image Translation
In this project, I explored the power of Generative Adversarial Networks (GANs) and CycleGANs for image generation and image translation.
Specifically, I used the MNIST dataset and colored each digit with a predetermined color, such as red, yellow, etc. 
I then used GANs to generate new images based on the colored digits.

To accomplish this, I first trained a GAN model using PyTorch, and then used it to generate new images of the colored digits.
I also visualized the latent spaces of the model, demonstrating how the GAN can learn to generate new images that look like
they belong to the same distribution as the original dataset.

Next, I used CycleGANs to translate images of digits from one color to another. This involved training two GANs in a cycle, one to translate the colored
digit images from one color to another, and the other to translate them back to their original color. I demonstrated how this approach can be
used to generate new images of digits with colors that belong to other digits, such as a red five or a blue three.

Overall, this project showcases the versatility and power of GANs and CycleGANs for generating and translating images, and highlights their potential
for a wide range of applications, from image manipulation to data augmentation.

<img src="https://user-images.githubusercontent.com/81327428/221792402-a77a36c6-3872-44f4-a965-cbbd2e67741d.png" width="400" height="150">   <img src="https://user-images.githubusercontent.com/81327428/221792909-b2c5aef4-9a23-4318-bde1-94a60504e412.png" width="200" height="150">
