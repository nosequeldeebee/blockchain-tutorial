# Code your own blockchain in less than 200 lines of Go!

### Tutorial

[Read](https://medium.com/@mycoralhealth/code-your-own-blockchain-in-less-than-200-lines-of-go-e296282bcffc) our blog post first to see a walkthrough of the code.

#### Check out our follow-up tutorials:
- [Networking](https://github.com/mycoralhealth/blockchain-tutorial/tree/master/networking)
- [Proof of Work](https://github.com/mycoralhealth/blockchain-tutorial/tree/master/proof-work)
- [Proof of Stake](https://github.com/mycoralhealth/blockchain-tutorial/tree/master/proof-stake)
- [IPFS](https://medium.com/@mycoralhealth/learn-to-securely-share-files-on-the-blockchain-with-ipfs-219ee47df54c)
- [P2P](https://medium.com/coinmonks/code-a-simple-p2p-blockchain-in-go-46662601f417)
- [Advanced Concepts for Beginners](https://medium.com/@mycoralhealth/advanced-blockchain-concepts-for-beginners-32887202afad)
- [Start your own Hyperledger blockchain the Easy Way!](https://medium.com/@mycoralhealth/start-your-own-hyperledger-blockchain-the-easy-way-5758cb4ed2d1)
- [Build a DApp on Hyperledger the Easy Way!](https://medium.com/@mycoralhealth/build-a-dapp-on-hyperledger-the-easy-way-178c39e503fa)
- [Build your own Blockchain Twitter recorder](https://github.com/mycoralhealth/twitter-blockchain)

### Deployment steps:
- `git clone https://github.com/mycoralhealth/blockchain-tutorial.git`
- navigate to this directory and rename the example file `mv example.env .env`
- `go run main.go`
- open a web browser and visit `http://localhost:8080/`
- to write new blocks, send a `POST` request (I like to use [Postman](https://www.getpostman.com/apps)) to `http://localhost:8080/` with a JSON payload with `BPM` as the key and an integer as the value. For example:
```
{"BPM":50}
```
- Send as many requests as you like and refresh your browser to see your blocks grow! Use your actual heart rate (Beats Per Minute) to track it over time.

### Screenshot

![screen](https://user-images.githubusercontent.com/15616604/35492333-2829f690-0461-11e8-8c1f-8a0258d370e8.png)


