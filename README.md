# Time Series Forecasting Analysis For Corporation Favorita ⏰

Welcome to the **Time Series Forecasting Project**. The mission is to predict store sales using data from Corporation Favorita, a major grocery retailer in Ecuador, using Machine Learning techniques.

![Python Version](https://img.shields.io/badge/Python-3.11-blue)
![Data Analysis](https://img.shields.io/badge/Data-Analysis-yellow)
![Data Visualization](https://img.shields.io/badge/Data-Visualization-orange)
![Hypothesis Testing](https://img.shields.io/badge/Hypothesis-Testing-brightgreen)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-blueviolet)

## Preview 🔍

Below is a preview showcasing some features of the notebook.

<div style="display: flex; align-items: center;">
    <div style="flex: 33.33%; text-align: center;">
        <p>Top</p>
        <img src="Images/Readmepics/Image1.png" alt="Top" width="90%"/>
    </div>
    <div style="flex: 33.33%; text-align: center;">
        <p>Middle</p>
        <img src="Images/Readmepics/Image2.png" alt="Middle" width="90%"/>
    </div>
    <div style="flex: 33.33%; text-align: center;">
        <p>Bottom</p>
        <img src="Images/Readmepics/Image3.png" alt="Bottom" width="90%"/>
    </div>
</div>

## Project Description 📋

The primary focus of this project is to utilize time series regression analysis to forecast sales for Corporation Favorita, a prominent grocery retailer based in Ecuador.

The objective is to develop a robust model capable of accurately forecasting future sales by leveraging the extensive time series data of thousands of products sold across various Corporation Favorita locations. The resulting forecasts will provide valuable insights to the store's management, enabling them to formulate effective inventory and sales plans.

I will utilize the CRISP-DM framework to execute the project.


## Project Overview 🖼

The project includes the following stages:

### 1. 📥 Data Collection

- Azubi Africa's SQL Server database, GitHub repository and OneDrive.

N/B: The datasets from the sources above where saved in the root folder of this repository for easy access

### 2. 📚 Data Loading

- Utilizing `pyodbc` for SQL data
- Leveraging `pandas` for CSV and Excel files

### 3. 💡 Exploratory Data Analysis (EDA)

- Merging
- Duplicate checks
- Handling missing values
- Renaming Columns and Changing Datatypes
- Creating new features
- Visualizations
- Hypothesis testing
- ADF Testing

### 4. 📈 Answering Questions with Visualizations

**Questions:**

- Is the train dataset complete (has all the required dates)?
- Which dates have the lowest and highest sales for each year?
- Did the earthquake impact sales?
- Are certain groups of stores making more sales than others? (Cluster, city, state, type)
- Are sales affected by promotions, oil prices and holidays?
- What analysis can we get from the date and its extractable features?
- What is the difference between RMSLE, RMSE, MSE (or why is the MAE greater than all of them?)
- What is the total sales made each year by the corporation?

**Visualization Tools:**

- Matplotlib
- Seaborn

### 5. ⚙️ Feature Engineering

- Data Splitting
- Feature Encoding with OneHotEncoder
- Feature Scaling with MinMaxScaler

### 6. ⌛ Model Training

- Linear Regression
- XGBoost
- CatBoost
- AutoReg
- ARIMA
- SARIMA

### 7. 📊 Model Evaluation

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Squared Logarithmic Error (MSLE)
- Root Mean Squared Logarithmic Error (RMSLE)

### 8. 🎯 Hyperparameter Tuning

- RandomSearchCV

### 9. 💭 Exportation

- os
- pickle
- save_model

## Installation and Setup 🔧

To get started with this project, you'll need to install the following Python packages using `pip`:

```bash
pip install pyodbc sqlalchemy lightgbm catboost python-dotenv pandas numpy matplotlib seaborn scipy pmdarima
```

Make sure to have these packages installed before running the project.
Follow these steps for installation:

1. Clone this repository to your local machine.
2. Install the required Python packages using pip:
   ```bash
   pip install -r requirements.txt
   ```

You're now ready to dive into this exciting data journey!

## Author 👨‍💼

This project was built by **Chidiebere David Ogbonna**.

Here are his details:

![Author](Images/Author.jpg)

| Detail | Link |
| ------ | ---- |
| Email | eberedavid326@gmail.com |
| LinkedIn | [chidieberedavidogbonna](https://www.linkedin.com/in/chidieberedavidogbonna/) |
| GitHub | [iameberedavid](https://github.com/iameberedavid) |
| Medium | [eberedavid](https://eberedavid.medium.com) |
| Twitter | [iameberedavid](https://twitter.com/iameberedavid) |

## Article Publication 📄

I went further to explain the work process of this project in an article published on Medium. Click on this link to find the article: [TIME SERIES FORECASTING ANALYSIS FOR CORPORATION FAVORITA](https://eberedavid.medium.com/time-series-forecasting-analysis-for-corporation-favorita-4e43df145e50).

## App Deployment 📲

The model was embedded into a streamlit app and deployed for public usage. This was done in this GitHub repository: [Embed-Corporation-Favorita-Timeseries-Model-To-Streamlit](https://github.com/iameberedavid/Embed-Corporation-Favorita-Timeseries-Model-To-Streamlit). The deployment process was discussed in this medium article: [BUILDING A USER-FRIENDLY SALES PREDICTION APP USING STREAMLIT AND HUGGINGFACE](https://eberedavid.medium.com/embedding-timeseries-forecasting-analysis-for-corporation-favorita-model-to-streamlit-eefe13bf8bf2).

## Acknowledgments 🙏

I would like to express my gratitude to the [Azubi Africa Data Analyst Program](https://www.azubiafrica.org/data-analytics) for their support and for offering valuable projects as part of this program. Not forgeting my scrum masters on this project [Rachel Appiah-Kubi](https://www.linkedin.com/in/racheal-appiah-kubi/) & [Emmanuel Koupoh](https://github.com/eaedk)

## License 📜

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Contact 📧

For questions, feedback, and collaborations, please contact [Chidiebere David Ogbonna](eberedavid326@gmail.com).
