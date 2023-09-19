
# Historical Product Demand Forecasting 📈🌏

## About the Dataset 📊

### Context 🌟

The dataset contains historical product demand data for a globally operating manufacturing company. This company offers thousands of products across dozens of categories and operates from four central warehouses responsible for different regions. Usually, it takes over a month to ship products via ocean to the respective central warehouses due to the production locations being spread across various parts of the world. Achieving accurate forecasts for the monthly demand for the month after next can greatly benefit the company in several ways.

### Content 📁

The primary data file in this dataset is:

- `Historical Product Demand.csv`: A CSV file containing the demand data for encoded product IDs.

### Acknowledgements 🙏

This dataset comprises real-life data, with product, warehouse, and category information being encoded for confidentiality.

### Inspiration 💡

Is it feasible to accurately forecast the demands for thousands of products, including those with highly variable monthly demands, for the month after next? Explore this dataset to find out!

## Getting Started 🚀

### Requirements 🛠️

To work with this project, Python 3.8 or above is recommended. It is best practice to create a virtual environment using pyenv. Below are the instructions to set up a pyenv named `myenv_prophet`:

1. First, install pyenv following the instructions [here](https://github.com/pyenv/pyenv#installation).
2. Next, install Python 3.8 or above using pyenv:
   ```sh
   pyenv install 3.8.0
   ```
3. Create a new virtual environment named `myenv_prophet`:
   ```sh
   pyenv virtualenv 3.8.0 myenv_prophet
   ```
4. Activate the virtual environment:
   ```sh
   pyenv activate myenv_prophet
   ```
5. Once inside the virtual environment, install the necessary packages listed in the `requirements.txt` section below:
   ```sh
   pip install -r requirements.txt
   ```

### Setting Up the Forecasting Environment 🌐

To set up the forecasting environment, use the `fbprophet` package. You can find more details about this package [here](https://facebook.github.io/prophet/).

## Contribution 🤝

Feel free to fork this project and contribute by submitting pull requests. Let's work together to improve the forecasting accuracy and help the company grow!

## License 📜

This project is licensed under the MIT License. See the LICENSE file for more details.

## `requirements.txt` 📝

To install the necessary packages, create a `requirements.txt` file with the following content:

```
pystan==2.19.1.1
fbprophet
pandas
numpy
matplotlib
```
```
