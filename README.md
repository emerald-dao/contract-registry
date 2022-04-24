# Flow Contract Registry

A list of contracts and their addresses. 

# Adding a New Contract
If you'd like to add your own contract, make a new Pull Request by adding to the `contracts` object in the `flow.json` file in this format:

```javascript
[contract name] {
  "source": "",
  "aliases": {
    "testnet": "",
    "mainnet": ""
  }
}
```