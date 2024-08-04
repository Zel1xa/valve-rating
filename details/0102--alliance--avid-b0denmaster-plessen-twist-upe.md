### Roster Details<br />
Team Name: Alliance<br />
Roster: avid, b0denmaster, PlesseN, twist, upE<br />
Global Rank: [102](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [75]( ../standings_europe.md)<br />
<br />
Final Rank Value:  851.8<br />
<br />
Final Rank Value (851.8) = Starting Rank Value (850.5) + Head To Head Adjustments (1.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.332[<sup>2</sup>](#table1)
- Opponent Network: 0.094[<sup>2</sup>](#table1)
- LAN Wins: 0.094[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.5
- 400 + ( ( 0.220 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 850.5


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
|           47 |       51 | 2024-08-03 | RUSH B          | L   | 1.000      | -            | -                | -                | -         |   -11.48 | avid, b0denmaster, PlesseN, twist, upE    |
|           46 |      124 | 2024-08-01 | The Suspect     | W   | 1.000      | 0.342        | 0.008 (0.003)    | 0.229 (0.078)    | 0 (0.000) |    16.49 | avid, b0denmaster, PlesseN, twist, upE    |
|           45 |      251 | 2024-07-29 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -10.56 | avid, b0denmaster, PlesseN, twist, upE    |
|           44 |     1066 | 2024-06-14 | MIBR            | L   | 0.860      | -            | -                | -                | -         |    -1.24 | avid, b0denmaster, PlesseN, robiin, twist |
|           43 |     1082 | 2024-06-14 | Complexity      | L   | 0.859      | -            | -                | -                | -         |    -0.38 | avid, b0denmaster, PlesseN, robiin, twist |
|           42 |     1222 | 2024-06-09 | Johnny Speeds   | L   | 0.826      | -            | -                | -                | -         |    -2.79 | avid, b0denmaster, PlesseN, robiin, twist |
|           41 |     1245 | 2024-06-09 | Lilmix          | W   | 0.825      | 0.347        | 0.023 (0.007)    | 0.098 (0.028)    | 1 (0.825) |    13.48 | avid, b0denmaster, PlesseN, robiin, twist |
|           40 |     1641 | 2024-05-31 | VP.Prodigy      | L   | 0.765      | -            | -                | -                | -         |    -9.90 | avid, b0denmaster, PlesseN, robiin, twist |
|           39 |     1778 | 2024-05-24 | B8              | L   | 0.720      | -            | -                | -                | -         |    -3.66 | avid, b0denmaster, PlesseN, robiin, twist |
|           38 |     2152 | 2024-05-14 | kONO            | L   | 0.652      | -            | -                | -                | -         |   -10.65 | avid, b0denmaster, PlesseN, robiin, twist |
|           37 |     2456 | 2024-04-30 | B8              | L   | 0.559      | -            | -                | -                | -         |    -5.30 | avid, b0denmaster, PlesseN, robiin, twist |
|           36 |     2482 | 2024-04-29 | Endpoint        | W   | 0.551      | 0.384        | 0.012 (0.002)    | 0.522 (0.111)    | 0 (0.000) |     9.39 | avid, b0denmaster, PlesseN, robiin, twist |
|           35 |     2495 | 2024-04-28 | DMS             | W   | 0.546      | 0.500        | -                | 0.446 (0.122)    | 0 (0.000) |     9.42 | avid, b0denmaster, PlesseN, robiin, twist |
|           34 |     2534 | 2024-04-26 | B8              | L   | 0.534      | -            | -                | -                | -         |    -4.58 | avid, b0denmaster, PlesseN, robiin, twist |
|           33 |     2609 | 2024-04-23 | Metizport       | L   | 0.513      | -            | -                | -                | -         |    -7.69 | avid, b0denmaster, PlesseN, robiin, twist |
|           32 |     2626 | 2024-04-22 | B8              | W   | 0.505      | 0.384        | 0.165 (0.032)    | 0.951 (0.185)    | 0 (0.000) |    11.71 | avid, b0denmaster, PlesseN, robiin, twist |
|           31 |     2649 | 2024-04-21 | Sangal          | L   | 0.498      | -            | -                | -                | -         |    -2.73 | avid, b0denmaster, PlesseN, robiin, twist |
|           30 |     2730 | 2024-04-19 | 9 Pandas        | W   | 0.485      | 0.500        | 0.081 (0.020)    | 0.690 (0.167)    | 0 (0.000) |    10.29 | avid, b0denmaster, PlesseN, robiin, twist |
|           29 |     2802 | 2024-04-17 | Nemiga          | L   | 0.473      | -            | -                | -                | -         |    -2.24 | avid, b0denmaster, PlesseN, robiin, twist |
|           28 |     2814 | 2024-04-17 | ECLOT           | L   | 0.472      | -            | -                | -                | -         |    -2.05 | avid, b0denmaster, PlesseN, robiin, twist |
|           27 |     2861 | 2024-04-15 | HAVU            | W   | 0.459      | 0.384        | -                | 0.160 (0.028)    | 0 (0.000) |     4.23 | avid, b0denmaster, PlesseN, robiin, twist |
|           26 |     2865 | 2024-04-15 | MOUZ NXT        | L   | 0.458      | -            | -                | -                | -         |    -3.66 | avid, b0denmaster, PlesseN, robiin, twist |
|           25 |     2893 | 2024-04-13 | ALTERNATE aTTaX | L   | 0.445      | -            | -                | -                | -         |    -4.90 | avid, b0denmaster, PlesseN, robiin, twist |
|           24 |     2934 | 2024-04-11 | Zero Tenacity   | W   | 0.432      | 0.384        | 0.137 (0.023)    | 1.000 (0.166)    | 0 (0.000) |    10.56 | avid, b0denmaster, PlesseN, robiin, twist |
|           23 |     3027 | 2024-04-09 | BLEED           | L   | 0.420      | -            | -                | -                | -         |    -4.28 | avid, b0denmaster, PlesseN, robiin, twist |
|           22 |     3043 | 2024-04-09 | Astralis Talent | W   | 0.418      | 0.371        | 0.009 (0.001)    | -                | 0 (0.000) |     5.25 | avid, b0denmaster, PlesseN, robiin, twist |
|           21 |     3088 | 2024-04-07 | Johnny Speeds   | L   | 0.407      | -            | -                | -                | -         |    -1.05 | avid, b0denmaster, PlesseN, robiin, twist |
|           20 |     3091 | 2024-04-07 | EYEBALLERS      | L   | 0.406      | -            | -                | -                | -         |    -5.62 | avid, b0denmaster, PlesseN, robiin, twist |
|           19 |     3100 | 2024-04-06 | Lilmix          | W   | 0.401      | -            | -                | -                | 0 (0.000) |     0.92 | avid, b0denmaster, PlesseN, robiin, twist |
|           18 |     3105 | 2024-04-06 | BetBoom         | L   | 0.399      | -            | -                | -                | -         |    -0.57 | avid, b0denmaster, PlesseN, robiin, twist |
|           17 |     3122 | 2024-04-05 | BLEED           | L   | 0.393      | -            | -                | -                | -         |    -4.17 | avid, b0denmaster, PlesseN, robiin, twist |
|           16 |     3155 | 2024-04-04 | BetBoom         | L   | 0.387      | -            | -                | -                | -         |    -0.57 | avid, b0denmaster, PlesseN, robiin, twist |
|           15 |     3165 | 2024-04-04 | Benched Heroes  | W   | 0.386      | -            | -                | -                | -         |     0.86 | avid, b0denmaster, PlesseN, robiin, twist |
|           14 |     3210 | 2024-04-03 | AMKAL           | L   | 0.378      | -            | -                | -                | -         |    -2.21 | avid, b0denmaster, PlesseN, robiin, twist |
|           13 |     3609 | 2024-03-13 | MOUZ NXT        | L   | 0.239      | -            | -                | -                | -         |    -2.02 | avid, b0denmaster, PlesseN, robiin, twist |
|           12 |     3641 | 2024-03-12 | Passion UA      | L   | 0.232      | -            | -                | -                | -         |    -1.73 | avid, b0denmaster, PlesseN, robiin, twist |
|           11 |     3681 | 2024-03-10 | EYEBALLERS      | W   | 0.219      | -            | -                | -                | -         |     3.88 | avid, b0denmaster, PlesseN, robiin, twist |
|           10 |     3691 | 2024-03-09 | BLUDS           | W   | 0.214      | -            | -                | -                | -         |     0.48 | avid, b0denmaster, PlesseN, robiin, twist |
|            9 |     3705 | 2024-03-09 | Johnny Speeds   | W   | 0.213      | 0.143        | 0.122 (0.004)    | 0.941 (0.029)    | -         |     6.18 | avid, b0denmaster, PlesseN, robiin, twist |
|            8 |     3712 | 2024-03-09 | Entropiq        | W   | 0.212      | -            | -                | -                | -         |     1.05 | avid, b0denmaster, PlesseN, robiin, twist |
|            7 |     3755 | 2024-03-07 | ex-Sprout       | W   | 0.198      | -            | -                | -                | -         |     0.81 | avid, b0denmaster, PlesseN, robiin, twist |
|            6 |     3786 | 2024-03-06 | Sashi           | L   | 0.192      | -            | -                | -                | -         |    -1.01 | avid, b0denmaster, PlesseN, robiin, twist |
|            5 |     3830 | 2024-03-05 | Viperio         | W   | 0.185      | -            | -                | -                | -         |     0.42 | avid, b0denmaster, PlesseN, robiin, twist |
|            4 |     3910 | 2024-03-01 | 9INE            | L   | 0.159      | -            | -                | -                | -         |    -4.40 | avid, b0denmaster, PlesseN, robiin, twist |
|            3 |     3937 | 2024-02-28 | Sangal          | W   | 0.145      | 0.143        | 0.219 (0.005)    | -                | -         |     3.88 | avid, b0denmaster, PlesseN, robiin, twist |
|            2 |     3992 | 2024-02-25 | ALTERNATE aTTaX | W   | 0.126      | 0.358        | 0.031 (0.001)    | 0.560 (0.025)    | -         |     2.70 | avid, b0denmaster, PlesseN, robiin, twist |
|            1 |     4163 | 2024-02-18 | Portugal        | W   | 0.079      | -            | -                | -                | -         |     0.70 | avid, b0denmaster, PlesseN, robiin, twist |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,472.51)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-16 |      0.873 | $2,000.00      | $1,745.32       |
| 2024-06-09 |      0.826 | $2,889.00      | $2,387.10       |
| 2024-05-18 |      0.680 | $500.00        | $340.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
