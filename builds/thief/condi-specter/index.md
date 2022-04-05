---
title: Condi Specter
hidden: false
rating: Good
role: Condi Damage
profession: Thief
specialization: Specter
skills: null
conditions:
  - Vulnerability
  - Weakness
  - Immobilize
  - Poisoned
  - Bleeding
  - Torment
boons: null
cmGuide: ""
classification:
  - 5
  - 4
  - 3
  - 2
  - 3
compositions: null
code: "[&DQUcGywfRxcMAQAACwEAAC8BAAA+AQAADgEAAAAAAAAAAAAAAAAAAAAAAAA=]"
date: 2022-03-20T17:44:08.565Z
---

<Warning>

This build guide is not complete, gear and sections may change regularly as we explore the new elite spec and spend more time playing it in fractals!

</Warning>

The **<Specialization text="Condi Specter" name="Specter"/>** is a high DPS condition build with great team support options. The value of this build comes from the pure damage that it will bring, which is inflated by the **<Specialization text="Condi Soulbeast" name="Soulbeast"/>**'s <Skill id="40498"/>, on top of Venom Skills which can be precast on the _Mistlock Singularity_, and casted again as soon as your allies have consumed them by attacking the target.

At the same time it can generate large amounts of <Effect name="Barrier"/> for your party, some healing and a small amount of <Boon name="Might"/> and <Boon name="Swiftness"/> by targeting allied players.

<Divider text="Equipment"/>

<CharacterWithAr>  
<Character title="162 Agony Resistance" gear={{
  "profession": "Thief",
  "weight": "medium",
  "gear": [
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Viper",
    "Sinister",
    "Viper",
    "Sinister",
    "Sinister",
    "Viper",
    "Viper",
    "Viper"
  ],
  "attributes": {
    "Health": 13145,
    "Armor": 2361,
    "Power": 2866,
    "Precision": 1955,
    "Toughness": 1243,
    "Vitality": 1150,
    "Ferocity": 150,
    "Condition Damage": 2548,
    "Expertise": 779,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0.5193333333333333,
    "Boon Duration": 0.162,
    "Critical Chance": 0.7047619047619047,
    "Critical Damage": 1.6,
    "Power Coefficient": 2111,
    "Burning Coefficient": 0.55,
    "Bleeding Coefficient": 2.7,
    "Poison Coefficient": 20.68,
    "Torment Coefficient": 22.67,
    "Confusion Coefficient": 0,
    "Flat DPS": 0,
    "Torment Duration": 0.5,
    "Poison Duration": 0.48,
    "Outgoing Healing": 0.2,
    "Effective Power": 7977.000851999997,
    "Power DPS": 6484.192837340005,
    "Bleeding Damage": 280.6824,
    "Bleeding Stacks": 4.102200000000001,
    "Bleeding DPS": 1151.4153412800001,
    "Burning Damage": 844.1337,
    "Burning Stacks": 0.8356333333333335,
    "Burning DPS": 705.3862575100001,
    "Confusion Damage": 331.61226,
    "Confusion Stacks": 0,
    "Confusion DPS": 0,
    "Poison Damage": 397.85606699999994,
    "Poison Stacks": 41.34621333333333,
    "Poison DPS": 16449.841822142957,
    "Torment Damage": 502.91711999999995,
    "Torment Stacks": 45.34,
    "Torment DPS": 22802.2622208,
    "Damage": 47593.09847907296,
    "Effective Health": 77202350.74626867,
    "Survivability": 39248.780247213355,
    "Effective Healing": 468,
    "Healing": 468
  },
  "runeId": 44956,
  "runeName": "Tormenting",
  "infusions": [
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432,
    49432
  ],
    "weapons": {
      "weapon1MainType": "Scepter",
      "weapon1MainSigil1": "Doom",
      "weapon1OffType": "Dagger",
      "weapon1OffSigil": "Torment",
      "weapon2MainType": "Scepter",
      "weapon2MainSigil1": "Doom",
      "weapon2OffType": "Pistol",
      "weapon2OffSigil": "Paralyzation"
    },
    "consumables": {
      "foodId": 97422,
      "utilityId": 48917,
      "infusion": "Malign +9 Agony Infusion"
    },
    "skills": {
      "heal": "Hide in Shadows",
      "utility1": "Thousand Needles",
      "utility2": "Skale Venom",
      "utility3": "Spider Venom",
      "elite": "Basilisk Venom"
    },
    "assumedBuffs": [{"id": "Might", "type": "Boon"}, {"id": "Fury", "type": "Boon"}, {"gw2id": 1786, "type": "Trait"}, {"id": "jade-bot-per-tier", "value": 10, "type": "Text"}]
  }}
