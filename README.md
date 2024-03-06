**DeliveryBoy Contract**

The `DeliveryBoy` contract in Solidity is designed to manage the delivery operations carried out by a delivery person. It keeps track of the total number of orders completed, provides incentives based on performance, and calculates bonuses for timely completion of orders.

### Features

1. **Delivery Boy Identification**: The contract identifies the address of the delivery person upon deployment.

2. **Total Orders Tracking**: It keeps track of the total number of orders completed by the delivery person.

3. **Incentive System**: The contract provides incentives to the delivery person based on the total number of orders completed. If the total orders exceed 15, incentives are provided.

4. **Bonus Calculation**: It calculates a bonus for timely completion of orders. If the total orders exceed 15 and the time taken to complete the orders is less than 10 hours, a bonus of 1000 wei is transferred to the delivery person.

### Contract Deployment

Deploy the contract on a blockchain network supporting Solidity smart contracts, such as Ethereum, using the provided SPDX-License-Identifier: MIT.

### Usage

1. **Deployment**: Deploy the contract on the desired blockchain network.

2. **Total Orders Tracking**: The contract automatically tracks the total number of orders completed by the delivery person.

3. **Incentive Checking**: Use the `checkIncentives` function to check if incentives are provided based on the total number of orders completed.

4. **Bonus Calculation**: If the delivery person completes more than 15 orders and takes less than 10 hours to complete them, a bonus of 1000 wei is transferred to their address.

### License

This project is licensed under the MIT License. See the SPDX-License-Identifier in the source code for details.

