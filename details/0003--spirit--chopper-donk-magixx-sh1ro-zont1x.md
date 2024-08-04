### Roster Details<br />
Team Name: Spirit<br />
Roster: chopper, donk, magixx, sh1ro, zont1x<br />
Global Rank: [3](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [3]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1927.8<br />
<br />
Final Rank Value (1927.8) = Starting Rank Value (1903.1) + Head To Head Adjustments (24.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.667[<sup>2</sup>](#table1)
- Opponent Network: 0.274[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.735<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1903.1
- 400 + ( ( 0.735 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1903.1


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
|           31 |       22 | 2024-08-03 | Complexity    | W   | 1.000      | 0.581        | 0.310 (0.180)    | 0.380 (0.221)    | 1 (1.000) |     3.75 | chopper, donk, magixx, sh1ro, zont1x |
|           30 |      189 | 2024-07-30 | HEROIC        | W   | 1.000      | 0.581        | 0.229 (0.133)    | 0.374 (0.217)    | 1 (1.000) |     3.86 | chopper, donk, magixx, sh1ro, zont1x |
|           29 |      219 | 2024-07-29 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.19 | chopper, donk, magixx, sh1ro, zont1x |
|           28 |      560 | 2024-07-18 | G2            | L   | 1.000      | -            | -                | -                | -         |   -14.69 | chopper, donk, magixx, sh1ro, zont1x |
|           27 |      641 | 2024-07-17 | MIBR          | W   | 1.000      | 1.000        | 0.209 (0.209)    | 0.659 (0.659)    | 1 (1.000) |     1.45 | chopper, donk, magixx, sh1ro, zont1x |
|           26 |      968 | 2024-06-16 | Natus Vincere | W   | 0.874      | 0.729        | 1.000 (0.638)    | 0.331 (0.211)    | 1 (0.874) |    13.60 | chopper, donk, magixx, sh1ro, zont1x |
|           25 |      999 | 2024-06-15 | Vitality      | W   | 0.868      | 0.729        | 0.649 (0.411)    | 0.383 (0.242)    | 1 (0.868) |    11.58 | chopper, donk, magixx, sh1ro, zont1x |
|           24 |     1063 | 2024-06-13 | Virtus.pro    | W   | 0.856      | 0.729        | 0.497 (0.310)    | 0.323 (0.202)    | 1 (0.856) |     5.39 | chopper, donk, magixx, sh1ro, zont1x |
|           23 |     1094 | 2024-06-12 | G2            | W   | 0.849      | -            | -                | -                | 1 (0.849) |     0.02 | chopper, donk, magixx, sh1ro, zont1x |
|           22 |     1557 | 2024-06-01 | Vitality      | L   | 0.776      | -            | -                | -                | -         |   -14.01 | chopper, donk, magixx, sh1ro, zont1x |
|           21 |     1641 | 2024-05-29 | FaZe          | W   | 0.756      | 0.624        | 0.640 (0.302)    | 0.402 (0.190)    | 1 (0.756) |     6.56 | chopper, donk, magixx, sh1ro, zont1x |
|           20 |     1671 | 2024-05-28 | Natus Vincere | W   | 0.749      | 0.624        | 1.000 (0.467)    | -                | 1 (0.749) |    12.99 | chopper, donk, magixx, sh1ro, zont1x |
|           19 |     1686 | 2024-05-27 | FlyQuest      | W   | 0.743      | -            | -                | -                | -         |     0.49 | chopper, donk, magixx, sh1ro, zont1x |
|           18 |     1909 | 2024-05-19 | MOUZ          | L   | 0.688      | -            | -                | -                | -         |   -11.13 | chopper, donk, magixx, sh1ro, zont1x |
|           17 |     1945 | 2024-05-18 | Falcons       | W   | 0.681      | -            | -                | -                | -         |     1.37 | chopper, donk, magixx, sh1ro, zont1x |
|           16 |     2010 | 2024-05-16 | HEROIC        | W   | 0.668      | 0.769        | -                | 0.374 (0.192)    | -         |     2.57 | chopper, donk, magixx, sh1ro, zont1x |
|           15 |     2068 | 2024-05-15 | Aurora        | W   | 0.660      | 0.769        | 0.424 (0.215)    | 0.793 (0.402)    | -         |     2.90 | chopper, donk, magixx, sh1ro, zont1x |
|           14 |     3259 | 2024-03-28 | FaZe          | L   | 0.342      | -            | -                | -                | -         |    -8.36 | chopper, donk, magixx, sh1ro, zont1x |
|           13 |     3366 | 2024-03-22 | Natus Vincere | W   | 0.302      | 1.000        | 1.000 (0.302)    | -                | -         |     5.71 | chopper, donk, magixx, sh1ro, zont1x |
|           12 |     3380 | 2024-03-21 | Imperial      | W   | 0.296      | 1.000        | -                | 0.685 (0.203)    | -         |     0.27 | chopper, donk, magixx, sh1ro, zont1x |
|           11 |     3390 | 2024-03-21 | Cloud9        | W   | 0.295      | -            | -                | -                | -         |     0.08 | chopper, donk, magixx, sh1ro, zont1x |
|           10 |     3638 | 2024-03-10 | Metizport     | W   | 0.223      | -            | -                | -                | -         |     0.03 | chopper, donk, magixx, sh1ro, zont1x |
|            9 |     3658 | 2024-03-09 | BIG           | W   | 0.216      | -            | -                | -                | -         |     0.23 | chopper, donk, magixx, sh1ro, zont1x |
|            8 |     3693 | 2024-03-08 | Elevate       | W   | 0.208      | -            | -                | -                | -         |     0.04 | chopper, donk, magixx, sh1ro, zont1x |
|            7 |     4048 | 2024-02-21 | HEROIC        | W   | 0.102      | -            | -                | -                | -         |     0.42 | chopper, donk, magixx, sh1ro, zont1x |
|            6 |     4079 | 2024-02-20 | MOUZ          | L   | 0.095      | -            | -                | -                | -         |    -1.75 | chopper, donk, magixx, sh1ro, zont1x |
|            5 |     4098 | 2024-02-19 | Astralis      | W   | 0.089      | -            | -                | -                | -         |     0.64 | chopper, donk, magixx, sh1ro, zont1x |
|            4 |     4113 | 2024-02-19 | ENCE          | W   | 0.087      | -            | -                | -                | -         |     0.22 | chopper, donk, magixx, sh1ro, zont1x |
|            3 |     4298 | 2024-02-11 | FaZe          | W   | 0.035      | -            | -                | -                | -         |     0.25 | chopper, donk, magixx, sh1ro, zont1x |
|            2 |     4305 | 2024-02-10 | Falcons       | W   | 0.029      | -            | -                | -                | -         |     0.06 | chopper, donk, magixx, sh1ro, zont1x |
|            1 |     4354 | 2024-02-06 | FaZe          | W   | 0.002      | -            | -                | -                | -         |     0.01 | chopper, donk, magixx, sh1ro, zont1x |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($356,534.72)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.874 | $200,000.00    | $174,888.89     |
| 2024-06-02 |      0.782 | $20,000.00     | $15,644.44      |
| 2024-05-19 |      0.688 | $100,000.00    | $68,750.00      |
| 2024-03-31 |      0.362 | $45,000.00     | $16,300.00      |
| 2024-03-10 |      0.223 | $20,000.00     | $4,451.39       |
| 2024-02-11 |      0.035 | $400,000.00    | $14,000.00      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
