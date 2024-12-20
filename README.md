Ultralytics YOLOv8 is the latest version of the YOLO (You Only Look Once) object detection and image segmentation model developed by Ultralytics. The YOLOv8 model is designed to be fast, accurate, and easy to use, making it an excellent choice for a wide range of object detection and image segmentation tasks. It can be trained on large datasets and is capable of running on a variety of hardware platforms, from CPUs to GPUs.

⚠️ Disclaimer
YOLOv8 is still under heavy development. Breaking changes are being introduced almost weekly. We strive to make our YOLOv8 notebooks work with the latest version of the library. Last tests took place on 03.01.2024 with version YOLOv8.0.196.

If you notice that our notebook behaves incorrectly - especially if you experience errors that prevent you from going through the tutorial - don't hesitate! Let us know and open an issue on the Roboflow Notebooks repository.

Accompanying Blog Post
We recommend that you follow along in this notebook while reading the blog post on how to train YOLOv8 Object Detection, concurrently.

Pro Tip: Use GPU Acceleration
If you are running this notebook in Google Colab, navigate to Edit -> Notebook settings -> Hardware accelerator, set it to GPU, and then click Save. This will ensure your notebook uses a GPU, which will significantly speed up model training times.

Steps in this Tutorial
In this tutorial, we are going to cover:

Before you start
Install YOLOv8
CLI Basics
Inference with Pre-trained COCO Model
Roboflow Universe
Preparing a custom dataset
Custom Training
Validate Custom Model
Inference with Custom Model
