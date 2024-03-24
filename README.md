# Image Similarity

Image Similarity is a project implemented in Python using OpenCV. It aims to implement metrics for differentiating images, which could serve as a foundation for phishing detection. The program consists of three modules for comparing image screenshots:

1. Module 1 evaluates color similarity.
2. Module 2 compares layout similarity.
3. Module 3 finds different positions between images.

## Demo

### Color Comparison
![Color Comparison](./demo/color.png)

### Feature Comparison
![Feature Comparison](./demo/feature.png)

### Image Different Position
![Image Different Position](./demo/diff.png)


## Installation

To use Image Similarity, follow these steps:

1. Clone this repository to your local machine.
2. Make sure you have Python installed.
3. Install the required dependencies by running: pip install -r requirements.txt


## Usage

This model has 3 modules, each with a "mode" to run the code:

- Color Histogram Similarity: `mode = 0`
- SIFT Features Similarity: `mode = 1`
- Image Similarity: `mode = 2`

To run the model:
- Open a command prompt.
- Type the following script:
python main.py --first <image_1's PATH> --second <image_2's PATH> --mode <0/1/2>

Replace `<image_1's PATH>` and `<image_2's PATH>` with the paths to your images and `<0/1/2>` with the desired mode.

Example: python main.py --first Dataset/or1_amazon.png --second Dataset/Paypal.png --mode 2


## Contributing

Contributions are welcome! If you have any ideas for improvements or new features, feel free to open an issue or submit a pull request.


## Acknowledgements

- Implemented in Python programming language with OpenCV library
- Inspired by the need for image differentiation for phishing detection

