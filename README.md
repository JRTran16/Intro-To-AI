# Housing Price Prediction

This project focuses on building a Machine Learning model to predict housing prices based on various features. The dataset contains housing attributes like area, number of bedrooms, bathrooms, and additional amenities.

## Dataset Overview

The dataset (`Housing.csv`) contains 545 entries with the following columns:

- **price**: Price of the house
- **area**: Area of the house (in square feet)
- **bedrooms**: Number of bedrooms
- **bathrooms**: Number of bathrooms
- **stories**: Number of stories
- **mainroad**: Whether the house is on the main road (yes/no)
- **guestroom**: Availability of guestroom (yes/no)
- **basement**: Availability of basement (yes/no)
- **hotwaterheating**: Availability of hot water heating (yes/no)
- **airconditioning**: Availability of air conditioning (yes/no)
- **parking**: Number of parking spots
- **prefarea**: Whether the house is in a preferred area (yes/no)
- **furnishingstatus**: Furnishing status (furnished, semi-furnished, unfurnished)

## Project Workflow

The Jupyter Notebook (`HousingPracticeML.ipynb`) outlines the steps taken to build and evaluate the model:

1. **Data Cleaning**:
   - Checked for missing values. No missing data was found.

2. **Data Preprocessing**:
   - Categorical variables were converted to numerical values using One-Hot Encoding.

3. **Splitting the Dataset**:
   - The data was split into training and testing sets.

4. **Model Training**:
   - A regression model was trained on the dataset.

5. **Model Evaluation**:
   - The model's performance was evaluated using metrics such as Mean Squared Error (MSE) and R-squared.

6. **Visualization**:
   - Plots were generated to visualize the actual vs predicted prices and residuals distribution.

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/housing-price-prediction.git
   cd housing-price-prediction
   ```

2. Install the required libraries:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook HousingPracticeML.ipynb
   ```

## Results

- **Actual vs Predicted Housing Prices**: A scatter plot was used to visualize how well the model's predictions match actual prices. Points close to the diagonal line indicate accurate predictions.
- **Residuals Distribution**: The residual plot showed how errors were distributed, helping to assess model performance and identify potential issues.

## Contributing

Feel free to fork the repository and submit pull requests. For significant changes, please open an issue first to discuss what you'd like to change.

## Contact

For any inquiries or suggestions, please contact [johnraytran@gmail.com].

