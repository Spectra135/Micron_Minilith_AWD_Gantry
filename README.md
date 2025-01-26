[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

# Micron+ AWD Minilith gantry
> [!IMPORTANT]
> All props goes to cloakedwayne, I didn't do anything except adapt the monolith gantry to fit PFA specs.
> 
> Don't expect a step-by-step build guide. Everything is really tight and needs a well tuned printer.
> I won't be updating this gantry nor making a 2WD version. Now that Monolith RC1 is out I wan't to work towards
> something more similar to that

![1](Images/Front_view.png)

## Drive configurations:
there is only an AWD 6mm belt configuration as of now.

## Toolheads
Since this gantry has reversed belts, I kept Monoliths belt spacing for better toolhead support.
Any toolhead with a dedicated monolith MGN9H support should fit on this gantry. 

> [!NOTE]
> **If some things aren't clear, consider joining the Monolith Discord server.**
> **I have a user project in the server
>
> [![Join the Discord](https://discord.com/api/guilds/1227971059764953230/widget.png?style=banner3)](https://discord.gg/JanBKxAzDz)
>
> **If you would like to see more of this and other projects in the future, consider supporting me on Ko-fi.**
>
> [![Join the Discord](https://github.com/CloakedWayne/Monolith_Gantry_V2-VT/blob/main/Images/kofi_short_button_white.png)](https://ko-fi.com/cloakedwayne)

## futur plans
- Update the gantry to RC1 Monolith
- 2WD version
- PFA belt spacing for better fitment (so custom toolhead mounts)
- Fix the hights on the parts.
- Sheet metal version

## Design goals
- The shortest and the simplest belt path possible with AWD compatibility
- The shortest moment arms possible for increased rigidity even when reusing hardware and motion parts
- Double shear steppers and live shaft idlers for higher belt tensions and better reliability
- Good-looking design
- Cheap BOM

## Performance expectations
**2WD:** Due to the 10-15cm shorter belt path, with stiffer and lighter XY-joints the printer should perform similarly to a 50mm smaller one equipped with the same X-axis setup.

**AWD:** It doesn't come at the cost of adding 20cm belt length and idlers, so input shaper scaling can be close to +100% compared to 2WD due to the truly halved effective belt length. But only when no toolhead or frame bottlenecks are limiting its scaling.

**9mm belts:** Wider belts can offer an additional 50% input shaper scaling on top of what's described above.

## What's the catch?
- you have to build a well-balanced system: the increased effective belt stiffness with higher-end gantry configurations will amplify toolhead and frame rigidity issues
- Some toolheads are not yet compatible because of the different belt path
- Z-chain relocation or Z-umbilical is needed on V2
- Trident rear vertical extrusion brackets have to be rotated by 180 degrees or swapped to regular 2020 brackets based on the gantry configuration

## Acknowledgement
I want to thank:

- **ifp, iniqy, krankydonkey, MoneyShot, Nicket, tktktktk, Zakfarias, Scarecrow, The Adeo** for testing and good feedback
- **Sy-Noon** for the awesome logo and feedback on general aesthetics
- **ZaMarin** for FAQ
- **Armchair Heavy Industries** for the exposure and the moderation help I got in their user-project space
- **VoronDesign** for making V2.4 and Trident and for starting me on this journey to improve my FDM design skills
- anyone who helped me along the way

<br/><br/><br/><br/>
This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
