Model Final Results<br>
Reconstructed(Decoded) Representatinos in PNG & JPEG Formats in all quality levels `[0-15]` default is 8

each `32*32*3` input image is reduced to a `2*2*32` binarized representation(.npz | Numpy Format) per iteration. This results in each iteration representing `1/8` bit per pixel (bpp).
If only the first iteration is used, this would be `192:1` compression, even before entropy coding
