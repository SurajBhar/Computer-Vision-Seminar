# Computer-Vision-Seminar
DIVeR: Neural Radiance Fields with 
Deterministic Integration for Volume Rendering

Abstract :
Many methods have been presented for the problem of developing a generative
model capable of constructing a scene from multi-view 2D images with an adequate
number of image samples and then generating an image from the created 3D models.
To address this issue, generative models based on Monte Carlo Integrators fail
to detect or represent translucent thin surfaces accurately. Generative Models
such as NeRF and PlenOctrees can handle this issue by increasing the number of
samples that strike the thin surfaces more than previously, but at the expense of
linearly increasing computation, resulting in a new difficulty to tackle. DIVeR, with
minimal adjustments, draws on the basis of NeRF, NSVF, and Continuous
Volume rendering Integral to learning 3D scene representation and provides a
realistic novel view image. DIVeR surpasses the NeRF model in terms of speed
and accuracy by employing deterministic estimations of the volume rendering
integral rather than stochastic estimates. From NeRF findings, the DIVeR64 model
for offline rendering improves the PSNR score by 4.25%, the SSIM score by
1.3%, and the LPIPS measure by 60.49%. In terms of storage space and GPU
resources, the DIVeR32 model for real-time rendering surpasses KiloNeRF,
SNeRG, and PlenOctrees.

# Link to the official Project:
DIVeR(https://lwwu2.github.io/diver/)
Github Code:(https://github.com/lwwu2/diver-rt?tab=readme-ov-file)
