Setup

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

Links:

Remix IDE : https://remix.ethereum.org/

Ganache: https://archive.trufflesuite.com/ganache/

NOTE: Although not recommended, link to env folder: https://drive.google.com/file/d/1nlWPcH3XoAFEy4-8SFGKxOKjggk_TICL/view?usp=drive_link

You might face errors and warnings while installing and/or starting npm as many dependencies are depricated. If the issue persists, use this link to download the env folder. Copy the folder and all its elements in the root directory.
