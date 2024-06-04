# Test Average Calculator

## Overview
The **Test Average Calculator** is a Python application that uses a Graphical User Interface (GUI) to input three test scores and display their average. The application is built using the `tkinter` library.

## Features
- Input fields for three test scores.
- Calculation of the average of the three test scores.
- Display of the calculated average.
- Buttons to calculate the average and quit the application.

## Code Structure
The application is developed in Python using the `tkinter` library. The main components of the code are organized in the `TestAvg` class.

### Class: TestAvg
The `TestAvg` class encapsulates the functionality of the application.

#### Methods
- `__init__(self)`: Constructor to initialize the GUI components and layout.
- `calc_avg(self)`: Callback function for the "Average" button. It calculates the average of the three test scores and updates the display.

#### GUI Components
- **Frames**:
  - `test1_frame`: Frame for the first test score input.
  - `test2_frame`: Frame for the second test score input.
  - `test3_frame`: Frame for the third test score input.
  - `avg_frame`: Frame for displaying the average score.
  - `button_frame`: Frame for the buttons.
  
- **Labels and Entries**:
  - `test1_label`, `test2_label`, `test3_label`: Labels for the test score inputs.
  - `test1_entry`, `test2_entry`, `test3_entry`: Entry fields for the test score inputs.
  - `result_label`: Label for the average result.
  - `avg_label`: Label to display the calculated average.
  - `avg`: StringVar object to dynamically update the average display.
  
- **Buttons**:
  - `calc_button`: Button to calculate the average.
  - `quit_button`: Button to quit the application.

## Getting Started

### Prerequisites
- Python 3.x
- `tkinter` library (comes pre-installed with standard Python distributions)

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/TestAverageCalculator.git
    ```
2. Navigate to the project directory:
    ```sh
    cd TestAverageCalculator
    ```
3. Run the application:
    ```sh
    python test_average_calculator.py
    ```

### Usage
1. Enter the scores for the three tests in the respective input fields.
2. Click the "Average" button to calculate the average of the test scores.
3. The average will be displayed in the "Average" label.
4. Click the "Quit" button to exit the application.

## Example
```python
# Create an instance of the TestAvg class
if __name__ == '__main__':
    test_avg = TestAvg()
```

This script initializes and runs the Test Average Calculator application.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

Feel free to reach out for any questions or contributions. Happy coding!

---

### Note
This application is a sample project intended for learning and demonstration purposes. It may require further enhancements and testing for production use.
