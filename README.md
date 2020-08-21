# `Bcoin`
- A simple implementation of a cryptocurrency in python made on top of blockchain technology.
- It is a simple working blockchain cryptocurrency and to be used as an educational material.

## `Blockchain`
> - A blockchain is a digital record of transactions. The name comes from its structure, in which individual records, called blocks are linked together using cryptographic principles in single list, called a chain.

- The blockchain network has no central authority.
- The information in it is open for everyone to see.

- Main Properties of blockchain for its popularity
    - `Decentralization`
    - `Transperancy`
    - `Immutability`

Find more information in the [original paper](https://bitcoin.org/bitcoin.pdf).

Take a look at the original [bitcoin repository](https://github.com/bitcoin/bitcoin).

## Requirements
- `Python 3.x`
- `Flask`
- `Requests`
- `Postman`
 
## How to run it
Install [Python 3.x](https://www.python.org/) and [Postman](https://www.postman.com/) in your local machine.

Install flask and requests through pip(python package installer) in your command prompt.
- Example

    ```
    pip install flask
    ```

Clone this repository `https://github.com/bharathikannan1311/bcoin.git`

- After cloning just go into the folder and run the bcoin.py file.
    - Example
    ```
    C:\Users\BHARATHI KANNAN.N\Desktop\bcoin>python bcoin.py
    * Serving Flask app "bcoin" (lazy loading)
    * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
    * Debug mode: off
    * Running on http://0.0.0.0:5001/ (Press CTRL+C to quit)
    ```

- Then open your postman desktop app and test your application.
    - Example

    <img src="Images/Apptestinpostman.png" height=300px width=500px>

## How this code works
`bcoin.py`

- Running the file will create a node. It will create a genisis block at first and then you can add transactions and mine the block. As a reward for this you will receive some coins.
    - Consensus Mechanism - `Proof of work`

`bccoin_node_5001.py`<br>
`bccoin_node_5002.py`<br>
`bccoin_node_5003.py`

- Running these files seperately will create three nodes in your local machine.
- Connect these nodes in the post man using the POST request in postman 

    <img src="Images/ConnectingNode1.png" height=200px width=300px>
    <img src="Images/ConnectingNode2.png" height=200px width=300px>
    <img src="Images/ConnectingNode3.png" height=200px width=300px>

`Adding Transactions`
- Transaction can be added as a post method in postman

    <img src="Images/AddingTransaction.png" height=200px width=300px>

`Mining the block`   
- We can then mine the block and we will be rewarded with some bcoin.
    <img src="Images/MiningBlock.png" height=250px width=300px>