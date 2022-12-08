# fintech_finder
intech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them.

---

## Technologies

**Python 3.7** was used to code this app.  
Libraries used are **streamlit, dataclasses, typing, web3, os, dotenv, bip44**.  This app leverages functions in the crypto_wallet.py file and calls them in the fintech_finder.py file.

---

## Installation Guide

Open terminal/git bash and run "streamlit run fintech_finder.py" to open an the app in a streamlit window.

---

## Usage

After running the app, you can use the drop down menus on the sidebar to select the professional you'd like to hire, and input the number of hours you'd like to hire them for.  click the "Send Transaction" button in the side bar to hire them and pay them in eth, based on the hours you'd like multiplied by their Hourly Rate per Ether.

## Example
![example of streamlit app running](./images/streamlit transaction.png)
The above image shows an example of what it looks like when deployed to the local computer.

Using ganache to simulate an ethereum blockchain instance, you can see I was able to transfer 3.3 ETH from wallet 0x13812a3AF44520Bae7b0C7718dD5ABB7e834C67B to wallet 0x2422858F9C4480c2724A309D58Ffd7Ac8bF65396
![transaction screenshot](./images/ganache_screenshot.png)
![transaction screenshot](./images/recipient.png)
![transaction screenshot](./images/Account_balances.png)


---

## Contributors

This was created by Cuong Ha

---

## License

public