>

If healing isn't an issue, this is the perfect build to use <Item name="writofmasterfulmalice"/> over <Item name="tuningicicle"/> ! <Skill name="signetofmalice"/> is also the strongest personal-healing ability you can bring to maintain your health over 90%, if you feel you don't need <Skill name="hideinshadows"/>.

The <Skill name="skelkvenom"/> is a much better option to support your party as it brings a tremendous amount of party heal.
It's recommended to run a shortbow for additional movement during downtime and <Boon name="might"/> blasts on the _Mistlock Singularity_.

If you do not need the extra CC you can run a Dagger with <Item id="48911"/> instead of Pistol in your second weapon set.

</Character>  
</CharacterWithAr>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Card title="Traits">
<Traits unembossed traits1="Trickery" traits1Selected="Thrill of the Crime,Pressure Striking,Quick Pockets" traits2="Deadly Arts" traits2Selected="Deadly Ambition,Panic Strike,Potent Poison" traits3="Specter" traits3Selected="Consume Shadows,Larcenous Torment,Strength of Shadows"/>

### No Pain, No Gain Variant

<Trait id="1277"/> over <Trait id="1190"/> on <Instability name="No Pain, No Gain"/> days, or when boonstrip is needed.
<Traits traits1="Trickery" traits1Selected="Thrill of the Crime,Bountiful Theft,Quick Pockets" unembossed/>

### Alacrity Variant

