# Simple Interest Calculator

A simple command-line Bash script that calculates simple interest based on user input for principal amount, annual rate of interest, and time period in years.

## Project Description

This project provides a simple interest calculator developed as part of the IBM Developer Skills Network **Introduction to Git and GitHub** course. It allows users to compute interest payments easily using basic command-line interactions.

## Formula

$$\text{Simple Interest} = \frac{P \times R \times T}{100}$$

Where:
* **P (Principal):** The initial loan or investment amount.
* **R (Rate):** The annual interest rate (in percentage).
* **T (Time):** The duration or time period in years.

## Input Parameters

* `p` - Principal amount
* `r` - Rate of interest per year
* `t` - Time period in years

## Output

* `simple interest` - The calculated simple interest value ($p \times r \times t / 100$)

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yashmohite7324-byte/simple-calculator.git
   cd simple-calculator
   ```

2. Make the script executable:
   ```bash
   chmod +x simple-interest.sh
   ```

3. Run the calculator:
   ```bash
   ./simple-interest.sh
   ```

4. Follow the interactive prompts to enter principal, interest rate, and time period.

## Example

```
Enter the principal:
1000
Enter rate of interest per year:
5
Enter time period in years:
2
The simple interest is: 
100
```

## Authors
* Upkar Lidder (IBM)
* Yash Mohite ([yashmohite7324-byte](https://github.com/yashmohite7324-byte))

## License
This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.
