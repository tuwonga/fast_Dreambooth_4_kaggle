# fast_Dreambooth_4_kaggle
fast_Dreambooth by TheLastBen for kaggle notebook

Hello,
this is a version of fast_Dreambooth by TheLastBen but for using in kaggle notebbok.

It works for me, let me know.

I'm sorry, I'm not skilled in python and scripting so is fisrt time for me but as I said it works and I placed the model.ckpt into automatic111 stable diffusion models folder and everything is fine.

First of all you need an huggingface account to accept terms and use your token to download the stable-diffusion-v1-5 model.

You need an account on kaggle.

You have to create a data set with your images (the IMAGES_FOLDER).

Before running the script you have to activate the data set made before. You can do that on the left side panel with the "+" symbol near your dataset.

In the script you have to input: 

1- your huggingface token

2- instance_name (of course!!!)

3- image folder path (usually under: "/kaggle/input/youraccountname/yourdatasetfolder" or "/kaggle/input/yourdatasetfolder")

4- instance name at the end, in the last lines (instance_name.ckpt) to copy and download the model on local pc.

Of course you can change the steps number and the fp16 option (True or False). 

Please let me know. 

Thank you.

UPDATE > latest version with text encoder training

You can edit the % of text encoder
