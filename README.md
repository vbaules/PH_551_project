# PH_551_project
Code for PH 551 project at UA. Code should run/train a GAN to generate supplemental images for brain tumors.

Update 4/23/23: Here are a handful of generated images used for evaluating the DCGAN:

![gen_img_7](https://user-images.githubusercontent.com/68289697/233830815-bda1d9e3-9860-4396-aa30-29f64c60287d.png)
![gen_img_8](https://user-images.githubusercontent.com/68289697/233830818-d123dbb4-96cb-4702-afe9-9ac21c67d39d.png)
![gen_img_9](https://user-images.githubusercontent.com/68289697/233830819-c0d38cb4-b5ad-44e3-9e85-4bec2ce7db11.png)
![gen_img_10](https://user-images.githubusercontent.com/68289697/233830821-d23d90eb-9186-4607-974b-7bc8517f9664.png)
![gen_img_0](https://user-images.githubusercontent.com/68289697/233830823-beff3da1-247e-45e2-9a6d-b9f3c6cff427.png)
![gen_img_1](https://user-images.githubusercontent.com/68289697/233830824-dc5454e3-bb0b-45eb-940a-e0388b136e89.png)
![gen_img_2](https://user-images.githubusercontent.com/68289697/233830825-7dae6cfc-63cb-41c5-96c1-796bc095eb84.png)
![gen_img_3](https://user-images.githubusercontent.com/68289697/233830826-cb1aab0b-b290-45df-8170-557a988ff411.png)
![gen_img_4](https://user-images.githubusercontent.com/68289697/233830827-7c73e3fa-b46c-4b36-8a5e-b52d19740d09.png)
![gen_img_5](https://user-images.githubusercontent.com/68289697/233830828-0d1bc2c7-892b-4cca-9712-26153cc7c0f0.png)
![gen_img_6](https://user-images.githubusercontent.com/68289697/233830831-53d5e988-9672-46a8-968a-c0aa92b3bce1.png)

After implementing the GQI to compare the quality of the images, I found a GQI of 52.364. 
Since the GQI directly compares the accuracy of a classifier trained on the fake images to a classifier trained on the real images, this means that the fake images are low-quality results.

The StyleGAN is still a work-in-progress, and it almost certainly will take a while longer to get working.
