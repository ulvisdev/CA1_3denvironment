# Cozy Monastery

A cozy monastery in a calm nighttime setting, made in Unreal Engine 5.8 using Blueprints.
Explore the inner garden, monastery and upper floor.

## What's included

- Interactable doors and lanterns.
- Smooth door animations and lantern brightness changes.
- Cyan outlines and interaction prompts.
- Ragdoll when falling 3.5 metres, with R to get back up.
- Custom splash screen and game icon.

## Open the project

- Install Unreal Engine 5.8. No extra plugins needed.
- Clone/download the repository and extract it if needed.
- Open `CA1_Environment.uproject`.
- Wait for shaders to compile, then press Play.
- `Lvl_FirstPerson` should open automatically.

## Build it

- Open the project and save everything.
- In Project Settings > Packaging, use the Shipping configuration.
- From the Platforms menu, select Windows and Package Project.
- Choose an output folder and wait for packaging to finish.

## Play the packaged game

- Download it here: `https://ulvis.itch.io/cozy-monastery`
- Extract the whole ZIP.
- Open the Windows folder and run `CA1_Environment.exe`.
- Keep all the included files and folders together.

## Controls

- WASD - move
- Mouse - look
- Space - jump
- E - interact
- R - get up from ragdoll
- Alt + F4 - close the game

## Where things are

- `BP_SimpleDoor` - doors, outlines and interaction.
- `BP_SimpleLantern` - lanterns and brightness function.
- `BP_FirstPersonCharacter` - movement, ragdoll and recovery.
- `M_InteractOutline` - cyan outline effect.
- `WBP_InteractPrompt` / `WBP_RagdollPrompt` - UI prompts.

## Known issues

- Falling right beside a wall can leave too little room to stand up,
  sometimes requiring a restart.
- Sometimes the camera can still be moved around during ragdoll.

## Credits

Assets and sounds are listed in `CREDITS.txt`.