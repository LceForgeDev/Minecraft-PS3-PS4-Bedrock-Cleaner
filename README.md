# Bedrock Purge
Tool to remove bedrock and clear terrain from Minecraft Legacy saves.

## Features
- Remove Bedrock (ID 7).
- Clear all blocks below a custom Y-level.
- Creates an 8x8 stone spawn platform.
- Supports chunk formats V8-V13 (TU12-TU69).
- Works with Large worlds.

## Important Note
The tool only modifies chunks that already exist in the save file. 
Chunks that were never generated/loaded in-game will not be affected.

## Usage
1. Decrypt save using LegacyEditor (RPCS3 format).
2. Drag & drop GAMEDATA into the tool.
3. Get cleaned file from the "Out" folder.
4. Convert back via LegacyEditor.

Download the `.exe` in Releases.
