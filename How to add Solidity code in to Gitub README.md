## Example

A "Hello World" program in Solidity is of even less use than in other languages, but still:

" ```solidity 
add Code Here

``` "

```solidity
// SPDX-License-Identifier: MIT
pragma solidity >=0.6.0 <0.9.0;

contract HelloWorld {
    function helloWorld() external pure returns (string memory) {
        return "Hello, World!";
    }
}
```
