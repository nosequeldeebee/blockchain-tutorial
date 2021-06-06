# Peer 2 Peer Blockchain Tutorial

### Tutorial
[Read](https://medium.com/@mycoralhealth/code-a-simple-p2p-blockchain-in-go-46662601f417) the blog post for this tutorial first!

### Ask us anything!

Join our [Telegram](https://t.me/joinchat/FX6A7UThIZ1WOUNirDS_Ew) community and follow us on [Twitter](https://twitter.com/myCoralHealth)!

### Deployment steps:
- clone this repo
- navigate to this directory
- `go run main.go -l 10000 -secio`
- open a new terminal window
- follow the instructions in your 1st terminal and copy and paste the given command into your 2nd terminal e.g. `go run main.go -l 10001 -d /ip4/127.0.0.1/tcp/10000/ipfs/QmZ8NayvdXc2U2A1cwh9qGaHK7uxXXVrZQEYwDqbfFydfj -secio`
- open a new terminal window
- follow the instructions in your 2nd terminal and copy and paste the given command into your 3rd terminal e.g. `go run main.go -l 10002 -d /ip4/127.0.0.1/tcp/10001/ipfs/QmRAj9JJVKRJmWHbDKzvzKDVVFPWxuWYio3bPym4SgGPgF -secio`
- type a BPM into any of your terminals and watch your blockchain be broadcast to all terminals!


