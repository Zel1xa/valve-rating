### Roster Details<br />
Team Name: Spirit<br />
Roster: chopper, donk, magixx, sh1ro, zont1x<br />
Global Rank: [2](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [2]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1932.2<br />
<br />
Final Rank Value (1932.2) = Starting Rank Value (1910.4) + Head To Head Adjustments (21.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.668[<sup>2</sup>](#table1)
- Opponent Network: 0.284[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.738<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1910.4
- 400 + ( ( 0.738 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1910.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |       16 | 2024-08-03 | Complexity    | W   | 1.000      | 0.581        | 0.313 (0.182)    | 0.394 (0.229)    | 1 (1.000) |     3.65 | chopper, donk, magixx, sh1ro, zont1x |
|           30 |      163 | 2024-07-30 | HEROIC        | W   | 1.000      | 0.581        | 0.230 (0.134)    | 0.388 (0.226)    | 1 (1.000) |     3.71 | chopper, donk, magixx, sh1ro, zont1x |
|           29 |      193 | 2024-07-29 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.18 | chopper, donk, magixx, sh1ro, zont1x |
|           28 |      534 | 2024-07-18 | G2            | L   | 1.000      | -            | -                | -                | -         |   -15.11 | chopper, donk, magixx, sh1ro, zont1x |
|           27 |      612 | 2024-07-17 | MIBR          | W   | 1.000      | 1.000        | 0.210 (0.210)    | 0.682 (0.682)    | 1 (1.000) |     1.33 | chopper, donk, magixx, sh1ro, zont1x |
|           26 |      928 | 2024-06-16 | Natus Vincere | W   | 0.879      | 0.729        | 1.000 (0.641)    | 0.343 (0.220)    | 1 (0.879) |    13.66 | chopper, donk, magixx, sh1ro, zont1x |
|           25 |      956 | 2024-06-15 | Vitality      | W   | 0.873      | 0.729        | 0.650 (0.413)    | 0.396 (0.252)    | 1 (0.873) |    11.58 | chopper, donk, magixx, sh1ro, zont1x |
|           24 |     1009 | 2024-06-13 | Virtus.pro    | W   | 0.861      | 0.729        | 0.496 (0.311)    | 0.335 (0.210)    | 1 (0.861) |     5.25 | chopper, donk, magixx, sh1ro, zont1x |
|           23 |     1039 | 2024-06-12 | G2            | W   | 0.854      | -            | -                | -                | 1 (0.854) |     0.02 | chopper, donk, magixx, sh1ro, zont1x |
|           22 |     1491 | 2024-06-01 | Vitality      | L   | 0.780      | -            | -                | -                | -         |   -14.13 | chopper, donk, magixx, sh1ro, zont1x |
|           21 |     1574 | 2024-05-29 | FaZe          | W   | 0.761      | 0.624        | 0.644 (0.306)    | 0.418 (0.198)    | 1 (0.761) |     6.65 | chopper, donk, magixx, sh1ro, zont1x |
|           20 |     1604 | 2024-05-28 | Natus Vincere | W   | 0.753      | 0.624        | 1.000 (0.470)    | -                | 1 (0.753) |    13.06 | chopper, donk, magixx, sh1ro, zont1x |
|           19 |     1619 | 2024-05-27 | FlyQuest      | W   | 0.748      | -            | -                | -                | -         |     0.48 | chopper, donk, magixx, sh1ro, zont1x |
|           18 |     1840 | 2024-05-19 | MOUZ          | L   | 0.692      | -            | -                | -                | -         |   -12.72 | chopper, donk, magixx, sh1ro, zont1x |
|           17 |     1876 | 2024-05-18 | Falcons       | W   | 0.685      | -            | -                | -                | -         |     1.37 | chopper, donk, magixx, sh1ro, zont1x |
|           16 |     1941 | 2024-05-16 | HEROIC        | W   | 0.673      | 0.769        | -                | 0.388 (0.201)    | -         |     2.46 | chopper, donk, magixx, sh1ro, zont1x |
|           15 |     1999 | 2024-05-15 | Aurora        | W   | 0.665      | 0.769        | 0.425 (0.217)    | 0.809 (0.413)    | -         |     2.86 | chopper, donk, magixx, sh1ro, zont1x |
|           14 |     3188 | 2024-03-28 | FaZe          | L   | 0.347      | -            | -                | -                | -         |    -8.46 | chopper, donk, magixx, sh1ro, zont1x |
|           13 |     3290 | 2024-03-22 | Natus Vincere | W   | 0.307      | 1.000        | 1.000 (0.307)    | -                | -         |     5.78 | chopper, donk, magixx, sh1ro, zont1x |
|           12 |     3304 | 2024-03-21 | Imperial      | W   | 0.301      | 1.000        | -                | 0.708 (0.213)    | -         |     0.23 | chopper, donk, magixx, sh1ro, zont1x |
|           11 |     3314 | 2024-03-21 | Cloud9        | W   | 0.300      | -            | -                | -                | -         |     0.08 | chopper, donk, magixx, sh1ro, zont1x |
|           10 |     3559 | 2024-03-10 | Metizport     | W   | 0.227      | -            | -                | -                | -         |     0.03 | chopper, donk, magixx, sh1ro, zont1x |
|            9 |     3579 | 2024-03-09 | BIG           | W   | 0.221      | -            | -                | -                | -         |     0.23 | chopper, donk, magixx, sh1ro, zont1x |
|            8 |     3614 | 2024-03-08 | Elevate       | W   | 0.213      | -            | -                | -                | -         |     0.03 | chopper, donk, magixx, sh1ro, zont1x |
|            7 |     3969 | 2024-02-21 | HEROIC        | W   | 0.107      | -            | -                | -                | -         |     0.43 | chopper, donk, magixx, sh1ro, zont1x |
|            6 |     4000 | 2024-02-20 | MOUZ          | L   | 0.100      | -            | -                | -                | -         |    -2.10 | chopper, donk, magixx, sh1ro, zont1x |
|            5 |     4019 | 2024-02-19 | Astralis      | W   | 0.094      | -            | -                | -                | -         |     0.68 | chopper, donk, magixx, sh1ro, zont1x |
|            4 |     4034 | 2024-02-19 | ENCE          | W   | 0.092      | -            | -                | -                | -         |     0.22 | chopper, donk, magixx, sh1ro, zont1x |
|            3 |     4218 | 2024-02-11 | FaZe          | W   | 0.040      | -            | -                | -                | -         |     0.29 | chopper, donk, magixx, sh1ro, zont1x |
|            2 |     4225 | 2024-02-10 | Falcons       | W   | 0.034      | -            | -                | -                | -         |     0.07 | chopper, donk, magixx, sh1ro, zont1x |
|            1 |     4274 | 2024-02-06 | FaZe          | W   | 0.006      | -            | -                | -                | -         |     0.04 | chopper, donk, magixx, sh1ro, zont1x |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($360,278.01)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.879 | $200,000.00    | $175,842.59     |
| 2024-06-02 |      0.787 | $20,000.00     | $15,739.81      |
| 2024-05-19 |      0.692 | $100,000.00    | $69,226.85      |
| 2024-03-31 |      0.367 | $45,000.00     | $16,514.58      |
| 2024-03-10 |      0.227 | $20,000.00     | $4,546.76       |
| 2024-02-11 |      0.040 | $400,000.00    | $15,907.41      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
