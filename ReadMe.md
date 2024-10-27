# Minecraft-Bedrock-Server-GUI

A control dashboard to monitor and control your minecraft bedrock dedicated server through an easy user interface.  Created by Nathan-Busse  13 January 2022.  Made with Python 3.8

# Currently only works for Windows 10 & 11


![Screenshot (5)](https://user-images.githubusercontent.com/82398683/153929326-7b7d4485-2623-4391-a653-917027dc03e5.png)


# Note!

This only works for Bedrock.

# Installation.


# Step 1:
Open the ```Command prompt``` and type:
```cd Documents```

 Then clone the repository.
``` git clone https://github.com/Nathan-Busse/Minecraft-Bedrock-Server-Control-Panel-GUI.git ```

 # Step 2:
 
 Extract the cloned repository.
 
 # Step 3:
 
 Once the cloned Repository is extracted move the folder ```My Bedrock Server``` to ```Documents``` and open it.

# Step 4:

Inside the folder ```MCBE Server``` open the ```MCBE Control Panel``` folder and under ```Scripts``` run the ```install.py``` script.

It will install all the package requirements automatically and create a folder called ```Server``` where the downloaded Bedrock Dedicated Server will be located.

It will automatically close the script.

# Step 5:

Download the server from the official Minecraft website: https://minecraft.net/download/server/bedrock

# Step 6:

Move the ```bedrock-server-1.19.31.01.zip``` folder to the created folder called ```Server``` and extract it. (Latest version in the making of this ReadMe.)

You can delete the zip file once everything is extracted.

Here is a tutorial to help you with port forwarding and setting up a Dynamic IP using a free and extremely reliable service called Dynu.

https://youtu.be/aiSla-5xq3w

# Step 7:

Inside the ```MCBE Control Panel``` folder under ```Scripts```:

Run ```MCBE Control Panel.pyw```.

# Step 8

A firewall pop-up will appear.
Make sure that both ```private``` and ```public``` networks are selected then click ```Allow```.

Your Server should start automatically.

# How to use the server updater feature

The ```Update``` Updates the Server to the latest version. 

Here are the steps to install the update.

# Step 1

Click ```Update```. Then click ```Update Server```. Make sure that the Server is not running.

When completed a message will say ```Download completed```.

# Step 2

Close ```MCBE Control Panel.pyw```.

# step 4

In the ```MCBE Control Panel``` folder you will see a new zip folder.
Open the zip folder without extracting and move the ```bedrock_server.exe``` folder to ```MCBE Server```.

A message box will a appear saying that the file already exists.
Click ```Replace file in the destination```.

# step 5 

You are done. 
You can delete the zip folder if you want.

Now you can launch the ```MCBE Control Panel.pyw```. 


# Server features continued

The ```Server Console``` Displays the inputs and outputs and other useful information of the server. 

The ```File``` button gives additional functions such as ```View folder directory```,  ```exit``` and ```force exit``` the script.


The ```Start Server``` button Starts the server.

The ```Backup World``` button Creates a copy of your world which can be executed even while your world is still running meaning you don't have to shut the server down.
How it works is that it pauses the world save temporarily which means that no world correction. The players are still able to play but while it is backing the world up it does not save any changes made.
Once backup is complete world save will be resumed and changes made during the back up and after will be saved.

The ```Players``` Lists the players connected to the server.

The ```Interact``` Send in-game commands through the control panel.

The ```Send Host Command``` Used to send console commands or in-game commands.

The ```SEND``` button Sends the command to the console.

Type ```stop``` in the ```Send Command``` tab and click ```SEND``` to shutdown the server or close the programme completely.

The server has shutdown successfuly when this message is displayed:

```
Quit correctly

```
# What I plan to add to the GUI

~~```Patch the update bug```~~

~~```Patch window centre bug```~~

~~```Add a SplashScreen```~~

~~```Add an anti-sleep system```~~

```Add a performance monitor```

```Auto Rollback```

```Auto restart and shutdown```

```Auto backup everytime the sever is updated to the latest version```

```Access sever.properties through the console```

```Access whitelist.json through the console```

```Access permissions.json through the console```

```Add a stop button```

```Add a configuration menu```

```Add an auto world backup at set times bt the user in configuration menu```


Enjoy! 😉