Situationally <Specialization name="Specter"/> can be used as a <Boon name="Alacrity"/> source. You will need to adjust your gear using the [gear optimizer](https://optimizer.discretize.eu/) to gain at least 43% <Attribute name="Boon Duration"/> if you want to upkeep it permanantly.

<Traits traits1="Specter" traits1Selected="Consume Shadows,Traversing Dusk,Strength of Shadows" unembossed/>
<Skills heal="Well of Gloom" utility1="Well of Bounty" utility2="Well of Sorrow" utility3="Spider Venom" elite="Basilisk Venom" unembossed/>

</Card>
<Card title="Defiance Bar Damage">

|                                            |                                                        |
| ------------------------------------------ | ------------------------------------------------------ |
| <Skill id="13132" size="big" disableText/> | 150 Defiance bar damage per ally (Up to 750 CC).       |
| <Skill id="63155" size="big" disableText/> | Mind Shock (skill 5) 150 Defiance bar damage           |
| <Skill id="13020" size="big" disableText/> | 150 Defiance bar damage.                               |
| <Skill id="13012" size="big" disableText/> | 200 Defiance bar damage (260 with <Item id="24639"/>). |
| <Skill id="13019" size="big" disableText/> | <Condition name="Crippled"/> 15/s Defiance bar damage. |
| <Skill id="13093" size="big" disableText/> | <Condition name="Immobile"/> 50/s Defiance bar damage. |

</Card>
</GridItem>
<GridItem sm="5">

<Card title="Situational Skills">

|                                                       |                                                                                                                                              |
| ----------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| <Skill id="13093" size="big" disableText/>            | A situational damage ability, to take over <Skill name="Thousand Needles"/> on moving targets.                                              |
| <Skill name="signetofmalice" size="big" disableText/> | Highest sustained healing.                                                                                                                   |
| <Skill name="skelkvenom" size="big" disableText/>     | Best party healing.                                                                                                                          |
| <Skill id="13020" size="big" disableText/>            | Taken over <Skill name="Prepare Thousand Needles"/> when extra CC is needed (particularly useful on MAMA).                                   |
| <Skill id="13082" size="big" disableText/>            | Taken for extra personal DPS, when CC isn't needed. Can also be precasted on the mistlock before swapping to <Skill name="Basilisk Venom"/>, |

</Card>

<Card title="Useful skills for skips">

|                                            |                                                                                                           |
| ------------------------------------------ | --------------------------------------------------------------------------------------------------------- |
| <Skill id="13117" size="big" disableText/> | Group stealth. Keep in mind, if you leave the AoE before it ends, you will be revealed for a long period. |
| <Skill id="13065" size="big" disableText/> | Used for a smoke field to blast <Effect name="Stealth"/> for skips.                                       |
| <Skill id="13044" size="big" disableText/> | 3 seconds AoE <Effect name="Stealth"/> (also another blast).                                              |
| <Skill id="13064" size="big" disableText/> | 1200 range shadowstep, useful for some skips.                                                             |
| <Skill id="13002" size="big" disableText/> | 1200 range teleport, use it again to teleport back.                                                       |
| <Skill id="13038" size="big" disableText/> | One way portal, useful if you don't have <Item id="78978"/>.                                              |
| <Skill id="13025" size="big" disableText/> | 900 range shadowstep, useful for some skips.                                                              |
| <Skill id="13041" size="big" disableText/> | Used as a blast finisher to stack <Effect name="Stealth"/>.                                               |

</Card>

</GridItem>
</Grid>

<Divider text="Rotation / Skill usage"/>

<Grid>
<GridItem sm="6">
<Card title="Rotation">
There is no set rotation for <Specialization name="Specter" text="Condi Specter"/>, your rotation comes from skill priority. Your main aim when playing <Specialization name="Specter" text="Condi Specter"/> is to never have full Initiative, cast utility skills of cooldown and proc <Trait name="Quick Pockets"/> and <Item id="24609"/> as often as possible.

You should be casting your <Skill name="Skale Venom"/>, <Skill name="Spider Venom"/> and <Skill name="Thousand Needles"/> off cooldown (unless a phase is about to end).

On Scepter/Dagger you want to use:
- <Skill name="Twilight Combo"/>
- <Skill name="Shadow Bolt"/>, <Skill name="Double Bolt"/>, <Skill name="Triple Bolt"/>

You should also be weapon swapping off cooldown if you are not playing Pistol to make the best use of <Trait name="Quick Pockets"/> and <Item id="24609"/>

In <Skill name="Enter Shadow Shroud" text="Shadow Shorud"/> you want to use:
- Mind Shock (Skill 5)
- Eternal Night (Skill 4)
- Grasping Shadows (Skill 2)
- Haunt Shot (Skill 1)

</Card>
</GridItem>

<GridItem sm="6">
<Card title="Golem rotation">
<Video youtube="7ZjQJmms_Dw" caption="by Incera"/>
</Card>

<Card title="Precasting">

All Damaging Venom Skills should be casted on the _Mistlock Singularity_: <Skill name="Skale Venom"/>, <Skill name="Spider Venom"/> and <Skill name="Devourer Venom"/>. On stationary bosses which can be manually activated, instead of precasting <Skill name="Devourer Venom"/>, you can instead go to the spawn location and precast <Skill name="preparethousandneedles"/>. All you have to do then is to activate the Preparation when the boss becomes vulnerable, and cast it again as it will be off cooldown. This is possible on Skorvald, Artsariiv, Arkk, MAMA and Ensolyss with the use of a <Item name="White Mantle Portal Device"/>, or on Siax without. It is also possible on the Sorrowful Spellcaster (Light & Dark Ai), but with a 1/4 chance of success.

- On 100CM, make sure to precast venoms on your <Skill id="13082"/> minions, as every boon and special ability effect currently on you will be stripped upon starting the encounter.
- Spam <Skill name="clusterbomb"/> for <Boon name="might"/> blasts on the _Mistlock Singularity_.

</Card>
</GridItem>
</Grid>
