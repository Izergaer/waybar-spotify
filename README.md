Tested building on Zig version 0.16.0-dev.229+bfda12efc

# How to build
```
git clone https://github.com/Izergaer/waybar-spotify.git
cd waybar-spotify
zig build
```

# Styling
Styles available:
- .playing
- .paused

# Example config
```
"custom/spotify": {
    "format": "{}",
    "exec": "path-to-the-executable",
    "return-type": "json",
    "escape": true,
}
```

