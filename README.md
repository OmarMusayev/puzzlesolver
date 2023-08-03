# Jigsaw Puzzle AI

## Project Overview

This project is an exploration into the development of an Artificial Intelligence (AI) system capable of solving jigsaw puzzles. The AI uses a combination of image processing techniques and machine learning algorithms to identify individual puzzle pieces, determine their correct orientation, and place them in their correct position to solve the puzzle.

The project is divided into several stages:

1. **Image Preprocessing**: The AI first processes the image of the jigsaw puzzle to identify individual pieces. This involves techniques such as edge detection, contour detection, and image segmentation.

2. **Piece Classification**: Once the pieces are identified, the AI uses a machine learning model to classify the pieces based on their shape and the presence of edge or corner pieces.

3. **Piece Orientation**: The AI then determines the correct orientation of each piece. This is done by comparing the edges of the pieces to each other and finding the best match.

4. **Puzzle Solving**: Finally, the AI places the pieces in their correct position to solve the puzzle. This is done by comparing the images on the pieces and finding the best match.

## Repository Contents

This repository contains the following:

- Source code for the AI system.
- A set of sample jigsaw puzzles for testing.
- Documentation on how to use the system and interpret the results.

## Sample Puzzles and Solutions

![van-gogh](https://github.com/TitanWolfie/puzzlesolver/assets/104903102/2c07b48d-eaa8-4db9-a7e0-5f48b45fc461)


![van-gogh](https://github.com/TitanWolfie/puzzlesolver/assets/104903102/bf49a681-2224-476d-a101-1ab9ddeda6b5)

![craies_32](https://github.com/TitanWolfie/puzzlesolver/assets/104903102/8689611f-c754-488d-a572-1e71ece722a6)

![craies_32](https://github.com/TitanWolfie/puzzlesolver/assets/104903102/7e5e9667-002b-4e20-91ac-e2e479bbba10)

![puzzle](https://github.com/TitanWolfie/puzzlesolver/assets/104903102/7eee04f9-2f5f-4df2-a01e-cf57e86c16c7)

![af28d739-405e-42f4-b93c-879cd82c1009](https://github.com/TitanWolfie/puzzlesolver/assets/104903102/6b0fc17e-53e8-45a4-a114-9acc1c448edd)

## Usage

To use the system, simply run the main script with the image of the jigsaw puzzle as an argument. The system will then process the image, identify the pieces, classify them, determine their orientation, and solve the puzzle.

## Dependencies

This project requires Python 3.6 or later and the following Python libraries installed:

- NumPy
- OpenCV
- scikit-learn
- TensorFlow

## Future Work

Future work on this project will focus on improving the accuracy of the piece classification and orientation determination stages, as well as optimizing the puzzle solving algorithm for speed.

## Contributing

Contributions to this project are welcome. If you have a feature request, bug report, or want to contribute code, please open an issue or pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
