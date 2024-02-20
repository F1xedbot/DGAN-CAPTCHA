# DGAN-CAPTCHA

## Overview
DGAN-CAPTCHA is a project focused on developing a model that generates captchas challenging for robots or captcha-reading models to decipher while ensuring readability for humans. The model has achieved a notable 68% accuracy in generating complex and human-readable captchas and a commendable 70% success rate in evading generic text recognition models. Employing a Deep Conditional Generative Adversarial Network (DCGAN) and utilizing the captcha dataset [yzm](https://github.com/aceimnorstuvwxz/captcha-dataset/blob/master/yzm1.tar.gz), this project delivers unique captchas effective against automated reading tools.

## Results
- Captcha generated from a generic GAN model trained on the yzm dataset at 100 epochs
  ![Generic Captcha](https://github.com/F1xedbot/DGAN-CAPTCHA/blob/60cdd338a4a0e7f2d27c51a690d21d889bc9e54c/image_at_epoch_100.png?raw=true)
- Captcha generated from DCGAN trained on the yzm dataset at 50 epochs
  ![DCGAN Captcha]()

## Project Structure
Within the project, two folders are present:
- **Model Folder:** Contains notebooks for data preprocessing on the yzm datasets and code for implementing and training the main model.
- **Weights Folder:** Stores the weights for the generator and discriminator for simplified testing and integration.

Explore the preprocessed dataset for training the model [here](https://drive.google.com/drive/folders/1cU2bmPF3xwJd7Ho9DNFZMFdGqicKydKc?usp=sharing)

Feel free to explore, contribute, and enhance the DGAN-CAPTCHA project for improved captcha generation and increased security against automated recognition tools.
