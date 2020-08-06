# Start your core node

To start your node as the leader candidate you need to add the keys and node certificate to the command that we have used to run the node:

```text
cardano-node run \
--topology shelley_testnet-topology.json \
--database-path /db \
--socket-path /db/node.socket \
--host-addr <PUBLIC IP> \
--port <PORT> \
--config shelley_testnet-config.json \
--shelley-kes-key kes.skey \
--shelley-vrf-key vrf.skey \
--shelley-operational-certificate node.cert
```

{% hint style="info" %}
QUESTIONS AND FEEDBACK

If you have any questions and suggestions while taking the lessons please feel free to ask in the [forum](https://forum.cardano.org/c/english/operators-talk/119) and we will respond as soon as possible.
{% endhint %}

