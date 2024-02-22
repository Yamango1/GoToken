GOYA TOKEN CONTRACT

This is the smart contract for a token (GOYA). The contract includes functionality for minting new tokens and burning existing tokens.

TOKEN DETAILS

*Token Name: GOYA
*Token Abbreviation: GYA
*Token Supply: [Enter Total Supply]

PUBLIC VARIABLES

*tokeName: The name of the token (string).
*tokenAbbrv: The abbreviation or symbol of the token (string).
*totalSupply: The total supply of the token (uint).

MAPPING VARIABLE

balances: A mapping of addresses to token balances.

FUNTIONS

mint(address _address; uint _value)

MInts _value number of tokens and assigns them to the specified _address. Increases total supply accordingly.

burn(address _address, uint _value)

Burns _value number of tokens from the specified _address. Decreases total supply accordingly.
Note: the burn function is limited to only burn if the tokens are available and only that _address.

