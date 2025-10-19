# Part 1 Task 6: simple-interest.sh File (2 pts)

## Detailed Answer

The repository contains the simple-interest.sh file in the root directory, which is the core bash script that implements the Simple Interest Calculator functionality. This script is the main deliverable of the project and provides the practical implementation of the simple interest calculation.

The simple-interest.sh file includes several important components:

1. **Shebang Line**: The script begins with `#!/bin/bash`, ensuring it runs with the bash shell interpreter, making it compatible across different Unix-like systems.

2. **Comprehensive Documentation**: The script includes detailed comments explaining its purpose, author information, input parameters, and output format, following best practices for code documentation.

3. **Author Attribution**: The script properly credits Upkar Lidder (IBM) as the original author and includes a placeholder for additional authors, demonstrating proper attribution practices.

4. **Input Collection**: The script uses the `read` command to collect three essential inputs from the user:
   - Principal amount (p)
   - Rate of interest per year (r)
   - Time period in years (t)

5. **Mathematical Calculation**: The script implements the simple interest formula using the `expr` command: `s=\`expr $p \* $t \* $r / 100\``, which correctly calculates simple interest as (principal × time × rate) / 100.

6. **User-Friendly Interface**: The script provides clear prompts for each input and displays the result in a readable format.

7. **Production Disclaimer**: The script includes a note that it's for sample purposes only and not intended for production use, demonstrating responsible software development practices.

This script is essential for the micro-finance startup's mission because:
- It provides a practical tool for calculating simple interest
- It's accessible to users with basic command-line knowledge
- It demonstrates the mathematical principles behind interest calculations
- It can serve as a foundation for more complex financial calculation tools
- It supports the startup's goal of empowering individuals with financial literacy tools

The script's simplicity and clear documentation make it an excellent educational tool while also serving practical purposes for basic interest calculations.
