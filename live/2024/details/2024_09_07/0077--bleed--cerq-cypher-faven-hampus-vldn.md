### Roster Details<br />
Team Name: BLEED<br />
Roster: CeRq, CYPHER, faveN, hampus, VLDN<br />
Global Rank: [77](../../standings_global_2024_09_07.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_07.md)<br />
Regional Rank: [56]( ../../standings_europe_2024_09_07.md)<br />
<br />
Final Rank Value:  922.6<br />
<br />
Final Rank Value (922.6) = Starting Rank Value (845.9) + Head To Head Adjustments (76.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.427[<sup>1</sup>](#table2)
- Bounty Collected: 0.357[<sup>2</sup>](#table1)
- Opponent Network: 0.127[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.228<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 845.9
- 400 + ( ( 0.228 - 0.000 ) / ( 0.818 - 0.000 ) ) * 1600 = 845.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |     3372 | 2024-05-11 | B8                | L   | 0.407      | -            | -                | -                | -         |    -4.36 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     3400 | 2024-05-09 | Sampi             | W   | 0.396      | 0.435        | 0.033 (0.006)    | 1.000 (0.172)    | 0 (0.000) |     6.19 | CYPHER, draken, faveN, hampus, VLDN |
|           31 |     3442 | 2024-05-07 | 1WIN              | L   | 0.382      | -            | -                | -                | -         |    -6.44 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     3466 | 2024-05-06 | Insilio           | W   | 0.374      | 0.396        | -                | 0.637 (0.094)    | 0 (0.000) |     5.74 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     3530 | 2024-05-02 | AMKAL             | L   | 0.349      | -            | -                | -                | -         |    -2.89 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     3566 | 2024-05-01 | MOUZ NXT          | L   | 0.341      | -            | -                | -                | -         |    -4.41 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     3598 | 2024-04-30 | Permitta          | W   | 0.333      | 0.384        | -                | 0.999 (0.128)    | 0 (0.000) |     5.52 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     3621 | 2024-04-28 | B8                | W   | 0.323      | 0.500        | 0.176 (0.028)    | 1.000 (0.161)    | 0 (0.000) |     6.68 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     3671 | 2024-04-26 | ex-Guild Eagles   | W   | 0.309      | -            | -                | -                | 0 (0.000) |     2.92 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           24 |     3679 | 2024-04-26 | DMS               | W   | 0.308      | -            | -                | -                | 0 (0.000) |     4.32 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     3721 | 2024-04-24 | Permitta          | W   | 0.296      | 0.435        | -                | 0.999 (0.128)    | 0 (0.000) |     5.36 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     3722 | 2024-04-24 | Nemiga            | L   | 0.295      | -            | -                | -                | -         |    -1.70 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     3741 | 2024-04-23 | B8                | W   | 0.288      | 0.500        | 0.176 (0.025)    | 1.000 (0.144)    | 0 (0.000) |     6.21 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     3750 | 2024-04-23 | Sashi             | L   | 0.287      | -            | -                | -                | -         |    -2.37 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     3758 | 2024-04-22 | Sangal            | W   | 0.282      | 0.500        | 0.248 (0.035)    | 0.869 (0.122)    | 0 (0.000) |     7.85 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           18 |     3760 | 2024-04-22 | Gaimin Gladiators | W   | 0.281      | -            | -                | -                | 0 (0.000) |     4.92 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     3775 | 2024-04-21 | Illuminar         | W   | 0.276      | -            | -                | -                | -         |     0.96 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     3781 | 2024-04-21 | BIG               | W   | 0.274      | 0.384        | 0.146 (0.015)    | -                | -         |     7.43 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     3804 | 2024-04-20 | MOUZ NXT          | W   | 0.268      | 0.500        | 0.111 (0.015)    | 0.844 (0.113)    | -         |     5.55 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           14 |     3861 | 2024-04-19 | Sampi             | W   | 0.261      | 0.384        | -                | 1.000 (0.100)    | -         |     4.60 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     3918 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.253      | 0.500        | 0.101 (0.013)    | 0.862 (0.109)    | -         |     5.88 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           12 |     3953 | 2024-04-17 | 3DMAX             | L   | 0.247      | -            | -                | -                | -         |    -0.09 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           11 |     3972 | 2024-04-16 | KOI               | W   | 0.242      | 0.384        | 0.053 (0.005)    | -                | -         |     4.86 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           10 |     3982 | 2024-04-16 | SINNERS           | W   | 0.240      | 0.384        | 0.081 (0.007)    | -                | -         |     6.44 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            9 |     4162 | 2024-04-09 | Alliance          | W   | 0.195      | -            | -                | -                | -         |     2.94 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            8 |     4170 | 2024-04-09 | HAVU              | W   | 0.194      | -            | -                | -                | -         |     1.03 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            7 |     4254 | 2024-04-05 | BetBoom           | L   | 0.169      | -            | -                | -                | -         |    -0.54 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            6 |     4257 | 2024-04-05 | Alliance          | W   | 0.168      | -            | -                | -                | -         |     2.59 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            5 |     4296 | 2024-04-04 | Benched Heroes    | W   | 0.162      | -            | -                | -                | -         |     0.39 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            4 |     4303 | 2024-04-04 | BetBoom           | L   | 0.161      | -            | -                | -                | -         |    -0.51 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            3 |     4373 | 2024-04-02 | Passion UA        | W   | 0.149      | 0.384        | 0.147 (0.008)    | -                | -         |     3.36 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            2 |     4395 | 2024-04-01 | Enterprise        | L   | 0.141      | -            | -                | -                | -         |    -2.02 | CeRq, CYPHER, faveN, hampus, VLDN   |
|            1 |     4750 | 2024-03-13 | Sashi             | W   | 0.014      | -            | -                | -                | -         |     0.34 | CeRq, CYPHER, faveN, hampus, VLDN   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($14,059.79)
- Divide that value by the 5th highest value among all rosters ($307,186.12)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      0.456 | $500.00        | $227.85         |
| 2024-05-12 |      0.416 | $2,000.00      | $831.25         |
| 2024-04-24 |      0.295 | $25,000.00     | $7,378.47       |
| 2024-04-22 |      0.281 | $20,000.00     | $5,622.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
