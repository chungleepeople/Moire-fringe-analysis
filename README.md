*These files are for the master degree of wafer alignment by using moire fringe in National Taiwan university .*
# What is moire fringe ?
`The Moiré fringes can be used for nano-level detection, which can be directly detected by the optical system through the magnification characteristics of the fringes without additional assistances.`
# Zemax simulation model
![zemax model](https://i.ibb.co/6Zm3tGK/zemax-model.png)

## Zemax simulation parameters
####  Wavelength: 1064nm 
####  CCD1 & CCD2 sensor size: 4𝑚𝑚 × 4𝑚𝑚
####  Pixel size : 7.825  
####  Lens Magnification: 10x 
####  Power : 1w
####  Analysis Rays: 1000000
####  Layout Rays: 20000

# Step 1 line profile  Moire-fringe-analysis
![line profile](https://i.ibb.co/sHkWVF3/line-profile.png)

# Step 2 Fourier transform  Moire-fringe-analysis
![Fourier transform](https://i.ibb.co/c36dN4m/FT.png)

# Step 3 low pass filter Moire-fringe-analysis
![low pass filter](https://i.ibb.co/TPZ8RJ6/low-pass.png)

# Step 4 Inverse Fourier transform Moire-fringe-analysis
![IFT](https://i.ibb.co/zmpZpCK/IFFT.png)
