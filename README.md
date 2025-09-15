# Monte Carlo Pi Approximation in MATLAB

This project demonstrates the approximation of $\pi$ using the Monte Carlo method in MATLAB. It explores two primary approaches: one using a `for` loop for a fixed number of iterations and another using a `while` loop to achieve a desired level of precision. The project also analyzes the trade-off between computational time and accuracy.

---

## How to Run

The code is designed to be run in a MATLAB environment, preferably as a script with runnable cells (e.g., a Live Script `.mlx`).

1.  Open the script in MATLAB.
2.  Run the cells sequentially from top to bottom to see the full analysis.
3.  **Important:** To accurately measure performance for the **Error vs. Computation Time** analysis, **run that specific cell twice**. The first execution includes MATLAB's JIT (Just-In-Time) compilation time, which can artificially inflate the measured runtime. The second run will provide a more accurate timing for the algorithm itself.

---
