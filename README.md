# [ChainOrchestra-SDK](https://github.com/ChainOrchestra/ChainOrchestra-SDK)

This SDK provides tools and APIs to access the ChainOrchestra blockchains based on 
[Hyperledger v0.6](http://hyperledger-fabric.readthedocs.io/en/v0.6/API/CoreAPI.html)

The software in this repository is distributed in open-source under the 
[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)


## ChainOrchestra simplified Hyperledger REST client [API](https://chainorchestra.github.io/ChainOrchestra-SDK/index.html)

### API documentation

The [chainorchestra.js API](https://chainorchestra.github.io/ChainOrchestra-SDK/index.html) defines 
a basic set of objects to handle Hyperledger peer interactions over the REST API.

### Web app

Just include the [chainorchestra.js](https://chainorchestra.github.io/ChainOrchestra-SDK/chainorchestra.js.html) lib in a web page
to connect to Hyperledger using the REST API.

```
<script src="chainorchestra.js"></script>
```

The following live examples from the [registration](http://chainorchestra.net/#/4) application on 
[chainorchestra.net](http://chainorchestra.net) use the chainorchestra.js objects to:

  * [Connect](http://chainorchestra.net/ChainOrchestra-SDK/sampleConnection.html) a user to the blockchain.
  * [Query](http://chainorchestra.net/ChainOrchestra-SDK/sampleQuery.html) the blockchain.
  * Execute a [transaction](http://chainorchestra.net/ChainOrchestra-SDK/sampleTransaction.html) on the blockchain.

### Node.js

Install the [chainorchestra.js lib as a Node.js package](lib/js/) to run scripts and use it as a command line app.

## Blockchain demos

  * Live demo blockchain on [chainorchestra.net](http://chainorchestra.net)
  * Guest [registration](http://chainorchestra.net/#/4) application
  * Value [exchange](http://chainorchestra.net/#/5) application


## About ChainOrchestra

[ChainOrchestra](http://chainorchestra.com) conceives and develops demonstrators, 
proof-of-concept and pilots on its own permissioned blockchains.

