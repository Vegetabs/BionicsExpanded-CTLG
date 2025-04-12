# Bionics Expanded
*Bionics Expanded* (BE) is a content mod for *Cataclysm: The Last Generation* (CTLG), consisting of bionics which I just thought would be fun to create. 

## Content
The current implemented bionics include:
- Chemical Synthesis CBM
- Dragon's Breath CBM
- Variable Dispersion Arrays CBM

## Installation Instructions
1. Download the src code in the latest mod release
2. Unzip the file in the 'data\mods' directory

## Known Issues
1. User input prompt for the bionics has a bunch of prewritten integers. Really annoying to deal with and caused by the current EOC infrastructure of TLG; don't worry, I've already created a TLG GitHub issue about it, and hopefully it should be solved soon. For now, hold backspace or delete until you've cleared the input field, then write your actual input.
2. Spells cast through the enchantment 'intermittent_activation' feature sometimes activate at irregular times. I'm pretty sure this one isn't my fault, but it ultimately isn't ***that*** impactful to regular gameplay if you don't know the intended synthesis times.

## FAQ
- **Q1**: I'm trying to use the Dragon's Breath/VDA bionics, and it's saying, "Gas reserves are too low!" What do I do?
    - **A1**: All gas-based bionics require the ***Chemical Synthesizer*** bionic to function, as they utilise gas reserves within the user to function.
- **Q2**: Why is my character's health is extremely low after synthesizing chemicals?
    - **A2**: Synthesizing chemicals is not free! It takes time and bionic power and reduces the user's health to simulate the bionic taking resources from the user's body.
- **Q3**: I've been blinded after turning on the VDA?!
    - **A3**: The VDA indiscriminately disperses chemicals into the surrounding area; this also includes ***your*** tile. To prevent being affected by your dispersed chemicals, consider using a gas mask or the 'air filtration' and 'protective lenses' bionics.
- **Q4**: Why did [insert bionic] not do anything when I activated it?
    - **A4**: This could be a range of things, such as not having sufficient bionic power, sufficient gas reserves, or the bionic's behavior changing due to a previous action. If you're using the VDA or Chemical Synthesizer, the bionic will behave differently if you have a current order active, so make sure to check the message log to see if it's canceling your current order. If none of these apply, please create a GitHub issue or notify me directly.

## Found a Bug?
If you find a bug/crash which you believe may be caused by this mod, make sure to either:
- Create a GitHub issue
- DM me directly or ping me on the TLG server

## Confused About a Mod Feature?
Any questions you might have can be directed at me through DM-ing or pinging me through discord. I'll (probably) respond in a timely manner if I'm not sleeping or otherwise busy.