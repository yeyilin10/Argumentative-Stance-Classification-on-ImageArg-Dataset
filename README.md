# Argumentative Stance Classification on ImageArg Datasets

In this project, we focused on classifying the argumentative stance of tweets about gun control and abortion using both text and image data. We proposed two multimodal fusion approaches: decision-level fusion and feature-level fusion. Our feature-level fusion method outperformed the decision-level approach, achieving higher F1 scores of 0.85 for abortion and 0.8 for gun control. This demonstrates the effectiveness of our approach in enhancing classification accuracy for this specific task.


## Resources
- `data`: Contains the ImageArg dataset (to download the images, follow the instruction here: [imageArg](https://imagearg.github.io)).
- This Repository contain only code for pure images classification for both datasets with VGG16.
  - `ImageArg_VGG16(abortion).ipynb`: image classficiation on Abortion datasets
  - `ImageArg_VGG16(gun).ipynb`: image classficiation on Gun Control datasets


## Conclusion
Our project demonstrates the effectiveness of multimodal fusion techniques for argumentative stance classification using the ImageArg dataset. We achieved improved performance compared to baselines, highlighting the importance of considering both text and image modalities in persuasive communication analysis.

Please refer to the paper (`5018_Group_Project_paper.pdf`) for more detailed information about our methodologies, related work, experiments, and results.
