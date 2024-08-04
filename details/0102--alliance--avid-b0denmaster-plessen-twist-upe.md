### Roster Details<br />
Team Name: Alliance<br />
Roster: avid, b0denmaster, PlesseN, twist, upE<br />
Global Rank: [102](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [75]( ../standings_europe.md)<br />
<br />
Final Rank Value:  851.5<br />
<br />
Final Rank Value (851.5) = Starting Rank Value (850.1) + Head To Head Adjustments (1.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.332[<sup>2</sup>](#table1)
- Opponent Network: 0.093[<sup>2</sup>](#table1)
- LAN Wins: 0.094[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.1
- 400 + ( ( 0.220 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 850.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           47 |       50 | 2024-08-03 | RUSH B          | L   | 1.000      | -            | -                | -                | -         |   -11.48 | avid, b0denmaster, PlesseN, twist, upE    |
|           46 |      123 | 2024-08-01 | The Suspect     | W   | 1.000      | 0.342        | 0.008 (0.003)    | 0.229 (0.078)    | 0 (0.000) |    16.50 | avid, b0denmaster, PlesseN, twist, upE    |
|           45 |      250 | 2024-07-29 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -10.56 | avid, b0denmaster, PlesseN, twist, upE    |
|           44 |     1065 | 2024-06-14 | MIBR            | L   | 0.860      | -            | -                | -                | -         |    -1.24 | avid, b0denmaster, PlesseN, robiin, twist |
|           43 |     1081 | 2024-06-14 | Complexity      | L   | 0.859      | -            | -                | -                | -         |    -0.38 | avid, b0denmaster, PlesseN, robiin, twist |
|           42 |     1221 | 2024-06-09 | Johnny Speeds   | L   | 0.827      | -            | -                | -                | -         |    -2.79 | avid, b0denmaster, PlesseN, robiin, twist |
|           41 |     1244 | 2024-06-09 | Lilmix          | W   | 0.826      | 0.347        | 0.023 (0.007)    | 0.098 (0.028)    | 1 (0.826) |    13.50 | avid, b0denmaster, PlesseN, robiin, twist |
|           40 |     1640 | 2024-05-31 | VP.Prodigy      | L   | 0.765      | -            | -                | -                | -         |    -9.90 | avid, b0denmaster, PlesseN, robiin, twist |
|           39 |     1777 | 2024-05-24 | B8              | L   | 0.720      | -            | -                | -                | -         |    -3.66 | avid, b0denmaster, PlesseN, robiin, twist |
|           38 |     2151 | 2024-05-14 | kONO            | L   | 0.653      | -            | -                | -                | -         |   -10.65 | avid, b0denmaster, PlesseN, robiin, twist |
|           37 |     2455 | 2024-04-30 | B8              | L   | 0.559      | -            | -                | -                | -         |    -5.30 | avid, b0denmaster, PlesseN, robiin, twist |
|           36 |     2481 | 2024-04-29 | Endpoint        | W   | 0.552      | 0.384        | 0.012 (0.002)    | 0.522 (0.111)    | 0 (0.000) |     9.41 | avid, b0denmaster, PlesseN, robiin, twist |
|           35 |     2494 | 2024-04-28 | DMS             | W   | 0.546      | 0.500        | -                | 0.446 (0.122)    | 0 (0.000) |     9.43 | avid, b0denmaster, PlesseN, robiin, twist |
|           34 |     2533 | 2024-04-26 | B8              | L   | 0.534      | -            | -                | -                | -         |    -4.58 | avid, b0denmaster, PlesseN, robiin, twist |
|           33 |     2608 | 2024-04-23 | Metizport       | L   | 0.513      | -            | -                | -                | -         |    -7.69 | avid, b0denmaster, PlesseN, robiin, twist |
|           32 |     2625 | 2024-04-22 | B8              | W   | 0.506      | 0.384        | 0.165 (0.032)    | 0.912 (0.177)    | 0 (0.000) |    11.72 | avid, b0denmaster, PlesseN, robiin, twist |
|           31 |     2648 | 2024-04-21 | Sangal          | L   | 0.498      | -            | -                | -                | -         |    -2.75 | avid, b0denmaster, PlesseN, robiin, twist |
|           30 |     2729 | 2024-04-19 | 9 Pandas        | W   | 0.485      | 0.500        | 0.081 (0.020)    | 0.690 (0.167)    | 0 (0.000) |    10.31 | avid, b0denmaster, PlesseN, robiin, twist |
|           29 |     2801 | 2024-04-17 | Nemiga          | L   | 0.473      | -            | -                | -                | -         |    -2.24 | avid, b0denmaster, PlesseN, robiin, twist |
|           28 |     2813 | 2024-04-17 | ECLOT           | L   | 0.472      | -            | -                | -                | -         |    -2.05 | avid, b0denmaster, PlesseN, robiin, twist |
|           27 |     2860 | 2024-04-15 | HAVU            | W   | 0.459      | 0.384        | -                | 0.160 (0.028)    | 0 (0.000) |     4.24 | avid, b0denmaster, PlesseN, robiin, twist |
|           26 |     2864 | 2024-04-15 | MOUZ NXT        | L   | 0.458      | -            | -                | -                | -         |    -3.67 | avid, b0denmaster, PlesseN, robiin, twist |
|           25 |     2892 | 2024-04-13 | ALTERNATE aTTaX | L   | 0.445      | -            | -                | -                | -         |    -4.89 | avid, b0denmaster, PlesseN, robiin, twist |
|           24 |     2933 | 2024-04-11 | Zero Tenacity   | W   | 0.433      | 0.384        | 0.137 (0.023)    | 1.000 (0.166)    | 0 (0.000) |    10.55 | avid, b0denmaster, PlesseN, robiin, twist |
|           23 |     3026 | 2024-04-09 | BLEED           | L   | 0.420      | -            | -                | -                | -         |    -4.29 | avid, b0denmaster, PlesseN, robiin, twist |
|           22 |     3042 | 2024-04-09 | Astralis Talent | W   | 0.418      | 0.371        | 0.009 (0.001)    | -                | 0 (0.000) |     5.26 | avid, b0denmaster, PlesseN, robiin, twist |
|           21 |     3087 | 2024-04-07 | Johnny Speeds   | L   | 0.407      | -            | -                | -                | -         |    -1.05 | avid, b0denmaster, PlesseN, robiin, twist |
|           20 |     3090 | 2024-04-07 | EYEBALLERS      | L   | 0.406      | -            | -                | -                | -         |    -5.62 | avid, b0denmaster, PlesseN, robiin, twist |
|           19 |     3099 | 2024-04-06 | Lilmix          | W   | 0.401      | -            | -                | -                | 0 (0.000) |     0.92 | avid, b0denmaster, PlesseN, robiin, twist |
|           18 |     3104 | 2024-04-06 | BetBoom         | L   | 0.399      | -            | -                | -                | -         |    -0.57 | avid, b0denmaster, PlesseN, robiin, twist |
|           17 |     3121 | 2024-04-05 | BLEED           | L   | 0.393      | -            | -                | -                | -         |    -4.18 | avid, b0denmaster, PlesseN, robiin, twist |
|           16 |     3154 | 2024-04-04 | BetBoom         | L   | 0.387      | -            | -                | -                | -         |    -0.57 | avid, b0denmaster, PlesseN, robiin, twist |
|           15 |     3164 | 2024-04-04 | Benched Heroes  | W   | 0.386      | -            | -                | -                | -         |     0.86 | avid, b0denmaster, PlesseN, robiin, twist |
|           14 |     3209 | 2024-04-03 | AMKAL           | L   | 0.379      | -            | -                | -                | -         |    -2.22 | avid, b0denmaster, PlesseN, robiin, twist |
|           13 |     3608 | 2024-03-13 | MOUZ NXT        | L   | 0.239      | -            | -                | -                | -         |    -2.03 | avid, b0denmaster, PlesseN, robiin, twist |
|           12 |     3640 | 2024-03-12 | Passion UA      | L   | 0.232      | -            | -                | -                | -         |    -1.73 | avid, b0denmaster, PlesseN, robiin, twist |
|           11 |     3680 | 2024-03-10 | EYEBALLERS      | W   | 0.220      | -            | -                | -                | -         |     3.88 | avid, b0denmaster, PlesseN, robiin, twist |
|           10 |     3690 | 2024-03-09 | BLUDS           | W   | 0.214      | -            | -                | -                | -         |     0.49 | avid, b0denmaster, PlesseN, robiin, twist |
|            9 |     3704 | 2024-03-09 | Johnny Speeds   | W   | 0.213      | 0.143        | 0.122 (0.004)    | 0.941 (0.029)    | -         |     6.19 | avid, b0denmaster, PlesseN, robiin, twist |
|            8 |     3711 | 2024-03-09 | Entropiq        | W   | 0.212      | -            | -                | -                | -         |     1.05 | avid, b0denmaster, PlesseN, robiin, twist |
|            7 |     3754 | 2024-03-07 | ex-Sprout       | W   | 0.199      | -            | -                | -                | -         |     0.81 | avid, b0denmaster, PlesseN, robiin, twist |
|            6 |     3785 | 2024-03-06 | Sashi           | L   | 0.192      | -            | -                | -                | -         |    -1.01 | avid, b0denmaster, PlesseN, robiin, twist |
|            5 |     3829 | 2024-03-05 | Viperio         | W   | 0.185      | -            | -                | -                | -         |     0.43 | avid, b0denmaster, PlesseN, robiin, twist |
|            4 |     3909 | 2024-03-01 | 9INE            | L   | 0.159      | -            | -                | -                | -         |    -4.41 | avid, b0denmaster, PlesseN, robiin, twist |
|            3 |     3936 | 2024-02-28 | Sangal          | W   | 0.145      | 0.143        | 0.219 (0.005)    | -                | -         |     3.88 | avid, b0denmaster, PlesseN, robiin, twist |
|            2 |     3991 | 2024-02-25 | ALTERNATE aTTaX | W   | 0.127      | 0.358        | 0.031 (0.001)    | 0.560 (0.025)    | -         |     2.71 | avid, b0denmaster, PlesseN, robiin, twist |
|            1 |     4162 | 2024-02-18 | Portugal        | W   | 0.079      | -            | -                | -                | -         |     0.71 | avid, b0denmaster, PlesseN, robiin, twist |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,474.13)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-16 |      0.873 | $2,000.00      | $1,745.93       |
| 2024-06-09 |      0.827 | $2,889.00      | $2,387.97       |
| 2024-05-18 |      0.680 | $500.00        | $340.23         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
