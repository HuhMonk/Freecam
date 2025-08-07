# Freecam
a unity freecam with alot of options like orion drift made by HuhMonke
make sure you downloaded [MoonSharp](https://github.com/moonsharp-devs/moonsharp)

# Documentation

## how to add lua scripts

YourGame_DATA/
----StreamingAssets/
-------Lua/
----------MyScript.lua


## Heres all the functions

add waypoint at position using x y z
```lua
Freecam:AddWaypointFromLua(x, y, z)
```

add unity components
```lua
allowed
        "UnityEngine.Light",
        "UnityEngine.AudioSource",
        "UnityEngine.BoxCollider",
        "UnityEngine.SphereCollider",
        "UnityEngine.MeshCollider"

Freecam:AddComponentFromLua("UnityEngine.Light")
```
Set camera fov
```lua
Freecam:SetCameraFovFromLua(75)
```
Set movement speed
```lua
Freecam:SetMovementSpeedFromLua(12
```
teleport camera to position using x y z
```lua
Freecam:TeleportToFromLua(x, y, z)
```
Follow player by name
```lua
Freecam:FollowPlayerByNameFromLua("Player456")
```
Clear waypoints
```lua
Freecam:ClearWaypointsFromLua()
```
play path
```lua
Freecam:PlayPathFromLua()
```
set path speed
```lua
Freecam:SetPathSpeedFromLua(8)
```
set mouse sens
```lua
Freecam:SetSensitivityFromLua(1.5)
```
save waypoints
```lua
Freecam:SaveWaypointsToFileFromLua("waypoints.txt")
```
load waypoints
```lua
Freecam:LoadWaypointsFromFile("waypoints.txt")
```
take screenshot
```lua
Freecam:TakeScreenshot("screenshot1.png")
```
