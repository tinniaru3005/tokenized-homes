# Tokenized Homes
Real Estate NFT DApp

![millow](https://github.com/tinniaru3005/tokenized-homes/assets/62856848/615687a7-99be-445d-afc8-536fd013243e)

## Technology Stack & Tools

- Solidity (Smart Contracts & Tests)
- Javascript (React & Testing)
- [Hardhat](https://hardhat.org/) (Development Framework)
- [Ethers.js](https://docs.ethers.io/v5/) (Blockchain Interaction)
- [React.js](https://reactjs.org/) (Frontend Framework)

## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/)

## Setting Up
### 1. Clone/Download the Repository

### 2. Install Dependencies:
`$ npm install`

### 3. Run tests
`$ npx hardhat test`

### 4. Start Hardhat node
`$ npx hardhat node`

### 5. Run deployment script
In a separate terminal execute:
`$ npx hardhat run ./scripts/deploy.js --network localhost`

### 7. Start frontend
`$ npm run start`

## Setting Up Using Docker

### 1. Build the Docker image:

`$ docker build -t tokenized-homes .`

### 2. Run the Docker container:
 `$ docker run -p 3000:3000 tokenized-homes`

 This will start your application inside a Docker container and expose it on port 3000 of your host machine. You can access your application by navigating to `http://localhost:3000` in your web browser.