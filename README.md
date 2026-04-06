Calorie Burn Predictor (Linear Regression from Scratch)

This project predicts the number of calories burned during physical activity by implementing Linear Regression from scratch using gradient descent, without relying on machine learning libraries like Scikit-learn.

 Features

- Predicts calories burned based on input features
- Implements Linear Regression manually
- Uses gradient descent optimization
- Includes data visualization for better insights

 Concepts Implemented

- Linear Regression (from scratch)
- Gradient Descent
- Cost Function (Mean Squared Error)
- Parameter optimization (weights & bias)
- Feature-target relationships

 Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib



 Input Features

- Age
- Weight
- Height
- Duration of exercise
- Heart rate

How It Works

The model learns by minimizing error using gradient descent:

- Initialize weights and bias
- Compute predictions
- Calculate error using Mean Squared Error
- Update parameters using gradients
- Repeat until convergence

Cost Function

The model minimizes Mean Squared Error:

 How to Run

1. Clone the repository:

git clone https://github.com/tiwalolui/Calories-predictor.git
cd calories-predictor

2. Install dependencies:

pip install -r requirements.txt

3. Run the project:

python src/calorie_predictor.py

Output

- Predicted calories burned
- Optional visualizations of trends
- (Optional) Loss reduction over iterations

Future Improvements

- Compare with Scikit-learn implementation
- Optimize learning rate tuning
- Extend to multiple regression features
- Deploy using Streamlit

Learning Outcome

This project helped reinforce:

- The mathematics behind Linear Regression
- How gradient descent works internally
- Building ML models without external libraries
- Understanding optimization techniques

Author

*IGE TIWALOLU*
