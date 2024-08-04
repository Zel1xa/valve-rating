### Roster Details<br />
Team Name: Alliance<br />
Roster: avid, b0denmaster, PlesseN, twist, upE<br />
Global Rank: [102](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [75]( ../standings_europe.md)<br />
<br />
Final Rank Value:  850.5<br />
<br />
Final Rank Value (850.5) = Starting Rank Value (849.6) + Head To Head Adjustments (0.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.332[<sup>2</sup>](#table1)
- Opponent Network: 0.092[<sup>2</sup>](#table1)
- LAN Wins: 0.095[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 849.6
- 400 + ( ( 0.220 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 849.6


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
|           48 |       21 | 2024-08-03 | RUSH B          | L   | 1.000      | -            | -                | -                | -         |   -11.85 | avid, b0denmaster, PlesseN, twist, upE    |
|           47 |       92 | 2024-08-01 | The Suspect     | W   | 1.000      | 0.342        | 0.008 (0.003)    | 0.189 (0.065)    | 0 (0.000) |    16.41 | avid, b0denmaster, PlesseN, twist, upE    |
|           46 |      218 | 2024-07-29 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -11.27 | avid, b0denmaster, PlesseN, twist, upE    |
|           45 |     1034 | 2024-06-14 | MIBR            | L   | 0.862      | -            | -                | -                | -         |    -1.24 | avid, b0denmaster, PlesseN, robiin, twist |
|           44 |     1050 | 2024-06-14 | Complexity      | L   | 0.860      | -            | -                | -                | -         |    -0.40 | avid, b0denmaster, PlesseN, robiin, twist |
|           43 |     1190 | 2024-06-09 | Johnny Speeds   | L   | 0.828      | -            | -                | -                | -         |    -2.89 | avid, b0denmaster, PlesseN, robiin, twist |
|           42 |     1213 | 2024-06-09 | Lilmix          | W   | 0.827      | 0.347        | 0.023 (0.007)    | 0.098 (0.028)    | 1 (0.827) |    13.51 | avid, b0denmaster, PlesseN, robiin, twist |
|           41 |     1609 | 2024-05-31 | VP.Prodigy      | L   | 0.766      | -            | -                | -                | -         |    -9.98 | avid, b0denmaster, PlesseN, robiin, twist |
|           40 |     1746 | 2024-05-24 | B8              | L   | 0.722      | -            | -                | -                | -         |    -3.69 | avid, b0denmaster, PlesseN, robiin, twist |
|           39 |     2120 | 2024-05-14 | kONO            | L   | 0.654      | -            | -                | -                | -         |   -10.68 | avid, b0denmaster, PlesseN, robiin, twist |
|           38 |     2424 | 2024-04-30 | B8              | L   | 0.561      | -            | -                | -                | -         |    -5.32 | avid, b0denmaster, PlesseN, robiin, twist |
|           37 |     2450 | 2024-04-29 | Endpoint        | W   | 0.553      | 0.384        | 0.012 (0.003)    | 0.522 (0.111)    | 0 (0.000) |     9.40 | avid, b0denmaster, PlesseN, robiin, twist |
|           36 |     2463 | 2024-04-28 | DMS             | W   | 0.547      | 0.500        | -                | 0.446 (0.122)    | 0 (0.000) |     9.44 | avid, b0denmaster, PlesseN, robiin, twist |
|           35 |     2502 | 2024-04-26 | B8              | L   | 0.536      | -            | -                | -                | -         |    -4.60 | avid, b0denmaster, PlesseN, robiin, twist |
|           34 |     2577 | 2024-04-23 | Metizport       | L   | 0.514      | -            | -                | -                | -         |    -6.54 | avid, b0denmaster, PlesseN, robiin, twist |
|           33 |     2594 | 2024-04-22 | B8              | W   | 0.507      | 0.384        | 0.165 (0.032)    | 0.912 (0.178)    | 0 (0.000) |    11.78 | avid, b0denmaster, PlesseN, robiin, twist |
|           32 |     2617 | 2024-04-21 | Sangal          | L   | 0.500      | -            | -                | -                | -         |    -2.78 | avid, b0denmaster, PlesseN, robiin, twist |
|           31 |     2698 | 2024-04-19 | 9 Pandas        | W   | 0.486      | 0.500        | 0.082 (0.020)    | 0.690 (0.168)    | 0 (0.000) |    10.32 | avid, b0denmaster, PlesseN, robiin, twist |
|           30 |     2770 | 2024-04-17 | Nemiga          | L   | 0.475      | -            | -                | -                | -         |    -2.46 | avid, b0denmaster, PlesseN, robiin, twist |
|           29 |     2782 | 2024-04-17 | ECLOT           | L   | 0.473      | -            | -                | -                | -         |    -2.07 | avid, b0denmaster, PlesseN, robiin, twist |
|           28 |     2829 | 2024-04-15 | HAVU            | W   | 0.461      | 0.384        | -                | 0.160 (0.028)    | 0 (0.000) |     4.27 | avid, b0denmaster, PlesseN, robiin, twist |
|           27 |     2833 | 2024-04-15 | MOUZ NXT        | L   | 0.460      | -            | -                | -                | -         |    -3.68 | avid, b0denmaster, PlesseN, robiin, twist |
|           26 |     2861 | 2024-04-13 | ALTERNATE aTTaX | L   | 0.447      | -            | -                | -                | -         |    -4.91 | avid, b0denmaster, PlesseN, robiin, twist |
|           25 |     2902 | 2024-04-11 | Zero Tenacity   | W   | 0.434      | 0.384        | 0.137 (0.023)    | 1.000 (0.167)    | 0 (0.000) |    10.59 | avid, b0denmaster, PlesseN, robiin, twist |
|           24 |     2995 | 2024-04-09 | BLEED           | L   | 0.422      | -            | -                | -                | -         |    -4.30 | avid, b0denmaster, PlesseN, robiin, twist |
|           23 |     3011 | 2024-04-09 | Astralis Talent | W   | 0.419      | 0.371        | 0.009 (0.001)    | -                | 0 (0.000) |     5.29 | avid, b0denmaster, PlesseN, robiin, twist |
|           22 |     3056 | 2024-04-07 | Johnny Speeds   | L   | 0.408      | -            | -                | -                | -         |    -1.09 | avid, b0denmaster, PlesseN, robiin, twist |
|           21 |     3059 | 2024-04-07 | EYEBALLERS      | L   | 0.407      | -            | -                | -                | -         |    -5.63 | avid, b0denmaster, PlesseN, robiin, twist |
|           20 |     3068 | 2024-04-06 | Lilmix          | W   | 0.402      | -            | -                | -                | 0 (0.000) |     0.92 | avid, b0denmaster, PlesseN, robiin, twist |
|           19 |     3073 | 2024-04-06 | BetBoom         | L   | 0.401      | -            | -                | -                | -         |    -0.57 | avid, b0denmaster, PlesseN, robiin, twist |
|           18 |     3090 | 2024-04-05 | BLEED           | L   | 0.394      | -            | -                | -                | -         |    -4.18 | avid, b0denmaster, PlesseN, robiin, twist |
|           17 |     3123 | 2024-04-04 | BetBoom         | L   | 0.389      | -            | -                | -                | -         |    -0.57 | avid, b0denmaster, PlesseN, robiin, twist |
|           16 |     3133 | 2024-04-04 | Benched Heroes  | W   | 0.388      | -            | -                | -                | -         |     0.87 | avid, b0denmaster, PlesseN, robiin, twist |
|           15 |     3178 | 2024-04-03 | AMKAL           | L   | 0.380      | -            | -                | -                | -         |    -2.21 | avid, b0denmaster, PlesseN, robiin, twist |
|           14 |     3577 | 2024-03-13 | MOUZ NXT        | L   | 0.240      | -            | -                | -                | -         |    -2.04 | avid, b0denmaster, PlesseN, robiin, twist |
|           13 |     3609 | 2024-03-12 | Passion UA      | L   | 0.234      | -            | -                | -                | -         |    -1.76 | avid, b0denmaster, PlesseN, robiin, twist |
|           12 |     3649 | 2024-03-10 | EYEBALLERS      | W   | 0.221      | -            | -                | -                | -         |     3.92 | avid, b0denmaster, PlesseN, robiin, twist |
|           11 |     3659 | 2024-03-09 | BLUDS           | W   | 0.215      | -            | -                | -                | -         |     0.49 | avid, b0denmaster, PlesseN, robiin, twist |
|           10 |     3673 | 2024-03-09 | Johnny Speeds   | W   | 0.214      | 0.143        | 0.122 (0.004)    | 0.901 (0.028)    | -         |     6.21 | avid, b0denmaster, PlesseN, robiin, twist |
|            9 |     3680 | 2024-03-09 | Entropiq        | W   | 0.214      | -            | -                | -                | -         |     1.06 | avid, b0denmaster, PlesseN, robiin, twist |
|            8 |     3723 | 2024-03-07 | ex-Sprout       | W   | 0.200      | -            | -                | -                | -         |     0.82 | avid, b0denmaster, PlesseN, robiin, twist |
|            7 |     3754 | 2024-03-06 | Sashi           | L   | 0.194      | -            | -                | -                | -         |    -1.03 | avid, b0denmaster, PlesseN, robiin, twist |
|            6 |     3798 | 2024-03-05 | Viperio         | W   | 0.186      | -            | -                | -                | -         |     0.43 | avid, b0denmaster, PlesseN, robiin, twist |
|            5 |     3878 | 2024-03-01 | 9INE            | L   | 0.160      | -            | -                | -                | -         |    -4.44 | avid, b0denmaster, PlesseN, robiin, twist |
|            4 |     3905 | 2024-02-28 | Sangal          | W   | 0.147      | 0.143        | 0.219 (0.005)    | -                | -         |     3.91 | avid, b0denmaster, PlesseN, robiin, twist |
|            3 |     3960 | 2024-02-25 | ALTERNATE aTTaX | W   | 0.128      | 0.358        | 0.031 (0.001)    | 0.560 (0.026)    | -         |     2.75 | avid, b0denmaster, PlesseN, robiin, twist |
|            2 |     4131 | 2024-02-18 | Portugal        | W   | 0.081      | -            | -                | -                | -         |     0.72 | avid, b0denmaster, PlesseN, robiin, twist |
|            1 |     4360 | 2024-02-06 | 9INE            | W   | 0.000      | -            | -                | -                | -         |     0.00 | avid, b0denmaster, PlesseN, robiin, twist |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,482.11)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-16 |      0.874 | $2,000.00      | $1,748.89       |
| 2024-06-09 |      0.828 | $2,889.00      | $2,392.25       |
| 2024-05-18 |      0.682 | $500.00        | $340.97         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
