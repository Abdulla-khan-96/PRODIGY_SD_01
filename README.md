# Temperature Conversion Program

This is a simple Python program that converts temperatures between Celsius, Fahrenheit, and Kelvin scales. The program prompts the user to input a temperature value and its original unit of measurement, then converts the temperature to the other two units and displays the results.

## Features

- Converts temperatures between Celsius, Fahrenheit, and Kelvin.
- User-friendly command-line interface.
- Handles invalid input gracefully.

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/temperature-converter.git
   cd temperature-converter
   ```

2. **Run the Program**:
   Ensure you have Python installed on your system. Then, run the program using the following command:
   ```bash
   python temperature_converter.py
   ```

3. **Follow the Prompts**:
   - Enter the temperature value when prompted.
   - Specify the unit of measurement (`C` for Celsius, `F` for Fahrenheit, or `K` for Kelvin).

4. **View the Results**:
   The program will display the converted temperatures in the other two units.

## Example

```bash
Enter the temperature value: 25
Enter the unit of measurement (C, F, K): C
25.0°C is 77.0°F and 298.15K
```

## Conversion Formulas

- **Celsius to Fahrenheit**: \( F = \frac{9}{5}C + 32 \)
- **Celsius to Kelvin**: \( K = C + 273.15 \)
- **Fahrenheit to Celsius**: \( C = \frac{5}{9}(F - 32) \)
- **Fahrenheit to Kelvin**: \( K = \frac{5}{9}(F - 32) + 273.15 \)
- **Kelvin to Celsius**: \( C = K - 273.15 \)
- **Kelvin to Fahrenheit**: \( F = \frac{9}{5}(K - 273.15) + 32 \)

## Requirements

- Python 3.x

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
