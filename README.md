# Issues-encountered in Task4 and Task 5


## Difficulty in choosing a proper API 
React storefront does not have its own API but instead can be integrated with other API
needed to explore other API as an alternative
pages/api endpoints were not clear in documentation



### configuration issues in unit testing with codecept
npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\user\AppData\Local\npm-cache\_logs\2022-11-05T17_31_54_167Z-debug-0.log
PS D:\codecept> npx codeceptjs run   
SyntaxError: Error parsing D:\codecept\package.json: Unexpected token / in JSON at position 92
    at parse (<anonymous>)
    at readPackage (node:internal/modules/cjs/loader:333:42)
    at readPackageScope (node:internal/modules/cjs/loader:369:19)
    at Module._extensions..js (node:internal/modules/cjs/loader:1169:17)
    at Module.load (node:internal/modules/cjs/loader:1027:32)
    at Module._load (node:internal/modules/cjs/loader:868:12)
    at Module.require (node:internal/modules/cjs/loader:1051:19)
    at require (node:internal/modules/cjs/helpers:103:18)
    at loadConfigFile (D:\codecept\node_modules\codeceptjs\lib\config.js:156:26)
    at Config.load (D:\codecept\node_modules\codeceptjs\lib\config.js:95:16)
    
    
