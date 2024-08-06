### Roster Details<br />
Team Name: Alliance<br />
Roster: avid, b0denmaster, PlesseN, twist, upE<br />
Global Rank: [119](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [84]( ../standings_europe.md)<br />
<br />
Final Rank Value:  820.5<br />
<br />
Final Rank Value (820.5) = Starting Rank Value (850.8) + Head To Head Adjustments (-30.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.331[<sup>2</sup>](#table1)
- Opponent Network: 0.091[<sup>2</sup>](#table1)
- LAN Wins: 0.094[<sup>2</sup>](#table1)

The average of these factors is 0.219<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.8
- 400 + ( ( 0.219 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 850.8


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
|           49 |       35 | 2024-08-05 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -13.43 | avid, b0denmaster, PlesseN, twist, upE    |
|           48 |       43 | 2024-08-04 | Young Ninjas    | L   | 1.000      | -            | -                | -                | -         |   -19.15 | avid, b0denmaster, PlesseN, twist, upE    |
|           47 |       96 | 2024-08-03 | RUSH B          | L   | 1.000      | -            | -                | -                | -         |   -11.51 | avid, b0denmaster, PlesseN, twist, upE    |
|           46 |      169 | 2024-08-01 | The Suspect     | W   | 1.000      | 0.342        | 0.008 (0.003)    | 0.223 (0.076)    | 0 (0.000) |    16.48 | avid, b0denmaster, PlesseN, twist, upE    |
|           45 |      297 | 2024-07-29 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -10.36 | avid, b0denmaster, PlesseN, twist, upE    |
|           44 |     1111 | 2024-06-14 | MIBR            | L   | 0.847      | -            | -                | -                | -         |    -1.26 | avid, b0denmaster, PlesseN, robiin, twist |
|           43 |     1127 | 2024-06-14 | Complexity      | L   | 0.846      | -            | -                | -                | -         |    -0.38 | avid, b0denmaster, PlesseN, robiin, twist |
|           42 |     1267 | 2024-06-09 | Johnny Speeds   | L   | 0.813      | -            | -                | -                | -         |    -2.70 | avid, b0denmaster, PlesseN, robiin, twist |
|           41 |     1290 | 2024-06-09 | Lilmix          | W   | 0.812      | 0.347        | 0.023 (0.006)    | 0.095 (0.027)    | 1 (0.812) |    13.29 | avid, b0denmaster, PlesseN, robiin, twist |
|           40 |     1686 | 2024-05-31 | VP.Prodigy      | L   | 0.752      | -            | -                | -                | -         |    -9.73 | avid, b0denmaster, PlesseN, robiin, twist |
|           39 |     1823 | 2024-05-24 | B8              | L   | 0.707      | -            | -                | -                | -         |    -3.60 | avid, b0denmaster, PlesseN, robiin, twist |
|           38 |     2197 | 2024-05-14 | kONO            | L   | 0.639      | -            | -                | -                | -         |   -10.37 | avid, b0denmaster, PlesseN, robiin, twist |
|           37 |     2501 | 2024-04-30 | B8              | L   | 0.546      | -            | -                | -                | -         |    -5.12 | avid, b0denmaster, PlesseN, robiin, twist |
|           36 |     2527 | 2024-04-29 | Endpoint        | W   | 0.538      | 0.384        | 0.012 (0.002)    | 0.540 (0.112)    | 0 (0.000) |     9.22 | avid, b0denmaster, PlesseN, robiin, twist |
|           35 |     2540 | 2024-04-28 | DMS             | W   | 0.533      | 0.500        | -                | 0.428 (0.114)    | 0 (0.000) |     9.16 | avid, b0denmaster, PlesseN, robiin, twist |
|           34 |     2579 | 2024-04-26 | B8              | L   | 0.521      | -            | -                | -                | -         |    -4.42 | avid, b0denmaster, PlesseN, robiin, twist |
|           33 |     2654 | 2024-04-23 | Metizport       | L   | 0.500      | -            | -                | -                | -         |    -6.34 | avid, b0denmaster, PlesseN, robiin, twist |
|           32 |     2671 | 2024-04-22 | B8              | W   | 0.492      | 0.384        | 0.170 (0.032)    | 0.912 (0.173)    | 0 (0.000) |    11.48 | avid, b0denmaster, PlesseN, robiin, twist |
|           31 |     2694 | 2024-04-21 | Sangal          | L   | 0.485      | -            | -                | -                | -         |    -2.56 | avid, b0denmaster, PlesseN, robiin, twist |
|           30 |     2775 | 2024-04-19 | 9 Pandas        | W   | 0.472      | 0.500        | 0.081 (0.019)    | 0.700 (0.165)    | 0 (0.000) |     9.98 | avid, b0denmaster, PlesseN, robiin, twist |
|           29 |     2847 | 2024-04-17 | Nemiga          | L   | 0.460      | -            | -                | -                | -         |    -2.21 | avid, b0denmaster, PlesseN, robiin, twist |
|           28 |     2859 | 2024-04-17 | ECLOT           | L   | 0.459      | -            | -                | -                | -         |    -1.97 | avid, b0denmaster, PlesseN, robiin, twist |
|           27 |     2906 | 2024-04-15 | HAVU            | W   | 0.446      | 0.384        | -                | 0.152 (0.026)    | 0 (0.000) |     4.10 | avid, b0denmaster, PlesseN, robiin, twist |
|           26 |     2910 | 2024-04-15 | MOUZ NXT        | L   | 0.445      | -            | -                | -                | -         |    -3.50 | avid, b0denmaster, PlesseN, robiin, twist |
|           25 |     2938 | 2024-04-13 | ALTERNATE aTTaX | L   | 0.432      | -            | -                | -                | -         |    -4.71 | avid, b0denmaster, PlesseN, robiin, twist |
|           24 |     2979 | 2024-04-11 | Zero Tenacity   | W   | 0.419      | 0.384        | 0.143 (0.023)    | 1.000 (0.161)    | 0 (0.000) |    10.29 | avid, b0denmaster, PlesseN, robiin, twist |
|           23 |     3072 | 2024-04-09 | BLEED           | L   | 0.407      | -            | -                | -                | -         |    -4.20 | avid, b0denmaster, PlesseN, robiin, twist |
|           22 |     3088 | 2024-04-09 | Astralis Talent | W   | 0.405      | 0.371        | 0.009 (0.001)    | 0.156 (0.023)    | 0 (0.000) |     5.07 | avid, b0denmaster, PlesseN, robiin, twist |
|           21 |     3133 | 2024-04-07 | Johnny Speeds   | L   | 0.394      | -            | -                | -                | -         |    -0.98 | avid, b0denmaster, PlesseN, robiin, twist |
|           20 |     3136 | 2024-04-07 | EYEBALLERS      | L   | 0.393      | -            | -                | -                | -         |    -5.42 | avid, b0denmaster, PlesseN, robiin, twist |
|           19 |     3145 | 2024-04-06 | Lilmix          | W   | 0.388      | -            | -                | -                | 0 (0.000) |     0.89 | avid, b0denmaster, PlesseN, robiin, twist |
|           18 |     3150 | 2024-04-06 | BetBoom         | L   | 0.386      | -            | -                | -                | -         |    -0.56 | avid, b0denmaster, PlesseN, robiin, twist |
|           17 |     3167 | 2024-04-05 | BLEED           | L   | 0.380      | -            | -                | -                | -         |    -4.07 | avid, b0denmaster, PlesseN, robiin, twist |
|           16 |     3200 | 2024-04-04 | BetBoom         | L   | 0.374      | -            | -                | -                | -         |    -0.56 | avid, b0denmaster, PlesseN, robiin, twist |
|           15 |     3210 | 2024-04-04 | Benched Heroes  | W   | 0.373      | -            | -                | -                | -         |     0.83 | avid, b0denmaster, PlesseN, robiin, twist |
|           14 |     3255 | 2024-04-03 | AMKAL           | L   | 0.366      | -            | -                | -                | -         |    -2.12 | avid, b0denmaster, PlesseN, robiin, twist |
|           13 |     3654 | 2024-03-13 | MOUZ NXT        | L   | 0.226      | -            | -                | -                | -         |    -1.88 | avid, b0denmaster, PlesseN, robiin, twist |
|           12 |     3686 | 2024-03-12 | Passion UA      | L   | 0.219      | -            | -                | -                | -         |    -1.58 | avid, b0denmaster, PlesseN, robiin, twist |
|           11 |     3726 | 2024-03-10 | EYEBALLERS      | W   | 0.206      | -            | -                | -                | -         |     3.66 | avid, b0denmaster, PlesseN, robiin, twist |
|           10 |     3736 | 2024-03-09 | BLUDS           | W   | 0.201      | -            | -                | -                | -         |     0.46 | avid, b0denmaster, PlesseN, robiin, twist |
|            9 |     3750 | 2024-03-09 | Johnny Speeds   | W   | 0.200      | 0.143        | 0.122 (0.003)    | 1.000 (0.029)    | -         |     5.81 | avid, b0denmaster, PlesseN, robiin, twist |
|            8 |     3757 | 2024-03-09 | Entropiq        | W   | 0.199      | -            | -                | -                | -         |     0.98 | avid, b0denmaster, PlesseN, robiin, twist |
|            7 |     3800 | 2024-03-07 | ex-Sprout       | W   | 0.186      | -            | -                | -                | -         |     0.72 | avid, b0denmaster, PlesseN, robiin, twist |
|            6 |     3831 | 2024-03-06 | Sashi           | L   | 0.179      | -            | -                | -                | -         |    -0.94 | avid, b0denmaster, PlesseN, robiin, twist |
|            5 |     3875 | 2024-03-05 | Viperio         | W   | 0.172      | -            | -                | -                | -         |     0.40 | avid, b0denmaster, PlesseN, robiin, twist |
|            4 |     3955 | 2024-03-01 | 9INE            | L   | 0.146      | -            | -                | -                | -         |    -4.04 | avid, b0denmaster, PlesseN, robiin, twist |
|            3 |     3982 | 2024-02-28 | Sangal          | W   | 0.132      | 0.143        | 0.219 (0.004)    | -                | -         |     3.55 | avid, b0denmaster, PlesseN, robiin, twist |
|            2 |     4037 | 2024-02-25 | ALTERNATE aTTaX | W   | 0.113      | 0.358        | 0.031 (0.001)    | -                | -         |     2.43 | avid, b0denmaster, PlesseN, robiin, twist |
|            1 |     4208 | 2024-02-18 | Portugal        | W   | 0.066      | -            | -                | -                | -         |     0.58 | avid, b0denmaster, PlesseN, robiin, twist |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,402.78)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-16 |      0.860 | $2,000.00      | $1,719.44       |
| 2024-06-09 |      0.813 | $2,889.00      | $2,349.72       |
| 2024-05-18 |      0.667 | $500.00        | $333.61         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
