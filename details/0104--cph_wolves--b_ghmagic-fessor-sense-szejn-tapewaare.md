### Roster Details<br />
Team Name: CPH Wolves<br />
Roster: BøghmagiC, Fessor, sense, szejn, Tapewaare<br />
Global Rank: [104](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [75]( ../standings_europe.md)<br />
<br />
Final Rank Value:  812.2<br />
<br />
Final Rank Value (812.2) = Starting Rank Value (781.3) + Head To Head Adjustments (31.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.283[<sup>1</sup>](#table2)
- Bounty Collected: 0.344[<sup>2</sup>](#table1)
- Opponent Network: 0.160[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.197<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 781.3
- 400 + ( ( 0.197 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 781.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |       15 | 2024-09-07 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |    -9.17 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           35 |       78 | 2024-09-05 | UNiTY             | W   | 1.000      | 0.372        | 0.026 (0.010)    | 0.394 (0.147)    | 0 (0.000) |    21.19 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           34 |      146 | 2024-09-03 | L&G               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.95 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           33 |      194 | 2024-09-01 | Monte Gen         | L   | 1.000      | -            | -                | -                | -         |   -11.51 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           32 |      199 | 2024-09-01 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |    -8.88 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           31 |      228 | 2024-08-30 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -10.10 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           30 |      320 | 2024-08-28 | Aurora Young Blud | W   | 1.000      | 0.435        | 0.019 (0.008)    | 0.711 (0.309)    | 0 (0.000) |    19.17 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           29 |      373 | 2024-08-27 | Sampi             | L   | 1.000      | -            | -                | -                | -         |   -10.76 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           28 |      530 | 2024-08-24 | The Suspect       | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.263 (0.038)    | 0 (0.000) |    16.46 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           27 |      545 | 2024-08-23 | Spirit Academy    | W   | 1.000      | 0.143        | 0.011 (0.002)    | 0.308 (0.044)    | 0 (0.000) |    14.70 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           26 |      585 | 2024-08-22 | Preasy            | W   | 1.000      | 0.143        | 0.007 (0.001)    | -                | 0 (0.000) |    10.48 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           25 |      615 | 2024-08-21 | Spirit Academy    | L   | 1.000      | -            | -                | -                | -         |   -15.85 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           24 |      940 | 2024-08-12 | Young Ninjas      | L   | 1.000      | -            | -                | -                | -         |   -12.37 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           23 |     1178 | 2024-08-04 | The Suspect       | L   | 0.966      | -            | -                | -                | -         |   -14.53 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           22 |     1370 | 2024-07-30 | Passion UA        | L   | 0.934      | -            | -                | -                | -         |    -5.82 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           21 |     1436 | 2024-07-28 | Sampi             | L   | 0.921      | -            | -                | -                | -         |   -11.70 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           20 |     1461 | 2024-07-27 | 1WIN              | L   | 0.914      | -            | -                | -                | -         |   -10.91 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           19 |     1571 | 2024-07-24 | Space             | W   | 0.892      | 0.435        | 0.004 (0.002)    | 0.463 (0.180)    | 0 (0.000) |    15.84 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           18 |     1597 | 2024-07-23 | Sampi             | L   | 0.888      | -            | -                | -                | -         |   -12.02 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           17 |     1619 | 2024-07-22 | TSM               | W   | 0.882      | 0.143        | 0.058 (0.007)    | 0.900 (0.113)    | 0 (0.000) |    21.04 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           16 |     1629 | 2024-07-22 | SINNERS           | L   | 0.880      | -            | -                | -                | -         |    -7.07 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           15 |     1674 | 2024-07-20 | INFINITE          | W   | 0.868      | -            | -                | -                | 0 (0.000) |     5.33 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           14 |     1686 | 2024-07-20 | Space             | L   | 0.867      | -            | -                | -                | -         |   -11.61 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           13 |     1721 | 2024-07-19 | Heimo             | W   | 0.861      | -            | -                | -                | 0 (0.000) |     6.39 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           12 |     1794 | 2024-07-18 | Passion UA        | W   | 0.852      | 0.435        | 0.164 (0.061)    | 1.000 (0.370)    | -         |    20.32 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           11 |     1897 | 2024-07-16 | 9INE              | L   | 0.841      | -            | -                | -                | -         |   -10.11 | BøghmagiC, Fessor, sense, shadiy, Tapewaare |
|           10 |     1953 | 2024-07-15 | GUN5              | W   | 0.833      | 0.435        | 0.091 (0.033)    | 0.959 (0.347)    | -         |    19.41 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|            9 |     2172 | 2024-06-16 | 777               | W   | 0.640      | 0.143        | 0.010 (0.001)    | -                | -         |     7.01 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            8 |     2240 | 2024-06-14 | FLuffy Gangsters  | W   | 0.627      | 0.143        | -                | 0.357 (0.032)    | -         |     5.13 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            7 |     2281 | 2024-06-13 | INFINITE          | W   | 0.620      | -            | -                | -                | -         |     3.96 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            6 |     2296 | 2024-06-12 | Sashi             | L   | 0.615      | -            | -                | -                | -         |    -2.66 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            5 |     2306 | 2024-06-12 | WOPA              | W   | 0.614      | 0.340        | -                | 0.119 (0.025)    | -         |     5.83 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            4 |     3143 | 2024-05-18 | VP.Prodigy        | L   | 0.446      | -            | -                | -                | -         |    -6.18 | Basso, BøghmagiC, Fessor, szejn, vigg0      |
|            3 |     3169 | 2024-05-17 | MASONIC           | W   | 0.441      | -            | -                | -                | -         |     5.24 | Basso, BøghmagiC, Fessor, szejn, vigg0      |
|            2 |     3205 | 2024-05-16 | Rhyno             | L   | 0.434      | -            | -                | -                | -         |    -5.23 | Basso, BøghmagiC, Fessor, szejn, vigg0      |
|            1 |     3262 | 2024-05-15 | MASONIC           | W   | 0.427      | -            | -                | -                | -         |     5.00 | Basso, BøghmagiC, Fessor, szejn, vigg0      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($885.51)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
