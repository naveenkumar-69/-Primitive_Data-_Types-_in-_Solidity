# -Primitive_Data-_Types-_in-_Solidity Challenge
In this contract, the getEtherValue function is marked as payable to allow users to send ether along with the function call. The function receives the ether value in wei through the msg.value variable.
The function then calculates the value in ether by dividing the weiValue by 1 ether (where 1 ether is equal to 1e18 wei). Similarly, it calculates the value in gwei by dividing the weiValue by 1 gwei (where 1 gwei is equal to 1e9 wei).
The function returns the values in wei, ether, and gwei as a tuple (weiValue, etherValue, gweiValue).
