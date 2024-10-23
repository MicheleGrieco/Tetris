# Tetris Game

Tetris is a classic puzzle video game where geometric shapes, known as "tetrominoes," fall from the top of a rectangular grid. The player must rotate and arrange these tetrominoes to form complete lines. Once a line is completed, it disappears, allowing more room for additional tetrominoes. The objective is to prevent the stack of blocks from reaching the top of the grid.

## Key Features:
- **Falling Tetrominoes**: Shapes like I, O, T, S, Z, L, and J fall from the top.
- **Line Clearing**: Complete a row to clear it and earn points.
- **Increasing Difficulty**: As the game progresses, tetrominoes fall faster.
- **Simple yet Challenging**: Requires both strategy and reflexes.

---

# Installation Instructions

Follow these steps to install and run a Tetris game created using Python.

## Prerequisites
Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

### 1. **Clone the Repository**
First, clone the project repository from GitHub or download it as a ZIP file.

```bash
git clone https://github.com/username/tetris-game.git
cd tetris-game
```

### 2. **Set up a Virtual Environment (Optional but Recommended)**
It's good practice to create a virtual environment to manage dependencies.

- **On macOS/Linux:**
  ```bash
  python3 -m venv venv
  source venv/bin/activate
  ```

- **On Windows:**
  ```cmd
  python -m venv venv
  venv\Scripts\activate
  ```

### 3. **Install Dependencies**
Once in the project directory, install the required libraries using `pip`.

```bash
pip install -r requirements.txt
```

If you don’t have a `requirements.txt` file, make sure to install the necessary libraries, such as `pygame`, manually:

```bash
pip install pygame
```

### 4. **Run the Game**
After installing the dependencies, run the game using the following command:

```bash
python main.py
```

### 5. **Deactivating the Virtual Environment**
When you are done playing or modifying the game, you can deactivate the virtual environment with:

```bash
deactivate
```

---