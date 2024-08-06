### Roster Details<br />
Team Name: Alliance<br />
Roster: avid, b0denmaster, PlesseN, twist, upE<br />
Global Rank: [119](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [84]( ../standings_europe.md)<br />
<br />
Final Rank Value:  819.7<br />
<br />
Final Rank Value (819.7) = Starting Rank Value (850.1) + Head To Head Adjustments (-30.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.331[<sup>2</sup>](#table1)
- Opponent Network: 0.092[<sup>2</sup>](#table1)
- LAN Wins: 0.094[<sup>2</sup>](#table1)

The average of these factors is 0.219<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.1
- 400 + ( ( 0.219 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 850.1


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
|           49 |       22 | 2024-08-05 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -13.57 | avid, b0denmaster, PlesseN, twist, upE    |
|           48 |       30 | 2024-08-04 | Young Ninjas    | L   | 1.000      | -            | -                | -                | -         |   -19.12 | avid, b0denmaster, PlesseN, twist, upE    |
|           47 |       83 | 2024-08-03 | RUSH B          | L   | 1.000      | -            | -                | -                | -         |   -11.49 | avid, b0denmaster, PlesseN, twist, upE    |
|           46 |      156 | 2024-08-01 | The Suspect     | W   | 1.000      | 0.342        | 0.008 (0.003)    | 0.228 (0.078)    | 0 (0.000) |    16.48 | avid, b0denmaster, PlesseN, twist, upE    |
|           45 |      284 | 2024-07-29 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -10.37 | avid, b0denmaster, PlesseN, twist, upE    |
|           44 |     1098 | 2024-06-14 | MIBR            | L   | 0.849      | -            | -                | -                | -         |    -1.25 | avid, b0denmaster, PlesseN, robiin, twist |
|           43 |     1114 | 2024-06-14 | Complexity      | L   | 0.847      | -            | -                | -                | -         |    -0.38 | avid, b0denmaster, PlesseN, robiin, twist |
|           42 |     1254 | 2024-06-09 | Johnny Speeds   | L   | 0.815      | -            | -                | -                | -         |    -2.73 | avid, b0denmaster, PlesseN, robiin, twist |
|           41 |     1277 | 2024-06-09 | Lilmix          | W   | 0.814      | 0.347        | 0.023 (0.006)    | 0.097 (0.027)    | 1 (0.814) |    13.30 | avid, b0denmaster, PlesseN, robiin, twist |
|           40 |     1673 | 2024-05-31 | VP.Prodigy      | L   | 0.753      | -            | -                | -                | -         |    -9.75 | avid, b0denmaster, PlesseN, robiin, twist |
|           39 |     1810 | 2024-05-24 | B8              | L   | 0.709      | -            | -                | -                | -         |    -3.61 | avid, b0denmaster, PlesseN, robiin, twist |
|           38 |     2184 | 2024-05-14 | kONO            | L   | 0.641      | -            | -                | -                | -         |   -10.39 | avid, b0denmaster, PlesseN, robiin, twist |
|           37 |     2488 | 2024-04-30 | B8              | L   | 0.547      | -            | -                | -                | -         |    -5.15 | avid, b0denmaster, PlesseN, robiin, twist |
|           36 |     2514 | 2024-04-29 | Endpoint        | W   | 0.540      | 0.384        | 0.012 (0.002)    | 0.513 (0.106)    | 0 (0.000) |     9.23 | avid, b0denmaster, PlesseN, robiin, twist |
|           35 |     2527 | 2024-04-28 | DMS             | W   | 0.534      | 0.500        | -                | 0.437 (0.117)    | 0 (0.000) |     9.21 | avid, b0denmaster, PlesseN, robiin, twist |
|           34 |     2566 | 2024-04-26 | B8              | L   | 0.522      | -            | -                | -                | -         |    -4.46 | avid, b0denmaster, PlesseN, robiin, twist |
|           33 |     2641 | 2024-04-23 | Metizport       | L   | 0.501      | -            | -                | -                | -         |    -6.39 | avid, b0denmaster, PlesseN, robiin, twist |
|           32 |     2658 | 2024-04-22 | B8              | W   | 0.494      | 0.384        | 0.164 (0.031)    | 0.933 (0.177)    | 0 (0.000) |    11.49 | avid, b0denmaster, PlesseN, robiin, twist |
|           31 |     2681 | 2024-04-21 | Sangal          | L   | 0.486      | -            | -                | -                | -         |    -2.62 | avid, b0denmaster, PlesseN, robiin, twist |
|           30 |     2762 | 2024-04-19 | 9 Pandas        | W   | 0.473      | 0.500        | 0.081 (0.019)    | 0.716 (0.169)    | 0 (0.000) |    10.03 | avid, b0denmaster, PlesseN, robiin, twist |
|           29 |     2834 | 2024-04-17 | Nemiga          | L   | 0.461      | -            | -                | -                | -         |    -2.21 | avid, b0denmaster, PlesseN, robiin, twist |
|           28 |     2846 | 2024-04-17 | ECLOT           | L   | 0.460      | -            | -                | -                | -         |    -1.98 | avid, b0denmaster, PlesseN, robiin, twist |
|           27 |     2893 | 2024-04-15 | HAVU            | W   | 0.448      | 0.384        | -                | 0.156 (0.027)    | 0 (0.000) |     4.12 | avid, b0denmaster, PlesseN, robiin, twist |
|           26 |     2897 | 2024-04-15 | MOUZ NXT        | L   | 0.446      | -            | -                | -                | -         |    -3.50 | avid, b0denmaster, PlesseN, robiin, twist |
|           25 |     2925 | 2024-04-13 | ALTERNATE aTTaX | L   | 0.433      | -            | -                | -                | -         |    -4.75 | avid, b0denmaster, PlesseN, robiin, twist |
|           24 |     2966 | 2024-04-11 | Zero Tenacity   | W   | 0.421      | 0.384        | 0.143 (0.023)    | 1.000 (0.162)    | 0 (0.000) |    10.33 | avid, b0denmaster, PlesseN, robiin, twist |
|           23 |     3059 | 2024-04-09 | BLEED           | L   | 0.408      | -            | -                | -                | -         |    -4.20 | avid, b0denmaster, PlesseN, robiin, twist |
|           22 |     3075 | 2024-04-09 | Astralis Talent | W   | 0.406      | 0.371        | 0.009 (0.001)    | 0.160 (0.024)    | 0 (0.000) |     5.08 | avid, b0denmaster, PlesseN, robiin, twist |
|           21 |     3120 | 2024-04-07 | Johnny Speeds   | L   | 0.395      | -            | -                | -                | -         |    -1.00 | avid, b0denmaster, PlesseN, robiin, twist |
|           20 |     3123 | 2024-04-07 | EYEBALLERS      | L   | 0.394      | -            | -                | -                | -         |    -5.43 | avid, b0denmaster, PlesseN, robiin, twist |
|           19 |     3132 | 2024-04-06 | Lilmix          | W   | 0.389      | -            | -                | -                | 0 (0.000) |     0.89 | avid, b0denmaster, PlesseN, robiin, twist |
|           18 |     3137 | 2024-04-06 | BetBoom         | L   | 0.388      | -            | -                | -                | -         |    -0.56 | avid, b0denmaster, PlesseN, robiin, twist |
|           17 |     3154 | 2024-04-05 | BLEED           | L   | 0.381      | -            | -                | -                | -         |    -4.07 | avid, b0denmaster, PlesseN, robiin, twist |
|           16 |     3187 | 2024-04-04 | BetBoom         | L   | 0.376      | -            | -                | -                | -         |    -0.56 | avid, b0denmaster, PlesseN, robiin, twist |
|           15 |     3197 | 2024-04-04 | Benched Heroes  | W   | 0.374      | -            | -                | -                | -         |     0.84 | avid, b0denmaster, PlesseN, robiin, twist |
|           14 |     3242 | 2024-04-03 | AMKAL           | L   | 0.367      | -            | -                | -                | -         |    -2.13 | avid, b0denmaster, PlesseN, robiin, twist |
|           13 |     3641 | 2024-03-13 | MOUZ NXT        | L   | 0.227      | -            | -                | -                | -         |    -1.89 | avid, b0denmaster, PlesseN, robiin, twist |
|           12 |     3673 | 2024-03-12 | Passion UA      | L   | 0.221      | -            | -                | -                | -         |    -1.58 | avid, b0denmaster, PlesseN, robiin, twist |
|           11 |     3713 | 2024-03-10 | EYEBALLERS      | W   | 0.208      | -            | -                | -                | -         |     3.69 | avid, b0denmaster, PlesseN, robiin, twist |
|           10 |     3723 | 2024-03-09 | BLUDS           | W   | 0.202      | -            | -                | -                | -         |     0.46 | avid, b0denmaster, PlesseN, robiin, twist |
|            9 |     3737 | 2024-03-09 | Johnny Speeds   | W   | 0.201      | 0.143        | 0.122 (0.004)    | 1.000 (0.029)    | -         |     5.85 | avid, b0denmaster, PlesseN, robiin, twist |
|            8 |     3744 | 2024-03-09 | Entropiq        | W   | 0.200      | -            | -                | -                | -         |     0.99 | avid, b0denmaster, PlesseN, robiin, twist |
|            7 |     3787 | 2024-03-07 | ex-Sprout       | W   | 0.187      | -            | -                | -                | -         |     0.73 | avid, b0denmaster, PlesseN, robiin, twist |
|            6 |     3818 | 2024-03-06 | Sashi           | L   | 0.180      | -            | -                | -                | -         |    -0.94 | avid, b0denmaster, PlesseN, robiin, twist |
|            5 |     3862 | 2024-03-05 | Viperio         | W   | 0.173      | -            | -                | -                | -         |     0.40 | avid, b0denmaster, PlesseN, robiin, twist |
|            4 |     3942 | 2024-03-01 | 9INE            | L   | 0.147      | -            | -                | -                | -         |    -4.08 | avid, b0denmaster, PlesseN, robiin, twist |
|            3 |     3969 | 2024-02-28 | Sangal          | W   | 0.134      | 0.143        | 0.219 (0.004)    | -                | -         |     3.58 | avid, b0denmaster, PlesseN, robiin, twist |
|            2 |     4024 | 2024-02-25 | ALTERNATE aTTaX | W   | 0.115      | 0.358        | 0.031 (0.001)    | -                | -         |     2.45 | avid, b0denmaster, PlesseN, robiin, twist |
|            1 |     4195 | 2024-02-18 | Portugal        | W   | 0.067      | -            | -                | -                | -         |     0.60 | avid, b0denmaster, PlesseN, robiin, twist |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,410.26)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-16 |      0.861 | $2,000.00      | $1,722.22       |
| 2024-06-09 |      0.815 | $2,889.00      | $2,353.73       |
| 2024-05-18 |      0.669 | $500.00        | $334.31         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
