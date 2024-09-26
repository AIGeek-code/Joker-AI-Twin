# Joker AI Twin
 
To prevent any errors, Instead of cloning this repository I suggest you download the gaianet node using the following curl command on your linux machine. 
```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```
After successful installation of the node, 
Run the command printed on the terminal to set up the environment path, it is something like `source /<directory>/.zshrc`


After that set the configuration file using the following command. This is the config command used to initialize the node in my repository. My repository has a gigabyte sized file missing since I wanted to upload my project on github. 
This is the configure command which fetches the data from my configuration file. 
```
gaianet init --config https://raw.githubusercontent.com/AIGeek-code/Joker-AI-Twin/main/config.json
```
# After the init command
The init command may take sometime to configure the node based on your machine, after it completes successfully, run the following to start the node. 
```
gaianet start
```
Doing so will start the node on your machine and you should see a link where you will be able to chat and interact with the Joker chat bot. 

# BEWARE IT IS THE JOKER, Answers might not be ACCURATE~@#$
