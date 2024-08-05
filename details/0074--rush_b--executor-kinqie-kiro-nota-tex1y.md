### Roster Details<br />
Team Name: RUSH B<br />
Roster: executor, kinqie, Kiro, nota, tex1y<br />
Global Rank: [74](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [52]( ../standings_europe.md)<br />
<br />
Final Rank Value:  945.9<br />
<br />
Final Rank Value (945.9) = Starting Rank Value (860.6) + Head To Head Adjustments (85.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.386[<sup>1</sup>](#table2)
- Bounty Collected: 0.361[<sup>2</sup>](#table1)
- Opponent Network: 0.152[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.225<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 860.6
- 400 + ( ( 0.225 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 860.6


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
|           31 |       30 | 2024-08-04 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -16.12 | executor, kinqie, Kiro, nota, tex1y |
|           30 |       68 | 2024-08-03 | Alliance        | W   | 1.000      | 0.342        | 0.017 (0.006)    | 0.296 (0.101)    | 0 (0.000) |    11.48 | executor, kinqie, Kiro, nota, tex1y |
|           29 |      106 | 2024-08-02 | Astralis Talent | W   | 1.000      | 0.342        | -                | 0.162 (0.055)    | 0 (0.000) |     6.61 | executor, kinqie, Kiro, nota, tex1y |
|           28 |      217 | 2024-07-30 | Rebels          | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.598 (0.299)    | 0 (0.000) |    19.58 | executor, kinqie, Kiro, nota, tex1y |
|           27 |      448 | 2024-07-23 | SINNERS         | W   | 1.000      | 0.500        | 0.037 (0.019)    | 0.794 (0.397)    | 0 (0.000) |    18.98 | executor, kinqie, Kiro, nota, tex1y |
|           26 |      572 | 2024-07-19 | SAW             | L   | 1.000      | -            | -                | -                | -         |    -5.27 | executor, kinqie, Kiro, nota, tex1y |
|           25 |      690 | 2024-07-17 | brazylijski luz | L   | 1.000      | -            | -                | -                | -         |   -19.01 | executor, kinqie, Kiro, nota, tex1y |
|           24 |      791 | 2024-07-15 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -5.33 | executor, kinqie, Kiro, nota, tex1y |
|           23 |     1201 | 2024-06-10 | PARIVISION      | L   | 0.827      | -            | -                | -                | -         |    -8.14 | executor, kinqie, Kiro, nota, tex1y |
|           22 |     1209 | 2024-06-10 | SAW             | L   | 0.826      | -            | -                | -                | -         |    -5.79 | executor, kinqie, Kiro, nota, tex1y |
|           21 |     1214 | 2024-06-10 | Monte           | W   | 0.826      | 0.143        | 0.080 (0.009)    | 0.618 (0.073)    | 0 (0.000) |    16.12 | executor, kinqie, Kiro, nota, tex1y |
|           20 |     1243 | 2024-06-09 | 9 Pandas        | W   | 0.820      | 0.143        | 0.081 (0.010)    | 0.727 (0.085)    | 0 (0.000) |    17.82 | executor, kinqie, Kiro, nota, tex1y |
|           19 |     1252 | 2024-06-09 | Aurora          | W   | 0.820      | 0.143        | 0.422 (0.049)    | 0.788 (0.092)    | 0 (0.000) |    24.71 | executor, kinqie, Kiro, nota, tex1y |
|           18 |     1259 | 2024-06-09 | SINNERS         | W   | 0.820      | 0.143        | 0.037 (0.004)    | 0.794 (0.093)    | 0 (0.000) |    18.17 | executor, kinqie, Kiro, nota, tex1y |
|           17 |     1270 | 2024-06-09 | 3DMAX           | L   | 0.819      | -            | -                | -                | -         |    -0.87 | executor, kinqie, Kiro, nota, tex1y |
|           16 |     1421 | 2024-06-06 | Aurora          | L   | 0.801      | -            | -                | -                | -         |    -0.66 | executor, kinqie, Kiro, nota, tex1y |
|           15 |     1484 | 2024-06-05 | SINNERS         | L   | 0.794      | -            | -                | -                | -         |    -7.75 | executor, kinqie, Kiro, nota, tex1y |
|           14 |     1532 | 2024-06-04 | SAW             | W   | 0.788      | 0.500        | 0.105 (0.041)    | 0.537 (0.211)    | 0 (0.000) |    21.28 | executor, kinqie, Kiro, nota, tex1y |
|           13 |     2330 | 2024-05-07 | MOUZ NXT        | L   | 0.600      | -            | -                | -                | -         |    -5.34 | executor, kinqie, Kiro, nota, tex1y |
|           12 |     2359 | 2024-05-05 | Sampi           | L   | 0.588      | -            | -                | -                | -         |    -7.98 | executor, kinqie, Kiro, nota, tex1y |
|           11 |     2380 | 2024-05-04 | HAVU            | W   | 0.581      | -            | -                | -                | 0 (0.000) |     5.22 | executor, kinqie, Kiro, nota, tex1y |
|           10 |     2425 | 2024-05-02 | EYEBALLERS      | L   | 0.566      | -            | -                | -                | -         |    -8.42 | executor, kinqie, Kiro, nota, tex1y |
|            9 |     2482 | 2024-04-29 | ENCE Academy    | W   | 0.548      | -            | -                | -                | -         |     5.12 | executor, kinqie, Kiro, nota, tex1y |
|            8 |     2985 | 2024-04-10 | KOI             | L   | 0.421      | -            | -                | -                | -         |    -3.22 | executor, kinqie, Kiro, nota, tex1y |
|            7 |     3039 | 2024-04-09 | PARIVISION      | W   | 0.415      | 0.500        | 0.017 (0.004)    | 0.532 (0.110)    | -         |    10.21 | executor, kinqie, Kiro, nota, tex1y |
|            6 |     3274 | 2024-04-01 | PERA            | L   | 0.361      | -            | -                | -                | -         |    -4.95 | executor, kinqie, Kiro, nota, tex1y |
|            5 |     3283 | 2024-03-31 | Monte           | W   | 0.354      | 0.500        | 0.057 (0.010)    | -                | -         |     7.39 | executor, kinqie, Kiro, nota, tex1y |
|            4 |     3295 | 2024-03-29 | System5         | W   | 0.342      | -            | -                | -                | -         |     2.82 | executor, kinqie, Kiro, nota, tex1y |
|            3 |     3612 | 2024-03-13 | Betera          | W   | 0.235      | -            | -                | -                | -         |     2.11 | executor, kinqie, Kiro, nota, tex1y |
|            2 |     3877 | 2024-03-03 | Metizport       | L   | 0.168      | -            | -                | -                | -         |    -2.83 | executor, kinqie, Kiro, nota, tex1y |
|            1 |     3988 | 2024-02-26 | SAW             | L   | 0.128      | -            | -                | -                | -         |    -0.62 | executor, kinqie, Kiro, nota, tex1y |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,334.97)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-09 |      0.821 | $6,500.00      | $5,334.97       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
