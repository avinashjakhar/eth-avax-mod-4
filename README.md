# eth-avax-mod-4 :Unlocking the Future of Gaming

Welcome to the DEGEN Token smart contract repository for the Metacrafters AVAX Course Module 4. This Solidity contract implements a comprehensive token management system that empowers minting, burning, transferring, and redeeming rewards using the DEGEN token.

## Features

- **Minting:** Only the contract owner possesses the authority to mint new DEGEN tokens, thereby increasing the total supply.
- **Burning:** DEGEN tokens can be burned, leading to a reduction in the overall supply.
- **Transferring:** DEGEN tokens can be easily transferred between addresses.
- **Redeeming Rewards:** Users have the opportunity to redeem various rewards using their DEGEN tokens, each tied to a unique reward type.

## Functions

1. `mint(address to, uint256 amount)`: Enables the contract owner to mint new DEGEN tokens and dispatch them to a designated address.
2. `burn(address from, uint256 amount)`: Allows the burning of a specified amount of DEGEN tokens from a given address.
3. `transfer(address to, uint256 amount)`: Facilitates the transfer of a defined amount of DEGEN tokens from the sender's address to a target address.
4. `redeem(address to, uint256 amount, uint256 rewardType)`: Permits the redemption of rewards through DEGEN tokens. This function requires the recipient's address, the amount of tokens to be utilized, and the corresponding reward type.

## How to Use

1. Open the contract in Remix IDE using the provided [link](<link_to_remix>).
2. Deploy the contract using a compatible Solidity compiler version (0.8.18 or higher) by clicking the "Deploy" button.
3. Interact with the contract using the available functions in Remix IDE.
4. To mint tokens, ensure you're logged into Remix with the contract owner's address and execute the `mint` function with the recipient's address and the desired token amount.
5. For redeeming rewards, utilize the `redeem` function with the recipient's address, the amount of tokens to be expended, and the reward type (1 to 4).
6. Explore other functions like `burn` and `transfer` to effectively manage DEGEN tokens.

## Event

The contract emits a "RewardRedeemed" event whenever a reward is successfully redeemed. This event includes crucial information about the recipient's address and the type of reward redeemed.

## Owner Name
Owner: Avinash - 22BCT10100
