# Verus ccminer install commands
<br>
Check the instruction on how to use it on [YouTube](https://www.youtube.com/@bloxylabs "YouTube").
<br>
If you had fun with the projects, please consider giving us a Super Thanks on YouTube or buying us a [cup of coffee](https://www.buymeacoffee.com/bloxylabs "cupofcoffee").
<br>

<h3><u>The commands to install CCMiner</u></h3>

Command to update and upgrade your OS:

```
sudo apt update
```

```
sudo apt upgrade
```

Command to install the arm-optimized ccminer from the Great Oink70:

```
curl -o- -k https://raw.githubusercontent.com/Oink70/Android-Mining/main/install.sh | bash
```

Command to go to ccminer directory:

```
cd ccminer
```

Command to configure ccminer:

```
nano config.json 
```

Command to start the miner:

```
~/ccminer/start.sh
```

Command to connect to screen session:

```
screen -r
```

Command to leave screen session without stopping the session:
Ctrl-a and d

Commands for automatic startup:

```
crontab -e
```

Insert the following at the end of the file:

```
@reboot ~/ccminer/start.sh
```

Have fun!
