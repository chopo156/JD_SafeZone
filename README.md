# JD_SafeZone
<h4 align="center">
	<a href="#download--installation">Download & Installation</a>
	|
	<a href="https://docs.jokedevil.com/JD_logs">Documentation</a>
</h4>
<h4 align="center">
	<a href="https://github.com/JokeDevil/JD_SafeZone/releases/latest" title=""><img alt="Release" src="https://img.shields.io/github/v/release/JokeDevil/JD_SafeZone"></a>
	<a href="LICENSE" title=""><img alt="Licence" src="https://img.shields.io/github/license/JokeDevil/JD_SafeZone.svg"></a>
	<a href="https://discord.gg/m4BvmkG" title=""><img alt="Discord Status" src="https://discordapp.com/api/guilds/721339695199682611/widget.png"></a>
</h4>
<h4 align="center">
 Safezone for FiveM (A place where you can't kill anyone and can't be killed)
</h4>

### Requirements
- A Discord Server
- FiveM FXServer
- pNotify (Optional)

# Download & Installation

1. Download the files
2. Put the JD_SafeZone folder in the server resource directory
3. Add this to your `server.cfg`:
```
ensure JD_SafeZone
```

# Adding more Zones
```
Config.Zone = {
	["Sandy PD"] = {
    x = 1835.73,
    y = 3676.72,
    z = 39.89,
    radius = 50.0
    },
	["Mission Row"] = {
    x = 446.8,
    y = -993.06,
    z = 29.26,
    radius = 40.0
    },
	["Medical Center"] = {
    x = 311.62,
    y = -1443.69,
    z = 29.8,
    radius = 50.0
    },
  ["YOUR_NEW_ZONE_NAME"], = {
    x = YOUR_NEW_ZONE_X,
    y = YOUR_NEW_ZONE_Y,
    z = YOUR_NEW_ZONE_Z,
    radius = YOUR_NEW_ZONE_RADIUS -- This is how big you want the zone to be.
  },
}
```
### My Discord: https://discord.gg/m4BvmkG
