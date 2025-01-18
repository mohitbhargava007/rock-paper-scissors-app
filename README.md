# Rock Paper Scissors Game

This is a simple web-based Rock Paper Scissors game built using Flask. The application allows users to play the classic game against the computer through an intuitive front end.

## Project Structure

```
rock-paper-scissors-app
├── app
│   ├── __init__.py
│   ├── routes.py
│   ├── static
│   │   ├── css
│   │   │   └── styles.css
│   └── templates
│       └── index.html
├── venv
├── app.py
├── requirements.txt
└── README.md
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd rock-paper-scissors-app
   ```

2. **Create a virtual environment:**
   ```
   python -m venv venv
   ```

3. **Activate the virtual environment:**
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```

4. **Install the required packages:**
   ```
   pip install -r requirements.txt
   ```

5. **Run the application:**
   ```
   python app.py
   ```

6. **Open your web browser and go to:**
   ```
   http://127.0.0.1:5000
   ```

## Usage

- Select Rock, Paper, or Scissors to play against the computer.
- The result of each round will be displayed on the screen.
- Enjoy the game!

## License

This project is licensed under the MIT License.