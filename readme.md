# Crypto API Automation and Data Transformation

This repository contains Python scripts that automate the retrieval of cryptocurrency data from the CoinMarketCap API, store the data in a CSV file, perform data transformation and visualization.

## Automating the Data Pull

### Overview
- **API Runner:** Utilizes the CoinMarketCap API to retrieve cryptocurrency data periodically and store it in a CSV file.
- **Transforming Data:** Processes the data, calculates mean percentage changes for various timeframes, transforms it, and performs visualization.

### Steps Performed
1. **API Runner Function:** Makes requests to the CoinMarketCap API, retrieves data, normalizes it, and saves it to a CSV file.
2. **Automated Data Pull:** Loops through API calls, retrieves data, and stores it in a CSV file repeatedly with a time delay.
3. **Data Transformation:** Groups cryptocurrency data by 'name' and calculates mean percentage changes for different timeframes.
4. **Visualization:** Generates visualizations using Seaborn library to display cryptocurrency data trends.

## How to Use:

1. **API Key:** Replace `'X-CMC_PRO_API_KEY'` in the API call with your own CoinMarketCap API key.
2. **Python Environment:** Ensure the necessary Python libraries (`requests`, `pandas`, `seaborn`, `matplotlib`) are installed.
3. **Data Storage:** Adjust the file paths in the script to store the CSV file in your desired location.
4. **Data Transformation and Visualization:** Modify code parameters, if needed, for data transformations or different visualization styles.

## Notes:

- The script assumes access to the CoinMarketCap API and requires an API key for data retrieval.
- Adjust the file paths, API key, and any other parameters as per your requirements.
- This script includes a loop for automated data pulls; ensure it aligns with your intended data retrieval frequency.

Please refer to the comments within the code for detailed explanations of each step and adapt the code as per your cryptocurrency analysis needs.

For any questions or improvements, feel free to open an issue or submit a pull request.
