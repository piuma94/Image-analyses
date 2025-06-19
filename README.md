# Image-analyses
These are two equal pipelines that can be used to analyse tweets (from URL) and images (from file locations) and perform different ML algo. 
Specifically, some algorithms are for object descriptions and others are for object recognition. Overall, each algorithm has its own strengths and weakness. Obviously, this can depend on the labels it was trained on as well as the training. 
resnet-50: https://huggingface.co/microsoft/resnet-50
YOLOS-base: https://huggingface.co/hustvl/yolos-base
VIT-gpt: https://huggingface.co/nlpconnect/vit-gpt2-image-captioning
blip: https://huggingface.co/Salesforce/blip-image-captioning-base
faster CNN: https://pytorch.org/vision/main/models/faster_rcnn.html

The URL pipeline is a bit more sophisticated and it allows handling multiple types of errors deriving from not available URLs and internet connection losses. It also analyse the imagesin batches of 1k to save the results every time. The code can also continue automatically from the previous batch once it is sent again. 

Future improvements may involve a new AI algo: "https://huggingface.co/spaces/gokaygokay/Florence-2"
