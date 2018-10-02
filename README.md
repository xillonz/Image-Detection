# Image Detection

## Description

An experiment to see if products can be dynamically located on user uploaded files.
Initially intended for automatically placing text on product files that are likely to have a simple textured background.

Uses self written algorithms based on colour gradient, inspired by the seam carving methods used for such things as Photoshop Content Aware cropping.

Generates the center of mass of the product as an X,Y coordinate on the file as well as an average radius. As such, product name or other text can be efficientally placed overtop of the file while minimally covering the product.
Reduces work for designers or product file uploaders for website product pages.

Different gradient values and other parameters generate different levels of accuracy, so parameters can be adjusted for better results, or reduced computation time.
