# Valheim
Tools and utils for Valheim

## Quaalude Inmersive
> Dedicated Server  
> smurfgames.duckdns.org:2456  
> Version 1.0.3

### Required Modpack
https://thunderstore.io/c/valheim/p/Smurfgames/QuaaludeInmersiveModPack/

### r2modman Profile Code
`019b135a-3ae8-bff4-7b0e-ba2798ee3a41`

### Launcher (Windows batch)
```
@echo off
"C:\Program Files (x86)\Steam\steam.exe" ^
  -applaunch 892970 +connect smurfgames.duckdns.org:2456 -password [YOUR_PASSWD]^
  --doorstop-enabled true ^
  --doorstop-target-assembly "C:\Users\[YOUR_USER]\AppData\Roaming\r2modmanPlus-local\Valheim\profiles\[YOUR_PROFILE]\BepInEx\core\BepInEx.Preloader.dll"
```

