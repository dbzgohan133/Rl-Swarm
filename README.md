# Rl-Swarm
this is for swarm role in gensyn discord



# Install go 
```
sudo rm -rf /usr/local/go
curl -L https://go.dev/dl/go1.22.4.linux-amd64.tar.gz | sudo tar -xzf - -C /usr/local
echo 'export PATH=$PATH:/usr/local/go/bin:$HOME/go/bin' >> $HOME/.bash_profile
echo 'export PATH=$PATH:$(go env GOPATH)/bin' >> $HOME/.bash_profile
source .bash_profile
go version
```
```
go install github.com/Deep-Commit/gswarm/cmd/gswarm@latest
```


# Check version 
```
gswarm --version
```

# Run Swarm 
```
gswarm
```


# Use Telegram bot 
Check out [@BotFather](https://t.me/botfather) to create a bot 

# Use Bot Api 
`
https://api.telegram.org/bot/getUpdates
`

# Next step 
Use bot api token in code 
Use bot Chat id open from above step 
Use You Gensyn Address from [Dashboard](https://dashboard.gensyn.ai/) for more info.

# Last step
-- Get the verification code:
Go to Discord in #|swarm-link channel
Type /link-telegram (this gives you a code)

-- Verify the code:
Go to your Telegram bot
Type /verify <code> (replace <code> with the code you received)
