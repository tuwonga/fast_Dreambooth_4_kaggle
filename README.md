# fast_Dreambooth_4_kaggle
fast_Dreambooth by TheLastBen for kaggle notebook

Hello,
this is a version of fast_Dreambooth by [TheLastBen](https://github.com/TheLastBen) but for use in a Kaggle Kernel runtime.

It works for me, let me know if you encounter any issues.

I'm sorry, I'm not skilled in python and scripting so is first time for me. As I said, it works; I placed the model.ckpt into AUTOMATIC1111 stable diffusion models folder and everything worked fine.

**Requirements**

1. First of all you need an huggingface account to accept terms and use your token to download the stable-diffusion-v1-5 model.
2. You need an account on kaggle.
3. You have to create a data set with your images (the IMAGES_FOLDER).
4. Before running the script you have to activate the data set made before. You can do that on the left side panel with the "+" symbol near your dataset.

In the script you have to input: 
1. Your [Hugging Face](https://huggingface.co) token
2. instance_name (of course!!!)
3. image folder path (usually under: "/kaggle/input/youraccountname/yourdatasetfolder" or "/kaggle/input/yourdatasetfolder")
4. instance name at the end, in the last lines (instance_name.ckpt) to copy and download the model on local pc.

Of course you can change the steps number and the fp16 option (True or False). 

Please let me know. 

Thank you.

# Changelog
- May 27, 2023: ported the recent version suitable for 1.5 and V2. The repo was edited with stable diffusion V2.1-512 loaded model from huggingface but you can  use whatever you want using the format "profile/model". Please read all the @markdowns in the code.
- Nov 4, 2022: latest version with text encoder training, you can edit the % of text encoder.
- Nov 10, 2022: fp16 option added.
- Nov 18, 2022: please in the last update you have to upload to Kaggle only .png files as dataset and not .jpg
- Nov 28, 2022: fast_dreambooth with SDv2 model added, at the moment I've just tried the V2-512px model and training is working.
- Dec 1, 2022: fast_dreambooth with SDv2 model fixed, latest version.
  - There are still some cell output errors but the code is working. 
