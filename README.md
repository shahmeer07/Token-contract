# Token-contract
The contract Token represents a basic token contract with functionalities for transferring tokens, approving spenders, and transferring tokens on behalf of someone else (if approved).


The constructor initializes the contract with an initial supply of tokens which is then assigned to the deploying address.

The transfer function allows users to transfer tokens from their account to another address. It checks for sufficient balance and emits a Transfer event.

The approve function allows users to approve another address (spender) to spend tokens on their behalf.

The transferFrom function allows a spender to transfer tokens from the owner's account to another address if the allowance is not exceeded.

The balanceOf and allowance mappings keep track of account balances and approved allowances.

The Transfer and Approval events are emitted to notify external observers of token transfers and approvals.
