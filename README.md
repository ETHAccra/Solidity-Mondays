# <div align="center"><p style="text-align: center;"><strong>ETHAccra Solidity Mondays: Weekly Solidity Tutorial</strong></p></div>

<div align="center" ><img width="350px" src="https://github.com/eben619/Zero-To-Dapp-Workshop/blob/main/ethAccraHero.png"></div>

Welcome to **Solidity Mondays**! This is a structured weekly plan to help you learn Solidity, the programming language used to write smart contracts on Ethereum and EVM compatible chains. Each week, we’ll cover a new topic, gradually building your skills from beginner to advanced.

---

## <div align="center"><p style="text-align: center;"><strong>Weekly Schedule</strong></p></div>

<details>
<summary><strong>Week 1: Introduction to Solidity and Blockchain Basics</strong></summary>

### Topics Covered:
- Evolution of the Web: Web1, Web2, and Web3
- Overview of blockchain and Ethereum.
- Smart contracts: What they are and why they matter.
- Setting up your development environment (Remix IDE, MetaMask, and Node.js).


<h1>📌 Introduction to Blockchain: From Web1 to Solidity on Ethereum</h1>

<h2>🚀 Lesson Overview</h2>
<p>This lesson covers the evolution of the web (Web1, Web2, Web3), blockchain fundamentals, wallets, Ethereum smart contracts, and Solidity programming.</p>

<hr>

<h2>1️⃣ Evolution of the Web: Web1, Web2, and Web3</h2>

<h3>🌐 Web1: The Static Web (1990s - early 2000s)</h3>
<ul>
    <li>Read-only web where users could only consume content.</li>
    <li>Static websites with minimal interaction.</li>
    <li><strong>Examples:</strong> Yahoo, early blogs, and company websites.</li>
</ul>

<h3>🌍 Web2: The Interactive Web (Mid-2000s - Present)</h3>
<ul>
    <li>Read and write capabilities, allowing user-generated content.</li>
    <li>Centralized platforms control data (Facebook, Google, Twitter).</li>
    <li>Monetization through ads and data collection.</li>
    <li><strong>Problems:</strong> Privacy issues, censorship, platform dependence.</li>
</ul>

<h3>🌎 Web3: The Decentralized Web (Emerging Future)</h3>
<ul>
    <li>Built on blockchain and smart contracts.</li>
    <li>Users own their data, assets, and identities.</li>
    <li>Peer-to-peer interactions without intermediaries.</li>
    <li><strong>Examples:</strong> Ethereum-based DApps, DAOs, DeFi, NFTs.</li>
</ul>

<hr>

<h2>2️⃣ What is Blockchain?</h2>

<h3>🔗 Definition</h3>
<p>Blockchain is a decentralized, distributed ledger that records transactions securely and transparently.</p>

<h3>🔑 Key Features</h3>
<ul>
    <li><strong>Decentralization</strong> – No central authority.</li>
    <li><strong>Transparency</strong> – Publicly accessible transactions.</li>
    <li><strong>Security</strong> – Cryptographic encryption ensures integrity.</li>
    <li><strong>Immutability</strong> – Transactions cannot be altered once confirmed.</li>
</ul>

<h3>📌 Types of Blockchains</h3>
<ul>
    <li><strong>Public Blockchains</strong> (Ethereum, Bitcoin) – Open networks, permissionless access.</li>
    <li><strong>Private Blockchains</strong> (Hyperledger) – Restricted access for enterprises.</li>
    <li><strong>Consortium Blockchains</strong> – Controlled by multiple entities.</li>
</ul>

<hr>

<h2>3️⃣ Crypto Wallets</h2>

<h3>🛠 What is a Crypto Wallet?</h3>
<p>A crypto wallet allows users to store, send, and receive digital assets.</p>

<h3>📌 Types of Wallets</h3>
<ul>
    <li><strong>Custodial Wallets</strong> – Centralized control (e.g., Binance, Coinbase).</li>
    <li><strong>Non-Custodial Wallets</strong> – User-controlled keys (e.g., MetaMask, Trust Wallet).</li>
    <li><strong>Hardware Wallets</strong> – Secure offline storage (e.g., Ledger, Trezor).</li>
</ul>

