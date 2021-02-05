# SoundDelayRBLX v1
Roblox module for implementing sound delay into sounds like gunshots and rockets.

### About
Allows you to implement sound delay and have sounds travel the speed of sound to an individual instead of it playing right away regardless of distance. 

(Version v1.0.0)

### Installation
Download the RBXM file and unpack the following components to their respective locations:

* SoundDelayModule -> ServerScriptService
* DelaySoundEvent -> ReplicatedStorage
* SoundDelayClient -> StarterPlayer / StarterCharacterScripts
    
Delete the folder that the previous files were in once it is empty.

### How to use the module
Example of use:
```lua
    local SoundDelayModule = require(game:GetService("ServerScriptStorage):WaitForChild("SoundDelayModule")) -- Require the module 
    local SoundToPlay = workspace.Part.Sound -- Change this to your sound location AND MAKE SURE IT IS INSIDE OF A PART OR THE SCRIPT WILL NOT WORK
    
    SoundDelayModule:PlaySound(Location.Of.Sound) -- Play the sound
 ```
Place the following code up above in a script located in ServerScriptStorage.

### Try it out!
Try out the script and see the delay in action!

### Questions?  Open an issue or contact me on Discord: astro#2588
