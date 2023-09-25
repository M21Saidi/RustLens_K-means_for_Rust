
# Wheat Leaf Rust Analysis Using Image Processing
------------------------------------------------

## Context:

Stripe rust is a significant disease affecting wheat crops globally. Accurately assessing the extent of rust infection is crucial for researchers working on disease-resistant wheat varieties. Traditionally, this assessment was manual, labor-intensive, and prone to human error. In this project, we leverage image analysis to automate the quantification of rust infection, providing a more efficient and accurate assessment method.

## Data:

The dataset comprises two images of wheat leaves affected by stripe rust (rust1, rust2). These images serve as the basis for our analysis, allowing us to segment and quantify rust-infected regions.

## Process:

1. Image Reading: Loaded and examined the two rust-infected wheat leaf images.
2. Image Preprocessing: Reshaped the images to prepare them for clustering and applied various preprocessing techniques, including color space conversions and Gaussian blurring, to enhance clustering results.
3. K-means Clustering: Used the K-means clustering algorithm to segment the images into three regions: rust, healthy leaf, and background.
4. Quantification: Calculated the proportion of rust in each leaf based on the clustering results.
5. Visualization: Visualized the original images, clustered images, and cluster centers to understand and validate the results.

## Conclusion:

Through image analysis and K-means clustering, we successfully segmented the wheat leaf images into distinct regions, enabling automated and accurate quantification of rust infection.
