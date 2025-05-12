# Using MRI for Brain Tumor Detection and Segmentation
**Authors:** Isha Dev, Dharvi Jagirdar, Rohan Giridharan

This is the repository containing the code for the Machine Learning for Medical Applications Spring 2025 final project group working on: Using MRI for Brain Tumor Detection and Segmentation.

This work presents an Attention UNet model for brain tumor segmentation using the BraTS 2020 Challenge dataset. Using different MRI modalitied, out model leverages attention gates to enhance focus on tumor-relevant features and regions. A DDPM pipeline generates synthetic MRI data to augment UNet training for improved performance and generalization. Additionally, model outputs are passed to the Radiology Infer-Mini LLM to generate structured clinical reports to provide diagnostic and prognostic support, and increase interpretibility while aiming to reduce radiologist and physician cognitive load.
