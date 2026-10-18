// SPDX-License-Identifier: MIT
// BS3G Gold VAULT - World's First CERN-Indexed Token
// DOI: 10.5281/zenodo.23340833
// Creator, Maker, Owner: Socrates Kargbo
// License: MIT

pragma solidity ^0.8.20;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

contract BS3GGoldVault is ERC20 {
    constructor() ERC20("BS3G Gold VAULT", "BS3G") {
        _mint(msg.sender, 4858784 * 10 ** decimals());
    }
}
