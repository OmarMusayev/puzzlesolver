# AI for Jigsaw Puzzles

## Project Details

This project is about creating an AI system that can solve jigsaw puzzles. The AI uses a blend of image processing methods and machine learning algorithms to spot individual puzzle pieces, figure out their correct orientation, and place them in the right position to complete the puzzle.

The project has several phases:

1. **Image Processing**: The AI begins by processing the puzzle image to spot individual pieces. This involves methods like edge detection, contour identification, and image division.

2. **Piece Sorting**: After the pieces are spotted, the AI uses a machine learning model to sort the pieces based on their shape and whether they're edge or corner pieces.

3. **Piece Orientation**: The AI then determines the correct orientation of each piece. This is done by comparing the edges of the pieces to each other and finding the best match.

4. **Puzzle Completion**: Finally, the AI places the pieces in the correct position to complete the puzzle. This is done by comparing the images on the pieces and finding the best match.

## Repository Contents

This repository includes:

- Source code for the AI system.
- A set of sample jigsaw puzzles for testing.
- Guides on how to operate the system and understand the results.

## Sample Puzzles and Solutions

![van-gogh](https://github.com/TitanWolfie/puzzlesolver/assets/104903102/2c07b48d-eaa8-4db9-a7e0-5f48b45fc461)

![van-gogh](https://github.com/TitanWolfie/puzzlesolver/assets/104903102/bf49a681-2224-476d-a101-1ab9ddeda6b5)

![craies_32](https://github.com/TitanWolfie/puzzlesolver/assets/104903102/8689611f-c754-488d-a572-1e71ece722a6)

![craies_32](https://github.com/TitanWolfie/puzzlesolver/assets/104903102/7e5e9667-002b-4e20-91ac-e2e479bbba10)

![puzzle](https://github.com/TitanWolfie/puzzlesolver/assets/104903102/7eee04f9-2f5f-4df2-a01e-cf57e86c16c7)

![af28d739-405e-42f4-b93c-879cd82c1009](https://github.com/TitanWolfie/puzzlesolver/assets/104903102/6b0fc17e-53e8-45a4-a114-9acc1c448edd)

## How to Operate

To operate the system, simply run the main script with the puzzle image as an argument. The system will then process the image, spot the pieces, sort them, determine their orientation, and complete the puzzle.

## Requirements

This project requires Python 3.6 or later and the following Python libraries:

- NumPy
- OpenCV
- scikit-learn
- TensorFlow

## Future Plans

Future plans for this project will focus on improving the accuracy of the piece sorting and orientation determination stages, as well as optimizing the puzzle completion algorithm for speed.

## How to Contribute

Contributions to this project are welcome. If you have a feature request, bug report, or want to contribute code, please open an issue or pull request.

## License

This project is free for everyone to use.

## Video

https://www.youtube.com/watch?v=FK3mwMWRR2I

