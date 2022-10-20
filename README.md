# Overview
Prestare Finance (Prestare) is a lending protocol that offers a lower collateral ratio and can even support under-collateralized loans with almost any assets, without using off-chain information. Compared with other lending protocols, we bring greater capital efficiency to catalyse DeFi growth and adoption.


# Features

Under-collateralized borrowing is achieved by **allowing the borrower to use a portion of the previously accumulated interests as collateral to borrow more funds next time**. A portion of interest paid by borrowers will be reserved in ‘Credit Reserve Pool’. 1 CRT is minted with $1 in the pool, then distributed to borrowers who contributed to the pool. CRT can be used for collateral in the next borrowing, making the loan under-collateralized.

**SoulBound Token containing credit score for all users need to be minted if users want to borrow on Prestare**. Users with higher credit score can have a loan with lower collateral ratio. An address’s initial credit score will be capped and determined based on the address’s prior interactions with other protocols and addresses when it first interacts with Prestare.

Permissionless Listing is introduced to Prestare by **adopting isolated assets tiers**. Assets on Prestare are divided into different tiers according to their risk. Users putting certain tier assets as collateral can only borrow the money from the corresponding tier pool out. If prices of low-tier assets are manipualted, only deposits in the particular tier will be affected. Risks are minimized.

Internal Liquidation can be done on Prestare. **Liquidity providers can choose to use their deposits to buy liquidated assets**. As a result, depositors can swap deposits into their favourite assets with discounts and save gas fees and slippages which occur on DEX, while enjoying saving interest on Prestare. This is designed to absorb debt from liquidations, and reward depositors with the liquidated collateral shared between depositors in proportion to their deposit size.

# Problems that Prestare is solving

## Collateralized loans
Under-collateralized borrowing has been the hard-to-achieve holy grail in decentralized finance (DeFi). In order to operate trustlessly, decentralized lending protocols, like Compound and AAVE, are predominantly over-collateralized to ensure the lenders can be paid back in case of a default. This means that borrowers will have to deposit an amount that exceeds the value of any loans. As noble as it sounds to serve the underbanked and the unbanked, the truth of the matter is that over-collateralized borrowing does not reach the borrowers in need. Because they are unlikely to afford the necessary crypto assets to begin with. Simply put, over-collateralized loans are not an efficient allocation of capital.

## Permissioned Listing
Compound and Aave are two examples of first-generation DeFi lending systems. Users have access to loan and borrowing features for a few of the most liquid ERC20 tokens thanks to these protocols. However, these protocols have relied on a permissioned listing system to protect their users from the hazards associated with lending and borrowing illiquid or volatile assets because they were not intended to handle those risks.
