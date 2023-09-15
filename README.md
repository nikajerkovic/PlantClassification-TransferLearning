# Plant Classification Using Transfer Learning

Plant classification system using transfer learning on a custom, unbalanced dataset. The project involves careful model selection and fine-tuning to achieve the best results.

## Dataset

Total Images: 689

Number of Classes: 20

Class with Most Images: 76 images

Class with Fewest Images: 17 images

Data Split: 70% training, 15% validation, 15% testing

Note: We are unable to share the dataset due to copyright restrictions. The images were provided to us by the author of a plant guidebook, which serves as a walking guide in nature.

## Files

### Model_Selection.ipynb

This notebook showcases examples of the dataset images and provides a breakdown of image distribution across classes. The latter part delves into the model selection process, evaluating various pre-trained models to identify the one best suited for our classification task.

### Top_3.ipynb

Here, the top three pre-trained models, as determined from Model_Selection.ipynb, are trained further over additional epochs. Their performances are tracked, aiming to narrow down the most effective model from this trio.

### FineTuneResNet50.ipynb

This notebook trains the top model from our selections. After initial training, we fine-tune it to improve performance on our dataset.
