# Segment Anything Model Demo for Images and Videos
This is a demonstration of Meta's (Facebook) Segment Anything Model (SAM) which enables promptable segmentation yielding high-quality masks from a single foreground point. SAM has impressive zero-shot performance across a wide range of tasks, including edge detection, object proposal generation, and instance segmentation.

## Features

- **Google Drive Integration**: The demo includes functionality to connect to Google Drive. This integration allows for seamless access to data stored in your Google Drive account. Ensure you have the necessary permissions and API credentials to utilize this feature effectively.

- **GPU Acceleration**: The SAM model is designed to leverage GPU resources for enhanced performance. Make sure your system has access to a compatible GPU for optimal execution speed and efficiency.

- **Support for Videos and Photos**: SAM can handle both videos and photos, enabling you to perform segmentation tasks on a diverse range of media types. Whether you're working with individual images or video sequences, SAM has you covered.

- **Integration with Object Detection Classifiers**: In future versions, we plan to integrate SAM with other object detection classifiers, such as YOLO (You Only Look Once), to further enhance the model's capabilities. This integration will allow for more comprehensive and accurate object detection and segmentation tasks.


## Getting Started

To get started with the SAM demo, follow these steps:

1. **Installation**: Clone this repository to your local machine and ensure you have the necessary dependencies and libraries installed. Detailed installation instructions can be found in the `INSTALLATION.md` file.

2. **Connect to Google Drive**: Set up the Google Drive integration by following the guidelines provided in the `GOOGLE_DRIVE_INTEGRATION.md` file. This will enable easy access to your Google Drive data within the demo.

3. **Verify GPU Access**: Make sure your system has GPU access and that the necessary GPU drivers and libraries are installed. Refer to the `GPU_SETUP.md` file for instructions on verifying and configuring GPU access.

4. **Usage**: Detailed instructions on how to use the SAM demo for different tasks, such as edge detection, object proposal generation, and instance segmentation, can be found in the `USAGE.md` file. Follow the guidelines to achieve accurate and efficient results.


## Contribution and Future Development

Any contributions from the community to further enhance this demo and expand its capabilities are welcomed. If you have ideas, bug fixes, or feature suggestions, please refer to the `CONTRIBUTING.md` file for guidelines on how to contribute.

In future versions, I aim to integrate SAM with additional object detection classifiers, enabling more advanced and diverse segmentation tasks. Stay tuned for updates and new releases.

## Citation

If you use SAM or SA-1B in your research, please acknowledge and give proper credit to Meta for their work on Segment Anything Model.

please use the following BibTeX entry to cite the original paper by Meta:

```bibtex
@article{kirillov2023segany,
  title={Segment Anything},
  author={Kirillov, Alexander and Mintun, Eric and Ravi, Nikhila and Mao, Hanzi and Rolland, Chloe and Gustafson, Laura and Xiao, Tete and Whitehead, Spencer and Berg, Alexander C. and Lo, Wan-Yen and Doll{\'a}r, Piotr and Girshick, Ross},
  journal={arXiv:2304.02643},
  year={2023}
}


