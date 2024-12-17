# Calculator Application  

## Description  
This is a simple calculator application written in Python. It performs basic arithmetic operations such as addition, subtraction, multiplication, and division. The user can choose an operation and input two numbers to get the result.  

## Features  
- Supports four basic arithmetic operations:  
  1. Addition  
  2. Subtraction  
  3. Multiplication  
  4. Division  
- Handles division by zero with a custom error message.  

## Requirements  
- Python 3.x installed on your system.  

## How to Run  
1. Clone or download the project to your local machine.  
2. Open the project folder in your terminal or preferred IDE.  
3. Run the Python script with the following command:  
   ```bash  
   python calculator.py  
   ```  
4. Follow the instructions displayed on the terminal to:  
   - Select an operation.  
   - Input two numbers.  
   - View the result.  

## Code Explanation  

### Functions:  
- **`add(x, y)`**: Returns the sum of two numbers.  
- **`subtract(x, y)`**: Returns the difference between two numbers.  
- **`multiply(x, y)`**: Returns the product of two numbers.  
- **`divide(x, y)`**: Returns the quotient of two numbers. If the second number is zero, it returns an error message.  

## Example Usage  

### Select operation:  
1. Add  
2. Subtract  
3. Multiply  
4. Divide  

**Enter choice (1/2/3/4):** `1`  
**Enter first number:** `10`  
**Enter second number:** `5`  
**Output:**  
```
10.0 + 5.0 = 15.0  
```  

**If you try to divide by zero:**  
- **Enter choice (1/2/3/4):** `4`  
- **Enter first number:** `8`  
- **Enter second number:** `0`  
**Output:**  
```
8.0 / 0.0 = Error! Division by zero.  
```  

## Future Improvements  
- Allow continuous calculations without restarting the program.  
- Implement a graphical user interface (GUI).  
- Add advanced operations like square root, power, or modulus.  

## License  
This project is licensed under the MIT License.  
