# food_101_vision_project
<h3>Abstract</h3>
<p>Much research has been done on the classification of the food101 dataset, but much of this research which achieved an accuracy score of more than 90% explores heavyweight architecture such as EfficientNetB7, Visual Geometry Group19, ResNet-200, Inception v4, DenseNet-201, ResNeXt-101, MobileNet v3 and many more. This study explores the classification of the Food101 dataset using the EfficientNetB0 architecture. The research aims to balance model accuracy and computational efficiency, addressing the need for resource-constrained environments. Results demonstrate that the fine-tuned EfficientNetB0 model achieves an accuracy score of accuracy score of 97.54%, Top_k_categorical accuracy of 99.89%, precision of 98.21%, and recall of 97.02% in just 5 epochs. This research will contribute to advancements in dietary monitoring, food logging, and health-related technologies, enabling more accessible and practical solutions for consumers. The optimal number of layers to fine-tune for achieving perfect accuracy with EfficientNetB0 remains uncertain. It often involves trial and error to determine the best configuration for optimal results, presenting an opportunity for future research.</p>
<img src="food101.jpg" alt="food101" width="800" height="400">
<h3>Summary of the research</h3>
<p>The Food101 dataset is a very popular dataset for demonstrating the potency of transfer learning. Much research has been done on the classification of food101, but those that achieve high accuracy results utilize heavyweight architecture, which requires high computational resources.  The research showed that lightweight convolutional architecture, such as fine-tuned EfficientNetB0 can achieve much better results than most heavyweight architectures. Besides, the research also balanced model accuracy and computational efficiency, addressing the possibility of achieving high-accuracy results in resource-constrained environments in less than 6 epochs.</p>
<p>The food101 dataset used for this research contains 101 food classes, and each class has 1000 images. Five experiments were performed to determine the optimal solution. The first two experiments used 10% of the training data, which achieved an accuracy score of 77.68% in 5 epochs after fine-tuning the last 5 layers. The last three experiments used the entire data. The optimal solution is achieved by fine-tuning the last 100 layers of the EfficientNetB0. The model achieved an accuracy of 97.54% in just 5 epochs.</p>
<p>The research demonstrated the potency of EfficientNetB0 on image classification. It also reveals that it is possible to achieve an accuracy of 100% with lightweight architecture. The major limitation is to determine the optimal number of layers to fine-tune to achieve 100% accuracy with less than 5 epochs, presenting an opportunity for future research.</p>







