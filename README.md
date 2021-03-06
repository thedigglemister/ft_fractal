# ft_fractal
The 2nd project of the 42 Silicon Valley graphics branch

### --Project Description--

ft_fractal is a program that renders colorful fractal images that can be zoomed in and out of in real time. Supported fractals are "Mandelbrot", "Julia", "Burning Ship", and "Buddhabrot". To facilitate quick frame rendering, I've employed both multithreading and principle of efficient calculating.

#### --Coding Style--

At 42, we follow a strict norm in order to teach us to follow style guides. This norm also prevents us from using many built-in functions. In this project, we are limited to using a barebones graphic library called minilibx. This library limits the functionality to creating windows, handling input hooks, and coloring specific pixels.

The allowed functions are : ```exit, malloc, free, and the functions of minilibx and math.h```.

The Project is written in C and in accordance with "The Norm".

#### --The Norm--

    • Functions must not exceed 25 lines
    • No more than 5 function-definitions in a .c file
    • One instruction per line
    • One single variable declaration per line; cannot stick declaration and initialisation on the same line
    • No more than 5 variables per bloc
    • No more than 4 parameters per function
    • Forbidden keywords are: [for] [do ... while] [switch] [case] [goto]
    
### --Demo Instructions (Mac OSX Sierra)--

    • Open Terminal and run the following commands:
    • git clone https://github.com/thedigglemister/ft_fractal ft_fractal
    • cd ft_fractal
    • make && ./fractal "mandelbrot"
    • Additionally, you might try "burning_ship", "julia", or "buddhabrot" in place of "mandelbrot"
       
#### --User Controls--

    • Arrows keys will translate the image
    • Z and X can be used to zoom in and out with zoom following the mouse
    • Left Shift can toggle automatic zoom
    • Space will rotate the color gradient
    • Right Shift will toggle automaticcolor gradient rotation
    • esc to exit
    
 <img src="/images/mandel1.png" width="420"> <img src="/images/mandel2.png" width="420">
 <img src="/images/burning_ship.png" width="420"> <img src="/images/mandel3.png" width="420">
