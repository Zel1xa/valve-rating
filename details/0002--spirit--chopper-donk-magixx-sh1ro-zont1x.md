### Roster Details<br />
Team Name: Spirit<br />
Roster: chopper, donk, magixx, sh1ro, zont1x<br />
Global Rank: [2](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [2]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1930.2<br />
<br />
Final Rank Value (1930.2) = Starting Rank Value (1904.8) + Head To Head Adjustments (25.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.668[<sup>2</sup>](#table1)
- Opponent Network: 0.276[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.736<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1904.8
- 400 + ( ( 0.736 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1904.8


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
|           30 |       53 | 2024-08-03 | Complexity    | W   | 1.000      | 0.581        | 0.342 (0.199)    | 0.380 (0.221)    | 1 (1.000) |     3.87 | chopper, donk, magixx, sh1ro, zont1x |
|           29 |      221 | 2024-07-30 | HEROIC        | W   | 1.000      | 0.581        | 0.229 (0.133)    | 0.373 (0.217)    | 1 (1.000) |     3.92 | chopper, donk, magixx, sh1ro, zont1x |
|           28 |      252 | 2024-07-29 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.19 | chopper, donk, magixx, sh1ro, zont1x |
|           27 |      592 | 2024-07-18 | G2            | L   | 1.000      | -            | -                | -                | -         |   -14.68 | chopper, donk, magixx, sh1ro, zont1x |
|           26 |      670 | 2024-07-17 | MIBR          | W   | 1.000      | 1.000        | 0.209 (0.209)    | 0.659 (0.659)    | 1 (1.000) |     1.44 | chopper, donk, magixx, sh1ro, zont1x |
|           25 |     1000 | 2024-06-16 | Natus Vincere | W   | 0.873      | 0.729        | 1.000 (0.636)    | 0.371 (0.236)    | 1 (0.873) |    13.65 | chopper, donk, magixx, sh1ro, zont1x |
|           24 |     1031 | 2024-06-15 | Vitality      | W   | 0.866      | 0.729        | 0.649 (0.410)    | 0.383 (0.242)    | 1 (0.866) |    11.65 | chopper, donk, magixx, sh1ro, zont1x |
|           23 |     1095 | 2024-06-13 | Virtus.pro    | W   | 0.854      | 0.729        | 0.497 (0.309)    | 0.323 (0.201)    | 1 (0.854) |     5.42 | chopper, donk, magixx, sh1ro, zont1x |
|           22 |     1126 | 2024-06-12 | G2            | W   | 0.848      | -            | -                | -                | 1 (0.848) |     0.02 | chopper, donk, magixx, sh1ro, zont1x |
|           21 |     1589 | 2024-06-01 | Vitality      | L   | 0.774      | -            | -                | -                | -         |   -13.88 | chopper, donk, magixx, sh1ro, zont1x |
|           20 |     1673 | 2024-05-29 | FaZe          | W   | 0.754      | 0.624        | 0.638 (0.300)    | 0.402 (0.189)    | 1 (0.754) |     6.62 | chopper, donk, magixx, sh1ro, zont1x |
|           19 |     1703 | 2024-05-28 | Natus Vincere | W   | 0.747      | 0.624        | 1.000 (0.466)    | -                | 1 (0.747) |    13.01 | chopper, donk, magixx, sh1ro, zont1x |
|           18 |     1718 | 2024-05-27 | FlyQuest      | W   | 0.741      | -            | -                | -                | -         |     0.49 | chopper, donk, magixx, sh1ro, zont1x |
|           17 |     1941 | 2024-05-19 | MOUZ          | L   | 0.686      | -            | -                | -                | -         |   -11.06 | chopper, donk, magixx, sh1ro, zont1x |
|           16 |     1977 | 2024-05-18 | Falcons       | W   | 0.679      | -            | -                | -                | -         |     1.35 | chopper, donk, magixx, sh1ro, zont1x |
|           15 |     2042 | 2024-05-16 | HEROIC        | W   | 0.666      | 0.769        | -                | 0.373 (0.191)    | -         |     2.59 | chopper, donk, magixx, sh1ro, zont1x |
|           14 |     2100 | 2024-05-15 | Aurora        | W   | 0.658      | 0.769        | 0.423 (0.214)    | 0.793 (0.401)    | -         |     2.89 | chopper, donk, magixx, sh1ro, zont1x |
|           13 |     3291 | 2024-03-28 | FaZe          | L   | 0.341      | -            | -                | -                | -         |    -8.33 | chopper, donk, magixx, sh1ro, zont1x |
|           12 |     3398 | 2024-03-22 | Natus Vincere | W   | 0.300      | 1.000        | 1.000 (0.300)    | -                | -         |     5.69 | chopper, donk, magixx, sh1ro, zont1x |
|           11 |     3412 | 2024-03-21 | Imperial      | W   | 0.295      | 1.000        | -                | 0.685 (0.202)    | -         |     0.26 | chopper, donk, magixx, sh1ro, zont1x |
|           10 |     3422 | 2024-03-21 | Cloud9        | W   | 0.293      | -            | -                | -                | -         |     0.08 | chopper, donk, magixx, sh1ro, zont1x |
|            9 |     3670 | 2024-03-10 | Metizport     | W   | 0.221      | -            | -                | -                | -         |     0.02 | chopper, donk, magixx, sh1ro, zont1x |
|            8 |     3690 | 2024-03-09 | BIG           | W   | 0.214      | -            | -                | -                | -         |     0.23 | chopper, donk, magixx, sh1ro, zont1x |
|            7 |     3725 | 2024-03-08 | Elevate       | W   | 0.206      | -            | -                | -                | -         |     0.04 | chopper, donk, magixx, sh1ro, zont1x |
|            6 |     4080 | 2024-02-21 | HEROIC        | W   | 0.100      | -            | -                | -                | -         |     0.41 | chopper, donk, magixx, sh1ro, zont1x |
|            5 |     4111 | 2024-02-20 | MOUZ          | L   | 0.093      | -            | -                | -                | -         |    -1.72 | chopper, donk, magixx, sh1ro, zont1x |
|            4 |     4130 | 2024-02-19 | Astralis      | W   | 0.088      | -            | -                | -                | -         |     0.76 | chopper, donk, magixx, sh1ro, zont1x |
|            3 |     4145 | 2024-02-19 | ENCE          | W   | 0.085      | -            | -                | -                | -         |     0.21 | chopper, donk, magixx, sh1ro, zont1x |
|            2 |     4330 | 2024-02-11 | FaZe          | W   | 0.033      | -            | -                | -                | -         |     0.24 | chopper, donk, magixx, sh1ro, zont1x |
|            1 |     4337 | 2024-02-10 | Falcons       | W   | 0.027      | -            | -                | -                | -         |     0.05 | chopper, donk, magixx, sh1ro, zont1x |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($355,135.53)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.873 | $200,000.00    | $174,532.41     |
| 2024-06-02 |      0.780 | $20,000.00     | $15,608.80      |
| 2024-05-19 |      0.686 | $100,000.00    | $68,571.76      |
| 2024-03-31 |      0.360 | $45,000.00     | $16,219.79      |
| 2024-03-10 |      0.221 | $20,000.00     | $4,415.74       |
| 2024-02-11 |      0.033 | $400,000.00    | $13,287.04      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
