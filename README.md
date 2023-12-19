# Image Classifier to Identify Dog Breeds

This repository contains the Python code for an image classification project, developed as part of the Udacity AI Programming with Python Nanodegree. The project's goal is to build an image classifier to identify different breeds of dogs.

## Project Overview

The project uses a pre-trained image classifier to identify dog breeds in images. The classifier is built with Python and utilizes popular deep learning libraries.

### Key Features

- Classification of dog breeds in images.
- Use of pre-trained models like AlexNet, VGG, and ResNet.
- Ability to handle both pre-specified image datasets and user-uploaded images.

### Files Description

- `adjust_results4_isadog.py`: Adjusts the classifier's results.
- `calculates_results_stats.py`: Calculates statistics of the model's results.
- `check_images.py`: Main script to check images against the classifier.
- `classifier.py`: Contains the image classification function.
- `classify_images.py`: Script to classify images in a specified folder.
- `get_input_args.py`: Handles input arguments for the script.
- `get_pet_labels.py`: Generates labels for pet images.
- `print_results.py`: Prints the classification results.
- `run_models_batch.sh`: Bash script to run the classifier on a batch of images.
- `test_classifier.py`: Tests the classifier with various inputs.

### Directories

- `pet_images/`: Contains images of pets to be classified.
- `uploaded_images/`: Folder for user-uploaded images for classification.

### Additional Files

- `dognames.txt`: List of dog names to aid in classification.
- `imagenet1000_clsid_to_human.txt`: Mapping of ImageNet classes to human-readable labels.

## Getting Started

### Prerequisites

- Python 3.x
- Libraries: [Add specific libraries and versions]

### Installation

Clone the repository to your local machine:

```
git clone [Repository URL]
```

### Usage

Run the `check_images.py` script with appropriate arguments to classify images. For example:

```
python check_images.py --dir pet_images/ --arch vgg --dogfile dognames.txt
```

## Contributing

Feel free to fork this repository and contribute. Pull requests for bug fixes, improvements, or new features are welcome.

## License

This project is licensed under the [Specify License].

## Acknowledgments

- Udacity for the foundational AI and machine learning concepts.
- Creators of the pre-trained models used in this project.
