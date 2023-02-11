# Trusty Multi-Signature Factory
## Author: 0xrms

*Trusty* is a product/service directed towards the individual or the business…

Trusty is on the Goerli TestNet network and allows you to create and manage an infinite number of 2/3 or 3/3 multi-signature smart-contracts/wallets, but it is possible to create variants with specifications on request as its modularity and scalability make it a versatile and powerful tool for different applications.

For the single individual, if you are afraid of a single private key, you can use up to 2 more for the management of a single wallet with double if not triple security

It can be a mixer of TXs and a way to "diversify" funds (traceable by the expert)…
If desired, the possibility of managing any ERC20 Token can be added.

It can be used to build a family safe or use several small wallets to divide up savings or expenses.

The trustyFactory (contract generator and deployer/trusty) can be sold as a bundle to companies to manage internal employee payments or interaction with other companies in the market that have contracts.

It is rather modular and adaptable therefore, in addition to acting as our service that delivers and deploys Trusty for customers upon payment of a commission, it can also be "installed" for internal services or scaled for any use-cases where management/ multiple validation/mediation

A single Trusty can be a corporate vault managed by a few directors or delegates, or several Trustys can act as operating capital for various departments each with its own fund but with the common supervision of a private key or two of the CEOs or managing directors or, if desired, can also act for the internal payment of employees.

It can be used as a deposit fund or as an interaction tool for DeFi, or simply as an NFT or Token management wallet, a bit like a mini-DAO between individuals or several Trusties together.

The trusty can also be seen as a mini governance/DAO that uses funds to interact on the web3 as if it were a unique wallet/entity.

All the big institutions that have large amounts of capital in crypto all use multi-signature wallets on purpose because they are a high level of security.

It goes without saying that it could be adapted very well in the mediation of the use-cases that we have identified for the real estate sector, crowdfunding, etc…

- [You access trusty.app and enter the addresses or ENSs of the other two owners/validators with which to create a Trusty multi-signature wallet and select the minimum number of confirmations that Trusty will need to spend the funds and execute transactions depending on configuration needed.]

- [Once you have created your Trusty, the address will appear in the dApp and an interface for managing its transactions which allows you to deposit funds in the Trusty and create transactions which can then be confirmed/revoked/executed by the other validators/owners of the Trusty.]

- [If instead you are the creator or owner of a Trusty, the TXs proposed by the other owners will appear, if existing, ready for confirmation and execution.]

- [* The use of ENS works if you have registered the domain on Goerli otherwise it does not identify the associated address]

The creation of a trusty/wallet/vault takes place upon payment of the service with 0.10 ETH + fee (currently 0 ETH + fee on TestNet) to the TrustyFactory (the Smart-Contract generator of single Trusty smart-contracts of which only the owner/deployer can withdraw the funds )
The subsequent deposit of funds (management of the trusty) can be mediated by the TrustyFactory (which "if desired" could retain a percentage of the deposits (mediation and costs for the chain management of operations on Trustys).

A trusty can interact with other contracts at will by calling their functions.

- Example: I send a tx to the trusty by setting the "data" parameter in order to spend the funds to call a contract function such as that of the AAVE protocol to deposit collateral or to mint an NFT or a fungible Token from a contract which issues ERC20,ERC721,ERC115 tokens.
Just indicate in the "data" field (now disabled) the name of the function to call and in the "to" field of course the contract with which to interact.