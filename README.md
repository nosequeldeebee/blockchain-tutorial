# Code your own blockchain in less than 200 lines of Go!

### Tutorial

[Read](https://medium.com/@mycoralhealth/code-your-own-blockchain-in-less-than-200-lines-of-go-e296282bcffc) our blog post first to see a walkthrough of the code.

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

### Questions? Comments?

Join our [Telegram](https://t.me/joinchat/FX6A7UThIZ1WOUNirDS_Ew) chat and follow us on [Twitter](https://twitter.com/myCoralHealth)!
