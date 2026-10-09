# Simple Calculator

A beginner-friendly command-line calculator written in Python. It performs basic arithmetic operations through an easy-to-use menu.

## Features

- Addition, subtraction, multiplication, and division
- Menu-driven interface that repeats until you quit
- Input validation (re-prompts if you enter something that isn't a number)
- Handles division by zero without crashing
- Clean, simple code with one function per operation

## Requirements

- Python 3.6 or higher
- No external libraries needed

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/simple-calculator.git
   cd simple-calculator
   ```

2. Run the calculator:

   ```bash
   python calculator.py
   ```

## Example Output

```
=== Simple Calculator ===

Choose an operation:
1. Add (+)
2. Subtract (-)
3. Multiply (*)
4. Divide (/)
5. Quit
Enter choice (1-5): 3
Enter first number: 6
Enter second number: 7
Result: 42.0
```

## How It Works

Each operation (`add`, `subtract`, `multiply`, `divide`) is its own function. The `main()` function shows the menu, reads your choice, asks for two numbers, calls the matching function, and prints the result. The `get_number()` helper keeps asking until you enter a valid number.

## Ideas for Improvement

- Add more operations such as power, modulus, and square root
- Keep a history of past calculations
- Build a graphical version using Tkinter

## Project Structure

```
simple-calculator/
├── calculator.py
└── README.md
```

## Contributing

Pull requests are welcome. Feel free to suggest new features or improvements.

## License

This project is open source and available under the [MIT License](LICENSE).
