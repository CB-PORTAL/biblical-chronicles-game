# 🎮 1 GAME PROJECT

## Purpose
The beating heart of Biblical Chronicles - your complete Unity project workspace

## What Goes Here
- The entire Unity project created through Unity Hub
- All C# gameplay scripts (PlayerMovement.cs, DialogueSystem.cs, etc.)
- Unity scene files (.unity) for each Biblical chapter
- Prefabs for reusable game objects
- Unity packages and dependencies
- Project settings and configurations

## Folder Structure Inside
```
1 game project\
├── Assets\
│   ├── Scripts\        (All your C# code)
│   ├── Prefabs\        (Reusable game objects)
│   ├── Scenes\         (Garden of Eden, Noah's Ark, etc.)
│   ├── Materials\      (Visual effects, shaders)
│   └── Imported\       (Sprites/sounds Unity copies here)
├── ProjectSettings\    (Unity configuration)
└── Packages\          (Unity package manager)
```

## Use Cases
- Opening Unity Hub points here to load your project
- VS Code opens Scripts folder for coding
- Build your game executables from here
- Version control (Git) tracks this entire folder
- This is where the ACTUAL GAME exists

## Important Notes
- **NEVER** manually move files inside Assets - use Unity
- **ALWAYS** backup before major changes
- **KEEP** scenes organized by Biblical book
- **NAME** scripts clearly: `NoahArkBuilder.cs` not `Script1.cs`

## Quick Commands
```bash
# Open in Unity Hub
unity-hub://1 game project

# Build for Windows
File → Build Settings → PC, Mac & Linux Standalone → Build
```