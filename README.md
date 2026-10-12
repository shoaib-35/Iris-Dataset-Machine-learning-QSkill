# Iris Flower Classification

A machine learning project completed as part of the **QSkill Artificial
Intelligence & Machine Learning Internship**. The project uses the Iris
dataset to classify flowers into **Setosa**, **Versicolor**, or
**Virginica** based on sepal and petal measurements.

## Internship Information

-   **Domain:** Artificial Intelligence & Machine Learning
-   **Internship period:** 14 September 2026 -- 14 October 2026
-   **Task:** Iris Flower Classification

## Objective

Build and evaluate a classification model that predicts an Iris flower
species from four measurements:

-   Sepal length (cm)
-   Sepal width (cm)
-   Petal length (cm)
-   Petal width (cm)

## Dataset

This project uses the built-in Iris dataset provided by `scikit-learn`.
It contains 150 samples across three species:

-   Setosa
-   Versicolor
-   Virginica

Each sample has four numeric features. The dataset is loaded directly in
the notebook, so a separate dataset download is not required.

## Project Workflow

1.  Load the Iris dataset using `scikit-learn`.
2.  Create a Pandas DataFrame and inspect the data and descriptive
    statistics.
3.  Explore feature distributions with histograms.
4.  Visualize relationships between features and species, including a
    pair plot.
5.  Split the data into training and test sets.
6.  Establish a simple rule-based baseline using petal length.
7.  Train a Logistic Regression classifier.
8.  Evaluate the model using validation accuracy, cross-validation, and
    final test accuracy.
9.  Inspect incorrectly classified samples and experiment with the
    model's `C` parameter.

## Tools and Libraries

-   Python
-   Jupyter Notebook
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   scikit-learn

## Repository Contents

-   `Iris Flower Classification.ipynb` --- notebook containing data
    exploration, visualizations, model training, and evaluation.

## How to Run

1.  Install Python 3.10 or later (or use an environment that already
    supports the libraries below).

2.  Clone or download this repository.

3.  Install the dependencies:

    ``` bash
    pip install -r requirements.txt
    ```

4.  Start Jupyter:

    ``` bash
    jupyter notebook
    ```
    or if you want it in another browser tab

    ``` bash
    jupyter notebook &
    ```

6.  Open `Iris Flower Classification.ipynb` and run the cells from top
    to bottom.

## Results

The current notebook records a **97.37% test accuracy** for its final
Logistic Regression model. Because the notebook's train/test and
validation splits do not currently specify a fixed `random_state`, the
exact result may change when the notebook is run again.

## Notes and Possible Improvements

-   Set `random_state=42` in the train/test and validation splits to
    make the experiments reproducible.
-   Add a confusion matrix and a classification report with precision,
    recall, and F1-score for a more complete evaluation.
-   Keep the final test set separate from model selection and tuning.
-   Restart the notebook kernel and run all cells before submitting,
    then confirm that the outputs and reported result are consistent.

## Internship Requirement Coverage

---------------------------------------------------------------------------
| QSkill requirement               | Project coverage                       |
|----------------------------------|---------------------------------------|
| Load the Iris dataset            | Uses `scikit-learn`'s built-in dataset  |
| Explore the dataset visually     | Histograms, feature/target plots, and pair plot    |
| Split training and test data     | Uses `train_test_split`               |
| Preprocess if needed             | Dataset is used without additional cleaning     |
| Train a classifier               | Logistic Regression, plus a simple rule-based baseline    |
| Evaluate the model               | Validation accuracy, cross-validation, and test accuracy               |
---------------------------------------------------------------------------
## Author

Prepared for the QSkill AI & ML Internship.
