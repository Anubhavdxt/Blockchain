# Incentive Model

Module two, lesson four, the incentive model. As we learned earlier in module one, mining is the process used to secure the network by validating the computations, collecting them to form a block, verifying them, and broadcasting it.

Ethereum also uses a incentive-based model for block creation.

In this lesson we'll explore some relevant concept about fee structure and the incentive model.

Every action in Ethereum requires crypto fuel, or gas. Gas points are used to specify the fees inside of Ether, for ease of computation using standard values.

Gas points allow for cryptocurrency independent valuation of the transaction fee and computation fees.

Ether, as a cryptocurrency, varies in value with market swings, but gas points do not vary.

Ethereum has specified gas points for each type of operation. Mining process computes gas points required for execution of a transaction.

If the fee specified and the gas point in the transaction are not sufficient, it is rejected. This is similar to mailing a letter with insufficient postage. The letter will not be delivered if it had insufficient postage. The gas points needed for execution must be in the account balance for the execution to happen. If there is any amount left over after the execution of a transaction, it is returned to the originating account.

So far we looked at the gas related items in a transaction, now let's look at the gas related items in a block. Gas limit and gas spent.

Gas limit is the amount of gas points available for a block to spend. For example, if a block specifies a limit of 1 million 5 hundred thousand units of gas, and a basic Ether transaction fee is 21,000, this particular Ethereum block can fit about 70 plain Ether transactions. If we add smart contract transactions also into this block, that usually requires more gas, and the number of transactions for this block will likely be lower.

Gas spent is the actual amount of gas spent at the completion of the block creation. Now let's look at the mining incentive model. The proof of work puzzle winner, miner that creates a new block, is incentivized with the base fees of three Ethers, and the transaction fees in Ethereum blockchain.

The winning miner also gets the fees, gas points for execution of a smart contract transactions.

That there may be other miners who also solve the puzzle besides the winner.

These miners will solve the puzzle, but didn't win the block are called Ommers. The blocks created by them are called Ommer Blocks. These are added as Ommer Blocks, or side blocks, to the main chain.

Ommer miners also get a small percentage of the total gas points as a consolation and for network security. Summarizing, any transaction in Ethereum, including transfer of Ethers, requires fees or gas points to be specified in the transactions. Miners are paid fees for security, validation, execution of smart contract, as well as for creation of blocks. We presented a high level view of Ethereum blockchain. We'll use Ethereum as a reference blockchain in the next two modules and the following two courses.

## Resources

- [Vitalik Buterin Doubles Down on Ethereum Incentive Strategy](https://www.coindesk.com/vitalik-buterin-doubles-ethereum-incentive-strategy/)
- [Ether](https://www.ethereum.org/ether)
- [Proof of Work vs Proof of Stake: Basic Mining Guide](https://blockgeeks.com/guides/proof-of-work-vs-proof-of-stake/)
