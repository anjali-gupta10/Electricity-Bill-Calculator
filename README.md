# Electricity Bill Calculator

A Python 3 project that calculates an electricity bill using slab-wise rates.

## Rates
- First 100 units: Rs. 3 per unit
- Next 100 units (101-200): Rs. 5 per unit
- Above 200 units: Rs. 8 per unit
- Fixed charge: Rs. 50
- Tax: 5% on energy charge + fixed charge

## Concepts
Conditions, operators, functions, input validation and formatted output.

## Run in VS Code
1. Open this folder in VS Code.
2. Open `electricity_bill_calculator.py`.
3. Open the VS Code terminal.
4. Run: `python electricity_bill_calculator.py`
5. Enter the consumer name and units consumed.

## Test Cases

| Units | Energy | Fixed | Tax | Total |
|---:|---:|---:|---:|---:|
| 80 | Rs. 240.00 | Rs. 50.00 | Rs. 14.50 | Rs. 304.50 |
| 100 | Rs. 300.00 | Rs. 50.00 | Rs. 17.50 | Rs. 367.50 |
| -20 or abc | Invalid units message | | | |
| 250 | Rs. 1200.00 | Rs. 50.00 | Rs. 62.50 | Rs. 1312.50 |

## Upload to GitHub
Create a repository named `electricity-bill-calculator`, then upload this Python file and `README.md`. Commit the files with a message such as `Add electricity bill calculator project`.
