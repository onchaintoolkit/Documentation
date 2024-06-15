---
description: >-
  Overview and technical documentation for Smart Contract scanner utilizing
  Slither Analytic tool.
---

# AI Smart Contract Scanner

## <mark style="color:green;">Introduction</mark>

Onchain Toolkit Smart Contract Scanner is powered by Revoluzion, an advanced AI-driven analytical tool designed to enhance the security and performance of smart contracts on various blockchain networks. The scanner leverages the power of Slither, a Python-based static analysis framework, to identify potential vulnerabilities and optimization opportunities within smart contracts. Hosted on Heroku’s robust cloud platform, it provides developers, auditors, and stakeholders with crucial insights into smart contract code, integrating cutting-edge AI technology to ensure thorough analysis and improved contract integrity.

***

## <mark style="color:green;">System Overview</mark>

Onchain Toolkit Scanner is enhanced by integrating AI capabilities, operating by accepting a smart contract address input from the user along with the selection of the corresponding blockchain network. This input initiates a comprehensive AI-assisted scanning process powered by the Slither framework, which examines the bytecode and source code, when available, of the submitted smart contract. The inclusion of AI technologies allows for more nuanced analysis and prediction of potential vulnerabilities.

***

## <mark style="color:green;">Technical Workflow</mark>

### Input and Initialization:

* **Contract Address**: Users input the address of the smart contract they wish to analyze.
* **Network Selection**: Users select the network on which the contract resides (e.g., Ethereum, Binance Smart Chain).

### Analysis Process:

* **Slither Integration**: Upon submission, the scanner triggers a Heroku-hosted Python script that utilizes Slither, enhanced by AI algorithms, to statically analyze the contract.
* **Vulnerability Detection**:AI-driven Slither inspects the contract’s codebase for known patterns that indicate potential security issues or areas for codebase optimization.
* **Optimization Identification**: The program assesses the contract's structure and logic for efficiency and optimization opportunities.

***

## <mark style="color:green;">Heroku Server Usage</mark>

The Onchain Toolkit Scanner's back-end services are deployed on Heroku, a cloud platform as a service (PaaS) that enables seamless interaction with the Slither framework. Heroku's dynamic server allocation allows for the scalable execution of the Python script necessary for smart contract analysis.

### Rate Limits and Operational Guidance

Due to Heroku server's rate limits and traffic management protocols, there are occasions when the Onchain Toolkit Scanner may fail to fetch data on the first attempt. In such cases, users are advised to:

* **Refresh the Page**: A simple page refresh can reinitiate the scanning process.
* **Retry the Scan**: If the initial attempt is unsuccessful, users should wait momentarily before retrying.

### Output and Recommendations

Upon completion of the scan, the Onchain Toolkit Contract Scanner provides:

* **Preliminary Analysis**: A brief report summarizing the identified vulnerabilities and areas for optimization.
* **Actionable Recommendations**: Suggestions for improving contract security and efficiency based on the scan results.

***

## <mark style="color:green;">Frequently Asked Questions</mark>

### Why doesn't it work at times?

**Possible due to rate limit:** The Heroku server hosting the scanner has rate limits. If many users are accessing the service simultaneously, it might temporarily be unavailable.&#x20;

**What to do:** Try to refresh the page or wait a moment before trying to input the data again.

### It still doesn't work?

**Check Network and Address:** Ensure you have selected the correct blockchain network and entered the accurate smart contract address.&#x20;

**Check Code Verification:** The scanner requires the contract's source code to be verified. If it's not, the scanner cannot perform the analysis.

### Can it scan contracts that are not verified?

**No:** The Onchain Toolkit Scanner needs the contract's source code for a comprehensive analysis. Contracts that are not verified only provide bytecode, which isn't sufficient for a detailed scan.

### It says "error file missing."

**File Name Mismatch:** This error occurs when the scanner attempts to locate the contract file but finds that the filename has been altered or differs from what was expected during deployment.&#x20;

**What to do:** Verify that the contract's file name matches the one used during its deployment and is correctly reflected on the blockchain explorer.

### Will it work with non-flattened contracts?

**Yes:** The Onchain Toolkit Scanner is capable of working with non-flattened contracts. It automatically flattens the contract and proceeds with the scan. This means it consolidates all imported files and contracts into a single file for analysis.

### How often is the scanner updated?

**Regular Updates:** The scanner is regularly updated to include the latest security checks and optimizations. However, the frequency of updates might vary based on the development cycle and emerging security trends in the blockchain space.

### Can I rely solely on the scanner for contract's security?

**Part of a Broader Strategy:** _The Onchain Toolkit Scanner_ should be part of a broader security strategy that includes manual reviews, professional audits, and ongoing monitoring. No single tool can guarantee complete security, given the complexity and evolving nature of smart contracts.



***

##
