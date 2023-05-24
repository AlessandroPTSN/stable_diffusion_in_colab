# Stable diffusion
This project consists of showing step by step the installation and use of stable diffusion, as well as the installation and creation of models and showing very useful applications for the tool, without necessarily having a good computer, all using google colab.

Medium : [Link](https://medium.com/@alessandro.pereira.700/%EF%B8%8F-image-generation-using-neural-networks-3863cb234383) 

![image](https://github.com/AlessandroPTSN/stable_diffusion_in_colab/assets/50224653/dbbb3b15-204c-4195-a228-359158ccc618)

Stable Diffusion is a software that generates images through artificial intelligence fed by an image bank with multiple descriptions used as a reference in the production of new images.

AUTOMATIC1111 (A1111 for short) Stable Diffusion webui is the web interface where users can use stable diffusion on a more user friendly platform.  
You can use AUTOMATIC1111 on Google Colab , Windows or Mac, however, in this repository we will focus on how to use GUI AUTOTMATIC1111 on google colab.

Video of how to adjust the settings: https://www.youtube.com/watch?v=X-mgG79HOZM  
Main Github: https://github.com/nolanaatama/sd-1click-colab  

To use it, just run the stable_in_webui.ipynb file, it already has some models listed, and other models from other sources can be added (such as hugging_face or civitai).  

![toon_alessandrop](https://github.com/AlessandroPTSN/stable_diffusion_in_colab/assets/50224653/d2202c2e-ae35-43f0-8ee1-900972d5586f)



## Traning models

If you want to create your own model, we recommend opening the train_model.ipynb file, it is already configured for creating a custom model.  

Video of how to adjust the settings: https://www.youtube.com/watch?v=UoQIVNjOPsI  
Main Github: https://github.com/Linaqruf/kohya-trainer  

Before training the Lora model, it is necessary to organize our set of images. to be compatible with the notebook we provide, we recommend 20 images, from the birme website, it is possible to cut them to 512x512 pixels, leave them all in jpeg format and download them in zip format.

![image](https://github.com/AlessandroPTSN/stable_diffusion_in_colab/assets/50224653/823f2027-1278-42b4-b3b4-0a48448a608a)

Even though in our tests we had no problems, we strongly recommend using a test account to save the images to the google drive and using the google colab notebooks, see more [here](https://www.reddit.com/r/StableDiffusion/comments/12t8tc7/is_colab_going_to_start_banning_people_who_use_it/)

## About Us
I (Alessandro Pereira) and Angelo Leite  are students of the Postgraduate Program in Electrical and Computer Engineering (PPgEEC) at the Federal University of Rio Grande do Norte (UFRN). As the first project of the EEC2006 - special topics f discipline we made a study on how to setup and what to expect from state-of-the-art Stable Diffusion for generating illustrations and style transfer.
