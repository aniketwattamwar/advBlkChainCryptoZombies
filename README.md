# Midterm project: CryptoZombies DApp

# Project Repository

[Repository Link](https://github.com/aniketwattamwar/advBlkChainCryptoZombies)

## Group Members:

* Aniket Wattamar (885680645)   ( aniket.wattamar@csu.fullerton.edu )
* Mrunal Anant Kakirwar (884428111)  ( mrunal@csu.fullerton.edu )
* Mikaella Sharma (885175406)    ( mikaella.sharma001@csu.fullerton.edu )
* Akshay Sadawarte (885175422) ( AkshaySD@csu.fullerton.edu )

## Project Setup 

1. Clone the repository
2. Install the dependencies using `npm install`
3. Install [ganache](https://trufflesuite.com/ganache/) and add this project to workspace using `truffle-config.js` file
   in the root directory
4. Compile the contracts using `truffle compile`
5. Migrate the contracts using `truffle migrate`
6. Copy ZombieOwnership Deployed contract address and paste it in at src/constants.js
7. Set up Metamask and link it to the Ganache network using the following details:

        Network Name: Ganache
        New RPC URL: http://localhost:7545 
        Chain ID: 1337 
        Symbol: ETH

8. Copy the private key of any Ganache account excluding the first one, then add the new account to Metamask using the private key
9. Run `npm run start` to start the front-end server (this will start the front-end server on port 3000 by default and
   opens the browser)
10. Establish a connection between Metamask and the front-end server by clicking the Metamask icon within the browser
11. You can now create your zombies and level them up
12. Modify the names and DNA of your zombies as desired


## Improvements to the CryptoZombies DApp

