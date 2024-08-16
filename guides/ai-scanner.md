# 🟢 AI Scanner

The AI Scanner provided by GoPlus and Revoluzion is a comprehensive tool designed to help users scan and analyze token addresses, normal wallet addresses, smart contracts, and allowances in user wallets. Below is a detailed guide on how to utilize each tab within the AI Scanner.

***

### **Token Address Tab**

This tab allows users to scan and analyze token smart contract addresses on various networks.

**Select Network:**

<figure><img src="../.gitbook/assets/image.png" alt="" width="520"><figcaption></figcaption></figure>

* Begin by selecting the network on which the token is deployed (e.g., Ethereum, BSC, Polygon).



**Input Contract Address:**

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

* Paste the token's smart contract address into the provided input field.



**Click Scan:**

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

* After entering the address, click the "Scan" button to initiate the analysis.
* **Error Handling:**

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

* Note that if the contract address provided is not a token smart contract address, an error message will appear, indicating that the address needs to be a valid token smart contract.
* Also note that, if the total of the address is 42 and below, clicking scan will not result anything.

***

### **Contract Tab**

This tab is dedicated to scanning smart contracts for vulnerabilities and optimization.

**Select Network:**



* Select the appropriate network where the contract is deployed.



**Input Contract Address:**



* Enter the smart contract address in the provided field.



**Scan for Vulnerabilities:**



* Click the "Scan" button to analyze the contract. The scanner will assess the code for vulnerabilities and optimization issues, providing a detailed report.

***

**3. Address Tab**

The Address tab is used to scan any wallet address for potential malicious activities.

**Select Network:**



* Choose the network on which the wallet address operates.



**Input Wallet Address:**



* Paste the wallet address you want to scan into the input field.



**Scan for Malicious Activity:**



* Click the "Scan" button to detect any malicious conduct associated with the wallet address.
* If there is no allowance available for the wallet address, an error sonner will pop up as below : ![](<../.gitbook/assets/image (5).png>)

***

**Allowance Tab**

The Allowance tab allows users to check and manage token allowances for their wallet addresses.

**Connect Wallet:**



* Before using this tab, click the "Connect Wallet" button to connect your wallet to the scanner.



**Select Network:**



* After connecting your wallet, select the network on which your wallet operates.



**Input Wallet Address:**



* Enter your wallet address in the provided field.



**Scan Allowances:**

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

* Click "Scan" to view all token allowances granted by your wallet. The scanner will display a list of allowances, showing the tokens, their corresponding smart contracts, and the amount allowed.
*   In the event the scan button do not appear, it means that you have yet to connect your wallet. Click on the connect wallet button to connect your wallet first.

    <figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>
* Even after connecting your wallet, you can still scan for allowances associated with any other wallet address. However, please note that you won't have the ability to revoke those allowances for addresses other than your own.



* **Revoke Allowances:**
  *   If you wish to revoke any allowance, simply click the "Revoke" button next to the corresponding allowance. This will remove the permission granted to the smart contract, preventing it from accessing your tokens.

      <figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>
  *   When you click the "Revoke Allowance" button, a confirmation prompt will appear in your connected wallet (e.g., MetaMask). You will then need to approve the transaction, which will reset the allowance to zero.

      <figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>
  *   In the event there is no revoke allowance button is shown and change network button instead as shown below, kindly click on change network to the appropriate network and the revoke button will be shown.

      <figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

#### Important Notes:

{% hint style="warning" %}
* **Accuracy:** While the AI Scanner is a powerful tool, it may not always be 100% accurate. Users are advised to conduct their own research and due diligence in addition to using this tool.
* **Security:** Ensure your wallet is connected securely, and always double-check the addresses and contracts you are scanning to avoid phishing attacks or malicious actions.
* **User Responsibility:** The user is responsible for the decisions made based on the scanner's results. Neither GoPlus, Revoluzion, nor the platform takes responsibility for inaccuracies or misuse of the tool.
{% endhint %}
