# IAT360_CV_Pest_Classification

 ## Project Idea
 Our project aims to classify five crop pests, supporting pest identification to reduce crop
 damage. With the model, a farmer can quickly identify which pest is affecting their crops
 just by taking a picture, without needing detailed pest maps. Agricultural students can
 also use it to learn about pests in the field.
 This is considered important, as crop pests interfere with the growth of healthy crops,
 leading to decreased supply and higher food prices, negatively affecting agricultural
 workers and consumers alike.
 ## Type of Computer Vision problem
 The problem we are tackling is a supervised classification task.
 ## Data Preparation
 ● We will require labelled images of the target pests.
 ● Our primary data sources will include a labelled crop pest dataset from Kaggle.
 We will also gather more images from Google and label them ourselves. To
 ensure the model generalizes well, we will collect images that vary in lighting,
 angles, backgrounds, and pest sizes.
 ### The model will recognize five types of pests, with the following class labels:
 ■ Ricestem borer
 ■ Greenleafhopper
 ■ Planthopper
 ■ Ricebug
 ■ Riceleaf roller
 ● We won’t annotate the images with bounding boxes, as this annotation is
 unnecessary for a classification problem. Instead, we will organize images into
 dedicated folders for each type of pest and name them appropriately.
 Potential Bias or Ethical Issues
 ● Bias or ethical issues may arise if our dataset does not encompass diverse
 farming conditions across various regions and methods, which could cause bad
 generalization of the model. To mitigate this, we will actively seek diverse
 datasets and ensure our image collection reflects various agricultural practices.
 ● Additionally, there is a risk of misclassifying non-harmful insects as pests, which
 could misinform farmers and lead to unnecessary pesticide use.
## Timeline
 ● Oct. 20- Oct. 25
 ○ Sylvia: Github Repository Setup
 ○ Together: Dataset collection- each collect 30 images and put them into
 their corresponding folder (For the 30 images, 6 for each type of crop
 pest)
 ● Oct. 26- Nov. 2
 ○ Sylvia: Clone the YOLO repository from official Github page
 ○ Together: Integrate our custom dataset into YOLO framework +
 Fine-tuning YOLO model with our dataset + adjusting model’s parameters
 + saving fine tuned model + evaluate accuracy
 ● Nov. 3-Nov. 6 (Final report)
 ○ Jenna: Problem introduction +Dataset report
 ○ Sylvia: Model analysis + Challenges

## References
 ● Crop pest dataset: https://www.kaggle.com/datasets/pialghosh/crop-pest-dataset
 ● Image Annotation tool: https://www.makesense.ai/ 
