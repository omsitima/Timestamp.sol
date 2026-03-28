# Timestamp.sol
How to deploy a contract on Base Chain Timestamp.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract Timestamp {
    function getTime() public view returns (uint) {
        return block.timestamp;
    }
}
