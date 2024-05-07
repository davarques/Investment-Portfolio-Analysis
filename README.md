# Investment Portfolio Analysis

<img src="https://media.licdn.com/dms/image/D5612AQGZb8k1NrXFkg/article-cover_image-shrink_720_1280/0/1677728307518?e=1720051200&v=beta&t=Ye8GLxYm1eSg7rnx94Lmqgi2Q7Z916WKeUpaUQWe9jQ" alt="Portfolio Investment Image" width="600">

## Project Overview 📋

In this practical tech assignment, we are provided with a portfolio of 5 investment assets, and our goal is to apply our Python knowledge to review and assess the investment portfolio.

### Available Datasets 💾

| Dataframes              |
|-------------------------|
| [Asset Information Data](https://drive.google.com/file/d/1GsL7vAatihCZGr-M2v5iR5tMNxtQlX0s/view?usp=drive_link) |
| [Asset Price Data](https://drive.google.com/file/d/1EwcJlExRlA7Ym3LakOrKm6SD360d_iey/view?usp=drive_link)       |
| [Portfolio Weights Data](https://drive.google.com/file/d/1RDrqtFPiiCfLMJPkiIK0gL5XRjsoiXO1/view?usp=drive_link) |

## Tasks ✏️

- **Exercise 1: Data Loading and Price Charting**
  - Import the three available datasets: `asset_price`, `asset_information`, and `portfolio_weights`
  - Visualize the portfolio’s assets with a time series graph.

- **Exercise 2: Daily Percentage Returns**
  - Calculate asset’s daily percentage returns.
  - Calculate the correlation matrix for the five assets.
  - Create a scatter plot comparing the returns of two specific assets.

- **Exercise 3: Portfolio Analysis**
  - Create an area chart of the asset weights.
  - Plot the historical cumulative returns of the portfolio.
  - Calculate the annualized return of the portfolio.
  -  Determine the annualized volatility of the portfolio (using an annualization factor of 261 days).
  -  Produce an area chart grouping asset weights by their categories, as detailed in the `asset_information_data.csv`.

## Results 🎯

- **1) Price Time Series Graph:** Distribution of the 5 portfolio assets across time (2019-2022).

<img src="https://github.com/davarques/Investment-Portfolio-Analysis/assets/160759223/00f77654-d0b7-4037-b1a5-ebd5b5f6d07a" width="600">

- **2.1) Correlation Matrix Heatmap** with the Asset’s daily returns. 

<img src="https://github.com/davarques/Investment-Portfolio-Analysis/assets/160759223/603e4875-e5a7-4434-8d2c-7e0c78c45795" width="500">

- **2.2) Scatter Plot:** Comparing two specific assets: Asset 2 (Fixed Income) vs. Asset 3 (Equity)

<img src="https://github.com/davarques/Investment-Portfolio-Analysis/assets/160759223/e5b94bc1-0eec-49ce-9f9f-bfe09b96117d" width="600">

- **3.1) Asset's Weights (%) distribution through Area Charts**
  
   - By Asset number:
     
    <img src="https://github.com/davarques/Investment-Portfolio-Analysis/assets/160759223/e9ef12f6-ddce-4a73-b69e-34ea82303f49" width="400">

   - By Family type:
     
    <img src="https://github.com/davarques/Investment-Portfolio-Analysis/assets/160759223/95920d32-5fdc-40e6-a8ff-5e8ed7d52c14" width="400">

- **3.2) Portfolio Analysis:** Annualized return and volatility
  
    ![Screenshot 2024-05-07 at 20 52 43](https://github.com/davarques/Investment-Portfolio-Analysis/assets/160759223/c4b4bb18-fb69-4115-a9e9-241ec8570a01)

    ![Screenshot 2024-05-07 at 20 52 54](https://github.com/davarques/Investment-Portfolio-Analysis/assets/160759223/1adc2817-c702-4be3-adbc-72d95cb22064)

- **3.3) Portfolio's Return:** Historical Cumulative Returns.

<img src="https://github.com/davarques/Investment-Portfolio-Analysis/assets/160759223/597b0872-691f-42ab-9ab4-781a912420e4" width="600">


