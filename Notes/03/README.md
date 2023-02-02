
Here we introduce you to some primitive VALUE data types available in Solidity.

boolean (true or false)</br>
uint (no negative numbers)</br>
int (both negative and positive numbers) </br>
address</br>

=========================================

// SPDX-License-Identifier: MIT
pragma solidity ^0.8.17;

contract Primitives { </br>
    bool public boo = true; </br>
    uint public u = 123; </br>
    int public i = -123; </br>
    address public addr = 0xCA35b7d915458EF540aDe6068dFe2F44E8fa733c; </br>
 }
