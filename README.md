# BDB2022 Week 3 Exercise

For Week 3, you will be developing smart contracts using REMIX IDE and the Rinkeby Testing network. Week 3 will consist of four projects you can work on. I recommend you complete at least two projects. Or if you are feeling confident you can complete all the projects.

### Setup
1. Clone this repository by running git clone. 
	```
	git clone https://github.com/sparklearnedtech/bdb2022-week3.git
	```
2. Create your own branch using this format (firstname-lastname), checkout, and make sure you are not on the main branch.
	```
	git branch john-doe    // create a branch using the firstname-lastname format
	git checkout john-doe  // checkout on the newly created branch
	git branch             // check and make sure you are currently on your john-doe branch, not the main
	```
3. You are given an initial file that you can initially work on and at the end of the project, you will arrive at a working code. The initial file is located inside the `/contract` folder. Then look for the `/set-1` folder if you are following the Altcoin track, or look for the `/set-2` folder if you are following the NFT track.
4. You can use [REMIXD](https://remix-ide.readthedocs.io/en/latest/remixd.html), a popular extension of the REMIX IDE where in you can connect directly to your local storage and start coding. If you are not confident, you can manually copy-paste the smart contract code to REMIX IDE, then paste it back to your local repository whenever you are done coding. This way you can still commit your changes to GitHub and have them checked by the mentors.
5. Once you're done, just message [@aldrickb](https://github.com/aldrickb) on Slack, and he will check your branch and your deployed contract on Rinkeby.


## Projects

Week 3 has four projects in total.

1. **Altcoin Project** (Set 1)
2. **IDO Project** (Set 1)
3. **NFT Project** (Set 2)
4. **INO Project** (Set 2)

It is recommended to complete 1 set of projects for this week. You can follow the Altcoin track where you will develop your own ERC-20 token and sell it with your IDO contract or you can follow the NFT Project where in you will develop your own ERC-721 token and sell it with your INO contract.

## Altcoin Project
##### /contract/set-1/ERC20.sol

#### Grading Metrics
The following are the Grading Metrics on how well the student was able to complete the project. Each item corresponds to a point/s whose perfect point is 10.

1. Fix total supply of the ERC20 contract (2 points)
2. Deploy the ERC20 contract to Rinkeby with the following:
	a. Your own token name; (2 points)
	b. Your own token symbol, and; (2 points)
	c. Non-zero total supply. (1 point)
3. A published smart contract code in Rinkeby Explorer. (1 point)
4. The student should be able to send at least 100 of their tokens to the mentor. (2 points)

## IDO Project
##### /contract/set-1/IDO.sol

#### Grading Metrics
The following are the Grading Metrics on how well the student was able to complete the project. Each item corresponds to a point/s whose perfect point is 10.

1. Complete the IDO contract from the video; (3 points)
2. Deploy IDO contract to Rinkeby; (2 points)
3. A published smart contract code in Rinkeby Explorer; (1 point)
4. Use your own ERC20 token as a sale token; (1 point)
5. Being able to buy tokens, must be in the contract transaction history, and; (1 point)
6. Be able to withdraw the following:
	a. Collected ETH Balance (1 point)
	b. Remaining sale tokens (1 point)

## NFT Project
##### /contract/set-1/ERC721.sol

#### Grading Metrics
The following are the Grading Metrics on how well the student was able to complete the project. Each item corresponds to a point/s whose perfect point is 10.

1. Complete the MyNFT contract from the video; (3 points)
2. Deploy MyNFT contract to Rinkeby; (2 points)
3. A published smart contract code in Rinkeby Explorer; (1 point)
4. Be able to mint one or many NFTs; (1 point)
5. Minted NFT uses the prescribed URI, or your own working URI, and; (1 point)
6. The student should be able to send at least one of their NFTs to the mentor (2 points)

## INO Project
##### /contract/set-1/INO.sol

#### Grading Metrics
The following are the Grading Metrics on how well the student was able to complete the project. Each item corresponds to a point/s whose perfect point is 10.

1. Complete the INO contract from the video; (3 points)
2. Deploy INO contract to Rinkeby; (2 points)
3. A published smart contract code in Rinkeby Explorer; (1 point)
4. Use your own NFT as a sale token; (1 point)
5. Being able to buy an NFT, must be in the contract transaction history, and; (1 point)
6. Be able to withdraw the following:
	a. Collected ETH Balance (1 point)
	b. Remaining NFT sale tokens (1 point)
