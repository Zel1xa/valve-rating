### Roster Details<br />
Team Name: RUSH B<br />
Roster: executor, kinqie, Kiro, nota, tex1y<br />
Global Rank: [70](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [49]( ../standings_europe.md)<br />
<br />
Final Rank Value:  953.3<br />
<br />
Final Rank Value (953.3) = Starting Rank Value (845.9) + Head To Head Adjustments (107.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.360[<sup>1</sup>](#table2)
- Bounty Collected: 0.363[<sup>2</sup>](#table1)
- Opponent Network: 0.151[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.218<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 845.9
- 400 + ( ( 0.218 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 845.9


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
|           30 |       18 | 2024-08-03 | Alliance        | W   | 1.000      | 0.342        | 0.017 (0.006)    | 0.302 (0.103)    | 0 (0.000) |    11.84 | executor, kinqie, Kiro, nota, tex1y |
|           29 |       56 | 2024-08-02 | Astralis Talent | W   | 1.000      | 0.342        | -                | 0.162 (0.056)    | 0 (0.000) |     6.81 | executor, kinqie, Kiro, nota, tex1y |
|           28 |      165 | 2024-07-30 | Rebels          | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.599 (0.299)    | 0 (0.000) |    19.93 | executor, kinqie, Kiro, nota, tex1y |
|           27 |      395 | 2024-07-23 | SINNERS         | W   | 1.000      | 0.500        | 0.037 (0.019)    | 0.758 (0.379)    | 0 (0.000) |    18.47 | executor, kinqie, Kiro, nota, tex1y |
|           26 |      519 | 2024-07-19 | SAW             | L   | 1.000      | -            | -                | -                | -         |    -5.08 | executor, kinqie, Kiro, nota, tex1y |
|           25 |      635 | 2024-07-17 | brazylijski luz | L   | 1.000      | -            | -                | -                | -         |   -18.66 | executor, kinqie, Kiro, nota, tex1y |
|           24 |      737 | 2024-07-15 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -5.20 | executor, kinqie, Kiro, nota, tex1y |
|           23 |     1148 | 2024-06-10 | PARIVISION      | L   | 0.837      | -            | -                | -                | -         |    -8.07 | executor, kinqie, Kiro, nota, tex1y |
|           22 |     1156 | 2024-06-10 | SAW             | L   | 0.837      | -            | -                | -                | -         |    -5.61 | executor, kinqie, Kiro, nota, tex1y |
|           21 |     1161 | 2024-06-10 | Monte           | W   | 0.836      | 0.143        | 0.080 (0.010)    | 0.618 (0.074)    | 0 (0.000) |    16.62 | executor, kinqie, Kiro, nota, tex1y |
|           20 |     1190 | 2024-06-09 | 9 Pandas        | W   | 0.831      | 0.143        | 0.082 (0.010)    | 0.691 (0.082)    | 0 (0.000) |    18.48 | executor, kinqie, Kiro, nota, tex1y |
|           19 |     1199 | 2024-06-09 | Aurora          | W   | 0.831      | 0.143        | 0.424 (0.050)    | 0.794 (0.094)    | 0 (0.000) |    25.05 | executor, kinqie, Kiro, nota, tex1y |
|           18 |     1206 | 2024-06-09 | SINNERS         | W   | 0.830      | 0.143        | 0.037 (0.004)    | 0.758 (0.090)    | 0 (0.000) |    18.07 | executor, kinqie, Kiro, nota, tex1y |
|           17 |     1217 | 2024-06-09 | 3DMAX           | L   | 0.830      | -            | -                | -                | -         |    -0.86 | executor, kinqie, Kiro, nota, tex1y |
|           16 |     1368 | 2024-06-06 | Aurora          | L   | 0.812      | -            | -                | -                | -         |    -0.65 | executor, kinqie, Kiro, nota, tex1y |
|           15 |     1431 | 2024-06-05 | SINNERS         | L   | 0.805      | -            | -                | -                | -         |    -8.27 | executor, kinqie, Kiro, nota, tex1y |
|           14 |     1479 | 2024-06-04 | SAW             | W   | 0.798      | 0.500        | 0.106 (0.042)    | 0.541 (0.216)    | 0 (0.000) |    21.78 | executor, kinqie, Kiro, nota, tex1y |
|           13 |     2277 | 2024-05-07 | MOUZ NXT        | L   | 0.611      | -            | -                | -                | -         |    -5.25 | executor, kinqie, Kiro, nota, tex1y |
|           12 |     2306 | 2024-05-05 | Sampi           | L   | 0.598      | -            | -                | -                | -         |    -7.80 | executor, kinqie, Kiro, nota, tex1y |
|           11 |     2327 | 2024-05-04 | HAVU            | W   | 0.591      | -            | -                | -                | 0 (0.000) |     5.58 | executor, kinqie, Kiro, nota, tex1y |
|           10 |     2372 | 2024-05-02 | EYEBALLERS      | L   | 0.577      | -            | -                | -                | -         |    -8.22 | executor, kinqie, Kiro, nota, tex1y |
|            9 |     2429 | 2024-04-29 | ENCE Academy    | W   | 0.559      | -            | -                | -                | -         |     5.49 | executor, kinqie, Kiro, nota, tex1y |
|            8 |     2931 | 2024-04-10 | KOI             | L   | 0.432      | -            | -                | -                | -         |    -3.09 | executor, kinqie, Kiro, nota, tex1y |
|            7 |     2985 | 2024-04-09 | PARIVISION      | W   | 0.425      | 0.500        | 0.017 (0.004)    | 0.534 (0.114)    | -         |    10.59 | executor, kinqie, Kiro, nota, tex1y |
|            6 |     3220 | 2024-04-01 | PERA            | L   | 0.371      | -            | -                | -                | -         |    -4.94 | executor, kinqie, Kiro, nota, tex1y |
|            5 |     3229 | 2024-03-31 | Monte           | W   | 0.365      | 0.500        | 0.060 (0.011)    | -                | -         |     7.88 | executor, kinqie, Kiro, nota, tex1y |
|            4 |     3241 | 2024-03-29 | System5         | W   | 0.352      | -            | -                | -                | -         |     3.08 | executor, kinqie, Kiro, nota, tex1y |
|            3 |     3558 | 2024-03-13 | Betera          | W   | 0.246      | -            | -                | -                | -         |     2.34 | executor, kinqie, Kiro, nota, tex1y |
|            2 |     3822 | 2024-03-03 | Metizport       | L   | 0.178      | -            | -                | -                | -         |    -2.36 | executor, kinqie, Kiro, nota, tex1y |
|            1 |     3933 | 2024-02-26 | SAW             | L   | 0.139      | -            | -                | -                | -         |    -0.62 | executor, kinqie, Kiro, nota, tex1y |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,403.58)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
