# TwitchGiftSubHarvester
Bot qui récupère les 1000 plus gros streamers et qui se co à leurs chat via irc pour récolter les sub gifts.

### Résultats avec un crontab de 30mn
![](https://cdn.discordapp.com/attachments/508043568900735013/619432991751405568/unknown.png)

### Commandes
sudo pkill -f TwitchBot/irc_connect.js || echo "Process was not running."
node fetch_users.js
node irc_connect.js &

Thanks to [@rigwild]( https://github.com/rigwild )
