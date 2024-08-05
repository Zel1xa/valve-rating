### Roster Details<br />
Team Name: Alliance<br />
Roster: avid, b0denmaster, PlesseN, twist, upE<br />
Global Rank: [102](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [75]( ../standings_europe.md)<br />
<br />
Final Rank Value:  851.4<br />
<br />
Final Rank Value (851.4) = Starting Rank Value (850.2) + Head To Head Adjustments (1.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.332[<sup>2</sup>](#table1)
- Opponent Network: 0.093[<sup>2</sup>](#table1)
- LAN Wins: 0.094[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.2
- 400 + ( ( 0.220 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 850.2


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
|           47 |       55 | 2024-08-03 | RUSH B          | L   | 1.000      | -            | -                | -                | -         |   -11.48 | avid, b0denmaster, PlesseN, twist, upE    |
|           46 |      128 | 2024-08-01 | The Suspect     | W   | 1.000      | 0.342        | 0.008 (0.003)    | 0.230 (0.079)    | 0 (0.000) |    16.50 | avid, b0denmaster, PlesseN, twist, upE    |
|           45 |      256 | 2024-07-29 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -10.55 | avid, b0denmaster, PlesseN, twist, upE    |
|           44 |     1070 | 2024-06-14 | MIBR            | L   | 0.858      | -            | -                | -                | -         |    -1.24 | avid, b0denmaster, PlesseN, robiin, twist |
|           43 |     1086 | 2024-06-14 | Complexity      | L   | 0.856      | -            | -                | -                | -         |    -0.38 | avid, b0denmaster, PlesseN, robiin, twist |
|           42 |     1226 | 2024-06-09 | Johnny Speeds   | L   | 0.824      | -            | -                | -                | -         |    -2.78 | avid, b0denmaster, PlesseN, robiin, twist |
|           41 |     1249 | 2024-06-09 | Lilmix          | W   | 0.823      | 0.347        | 0.023 (0.007)    | 0.098 (0.028)    | 1 (0.823) |    13.46 | avid, b0denmaster, PlesseN, robiin, twist |
|           40 |     1645 | 2024-05-31 | VP.Prodigy      | L   | 0.762      | -            | -                | -                | -         |    -9.87 | avid, b0denmaster, PlesseN, robiin, twist |
|           39 |     1782 | 2024-05-24 | B8              | L   | 0.718      | -            | -                | -                | -         |    -3.65 | avid, b0denmaster, PlesseN, robiin, twist |
|           38 |     2156 | 2024-05-14 | kONO            | L   | 0.650      | -            | -                | -                | -         |   -10.61 | avid, b0denmaster, PlesseN, robiin, twist |
|           37 |     2460 | 2024-04-30 | B8              | L   | 0.556      | -            | -                | -                | -         |    -5.27 | avid, b0denmaster, PlesseN, robiin, twist |
|           36 |     2486 | 2024-04-29 | Endpoint        | W   | 0.549      | 0.384        | 0.012 (0.002)    | 0.522 (0.110)    | 0 (0.000) |     9.36 | avid, b0denmaster, PlesseN, robiin, twist |
|           35 |     2499 | 2024-04-28 | DMS             | W   | 0.543      | 0.500        | -                | 0.446 (0.121)    | 0 (0.000) |     9.39 | avid, b0denmaster, PlesseN, robiin, twist |
|           34 |     2538 | 2024-04-26 | B8              | L   | 0.531      | -            | -                | -                | -         |    -4.55 | avid, b0denmaster, PlesseN, robiin, twist |
|           33 |     2613 | 2024-04-23 | Metizport       | L   | 0.510      | -            | -                | -                | -         |    -7.67 | avid, b0denmaster, PlesseN, robiin, twist |
|           32 |     2630 | 2024-04-22 | B8              | W   | 0.503      | 0.384        | 0.165 (0.032)    | 0.951 (0.184)    | 0 (0.000) |    11.66 | avid, b0denmaster, PlesseN, robiin, twist |
|           31 |     2653 | 2024-04-21 | Sangal          | L   | 0.496      | -            | -                | -                | -         |    -2.71 | avid, b0denmaster, PlesseN, robiin, twist |
|           30 |     2734 | 2024-04-19 | 9 Pandas        | W   | 0.482      | 0.500        | 0.081 (0.020)    | 0.690 (0.166)    | 0 (0.000) |    10.24 | avid, b0denmaster, PlesseN, robiin, twist |
|           29 |     2806 | 2024-04-17 | Nemiga          | L   | 0.471      | -            | -                | -                | -         |    -2.23 | avid, b0denmaster, PlesseN, robiin, twist |
|           28 |     2818 | 2024-04-17 | ECLOT           | L   | 0.469      | -            | -                | -                | -         |    -2.04 | avid, b0denmaster, PlesseN, robiin, twist |
|           27 |     2865 | 2024-04-15 | HAVU            | W   | 0.457      | 0.384        | -                | 0.160 (0.028)    | 0 (0.000) |     4.21 | avid, b0denmaster, PlesseN, robiin, twist |
|           26 |     2869 | 2024-04-15 | MOUZ NXT        | L   | 0.456      | -            | -                | -                | -         |    -3.64 | avid, b0denmaster, PlesseN, robiin, twist |
|           25 |     2897 | 2024-04-13 | ALTERNATE aTTaX | L   | 0.443      | -            | -                | -                | -         |    -4.87 | avid, b0denmaster, PlesseN, robiin, twist |
|           24 |     2938 | 2024-04-11 | Zero Tenacity   | W   | 0.430      | 0.384        | 0.137 (0.023)    | 1.000 (0.165)    | 0 (0.000) |    10.51 | avid, b0denmaster, PlesseN, robiin, twist |
|           23 |     3031 | 2024-04-09 | BLEED           | L   | 0.417      | -            | -                | -                | -         |    -4.27 | avid, b0denmaster, PlesseN, robiin, twist |
|           22 |     3047 | 2024-04-09 | Astralis Talent | W   | 0.415      | 0.371        | 0.009 (0.001)    | 0.163 (0.025)    | 0 (0.000) |     5.23 | avid, b0denmaster, PlesseN, robiin, twist |
|           21 |     3092 | 2024-04-07 | Johnny Speeds   | L   | 0.404      | -            | -                | -                | -         |    -1.04 | avid, b0denmaster, PlesseN, robiin, twist |
|           20 |     3095 | 2024-04-07 | EYEBALLERS      | L   | 0.403      | -            | -                | -                | -         |    -5.59 | avid, b0denmaster, PlesseN, robiin, twist |
|           19 |     3104 | 2024-04-06 | Lilmix          | W   | 0.398      | -            | -                | -                | 0 (0.000) |     0.91 | avid, b0denmaster, PlesseN, robiin, twist |
|           18 |     3109 | 2024-04-06 | BetBoom         | L   | 0.397      | -            | -                | -                | -         |    -0.56 | avid, b0denmaster, PlesseN, robiin, twist |
|           17 |     3126 | 2024-04-05 | BLEED           | L   | 0.390      | -            | -                | -                | -         |    -4.15 | avid, b0denmaster, PlesseN, robiin, twist |
|           16 |     3159 | 2024-04-04 | BetBoom         | L   | 0.385      | -            | -                | -                | -         |    -0.57 | avid, b0denmaster, PlesseN, robiin, twist |
|           15 |     3169 | 2024-04-04 | Benched Heroes  | W   | 0.384      | -            | -                | -                | -         |     0.86 | avid, b0denmaster, PlesseN, robiin, twist |
|           14 |     3214 | 2024-04-03 | AMKAL           | L   | 0.376      | -            | -                | -                | -         |    -2.20 | avid, b0denmaster, PlesseN, robiin, twist |
|           13 |     3613 | 2024-03-13 | MOUZ NXT        | L   | 0.236      | -            | -                | -                | -         |    -2.00 | avid, b0denmaster, PlesseN, robiin, twist |
|           12 |     3645 | 2024-03-12 | Passion UA      | L   | 0.230      | -            | -                | -                | -         |    -1.70 | avid, b0denmaster, PlesseN, robiin, twist |
|           11 |     3685 | 2024-03-10 | EYEBALLERS      | W   | 0.217      | -            | -                | -                | -         |     3.83 | avid, b0denmaster, PlesseN, robiin, twist |
|           10 |     3695 | 2024-03-09 | BLUDS           | W   | 0.211      | -            | -                | -                | -         |     0.48 | avid, b0denmaster, PlesseN, robiin, twist |
|            9 |     3709 | 2024-03-09 | Johnny Speeds   | W   | 0.210      | 0.143        | 0.122 (0.004)    | 0.942 (0.028)    | -         |     6.11 | avid, b0denmaster, PlesseN, robiin, twist |
|            8 |     3716 | 2024-03-09 | Entropiq        | W   | 0.209      | -            | -                | -                | -         |     1.04 | avid, b0denmaster, PlesseN, robiin, twist |
|            7 |     3759 | 2024-03-07 | ex-Sprout       | W   | 0.196      | -            | -                | -                | -         |     0.79 | avid, b0denmaster, PlesseN, robiin, twist |
|            6 |     3790 | 2024-03-06 | Sashi           | L   | 0.189      | -            | -                | -                | -         |    -0.99 | avid, b0denmaster, PlesseN, robiin, twist |
|            5 |     3834 | 2024-03-05 | Viperio         | W   | 0.182      | -            | -                | -                | -         |     0.42 | avid, b0denmaster, PlesseN, robiin, twist |
|            4 |     3914 | 2024-03-01 | 9INE            | L   | 0.156      | -            | -                | -                | -         |    -4.33 | avid, b0denmaster, PlesseN, robiin, twist |
|            3 |     3941 | 2024-02-28 | Sangal          | W   | 0.143      | 0.143        | 0.219 (0.004)    | -                | -         |     3.82 | avid, b0denmaster, PlesseN, robiin, twist |
|            2 |     3996 | 2024-02-25 | ALTERNATE aTTaX | W   | 0.124      | 0.358        | 0.031 (0.001)    | -                | -         |     2.65 | avid, b0denmaster, PlesseN, robiin, twist |
|            1 |     4167 | 2024-02-18 | Portugal        | W   | 0.076      | -            | -                | -                | -         |     0.68 | avid, b0denmaster, PlesseN, robiin, twist |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,459.66)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-16 |      0.870 | $2,000.00      | $1,740.56       |
| 2024-06-09 |      0.824 | $2,889.00      | $2,380.22       |
| 2024-05-18 |      0.678 | $500.00        | $338.89         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
