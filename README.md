This is a project by team O.N.C.E. (Operation Nifty Carbon Emissions)! Brought to you by members from the RSK and Indorse teams! 

## Project Scope

In every serious conversation about blockchains, in particular NFTs, there are always detractors who talk about how harmful the NFTs are for the environment. One of the rebuttals to this argument is the renewable energy sources used by miners across the world. Still, we do not have the actual numbers to prove our point and show how “green” the NFTs are. In this project, we assess the actual environmental impact of the NFTs by going drilled down all the way to the transaction level. Several projects showcase the environmental impact of a blockchain network as a whole. This project attempts to go further, by segregating the NFT transactions independently. 

We have used a sample Smart Contract for an NFT on the Ethereum blockchain and look at various types of transactions such as “deploy”, “mint”, and “transfer”. Each transaction will have a different gas cost associated with that, hence varying carbon emission impact. We also consider other factors like the energy mix used for mining these transactions and try to make it palatable and easy to understand by comparing these values against trees felled or miles travelled in a typical car. 

### Visualisation

https://blockchain-carbon-cost-visualizer.vercel.app/

### Light Paper

[Operation Nifty Carbon Emissions](operation-nifty-carbon-emissions.pdf)

### Technology used

- Frontend - ReactJS
- Backend - NodeJS + web3.js
- Smart Contract - Solidity

### Project Structure

We have created two new works, plus leveraged one existing work, in this project.

- The frontend can be found in [this repo](https://github.com/utkarshg6/blockchain-carbon-cost-visualizer)
    - This repo is the main visualization of the project where we compare the different NFT transactions and showcase how much energy they consume as compared to cutting down trees or driving around in a car!
- The backend can be found in [this repo](https://github.com/vijaykrishnavanshi/once-hackathon-api)
    - This is the repo where we have APIs that feed data to the React visualization
    - This repo also connects to a script that calculates the estimated energy consumption and the carbon costs associated with the various transactions
- This project is based on prior work found at [this repo](https://github.com/bguiz/gas-fee-comparison)
    - This was originally created to compare dollar costs of transactions in different compatible blockchains, and has been extended to also compute carbon costs

### Team

1. Brendan Graetz, RSK
2. Gaurang Torvekar, Indorse
3. Vijay Krishnavanshi, Indorse
4. Utkarsh Gupta, Indorse

### License

This project is released under the [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.txt)
