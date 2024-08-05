### Roster Details<br />
Team Name: Spirit<br />
Roster: chopper, donk, magixx, sh1ro, zont1x<br />
Global Rank: [3](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [3]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1941.1<br />
<br />
Final Rank Value (1941.1) = Starting Rank Value (1917.5) + Head To Head Adjustments (23.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.670[<sup>2</sup>](#table1)
- Opponent Network: 0.274[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.736<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1917.5
- 400 + ( ( 0.736 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1917.5


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
|           32 |       72 | 2024-07-30 | HEROIC        | W   | 1.000      | 0.581        | 0.234 (0.136)    | 0.382 (0.222)    | 1 (1.000) |     3.93 | chopper, donk, magixx, sh1ro, zont1x |
|           31 |      103 | 2024-07-29 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.19 | chopper, donk, magixx, sh1ro, zont1x |
|           30 |      443 | 2024-07-18 | G2            | L   | 1.000      | -            | -                | -                | -         |   -15.29 | chopper, donk, magixx, sh1ro, zont1x |
|           29 |      521 | 2024-07-17 | MIBR          | W   | 1.000      | 1.000        | 0.200 (0.200)    | 0.637 (0.637)    | 1 (1.000) |     1.40 | chopper, donk, magixx, sh1ro, zont1x |
|           28 |      851 | 2024-06-16 | Natus Vincere | W   | 0.898      | 0.729        | 1.000 (0.655)    | 0.331 (0.217)    | 1 (0.898) |    13.99 | chopper, donk, magixx, sh1ro, zont1x |
|           27 |      882 | 2024-06-15 | Vitality      | W   | 0.892      | 0.729        | 0.654 (0.425)    | 0.385 (0.250)    | 1 (0.892) |    11.77 | chopper, donk, magixx, sh1ro, zont1x |
|           26 |      946 | 2024-06-13 | Virtus.pro    | W   | 0.880      | 0.729        | 0.494 (0.317)    | 0.327 (0.210)    | 1 (0.880) |     5.78 | chopper, donk, magixx, sh1ro, zont1x |
|           25 |      977 | 2024-06-12 | G2            | W   | 0.873      | -            | -                | -                | 1 (0.873) |     0.02 | chopper, donk, magixx, sh1ro, zont1x |
|           24 |     1440 | 2024-06-01 | Vitality      | L   | 0.799      | -            | -                | -                | -         |   -14.55 | chopper, donk, magixx, sh1ro, zont1x |
|           23 |     1524 | 2024-05-29 | FaZe          | W   | 0.780      | 0.624        | 0.663 (0.323)    | 0.410 (0.199)    | 1 (0.780) |     7.33 | chopper, donk, magixx, sh1ro, zont1x |
|           22 |     1554 | 2024-05-28 | Natus Vincere | W   | 0.772      | 0.624        | 1.000 (0.482)    | 0.331 (0.160)    | 1 (0.772) |    13.45 | chopper, donk, magixx, sh1ro, zont1x |
|           21 |     1569 | 2024-05-27 | FlyQuest      | W   | 0.767      | -            | -                | -                | 1 (0.767) |     0.53 | chopper, donk, magixx, sh1ro, zont1x |
|           20 |     1792 | 2024-05-19 | MOUZ          | L   | 0.711      | -            | -                | -                | -         |   -11.03 | chopper, donk, magixx, sh1ro, zont1x |
|           19 |     1828 | 2024-05-18 | Falcons       | W   | 0.704      | 0.769        | 0.231 (0.125)    | -                | -         |     1.54 | chopper, donk, magixx, sh1ro, zont1x |
|           18 |     1893 | 2024-05-16 | HEROIC        | W   | 0.692      | 0.769        | -                | 0.382 (0.203)    | -         |     2.78 | chopper, donk, magixx, sh1ro, zont1x |
|           17 |     1951 | 2024-05-15 | Aurora        | W   | 0.684      | 0.769        | 0.429 (0.225)    | 0.800 (0.420)    | -         |     2.95 | chopper, donk, magixx, sh1ro, zont1x |
|           16 |     3142 | 2024-03-28 | FaZe          | L   | 0.366      | -            | -                | -                | -         |    -8.66 | chopper, donk, magixx, sh1ro, zont1x |
|           15 |     3249 | 2024-03-22 | Natus Vincere | W   | 0.326      | 1.000        | 1.000 (0.326)    | -                | -         |     6.22 | chopper, donk, magixx, sh1ro, zont1x |
|           14 |     3263 | 2024-03-21 | Imperial      | W   | 0.320      | 1.000        | -                | 0.685 (0.219)    | -         |     0.30 | chopper, donk, magixx, sh1ro, zont1x |
|           13 |     3273 | 2024-03-21 | Cloud9        | W   | 0.319      | -            | -                | -                | -         |     0.09 | chopper, donk, magixx, sh1ro, zont1x |
|           12 |     3521 | 2024-03-10 | Metizport     | W   | 0.246      | -            | -                | -                | -         |     0.03 | chopper, donk, magixx, sh1ro, zont1x |
|           11 |     3541 | 2024-03-09 | BIG           | W   | 0.240      | -            | -                | -                | -         |     0.17 | chopper, donk, magixx, sh1ro, zont1x |
|           10 |     3576 | 2024-03-08 | Elevate       | W   | 0.232      | -            | -                | -                | -         |     0.04 | chopper, donk, magixx, sh1ro, zont1x |
|            9 |     3931 | 2024-02-21 | HEROIC        | W   | 0.126      | -            | -                | -                | -         |     0.56 | chopper, donk, magixx, sh1ro, zont1x |
|            8 |     3962 | 2024-02-20 | MOUZ          | L   | 0.119      | -            | -                | -                | -         |    -2.10 | chopper, donk, magixx, sh1ro, zont1x |
|            7 |     3981 | 2024-02-19 | Astralis      | W   | 0.113      | -            | -                | -                | -         |     0.83 | chopper, donk, magixx, sh1ro, zont1x |
|            6 |     3996 | 2024-02-19 | ENCE          | W   | 0.111      | -            | -                | -                | -         |     0.29 | chopper, donk, magixx, sh1ro, zont1x |
|            5 |     4181 | 2024-02-11 | FaZe          | W   | 0.059      | -            | -                | -                | -         |     0.47 | chopper, donk, magixx, sh1ro, zont1x |
|            4 |     4188 | 2024-02-10 | Falcons       | W   | 0.053      | -            | -                | -                | -         |     0.12 | chopper, donk, magixx, sh1ro, zont1x |
|            3 |     4237 | 2024-02-06 | FaZe          | W   | 0.025      | -            | -                | -                | -         |     0.20 | chopper, donk, magixx, sh1ro, zont1x |
|            2 |     4266 | 2024-02-04 | Complexity    | W   | 0.012      | -            | -                | -                | -         |     0.07 | chopper, donk, magixx, sh1ro, zont1x |
|            1 |     4294 | 2024-02-03 | Natus Vincere | W   | 0.006      | -            | -                | -                | -         |     0.10 | chopper, donk, magixx, sh1ro, zont1x |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($375,203.91)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-31 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.898 | $200,000.00    | $179,645.37     |
| 2024-06-02 |      0.806 | $20,000.00     | $16,120.09      |
| 2024-05-19 |      0.711 | $100,000.00    | $71,128.24      |
| 2024-03-31 |      0.386 | $45,000.00     | $17,370.21      |
| 2024-03-10 |      0.246 | $20,000.00     | $4,927.04       |
| 2024-02-11 |      0.059 | $400,000.00    | $23,512.96      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
