# Annihilated Cheat Table

A Cheat Engine table for Annihilated.

> Designed for offline, single-player use only. Use at your own risk. Back up your save files before using this table.

Download **[Annihilated-Stats-Editor.CT](Annihilated-Stats-Editor.CT)**. Only this CT file is needed; all scripts are included. The editor interface is in English.

## Features

- Edit player, partner and enemy HP, including maximum HP.
- Edit player and partner sanity.
- Edit curse.
- Restore full player HP or undo the last edit.
- Automatically find game addresses when connecting.

## How to use

1. Start Annihilated and load a save.
2. Open the CT in a standard **64-bit Cheat Engine** installation (with built-in Mono/IL2CPP support) and allow its Lua script to run when prompted.
3. Click **1. Connect** in the editor window.
4. Select a field, enter a whole number and click **2. Apply**.
5. If a write is waiting, switch back to the game window.
6. Click **Disconnect** when finished. Edited values are not automatically undone.

Use **Rescan** to refresh the fields after loading a different save. Edits are not permanent freezes, and the game can change values during play.

The table finds addresses automatically instead of requiring a preset game version. Some internal game changes may still require an updated table; it will stop if its compatibility checks fail.
