# Contributing

## Documentation

On every update be sure to:
- Test your changes using the example files in a Minecraft world
- Update History.md
  - On small updates, add description to the current version
  - On large updates, increment version number
- Update README.md
  - On large updates, increment version number
  - Add any extra functionality added to uses
  - Remove any fixed bugs, add any new bugs
  - Remove any added feature requests
- Make a descriptive PR name and use the longer description if needed


## General Project Structure
```
.
├── src/main
│   ├── java/me/melonboy10/midi2building
│   │   ├── conversion (code to convert midi to usable data)
│   │   ├── screenElements (gui code)
│   │   ├── util (extra utilities)
│   │   └── Main.java
│   └── resources
│       ├── defualtSongs (default files for testing and demoing)
│       │   ├── defaultMidi (default midi files)
│       │   └── defaultStructure (default structure files)
│       └── gui (images and font files for the gui)
├── README.md
└── Contributing.md
```