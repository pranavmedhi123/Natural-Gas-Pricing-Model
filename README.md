# Natural-Gas-Pricing-Model

#### Problem Statement:
- Write a function to return total value of a gas storage contract.

#### Components to consider:
1. Maximum storage capacity.
2. Storage costs per day.
3. Injection/Withdrawal cost per unit of gas.
4. Injection Dates and Prices.
5. Withdrawal Dates and Prices.

#### Limitations to consider:
1. Injection should not exceed Total Maximum storage capacity.
2. Withdrawal should not exceed Total Stored Gas at that point or Maximum storage capacity.

#### Pseudo Code
1. We need to keep track of number of days the gas units are stored at each step.(Storage costs need to be updated at each Injection/Withdrawal date)
2. Rough forumula : Contract Value= Price_Withdrawal*Withdrawal_Volume-Storage_costs- Injection Costs(to date)-Withdrawal Costs(to date).
3. While calculating gas stored at each step and keeping it less than or equal to Maximum storage capacity.
