# Guessing Game App

This is a simple guessing game built using React Native and Expo. The user picks a number, and the system tries to guess it within a specified range.

## Features

- **Expo Font**: Custom fonts are used in the app.
- **Expo Linear Gradient**: Gradient backgrounds are used for the screens.
- **Splash Screen**: Handles splash screen and font loading.
- **Multiple Screens**: Includes screens for starting the game, the game itself, and game over.

## Setup

### Prerequisites

- Node.js
- npm or yarn
- Expo CLI

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/your-repo/guessing-game-app.git
    cd guessing-game-app
    ```

2. Install dependencies:

    ```sh
    npm install
    # or
    yarn install
    ```

### Running the App

1. Run the app in development mode:

    ```sh
    expo start
    ```

2. Follow the instructions on the terminal to run the app on an emulator or physical device.

## Project Structure

- **`/constants`**: Contains color constants.
- **`/screens`**: Contains screen components for the app (StartGameScreen, GameScreen, GameOverScreen).
- **`/assets`**: Contains fonts and images used in the app.

## Main Components

### `App.js`

This is the main entry point of the application. It manages the game state and handles the transition between different screens.

#### State Variables

- `userNumber`: Stores the number selected by the user.
- `gameIsOver`: Boolean to check if the game is over.
- `guessRounds`: Number of rounds taken to guess the number.

#### Handlers

- `pickedNumberHandler`: Sets the selected number and starts the game.
- `gameOverHandler`: Ends the game and records the number of rounds.
- `startNewGameHandler`: Resets the game state for a new game.

### Styles

Defined using `StyleSheet`:

- `rootScreen`: Main container style.
- `backgroundImage`: Style for the background image.

## Dependencies

- `expo-font`: Handles custom fonts.
- `expo-linear-gradient`: Provides gradient backgrounds.
- `expo-splash-screen`: Manages splash screen visibility.
- `react-native`: Core library for building mobile apps using React.
- `expo-app-loading`: Used for loading fonts and managing splash screen.

## License

This project is licensed under the MIT License.
