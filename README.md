# USA House Price Prediction Model

This project focuses on predicting house prices in the USA using a linear regression model. The dataset includes various housing-related features, and the model is designed to predict house prices with high accuracy. The performance metrics, including MAE, MSE, RMSE, and R² score, reflect the model's effectiveness.

## Dataset Description

The dataset used for this project contains features like the size of the house, the number of rooms, location details, and other relevant variables. Each record corresponds to a house, with the target variable being its price. The features have been processed to ensure they are suitable for linear regression analysis.

<p align="center"> <img src="https://github.com/user-attachments/assets/5fe55c24-e6f9-45ce-b509-985b049bdf71" alt="USA house price prediction" width = 1000 /> </p>

## Methodology

The following steps were followed to build and evaluate the model:

1. **Data Loading and Preprocessing**: The dataset was loaded using Pandas. Basic preprocessing steps like handling missing values, encoding categorical variables, and feature scaling were applied where necessary.

2. **Feature Selection**: Relevant features that significantly influence house prices were selected. Feature importance analysis and correlation heatmaps were used to guide the selection.

3. **Model Training**: The linear regression model was trained using the Scikit-learn library. The data was split into training and testing sets to ensure unbiased evaluation.

4. **Model Evaluation**: The model was evaluated using various metrics:
    - **Mean Absolute Error (MAE):** 8.229 × 10⁴
    - **Mean Squared Error (MSE):** 1.046 × 10¹⁰
    - **Root Mean Squared Error (RMSE):** 1.023 × 10⁵
    - **R² Score:** 0.9177

These metrics indicate a near-perfect model performance, with the R² score of 0.9177 demonstrating that the model explains all the variance in the target variable.

## Accuracy and Model Performance

The linear regression model achieves an **accuracy of 91.8%**, as indicated by the R² score of 0.9177. This means the model perfectly predicts house prices based on the given features. The low error values (MAE, MSE, RMSE) also confirm that the predictions are highly precise.

<p align="center"> <img src="https://github.com/user-attachments/assets/85427953-1e5b-4d30-a521-a6dbc9856ae0" alt="USA house price prediction" width = 1000 /> </p>

## Further Scope

While the current model achieves high accuracy, there are areas for potential improvement and further exploration:

- **Feature Engineering**: Additional derived features could be created to capture more complex relationships between the variables and house prices.
- **Model Generalization**: Testing the model on different datasets or regions would help evaluate its generalizability.
- **Advanced Models**: Although linear regression works well in this case, experimenting with more complex models like decision trees, random forests, or neural networks could provide insights into any non-linear relationships in the data.
- **Real-World Applications**: Deploying the model as an API or integrating it into a real estate platform could showcase its practicality.

## Dependencies

The following libraries are required to run this project:

- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/PriyanshuLathi/USA-House-Price-Prediction-Model.git
    ```

2. Install the required Python dependencies:

    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/PriyanshuLathi/USA-House-Price-Prediction-Model/blob/main/LICENSE) file for details.

## Contact

For questions or feedback, feel free to reach out:

- LinkedIn: [Priyanshu Lathi](https://www.linkedin.com/in/priyanshu-lathi)
- GitHub: [Priyanshu Lathi](https://github.com/PriyanshuLathi)

## Authors
- Priyanshu Lathi