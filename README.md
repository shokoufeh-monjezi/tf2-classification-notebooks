# tf2-classification-notebooks


## NVIDIA TAO Toolkit on Google Vertex AI
The [NVIDIA TAO Toolkit](https://developer.nvidia.com/tao-toolkit), an AI training toolkit which simplifies the model training and inference optimization process using pretrained models and simple CLI interface. The result is an ultra-streamlined workflow. Bring your own models or use NVIDIA pre-trained models and adapt them to your own real or synthetic data, then optimize for inference throughput. All without needing AI expertise or large training datasets.

TAO Toolkit workflows can be deployed on Google Vertex AI using the Quick Deploy. 

## About Quick Deploy
The quick deploy feature automatically sets up the Vertex AI instance with an optimal configuration, preloads the dependencies, runs the software from NGC without any need to set up the infrastructure.

## TAO Classification-tf2
In this workflow, you will train and optimize an action recognition model using [Classification-tf2](https://catalog.ngc.nvidia.com/orgs/nvidia/teams/tao/models/pretrained_classification_tf2) pretrained model and TAO. 
Object detection is a popular computer vision technique that can detect one or multiple objects in a frame. Object detection will recognize the individual objects in an image and places bounding boxes around the object. This model card contains pre-trained weights for the backbones that may be used as a starting point with the [efficientdet](https://arxiv.org/pdf/1911.09070.pdf) object detection networks in Train Adapt Optimize (TAO) Toolkit to facilitate transfer learning. These models are trained on a subset of the Google OpenImages dataset.More information about this model can be found in [Classification-tf2](https://catalog.ngc.nvidia.com/orgs/nvidia/teams/tao/models/pretrained_classification_tf2) model card.

## Get Started with TAO:
To help you get started, we have created a few Jupyter Notebooks that can be easily deployed on Vertex AI using NGC’s quick deploy feature. This feature automatically sets up the Vertex AI instance with an optimal configuration needed for training the model.

#### Learning Objective
This notebook shows an example use case for classification using the Train Adapt Optimize (TAO) Toolkit.We will be using the pascal VOC dataset for the tutorial.

Simply click on the button that reads “**Deploy to Vertex AI**” and follow the instructions.

*Note*: A customized kernel for the Jupyter Notebook is used as the primary mechanism for deployment. This kernel has been built on the TAO Toolkit container. For more information on the container itself, please refer to this link for more information:

https://catalog.ngc.nvidia.com/orgs/nvidia/teams/tao/containers/tao-toolkit

The container version for this notebooks is **nvcr.io/nvidia/tao/tao-toolkit:4.0.0-pyt**

## License <a class="anchor" name="license"></a>

By pulling and using the TAO Toolkit container, you accept the terms and conditions of these [licenses](https://developer.nvidia.com/tao-toolkit-software-license-agreement).

## Technical blogs <a class="anchor" name="technical_blogs"></a>

- [Train like a ‘pro’ without being an AI expert using TAO AutoML](https://developer.nvidia.com/blog/training-like-an-ai-pro-using-tao-automl/)
- [Developing and Deploying AI-powered Robots with NVIDIA Isaac Sim and NVIDIA TAO](https://developer.nvidia.com/blog/developing-and-deploying-ai-powered-robots-with-nvidia-isaac-sim-and-nvidia-tao/)
- Learn endless ways to adapt and supercharge your AI workflows with TAO - [Whitepaper](https://developer.nvidia.com/tao-toolkit-usecases-whitepaper/1-introduction)

