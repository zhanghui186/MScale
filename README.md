# MScale
<!-- #Amplitude correction algorithm for denoising particles guided by 3D density maps (MScale)
The pipeline of Mscale algorithm:
1. Autorefine the given original particle stack, based on this, reconstruct the density map raw.mrc and denoised.mrc
2. Calculate the amplitude attenuation scale factor scale
4. Scale Factor Scaling Denoising Grain Fourier rotationally averaged amplitudes
5. Save the scaled particle stack -->