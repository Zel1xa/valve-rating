### Roster Details<br />
Team Name: Alliance<br />
Roster: avid, b0denmaster, PlesseN, twist, upE<br />
Global Rank: [120](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [85]( ../standings_europe.md)<br />
<br />
Final Rank Value:  819.0<br />
<br />
Final Rank Value (819.0) = Starting Rank Value (850.6) + Head To Head Adjustments (-31.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.332[<sup>2</sup>](#table1)
- Opponent Network: 0.093[<sup>2</sup>](#table1)
- LAN Wins: 0.094[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.6
- 400 + ( ( 0.220 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 850.6


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
|           49 |       16 | 2024-08-05 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -13.74 | avid, b0denmaster, PlesseN, twist, upE    |
|           48 |       24 | 2024-08-04 | Young Ninjas    | L   | 1.000      | -            | -                | -                | -         |   -19.05 | avid, b0denmaster, PlesseN, twist, upE    |
|           47 |       77 | 2024-08-03 | RUSH B          | L   | 1.000      | -            | -                | -                | -         |   -11.47 | avid, b0denmaster, PlesseN, twist, upE    |
|           46 |      150 | 2024-08-01 | The Suspect     | W   | 1.000      | 0.342        | 0.008 (0.003)    | 0.227 (0.078)    | 0 (0.000) |    16.50 | avid, b0denmaster, PlesseN, twist, upE    |
|           45 |      278 | 2024-07-29 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -10.39 | avid, b0denmaster, PlesseN, twist, upE    |
|           44 |     1092 | 2024-06-14 | MIBR            | L   | 0.853      | -            | -                | -                | -         |    -1.24 | avid, b0denmaster, PlesseN, robiin, twist |
|           43 |     1108 | 2024-06-14 | Complexity      | L   | 0.851      | -            | -                | -                | -         |    -0.38 | avid, b0denmaster, PlesseN, robiin, twist |
|           42 |     1248 | 2024-06-09 | Johnny Speeds   | L   | 0.819      | -            | -                | -                | -         |    -2.75 | avid, b0denmaster, PlesseN, robiin, twist |
|           41 |     1271 | 2024-06-09 | Lilmix          | W   | 0.818      | 0.347        | 0.023 (0.006)    | 0.097 (0.027)    | 1 (0.818) |    13.40 | avid, b0denmaster, PlesseN, robiin, twist |
|           40 |     1667 | 2024-05-31 | VP.Prodigy      | L   | 0.757      | -            | -                | -                | -         |    -9.79 | avid, b0denmaster, PlesseN, robiin, twist |
|           39 |     1804 | 2024-05-24 | B8              | L   | 0.713      | -            | -                | -                | -         |    -3.63 | avid, b0denmaster, PlesseN, robiin, twist |
|           38 |     2178 | 2024-05-14 | kONO            | L   | 0.645      | -            | -                | -                | -         |   -10.54 | avid, b0denmaster, PlesseN, robiin, twist |
|           37 |     2482 | 2024-04-30 | B8              | L   | 0.552      | -            | -                | -                | -         |    -5.20 | avid, b0denmaster, PlesseN, robiin, twist |
|           36 |     2508 | 2024-04-29 | Endpoint        | W   | 0.544      | 0.384        | 0.012 (0.002)    | 0.514 (0.107)    | 0 (0.000) |     9.29 | avid, b0denmaster, PlesseN, robiin, twist |
|           35 |     2521 | 2024-04-28 | DMS             | W   | 0.538      | 0.500        | -                | 0.438 (0.118)    | 0 (0.000) |     9.30 | avid, b0denmaster, PlesseN, robiin, twist |
|           34 |     2560 | 2024-04-26 | B8              | L   | 0.527      | -            | -                | -                | -         |    -4.50 | avid, b0denmaster, PlesseN, robiin, twist |
|           33 |     2635 | 2024-04-23 | Metizport       | L   | 0.505      | -            | -                | -                | -         |    -7.61 | avid, b0denmaster, PlesseN, robiin, twist |
|           32 |     2652 | 2024-04-22 | B8              | W   | 0.498      | 0.384        | 0.165 (0.032)    | 0.935 (0.179)    | 0 (0.000) |    11.56 | avid, b0denmaster, PlesseN, robiin, twist |
|           31 |     2675 | 2024-04-21 | Sangal          | L   | 0.491      | -            | -                | -                | -         |    -2.66 | avid, b0denmaster, PlesseN, robiin, twist |
|           30 |     2756 | 2024-04-19 | 9 Pandas        | W   | 0.477      | 0.500        | 0.081 (0.019)    | 0.717 (0.171)    | 0 (0.000) |    10.12 | avid, b0denmaster, PlesseN, robiin, twist |
|           29 |     2828 | 2024-04-17 | Nemiga          | L   | 0.466      | -            | -                | -                | -         |    -2.22 | avid, b0denmaster, PlesseN, robiin, twist |
|           28 |     2840 | 2024-04-17 | ECLOT           | L   | 0.464      | -            | -                | -                | -         |    -2.01 | avid, b0denmaster, PlesseN, robiin, twist |
|           27 |     2887 | 2024-04-15 | HAVU            | W   | 0.452      | 0.384        | -                | 0.157 (0.027)    | 0 (0.000) |     4.16 | avid, b0denmaster, PlesseN, robiin, twist |
|           26 |     2891 | 2024-04-15 | MOUZ NXT        | L   | 0.451      | -            | -                | -                | -         |    -3.55 | avid, b0denmaster, PlesseN, robiin, twist |
|           25 |     2919 | 2024-04-13 | ALTERNATE aTTaX | L   | 0.438      | -            | -                | -                | -         |    -4.81 | avid, b0denmaster, PlesseN, robiin, twist |
|           24 |     2960 | 2024-04-11 | Zero Tenacity   | W   | 0.425      | 0.384        | 0.143 (0.023)    | 1.000 (0.163)    | 0 (0.000) |    10.43 | avid, b0denmaster, PlesseN, robiin, twist |
|           23 |     3053 | 2024-04-09 | BLEED           | L   | 0.413      | -            | -                | -                | -         |    -4.24 | avid, b0denmaster, PlesseN, robiin, twist |
|           22 |     3069 | 2024-04-09 | Astralis Talent | W   | 0.410      | 0.371        | 0.009 (0.001)    | 0.160 (0.024)    | 0 (0.000) |     5.13 | avid, b0denmaster, PlesseN, robiin, twist |
|           21 |     3114 | 2024-04-07 | Johnny Speeds   | L   | 0.399      | -            | -                | -                | -         |    -1.02 | avid, b0denmaster, PlesseN, robiin, twist |
|           20 |     3117 | 2024-04-07 | EYEBALLERS      | L   | 0.398      | -            | -                | -                | -         |    -5.51 | avid, b0denmaster, PlesseN, robiin, twist |
|           19 |     3126 | 2024-04-06 | Lilmix          | W   | 0.393      | -            | -                | -                | 0 (0.000) |     0.90 | avid, b0denmaster, PlesseN, robiin, twist |
|           18 |     3131 | 2024-04-06 | BetBoom         | L   | 0.392      | -            | -                | -                | -         |    -0.56 | avid, b0denmaster, PlesseN, robiin, twist |
|           17 |     3148 | 2024-04-05 | BLEED           | L   | 0.385      | -            | -                | -                | -         |    -4.12 | avid, b0denmaster, PlesseN, robiin, twist |
|           16 |     3181 | 2024-04-04 | BetBoom         | L   | 0.380      | -            | -                | -                | -         |    -0.56 | avid, b0denmaster, PlesseN, robiin, twist |
|           15 |     3191 | 2024-04-04 | Benched Heroes  | W   | 0.379      | -            | -                | -                | -         |     0.85 | avid, b0denmaster, PlesseN, robiin, twist |
|           14 |     3236 | 2024-04-03 | AMKAL           | L   | 0.371      | -            | -                | -                | -         |    -2.17 | avid, b0denmaster, PlesseN, robiin, twist |
|           13 |     3635 | 2024-03-13 | MOUZ NXT        | L   | 0.231      | -            | -                | -                | -         |    -1.93 | avid, b0denmaster, PlesseN, robiin, twist |
|           12 |     3667 | 2024-03-12 | Passion UA      | L   | 0.225      | -            | -                | -                | -         |    -1.63 | avid, b0denmaster, PlesseN, robiin, twist |
|           11 |     3707 | 2024-03-10 | EYEBALLERS      | W   | 0.212      | -            | -                | -                | -         |     3.75 | avid, b0denmaster, PlesseN, robiin, twist |
|           10 |     3717 | 2024-03-09 | BLUDS           | W   | 0.206      | -            | -                | -                | -         |     0.47 | avid, b0denmaster, PlesseN, robiin, twist |
|            9 |     3731 | 2024-03-09 | Johnny Speeds   | W   | 0.205      | 0.143        | 0.122 (0.004)    | 1.000 (0.029)    | -         |     5.97 | avid, b0denmaster, PlesseN, robiin, twist |
|            8 |     3738 | 2024-03-09 | Entropiq        | W   | 0.205      | -            | -                | -                | -         |     1.01 | avid, b0denmaster, PlesseN, robiin, twist |
|            7 |     3781 | 2024-03-07 | ex-Sprout       | W   | 0.191      | -            | -                | -                | -         |     0.76 | avid, b0denmaster, PlesseN, robiin, twist |
|            6 |     3812 | 2024-03-06 | Sashi           | L   | 0.185      | -            | -                | -                | -         |    -0.97 | avid, b0denmaster, PlesseN, robiin, twist |
|            5 |     3856 | 2024-03-05 | Viperio         | W   | 0.177      | -            | -                | -                | -         |     0.41 | avid, b0denmaster, PlesseN, robiin, twist |
|            4 |     3936 | 2024-03-01 | 9INE            | L   | 0.151      | -            | -                | -                | -         |    -4.20 | avid, b0denmaster, PlesseN, robiin, twist |
|            3 |     3963 | 2024-02-28 | Sangal          | W   | 0.138      | 0.143        | 0.219 (0.004)    | -                | -         |     3.69 | avid, b0denmaster, PlesseN, robiin, twist |
|            2 |     4018 | 2024-02-25 | ALTERNATE aTTaX | W   | 0.119      | 0.358        | 0.031 (0.001)    | -                | -         |     2.55 | avid, b0denmaster, PlesseN, robiin, twist |
|            1 |     4189 | 2024-02-18 | Portugal        | W   | 0.072      | -            | -                | -                | -         |     0.64 | avid, b0denmaster, PlesseN, robiin, twist |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,433.46)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-16 |      0.865 | $2,000.00      | $1,730.83       |
| 2024-06-09 |      0.819 | $2,889.00      | $2,366.17       |
| 2024-05-18 |      0.673 | $500.00        | $336.46         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
