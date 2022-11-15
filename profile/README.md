## Hi there 👋

🙋‍♀️ Sub.Net Sdk will provide tools to create a subnet easily.

It contains everything needed to create a custom avalanche subnet VM. It implements the grpc protos required, and it is compatible with metamask (custom handlers).

Subdotnet-cli helps during the development process. is a wrapper around avalanche-network-runner (which itself is a wrapper around avalanchego). It builds your sub.net project, starts a local network of 4 nodes, creates a subnet on the local nodes, registers your custom vm and calls the nodes to register an alias to your vm.

When running the cli, you will be able to configure metamask with this url http://127.0.0.1:9650/ext/bc/subnetalias.

_I started this project with almost zero blockchain knowledge. A complete rewrite will be done in the next few weeks and some repos might be deleted._

[![Demo](https://user-images.githubusercontent.com/1549198/201880624-55b7bd3f-46cc-40d8-8466-156e993b26a2.png)](https://www.youtube.com/watch?v=_apEEeuivsM "Subdotnet demo - Click to Watch!")
