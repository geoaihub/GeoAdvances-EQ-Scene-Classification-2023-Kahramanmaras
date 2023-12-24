
# Collapsed and Non-collapsed Building Classification

![GitHub](https://raw.githubusercontent.com/geoaihub/geoaihub/main/assets/Mersin%20GeoAI%20Hub%202.png)

*Picture Source: [GeoAI Hub Mersin](https://github.com/geoaihub)*

## Abstract

This research presents an automated approach for detecting and classifying in high-resolution satellite images, particularly in the aftermath of the Hatay earthquake, utilizing Maxar high-resolution satellite imagery. Advanced deep learning models are employed to identify "collapsed" and "non-collapsed" building classes.

### Architectures  
-  **ResNet-50:** [Details](https://github.com/geoaihub/GeoAdvances-EQ-Scene-Classification-2023-Kahramanmaras/blob/main/collapsed_non_collapsed/ResNet50/collapsed_noncollapsed_ResNet50.ipynb) -  *Summary:* Good accuracy at 77.50%. 
-  **ResNet-50V2:** [Details](https://github.com/geoaihub/GeoAdvances-EQ-Scene-Classification-2023-Kahramanmaras/blob/main/collapsed_non_collapsed/ResNet50V2/collapsed_noncollapsed_ResNet50v2.ipynb) -  *Summary:* Remarkable accuracy at 90.00%. 
- **ResNet-101:** [Details](https://github.com/geoaihub/GeoAdvances-EQ-Scene-Classification-2023-Kahramanmaras/blob/main/collapsed_non_collapsed/ResNet101/collapsed_noncollapsed_ResNet101.ipynb) -  *Summary:* Relatively good accuracy at 75.00%. 
-  **VGG-16:** [Details](https://github.com/geoaihub/GeoAdvances-EQ-Scene-Classification-2023-Kahramanmaras/blob/main/collapsed_non_collapsed/VGG16/collapsed_noncollapsed_VGG16.ipynb) -  *Summary:* Impressive performance at 87.50%. 
- **VGG-19:** [Details](https://github.com/geoaihub/GeoAdvances-EQ-Scene-Classification-2023-Kahramanmaras/blob/main/collapsed_non_collapsed/VGG19/collapsed_noncollapsed_VGG19.ipynb) -  *Summary:* Good accuracy at 85.83%. 
- **DenseNet-169:** [Details](https://github.com/geoaihub/GeoAdvances-EQ-Scene-Classification-2023-Kahramanmaras/blob/main/collapsed_non_collapsed/DenseNet169/collapsed_noncollapsed_DenseNet169.ipynb) -  *Summary:* Impressive accuracy at 88.33%.
- **DenseNet-121:** [Details](https://github.com/geoaihub/GeoAdvances-EQ-Scene-Classification-2023-Kahramanmaras/blob/main/collapsed_non_collapsed/DenseNet121/collapsed_noncollapsed_DenseNet121.ipynb) -  *Summary:* Outstanding accuracy at 93.33%.  
- **MobileNetV2:** [Details](https://github.com/geoaihub/GeoAdvances-EQ-Scene-Classification-2023-Kahramanmaras/blob/main/collapsed_non_collapsed/MobileNetV2/collapsed_noncollapsed_MobileNetV2.ipynb) -  *Summary:* Almost good accuracy at 70.00%.

## ResNet-50

### Abstract

Our ResNet-50 model, meticulously engineered for classifying collapsed and non-collapsed scenes, has demonstrated commendable performance across crucial metrics. Over an extended training process spanning 64 epochs, the model achieved a loss value of 0.4830, underlining its robustness in predictive tasks. The model also demonstrated respectable accuracy, precision, and recall, all reaching 77.50%. These metrics emphasize the model's proficiency in distinguishing between collapsed and non-collapsed scenes.

The F1 score, which harmonizes precision and recall, attained a value of 0.78, indicating the model's ability to effectively manage both true positives and true negatives with a balanced approach.

Employing the softmax activation function and categorical cross-entropy loss function, this ResNet-50 model exhibits its potential in scene classification tasks. Its applications span various domains, including disaster management, urban planning, and infrastructure assessment, where accurate identification of collapsed scenes is of paramount importance.

## ResNet-50V2

### Abstract

Our ResNet-50V2 model, meticulously designed for classifying collapsed and non-collapsed scenes, has demonstrated commendable performance across pivotal metrics. Over an extended training process spanning 64 epochs, the model achieved a loss value of 0.3214, underscoring its stability in predictive tasks. The model also demonstrated impressive accuracy, precision, and recall, all reaching 90.00%. These metrics emphasize the model's proficiency in distinguishing between collapsed and non-collapsed scenes.

The F1 score, which harmonizes precision and recall, reached an outstanding value of 0.90, signifying the model's ability to effectively manage both true positives and true negatives with a balanced approach.  

With the utilization of the softmax activation function and categorical cross-entropy loss function, this ResNet-50V2 model showcases its potential in scene classification tasks. Its applications span various domains, including disaster management, urban planning, and infrastructure assessment, where accurate identification of collapsed scenes is of paramount importance.

## ResNet-101

### Abstract

Our ResNet-101 model, meticulously tailored for classifying collapsed and non-collapsed scenes, has demonstrated respectable performance across essential metrics. Over an extended training process spanning 64 epochs, the model achieved a loss value of 0.5030, underlining its robustness in predictive tasks. The model also demonstrated moderate accuracy, precision, and recall, all reaching 75.00%. These metrics emphasize the model's proficiency in distinguishing between collapsed and non-collapsed scenes.

The F1 score, which harmonizes precision and recall, achieved a value of 0.75, signifying the model's ability to effectively manage both true positives and true negatives.

Employing the softmax activation function and categorical cross-entropy loss function, this ResNet-101 model showcases its potential in scene classification tasks. While its performance is notable, further fine-tuning may be considered in applications where higher accuracy is paramount, such as disaster management and infrastructure assessment.

## VGG-16

### Abstract

Our VGG-16 model, thoughtfully designed for classifying collapsed and non-collapsed scenes, has demonstrated robust performance across pivotal metrics. Over the extended training process spanning 64 epochs, the model achieved a loss value of 0.3453, showcasing its stability in predictive tasks. The model also demonstrated commendable accuracy, precision, and recall, all registering at 87.50%. These metrics underscore the model's proficiency in distinguishing between collapsed and non-collapsed scenes.

The F1 score, which harmonizes precision and recall, achieved a value of 0.88, indicating the model's ability to effectively manage both true positives and true negatives with a balanced approach.

With the utilization of the softmax activation function and categorical cross-entropy loss function, this VGG-16 model exhibits its potential in scene classification tasks. Its applications span various domains, including disaster management, urban planning, and infrastructure assessment, where accurate identification of collapsed scenes is of paramount importance.

## VGG-19

### Abstract

Our VGG-19 model, thoughtfully designed for classifying collapsed and non-collapsed scenes, has demonstrated notable performance across pivotal metrics. Throughout the extended training process of 64 epochs, the model achieved a loss value of 0.3347, showcasing its robustness in predictive tasks. The model also demonstrated commendable accuracy, precision, and recall, all registering at 85.83%. These metrics emphasize the model's proficiency in distinguishing between collapsed and non-collapsed scenes.

The F1 score, which harmonizes precision and recall, achieved a value of 0.86, indicating the model's ability to effectively manage both true positives and true negatives with a balanced approach.

With the utilization of the softmax activation function and categorical cross-entropy loss function, this VGG-19 model exhibits its potential in scene classification tasks. Its applications span various domains, including disaster management, urban planning, and infrastructure assessment, where accurate identification of collapsed scenes is of paramount importance.

## DenseNet-169

### Abstract

Our DenseNet-169 model, meticulously designed for classifying collapsed and non-collapsed scenes, has demonstrated commendable performance across pivotal metrics. Over an extended training process spanning 64 epochs, the model achieved a loss value of 0.4214, underscoring its robustness in predictive tasks. The model also demonstrated impressive accuracy, precision, and recall, all reaching 88.33%. These metrics emphasize the model's proficiency in distinguishing between collapsed and non-collapsed scenes.

The F1 score, which harmonizes precision and recall, reached a notable value of 0.88, indicating the model's ability to effectively manage both true positives and true negatives with a balanced approach.

Employing the softmax activation function and categorical cross-entropy loss function, this DenseNet-169 model showcases its potential in scene classification tasks. Its applications span various domains, including disaster management, urban planning, and infrastructure assessment, where accurate identification of collapsed scenes is of paramount importance.

## DenseNet-121

### Abstract

Our DenseNet-121 model, meticulously engineered for classifying collapsed and non-collapsed scenes, has demonstrated commendable performance across pivotal metrics. Over an extended training process spanning 64 epochs, the model achieved a loss value of 0.1842, underlining its stability in predictive tasks. The model also demonstrated impressive accuracy, precision, and recall, all reaching 93.33%. These metrics emphasize the model's proficiency in distinguishing between collapsed and non-collapsed scenes.

The F1 score, which harmonizes precision and recall, attained a value of 0.93, signifying the model's ability to effectively manage both true positives and true negatives with a balanced approach.

Employing the softmax activation function and categorical cross-entropy loss function, this DenseNet-121 model showcases its potential in scene classification tasks. Its applications span various domains, including disaster management, urban planning, and infrastructure assessment, where accurate identification of collapsed scenes is of paramount importance.

## MobileNetV2

### Abstract

Our MobileNetV2 model, thoughtfully crafted for classifying collapsed and non-collapsed scenes, has demonstrated commendable performance across pivotal metrics. Over an extended training process spanning 64 epochs, the model achieved a loss value of 1.0641, underscoring its stability in predictive tasks. The model also demonstrated respectable accuracy, precision, and recall, all reaching 70.00%. These metrics emphasize the model's proficiency in distinguishing between collapsed and non-collapsed scenes.

The F1 score, which harmonizes precision and recall, achieved a respectable value of 0.70, signifying the model's ability to effectively manage both true positives and true negatives with a balanced approach.

With the utilization of the softmax activation function and categorical cross-entropy loss function, this MobileNetV2 model showcases its potential in scene classification tasks. Its applications span various domains, including disaster management, urban planning, and infrastructure assessment, where accurate identification of collapsed scenes is of paramount importance.

## Objective

The objective of this project is to develop a deep learning model for classifying high-resolution satellite images into "collapsed" and "non-collapsed" categories using various advanced architectures. The model aims to achieve high accuracy in identifying structural damage in satellite imagery, particularly in post-earthquake scenarios. Through this project, we aim to demonstrate the effectiveness of deep learning in image classification tasks and its application in real-world disaster response scenarios.
