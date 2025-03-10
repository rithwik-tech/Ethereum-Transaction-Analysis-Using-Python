# Ethereum-Transaction-Analysis-Using-Python

Overview
This project involves analyzing Ethereum blockchain transaction data to gain insights into transaction trends, gas usage, failed transactions, and more. The dataset includes key attributes such as block numbers, timestamps, transaction values, gas usage, and whether the transaction was successful or failed.

The analysis includes:

Total transaction value
Gas usage statistics
Transaction trends over time
Distribution of gas prices
Failed transactions
Visualization of transaction value vs gas price
Dataset
The dataset consists of Ethereum transaction data, including the following columns:

block_number: Unique identifier for each block.
timestamp: Date and time of the transaction.
hash: Unique identifier for the transaction.
from_address: Sender's address.
to_address: Receiver's address.
value: Amount of Ether transferred.
gas: Gas used for the transaction.
gas_price: Price of gas during the transaction.
is_error: 0 for successful transactions and 1 for failed transactions.
Requirements
To run this analysis, you need to have Python and the following libraries installed:

pandas
matplotlib
seaborn
You can install the required libraries using the following:

pip install pandas matplotlib seaborn
Files Included
Ethereum_Transactions_100.csv: The dataset file with 100 Ethereum transaction records.
analysis.py: Python script for analysis.
Running the Analysis
Download or clone the repository.
Place the Ethereum_Transactions_100.csv file in the same directory as the script.
Run the Python script using:
bash
Copy
Edit
python analysis.py
The script will generate various analyses, including:

A bar chart of transaction trends over time.
A histogram of gas price distribution.
A scatter plot of transaction value vs gas price.
It will also output the failed transactions into a separate CSV file called Failed_Transactions.csv.

License
This project is licensed under the MIT License - see the LICENSE file for details.

