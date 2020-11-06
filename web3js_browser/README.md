# Web3.js in browser  <!-- omit in toc --> 
([Up](..) [Home](..\..))
Web3.js examples in browser

# HTML and Javascript
  
| Feature                       | Link                  | Github
| ---------                     | -------               | ----------- 
| html framework 1              | [htmlframework1]      | [htmlframework1_gh]
| Version                       | [version]             | [version_gh]
| Metamask inserted             | [metamask_inserted]   | [metamask_inserted_gh]
| get BlockNumber               | [getBlockNumber]      | [getBlockNumber_gh]
| get Accounts 1                | [getAccounts1]        | [getAccounts1_gh]
| get Accounts 2                | [getAccounts2]        | [getAccounts2_gh]
| get Accounts 3                | [getAccounts3]        | [getAccounts3_gh]
| ..............
| html framework 2              | [htmlframework2]      | [htmlframework2_gh]
| send Transaction              | [sendtransaction]     | [sendtransaction_gh]
| Get Set Emit                  | [getsetemit]          | [getsetemit_gh]
| accounts Changed              | [accountsChanged]     | [accountsChanged_gh]
| chain Changed                 | [chainChanged]        | [chainChanged_gh]
| ..............   
| E2E Test Dapp                 | [E2E_Test_Dapp]       | [E2E_Test_Dapp_gh]
| Mini casino: snippet          | [casino_snippet]      | [casino_snippet_gh]
| Mini casino: full version     | [casino]              | [casino1_github]<br>[casino2_github]
| Location snippet              | [location_snippet]    | [location_snippet_gh]
| Log your location (check-in)  | [location]            | [location_github]
| Faucet snippet                | [faucet_snippet]      | [faucet_snippet_gh]
| Faucet                        | [w3e_faucet]          | [w3e_faucet_github]

[location]:          http://web3examples.com/location
[location_github]:   https://github.com/web3examples/location

[casino]:            http://web3examples.com/ethereum/casino/

[casino1_github]:    https://github.com/web3examples/ethereum/tree/master/casino
[casino2_github]:    https://github.com/web3examples/ethereum/blob/master/solidity_examples/Casino.sol

[w3e_faucet]:        http://web3examples.com/ethereum/faucet
[w3e_faucet_github]: https://github.com/web3examples/ethereum/tree/master/faucet

[htmlframework1]:    https://web3examples.com/ethereum/web3js_browser/htmlframework1.html   
[htmlframework2]:    https://web3examples.com/ethereum/web3js_browser/htmlframework2.html   
[version]:           https://web3examples.com/ethereum/web3js_browser/version.html
[metamask_inserted]: https://web3examples.com/ethereum/web3js_browser/metamask_inserted.html
[getBlockNumber]:    https://web3examples.com/ethereum/web3js_browser/getBlockNumber.html
[getAccounts1]:      https://web3examples.com/ethereum/web3js_browser/getaccounts1.html
[getAccounts2]:      https://web3examples.com/ethereum/web3js_browser/getaccounts2.html
[getAccounts3]:      https://web3examples.com/ethereum/web3js_browser/getaccounts3.html
[accountsChanged]:   https://web3examples.com/ethereum/web3js_browser/accountsChanged.html
[chainChanged]:      https://web3examples.com/ethereum/web3js_browser/chainChanged.html
[sendtransaction]:   https://web3examples.com/ethereum/web3js_browser/sendtransaction.html
[E2E_Test_Dapp]:     https://metamask.github.io/test-dapp

[casino_snippet]:    https://web3examples.com/ethereum/web3js_browser/casino_snippet.html
[location_snippet]:  https://web3examples.com/ethereum/web3js_browser/location_snippet.html
[faucet_snippet]:    https://web3examples.com/ethereum/web3js_browser/faucet_snippet.html
[getsetemit]:        https://web3examples.com/ethereum/web3js_browser/getsetemit.html


[htmlframework1_gh]:     https://github.com/web3examples/ethereum/blob/master/web3js_browser/htmlframework1.html
[htmlframework2_gh]:     https://github.com/web3examples/ethereum/blob/master/web3js_browser/htmlframework2.html
[version_gh]:            https://github.com/web3examples/ethereum/blob/master/web3js_browser/version.html
[metamask_inserted_gh]:  https://github.com/web3examples/ethereum/blob/master/web3js_browser/metamask_inserted.html
[getBlockNumber_gh]:     https://github.com/web3examples/ethereum/blob/master/web3js_browser/getBlockNumber.html
[getAccounts1_gh]:       https://github.com/web3examples/ethereum/blob/master/web3js_browser/getaccounts1.html
[getAccounts2_gh]:       https://github.com/web3examples/ethereum/blob/master/web3js_browser/getaccounts2.html
[getAccounts3_gh]:       https://github.com/web3examples/ethereum/blob/master/web3js_browser/getaccounts3.html
[sendtransaction_gh]:    https://github.com/web3examples/ethereum/blob/master/web3js_browser/sendtransaction.html
[accountsChanged_gh]:    https://github.com/web3examples/ethereum/blob/master/web3js_browser/accountsChanged.html
[chainChanged_gh]:       https://github.com/web3examples/ethereum/blob/master/web3js_browser/chainChanged.html
[E2E_Test_Dapp_gh]:      https://github.com/MetaMask/test-dapp/blob/master/src/index.js
[casino_snippet_gh]:     https://github.com/web3examples/ethereum/blob/master/web3js_browser/casino_snippet.html
[location_snippet_gh]:   https://github.com/web3examples/ethereum/blob/master/web3js_browser/location_snippet.html
[faucet_snippet_gh]:     https://github.com/web3examples/ethereum/blob/master/web3js_browser/faucet_snippet.html
[getsetemit_gh]:         https://github.com/web3examples/ethereum/blob/master/web3js_browser/getsetemit.html

# Browserify

Create a browser compatible version of web3.js 1.x
* npm install -g web3
* npm link web3
* npm install -g [pkg_browserify]
* browserify [web3-require.js] -o [web3-browserify.js]

Result is accessible via: [web3examples_web3-browserify.js]

[browserify]:                      https://www.npmjs.com/package/browserify
[web3-require.js]:                 https://github.com/web3examples/ethereum/blob/master/web3js_browser/web3-require.js
[web3-browserify.js]:              https://github.com/web3examples/ethereum/blob/master/web3js_browser/web3-browserify.js
[web3examples_web3-browserify.js]: http://web3examples.com/ethereum/web3js_browser/web3-browserify.js

# SimpleHTTPServer

Use the SimpleHTTPServer in the following way:
* [go-web.cmd]

[go-web.cmd]: https://github.com/web3examples/ethereum/blob/master/web3js_browser/go-web.cmd
