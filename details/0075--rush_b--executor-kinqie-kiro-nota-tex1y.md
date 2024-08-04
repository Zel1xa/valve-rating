### Roster Details<br />
Team Name: RUSH B<br />
Roster: executor, kinqie, Kiro, nota, tex1y<br />
Global Rank: [75](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
<br />
Final Rank Value:  944.5<br />
<br />
Final Rank Value (944.5) = Starting Rank Value (859.4) + Head To Head Adjustments (85.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.386[<sup>1</sup>](#table2)
- Bounty Collected: 0.362[<sup>2</sup>](#table1)
- Opponent Network: 0.150[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.225<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 859.4
- 400 + ( ( 0.225 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 859.4


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
|           31 |        2 | 2024-08-04 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -15.79 | executor, kinqie, Kiro, nota, tex1y |
|           30 |       29 | 2024-08-03 | Alliance        | W   | 1.000      | 0.342        | 0.017 (0.006)    | 0.300 (0.103)    | 0 (0.000) |    11.54 | executor, kinqie, Kiro, nota, tex1y |
|           29 |       67 | 2024-08-02 | Astralis Talent | W   | 1.000      | 0.342        | -                | 0.162 (0.056)    | 0 (0.000) |     6.65 | executor, kinqie, Kiro, nota, tex1y |
|           28 |      176 | 2024-07-30 | Rebels          | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.599 (0.300)    | 0 (0.000) |    19.63 | executor, kinqie, Kiro, nota, tex1y |
|           27 |      406 | 2024-07-23 | SINNERS         | W   | 1.000      | 0.500        | 0.037 (0.019)    | 0.757 (0.379)    | 0 (0.000) |    18.43 | executor, kinqie, Kiro, nota, tex1y |
|           26 |      530 | 2024-07-19 | SAW             | L   | 1.000      | -            | -                | -                | -         |    -5.26 | executor, kinqie, Kiro, nota, tex1y |
|           25 |      646 | 2024-07-17 | brazylijski luz | L   | 1.000      | -            | -                | -                | -         |   -18.96 | executor, kinqie, Kiro, nota, tex1y |
|           24 |      748 | 2024-07-15 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -5.39 | executor, kinqie, Kiro, nota, tex1y |
|           23 |     1160 | 2024-06-10 | PARIVISION      | L   | 0.833      | -            | -                | -                | -         |    -8.29 | executor, kinqie, Kiro, nota, tex1y |
|           22 |     1168 | 2024-06-10 | SAW             | L   | 0.833      | -            | -                | -                | -         |    -5.80 | executor, kinqie, Kiro, nota, tex1y |
|           21 |     1173 | 2024-06-10 | Monte           | W   | 0.833      | 0.143        | 0.080 (0.010)    | 0.619 (0.074)    | 0 (0.000) |    16.25 | executor, kinqie, Kiro, nota, tex1y |
|           20 |     1202 | 2024-06-09 | 9 Pandas        | W   | 0.827      | 0.143        | 0.082 (0.010)    | 0.690 (0.082)    | 0 (0.000) |    17.99 | executor, kinqie, Kiro, nota, tex1y |
|           19 |     1211 | 2024-06-09 | Aurora          | W   | 0.827      | 0.143        | 0.423 (0.050)    | 0.793 (0.094)    | 0 (0.000) |    24.90 | executor, kinqie, Kiro, nota, tex1y |
|           18 |     1218 | 2024-06-09 | SINNERS         | W   | 0.826      | 0.143        | 0.037 (0.004)    | 0.757 (0.089)    | 0 (0.000) |    17.70 | executor, kinqie, Kiro, nota, tex1y |
|           17 |     1229 | 2024-06-09 | 3DMAX           | L   | 0.826      | -            | -                | -                | -         |    -0.89 | executor, kinqie, Kiro, nota, tex1y |
|           16 |     1380 | 2024-06-06 | Aurora          | L   | 0.808      | -            | -                | -                | -         |    -0.68 | executor, kinqie, Kiro, nota, tex1y |
|           15 |     1443 | 2024-06-05 | SINNERS         | L   | 0.801      | -            | -                | -                | -         |    -8.54 | executor, kinqie, Kiro, nota, tex1y |
|           14 |     1491 | 2024-06-04 | SAW             | W   | 0.795      | 0.500        | 0.105 (0.042)    | 0.540 (0.214)    | 0 (0.000) |    21.50 | executor, kinqie, Kiro, nota, tex1y |
|           13 |     2289 | 2024-05-07 | MOUZ NXT        | L   | 0.607      | -            | -                | -                | -         |    -5.45 | executor, kinqie, Kiro, nota, tex1y |
|           12 |     2318 | 2024-05-05 | Sampi           | L   | 0.594      | -            | -                | -                | -         |    -8.05 | executor, kinqie, Kiro, nota, tex1y |
|           11 |     2339 | 2024-05-04 | HAVU            | W   | 0.587      | -            | -                | -                | 0 (0.000) |     5.30 | executor, kinqie, Kiro, nota, tex1y |
|           10 |     2384 | 2024-05-02 | EYEBALLERS      | L   | 0.573      | -            | -                | -                | -         |    -8.47 | executor, kinqie, Kiro, nota, tex1y |
|            9 |     2441 | 2024-04-29 | ENCE Academy    | W   | 0.555      | -            | -                | -                | -         |     5.20 | executor, kinqie, Kiro, nota, tex1y |
|            8 |     2944 | 2024-04-10 | KOI             | L   | 0.428      | -            | -                | -                | -         |    -3.25 | executor, kinqie, Kiro, nota, tex1y |
|            7 |     2998 | 2024-04-09 | PARIVISION      | W   | 0.422      | 0.500        | 0.017 (0.004)    | 0.534 (0.113)    | -         |    10.34 | executor, kinqie, Kiro, nota, tex1y |
|            6 |     3233 | 2024-04-01 | PERA            | L   | 0.368      | -            | -                | -                | -         |    -5.05 | executor, kinqie, Kiro, nota, tex1y |
|            5 |     3242 | 2024-03-31 | Monte           | W   | 0.361      | 0.500        | 0.058 (0.010)    | -                | -         |     7.58 | executor, kinqie, Kiro, nota, tex1y |
|            4 |     3254 | 2024-03-29 | System5         | W   | 0.348      | -            | -                | -                | -         |     2.89 | executor, kinqie, Kiro, nota, tex1y |
|            3 |     3571 | 2024-03-13 | Betera          | W   | 0.242      | -            | -                | -                | -         |     2.18 | executor, kinqie, Kiro, nota, tex1y |
|            2 |     3836 | 2024-03-03 | Metizport       | L   | 0.175      | -            | -                | -                | -         |    -2.41 | executor, kinqie, Kiro, nota, tex1y |
|            1 |     3947 | 2024-02-26 | SAW             | L   | 0.135      | -            | -                | -                | -         |    -0.65 | executor, kinqie, Kiro, nota, tex1y |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,379.05)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-09 |      0.828 | $6,500.00      | $5,379.05       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
