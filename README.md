# Temperature-Converter
Here’s a C++ program to implement a temperature converter that allows conversions between Celsius, Fahrenheit, and Kelvin.
The code implements a **Temperature Converter** with the following functionalities and structure:

### Functionality:
1. **Input Temperature Scale**: Users choose between Celsius, Fahrenheit, or Kelvin for input.
2. **Conversions**:
   - Celsius: Converts to Fahrenheit and Kelvin.
   - Fahrenheit: Converts to Celsius and Kelvin.
   - Kelvin: Converts to Celsius and Fahrenheit.
3. **Input Validation**:
   - Ensures the temperature scale choice is valid.
   - Validates Kelvin input to prevent negative values.

### Code Structure:
- **Functions**: Each conversion is implemented as a separate function for modularity, e.g., `celsiusToFahrenheit`, `fahrenheitToKelvin`, etc.
- **Main Function**:
  - Handles user interaction: input selection, temperature input, and output of converted values.
  - Uses a `switch` statement for conditional execution based on user choice.

### Features:
- **Precision**: Outputs are formatted to two decimal places using `fixed` and `setprecision`.
- **Error Handling**: Provides feedback for invalid choices or temperatures.
- **Modularity**: Clear separation of conversion logic into functions improves readability and maintainability.

### Improvements:
The suggestions made in the comments focus on:
1. Avoiding the global namespace pollution with `using namespace std`.
2. Enhancing input validation for clarity and flexibility.
3. Centralizing formatting code for consistency.
4. Using constants for better readability and maintenance of conversion factors.
