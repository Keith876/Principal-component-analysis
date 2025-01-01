# Principal-component-analysis
This project demonstrates the functionality of Principal Component Analysis (PCA) using a simple 2D dataset. PCA is a dimensionality reduction technique that identifies the directions of maximum variance in data and reduces its dimensionality while retaining as much information as possible.

### Requirements
- Python 3.8+
- NumPy
- Matplotlib
- sci-kit-learn


### PCA
The data is reduced from 2 dimensions to 1 dimension (n_components=1).
The principal component is the direction of maximum variance in the data.
### Visualization
Original Data: The raw 2D data points.
Principal Component: The main axis along which the data has the most variance.
Reconstructed Data: Data is projected back into the original 2D space after being reduced to 1D.
### Steps in PCA
Center the data by subtracting the mean.
Calculate the principal component (direction of maximum variance).
Project data onto the principal component.

