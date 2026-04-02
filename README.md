# ClearMessage.sol
ClearMessage.sol4
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract ClearMessage {
    string public message;
    function clear() public { delete message; }
}
