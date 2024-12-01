# Object-Player-Tracking
**Warning: plug-in is currently in BETA phase!**  
  
*Made for Unreal Engine 5.4*  

***Version 1.0***   
  
# Introduction  
The Object/Player Tracking plugin is designed to simplify and streamline the process of enabling an object to follow or target a player or another object in real time within Unreal Engine.  
# How To Set Up  
Once the files have been downloaded, add the plugin to the "Plugins" folder in Unreal Engine project directory.  
You can they go to the your "Actor" blueprint and "Components" window  "Add" and insert **Tracking Components**.  
  
  ![Components](https://github.com/user-attachments/assets/b5989cd0-1890-49f2-a09d-ee27b1e5b885)

**Player Tracking Nodes**  
  
"Begin Track Player Event"  
"End Track Player Event"  
  
  ![Actor Nodes](https://github.com/user-attachments/assets/ec8d67b1-85ca-442d-b365-3346579b2e71)

**Object Tracking Nodes**  
  
"Begin Track Actor Event"  
"End Track Actor Event"  
  
![PlayerNodes](https://github.com/user-attachments/assets/85d8a865-61d5-4795-909d-1182ce618ea9)  

Both tracking methods can be used through any event or method that is required.  

# Ease of use   
  
**Each actor is "Instance Editable" so when you drag your actor into the world you will be give some options.** These are the following:  

***Lock Horizontal Rotation*** - Allows the designer able/disable your actor to follow the select target on different levels  
  
***Looping*** - To give the option to just move to the face the target and not actively track  
  
***Rotation Speed*** - If you want the rotation to have a *delayed* effect   

***Actor*** - **Actor Tracking Only** allows you to select what object with in the world you would like to track  

![Desigenr notes](https://github.com/user-attachments/assets/eebf5c37-c4e2-4829-b879-25f0e5bd4044)  

# Important  

Version 1.0 knowen bugs/issues  

On install you will need to go into the Unreal Directory > "Plugins" > "Player Object Tracking Content" > "Tracking Components" and within Variables > "Tracking" click the "Actor" to be public!  
  
  ![Bug](https://github.com/user-attachments/assets/3f4e32e3-2290-41fe-94e5-78fa81711e71)  
  
Bug the current "Actor Tracking" does not track with in real time but on on first call. "Player Tracking" works as intended.  

If there are any issues feel free to contact me through C2464767@tees.live.ac.uk
