# Pong Master Solo

**Pong Master Solo** is an engaging single-player Pong game that uses computer vision to track hand movements for paddle control. This interactive experience is built with Python, Flask, OpenCV, and TensorFlow, offering a fun and innovative way to play Pong using just your hands!

## Features

- **Hand Tracking**: Uses OpenCV and the cvzone library to track hand movements and control paddles.
- **Dynamic Gameplay**: Adjusts the paddle's position in real-time based on hand movements for a smooth gaming experience.
- **Score Keeping**: Keeps track of scores and displays them on the screen.
- **Game Over Detection**: Detects when the ball goes out of bounds and shows a game over screen.
- **Reset Functionality**: Allows resetting the game to start over.

## Technologies Used

- **Python**: The main programming language for the project.
- **Flask**: A lightweight web framework to serve the game.
- **OpenCV**: For computer vision tasks and image processing.
- **cvzone**: For easy integration of hand tracking capabilities.
- **TensorFlow**: Utilized for potential machine learning enhancements.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/pradyot29/PongMasterSolo.git
    cd PongMasterSolo
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Download the necessary assets (background image, ball image, paddle images) and place them in the `assets` directory.

## Usage

1. Run the application:
    ```bash
    python app.py
    ```

2. Open your web browser and go to `http://127.0.0.1:5000/` to start playing!

## How to Play

- **Start the Game**: Open the URL and you will see the game interface.
- **Control the Paddles**: Use your hands to control the paddles. The left hand controls the left paddle, and the right hand controls the right paddle.
- **Score Points**: Hit the ball with your paddle to score points. The game keeps track of the score and displays it on the screen.
- **Game Over**: When the ball goes out of bounds, the game shows a game over screen with the total score.
- **Reset**: Use the reset button to start a new game.


## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-branch
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature-branch
    ```
5. Create a pull request.


## Acknowledgements

- Special thanks to the developers of [OpenCV](https://opencv.org/) and [cvzone](https://www.cvzone.io/) for their fantastic libraries.
- Inspired by classic Pong games and modern computer vision techniques.

---

**Made by Pradyot ❤️**

[See the source code](https://github.com/pradyot29/PongMasterSolo)

