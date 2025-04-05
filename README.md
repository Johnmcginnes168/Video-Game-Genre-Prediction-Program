

# Video Game Genre Prediction Program

This project predicts the top video game genres for the year 2018 based on historical video game sales data from 1980 to 2016. The model uses machine learning techniques, specifically the Gradient Boosting Regressor, to forecast global sales for different video game genres. The aim is to help Bethesda Softworks make informed decisions about game development, marketing strategies, and resource allocation.

## Features

- Predicts the top video game genres for 2018.
- Built using the Gradient Boosting Regressor machine learning model.
- Interactive visualizations for exploring historical sales trends and predictions.
- Provides predictive insights into video game sales for better decision-making.

## Dataset

This project uses the **Video Game Sales dataset** from Kaggle, which includes global sales data by region, genre, and publisher information. The data spans from 1980 to 2016 and is publicly available [here](https://www.kaggle.com/datasets/ulrikthygepedersen/video-games-sales).

## Requirements

To run the program locally, you need the following:

- **Python** (version 3.12.3 or higher)
- **Jupyter Notebook**
- The following Python libraries:
  - `pandas`
  - `scikit-learn`
  - `ipywidgets`
  - `matplotlib`
  - `seaborn`

## Installation

1. **Install Python 3.12.3**:
   Download and install Python from the [official website](https://www.python.org/downloads/). Make sure to check the box to "Add Python to PATH" during installation.

2. **Install Jupyter Notebook**:
   Run the following command in your terminal or command prompt:
   ```bash
   pip install notebook
   ```

3. **Install necessary libraries**:
   Run the following command to install the required libraries:
   ```bash
   pip install pandas scikit-learn ipywidgets matplotlib seaborn
   ```

4. **Download the project files**:
   Download the following files:
   - `C964_Task2_Video_Game_Genre_Predictor.ipynb`
   - `Video_Games_Sales_as_of_2016.csv`

   Place them in the same directory on your local machine.

5. **Open Jupyter Notebook**:
   Navigate to the directory where you saved the files and run the following command in your terminal:
   ```bash
   jupyter notebook
   ```

6. **Run the program**:
   Open `C964_Task2_Video_Game_Genre_Predictor.ipynb` in Jupyter Notebook, then run all cells by selecting **Run All** from the **Run** menu or by pressing `Shift + Enter`.

## Usage

1. **Select a Genre**:
   Once the program runs, you'll see a dropdown menu where you can select a video game genre.
   
2. **View Predicted Sales**:
   After selecting a genre, the model will display its predicted sales for 2018.
   
3. **Explore Visualizations**:
   The program will also generate visualizations to help you better understand sales trends and predictions, including:
   - Sales trends for different genres in the North American market.
   - Global sales distribution across all regions.
   - Correlation matrix of sales features.
   - Top 3 predicted genres for 2018 by global sales.

## Machine Learning Model

The project utilizes the **Gradient Boosting Regressor**, an ensemble machine learning algorithm that builds multiple decision trees to improve the accuracy of predictions. The model was trained on historical video game sales data and validated using cross-validation techniques to ensure accurate forecasts.

### Performance Metrics

- **R-squared**: 0.99 (Goal: > 0.80)
- **Mean Absolute Error (MAE)**: 0.0229 million units (Goal: < 0.05)
- **Cross-validated MAE**: 0.0353 million units (Goal: < 0.05)
- **Runtime**: 6 seconds (Goal: < 10 seconds)

## Visualization Examples

- **Sales Trends for Different Genres**: A line plot showing sales trends over time for different genres in North America.
- **Global Sales Distribution**: A pie chart showing the distribution of sales across all regions.
- **Top 3 Predicted Genres for 2018**: A bar plot displaying the genres expected to dominate the market in 2018.


## Acknowledgements

- **Kaggle**: The dataset used for this project is sourced from Kaggle’s "Video Game Sales" dataset (Pederson, U.T., 2021).
- **Gradient Boosting Regressor**: The machine learning algorithm used for this project is implemented via the `scikit-learn` library.


