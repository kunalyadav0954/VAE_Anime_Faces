# VAE_Anime_Faces
A Variational Auto Encoder is trained on the [anime faces dataset by MckInsey666](https://github.com/bchao1/Anime-Face-Dataset) to generate anime faces.

# Things to Do
- Right now the output of the decoder after feeding a random normal input is very blurry. Things to try:
1. Change the architecture : try adding one more convolutional layer at the start of encoder and at the end of decoder.
2. Increase the size of the bottleneck : try to increase the latent vector dimension from 512 to a higher value.
