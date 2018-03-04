# Code your own Proof of Work algorithm!

[Read](https://medium.com/@mycoralhealth/code-your-own-blockchain-mining-algorithm-in-go-82c6a71aba1f) our blog post first to see a walkthrough of the code.

### Ask us anything!

Join our [Telegram](https://t.me/joinchat/FX6A7UThIZ1WOUNirDS_Ew) chat and follow us on [Twitter](https://twitter.com/myCoralHealth)!

### Deployment steps:
- clone this repo
- navigate to this directory and rename the example file `mv example.env .env`
- `go run main.go`
- open a web browser and visit `http://localhost:8080/`
- to write new blocks, send a `POST` request (I like to use [Postman](https://www.getpostman.com/apps)) to `http://localhost:8080/` with a JSON payload with `BPM` as the key and an integer as the value. For example:
```
{"BPM":50}
```
- **watch your Terminal to see Proof of Work in action!**

### Screenshot

![screen](https://user-images.githubusercontent.com/15616604/36948221-7ce7f9c0-1f8c-11e8-9d1b-0769233a6abc.png)
