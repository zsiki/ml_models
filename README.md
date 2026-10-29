# ml_models
machine learning models and training data for point cloud classification 

## Training data

Training data are organized in four classes (roof, wall, vegetation, other).
There are three subfolders for three independent training sets which can be
used either independently or in combination.

Training data are stored in las files. Las files have several scalar fields
for classification. Z coordinates are relative heights from ground level.
The so called geometric features are calculated for different environments of
the individual points (0.25, 0.5, 1 and 2 metres).

| Name of scalar field |
| -------------------- |
| 1st eigenvalue (0.25) |
| 1st eigenvalue (0.5) |
| 1st eigenvalue (1) |
| 1st eigenvalue (2) |
| 2nd eigenvalue (0.25) |
| 2nd eigenvalue (0.5) |
| 2nd eigenvalue (1) |
| 2nd eigenvalue (2) |
| 3rd eigenvalue (0.25) |
| 3rd eigenvalue (0.5) |
| 3rd eigenvalue (1) |
| Anisotropy (0.25) |
| Anisotropy (0.5) |
| Anisotropy (1) |
| Anisotropy (2) |
| Coord. Z |
| Degree of linearity (K) (0.25) |
| Degree of linearity (K) (0.5) |
| Degree of linearity (K) (1) |
| Degree of linearity (K) (2) |
| Degree of planarity (M) (0.25) |
| Degree of planarity (M) (0.5) |
| Degree of planarity (M) (1) |
| Degree of planarity (M) (2) |
| Dip (degrees) |
| Dip direction (degrees) |
| Eigenentropy (0.25) |
| Eigenentropy (0.5) |
| Eigenentropy (1) |
| Eigenentropy (2) |
| Linearity (0.25) |
| Linearity (0.5) |
| Linearity (1) |
| Linearity (2) |
| Mean curvature (0.25) |
| Mean curvature (0.5) |
| Omnivariance (0.25) |
| Omnivariance (0.5) |
| Omnivariance (1) |
| Omnivariance (2) |
| Planarity (0.25) |
| Planarity (0.5) |
| Planarity (1) |
| Planarity (2) |
| Roughness (0.25) |
| Roughness (0.5) |
| Sphericity (1) |
| Sphericity (2) |
| Surface variation (0.25) |
| Surface variation (0.5) |
| Surface variation (1) |
| Surface variation (2) |
| Verticality (0.25) |
| Verticality (0.5) |
| Verticality (1) |
| Verticality (2) |
| ------------------ | 

## Models

### Random forest models

| Model file                 | Description                              |
| -------------------------- | ---------------------------------------- |
| model_rf_full.pickle | rf_full.log |
| model_rf_full_color.3clpicklelog | rf_full_color.log |

### Neural network models

| Model file                 | Description                              |
| -------------------------- | ---------------------------------------- |
| model_mlp_full_large.pickle | mlp_full_large.log |
| model_mlp_full_color_large.pickle | mlp_full_color_large.log |
| model_mlp_full_geom_large.pickle | mlp_full_geom_large.log | 
