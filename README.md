# ShaguScore

The original version of ShagoScore shows a score which is not very straightforward to understand. I changed the score to item level to make it clear.

![character](https://github.com/fhh2626/ShaguScore-Itemlevel/blob/master/character.png)

## Installation
1. Download the master branch
2. Unpack the Zip file
3. Rename the folder "ShaguScore-master" to "ShaguScore"
4. Copy "ShaguScore" into Wow-Directory\Interface\AddOns
5. Restart Wow

## Older Versions

In older versions this addon did two things, it calculated the average color (rarity) of the player's equip and it aggregated a score of the overall equip.

The score value has been calculated as followed:

    Score = Rarity * ItemLevel * Bonus

**Rarity:**
<span style="color: #9d9d9d">Poor (0)</span>,
<span style="color: #000000">Common (1)</span>,
<span style="color: #1eff00">Uncommon (2)</span>,
<span style="color: #0080ff">Rare (3)</span>,
<span style="color: #b048f8">Epic (4)</span>,
<span style="color: #ff8000">Legendary (5)</span>,
<span style="color: #e6cc80">Artifact (6)</span>

**Bonus:** 
The Bonus is 2 when a TwoHand weapon is used, otherwise it will be 1
