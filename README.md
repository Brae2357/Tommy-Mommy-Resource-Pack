# Tommy Mommy Resource Pack
The Tommy Mommy server resource pack for adding custom models and things.
## Overview
The Tommy Mommy Resource Pack repository allows you to add custom textures and models into the realm without needing a datapack. By uploading a model, it will automatically compile the resource pack for everyone to use, just by clicking update on the TM Resource Pack Updater.
## Setting up the resource pack
1. Download the TMRPUpdater.exe
2. Run the executable
3. Click the update button
4. Open Minecraft -> Options -> Resource Packs -> enable Tommy Mommy Resource Pack
5. Whenever someone adds to the pack, launch the updater and click update (F3 + t reloads resources in game)
## How to upload models
1. Become a collaborater (talk to Braeden)
2. Create a model and texture (I recommend using BlockBench, more details below)
3. Upload your model file to `/models/` and texture file to `/textures/`
## How to use BlockBench
Download BlockBench at https://www.blockbench.net/
### How to create a model
Under the `Minecraft` category, select `Java Block/Item`.  
IMPORTANT: Make sure the name only has lower case letters, digits, or underscores.  
On the right panel, click the `Add Cube` button. You can model this by using the toolbar at the top, or the hotkeys:  
- v -> move
- r -> rotate
- s -> scale      
You can set temporary colors before texturing by right clicking on a cube and selecting `Marker Color`.  
I highly recommend finishing the model before you begin to texture,  
### How to texture your model
Once you have your model created, select all your cubes and click the `Create Texture` button.  
Now the texture file is created, click `Paint` in the top right to color your model.  
### How to test your model  
After you finish texturing, go to the `Display` tab in the top right.  
Under the slot category, you can preview it in different forms. I recommend looking through all the categories because they are all important. You can move the model around the player and rotate it however you would like.  
NOTE: You can test it on certain players by going to File -> Preferences -> Settings -> Preview -> Minecraft Skin  
### How to upload your model
You need two files: model (json) and texture (png)  
To get your model file, go to File -> Export -> Export Block/Item Model  
To get your texture, go to the `Edit` tab, right click on your texture (left panel) -> Save As (Make sure it matches your project name)  
Add your model file to `/models/` and your texture file to `/textures/`  
Once both are added, run the updater and reload your resources in Minecraft. To get your model, rename a pumpkin to your model name (EX: my_model if your files were my_model.json and my_model.png)  
