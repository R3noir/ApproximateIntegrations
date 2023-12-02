# ApproximateIntegrations.ipynb

This Jupyter notebook contains various methods for numerical integration. The methods implemented in this notebook are:

- Left Riemann Sum
- Right Riemann Sum
- Midpoint Rule
- Trapezoidal Rule
- Simpson's Rule

Each method is implemented as a function that takes a function `f`, a lower limit `a`, an upper limit `b`, and a number of intervals `n` as parameters and returns the numerical integral of `f` from `a` to `b` using the specified method.

## Variables

The notebook uses the following global variables:

- `linespace`: The number of points to plot. Default is 1000.
- `a`: The lower limit of the integral. Default is 0.
- `b`: The upper limit of the integral. Default is `np.pi`.
- `n`: A list of the number of intervals to use in the numerical integration methods. Default is `[4,8,16,126,256,1024]`.
- `fmt`: The number of decimal places to display. Default is ".10f".

## Functions

The notebook contains the following functions:

- `f(x)`: The function to integrate. Default is `np.sin(x)`.
- `rectangular_left(f, a, b, n)`: Calculates the Left Riemann Sum.
- `rectangular_right(f, a, b, n)`: Calculates the Right Riemann Sum.
- `midpoint_rule(f, a, b, n)`: Calculates the Midpoint Rule.
- `trapezoidal_rule(f, a, b, n)`: Calculates the Trapezoidal Rule.
- `simpsons_rule(f, a, b, n)`: Calculates the Simpson's Rule.

The notebook also contains functions to plot each method:

- `plot_rectangular_left(f, a, b, n, ax)`: Plots the Left Riemann Sum.
- `plot_rectangular_right(f, a, b, n, ax)`: Plots the Right Riemann Sum.
- `plot_midpoint_rule(f, a, b, n, ax)`: Plots the Midpoint Rule.
- `plot_trapezoidal_rule(f, a, b, n, ax)`: Plots the Trapezoidal Rule.
- `plot_simpsons_rule(f, a, b, n, ax)`: Plots the Simpson's Rule.

## Usage

To use this notebook, you can change the function `f(x)` and the variables `a`, `b`, and `n` to your desired values. Then, you can call the numerical integration functions with your function and limits to calculate the numerical integral. You can also call the plot functions to visualize the numerical integration methods.
