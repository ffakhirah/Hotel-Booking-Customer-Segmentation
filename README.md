# Hotel Booking Customer Segmentation 📊🏨

## Project Overview
This project compares the performance of **K-Means clustering** and **DBSCAN** algorithms for segmenting hotel booking data. The aim is to analyze and group guests based on their **lead time**, **average daily rate (adr)**, **total stay**, and **market segment**.

## Dataset Description
The **[Hotel Booking Dataset](https://www.kaggle.com/datasets/saadharoon27/hotel-booking-dataset/data)** contains detailed information about hotel bookings, including:
- **Guest Information**: Guest profiles and booking status.
- **Booking Details**: Dates, cancellations, and room types.
- **Hotel Attributes**: Hotel type and additional services.

## Data Preprocessing
1. **Data Cleaning**: Missing values are handled and irrelevant columns are dropped.
2. **Feature Engineering**: New features such as `total_stay` are created.
3. **Normalization**: Features are standardized using **StandardScaler**.

## Algorithms Used
### **K-Means Clustering**
- Applied to group hotel guests based on their booking patterns.
- Evaluation using **Elbow Method** and **Silhouette Score**.

### **DBSCAN (Density-Based Clustering)**
- Applied for clustering data with varying densities.
- Capable of identifying outliers as noise points.

## Algorithm Comparison
Both algorithms are compared using **Silhouette Scores** to assess the quality of clustering. The results help understand which algorithm provides better segmentation for hotel guests.

## Results and Insights
- **K-Means** is efficient for identifying clusters in well-separated data but is sensitive to the number of clusters (k).
- **DBSCAN** is robust to outliers and can find clusters of arbitrary shapes, but requires careful tuning of parameters.

## How to Run
1. Clone the repository.
2. Install dependencies.
3. Run the Jupyter notebook to see the analysis and clustering results.

## Technologies Used:
- **Python**
- **K-Means** Clustering
- **DBSCAN**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**
