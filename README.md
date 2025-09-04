# Simple-Machine-Learning-Model
This project demonstrates how to build a simple (music recommendation system using a {Decision Tree Classifier} in Python.

The workflow includes:
1. Loading the Data
   Importing the dataset (`music.csv`) into a Pandas DataFrame.
2. Preparing Data
   - Splitting the dataset into **features (X: age, gender)** and **labels (y: genre)**.
   -  Creating training and test sets with `train_test_split`.
3. Training the Model
   - Building a `DecisionTreeClassifier` model.
   - Training the model on the dataset.
   -Making predictions for given inputs (e.g., `[21, 1]` = age 21, male).
4. Evaluating Performance
   - Checking accuracy by comparing predicted genres with test data.
5. Persisting the Model
   - Saving the trained model using `joblib`.
   - Reloading the model and using it to make predictions.
6. Visualizing the Decision Tree
   - Exporting the trained decision tree into a `.dot` file using `export_graphviz`.
   - Rendering the visualization with **Graphviz** for better interpretability.
