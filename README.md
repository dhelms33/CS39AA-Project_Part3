# CS39AA-Project-DH

# Smoking and Gender Analysis Project

## Project Overview

This project aims to construct a RF and FF model to see which model predicts the charges of the healthcare dataset with a lower Mean Absolute Error.

## Dataset Information

- **Dataset Name**: Healthcare Insurance
- **Dataset Source**: https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance/
- **Dataset Description**: This dataset contains information on the relationship between personal attributes (age, gender, BMI, family size, smoking habits), geographic factors, and their impact on medical insurance charges. It can be used to study how these features influence insurance costs and develop predictive models for estimating healthcare expenses.
Age: The insured person's age.

Sex: Gender (male or female) of the insured.

BMI (Body Mass Index): A measure of body fat based on height and weight.

Children: The number of dependents covered.

Smoker: Whether the insured is a smoker (yes or no).

Region: The geographic area of coverage.

Charges: The medical insurance costs incurred by the insured person.

## Analysis Goals

- To determine the cost of insurance based on the available attributes (Age, BMI, Smoker (y/n), Region,)


## Data Preprocessing

- Data Cleaning: Done in part 2
- Feature Selection: Done in part 2/3

## Methodology

- Models Used: Linear regression, Random Forest
- Evaluation Metrics: Age, BMI, Smoker (y/n), Region, Children
## Results

- MAE for RF Model: 2532.2459332975795
- MAE for FF Model: 8710.7676

## Conclusion

- The Feed Forward Model produced a significantly worse MAE than the Random Forest Model.

## How to Run the Code

- Fork the repository from GitHub.
- Clone the repository to your local machine.
- Open the repository in your IDE of choice.
- Install Python, Matlab, and Jupyter Notebook.
- Run the cells

## Project Structure

- Several intermitten sections with markdown cells explaining the results of the code. 

## Dependencies

- pytorch
- numpy
- pandas
- matplotlib
- seaborn
- sklearn

## Author

- Dereck Helms
- dereckhelmsdev@gmail.com

## License

- MIT License

## Acknowledgments

- https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance


## Feedback

- I welcome feedback and suggestions. If you have any questions or recommendations, please contact Dereck Helms via the email above.

