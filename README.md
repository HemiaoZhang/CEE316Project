# CEE316 Project

## Meeting minutes (Fri, 03/03/23)

### Scope for the class project

To generate 2D pore images using variational autoencoder (VAE) benchmarked against traditional CNN-based autoencoder.

#### Tasks

- Prepare 1k instances of 50-by-50 2D slices from a 1000x1000x1000 [Berea sandstone binary image](https://www.digitalrocksportal.org/projects/317/origin_data/1354/) as the training data.

- First train a CNN autoencoder using pixel data.

- Then train a VAE using the same dataset. 

### Implementation to 3D 

- Use a similar VAE setting to serve as an interpolation between real micro-CT images ad augment an existing dataset for water retention curve prediction.