<h3>🔑 Wallet Addresses & Private Keys</h3>
<ul>
    <li><strong>Wallet Address</strong> – Public identifier for receiving funds.</li>
    <li><strong>Private Key</strong> – Secret code controlling wallet access.</li>
</ul>

<hr>

<h2>4️⃣ Introduction to Ethereum</h2>

<h3>🔹 Ethereum Overview</h3>
<ul>
    <li>A decentralized smart contract platform.</li>
    <li>Uses <strong>Ether (ETH)</strong> as the native cryptocurrency.</li>
    <li>Supports <strong>ERC20 (tokens)</strong> and <strong>ERC721 (NFTs)</strong>.</li>
</ul>

<h3>🔹 Ethereum Use Cases</h3>
<ul>
    <li><strong>Decentralized Finance (DeFi)</strong> – Lending, borrowing, staking.</li>
    <li><strong>NFTs</strong> – Digital ownership of assets.</li>
    <li><strong>DAOs</strong> – Community-driven governance.</li>
</ul>

<hr>

<h2>5️⃣ Solidity: Smart Contract Programming</h2>

<h3>📌 What is Solidity?</h3>
<p>A high-level language for writing smart contracts on Ethereum, similar to JavaScript and Python.</p>


<h2>6️⃣ Deploying and Interacting with Smart Contracts</h2>

<h3>🚀 Using Remix IDE</h3>
<ol>
    <li>Open <a href="https://remix.ethereum.org">Remix</a>.</li>
    <li>Create a new Solidity file (<code>.sol</code>).</li>
    <li>Compile and deploy using MetaMask.</li>
</ol>


