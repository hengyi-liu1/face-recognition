# Face Recognition Using Principal Component Analysis

Built a face recognition and similarity search system using PCA and clustering, reducing high-dimensional facial data into a compact latent representation for visualization and retrieval.

## Highlights

- Reduced facial feature dimensionality using PCA by **over 90%**
- Visualized latent spaces and principal components
- Applied k-means clustering to group facial expressions
- Implemented similarity search using Euclidean distance in latent space

## Methods & Results

- Applied SVD to a 136-dimensional facial dataset
- Extracted 4 principal components capturing most data variance
- Learned expression clusters using k-means
- Computed and visualized mean faces for each cluster
- Projected query faces into latent space and retrieved nearest matches

## Technical Skills

- Python, NumPy, Matplotlib
- Principal Component Analysis (PCA)
- Singular Value Decomposition (SVD)
- K-means clustering
- Latent space projection and similarity search

## Repository Contents

- `face_recognition.ipynb` – Implementation, experiments, and visualizations

## Running the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/hengyi-liu1/face-recognition.git
   ```
2. Open `face_recognition.ipynb` in Jupyter Notebook or VS Code
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run all cells to reproduce results