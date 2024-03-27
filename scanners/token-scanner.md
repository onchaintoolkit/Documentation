# Token Scanner

## <mark style="color:green;">Introduction</mark>

The Onchain Toolkit Token Scanner is powered by Goplus, an advanced analytical tool designed to provide an in-depth examination of tokens on various blockchain networks including Ethereum (ETH), Binance Smart Chain (BSC), and Polygon (MATIC). It is aimed at investors, developers, and analysts who need to assess the security, legitimacy, and potential risks associated with a token. By entering a verified contract address, users can receive a comprehensive breakdown of the token's characteristics and risk factors.

***

## <mark style="color:green;">System Overview</mark>

The Onchain Toolkit Token Scanner operates through an API endpoint that accepts a request containing the contract address of a token. It returns a detailed response, including various attributes and risk factors associated with the token. The scanner analyzes the token's smart contract for common vulnerabilities, ownership details, liquidity provisions, and more.

***

## <mark style="color:green;">How It Works</mark>

1. **User Input**: Users select the blockchain network (ETH, BSC, or Polygon) and enter the verified contract address of the token they wish to analyze.
2. **API Request**: The provided contract address is sent to the GoPlus Token Scanner API endpoint.
3. **Data Analysis**: The scanner processes the contract and returns a JSON object with various data points and risk assessments.

***

## <mark style="color:green;">Key Features and Detected Attributes</mark>

* **Contract Analysis**: Determines if the contract is open source, a proxy, mintable, and if it can be paused or has self destruct capabilities.
* **Ownership Details**: Identifies the creator's address, balance, and percentage of ownership. It also checks if the ownership is hidden or can be renounced.
* **Anti-Whale Mechanisms**: Checks for mechanisms that limit the maximum transaction amount to prevent large holders (whales) from manipulating the token price.
* **Tokenomics**: Provides details on the token's name, symbol, total supply, and taxes (if any) on buying and selling.
* **Liquidity Analysis**: Assesses the liquidity available in DEXs, type of liquidity provision, and details of liquidity pair addresses.
* **Holder Analysis**: Lists the top holders, their balances, and the percentage of tokens they hold. It also identifies if their tokens are locked and for how long.
* **Risk Factors**: Evaluates if the token is a potential honeypot, is blacklisted, or has other associated risks like a high number of tokens with the same creator.

***

## <mark style="color:green;">Operational Guidance</mark>

* **Verified Contracts Only**: The scanner requires the token's contract to be verified, as it relies on analyzing the contract's source code.
* **Rate Limits**: Note that API rate limits may apply. If a request fails, wait a moment before trying again.
* **Interpreting Results**: The data returned should be used as a guide to understand potential risks and issues with a token. It's not a definitive indication of security or value.

***

## <mark style="color:green;">Best Practices and Disclaimer</mark>

* **Supplementary Research**: The scanner's output should complement your research and due diligence. Always look into the project's team, history, and community discussions.
* **Professional Consultation**: For significant investments or development, consult with a professional auditor or legal advisor to interpret the findings appropriately.
* **Continual Monitoring**: Token attributes and risks can change over time. Regularly re-scan tokens and stay updated on project developments.

***

