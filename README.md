# Image Morphing with Delaunay Triangulation

This project implements image morphing using Delaunay triangulation, allowing you to transform one image into another smoothly and seamlessly. The technique involves breaking down both images into a set of triangles, establishing correspondences between the triangles, and then morphing the images by interpolating their pixel values.

![Image Morphing Demo](demo.gif)

## Features

- **Delaunay Triangulation:** The project uses the Delaunay triangulation algorithm to create a mesh of triangles on both source and target images.

- **Correspondence Calculation:** Correspondences between the triangles in the source and target images are established to determine how the pixels should morph.

- **Warping and Cross-Dissolving:** The project applies geometric warping to morph the triangles in the source image to match the positions of the triangles in the target image. It also performs cross-dissolve blending to create a smooth transition between the two images.

- **User Interface:** The project includes a simple user interface where you can load the source and target images, define corresponding points manually or automatically, and adjust morphing parameters.

## Installation

Clone the repository to your local machine:

   ```bash
   git clone https://github.com/keshav-04/Image-Morphing.git
  ```

## Contributing

Contributions are welcome! If you find any bugs or want to enhance the project, feel free to open an issue or submit a pull request.

