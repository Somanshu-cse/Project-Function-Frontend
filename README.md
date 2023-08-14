# Project with Hardhat Framework
Basic Ethereum Contract Application

## Overview

This undertaking constitutes a straightforward Ethereum contract application, enabling individuals to engage with a contract deployed on the nearby Hardhat network. Within the contract, functions for both depositing and withdrawing funds are embedded. The outputs of these functions are visible on the application's frontend, which has been constructed using Next.js.

## Initial Steps

### Installation

1. Duplicate the repository on your personal computer.

Command Line
Copy repository URL and execute: git clone <repository_url>


2. Access the designated project folder.

Command Line
Navigate to: cd <project_directory>


3. Fulfill the project's prerequisites by installing its dependencies.

Command Line
Employ: npm install


### Execution Guidelines

1. Launch two supplementary terminals within your preferred code editor, such as Visual Studio Code.

2. On the second terminal, initiate the local Hardhat network.

Command Line
Activate: npx hardhat node


3. On the third terminal, implement contract deployment on the local network.

Command Line
Execute: npx hardhat run --network localhost scripts/deploy.js


4. Return to the first terminal and commence the operation of the front-end application.

Command Line
Start with: npm run dev


5. Commence your web browser, then navigate to `http://localhost:3000` in order to access the application.

## Support

Should any complications arise or inquiries materialize, do not hesitate to communicate with the creators.

## Authors
- Creator 1: MetacrafterChris (Utilized their starter template)
- Creator 2: [Somanshu](mailto:somanshusharma888@gmail.com)

## Licensing

This endeavor is governed by the [MIT License](https://license.md/).
