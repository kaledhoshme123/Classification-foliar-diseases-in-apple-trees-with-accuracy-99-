# Classification foliar diseases in apple trees with accuracy 99%
Misdiagnosis of many diseases affecting agricultural crops can lead to chemical misuse resulting in the emergence of resistant pathogenic strains, increased input costs, and more outbreaks leading to significant economic losses and environmental impacts. A structure of a convolutional neural network has been proposed that is capable of diagnosing disease in apple plant leaves. The proposed neural network structure was able to reach an accuracy of more than 99 percent.

![__results___8_0](https://user-images.githubusercontent.com/108609519/193415636-3c4a14ba-5643-41d9-8338-7994221efb21.png)

The study reviewed several different methodologies through which apple leaf disease can be identified, including ("DenseNet CNN", "CNN + XGBOOST", "CNN + Random Forest", "CNN + SVM").
# Dataset Link:
https://www.kaggle.com/competitions/plant-pathology-2020-fgvc7
## Dataset Images Samples:
![__results___11_0](https://user-images.githubusercontent.com/108609519/193414704-533c1ad5-ed91-4d3c-ae67-7243dd42bb98.png)
# Results:
## DenseNet CNN:
![__results___25_1](https://user-images.githubusercontent.com/108609519/193414960-04fd8092-8986-4609-a67f-dcba9c576623.png) 
|  | Test data Evaluation    | confusion matrix    |
| :---:   | :---: | :---: |
| Results | ![image](https://user-images.githubusercontent.com/108609519/193414988-40893805-5762-468c-a110-c7b235cdce16.png)   | ![__results___33_0](https://user-images.githubusercontent.com/108609519/193415340-6d9b207e-1ea8-4c9f-a3cd-3fe2d4f64266.png)   |

## CNN Features + (RandomForest , XGBOOST, SVM):
|  | XGBOOST    | RandomForest    | SVM    |
| :---:   | :---: | :---: | :---: |
| Results | ![__results___49_0](https://user-images.githubusercontent.com/108609519/193415508-cae2bb2a-e664-48d6-9f40-016824bfd123.png)   | ![__results___55_0](https://user-images.githubusercontent.com/108609519/193415531-bca47070-da98-4f87-951e-7c187b234b95.png)   | ![__results___61_0](https://user-images.githubusercontent.com/108609519/193415544-bfd37428-32c5-4e3a-b8a0-93a949317d7d.png)   |
# Final Results:

![image](https://user-images.githubusercontent.com/108609519/193415591-aaeb9a10-a31e-41eb-af78-b884ab622ba6.png)

# Summary

According to the results obtained, neural networks are still able to give better accuracy than the rest of the proposed models.
