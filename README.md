# Leveraging-Zero-Shot-Learning-and-Generative-Adversarial-Networks-for-Plant-Disease-Classification
# Plant Disease Detection Project

## Overview

This repository contains code for a comprehensive plant disease detection system. The project involves multiple interrelated code files for preprocessing, image generation, counting, frame splitting, similarity index computation, segmentation, augmentation, and transfer learning.

## Files Description

1. **Preprocessed.py:**
   Converts dataset images to numpy format for further processing.

2. **styleGan.py or dcgan.py:**
   Generates synthetic images using GANs if the training dataset is small or classes are imbalanced.

3. **count.py:**
   Counts images in a specified folder.

4. **splitFrames.py:**
   Splits frames into images generated from GAN Python files in the Results Folder.

5. **ssim.py:**
   Utilizes structural similarity index to extract the best synthetic images resembling the training dataset.

6. **segmented.py and segmented2.py:**
   Implements segmentation techniques.

7. **augmentation.py:**
   Applies augmentation techniques for testing against diverse datasets.

8. **transferLearning.py:**
   Main file providing accuracy for 12 models over 25 epochs, using preprocessed data and incorporating all techniques mentioned.

## Usage

To run the project, follow these steps:

1. Execute `Preprocessed.py` to convert dataset images.
2. Use `styleGan.py` or `dcgan.py` for synthetic image generation if needed.
3. Run `count.py` to count images and `splitFrames.py` to split frames.
4. Apply `ssim.py` for similarity index computation.
5. Utilize `segmented.py` and `segmented2.py` for segmentation.
6. Employ `augmentation.py` for additional testing techniques.
7. Finally, execute `transferLearning.py` to assess accuracy over 25 epochs.

## License

This project is licensed under the [MIT License](LICENSE).
