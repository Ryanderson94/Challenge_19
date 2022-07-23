# PyChain Ledger

In this Challenge, we developed code that enables customers to send cryptocurrency payments to fintech professionals. We assume the perspective of a Fintech Finder customer using the application to find a fintech professional and pay them for their work.

This application allows users to review a list of candidates, select from said list, 'hire them' and effectively pay them. This is facilitated by integrating directly with with Ethereum Blockchain. 

# Technologies

This program leverages python 3.7+, Streamlit for the front-end development and Ganache as a test wallet.

To ensure all dependencies are installed and up-to-date, please run the following commands in your terminal once you have cloned the repository to your local machine.
run pip install -r requirements.txt

---

## Installation Guide

1. Copy this repository via the URL (SSH or HTTP)
<img width="907" alt="Screen Shot 2022-04-03 at 3 35 27 PM" src="https://user-images.githubusercontent.com/98444459/161445246-d4eecac4-44ae-452f-8e0c-ebaa9e523908.png">

2. Run a git clone command in your terminal or git bash under the desired local directory
<img width="715" alt="Screen Shot 2022-07-17 at 1 07 58 PM" src="https://user-images.githubusercontent.com/98444459/179416878-c43af521-a43f-477c-bd45-e16e147cc179.png">

3. If you receive errors, please review the dependencies above, install them and try again. 

---

## Usage

1. Navigate to the directory in either the Terminal or GitBash. 

2. Run the following command: streamlit run pychain.py
<img width="574" alt="Screen Shot 2022-07-23 at 10 19 11 AM" src="https://user-images.githubusercontent.com/98444459/180609053-b5c9877b-cd1b-4df8-8ed8-cd1ea4666e97.png">

3. The Streamlit application will run locally in your browser and should launch automatically.
4. <img width="1442" alt="Screen Shot 2022-07-23 at 10 20 53 AM" src="https://user-images.githubusercontent.com/98444459/180609108-0c93e7e5-7255-4a2e-aa7f-75c1080b4fca.png">

The application will pull in your crypto wallet and provide you with the public address and the account balance. Review the individuals from the list provided, then use the 'Select a Person' dropdown to indicate the individual you would like to hire. Indicate the number of hours for which you would like to hire them, and click 'Send Transaction' to deliver the ETH.
![FintechFinder](https://user-images.githubusercontent.com/98444459/180609199-1814b225-285e-417f-9738-078ac48fa7e6.gif)

5. If you have insufficient funds, you will receive an error. Otherwise, balloons will appear and your transaction hash will appear under the button. 

---

## Transaction Validation
Below is the iniital balance of the wallet from which we will be withdrawing ETH. As we can see, it contains 100 ETH.
<img width="1194" alt="Screen Shot 2022-07-23 at 9 52 02 AM" src="https://user-images.githubusercontent.com/98444459/180608689-30fb053a-f1fe-424a-a16e-21f4c486039c.png">

This screenshot contains the details of the transaction that will be sent to the selected individual.
<img width="333" alt="Screen Shot 2022-07-23 at 9 52 18 AM" src="https://user-images.githubusercontent.com/98444459/180608706-ef5a3b9e-1a9e-49be-9c43-ce6fa5682c69.png">

This is the resulting impact on the originating wallet.
<img width="1194" alt="Screen Shot 2022-07-23 at 9 52 02 AM" src="https://user-images.githubusercontent.com/98444459/180608702-cf7c4cc2-128b-4d3d-baa3-7e2f905375ed.png">


This is the details of the transactions as seen in Ganache. 
<img width="1194" alt="Screen Shot 2022-07-23 at 9 54 00 AM" src="https://user-images.githubusercontent.com/98444459/180608716-e3d346a9-467b-4780-b776-05e80bd9c18d.png">

--- 

## Contributors

Made by:
Ryan Anderson
  Email: m.anderson.ryan@gmail.com
  LinkedIn: https://www.linkedin.com/in/ryan-anderson-57b2b173

---

## License

No licenses are required to run this application
