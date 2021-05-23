## Overview of Intel® Distribution of OpenVINO™ Toolkit

AI inference applies capabilities learned after training a neural network to yield results. The [Intel® Distribution of OpenVINO™ toolkit](https://software.intel.com/content/www/us/en/develop/tools/openvino-toolkit.html) enables you to optimize, tune, and run comprehensive AI inference using the included model optimizer and runtime and development tools.

![Image of OpenVino](https://software.intel.com/content/dam/develop/public/us/en/images/diagrams-infographics/diagram-v1openvino-homepage-16x9.png)

## Discover the Capabilities

### High Performance, Deep Learning
Convert and optimize models to achieve high performance for deep-learning inference applications.

### Streamlined Development
Facilitate a smoother development process using the included inference tools for low-precision optimization and media processing, computer vision libraries, and preoptimized kernels.

### Write Once, Deploy Anywhere
Deploy your same application across combinations of host processors, accelerators, and environments, including CPUs, GPUs, VPUs, FPGAs, on-premise and on-device, and in the browser or in the cloud.

## How It Works

### 1. Build
Use the [Open Model Zoo](https://github.com/openvinotoolkit/open_model_zoo) to find open-source, pretrained, and preoptimized models ready for inference, or use your own deep-learning model.

![Image of Build](https://software.intel.com/content/dam/develop/public/us/en/images/diagrams-infographics/diagram-openvino-build-16x9.png.rendition.intel.web.416.234.png)

### 2. Optimize
Run the trained model through the [Model Optimizer](https://docs.openvinotoolkit.org/latest/openvino_docs_MO_DG_Deep_Learning_Model_Optimizer_DevGuide.html) to convert the model to an Intermediate Representation (IR), which is represented in a pair of files (.xml and .bin). These files describe the network topology and contain the weights and biases binary data of the model.

![Image of Optimize](https://software.intel.com/content/dam/develop/public/us/en/images/diagrams-infographics/diagram-openvino-optimize-16x9.png.rendition.intel.web.416.234.png)

### 3. Deploy
Use the [Inference Engine](https://docs.openvinotoolkit.org/latest/openvino_docs_IE_DG_Deep_Learning_Inference_Engine_DevGuide.html) to run inference and output results on multiple processors, accelerators, and environments with a write once, deploy anywhere efficiency.

![Image of Deploy](https://software.intel.com/content/dam/develop/public/us/en/images/diagrams-infographics/diagram-openvino-deploy-16x9.png.rendition.intel.web.416.234.png)
