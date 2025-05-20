# Experiment 2: Blockchain-Based Crowdfunding (Kickstarter Alternative)

## Aim:
To create a decentralized crowdfunding platform where donors contribute funds only if the campaign goal is met.

## Algorithm:
A project owner starts a campaign with a funding goal and deadline.
### Step 1:
Deploy a smart contract where the project owner sets the funding goal and deadline.

### Step 2:
Define campaign details: project owner address, funding goal, deadline, total contributions, and contributors.

Contributors can send ETH to the campaign.
### Step 3:
Contributors send ETH to the campaign, and their contribution is recorded in the contract.

### Step 4:
The smart contract tracks the total ETH raised for the campaign.

If the goal is met before the deadline, funds are released to the project owner.
### Step 5:
After each contribution, check if the funding goal is met before the deadline.

### Step 6:
If the goal is met before the deadline, release funds to the project owner. If the goal isn’t met before the deadline, allow contributors to withdraw their funds.

If the goal is not met, contributors can withdraw their funds.
### Step 7:
Contributors can withdraw their funds if the goal was not met.

### Step 8:
Once the deadline passes, the campaign ends, and either funds are released to the owner or refunded to contributors.

## Program:
```
REG NO : 212223240141
NAME : RIYA P L

// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

@@ -60,15 +76,12 @@ contract Crowdfunding {
   }
}
```
# Expected Output:
Users can contribute ETH to the campaign.


If the goal is met, the creator can withdraw funds.

# Output:
![Screenshot 2025-04-16 094918](https://github.com/user-attachments/assets/615e7834-a661-4485-9f3b-a9484b38df23)

If the goal is not met, contributors can claim a refund.
![Screenshot 2025-04-16 094939](https://github.com/user-attachments/assets/da372534-870e-4301-a71b-57a9788b969d)

![Screenshot 2025-04-16 094950](https://github.com/user-attachments/assets/1a4175ff-7350-46fb-a2e6-4bf59ad8c892)

# High-Level Overview:
Teaches decentralized fundraising.
@@ -77,3 +90,4 @@ Teaches decentralized fundraising.
Avoids fraud by ensuring funds are only transferred if the goal is met.

# RESULT: 
Thus the Blockchain-Based Crowdfunding is successfully implemented.
