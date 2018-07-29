# fourier-properties


## Reference
Fourier properties
- https://en.wikipedia.org/wiki/Fourier_transform

### 1) Linearity
        a*f(x) + b*g(x) <== Fourier Transform ==> a*FFT(f(x)) + b*FFT(g(x))

### 2) Shift in Spatial domain
        f(x - a) <== Fourier Transform ==> exp(-j*2pi*a*kx) * FFT(f(x))
        
### 3) Shift in Fourier domain
        exp(j*2pi*a*x) * f(x) <== Fourier Transform ==> FFT(f(x))(kx - a)

### 4) 1D Convolution theorem
        (f*g)(x) <== Fourier Transform ==> FFT(f(x)) .* FFT(g(x))
        
            where, * is convolution operator and .* is element-wise multiplication.

### 5) 2D Convolution theorem
        (f*g)(x) <== Fourier Transform ==> FFT(f(x)) .* FFT(g(x))

            where, * is convolution operator and .* is element-wise multiplication.
