# VisualizingJuliaSet

This project was created on February 27, 2025. I used numpy and matplotlib to define a complex plane and create a function to generate, plot, and visualize the Julia set. 

Google Colaboratory link: https://colab.research.google.com/drive/1xwoUfTUHUoIInVdMHJ-CpPLo2xbLNRl1?usp=sharing

# Overview
Julia sets are a family of fractals in the complex plane. Each unique value of the complex constant c produces a distinct fractal structure, ranging from intricate connected filaments to scattered "dust" depending on whether c lies inside or outside the Mandelbrot set.

# How it works
A 2D grid of complex numbers is initialized over the range [-2, 2] × [-2, 2]
Each point z is repeatedly updated via z → z² + c for a fixed number of iterations
Points are colored by how many iterations they survive before escaping to infinity (magnitude > 2)
The resulting iteration counts are plotted as a heatmap using the prism colormap

# Usage
Run the notebook and enter the real and imaginary parts of c when prompted:
Real C: -0.125
Imaginary C: 0.75
This produces a 500×500 visualization of the Julia set for c = -0.125 + 0.75i.
