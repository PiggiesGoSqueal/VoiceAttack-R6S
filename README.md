# VoiceAttack-R6S
 A VoiceAttack profile for Rainbow Six Siege. This profile requires the paid version of VoiceAttack as it uses more than 20 commands.

v0.1.1 on 2/10/2024:
Implemented most base voice commands to play Rainbow Six Siege.

A mouse is preferred but shouldn't be required. For maximum voice command processing speed and mouse control (without using a physical mouse) use Parrot.py on Github instead. 

For support and bug reports please contact me on Discord. My username is "PiggiesGoSqueal" (no ID).

## Improvement Steps:
1. Implement: Using additional weapons (e.g. frag gernades) and using abilities with voice commands.
2. Consider increasing consistency in voice commands. E.g. having multi-commands use "1;2;3" instead of "quick;short;long". Although variety may be good for memory and voice detection for the program. We'll see.
3. Keep the list of voice commands below updated for any new additions.

## Voice Processing Speed
Note some words are shortened in order to make them easier to say quickly in the heat of battle. It also allows the software to process the commands more quickly. E.g. "Stop Sprinting" was shortened to "stint" or "stop". However, if you feel it is still too slow to play the game then it is recommended to use Parrot.py on Github instead (less beginner friendly but quicker at processing).

## Voice Command List
| Voice Input |  Category  | Description |
|:-----|:--------:|------:|
| voiceattack help   | _voiceattack_ | Open the VoiceAttack help PDF |
| [start listening; voice attack wake]   | _voiceattack_ | Wake up VoiceAttack |
| [stop listening; voice attack sleep]   | _voiceattack_ | Put VoiceAttack to sleep |
| arrow [up;down;left;right] | _UI_Interaction_ | Interact with the UI using the arrow keys |
| [click;touch]   | _UI_Interaction_ | Right-click |
| [cancel;escape]   | _UI_Interaction_ | Click escape |
| enter   | _UI_Interaction_ | Press Enter |
| select   | _UI_Interaction_ | Right-click the active button |
| tab   | _UI_Interaction_ | Press tab to move to the next option |
| barricade   | _non_combat_actions_ | Barricade a wall |
| drone   | _non_combat_actions_ | Access your drone |
| scan   | _non_combat_actions_ | Scan for enemies (red ping) |
| [yellow;] ping   | _non_combat_actions_ | Perform a yellow-ping |
| sprint   | _movement_ | Self-explanatory |
| [stop;stint]   | _movement_ | Stop all movement; Stop sprinting |
| stalk   | _movement_ | Stop walking |
| jump   | _movement_ | Self-explanatory |
| climb [up;]   | _movement_ | Self-explanatory |
| [go;walk] [quick;short;long;]   | _movement_ | "go" or "walk" to continuously walk. OR specify the second param for how long to walk. |
| gight [quick;short;long;]   | _movement_ | Go-Right for a quick, short, long, or infinite period of time. |
| geft [quick;short;long;]   | _movement_ | Go-Left for a quick, short, long, or infinite period of time. |
| [gack;back] [quick;short;long;]   | _movement_ | Go-Backwards for a quick, short, long, or infinite period of time. |
| reset   | _misc_ | Release all controls |
| [fire;] [quick;short;long]   | _combat_ | Fire gun for a quick, short, long, or toggled period of time (say "fire" again to stop toggle) |
| [sire;sie] [1;2;3;4;]  | _combat_ | Single-Fire, or Sire/Sie your weapon. The number refers to how many single fires you do. |
| aim   | _combat_ | Aim your weapon |
| staim   | _combat_ | Stop aiming |
| reload   | _combat_ | Reload your gun |
| [look;] right [1;2;3;4;]   | _change_direction_ | Move mouse to look right. 1= 45 degrees, 2 = 90, 3 = 135, 4 = 180, unspecified = 22.5 |
| [look;] left [1;2;3;4;]   | _change_direction_ | Move mouse to look left. |
| [look;] down [1;2;3;4;]   | _change_direction_ | Move mouse to look down. |
| [look;] up [1;2;3;4;]   | _change_direction_ | Move mouse to look up. |
| voice_placeholder   | _category_placeholder_ | Description_placeholder |


Some of the options I went from memory on their controls so I still need to test whether I set the correct controls in v0.1.1 for barricading, droning, etc.