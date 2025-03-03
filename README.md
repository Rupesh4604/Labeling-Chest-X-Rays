# Labeling-Chest-X-Rays

**Labeling-Chest-X-Rays** is a deep learning-based project for automatic rib segmentation and labeling in chest X-rays (CXR). Using the **VinDr-RibCXR** dataset, models like **U-Net, U-Net++ with EfficientNet-B0, and FPN** are trained to segment and label 20 ribs. The best model achieves a **Dice score of 0.834**. The approach is also tested on **JSRT** and **Shenzhen** datasets for further analysis. 

### ABSTRACT 

Over the years The Medical procedures had evolved and became so advanced that they can predict the diseases in advance but when we go a little back to make it all possible, It required the study and diagnosis of the symptoms and conditions of the particular diseases and conditions and when it came to study of Lungs, cardio, diagnosing tumors, bone injuries and other respiratory diseases it became evident to study by using X-rays. Chest radiography (chest X-ray or CXR) is an economical and easy-to-use medical imagine and diagnostic technique. The technique is the most commonly used diagnostic tool in medical practice and has an important role in the diagnosis of the lung disease.

The Traditional way of identifying ribs by handpicking is not feasible in the case of identification of anterior bones, thus requiring the technical and analytical solutions, where Deep Learning (DL) has shown superior performance to other methods in the segmentation and labeling of individual ribs. Developing DL algorithms for this task requires annotated images for each rib structure at pixel-level. The Dataset VinDr-RibCXR is used for automatic segmentation and labeling of individual ribs from chest X-ray (CXR) scans. 

- The VinDr-RibCXR contains 245 CXRs with corresponding ground truth annotations provided by human experts. A set of state-of-the-art segmentation models are trained on 196 images from the dataset to segment and label 20 individual ribs. 

- The State-of-the-Art segmentation models like U-Net, U-Net with EffecientNet-B0 ,Feature Pyramid Network (FPN) with EffecientNet-B0, and U-Net++ with EffecientNet-B0 are used for the task .

- Our best performing model obtains a Dice score of 0.834 (95% CI, 0.810{0.853) on an independent test set of 49 images.The same experiment is conducted with other datasets like JSRT and Shenzen and  the results are recorded for further analysis. 

### Results
![RIBS Segmented Output ](Figures/CXR-Visualizer.png)
