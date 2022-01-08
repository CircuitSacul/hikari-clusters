# hikari-clusters
Clustering for hikari made easy. Run examples with `python -m examples.<example name>` (`python -m examples.basic`)

![Image](https://us-east-1.tixte.net/uploads/circuit.is-from.space/clustered-bot-structure.jpg)

## Creating Self-Signed Certificate:
```
openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout cert.key -out cert.cert && cat cert.key cert.cert > cert.pem
```
