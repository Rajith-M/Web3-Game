# Memory Tokens DApp

This project is a decentralized application (DApp) for managing memory tokens using the Ethereum blockchain. It leverages various technologies including Truffle, Solidity, React, and Web3.

## Tech Stack

- **Solidity**: A statically-typed programming language designed for developing smart contracts that run on the Ethereum Virtual Machine (EVM).
- **Truffle**: A development environment, testing framework, and asset pipeline for Ethereum, aiming to make life as an Ethereum developer easier.
- **React**: A JavaScript library for building user interfaces, particularly single-page applications where you need a fast, interactive user experience.
- **Web3.js**: A collection of libraries that allow you to interact with a local or remote Ethereum node using HTTP, IPC, or WebSocket.
- **Babel**: A JavaScript compiler that allows you to use next-generation JavaScript, today.
- **ESLint**: A tool for identifying and reporting on patterns found in ECMAScript/JavaScript code, with the goal of making code more consistent and avoiding bugs.

## Project Structure

- **migrations/**: Contains migration scripts for deploying smart contracts.
- **public/**: Contains static assets like images and the main HTML file.
- **src/**: Contains the main source code for the DApp.
  - **abis/**: Contains the ABI (Application Binary Interface) files for the smart contracts.
  - **components/**: Contains React components.
  - **contracts/**: Contains Solidity smart contracts.
  - **index.js**: The entry point for the React application.
  - **serviceWorker.js**: Service worker for offline capabilities.
- **test/**: Contains test scripts for the smart contracts.
- **truffle-config.js**: Configuration file for Truffle.
- **package.json**: Contains project metadata and dependencies.

## Getting Started

### Prerequisites

- Node.js
- npm (Node Package Manager)
- Truffle
- Ganache (for local blockchain development)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/memory-tokens-dapp.git
    cd memory-ttokens-dapp
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Compile the smart contracts:
    ```sh
    truffle compile
    ```

4. Migrate the smart contracts to the blockchain:
    ```sh
    truffle migrate
    ```

5. Start the React application:
    ```sh
    npm start
    ```

## Running Tests

To run the tests for the smart contracts, use:
```sh
truffle test
