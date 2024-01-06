# Tutorial on Celo Stablecoin:

## Table of Contents:

- [Celo-Stablecoin-tutorial](#Celo-Stablecoin-tutorial)
  - [Abstract](#abstract)
  - [Introduction](#introduction)
  - [Requirements/prerequisites](#requirements)
  - [Understanding the Celo Dollar (cUSD)](<#Understanding-the-Celo-Dollar-(cUSD)>)
  - [How cUSD Works - Exploring the Stability Mechanism of cUSD](#how-cUSD-works-exploring-the-stability-mechanism)
  - [Advantages of cUSD: Enhancing Financial Accessibility](#advantages-of-cUSD-enhancing-financial-accessibility)
  - [Building a Stablecoin on the Celo Blockchain](#building-a-stablecoin-on-the-celo-blockchain)
  - [Writing a Smart Contract with Hardhat and Solidity](#writing-a-smart-contract-with-hardhat-and-solidity)
    - [Setting Up Your Development Environment](#setting-up-your-development-environment)
    - [Defining the Stablecoin Contract](#defining-the-stablecoin-contract)
    - [Implementing the Stability Mechanism](#implementing-the-stability-mechanism)
    - [Testing Your Contract](#testing-your-contract)
    - [Deploying to the Celo Blockchain](#deploying-to-the-celo-blockchain)
    - [Interacting with Your Stablecoin](#interacting-with-your-stablecoin)
  - [Conclusion](#conclusion)

## Abstract:

This tutorial delves into the world of Celo Dollar (cUSD) which is a stablecoin built on the Celo blockchain. By providing a comprehensive overview to equip developers and enthusiasts with a deep understanding of cUSD's functionality, stability mechanism and the advantages it offers in promoting financial accessibility in the world. Additionally, exploring the process of writing a Smart Contract using [Solidity](https://docs.soliditylang.org/en/v0.8.19/) and [Hardhat](https://hardhat.org/) to build a stablecoin and deploy it on the Celo blockchain.
Join me on this journey as I uncover the intricacies of cUSD and its significance in the evolving landscape of digital currencies!!

## Introduction:

The surge in popularity of cryptocurrencies in recent years has revolutionized our perception and utilization of traditional financial institutions. Stablecoins offer a reliable solution to address the volatility commonly associated with various digital currencies. An illustration of this is the Celo Dollar (cUSD), a stablecoin operating on the Celo blockchain.

Upon completing this tutorial, the reader will acquire a comprehensive understanding of the Celo Dollar (cUSD) stablecoin. We will explore its stability mechanism, scrutinize its fundamental principles, and emphasize the advantages it brings to enhancing financial accessibility. Furthermore, I will guide you through the process of crafting a stablecoin and launching it on the Celo blockchain by employing a Smart Contract written using [Hardhat](https://hardhat.org/) and [Solidity](https://docs.soliditylang.org/en/v0.8.19/).

## Requirements:

Install the following in your computer:

1. [Remix IDE](https://remix.ethereum.org/#lang=en&optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.18+commit.87f61d96.js)
2. [Celo Extension wallet](https://chrome.google.com/webstore/detail/celoextensionwallet/kkilomkmpmkbdnfelcpgckmpcaemjcdh?hl=en)
3. [Node.js](https://nodejs.org/en/download)
4. [npm](https://www.npmjs.com/package/download) (Node Package Manager)
5. [Hardhat](https://hardhat.org/)

## Understanding the Celo Dollar (cUSD):

It's crucial to grasp the foundational concept of this stablecoin before delving into its technical intricacies. The Celo Dollar (cUSD) is a digital representation of fiat money, such as the US Dollar, characterized by a stable value. In contrast to volatile cryptocurrencies, cUSD aims to ensure stability by employing various methods that work together to maintain its value relatively constant.

## How cUSD Works: Exploring the Stability Mechanism-

The stability of cUSD is upheld through a mechanism known as the **stability protocol**, which relies on several components, including collateralization, algorithmic adjustments, and governance mechanisms. By delving into the intricacies of these elements, we can gain a deeper understanding of how cUSD preserves its stable value amidst market fluctuations.

A pivotal facet of the stability mechanism is collateralization. In the context of cUSD, collateral is furnished in the form of other digital assets. These assets are held in reserve, acting as a protective barrier against potential fluctuations and ensuring that the value of cUSD remains tied to the designated fiat currency.

Algorithmic adjustments play a crucial role in sustaining cUSD's stability. These adjustments respond to the supply and demand dynamics of the stablecoin. In instances of increased demand for cUSD, the algorithm may implement mechanisms to expand the supply, ensuring ample liquidity in the market. Conversely, in the presence of surplus supply, the algorithm may adjust accordingly to contract the circulating cUSD, thus maintaining stability.

Governance mechanisms are another crucial element in the stability protocol of cUSD. The Celo community actively participates in governing the stablecoin, making decisions related to collateralization ratios, algorithmic adjustments and other factors that impact stability. This decentralized governance model ensures that the stablecoin remains adaptable and responsive to the evolving needs of the community which further enhances its stability.

## Advantages of the Celo Dollar:

1. **Accessibility:**
   Individuals lacking access to banking services or facing economic instability are often excluded from traditional financial institutions. The Celo Dollar (cUSD) addresses this gap by providing a dependable and easily accessible medium of exchange. Its digital nature allows users to conduct seamless and secure transactions, irrespective of their location or financial circumstances. Leveraging the infrastructure of the Celo blockchain, cUSD facilitates global economic participation, fostering financial inclusivity and empowerment. Furthermore, cUSD extends opportunities to individuals in regions with volatile or underperforming national currencies. By using cUSD, they can mitigate the risks associated with currency fluctuations and maintain a stable store of value. This stability creates a favorable environment for commerce, savings, and investments, promoting economic growth and prosperity for those facing vulnerabilities.

2. **Security & transparency:** come standard with distributed ledger technology. Users benefit from the ease of a reliable medium of exchange while maintaining confidence in the integrity of their transactions.

3. **Low Transaction Fees:** makes cUSD an attractive option for microtransactions and everyday purchases. Whether you're sending money to a friend or making a purchase, the cost-efficiency of cUSD makes it a practical choice.

## Building a Stablecoin on the Celo Blockchain:

For individuals eager to establish their own stablecoin on the Celo blockchain, a key understanding of the Smart Contract creation process is essential. Robust tools such as Hardhat and Solidity play a pivotal role in simplifying the development of Smart Contracts and their subsequent deployment on the Celo blockchain.
<br/>

To begin, you will need to set up your development environment using Hardhat. **Hardhat** is a popular development framework that simplifies the process of writing, testing and deploying Smart Contracts. It provides a comprehensive suite of tools and utilities that aid in the smooth development process.
<br/>

Next, you will write your Smart Contract using Solidity which is a high-level programming language specifically designed for creating Smart Contracts. Solidity enables you to define the rules & functionalities of your stablecoin like its stability mechanisms, token supply and governance structure. By leveraging Solidity's capabilities, you can customize your stablecoin to meet your favored requirements.
<br/>

Once your Smart Contract is written, you can use Hardhat to compile and deploy it onto the Celo blockchain. Hardhat streamlines the deployment process by providing easy-to-use commands and integration with Celo's infrastructure. Through this process, your stablecoin will become a part of the Celo ecosystem, ready to empower users with stability and financial accessibility.
<br/>

By following these steps and leveraging the capabilities of Hardhat and Solidity, you can build a powerful and reliable stablecoin on the Celo blockchain. Remember to conduct thorough testing, ensure proper security measures and seek external audits (if necessary) in order to provide confidence in your stablecoin's integrity.

## Writing a Smart Contract using Hardhat and Solidity:

You will need to build a Smart Contract utilizing the well-known development framework "Hardhat" and the programming language "Solidity" to start creating your stablecoin on the Celo network. The essential steps are as follows:

### Setting Up Your Development Environment:

Start by installing Hardhat, a powerful tool for Ethereum and Celo development. Once installed, create a new directory for your project and initialize it with Hardhat.

1. Install Hardhat globally:

`npm install -g hardhat`

2. Create a new directory for your project:

`mkdir my-stablecoin-project`

`cd my-stablecoin-project`

3. Initialize the project with Hardhat:

`npx hardhat init`

The above code snippet assumes you have [Node.js](https://nodejs.org/en/download) and [npm](https://www.npmjs.com/package/download) (Node Package Manager) installed on your machine. By following these steps, you will have Hardhat installed globally and a new directory created for your stablecoin project. The **`npx hardhat init`** command initializes the project with the necessary configuration files and folder structure provided by Hardhat, allowing you to start developing and deploying your Smart Contracts on the Celo blockchain.
<br/>

Note: You may need to customize the project configuration and install additional dependencies based on your specific requirements. Make sure to refer to the [Hardhat documentation](https://hardhat.org/docs) for further guidance on configuring and extending your project.

### Defining the Stablecoin Contract:

Within your project directory, create a new Solidity file for your stablecoin contract. Define the necessary variables and functions to handle the token's supply, transfers and stability mechanisms. Consider incorporating the Celo Stability Protocol into your contract design.

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";
import "@openzeppelin/contracts/utils/math/SafeMath.sol";

contract MyStablecoin is ERC20 {
    using SafeMath for uint256;

    address private governance;
    uint256 private reserveRatio;
    mapping(address => uint256) private reserveFunds;

    // The construtor function is the first function to be ran once a user interacts with the contract.
    constructor() ERC20("My Stablecoin", "MYS") {
        governance = msg.sender;
        reserveRatio = 5000; // Example reserve ratio, adjust as needed
    }

    // A modifier that we can assign to certain functions to make sure that they can only be called by governance.
    modifier onlyGovernance() {
        require(msg.sender == governance, "Only governance can call this function");
        _;
    }

    // Setter function for reserveRatio variable
    function setReserveRatio(uint256 ratio) external onlyGovernance {
        reserveRatio = ratio;
    }

    function mint(address recipient, uint256 amount) external onlyGovernance {
        _mint(recipient, amount);
    }

    function burn(uint256 amount) external {
        _burn(msg.sender, amount);
    }

    function transfer(address recipient, uint256 amount) public override returns (bool) {
        require(amount <= _calculateStability(amount), "Transfer amount exceeds stability limit");
        return super.transfer(recipient, amount);
    }

    function transferFrom(
        address sender,
        address recipient,
        uint256 amount
    ) public override returns (bool) {
        require(amount <= _calculateStability(amount), "Transfer amount exceeds stability limit");
        return super.transferFrom(sender, recipient, amount);
    }

    function withdrawReserve(uint256 amount) external onlyGovernance {
        require(amount <= reserveFunds[msg.sender], "Insufficient reserve funds");
        reserveFunds[msg.sender] = reserveFunds[msg.sender].sub(amount);
        _burn(address(this), amount);
        payable(msg.sender).transfer(amount);
    }

    function _calculateStability(uint256 amount) private view returns (uint256) {
        uint256 totalSupply = totalSupply();
        uint256 reserve = totalSupply.mul(reserveRatio).div(10000); // adjust to decimal percentage
        uint256 totalReserve = balanceOf(address(this));
        uint256 stabilityAmount = totalSupply.sub(reserve).sub(totalReserve).sub(amount);
        return stabilityAmount;
    }

    receive() external payable {
        reserveFunds[msg.sender] = reserveFunds[msg.sender].add(msg.value);
    }
}

```

In the above code snippet:

1. Define a **`MyStablecoin`** contract that extends the **`ERC20`** contract from the OpenZeppelin library. The contract initializes with a governance address and a reserve ratio, which represents the portion of the total supply reserved to maintain stability.

2. **`mint`** function: allows the governance address to `mint` new stablecoins and allocate them to a recipient.

3. **`burn`** function: enables users to burn their stablecoins and reduce the token supply.

4. **`transfer`** and **`transferFrom`** functions: override the corresponding functions in the ERC20 contract. Before executing the transfer, these functions verify that the transfer amount does not exceed the stability limit, calculated based on the reserve ratio.

5. **`_calculateStability`** internal function: calculates the maximum transferable amount by subtracting the reserve and the desired transfer amount from the total supply.

Make sure to customize the contract name, token symbol, reserve ratio and other aspects based on your specific requirements.

### Implementing the Stability Mechanism:

Utilize the functionality provided by the Celo blockchain to implement the stability mechanism of your stablecoin. This may involve interacting with Celo's Oracle system to fetch real-time price information and adjusting the supply of your stablecoin accordingly.
<br/>

Here are some code samples that show how you can use the capabilities of the Celo blockchain to implement the stability mechanism in your stablecoin contract. These examples include connecting with Celo's Oracle system and modifying the token supply based on current pricing information.

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";
import { AggregatorV3Interface } from "./AggregatorV3Interface.sol";

contract MyStablecoin is ERC20 {
address public governance;
uint256 public reserveRatio;
AggregatorV3Interface public priceFeed;

   constructor(address _priceFeedAddress) ERC20("My Stablecoin", "MYS") {
    governance = msg.sender;
    reserveRatio = 200000000000000000; // 20% represented in wei
    priceFeed = AggregatorV3Interface(_priceFeedAddress);
}

modifier onlyGovernance() {
    require(msg.sender == governance, "Only governance can call this function");
    _;
}

function mint(address recipient, uint256 amount) external onlyGovernance {
    _mint(recipient, amount);
}

function burn(uint256 amount) external {
    _burn(msg.sender, amount);
}

function transfer(address recipient, uint256 amount) public override returns (bool) {
    require(amount <= calculateStability(amount), "Transfer amount exceeds stability limit");
    return super.transfer(recipient, amount);
}

function transferFrom(
    address sender,
    address recipient,
    uint256 amount
) public override returns (bool) {
    require(amount <= calculateStability(amount), "Transfer amount exceeds stability limit");
    return super.transferFrom(sender, recipient, amount);
}

function calculateStability(uint256 amount) public view returns (uint256) {
    uint256 totalSupply = totalSupply();
    uint256 reserve = totalSupply * reserveRatio / 1000000000000000000; // convert back to ether
    return totalSupply - reserve - amount;
}

function updatePriceFeedAddress(address _priceFeedAddress) external onlyGovernance {
    priceFeed = AggregatorV3Interface(_priceFeedAddress);
}

function getLatestPrice() public view returns (uint256) {
    (, int256 price, , , ) = priceFeed.latestRoundData();
    require(price > 0, "Invalid price"); // Ensure the price is positive
    return uint256(price);
}

function adjustSupply() external onlyGovernance {
    uint256 currentPrice = getLatestPrice();
    uint256 totalSupply = totalSupply();
    uint256 reserve = totalSupply * reserveRatio / 1000000000000000000; // convert back to ether
    uint256 targetSupply = reserve * 1000000000000000000 / currentPrice; // convert to wei
    if (totalSupply > targetSupply) {
        uint256 amountToBurn = totalSupply - targetSupply;
        _burn(governance, amountToBurn);
    } else if (totalSupply < targetSupply) {
        uint256 amountToMint = targetSupply - totalSupply;
        _mint(governance, amountToMint);
    }
}
}

```

In the above code snippet, we have made several updates to the previous stablecoin contract:

1. Imported the **`AggregatorV3Interface`** from the **`AggregatorV3Interface.sol`** file, which provides an interface for interacting with Celo's Oracle system.

2, The constructor now takes an address parameter **`_priceFeedAddress`**, which represents the address of the Celo Oracle price feed.

3. The **`updatePriceFeedAddress`** function allows the governance address to update the price feed address if needed.

4. The **`getLatestPrice`** function retrieves the latest price from the Oracle system using the **`latestRoundData`** function provided by the **`AggregatorV3Interface`**. It ensures that the price is positive before returning it.

5. The **`adjustSupply`\*** function is called by the governance address to adjust the stablecoin's supply based on the target reserve ratio. It fetches the current price from the Oracle system, calculates the target supply based on the reserve and the current price and adjusts the supply accordingly. If the total supply is greater than the target supply, it burns the excess tokens. If the total supply is less than the target supply, it mints additional tokens.

Note: The code assumes the availability of the AggregatorV3.

### Testing Your Contract:

Ensuring the security and functionality of your Smart Contract is paramount, and conducting a comprehensive test is a crucial step in this process. By leveraging the robust testing framework provided by Hardhat, you can create thorough test cases to verify the functionality of your stablecoin in diverse scenarios.

### Deploying to the Celo Blockchain:

After successfully passing all tests, the next step is to deploy your contract to the Celo blockchain. Hardhat streamlines this process by offering deployment scripts that simplify the deployment of your contract to the Celo network. Make sure you have the requisite Celo account and network configurations configured.

Below is an illustrative code snippet demonstrating how to utilize Hardhat's deployment tools to publish your stablecoin contract on the Celo blockchain:

```javascript
/ deploy.js
// This script deploys a stablecoin contract on the Celo network using an Oracle price feed address

async function main() {
// Set up your Celo account and network configurations
const [deployer] = await ethers.getSigners();

console.log("Deploying contracts with the account:", deployer.address);

// Set up your contract deployment parameters
const stablecoinName = "My Stablecoin"; // The name of the stablecoin
const stablecoinSymbol = "MYS"; // The symbol of the stablecoin
const priceFeedAddress = "0x1234567890123456789012345678901234567890"; // Replace with actual Oracle price feed address

// Deploy your stablecoin contract
const Stablecoin = await ethers.getContractFactory("MyStablecoin");
const stablecoin = await Stablecoin.deploy(priceFeedAddress);

await stablecoin.deployed();

console.log("Stablecoin deployed to:", stablecoin.address);
}

main()
.then(() => process.exit(0))
.catch((error) => {
console.error(error);
process.exit(1);
});
```

The JavaScript deployment script in the code snippet above makes use of Hardhat to upload the stablecoin contract to the Celo network. The script is broken down as follows:

1. Set up the necessary configurations and obtain the deployer's Celo account using **`ethers.getSigners()`**.

2. Define the parameters for the stablecoin contract deployment, including the name, symbol and the address of the Oracle price feed.

3. Use **`ethers.getContractFactory()`** to obtain the contract factory for the stablecoin contract.

4. Deploy the stablecoin contract using **`stablecoin.deploy(priceFeedAddress)`**. This deploys the contract with the provided price feed address as a constructor parameter.

5. Log the deployed contract's address to the console.

To deploy the contract, you can run this script using Hardhat's deployment command, such as **`npx hardhat run deploy.js --network celo`**. Ensure that you have the necessary network configurations in the Hardhat configuration file like the RPC URL and the private key of the deployer account.

Note: The code snippet assumes you have a valid Oracle price feed address and that you've replaced the placeholder address **(`0x1234567890123456789012345678901234567890`)** with the actual address of the Oracle price feed.

### Interacting with Your Stablecoin:

Upon deployment, you can engage with your stablecoin using a range of wallets and programs compatible with Celo. To ensure smooth functionality, conduct testing of transactions, transfers, and other features to guarantee a seamless user experience.

By adhering to these guidelines and harnessing the capabilities of Hardhat and Solidity, you can craft a robust and reliable stablecoin on the Celo blockchain. Instill confidence in the integrity of your stablecoin by conducting thorough testing, implementing suitable security measures, and, if needed, seeking external audits.

## Conclusion:

Hence, the Celo Dollar (cUSD) emerges as an impressive stablecoin established on the Celo blockchain, championing financial accessibility and stability. Delving into its stability mechanism and advantages illuminates its potential impact on the decentralized finance (De-Fi) landscape. Additionally, armed with the guidance on Smart Contract creation using Hardhat and Solidity, you possess the tools to embark on your journey of crafting your stablecoin on the Celo blockchain.

Seize the potential of cUSD and explore the avenues of stablecoin innovation within the Celo network. By adhering to best practices, conducting thorough testing, and building upon the robust infrastructure offered by Celo and Hardhat, you are now poised to contribute to the dynamic and swiftly evolving realm of decentralized finance.