### Materials:
- **Book**: [*Mastering Ethereum* by Andreas M. Antonopoulos and Gavin Wood (Chapter 1: Introduction to Ethereum).](https://ethereum.org/en/learn/)
- **Online Resources**: [Solidity Documentation](https://soliditylang.org/).   
- **Tools**: Install Remix IDE and MetaMask.

</details>

---

<details>
<summary><strong>Week 2: Solidity Fundamentals</strong></summary><br>

WEEK 2

https://docs.google.com/presentation/d/1etS78gVlWwDJBgpt2-aomsntDFG8mUpQ/edit?usp=sharing&ouid=109207709370381780005&rtpof=true&sd=true


REMIX PRESENTATION

https://docs.google.com/presentation/d/1UkdDAZYwNiS0rGIkdulOonFH6FDs4z9smaaj5iDim1s/edit#slide=id.g12e1023695a_0_0

SEPOLIA FAUCET

https://cloud.google.com/application/web3/faucet/ethereum/sepolia



### Topics Covered:
- Basic syntax and structure of a Solidity contract.
- Data types: `uint`, `address`, `bool`, `string`, etc.
- Variables: State variables, local variables, and constants.
- Functions: Visibility (`public`, `private`, `internal`, `external`), and modifiers.

<h1>Solidity Mondays: Solidity Fundamentals</h1>

<h2>1. Basic Structure of a Solidity Contract</h2>
<p>A Solidity smart contract starts with the <code>pragma</code> directive, followed by the contract definition. Solidity contracts contain functions, variables, and logic that define how they interact on the blockchain.</p>
<pre><code>
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.19; // Specifies the Solidity version

contract MyFirstContract {
    // Contract content goes here
}
</code></pre>

<h2>2. Data Types in Solidity</h2>
<h3>Value Types</h3>
<ul>
    <li><strong>Boolean (<code>bool</code>)</strong>: Stores <code>true</code> or <code>false</code>.</li>
    <li><strong>Unsigned Integer (<code>uint</code>)</strong>: Represents non-negative integers.</li>
    <li><strong>Signed Integer (<code>int</code>)</strong>: Stores positive and negative integers.</li>
    <li><strong>Address (<code>address</code>)</strong>: Stores Ethereum addresses.</li>
    <li><strong>Bytes (<code>bytes1</code> to <code>bytes32</code>)</strong>: Used for cryptographic operations.</li>
    <li><strong>String (<code>string</code>)</strong>: Used for storing text.</li>
</ul>

<h2>3. Functions in Solidity</h2>

***Basic Structure Of A function***<br>
<img src="https://github.com/eben619/Celo_Africa_Dao-Ghana_University_Tour/blob/main/function.avif" width="500px"><br>

<p>Functions define the behavior of a smart contract. They can be public, private, view (read-only), or payable (can receive Ether).</p>
<pre><code>
function getName() public pure returns (string memory) {
    return "Solidity Mondays"; // Returns a fixed string
}
</code></pre>

<h2>4. Variables in Solidity</h2>

<h3>State Variables</h3>
<p>State variables are permanently stored on the blockchain. They retain their values even after the contract execution ends.</p>
<pre><code>
contract Example {
    uint256 public storedNumber; // A state variable stored on the blockchain
    function setNumber(uint256 _num) public {
        storedNumber = _num; // Updates the state variable
    }
}
</code></pre>

<h3>Local Variables</h3>
<p>Local variables exist only within a function's execution scope. They do not persist on the blockchain.</p>
<pre><code>
function getNumber() public pure returns (uint256) {
    uint256 localNumber = 10; // Local variable, exists only in this function
    return localNumber;
}
</code></pre>

<h3>Global Variables</h3>
<p>Global variables provide blockchain-related information such as the sender's address, block number, or timestamp.</p>
<pre><code>
uint256 public blockNumber = block.number; // Gets the current block number
address public sender = msg.sender; // Gets the address of the sender
</code></pre>

<h2>5. Control Structures (If-Else, Loops)</h2>

<h3>If-Else Statement</h3>
<p>The if-else statement allows conditional execution of code based on specific conditions.</p>
<pre><code>
function checkEven(uint256 num) public pure returns (string memory) {
    if (num % 2 == 0) {
        return "Even"; // Returns "Even" if the number is divisible by 2
    } else {
        return "Odd"; // Returns "Odd" if the number is not divisible by 2
    }
}
</code></pre>

<h2>6. Mappings and Structs</h2>

<h3>Mappings</h3>
<p>Mappings store key-value pairs, where keys are unique, and values can be of any type.</p>
<pre><code>
mapping(address => uint256) public balances; // Maps addresses to balances

function updateBalance(address _user, uint256 _amount) public {
    balances[_user] = _amount; // Updates the balance for the user
}
</code></pre>

<h3>Structs</h3>
<p>Structs are used to define custom data structures, grouping multiple data fields.</p>
<pre><code>
struct Student {
    string name;
    uint256 age;
}

Student public student; // Declares a student struct variable

function setStudent(string memory _name, uint256 _age) public {
    student = Student(_name, _age); // Assigns values to the student struct
}
</code></pre>

<h2>7. Events and Logging</h2>
<p>Events in Solidity allow logging data on the blockchain. They are mainly used to track actions like transactions or contract updates.</p>
<pre><code>
event UserRegistered(address indexed user, uint256 timestamp); // Declares an event

function registerUser() public {
    emit UserRegistered(msg.sender, block.timestamp); // Emits an event when a user registers
}
</code></pre>

<h2>8. Modifiers</h2>
<p>Modifiers define rules that must be met before executing a function. They help enforce access control and conditions.</p>
<pre><code>
modifier onlyOwner() {
    require(msg.sender == owner, "Not the owner"); // Checks if the caller is the contract owner
    _;
}

function restrictedFunction() public onlyOwner {
    // Function logic that only the owner can execute
}
</code></pre>

<h2>9. Payable Functions (Handling Ether)</h2>
<p>Payable functions allow contracts to receive and send Ether. The <code>msg.value</code> property holds the amount of Ether sent.</p>
<pre><code>
function deposit() public payable {
    require(msg.value > 0, "Must send some Ether"); // Ensures Ether is sent
}

function getBalance() public view returns (uint256) {
    return address(this).balance; // Returns the contract's balance
}
</code></pre>




### Materials:
- **Book**: *Mastering Ethereum* (Chapter 7: Smart Contracts and Solidity).
- **Practice**: Write a simple "Hello World" contract in Remix IDE.

</details>

---

<details>
<summary><strong>Week 3: Advanced Data Structures</strong></summary>

### Topics Covered:
- Arrays: Fixed-size and dynamic arrays.
- Structs: Custom data types.
- Mappings: Key-value pairs.
- Enums: User-defined types for constants.

### Materials:
- **Book**: *Mastering Ethereum* (Chapter 7: Smart Contracts and Solidity).
- **Practice**: Create a contract that stores and retrieves user data using structs and mappings.

</details>

---

<details>
<summary><strong>Week 4: Control Structures and Error Handling</strong></summary>

### Topics Covered:
- Conditional statements: `if`, `else`, `else if`.
- Loops: `for`, `while`.
- Error handling: `require`, `assert`, `revert`.

### Materials:
- **Online Resources**: [Solidity by Example](https://solidity-by-example.org/).
- **Practice**: Write a contract that implements a basic voting system with error handling.

</details>

---

<details>
<summary><strong>Week 5: Function Modifiers and Events</strong></summary>

### Topics Covered:
- Function modifiers: `view`, `pure`, `payable`.
- Custom modifiers.
- Events: Logging and listening to events.

### Materials:
- **Book**: *Mastering Ethereum* (Chapter 7: Smart Contracts and Solidity).
- **Practice**: Add events to your voting contract to log votes.

</details>

---

<details>
<summary><strong>Week 6: Inheritance and Interfaces</strong></summary>

### Topics Covered:
- Inheritance: `is` keyword, parent and child contracts.
- Abstract contracts.
- Interfaces: Defining and implementing interfaces.

### Materials:
- **Online Resources**: [Solidity Documentation](https://soliditylang.org/).
- **Practice**: Create a parent contract with shared functionality and a child contract that inherits from it.

</details>

---

<details>
<summary><strong>Week 7: Security Best Practices</strong></summary>

### Topics Covered:
- Common vulnerabilities: Reentrancy, integer overflow, and more.
- Security tools: Slither, MythX.
- Writing secure code.

### Materials:
- **Book**: *Mastering Ethereum* (Chapter 9: Smart Contract Security).
- **Online Resources**: [Consensys Smart Contract Best Practices](https://consensys.github.io/smart-contract-best-practices/).
- **Practice**: Audit a simple contract for vulnerabilities.

</details>

---

<details>
<summary><strong>Week 8: Deploying and Interacting with Contracts</strong></summary>

### Topics Covered:
- Deploying contracts to testnets (Ropsten, Rinkeby, etc.).
- Interacting with contracts using Web3.js or Ethers.js.
- Gas optimization techniques.

### Materials:
- **Book**: *Mastering Ethereum* (Chapter 10: Tokens).
- **Tools**: Infura, Alchemy, or Hardhat for deployment.
- **Practice**: Deploy your voting contract to a testnet and interact with it using a simple frontend.

</details>

---

<details>
<summary><strong>Week 9: Tokens and Standards</strong></summary>

### Topics Covered:
- ERC-20: Fungible tokens.
- ERC-721: Non-fungible tokens (NFTs).
- ERC-1155: Multi-token standard.

### Materials:
- **Book**: *Mastering Ethereum* (Chapter 10: Tokens).
- **Practice**: Create and deploy your own ERC-20 token.

</details>

---

<details>
<summary><strong>Week 10: Advanced Topics and Final Project</strong></summary>

### Topics Covered:
- Upgradeable contracts using proxies.
- Layer 2 solutions: Optimism, Arbitrum.
- Decentralized Autonomous Organizations (DAOs).

### Materials:
- **Book**: *Mastering Ethereum* (Chapter 11: Oracles and Chapter 12: Decentralized Applications).
- **Final Project**: Build and deploy a decentralized application (dApp) that incorporates everything you’ve learned.

</details>

---

## Additional Resources
- **Books**:
  - *Mastering Ethereum* by Andreas M. Antonopoulos and Gavin Wood.
  - *Solidity Programming Essentials* by Ritesh Modi.
- **Online Courses**:
  - [CryptoZombies](https://cryptozombies.io/).
  - [Ethereum.org Learn Section](https://ethereum.org/en/learn/).
- **Communities**:
  - Ethereum Stack Exchange.
  - Reddit: r/ethdev.
  - Discord: Ethereum Developer Community.

---

## Final Thoughts
By following this **Solidity Fridays** schedule, you’ll gain a solid understanding of Solidity and Ethereum development. Happy coding! 🚀

Don't forget to follow these ETHAccra channels to get regular Updates.

### Telegram: https://t.me/+pXympPbcG7U5NWI0

### X (Twitter): https://x.com/ETHAccra
