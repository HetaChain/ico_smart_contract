# HetaChain - A Platform For Smart Economy

Too many blockchain projects build solutions that don’t work, for problems that don’t exist. Through our strategic partners, we created a global network of businesses that were asking for blockchain solutions, and defined a feature set based on their needs. We saw the opportunity to build a blockchain platform with broad applications across government, business, and communities.

Click [here](https://heta.org/) to get more information.  

## SMART CONTRACT FEATURES

```
function name() public pure returns(string)
```

Return token name: Heta Token.

```
function symbol() public pure returns(string)
```

Return token symbol: HETA.

```
function decimals() public pure returns(uint8)
```
 
Return token decimals: 18.

```
function totalSupply() public view returns (uint256)
```

Return total supply of token issues: 60 billion.

```
function balanceOf(address owner) public view returns (uint256)
```

Return the balance of a nominated address **owner**: The parameter is the address owner.

```
function allowance(address owner, address spender) public view returns (uint256)
```

Return the number of the token that the address **owner** allows the address **spender** to use.

``` 
function increaseAllowance(address spender, uint256 addedValue) public returns (bool)
```

Increase the number of the token that the address **spender** can use (thanks to the address **owner**) .

```
function decreaseAllowance(address spender, uint256 subtractedValue) public returns (bool)
```

Decrease the number of the token that the address **spender** can use (as the address **owner** increases).

```
function transfer(address to, uint256 value) public returns (bool)
```

Forward the token to the address **to**: The parameter is the address to and the number of the token to be forwarded.

```
function transferFrom(address from, address to, uint256 value) public returns (bool)
```

Forward the token from the address **from** to the address **to**. 

```
function batchTransfer(address[] tos, uint256[] values) public returns (bool)
```

Forward the token to many **address-tos**: the parameter is the list of many address-tos and the number of the token to be forwarded to each address.

```
function approve(address spender, uint256 value) public returns (bool)
```

Approve to forward the token to the address **spender**.

```
event Burn(address indexed burner, uint256 value);
```

Event **burn token**.

Used when not all tokens are distributed after ICO.

```
function burn(uint256 value) public 
```

Allow to burn a given number of token of a nominated address owner.

Used when not all tokens are distributed after ICO.

```
function burnFrom(address from, uint256 value) public 
```

Allow to burn a given number of the token of a nominated address owner: The parameter is the address and the number of token to burn.

Used when not all tokens are distributed after ICO.

```
function TokenTimelock(ERC20Basic _token, address _beneficiary, uint64 _releaseTime) public
```

Allow to lock a given number of the token of the nominated address with the releaseTime: The parameters are the number of token, the address and the lock time.
Used when it is necessary to lock all tokens of the founder team, development team, etc. within the period of **releaseTime, withdrawing or forwarding token is only approved after this period.**

```
function release() public 
```

Allow to unlock the token of the nominated address after the lock time exhausts.
The parameters are the number of token, the address and the lock time.
Used when it is necessary to lock all tokens of the founder team, development team, etc. within the period of **releaseTime, withdrawing or forwarding token is only approved after this period.**

```
function pause() public
```

Allow an admin address to pause forwarding the token to other addresses.

```
function resume() public
```

Allow an admin address to resume the pause of forwarding the token to other addresses. 

### Compiled with [Truffle](https://truffleframework.com/)

## Deployment on ropsten

### Ropsten testnet

Token contract:

```
https://ropsten.etherscan.io/token/0xf12f62e5b7e37b883c51190b35d151fce561f12f
```

Team's funding lock contract:

```
https://ropsten.etherscan.io/address/0xf88031112b84d03f1621a39d243015c75659b609
```

Advisors' funding lock contract:

```
https://ropsten.etherscan.io/address/0x2cb9c99fe6472cb60408c72f9db7cac0ccd6d14a
```

### Rinkeby testnet

Token contract:

```
https://rinkeby.etherscan.io/token/0xf12f62e5b7e37b883c51190b35d151fce561f12f
```

Team's funding lock contract: 

```
https://rinkeby.etherscan.io/address/0xf88031112b84d03f1621a39d243015c75659b609
```

Advisors' funding lock contract:

```
https://rinkeby.etherscan.io/address/0x2cb9c99fe6472cb60408c72f9db7cac0ccd6d14a
```

## License

The [MIT](https://choosealicense.com/licenses/mit/) License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

