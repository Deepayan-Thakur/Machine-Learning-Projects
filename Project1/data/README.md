# Data Description for Titanic Survival Prediction 🚢

This folder contains the data files used in the Titanic Survival Prediction project. Below is an overview of the dataset, including features and target variables.

## Data Files

### `data/raw/`
- **`titanic.csv`**: The raw dataset for further cleaning and preprocessing model.

### `data/processed/`
- **`titanic_processed.csv`**: The processed dataset after cleaning and transformation.

## Features and Target

### Features in `titanic.csv`
- **`PassengerId`**: Unique identifier for each passenger.
- **`Pclass`**: Passenger class (1st, 2nd, or 3rd).
- **`Name`**: Name of the passenger.
- **`Sex`**: Gender of the passenger (male or female).
- **`Age`**: Age of the passenger in years.
- **`SibSp`**: Number of siblings or spouses aboard the Titanic.
- **`Parch`**: Number of parents or children aboard the Titanic.
- **`Ticket`**: Ticket number.
- **`Fare`**: Amount of money paid for the ticket.
- **`Cabin`**: Cabin number (if available).
- **`Embarked`**: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).

### Target Variable
- **`Survived`**: Whether the passenger survived (1) or did not survive (0). This is present in the `train.csv` file and is used for training the model.

## Processed Data

The `titanic_processed.csv` file in the `data/processed/` folder contains the cleaned and transformed dataset. It includes:
- **Feature Engineering**: Includes features like `Age_Group` or `Fare_Band` if created.
- **Handling Missing Values**: Imputed or removed missing values.
- **Encoding Categorical Variables**: Categorical features such as `Sex` and `Embarked` may be encoded into numerical values.

## Example

To view the features and target in the processed dataset, load `titanic_processed.csv` and examine its contents. You can use pandas in Python for this:

```python
import pandas as pd

# Load the processed dataset
data = pd.read_csv('data/processed/titanic_processed.csv')

# Display the first few rows of the dataset
print(data.head())
