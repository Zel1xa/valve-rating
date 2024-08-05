### Roster Details<br />
Team Name: Spirit<br />
Roster: chopper, donk, magixx, sh1ro, zont1x<br />
Global Rank: [2](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [2]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1929.8<br />
<br />
Final Rank Value (1929.8) = Starting Rank Value (1904.5) + Head To Head Adjustments (25.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.667[<sup>2</sup>](#table1)
- Opponent Network: 0.275[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.735<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1904.5
- 400 + ( ( 0.735 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1904.5


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
|           30 |       57 | 2024-08-03 | Complexity    | W   | 1.000      | 0.581        | 0.342 (0.199)    | 0.380 (0.221)    | 1 (1.000) |     3.87 | chopper, donk, magixx, sh1ro, zont1x |
|           29 |      224 | 2024-07-30 | HEROIC        | W   | 1.000      | 0.581        | 0.226 (0.131)    | 0.372 (0.216)    | 1 (1.000) |     3.92 | chopper, donk, magixx, sh1ro, zont1x |
|           28 |      254 | 2024-07-29 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.19 | chopper, donk, magixx, sh1ro, zont1x |
|           27 |      596 | 2024-07-18 | G2            | L   | 1.000      | -            | -                | -                | -         |   -14.66 | chopper, donk, magixx, sh1ro, zont1x |
|           26 |      674 | 2024-07-17 | MIBR          | W   | 1.000      | 1.000        | 0.209 (0.209)    | 0.659 (0.659)    | 1 (1.000) |     1.44 | chopper, donk, magixx, sh1ro, zont1x |
|           25 |     1004 | 2024-06-16 | Natus Vincere | W   | 0.870      | 0.729        | 1.000 (0.634)    | 0.371 (0.235)    | 1 (0.870) |    13.63 | chopper, donk, magixx, sh1ro, zont1x |
|           24 |     1035 | 2024-06-15 | Vitality      | W   | 0.864      | 0.729        | 0.648 (0.408)    | 0.382 (0.241)    | 1 (0.864) |    11.62 | chopper, donk, magixx, sh1ro, zont1x |
|           23 |     1099 | 2024-06-13 | Virtus.pro    | W   | 0.852      | 0.729        | 0.497 (0.309)    | 0.323 (0.200)    | 1 (0.852) |     5.40 | chopper, donk, magixx, sh1ro, zont1x |
|           22 |     1130 | 2024-06-12 | G2            | W   | 0.845      | -            | -                | -                | 1 (0.845) |     0.02 | chopper, donk, magixx, sh1ro, zont1x |
|           21 |     1593 | 2024-06-01 | Vitality      | L   | 0.771      | -            | -                | -                | -         |   -13.84 | chopper, donk, magixx, sh1ro, zont1x |
|           20 |     1677 | 2024-05-29 | FaZe          | W   | 0.752      | 0.624        | 0.635 (0.298)    | 0.401 (0.188)    | 1 (0.752) |     6.57 | chopper, donk, magixx, sh1ro, zont1x |
|           19 |     1707 | 2024-05-28 | Natus Vincere | W   | 0.744      | 0.624        | 1.000 (0.465)    | -                | 1 (0.744) |    12.97 | chopper, donk, magixx, sh1ro, zont1x |
|           18 |     1722 | 2024-05-27 | FlyQuest      | W   | 0.739      | -            | -                | -                | -         |     0.49 | chopper, donk, magixx, sh1ro, zont1x |
|           17 |     1945 | 2024-05-19 | MOUZ          | L   | 0.683      | -            | -                | -                | -         |   -11.04 | chopper, donk, magixx, sh1ro, zont1x |
|           16 |     1981 | 2024-05-18 | Falcons       | W   | 0.676      | -            | -                | -                | -         |     1.34 | chopper, donk, magixx, sh1ro, zont1x |
|           15 |     2046 | 2024-05-16 | HEROIC        | W   | 0.664      | 0.769        | -                | 0.372 (0.190)    | -         |     2.57 | chopper, donk, magixx, sh1ro, zont1x |
|           14 |     2104 | 2024-05-15 | Aurora        | W   | 0.656      | 0.769        | 0.423 (0.213)    | 0.792 (0.399)    | -         |     2.90 | chopper, donk, magixx, sh1ro, zont1x |
|           13 |     3295 | 2024-03-28 | FaZe          | L   | 0.338      | -            | -                | -                | -         |    -8.28 | chopper, donk, magixx, sh1ro, zont1x |
|           12 |     3402 | 2024-03-22 | Natus Vincere | W   | 0.298      | 1.000        | 1.000 (0.298)    | -                | -         |     5.65 | chopper, donk, magixx, sh1ro, zont1x |
|           11 |     3416 | 2024-03-21 | Imperial      | W   | 0.292      | 1.000        | -                | 0.685 (0.200)    | -         |     0.26 | chopper, donk, magixx, sh1ro, zont1x |
|           10 |     3426 | 2024-03-21 | Cloud9        | W   | 0.291      | -            | -                | -                | -         |     0.08 | chopper, donk, magixx, sh1ro, zont1x |
|            9 |     3674 | 2024-03-10 | Metizport     | W   | 0.218      | -            | -                | -                | -         |     0.02 | chopper, donk, magixx, sh1ro, zont1x |
|            8 |     3694 | 2024-03-09 | BIG           | W   | 0.212      | -            | -                | -                | -         |     0.22 | chopper, donk, magixx, sh1ro, zont1x |
|            7 |     3729 | 2024-03-08 | Elevate       | W   | 0.204      | -            | -                | -                | -         |     0.04 | chopper, donk, magixx, sh1ro, zont1x |
|            6 |     4084 | 2024-02-21 | HEROIC        | W   | 0.098      | -            | -                | -                | -         |     0.40 | chopper, donk, magixx, sh1ro, zont1x |
|            5 |     4115 | 2024-02-20 | MOUZ          | L   | 0.091      | -            | -                | -                | -         |    -1.68 | chopper, donk, magixx, sh1ro, zont1x |
|            4 |     4134 | 2024-02-19 | Astralis      | W   | 0.085      | -            | -                | -                | -         |     0.74 | chopper, donk, magixx, sh1ro, zont1x |
|            3 |     4149 | 2024-02-19 | ENCE          | W   | 0.083      | -            | -                | -                | -         |     0.21 | chopper, donk, magixx, sh1ro, zont1x |
|            2 |     4334 | 2024-02-11 | FaZe          | W   | 0.031      | -            | -                | -                | -         |     0.22 | chopper, donk, magixx, sh1ro, zont1x |
|            1 |     4341 | 2024-02-10 | Falcons       | W   | 0.025      | -            | -                | -                | -         |     0.05 | chopper, donk, magixx, sh1ro, zont1x |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($353,263.89)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $22,500.00     | $22,500.00      |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.870 | $200,000.00    | $174,055.56     |
| 2024-06-02 |      0.778 | $20,000.00     | $15,561.11      |
| 2024-05-19 |      0.683 | $100,000.00    | $68,333.33      |
| 2024-03-31 |      0.358 | $45,000.00     | $16,112.50      |
| 2024-03-10 |      0.218 | $20,000.00     | $4,368.06       |
| 2024-02-11 |      0.031 | $400,000.00    | $12,333.33      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
