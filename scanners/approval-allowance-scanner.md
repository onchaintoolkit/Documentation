# Approval Allowance Scanner

## <mark style="color:purple;">Introduction</mark>

The Onchain Toolkit Allowance Approval Scanner is powered by Goplus a comprehensive tool designed to analyze and monitor the approvals granted to various contracts for spending tokens on behalf of users. This scanner is an essential part of risk management and security for token holders on blockchain networks like Ethereum (ETH), Binance Smart Chain (BSC), and Polygon (MATIC). By entering a verified contract address, users can access detailed information about the allowances set for that token, identifying potential risks and ensuring better control over their digital assets.

## <mark style="color:purple;">System Overview</mark>

The Onchain Toolkit Allowance Approval Scanner operates through an API endpoint that accepts a request containing the address of the user or token contract. It returns a detailed response, providing a breakdown of all contracts that have been approved to spend tokens, the amount they are allowed to spend, and other crucial data points.

## <mark style="color:purple;">How It Works</mark>

1. **User Input**: Users select the blockchain network (ETH, BSC, or Polygon) and enter the address of the token or wallet they wish to analyze.
2. **API Request**:The provided address is sent to the GoPlus Allowance Approval Scanner API endpoint.
3. **Data Analysis**: The scanner processes the address and returns a JSON object with various data points related to the allowances set for that address.

## <mark style="color:purple;">Key Features and Data Points</mark>

* **Token Information**: Details about the token including address, name, symbol, and decimals.
* **Allowance Details**: Information about each contract approved to spend tokens, including:
  * **Approved Contract**: The address of the contract that has been given approval.
  * **Approved Amount**: The amount of tokens the contract is allowed to spend.
  * **Approval Time**: When the approval was given.
  * **Initial Approval Time and Hash**: The time and transaction hash of the first approval.
* **Contract Analysis**: Information about the approved contracts, including:
  * **Contract Name**: The name of the contract, if available.
  * **Creator Address**: The address of the contract's creator.
  * **Open Source Verification**: Whether the contract's code is verified and open source.
  * **Malicious Behavior**: Any known malicious behavior associated with the contract.
  * **Deployment Time**: When the contract was deployed.
* **Risk Assessment**: Analysis of potential risks associated with the token and approved contracts, including malicious addresses and behaviors like gas abuse and honeypot-related activities.

## <mark style="color:purple;">Operational Guidance</mark>

* **Verified Contracts Only**: The scanner requires the token's contract to be verified as it relies on detailed information about the token and associated contracts.
* **Interpreting Results**: The data returned should be used as a guide to understand potential risks and to manage token allowances effectively. High allowances to unknown or untrusted contracts should be treated with caution.

## <mark style="color:purple;">Best Practices and Disclaimer</mark>

* **Revoke Unnecessary Allowances**: Regularly review and revoke any allowances that are no longer needed or are granted to contracts you no longer trust.
* **Consult Experts**: If you're unsure about an approval or contract, consult with a security expert or conduct further research.
* **Continual Monitoring**: Allowances can be set or changed at any time. Regularly re-scan addresses and stay updated on interactions with your tokens.

