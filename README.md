# hardhat-Yul
Needing compile Yul and Yul+, I thought I'd integrate my current scripts into a hardhat plugin. Loosely based off the Vyper plugin this one includes none of the safety checks, tests, or safety. It also forces js in some parts because the Yul+ compiler is javascript, and the abi part does have to tell Typescript to ignore typing. Will fix at a later date though!
