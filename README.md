# CODSOFT-TASK-1-MOVIE-RATING-PREDICTION-
🎬 Movie Rating Prediction using Python 🎬
This project is part of my internship at Codsoft, where I developed a Machine Learning model to predict movie ratings based on IMDb data. The goal was to analyze historical movie data and build a predictive model that estimates the rating given to a movie based on features such as year, duration, and votes.

🚀 Project Overview
This project focuses on using Linear Regression to predict the ratings of movies from an IMDb dataset. The primary goal is to explore data preprocessing, feature engineering, and model building using Python and Scikit-learn.

Features used for prediction:
Year: The release year of the movie.
Duration: Movie runtime in minutes.
Votes: Number of votes the movie received on IMDb.
Libraries Used:
pandas: For data manipulation and cleaning.
numpy: For numerical operations.
matplotlib & seaborn: For visualizing data and results.
scikit-learn: For building and evaluating the machine learning model.
🛠️ Project Workflow
Data Cleaning:

Remove missing values in key features (Rating, Votes).
Convert Duration and Votes to numeric values suitable for model training.
Extract year information from strings.
Data Preprocessing:

Use SimpleImputer to fill missing values in Year, Duration, and Votes.
Normalize features for better performance in the model.
Modeling:

A Linear Regression model was trained to predict movie ratings based on the selected features.
The dataset was split into training (80%) and testing (20%) sets for model evaluation.
Evaluation:

The model was evaluated using Mean Squared Error (MSE) and R-squared (R²) to determine prediction accuracy.
Visualization of Actual vs Predicted Ratings was created using matplotlib.
📊 Results
The model performed reasonably well on the test set with the following metrics:

Mean Squared Error:
R-Squared Score:
Below is a plot of the Actual vs Predicted Ratings:

🔧 Installation and Setup
# Clone the repository
git clone https://github.com/Jeevanreddygopidi/CODSOFT-TASK-1-MOVIE-RATING-PREDICTION.git
cd movie-rating-prediction

# Create a virtual environment (recommended)
python -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

# Install the required libraries
pip install pandas numpy matplotlib seaborn scikit-learn

# Run the project
python movie_rating_prediction.py

# Deactivate the virtual environment when done
deactivate

🔍 Key Takeaways
Data Preprocessing is crucial to improving model performance.
Feature Engineering such as extracting year data and handling missing values can significantly impact the results.
Visualizing the results helps in understanding model performance better.
🎯 Future Improvements
Explore more advanced models like Random Forests, Gradient Boosting, and XGBoost to improve prediction accuracy.
Add more features like genre, director, and actor popularity to make predictions more robust.
🤝 Contributing
Feel free to fork this project and submit pull requests. For major changes, please open an issue first to discuss what you would like to improve.

📝 License
This project is licensed under the MIT License - see the LICENSE file for details.
Contributing
Contributions are welcome! Please open an issue or submit a pull request on GitHub.

Contact
For any questions or suggestions, please contact jeevanreddy.work@gmail.com
