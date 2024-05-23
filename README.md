# PharmaGuard
PharmaGuard is a web application based on Blockchain(web3) which is used to make a transparent environment for all the customers regarding the medicines that they have bought from a retailer, manufactured by its manufacturer.

PharmaGuard caters to three types of users: customers, retailers and manufacturers.

Retailers and manufacturers have the sign up/login options whereas customers can use the application without logging in or signing up.

**Functionalities:**

Manufacturers: The manufacturer can add new product shipments to the blockchain and generate a QR code for each medicine ID, which is then affixed to the batch of medicines being shipped. Retailers and consumers can scan this QR code to verify the medicine's authenticity.

Retailers: The retailer or hospital will scan the medicine using the QR code scanner on our web or mobile application, and their details such as name, date, and location will automatically be updated on the blockchain.

Customers: The consumer will scan the QR code to obtain information about the medicine, including its name, MRP, manufacturing date, and expiry date. They will also be able to see the record of all the retailer locations the medicine has passed through. This same interface can be used to identify where the supply chain has been compromised in cases of issues like theft or drug counterfeiting, allowing for the responsible party to be easily identified and apprehended.

# Setup

Frontend:

To install all the dependencies, use the command "npm install" in the terminal of the root folder. To start a localhost, use "npm start" in the root folder's terminal. This will host the application on your web browser.

Backend:

Set up a virtual environment on your system using "py -m venv env" command in the terminal or command prompt on Windows or "python3 -m venv env" on Linux/MacOS.

Activate the virtual environment using ".\env\Scripts\activate" on Windows or "source env/bin/activate" on Linux/MacOS.

Install Flask and Flask-SQLAlchemy by running "pip install flask flask-sqlalchemy" command in terminal or command prompt.

Blockchain:

Begin by downloading Ganache. It will serve as a local blockchain node, providing trial accounts pre-funded with ether. It's important to note that actual transactions on a blockchain incur gas fees, paid in ether, which translates to real money.

To develop smart contracts, utilize Remix IDE, which supports Solidity programming language.

Install the Web3 Python library using the command "pip install web3" in your terminal or command line. This library facilitates communication between our smart contracts and Flask backend.

Finally, start the backend server by running "python app.py" in your terminal from the root directory. Ensure that the frontend server is also running simultaneously by executing "npm start" in another terminal.

# Links:

Remix IDE : https://remix.ethereum.org/

Ganache: https://archive.trufflesuite.com/ganache/

# Scope of Improvement
Port the web application to android and/or iOS to make authentication more accessible and easier for the user as scanning QR codes can be easier on mobile devices.
