Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a poc[![Build Status](https://dev.azure.com/jiheneboukaddidaMPWNI/Integrating%20External%20Source%20Control%20with%20Azure%20Pipeline/_apis/build/status/jajjaf.calculator?branchName=refs%2Fpull%2F2%2Fmerge)](https://dev.azure.com/jiheneboukaddidaMPWNI/Integrating%20External%20Source%20Control%20with%20Azure%20Pipeline/_build/latest?definitionId=1&branchName=refs%2Fpull%2F2%2Fmerge)ket calculator.

The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.
[![Build Status](https://dev.azure.com/jiheneboukaddida/ntegrating%20External%20Source%20Control%20with%20Azure%20Pipelines%20Lab%206/_apis/build/status/jajjaf.calculator?branchName=master)](https://dev.azure.com/jiheneboukaddida/ntegrating%20External%20Source%20Control%20with%20Azure%20Pipelines%20Lab%206/_build/latest?definitionId=26&branchName=master)
