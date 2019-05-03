# Intro
<img src="resources/preview.jpg">

This repository is a beginner's workshop for SJSU ML Club. It introduces members to deep learning classification in PyTorch. [This presentation](https://docs.google.com/presentation/d/1errQMusyaSrnrAcpmkTsY9CNGaJGlebwbI9NI0z-EWI/present) includes accompanying info.

# Installation and Setup

##### 1: Install Python

https://www.python.org/downloads/. Find Python installation help [here](https://docs.google.com/presentation/d/1errQMusyaSrnrAcpmkTsY9CNGaJGlebwbI9NI0z-EWI/present#slide=id.g58ced36789_0_233).

##### 2: Install prerequisite dependencies
Copy-paste this into your command line:
```
pip3 install numpy jupyter matplotlib pillow tqdm
```

##### 3: Install PyTorch! https://pytorch.org/get-started/locally/

Make sure to run the command appropriate for your system. Navigate to the website and select your options. Most people should choose "Pip" as their Package manager for this tutorial. If you don't have a GPU, select "None" under "CUDA".

<img src="resources/Pytorch_logo.png" width="300">
<img src="resources/install_pytorch_mac_cpu.png" width="800">



##### 4: Open this interactive Notebook on your computer!
In command line:
```bash
git clone https://github.com/sjsumlclub/workshop-chihuahua-vs-muffin.git
cd workshop-chihuahua-vs-muffin
jupyter notebook
```

Once your browser window opens, select the notebook:

<img src="resources/select_notebook.png">

Alternatively, select `workshop_1_output.ipynb` to see a version with all cells executed.

# Challenge
The default settings purposely perform non-optimally! Can you modify the notebook to get 100% accuracy?

# Credits
This workshop is based on code from the [tutorial by deepsense.ai](https://deepsense.ai/keras-vs-pytorch-avp-transfer-learning/), and was further modified by Andrew Jong, Jing Zhao, and Jason Do.
