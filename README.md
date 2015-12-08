summary:
implements multiplication of matrices up to 2048 x 2048 on the gpu by
encoding matrices as 32-bit floats in the Red and Green planes of an
RGB texture.
also supports 2x byte textures for gpus that don't support FLOAT textures.
