// SPDX-License-Identifier: MIT
pragma solidity ^0.8.4;

import "@openzeppelin/contracts@4.6.0/token/ERC721/ERC721.sol";
import "@openzeppelin/contracts@4.6.0/access/Ownable.sol";

contract MyNFT is ERC721, Ownable {
    uint256 public totalSupply;
    constructor() ERC721("MyNFT", "MNFT") {}

    function safeMint(address to) public {
        totalSupply++;
        _safeMint(to, totalSupply);
    }
}
