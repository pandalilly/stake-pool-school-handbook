# Get configuration files

Starting the node and connecting it to the testnet requires 4 configuration files:

* topology.json
* BYRON genesis.json
* SHELLEY genesis.json
* config.json

In your home directory, create a new directory for the configuration files:

```text
cd
mkdir relay
cd relay
```

{% hint style="info" %}
You can download the TESTNET configuration files from:

[https://hydra.iohk.io/job/Cardano/cardano-node/cardano-deployment/latest-finished/download/1/index.html](https://hydra.iohk.io/job/Cardano/cardano-node/cardano-deployment/latest-finished/download/1/index.html)
{% endhint %}

Or with the command line using:

```text
wget https://hydra.iohk.io/job/Cardano/cardano-node/cardano-deployment/latest-finished/download/1/testnet-config.json
wget https://hydra.iohk.io/job/Cardano/cardano-node/cardano-deployment/latest-finished/download/1/testnet-shelley-genesis.json
wget https://hydra.iohk.io/job/Cardano/cardano-node/cardano-deployment/latest-finished/download/1/testnet-byron-genesis.json
wget https://hydra.iohk.io/job/Cardano/cardano-node/cardano-deployment/latest-finished/download/1/testnet-topology.json
```

{% hint style="info" %}
[QUESTIONS AND FEEDBACK](https://github.com/carloslodelar/SPO/issues)

If you have any questions or need help, please raise an issue in [Github.](https://github.com/cardano-foundation/stake-pool-school-handbook/issues) We will respond as soon as possible.
{% endhint %}

