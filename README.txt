<h1 id="hetachainaplatformforsmarteconomy">HetaChain - A Platform For Smart Economy</h1>

<p>Too many blockchain projects build solutions that don’t work, for problems that don’t exist. Through our strategic partners, we created a global network of businesses that were asking for blockchain solutions, and defined a feature set based on their needs. We saw the opportunity to build a blockchain platform with broad applications across government, business, and communities.</p>

<p>Click <a href="https://heta.org/">here</a> to get more information.  </p>

<h2 id="smartcontractfeatures">SMART CONTRACT FEATURES</h2>

<pre><code>function name() public pure returns(string)
</code></pre>

<p>Return token name: Heta Token.</p>

<pre><code>function symbol() public pure returns(string)
</code></pre>

<p>Return token symbol: HETA.</p>

<pre><code>function decimals() public pure returns(uint8)
</code></pre>

<p>Return token decimals: 18.</p>

<pre><code>function totalSupply() public view returns (uint256)
</code></pre>

<p>Return total supply of token issues: 60 billion.</p>

<pre><code>function balanceOf(address owner) public view returns (uint256)
</code></pre>

<p>Return the balance of a nominated address <strong>owner</strong>: The parameter is the address owner.</p>

<pre><code>function allowance(address owner, address spender) public view returns (uint256)
</code></pre>

<p>Return the number of the token that the address <strong>owner</strong> allows the address <strong>spender</strong> to use.</p>

<pre><code class="  language- ">function increaseAllowance(address spender, uint256 addedValue) public returns (bool)
</code></pre>

<p>Increase the number of the token that the address <strong>spender</strong> can use (thanks to the address <strong>owner</strong>) .</p>

<pre><code>function decreaseAllowance(address spender, uint256 subtractedValue) public returns (bool)
</code></pre>

<p>Decrease the number of the token that the address <strong>spender</strong> can use (as the address <strong>owner</strong> increases).</p>

<pre><code>function transfer(address to, uint256 value) public returns (bool)
</code></pre>

<p>Forward the token to the address <strong>to</strong>: The parameter is the address to and the number of the token to be forwarded.</p>

<pre><code>function transferFrom(address from, address to, uint256 value) public returns (bool)
</code></pre>

<p>Forward the token from the address <strong>from</strong> to the address <strong>to</strong>. </p>

<pre><code>function batchTransfer(address[] tos, uint256[] values) public returns (bool)
</code></pre>

<p>Forward the token to many <strong>address-tos</strong>: the parameter is the list of many address-tos and the number of the token to be forwarded to each address.</p>

<pre><code>function approve(address spender, uint256 value) public returns (bool)
</code></pre>

<p>Approve to forward the token to the address <strong>spender</strong>.</p>

<pre><code>event Burn(address indexed burner, uint256 value);
</code></pre>

<p>Event <strong>burn token</strong>.</p>

<p>Used when not all tokens are distributed after ICO.</p>

<p><strong>Need to finalize the procedure to burn token: when to start and the conditions to burn?</strong></p>

<pre><code>function burn(uint256 value) public 
</code></pre>

<p>Allow to burn a given number of token of a nominated address owner.</p>

<p>Used when not all tokens are distributed after ICO.</p>

<p><strong>Need to finalize the procedure to burn token: when to start and the conditions to burn?</strong></p>

<pre><code>function burnFrom(address from, uint256 value) public 
</code></pre>

<p>Allow to burn a given number of the token of a nominated address owner: The parameter is the address and the number of token to burn.</p>

<p>Used when not all tokens are distributed after ICO.</p>

<p><strong>Need to finalize the procedure to burn token: when to start and the conditions to burn?</strong></p>

<pre><code>function TokenTimelock(ERC20Basic _token, address _beneficiary, uint64 _releaseTime) public
</code></pre>

<p>Allow to lock a given number of the token of the nominated address with the releaseTime: The parameters are the number of token, the address and the lock time.
Used when it is necessary to lock all tokens of the founder team, development team, etc. within the period of <strong>releaseTime, withdrawing or forwarding token is only approved after this period.</strong></p>

<pre><code>function release() public 
</code></pre>

<p>Allow to unlock the token of the nominated address after the lock time exhausts.
The parameters are the number of token, the address and the lock time.
Used when it is necessary to lock all tokens of the founder team, development team, etc. within the period of <strong>releaseTime, withdrawing or forwarding token is only approved after this period.</strong></p>

<pre><code>function pause() public
</code></pre>

<p>Allow an admin address to pause forwarding the token to other addresses.</p>

<p><strong>The risk is that the admin address may lose its private key.</strong></p>

<pre><code>function resume() public
</code></pre>

<p>Allow an admin address to resume the pause of forwarding the token to other addresses. </p>

<p><strong>The risk is that the admin address may lose its private key.</strong></p>

<h3 id="compiledwithtrufflehttpstruffleframeworkcom">Compiled with <a href="https://truffleframework.com/">Truffle</a></h3>

<h2 id="deploymentonropsten">Deployment on ropsten</h2>

<h3 id="ropstentestnet">Ropsten testnet</h3>

<p>Token contract:</p>

<pre><code>https://ropsten.etherscan.io/token/0xf12f62e5b7e37b883c51190b35d151fce561f12f
</code></pre>

<p>Team's funding lock contract:</p>

<pre><code>https://ropsten.etherscan.io/address/0xf88031112b84d03f1621a39d243015c75659b609
</code></pre>

<p>Advisors' funding lock contract:</p>

<pre><code>https://ropsten.etherscan.io/address/0x2cb9c99fe6472cb60408c72f9db7cac0ccd6d14a
</code></pre>

<h3 id="rinkebytestnet">Rinkeby testnet</h3>

<p>Token contract:</p>

<pre><code>https://rinkeby.etherscan.io/token/0xf12f62e5b7e37b883c51190b35d151fce561f12f
</code></pre>

<p>Team's funding lock contract: </p>

<pre><code>https://rinkeby.etherscan.io/address/0xf88031112b84d03f1621a39d243015c75659b609
</code></pre>

<p>Advisors' funding lock contract:</p>

<pre><code>https://rinkeby.etherscan.io/address/0x2cb9c99fe6472cb60408c72f9db7cac0ccd6d14a
</code></pre>

<h2 id="license">License</h2>

<p>The <a href="https://choosealicense.com/licenses/mit/">MIT</a> License</p>

<p>Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:</p>

<p>The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.</p>
