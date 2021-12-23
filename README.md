# Steganography Through Image Processing

**Steganography**, derived from the Greek words *steganos* (meaning hidden or covered) and *graph* (meaning to write), is the technique of concealing secret data within a non-secret file or transmission to prevent discovery; the secret data is then retrieved at its destination. Steganography can be used in conjunction with encryption to conceal or safeguard data ([Semilof]("https://searchsecurity.techtarget.com/definition/steganography"), 2021).
<br>

With the use of image processing, steganography can be applied to images to produce a ***stego image***; the output of the embedding process which contain the hidden message either in pixel values or in optimally selected coefficients. This done by reducing the image in their numerical forms, which essentially are pixel values. These pixel values, can then be mathematically manipulated in order to produce an image that looks normal to the naked eye, but has been manipulated to contain a secret.
<br>

This notebook demonstrates how steganography can be performed to hide *(a) text inside an image* and *(b) image inside another image* using the concepts of value replacements and extraction of the *most significant bits (MSB)* and the *least signigicant bits (LSB)* of an image.
