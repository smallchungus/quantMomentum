# Equal Weighted S&P Fund Calculator

This script allows users to calculate the number of shares they need to buy in order to emulate an equal weighted S&P fund. The script calls the IEX cloud API to get stock ticker data and returns the results in an xlsx file named "recommended trades".

## Prerequisites

To use this script, you will need an API key from IEX Cloud. You can sign up for a free account and obtain an API key here. Once you have your API key, save it to a file named sec.py in the same directory as the script, using the following format:

makefile
Copy code
API_KEY = "your_api_key_here"
You will also need the following Python libraries installed:

pandas
requests
numpy
You can install these libraries using anaconda:


## Usage
To use this script, run the code in jupyter notebook with python 3.9

The script will prompt you to enter your portfolio value. Enter the value as a number without commas or dollar signs.

The script will then call the IEX cloud API to get stock ticker data and calculate the number of shares you need to buy for each stock in the S&P 500 in order to emulate an equal weighted S&P fund. The results will be saved in an xlsx file named "recommended trades" in the same directory as the script.

Note: the API call may take a few minutes to complete, depending on your internet connection speed.

## Acknowledgements 
https://github.com/nickmccullum

## License
This script is licensed under the MIT License.
