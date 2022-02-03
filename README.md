# blockchain-ledger

The purpose of this project is to create a blockchain-based ledger system that can be accessed via a user-friendly web interface (Streamlit). This ledger allows users to conduct transactions between a sender and receiver while verifying the integrity of the data in the ledger. This project explores the foundational principles of blockchain technology which will be further built upon in later projects.

The Streamlit interface appears as follows:
![image](https://user-images.githubusercontent.com/89161654/152415364-51acd55a-4c91-41c7-8f7f-9b95315d34ec.png)

When sample transactions are added, the ledger is updated as such:
![image](https://user-images.githubusercontent.com/89161654/152415478-d376b2db-791f-48c0-bb45-5c754c0b89b8.png)

The chain may also be validated using the Validate Chain button. The return is True which means the chain has been validated:
![image](https://user-images.githubusercontent.com/89161654/152415811-6e72d057-d581-48ef-aa66-268977aad980.png)



## Technologies

This project leverages Python 3.7 and Streamlit. The required libraries include: streamlit, dataclasses, typing, datetime, pandas, and hashlib.

## Installation

Streamlit must be installed prior to using this file. To install Streamlit, simply run the following command in your desired environment:

```
pip install streamlit
```


## Usage

In order to use this project, clone the repo. Go to your terminal, navigate to the repo folder, and run the following command:
```
streamlit run pychain.py
```
You may enter values for the sender, receiver, and amount in order to test the recording of transactions into the blockchain ledger.

## Contributors

Brought to you by Austin Do (austindotech@gmail.com)

## License

MIT
