# Analyzing-Urban-Street-Network-Characteristics-in-Asia-Oceania-Cities
This project analyzes and clusters urban street network characteristics across different global regions using preprocessing, normalization, and various clustering techniques to uncover structural patterns and regional differences.
## Column Names and Descriptions

- **Region:** The global region where the city is located (e.g., Asia/Oceania, Europe, Latin America, Middle East/Africa, US/Canada).
- **City:** The name of the city.
- **orientation_order:** Indicator of the order of street orientations.
- **street_orientation_entropy:** Entropy of street orientations.
- **weighted_street_orientation_entropy:** Weighted entropy of street orientations.
- **median_street_segmant:** Median length of street segments.
- **average_circuity:** Average circuity of the street network.
- **average_node_degree:** Average node degree in the street network.
- **proportion_of_dead-ends:** Proportion of dead-end streets.
- **proportion_of_four_way_intersection:** Proportion of four-way intersections.

# Comparative Analysis and Clustering of Global Urban Street Networks

## Project Description

This project aims to analyze and compare the street network characteristics of various cities across different regions globally, including Asia/Oceania, Europe, Latin America, Middle East/Africa, and US/Canada. The analysis involves several key steps:

1. **Data Preprocessing:**
   - The dataset comprises various metrics related to urban street networks, such as orientation order, street orientation entropy, median street segment length, average circuity, average node degree, proportion of dead-ends, and proportion of four-way intersections.
   - Missing values in the dataset were identified and handled appropriately. Regions were filled based on index ranges to ensure a complete dataset for analysis.

2. **Normalization:**
   - The numeric features were normalized using MinMaxScaler to bring all variables into the same range, facilitating fair comparisons across different metrics.

3. **Clustering Analysis:**
   - **K-means Clustering:** This technique was used to group cities into clusters based on their street network characteristics. The optimal number of clusters was determined, and the cities were assigned to clusters, which were then visualized using scatter plots.
   - **Hierarchical Clustering:** Multiple linkage methods (single, complete, average, and Ward) were employed to perform hierarchical clustering. Dendrograms were generated to visualize the hierarchical relationships among the cities based on their street network features.

4. **Visualization:**
   - Various plots, including scatter plots and dendrograms, were created to visualize the clustering results and the distribution of street network characteristics across different regions. For instance, a scatter plot comparing average circuity and the proportion of dead-end nodes highlighted the differences among regions.

5. **Additional Analysis:**
   - An attempt was made to merge the urban street network data with another dataset containing population information for the cities, though the detailed analysis of this merged dataset is pending further exploration.

The primary goal of this project is to uncover patterns and similarities in the street networks of cities within and across different global regions. Such insights can help urban planners and researchers understand the structural differences in urban layouts, contributing to better city planning and development strategies.
