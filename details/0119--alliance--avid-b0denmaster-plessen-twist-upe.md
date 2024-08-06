### Roster Details<br />
Team Name: Alliance<br />
Roster: avid, b0denmaster, PlesseN, twist, upE<br />
Global Rank: [119](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [84]( ../standings_europe.md)<br />
<br />
Final Rank Value:  819.9<br />
<br />
Final Rank Value (819.9) = Starting Rank Value (850.5) + Head To Head Adjustments (-30.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.332[<sup>2</sup>](#table1)
- Opponent Network: 0.090[<sup>2</sup>](#table1)
- LAN Wins: 0.094[<sup>2</sup>](#table1)

The average of these factors is 0.219<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.5
- 400 + ( ( 0.219 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 850.5


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
|           49 |       26 | 2024-08-05 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -13.59 | avid, b0denmaster, PlesseN, twist, upE    |
|           48 |       34 | 2024-08-04 | Young Ninjas    | L   | 1.000      | -            | -                | -                | -         |   -19.13 | avid, b0denmaster, PlesseN, twist, upE    |
|           47 |       87 | 2024-08-03 | RUSH B          | L   | 1.000      | -            | -                | -                | -         |   -11.51 | avid, b0denmaster, PlesseN, twist, upE    |
|           46 |      160 | 2024-08-01 | The Suspect     | W   | 1.000      | 0.342        | 0.008 (0.003)    | 0.223 (0.076)    | 0 (0.000) |    16.49 | avid, b0denmaster, PlesseN, twist, upE    |
|           45 |      288 | 2024-07-29 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -10.38 | avid, b0denmaster, PlesseN, twist, upE    |
|           44 |     1102 | 2024-06-14 | MIBR            | L   | 0.848      | -            | -                | -                | -         |    -1.26 | avid, b0denmaster, PlesseN, robiin, twist |
|           43 |     1118 | 2024-06-14 | Complexity      | L   | 0.847      | -            | -                | -                | -         |    -0.38 | avid, b0denmaster, PlesseN, robiin, twist |
|           42 |     1258 | 2024-06-09 | Johnny Speeds   | L   | 0.814      | -            | -                | -                | -         |    -2.73 | avid, b0denmaster, PlesseN, robiin, twist |
|           41 |     1281 | 2024-06-09 | Lilmix          | W   | 0.813      | 0.347        | 0.023 (0.006)    | 0.095 (0.027)    | 1 (0.813) |    13.32 | avid, b0denmaster, PlesseN, robiin, twist |
|           40 |     1677 | 2024-05-31 | VP.Prodigy      | L   | 0.753      | -            | -                | -                | -         |    -9.77 | avid, b0denmaster, PlesseN, robiin, twist |
|           39 |     1814 | 2024-05-24 | B8              | L   | 0.708      | -            | -                | -                | -         |    -3.60 | avid, b0denmaster, PlesseN, robiin, twist |
|           38 |     2188 | 2024-05-14 | kONO            | L   | 0.641      | -            | -                | -                | -         |   -10.39 | avid, b0denmaster, PlesseN, robiin, twist |
|           37 |     2492 | 2024-04-30 | B8              | L   | 0.547      | -            | -                | -                | -         |    -5.13 | avid, b0denmaster, PlesseN, robiin, twist |
|           36 |     2518 | 2024-04-29 | Endpoint        | W   | 0.539      | 0.384        | 0.012 (0.002)    | 0.502 (0.104)    | 0 (0.000) |     9.20 | avid, b0denmaster, PlesseN, robiin, twist |
|           35 |     2531 | 2024-04-28 | DMS             | W   | 0.534      | 0.500        | -                | 0.428 (0.114)    | 0 (0.000) |     9.19 | avid, b0denmaster, PlesseN, robiin, twist |
|           34 |     2570 | 2024-04-26 | B8              | L   | 0.522      | -            | -                | -                | -         |    -4.43 | avid, b0denmaster, PlesseN, robiin, twist |
|           33 |     2645 | 2024-04-23 | Metizport       | L   | 0.501      | -            | -                | -                | -         |    -6.40 | avid, b0denmaster, PlesseN, robiin, twist |
|           32 |     2662 | 2024-04-22 | B8              | W   | 0.494      | 0.384        | 0.170 (0.032)    | 0.912 (0.173)    | 0 (0.000) |    11.50 | avid, b0denmaster, PlesseN, robiin, twist |
|           31 |     2685 | 2024-04-21 | Sangal          | L   | 0.486      | -            | -                | -                | -         |    -2.63 | avid, b0denmaster, PlesseN, robiin, twist |
|           30 |     2766 | 2024-04-19 | 9 Pandas        | W   | 0.473      | 0.500        | 0.081 (0.019)    | 0.700 (0.165)    | 0 (0.000) |    10.00 | avid, b0denmaster, PlesseN, robiin, twist |
|           29 |     2838 | 2024-04-17 | Nemiga          | L   | 0.461      | -            | -                | -                | -         |    -2.21 | avid, b0denmaster, PlesseN, robiin, twist |
|           28 |     2850 | 2024-04-17 | ECLOT           | L   | 0.460      | -            | -                | -                | -         |    -1.98 | avid, b0denmaster, PlesseN, robiin, twist |
|           27 |     2897 | 2024-04-15 | HAVU            | W   | 0.447      | 0.384        | -                | 0.152 (0.026)    | 0 (0.000) |     4.11 | avid, b0denmaster, PlesseN, robiin, twist |
|           26 |     2901 | 2024-04-15 | MOUZ NXT        | L   | 0.446      | -            | -                | -                | -         |    -3.51 | avid, b0denmaster, PlesseN, robiin, twist |
|           25 |     2929 | 2024-04-13 | ALTERNATE aTTaX | L   | 0.433      | -            | -                | -                | -         |    -4.73 | avid, b0denmaster, PlesseN, robiin, twist |
|           24 |     2970 | 2024-04-11 | Zero Tenacity   | W   | 0.420      | 0.384        | 0.143 (0.023)    | 1.000 (0.162)    | 0 (0.000) |    10.31 | avid, b0denmaster, PlesseN, robiin, twist |
|           23 |     3063 | 2024-04-09 | BLEED           | L   | 0.408      | -            | -                | -                | -         |    -4.20 | avid, b0denmaster, PlesseN, robiin, twist |
|           22 |     3079 | 2024-04-09 | Astralis Talent | W   | 0.406      | 0.371        | 0.009 (0.001)    | 0.156 (0.024)    | 0 (0.000) |     5.09 | avid, b0denmaster, PlesseN, robiin, twist |
|           21 |     3124 | 2024-04-07 | Johnny Speeds   | L   | 0.395      | -            | -                | -                | -         |    -1.00 | avid, b0denmaster, PlesseN, robiin, twist |
|           20 |     3127 | 2024-04-07 | EYEBALLERS      | L   | 0.394      | -            | -                | -                | -         |    -5.43 | avid, b0denmaster, PlesseN, robiin, twist |
|           19 |     3136 | 2024-04-06 | Lilmix          | W   | 0.389      | -            | -                | -                | 0 (0.000) |     0.89 | avid, b0denmaster, PlesseN, robiin, twist |
|           18 |     3141 | 2024-04-06 | BetBoom         | L   | 0.387      | -            | -                | -                | -         |    -0.56 | avid, b0denmaster, PlesseN, robiin, twist |
|           17 |     3158 | 2024-04-05 | BLEED           | L   | 0.381      | -            | -                | -                | -         |    -4.08 | avid, b0denmaster, PlesseN, robiin, twist |
|           16 |     3191 | 2024-04-04 | BetBoom         | L   | 0.375      | -            | -                | -                | -         |    -0.56 | avid, b0denmaster, PlesseN, robiin, twist |
|           15 |     3201 | 2024-04-04 | Benched Heroes  | W   | 0.374      | -            | -                | -                | -         |     0.84 | avid, b0denmaster, PlesseN, robiin, twist |
|           14 |     3246 | 2024-04-03 | AMKAL           | L   | 0.367      | -            | -                | -                | -         |    -2.13 | avid, b0denmaster, PlesseN, robiin, twist |
|           13 |     3645 | 2024-03-13 | MOUZ NXT        | L   | 0.227      | -            | -                | -                | -         |    -1.89 | avid, b0denmaster, PlesseN, robiin, twist |
|           12 |     3677 | 2024-03-12 | Passion UA      | L   | 0.220      | -            | -                | -                | -         |    -1.59 | avid, b0denmaster, PlesseN, robiin, twist |
|           11 |     3717 | 2024-03-10 | EYEBALLERS      | W   | 0.207      | -            | -                | -                | -         |     3.68 | avid, b0denmaster, PlesseN, robiin, twist |
|           10 |     3727 | 2024-03-09 | BLUDS           | W   | 0.202      | -            | -                | -                | -         |     0.46 | avid, b0denmaster, PlesseN, robiin, twist |
|            9 |     3741 | 2024-03-09 | Johnny Speeds   | W   | 0.201      | 0.143        | 0.122 (0.003)    | 1.000 (0.029)    | -         |     5.84 | avid, b0denmaster, PlesseN, robiin, twist |
|            8 |     3748 | 2024-03-09 | Entropiq        | W   | 0.200      | -            | -                | -                | -         |     0.99 | avid, b0denmaster, PlesseN, robiin, twist |
|            7 |     3791 | 2024-03-07 | ex-Sprout       | W   | 0.187      | -            | -                | -                | -         |     0.73 | avid, b0denmaster, PlesseN, robiin, twist |
|            6 |     3822 | 2024-03-06 | Sashi           | L   | 0.180      | -            | -                | -                | -         |    -0.94 | avid, b0denmaster, PlesseN, robiin, twist |
|            5 |     3866 | 2024-03-05 | Viperio         | W   | 0.173      | -            | -                | -                | -         |     0.40 | avid, b0denmaster, PlesseN, robiin, twist |
|            4 |     3946 | 2024-03-01 | 9INE            | L   | 0.147      | -            | -                | -                | -         |    -4.07 | avid, b0denmaster, PlesseN, robiin, twist |
|            3 |     3973 | 2024-02-28 | Sangal          | W   | 0.133      | 0.143        | 0.219 (0.004)    | -                | -         |     3.57 | avid, b0denmaster, PlesseN, robiin, twist |
|            2 |     4028 | 2024-02-25 | ALTERNATE aTTaX | W   | 0.115      | 0.358        | 0.031 (0.001)    | -                | -         |     2.45 | avid, b0denmaster, PlesseN, robiin, twist |
|            1 |     4199 | 2024-02-18 | Portugal        | W   | 0.067      | -            | -                | -                | -         |     0.59 | avid, b0denmaster, PlesseN, robiin, twist |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,408.76)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-16 |      0.861 | $2,000.00      | $1,721.67       |
| 2024-06-09 |      0.814 | $2,889.00      | $2,352.93       |
| 2024-05-18 |      0.668 | $500.00        | $334.17         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
