### Roster Details<br />
Team Name: Spirit<br />
Roster: chopper, donk, magixx, sh1ro, zont1x<br />
Global Rank: [2](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [2]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1928.6<br />
<br />
Final Rank Value (1928.6) = Starting Rank Value (1903.9) + Head To Head Adjustments (24.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.664[<sup>2</sup>](#table1)
- Opponent Network: 0.267[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.733<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1903.9
- 400 + ( ( 0.733 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1903.9


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
|           30 |       85 | 2024-08-03 | Complexity    | W   | 1.000      | 0.581        | 0.341 (0.198)    | 0.372 (0.216)    | 1 (1.000) |     3.86 | chopper, donk, magixx, sh1ro, zont1x |
|           29 |      252 | 2024-07-30 | HEROIC        | W   | 1.000      | 0.581        | 0.225 (0.130)    | 0.363 (0.211)    | 1 (1.000) |     3.89 | chopper, donk, magixx, sh1ro, zont1x |
|           28 |      282 | 2024-07-29 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.19 | chopper, donk, magixx, sh1ro, zont1x |
|           27 |      624 | 2024-07-18 | G2            | L   | 1.000      | -            | -                | -                | -         |   -14.57 | chopper, donk, magixx, sh1ro, zont1x |
|           26 |      702 | 2024-07-17 | MIBR          | W   | 1.000      | 1.000        | 0.208 (0.208)    | 0.647 (0.647)    | 1 (1.000) |     1.43 | chopper, donk, magixx, sh1ro, zont1x |
|           25 |     1032 | 2024-06-16 | Natus Vincere | W   | 0.861      | 0.729        | 1.000 (0.628)    | 0.365 (0.229)    | 1 (0.861) |    13.52 | chopper, donk, magixx, sh1ro, zont1x |
|           24 |     1063 | 2024-06-15 | Vitality      | W   | 0.855      | 0.729        | 0.647 (0.403)    | 0.375 (0.234)    | 1 (0.855) |    11.47 | chopper, donk, magixx, sh1ro, zont1x |
|           23 |     1127 | 2024-06-13 | Virtus.pro    | W   | 0.843      | 0.729        | 0.498 (0.306)    | 0.316 (0.194)    | 1 (0.843) |     5.31 | chopper, donk, magixx, sh1ro, zont1x |
|           22 |     1158 | 2024-06-12 | G2            | W   | 0.836      | -            | -                | -                | 1 (0.836) |     0.02 | chopper, donk, magixx, sh1ro, zont1x |
|           21 |     1621 | 2024-06-01 | Vitality      | L   | 0.762      | -            | -                | -                | -         |   -13.70 | chopper, donk, magixx, sh1ro, zont1x |
|           20 |     1705 | 2024-05-29 | FaZe          | W   | 0.743      | 0.624        | 0.626 (0.290)    | 0.391 (0.181)    | 1 (0.743) |     6.35 | chopper, donk, magixx, sh1ro, zont1x |
|           19 |     1735 | 2024-05-28 | Natus Vincere | W   | 0.735      | 0.624        | 1.000 (0.459)    | -                | 1 (0.735) |    12.82 | chopper, donk, magixx, sh1ro, zont1x |
|           18 |     1750 | 2024-05-27 | FlyQuest      | W   | 0.730      | -            | -                | -                | -         |     0.47 | chopper, donk, magixx, sh1ro, zont1x |
|           17 |     1973 | 2024-05-19 | MOUZ          | L   | 0.674      | -            | -                | -                | -         |   -10.93 | chopper, donk, magixx, sh1ro, zont1x |
|           16 |     2009 | 2024-05-18 | Falcons       | W   | 0.667      | -            | -                | -                | -         |     1.31 | chopper, donk, magixx, sh1ro, zont1x |
|           15 |     2074 | 2024-05-16 | HEROIC        | W   | 0.655      | 0.769        | -                | 0.363 (0.182)    | -         |     2.51 | chopper, donk, magixx, sh1ro, zont1x |
|           14 |     2132 | 2024-05-15 | Aurora        | W   | 0.647      | 0.769        | 0.421 (0.209)    | 0.776 (0.386)    | -         |     2.95 | chopper, donk, magixx, sh1ro, zont1x |
|           13 |     3323 | 2024-03-28 | FaZe          | L   | 0.329      | -            | -                | -                | -         |    -8.11 | chopper, donk, magixx, sh1ro, zont1x |
|           12 |     3430 | 2024-03-22 | Natus Vincere | W   | 0.288      | 1.000        | 1.000 (0.288)    | -                | -         |     5.47 | chopper, donk, magixx, sh1ro, zont1x |
|           11 |     3444 | 2024-03-21 | Imperial      | W   | 0.283      | 1.000        | -                | 0.673 (0.191)    | -         |     0.24 | chopper, donk, magixx, sh1ro, zont1x |
|           10 |     3454 | 2024-03-21 | Cloud9        | W   | 0.282      | -            | -                | -                | -         |     0.07 | chopper, donk, magixx, sh1ro, zont1x |
|            9 |     3702 | 2024-03-10 | Metizport     | W   | 0.209      | -            | -                | -                | -         |     0.03 | chopper, donk, magixx, sh1ro, zont1x |
|            8 |     3722 | 2024-03-09 | BIG           | W   | 0.203      | -            | -                | -                | -         |     0.21 | chopper, donk, magixx, sh1ro, zont1x |
|            7 |     3757 | 2024-03-08 | Elevate       | W   | 0.195      | -            | -                | -                | -         |     0.04 | chopper, donk, magixx, sh1ro, zont1x |
|            6 |     4112 | 2024-02-21 | HEROIC        | W   | 0.089      | -            | -                | -                | -         |     0.36 | chopper, donk, magixx, sh1ro, zont1x |
|            5 |     4143 | 2024-02-20 | MOUZ          | L   | 0.082      | -            | -                | -                | -         |    -1.51 | chopper, donk, magixx, sh1ro, zont1x |
|            4 |     4162 | 2024-02-19 | Astralis      | W   | 0.076      | -            | -                | -                | -         |     0.65 | chopper, donk, magixx, sh1ro, zont1x |
|            3 |     4177 | 2024-02-19 | ENCE          | W   | 0.074      | -            | -                | -                | -         |     0.20 | chopper, donk, magixx, sh1ro, zont1x |
|            2 |     4362 | 2024-02-11 | FaZe          | W   | 0.022      | -            | -                | -                | -         |     0.15 | chopper, donk, magixx, sh1ro, zont1x |
|            1 |     4369 | 2024-02-10 | Falcons       | W   | 0.016      | -            | -                | -                | -         |     0.03 | chopper, donk, magixx, sh1ro, zont1x |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($346,068.06)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.861 | $200,000.00    | $172,222.22     |
| 2024-06-02 |      0.769 | $20,000.00     | $15,377.78      |
| 2024-05-19 |      0.674 | $100,000.00    | $67,416.67      |
| 2024-03-31 |      0.349 | $45,000.00     | $15,700.00      |
| 2024-03-10 |      0.209 | $20,000.00     | $4,184.72       |
| 2024-02-11 |      0.022 | $400,000.00    | $8,666.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
