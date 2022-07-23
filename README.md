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
<img width="533" alt="Screen Shot 2022-07-17 at 1 10 56 PM" src="https://user-images.githubusercontent.com/98444459/179416949-cd4e4bda-f532-4195-b2ce-77f930e0b0cb.png">

3. The Streamlit application will run locally in your browser and should launch automatically.
<img width="988" alt="Screen Shot 2022-07-17 at 1 16 15 PM" src="https://user-images.githubusercontent.com/98444459/179417175-fb0f32f0-19cc-4cf2-bdc0-9bdaeb32509f.png">

4. Enter details into the Sender ID, Receiver ID, Amount and click the 'Add Block' button. This will add a block to the ledger. This can be validated in two ways: the new block will appear as a new row in the PyChain ledger dataframe and secondly, will appear under the Block Inspector dropdown. 

---

## Validation
As per the screenshot below, four additional blocks have been addeed to the chain, and upon clicking the 'Validate Chain' button, we receive a True statement indicating the validity of the entire ledger.


As per this screenshot below we can see the details of one of the blocks entered in the blockchain that has been selected using the dropdown. 
![Screen Shot 2022-07-14 at 8 30 02 PM](https://user-images.githubusercontent.com/98444459/179123130-a02fc238-698e-4ec9-982e-5a8cec2af8df.png)

--- 

## Contributors

Made by:
Ryan Anderson
  Email: m.anderson.ryan@gmail.com
  LinkedIn: https://www.linkedin.com/in/ryan-anderson-57b2b173

---

## License

No licenses are required to run this application