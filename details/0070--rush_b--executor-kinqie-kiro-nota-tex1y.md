### Roster Details<br />
Team Name: RUSH B<br />
Roster: executor, kinqie, Kiro, nota, tex1y<br />
Global Rank: [70](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [49]( ../standings_europe.md)<br />
<br />
Final Rank Value:  953.1<br />
<br />
Final Rank Value (953.1) = Starting Rank Value (848.9) + Head To Head Adjustments (104.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.360[<sup>1</sup>](#table2)
- Bounty Collected: 0.363[<sup>2</sup>](#table1)
- Opponent Network: 0.155[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.219<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 848.9
- 400 + ( ( 0.219 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 848.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |       15 | 2024-08-03 | Alliance        | W   | 1.000      | 0.342        | 0.017 (0.006)    | 0.313 (0.107)    | 0 (0.000) |    11.90 | executor, kinqie, Kiro, nota, tex1y |
|           29 |       47 | 2024-08-02 | Astralis Talent | W   | 1.000      | 0.342        | -                | 0.168 (0.057)    | 0 (0.000) |     6.97 | executor, kinqie, Kiro, nota, tex1y |
|           28 |      142 | 2024-07-30 | Rebels          | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.605 (0.303)    | 0 (0.000) |    20.15 | executor, kinqie, Kiro, nota, tex1y |
|           27 |      373 | 2024-07-23 | SINNERS         | W   | 1.000      | 0.500        | 0.037 (0.019)    | 0.784 (0.392)    | 0 (0.000) |    18.40 | executor, kinqie, Kiro, nota, tex1y |
|           26 |      497 | 2024-07-19 | SAW             | L   | 1.000      | -            | -                | -                | -         |    -5.18 | executor, kinqie, Kiro, nota, tex1y |
|           25 |      614 | 2024-07-17 | brazylijski luz | L   | 1.000      | -            | -                | -                | -         |   -18.58 | executor, kinqie, Kiro, nota, tex1y |
|           24 |      713 | 2024-07-15 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -5.95 | executor, kinqie, Kiro, nota, tex1y |
|           23 |     1094 | 2024-06-10 | PARIVISION      | L   | 0.839      | -            | -                | -                | -         |    -8.13 | executor, kinqie, Kiro, nota, tex1y |
|           22 |     1102 | 2024-06-10 | SAW             | L   | 0.839      | -            | -                | -                | -         |    -5.73 | executor, kinqie, Kiro, nota, tex1y |
|           21 |     1107 | 2024-06-10 | Monte           | W   | 0.838      | 0.143        | 0.080 (0.010)    | 0.639 (0.076)    | 0 (0.000) |    16.38 | executor, kinqie, Kiro, nota, tex1y |
|           20 |     1135 | 2024-06-09 | 9 Pandas        | W   | 0.833      | 0.143        | 0.082 (0.010)    | 0.715 (0.085)    | 0 (0.000) |    18.42 | executor, kinqie, Kiro, nota, tex1y |
|           19 |     1144 | 2024-06-09 | Aurora          | W   | 0.832      | 0.143        | 0.425 (0.050)    | 0.809 (0.096)    | 0 (0.000) |    25.11 | executor, kinqie, Kiro, nota, tex1y |
|           18 |     1151 | 2024-06-09 | SINNERS         | W   | 0.832      | 0.143        | 0.037 (0.004)    | 0.784 (0.093)    | 0 (0.000) |    18.01 | executor, kinqie, Kiro, nota, tex1y |
|           17 |     1162 | 2024-06-09 | 3DMAX           | L   | 0.831      | -            | -                | -                | -         |    -0.90 | executor, kinqie, Kiro, nota, tex1y |
|           16 |     1308 | 2024-06-06 | Aurora          | L   | 0.813      | -            | -                | -                | -         |    -0.65 | executor, kinqie, Kiro, nota, tex1y |
|           15 |     1371 | 2024-06-05 | SINNERS         | L   | 0.807      | -            | -                | -                | -         |    -8.25 | executor, kinqie, Kiro, nota, tex1y |
|           14 |     1418 | 2024-06-04 | SAW             | W   | 0.800      | 0.500        | 0.106 (0.042)    | 0.560 (0.224)    | 0 (0.000) |    21.76 | executor, kinqie, Kiro, nota, tex1y |
|           13 |     2211 | 2024-05-07 | MOUZ NXT        | L   | 0.612      | -            | -                | -                | -         |    -5.34 | executor, kinqie, Kiro, nota, tex1y |
|           12 |     2240 | 2024-05-05 | Sampi           | L   | 0.600      | -            | -                | -                | -         |    -7.78 | executor, kinqie, Kiro, nota, tex1y |
|           11 |     2261 | 2024-05-04 | HAVU            | W   | 0.593      | -            | -                | -                | 0 (0.000) |     5.60 | executor, kinqie, Kiro, nota, tex1y |
|           10 |     2306 | 2024-05-02 | EYEBALLERS      | L   | 0.579      | -            | -                | -                | -         |    -8.27 | executor, kinqie, Kiro, nota, tex1y |
|            9 |     2363 | 2024-04-29 | ENCE Academy    | W   | 0.561      | -            | -                | -                | -         |     5.70 | executor, kinqie, Kiro, nota, tex1y |
|            8 |     2865 | 2024-04-10 | KOI             | L   | 0.434      | -            | -                | -                | -         |    -5.34 | executor, kinqie, Kiro, nota, tex1y |
|            7 |     2919 | 2024-04-09 | PARIVISION      | W   | 0.427      | 0.500        | 0.018 (0.004)    | 0.553 (0.118)    | -         |    10.64 | executor, kinqie, Kiro, nota, tex1y |
|            6 |     3154 | 2024-04-01 | PERA            | L   | 0.373      | -            | -                | -                | -         |    -5.02 | executor, kinqie, Kiro, nota, tex1y |
|            5 |     3163 | 2024-03-31 | Monte           | W   | 0.366      | 0.500        | 0.060 (0.011)    | -                | -         |     7.91 | executor, kinqie, Kiro, nota, tex1y |
|            4 |     3175 | 2024-03-29 | System5         | W   | 0.354      | -            | -                | -                | -         |     3.07 | executor, kinqie, Kiro, nota, tex1y |
|            3 |     3486 | 2024-03-13 | Betera          | W   | 0.247      | -            | -                | -                | -         |     2.33 | executor, kinqie, Kiro, nota, tex1y |
|            2 |     3749 | 2024-03-03 | Metizport       | L   | 0.180      | -            | -                | -                | -         |    -2.40 | executor, kinqie, Kiro, nota, tex1y |
|            1 |     3860 | 2024-02-26 | SAW             | L   | 0.141      | -            | -                | -                | -         |    -0.63 | executor, kinqie, Kiro, nota, tex1y |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,414.71)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
