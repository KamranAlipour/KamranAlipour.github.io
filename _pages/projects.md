---
layout: archive
title: "Selected Projects"
permalink: /projects/
author_profile: true
---

## Glaucoma Detection Made Smarter: Using Transformers for Improved Generalization

Our paper proposes a novel approach for glaucoma detection from fundus photographs using deep learning without convolutions. We introduce a transformer-based architecture, which is typically used in natural language processing tasks, but has shown promising results for image classification tasks as well. Our approach aims to improve generalization across different datasets, which is crucial for deploying such models in real-world settings.

We evaluated our approach on two publicly available datasets of fundus photographs and achieved competitive results compared to state-of-the-art methods, with AUCs of 0.952 and 0.973, respectively. Our findings suggest that transformer-based models have the potential to enhance medical image analysis tasks and may pave the way for future research in this area.

![Alt text](/images/glaucoma_transformer_paper_schema.png)


## Visualizing the Mind of an AI: Generating Plausible Counterfactual Explanations for Image Classifiers

In this project, we propose a novel approach for explaining image classifiers using contrastive counterfactuals generated in generative latent spaces. Our method provides interpretable explanations for the predictions made by an image classifier, particularly in cases where the classifier's decision is unclear or counterintuitive.

To achieve this, we use a generative adversarial network (GAN) to map input images to a lower-dimensional latent space. We then generate a set of plausible counterfactual images in this space that lead to different classifier predictions. We present the counterfactual images to human evaluators to obtain feedback on their plausibility and usefulness as explanations.

Our approach has significant implications for AI and machine learning, as it can improve the interpretability and transparency of image classifiers. It can be applied to a wide range of applications, including medical image analysis, autonomous driving, and security. Notably, our method outperforms existing explanation methods, demonstrating the potential for generative models and counterfactual reasoning to advance the field of AI.

![Alt text](/images/latent_counterfactual_teaser_LQ.gif)


## Seeing More Clearly with AI: Enhancing Photoacoustic Imaging in Low-Fluence Conditions


In this project, we present a novel deep learning approach to enhance the contrast of photoacoustic imaging in low-fluence conditions. Our method employs convolutional neural networks (CNNs) and transfer learning techniques to adapt to the unique features of photoacoustic imaging and optimize the model's performance.

Our results demonstrate the potential of our approach to significantly improve the quality and accuracy of photoacoustic imaging, which has important implications for medical imaging and AI more broadly. Our method outperforms existing approaches in terms of both contrast enhancement and computational efficiency, and we believe it has promising applications in a variety of fields, including cancer detection, drug development, and neuroscience research.

Overall, we believe that our work showcases the power of deep learning to advance medical imaging and provides exciting opportunities for future research in this area. We are confident that our work will be of great interest to anyone interested in AI and its applications in healthcare.

![Alt text](/images/photoacoustic_paper_results.png)