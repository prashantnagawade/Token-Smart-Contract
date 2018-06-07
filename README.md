# Token-Smart-Contract

## ERC-223
ERC223 is a superset of the ERC20 token standard. It is also a more safe standard as it doesn't allow token transfers to contracts that don't support token receiving and handling. This proposal was introduced by a developer, who decided to solve issues with the current ERC-20 standard for tokens. Below I excluded main features of this proposed standard. 
###### **Advantages:**
•	Provides a possibility to avoid accidentally lost tokens inside contracts that are not designed to work with sent tokens.

•	Transfer to contracts consumes less gas than ERC-20: The transfer of ERC223 tokens to a contract is a one-step process rather than 2 step process (for ERC20)

•	Allows developers to handle incoming token transactions, and reject non-supported tokens (not possible with ERC20)

###### **Disadvantages and risks:**
•	ERC-223 is a proposal right now, not a standard. Therefore, there are none of the high-profile ICO tokens deployed with this standard. Also, it is not yet implemented in any production tokens that I found from my research.

•	Exchanges may need to do some modifications in order to support such token. There is a chance that some of the exchanges might not be prepared for it yet.

•	The benefits that this standard brings are not that high compared to risks of using unofficial token interface, which is not yet accepted by Ethereum foundation and is not a standard.
