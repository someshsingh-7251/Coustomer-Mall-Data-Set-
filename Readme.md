
# Customer Mall Data Set - Customer Segmentation Project

This repository contains a project focused on customer segmentation using a mall's customer data. The objective is to analyze the dataset and apply unsupervised learning techniques, such as K-Means clustering, to group customers based on their shopping behavior and characteristics. This segmentation can help businesses in targeted marketing, improving customer experiences, and optimizing mall operations.

## Table of Contents
- [Project Overview](#project-overview)
- [Data](#data)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Clustering Techniques](#clustering-techniques)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
Customer segmentation is a crucial strategy for businesses to better understand their customer base and tailor marketing strategies accordingly. This project applies clustering techniques to the mall's customer data to create meaningful groups based on spending patterns and other relevant features.

Key steps in the project include:
1. Data loading and preprocessing.
2. Exploratory Data Analysis (EDA).
3. Application of K-Means clustering to segment customers.
4. Visualizing and interpreting the clusters for business insights.

## Data
The dataset used for this project includes the following features:
- **CustomerID**: Unique ID assigned to each customer.
- **Gender**: Gender of the customer.
- **Age**: Age of the customer.
- **Annual Income (k$)**: The annual income of the customer in thousands of dollars.
- **Spending Score (1-100)**: A score assigned to the customer based on their spending behavior in the mall.

### Source
The dataset is publicly available and can be found in the repository.

## Dependencies
The project is built using the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Installation
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/someshsingh-7251/Coustomer-Mall-Data-Set-.git
    cd Coustomer-Mall-Data-Set-
    ```

2. (Optional) Set up a virtual environment:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use: env\Scripts\activate
    ```

3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

4. Launch Jupyter Notebook (if needed):
    ```bash
    jupyter notebook
    ```

## Usage
After setting up the environment, you can explore the Jupyter notebook provided in the repository to follow along with the customer segmentation process. The notebook guides you through:

1. **Loading the dataset**.
2. **Data preprocessing** such as handling missing values or encoding categorical features.
3. **Exploratory Data Analysis (EDA)** to understand the relationships between the features (age, gender, spending score, etc.).
4. **Applying the K-Means algorithm** to identify distinct clusters of customers based on their spending patterns and income levels.
5. **Visualizing the clusters** using plots to interpret customer groups.

## Clustering Techniques
In this project, **K-Means Clustering** is used to segment the customers. The optimal number of clusters is determined using the **Elbow Method**, which helps in identifying the "elbow point" in the plot of within-cluster sum of squares (WCSS).

### Steps for K-Means Clustering:
1. Feature scaling is applied to normalize the data.
2. The Elbow Method is used to determine the optimal number of clusters.
3. K-Means is applied to group customers based on their characteristics.
4. Results are visualized using 2D and 3D scatter plots to represent the customer clusters.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to your branch (`git push origin feature-branch`).
5. Open a pull request and describe the changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

*Note: Feel Free to Contact at Instagram: https://www.instagram.com/officialsomeshchinkusingh?igsh=MW1vdTZwbDdmMTZxbw==*
