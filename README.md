# Lesson 17 in Patrick's course HH DAO

- Open Zeppelin provides a special ERC-20 for voting proposals wich is nice

- A lot of the solidity code is leveraged from OpenZeppelin. The TimeLock contract is key, anything the timelock wants to do has to go through the governance process

- propose -> vote -> queue and execute. The key of this lesson is in the scripts folder, by executing each script in the correct order we interact with the DAO. **Understand the scripts/tests, understand the protocol**

- `castVoteBySig` is the function in the GovernorContract that would allow to sign the transaction off chain and submit after as a single transaction ;)

Nice project to interact with Typescript
