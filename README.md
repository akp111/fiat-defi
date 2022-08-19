# Fiat-Defi

A one stop solution for user to interact directly with a Defi protcol through their fiats and take control of their funds.

[Frontend Repo](https://github.com/akp111/fiat-defi-frontend)
Steps to run it:
1. Clone this repo
2. Open a terminal and run `npm install`
3. Once installation is done, run `npm start`

[Backend Repo](https://github.com/akp111/fiat-defi-backend)
1. Clone this repo
2. Open a terminal and run `npm install`
3. Create `.env.`as per `.env.sample` and fill the values.
4. Run `npm start` to start the server

[Contract Repo](https://github.com/akp111/fiat-defi-contract)
1. Fill the `.env`
2. Open a terminal and run `npm install`
3. To deploy, run `npx hardhat run --network mumbai scripts/deploy.js`
4. To test, run   `npx hardhat run --network mumbai scripts/test.js`
