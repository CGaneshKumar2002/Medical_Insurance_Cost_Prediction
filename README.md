# Medical Insurance Cost Prediction

This project aims to predict medical insurance costs based on various factors such as age, BMI, smoking status, region, etc. By using machine learning techniques, we can estimate the medical insurance costs for individuals and gain insights into the factors that contribute to higher or lower costs.

## Dataset

The project utilizes a dataset containing information about individuals and their medical insurance costs. The dataset includes the following features:

- Age: Age of the individual in years.
- Sex: Gender of the individual (male or female).
- BMI: Body Mass Index, a measure of body fat based on height and weight.
- Children: Number of children the individual has.
- Smoker: Smoking status of the individual (yes or no).
- Region: Geographic region of the individual (northeast, southeast, southwest, northwest).
- Charges: Medical insurance cost for the individual.

The dataset is stored in the file `insurance.csv`.

## Requirements

To run the project, you'll need the following dependencies:

- Python 3.5
- Pandas
- NumPy
- Scikit-learn
- Matplotlib


The script will load the dataset, preprocess the data, train a linear regression model, and then predict medical insurance costs for a set of test data. The predicted costs will be displayed on the console.

## Results

The project achieves a good level of accuracy in predicting medical insurance costs, as indicated by the R-squared (R2) score. The R2 score measures the proportion of the variance in the dependent variable that is predictable from the independent variables. A score closer to 1 indicates a better fit.

## Contributing

Contributions to the project are welcome! If you have any suggestions, improvements, or bug fixes, please submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
