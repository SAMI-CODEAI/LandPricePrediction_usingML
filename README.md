# Land Price Prediction Based on Square Feet Using Linear Regression

This project uses a linear regression model to predict land prices based on the land's square footage. The dataset consists of land area (in square feet) and corresponding land prices. The goal is to build a model that can accurately predict the price of land based on its size.

## Dataset
The dataset used for this project is a CSV file containing the following columns:
- `land`: The area of land in square feet.
- `price`: The price of the land in dollars.

You can find the dataset in the file `landpriceprediction.csv`.

## Project Structure
- **LandPricePrediction.ipynb**: Jupyter notebook containing the code for loading, preprocessing, visualizing the dataset, training the linear regression model, and making predictions.
- **landpriceprediction.csv**: The dataset file.

## Installation
To run this project, you need the following libraries:
- pandas
- numpy
- scikit-learn
- matplotlib

You can install them using the following command:

```bash
pip install pandas numpy matplotlib scikit-learn
```

If you're using Google Colab, you can also upload the dataset using the file upload feature.

## Steps to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/SAMI-CODEAI/LandPricePrediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd LandPricePrediction
   ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook LandPricePrediction.ipynb
   ```
4. Upload the dataset file (`landpriceprediction.csv`) when prompted.

## Model Training
The project uses a simple linear regression model from `scikit-learn` to predict land prices based on the area of land. The training process involves the following steps:
1. Load and preprocess the dataset.
2. Visualize the data.
3. Split the data into input features (`X`) and target labels (`Y`).
4. Train the linear regression model.
5. Make predictions and evaluate the model's performance.

## Prediction Example
For example, if you want to predict the price of a land area of 6660 square feet, the model will return a predicted price of approximately **$14,060.75**.

## Results
The model coefficients (slope and intercept) are displayed as follows:
- Coefficient (`m`): 2.0407
- Intercept (`b`): 469.47

The prediction formula used by the model is:  
**Price = m * Area + b**

## Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit pull requests.

## License
This project is licensed under the MIT License.

## Contact
For any questions, feel free to reach out:
- Email: your-sami.codeai@gmail.com
- GitHub: [SAMI-CODEAI](https://github.com/SAMI-CODEAI)

