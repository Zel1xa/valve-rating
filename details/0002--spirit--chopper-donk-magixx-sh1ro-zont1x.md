### Roster Details<br />
Team Name: Spirit<br />
Roster: chopper, donk, magixx, sh1ro, zont1x<br />
Global Rank: [2](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [2]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1928.7<br />
<br />
Final Rank Value (1928.7) = Starting Rank Value (1903.0) + Head To Head Adjustments (25.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.667[<sup>2</sup>](#table1)
- Opponent Network: 0.274[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.735<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1903.0
- 400 + ( ( 0.735 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1903.0


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
|           31 |       31 | 2024-08-03 | Complexity    | W   | 1.000      | 0.581        | 0.310 (0.180)    | 0.380 (0.221)    | 1 (1.000) |     3.78 | chopper, donk, magixx, sh1ro, zont1x |
|           30 |      197 | 2024-07-30 | HEROIC        | W   | 1.000      | 0.581        | 0.229 (0.133)    | 0.373 (0.217)    | 1 (1.000) |     3.92 | chopper, donk, magixx, sh1ro, zont1x |
|           29 |      228 | 2024-07-29 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.19 | chopper, donk, magixx, sh1ro, zont1x |
|           28 |      568 | 2024-07-18 | G2            | L   | 1.000      | -            | -                | -                | -         |   -14.63 | chopper, donk, magixx, sh1ro, zont1x |
|           27 |      649 | 2024-07-17 | MIBR          | W   | 1.000      | 1.000        | 0.209 (0.209)    | 0.659 (0.659)    | 1 (1.000) |     1.45 | chopper, donk, magixx, sh1ro, zont1x |
|           26 |      976 | 2024-06-16 | Natus Vincere | W   | 0.874      | 0.729        | 1.000 (0.637)    | 0.331 (0.211)    | 1 (0.874) |    13.65 | chopper, donk, magixx, sh1ro, zont1x |
|           25 |     1007 | 2024-06-15 | Vitality      | W   | 0.867      | 0.729        | 0.649 (0.410)    | 0.383 (0.242)    | 1 (0.867) |    11.71 | chopper, donk, magixx, sh1ro, zont1x |
|           24 |     1071 | 2024-06-13 | Virtus.pro    | W   | 0.855      | 0.729        | 0.497 (0.310)    | 0.323 (0.202)    | 1 (0.855) |     5.44 | chopper, donk, magixx, sh1ro, zont1x |
|           23 |     1102 | 2024-06-12 | G2            | W   | 0.849      | -            | -                | -                | 1 (0.849) |     0.02 | chopper, donk, magixx, sh1ro, zont1x |
|           22 |     1565 | 2024-06-01 | Vitality      | L   | 0.775      | -            | -                | -                | -         |   -13.85 | chopper, donk, magixx, sh1ro, zont1x |
|           21 |     1649 | 2024-05-29 | FaZe          | W   | 0.755      | 0.624        | 0.639 (0.301)    | 0.402 (0.190)    | 1 (0.755) |     6.65 | chopper, donk, magixx, sh1ro, zont1x |
|           20 |     1679 | 2024-05-28 | Natus Vincere | W   | 0.748      | 0.624        | 1.000 (0.467)    | -                | 1 (0.748) |    13.01 | chopper, donk, magixx, sh1ro, zont1x |
|           19 |     1694 | 2024-05-27 | FlyQuest      | W   | 0.742      | -            | -                | -                | -         |     0.49 | chopper, donk, magixx, sh1ro, zont1x |
|           18 |     1917 | 2024-05-19 | MOUZ          | L   | 0.687      | -            | -                | -                | -         |   -11.04 | chopper, donk, magixx, sh1ro, zont1x |
|           17 |     1953 | 2024-05-18 | Falcons       | W   | 0.680      | -            | -                | -                | -         |     1.37 | chopper, donk, magixx, sh1ro, zont1x |
|           16 |     2018 | 2024-05-16 | HEROIC        | W   | 0.667      | 0.769        | -                | 0.373 (0.191)    | -         |     2.60 | chopper, donk, magixx, sh1ro, zont1x |
|           15 |     2076 | 2024-05-15 | Aurora        | W   | 0.659      | 0.769        | 0.423 (0.215)    | 0.793 (0.402)    | -         |     2.90 | chopper, donk, magixx, sh1ro, zont1x |
|           14 |     3267 | 2024-03-28 | FaZe          | L   | 0.342      | -            | -                | -                | -         |    -8.35 | chopper, donk, magixx, sh1ro, zont1x |
|           13 |     3374 | 2024-03-22 | Natus Vincere | W   | 0.301      | 1.000        | 1.000 (0.301)    | -                | -         |     5.71 | chopper, donk, magixx, sh1ro, zont1x |
|           12 |     3388 | 2024-03-21 | Imperial      | W   | 0.296      | 1.000        | -                | 0.685 (0.203)    | -         |     0.27 | chopper, donk, magixx, sh1ro, zont1x |
|           11 |     3398 | 2024-03-21 | Cloud9        | W   | 0.294      | -            | -                | -                | -         |     0.08 | chopper, donk, magixx, sh1ro, zont1x |
|           10 |     3646 | 2024-03-10 | Metizport     | W   | 0.222      | -            | -                | -                | -         |     0.03 | chopper, donk, magixx, sh1ro, zont1x |
|            9 |     3666 | 2024-03-09 | BIG           | W   | 0.215      | -            | -                | -                | -         |     0.23 | chopper, donk, magixx, sh1ro, zont1x |
|            8 |     3701 | 2024-03-08 | Elevate       | W   | 0.207      | -            | -                | -                | -         |     0.04 | chopper, donk, magixx, sh1ro, zont1x |
|            7 |     4056 | 2024-02-21 | HEROIC        | W   | 0.101      | -            | -                | -                | -         |     0.42 | chopper, donk, magixx, sh1ro, zont1x |
|            6 |     4087 | 2024-02-20 | MOUZ          | L   | 0.094      | -            | -                | -                | -         |    -1.73 | chopper, donk, magixx, sh1ro, zont1x |
|            5 |     4106 | 2024-02-19 | Astralis      | W   | 0.089      | -            | -                | -                | -         |     0.77 | chopper, donk, magixx, sh1ro, zont1x |
|            4 |     4121 | 2024-02-19 | ENCE          | W   | 0.086      | -            | -                | -                | -         |     0.22 | chopper, donk, magixx, sh1ro, zont1x |
|            3 |     4306 | 2024-02-11 | FaZe          | W   | 0.034      | -            | -                | -                | -         |     0.25 | chopper, donk, magixx, sh1ro, zont1x |
|            2 |     4313 | 2024-02-10 | Falcons       | W   | 0.028      | -            | -                | -                | -         |     0.06 | chopper, donk, magixx, sh1ro, zont1x |
|            1 |     4362 | 2024-02-06 | FaZe          | W   | 0.001      | -            | -                | -                | -         |     0.01 | chopper, donk, magixx, sh1ro, zont1x |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($355,971.41)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.874 | $200,000.00    | $174,745.37     |
| 2024-06-02 |      0.782 | $20,000.00     | $15,630.09      |
| 2024-05-19 |      0.687 | $100,000.00    | $68,678.24      |
| 2024-03-31 |      0.362 | $45,000.00     | $16,267.71      |
| 2024-03-10 |      0.222 | $20,000.00     | $4,437.04       |
| 2024-02-11 |      0.034 | $400,000.00    | $13,712.96      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
