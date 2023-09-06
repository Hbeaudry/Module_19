# Module_19

## KryptoJobs2Go Application Ethereum Integration - README Summary

This README provides a brief overview of the steps required to integrate Ethereum transaction functionality into the KryptoJobs2Go application. The integration involves importing Ethereum wallet functions, calculating and processing payment transactions, and inspecting the transactions using Ganache.

### Step 1: Import Ethereum Transaction Functions

- Import functions from `crypto_wallet.py` into `krypto_jobs.py` to add wallet operations to the KryptoJobs2Go customer interface.
- Add your mnemonic seed phrase to the `.env` file for account authentication.
- In the `krypto_jobs.py` file, import `generate_account`, `get_balance`, and `send_transaction` functions.
- Create a customer account using the `generate_account` function and display the account balance using the `get_balance` function.

### Step 2: Sign and Run a Payment Transaction

- Calculate the wage of a fintech professional based on hourly rate and hours worked.
- Display the calculated wage in the Streamlit sidebar.
- Allow the customer to send an Ethereum transaction to pay the hired candidate using the `send_transaction` function.
- Provide necessary transaction parameters, including the customer's Ethereum account, candidate's address, and the wage value.

### Step 3: Inspect the Transaction in Ganache

- Launch the KryptoJobs2Go application using `streamlit run krypto_jobs.py`.
- Select a candidate and specify the number of hours for hiring.
- Click the "Send Transaction" button to sign and send the Ethereum transaction.
- Use Ganache to inspect the transactions:
  - Capture a screenshot of your address balance and history.
  - Capture a screenshot of the transaction details.
  - Capture a screenshot of the recipient's address balance and history.
