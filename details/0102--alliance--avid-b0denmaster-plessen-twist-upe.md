### Roster Details<br />
Team Name: Alliance<br />
Roster: avid, b0denmaster, PlesseN, twist, upE<br />
Global Rank: [102](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [75]( ../standings_europe.md)<br />
<br />
Final Rank Value:  851.0<br />
<br />
Final Rank Value (851.0) = Starting Rank Value (850.0) + Head To Head Adjustments (1.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.333[<sup>2</sup>](#table1)
- Opponent Network: 0.093[<sup>2</sup>](#table1)
- LAN Wins: 0.095[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.0
- 400 + ( ( 0.220 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 850.0


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
|           48 |       18 | 2024-08-03 | RUSH B          | L   | 1.000      | -            | -                | -                | -         |   -11.84 | avid, b0denmaster, PlesseN, twist, upE    |
|           47 |       89 | 2024-08-01 | The Suspect     | W   | 1.000      | 0.342        | 0.008 (0.003)    | 0.189 (0.065)    | 0 (0.000) |    16.39 | avid, b0denmaster, PlesseN, twist, upE    |
|           46 |      215 | 2024-07-29 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -11.28 | avid, b0denmaster, PlesseN, twist, upE    |
|           45 |     1030 | 2024-06-14 | MIBR            | L   | 0.865      | -            | -                | -                | -         |    -1.25 | avid, b0denmaster, PlesseN, robiin, twist |
|           44 |     1046 | 2024-06-14 | Complexity      | L   | 0.863      | -            | -                | -                | -         |    -0.40 | avid, b0denmaster, PlesseN, robiin, twist |
|           43 |     1186 | 2024-06-09 | Johnny Speeds   | L   | 0.831      | -            | -                | -                | -         |    -2.91 | avid, b0denmaster, PlesseN, robiin, twist |
|           42 |     1209 | 2024-06-09 | Lilmix          | W   | 0.830      | 0.347        | 0.023 (0.007)    | 0.098 (0.028)    | 1 (0.830) |    13.55 | avid, b0denmaster, PlesseN, robiin, twist |
|           41 |     1605 | 2024-05-31 | VP.Prodigy      | L   | 0.769      | -            | -                | -                | -         |   -10.02 | avid, b0denmaster, PlesseN, robiin, twist |
|           40 |     1742 | 2024-05-24 | B8              | L   | 0.725      | -            | -                | -                | -         |    -3.71 | avid, b0denmaster, PlesseN, robiin, twist |
|           39 |     2116 | 2024-05-14 | kONO            | L   | 0.657      | -            | -                | -                | -         |   -10.73 | avid, b0denmaster, PlesseN, robiin, twist |
|           38 |     2420 | 2024-04-30 | B8              | L   | 0.564      | -            | -                | -                | -         |    -5.36 | avid, b0denmaster, PlesseN, robiin, twist |
|           37 |     2446 | 2024-04-29 | Endpoint        | W   | 0.556      | 0.384        | 0.012 (0.003)    | 0.522 (0.112)    | 0 (0.000) |     9.45 | avid, b0denmaster, PlesseN, robiin, twist |
|           36 |     2459 | 2024-04-28 | DMS             | W   | 0.550      | 0.500        | -                | 0.446 (0.123)    | 0 (0.000) |     9.48 | avid, b0denmaster, PlesseN, robiin, twist |
|           35 |     2498 | 2024-04-26 | B8              | L   | 0.539      | -            | -                | -                | -         |    -4.63 | avid, b0denmaster, PlesseN, robiin, twist |
|           34 |     2572 | 2024-04-23 | Metizport       | L   | 0.517      | -            | -                | -                | -         |    -6.57 | avid, b0denmaster, PlesseN, robiin, twist |
|           33 |     2589 | 2024-04-22 | B8              | W   | 0.510      | 0.384        | 0.165 (0.032)    | 0.913 (0.179)    | 0 (0.000) |    11.84 | avid, b0denmaster, PlesseN, robiin, twist |
|           32 |     2612 | 2024-04-21 | Sangal          | L   | 0.503      | -            | -                | -                | -         |    -2.81 | avid, b0denmaster, PlesseN, robiin, twist |
|           31 |     2693 | 2024-04-19 | 9 Pandas        | W   | 0.489      | 0.500        | 0.082 (0.020)    | 0.691 (0.169)    | 0 (0.000) |    10.40 | avid, b0denmaster, PlesseN, robiin, twist |
|           30 |     2765 | 2024-04-17 | Nemiga          | L   | 0.478      | -            | -                | -                | -         |    -2.48 | avid, b0denmaster, PlesseN, robiin, twist |
|           29 |     2777 | 2024-04-17 | ECLOT           | L   | 0.476      | -            | -                | -                | -         |    -2.09 | avid, b0denmaster, PlesseN, robiin, twist |
|           28 |     2824 | 2024-04-15 | HAVU            | W   | 0.464      | 0.384        | -                | 0.160 (0.029)    | 0 (0.000) |     4.29 | avid, b0denmaster, PlesseN, robiin, twist |
|           27 |     2828 | 2024-04-15 | MOUZ NXT        | L   | 0.463      | -            | -                | -                | -         |    -3.71 | avid, b0denmaster, PlesseN, robiin, twist |
|           26 |     2856 | 2024-04-13 | ALTERNATE aTTaX | L   | 0.450      | -            | -                | -                | -         |    -4.95 | avid, b0denmaster, PlesseN, robiin, twist |
|           25 |     2897 | 2024-04-11 | Zero Tenacity   | W   | 0.437      | 0.384        | 0.137 (0.023)    | 1.000 (0.168)    | 0 (0.000) |    10.65 | avid, b0denmaster, PlesseN, robiin, twist |
|           24 |     2990 | 2024-04-09 | BLEED           | L   | 0.425      | -            | -                | -                | -         |    -4.32 | avid, b0denmaster, PlesseN, robiin, twist |
|           23 |     3006 | 2024-04-09 | Astralis Talent | W   | 0.422      | 0.371        | 0.009 (0.001)    | -                | 0 (0.000) |     5.32 | avid, b0denmaster, PlesseN, robiin, twist |
|           22 |     3051 | 2024-04-07 | Johnny Speeds   | L   | 0.411      | -            | -                | -                | -         |    -1.10 | avid, b0denmaster, PlesseN, robiin, twist |
|           21 |     3054 | 2024-04-07 | EYEBALLERS      | L   | 0.411      | -            | -                | -                | -         |    -5.68 | avid, b0denmaster, PlesseN, robiin, twist |
|           20 |     3063 | 2024-04-06 | Lilmix          | W   | 0.405      | -            | -                | -                | 0 (0.000) |     0.93 | avid, b0denmaster, PlesseN, robiin, twist |
|           19 |     3068 | 2024-04-06 | BetBoom         | L   | 0.404      | -            | -                | -                | -         |    -0.57 | avid, b0denmaster, PlesseN, robiin, twist |
|           18 |     3085 | 2024-04-05 | BLEED           | L   | 0.398      | -            | -                | -                | -         |    -4.21 | avid, b0denmaster, PlesseN, robiin, twist |
|           17 |     3118 | 2024-04-04 | BetBoom         | L   | 0.392      | -            | -                | -                | -         |    -0.57 | avid, b0denmaster, PlesseN, robiin, twist |
|           16 |     3128 | 2024-04-04 | Benched Heroes  | W   | 0.391      | -            | -                | -                | -         |     0.87 | avid, b0denmaster, PlesseN, robiin, twist |
|           15 |     3173 | 2024-04-03 | AMKAL           | L   | 0.383      | -            | -                | -                | -         |    -2.23 | avid, b0denmaster, PlesseN, robiin, twist |
|           14 |     3571 | 2024-03-13 | MOUZ NXT        | L   | 0.243      | -            | -                | -                | -         |    -2.07 | avid, b0denmaster, PlesseN, robiin, twist |
|           13 |     3603 | 2024-03-12 | Passion UA      | L   | 0.237      | -            | -                | -                | -         |    -1.79 | avid, b0denmaster, PlesseN, robiin, twist |
|           12 |     3643 | 2024-03-10 | EYEBALLERS      | W   | 0.224      | -            | -                | -                | -         |     3.97 | avid, b0denmaster, PlesseN, robiin, twist |
|           11 |     3653 | 2024-03-09 | BLUDS           | W   | 0.218      | -            | -                | -                | -         |     0.50 | avid, b0denmaster, PlesseN, robiin, twist |
|           10 |     3667 | 2024-03-09 | Johnny Speeds   | W   | 0.217      | 0.143        | 0.122 (0.004)    | 0.901 (0.028)    | -         |     6.30 | avid, b0denmaster, PlesseN, robiin, twist |
|            9 |     3674 | 2024-03-09 | Entropiq        | W   | 0.217      | -            | -                | -                | -         |     1.08 | avid, b0denmaster, PlesseN, robiin, twist |
|            8 |     3717 | 2024-03-07 | ex-Sprout       | W   | 0.203      | -            | -                | -                | -         |     0.84 | avid, b0denmaster, PlesseN, robiin, twist |
|            7 |     3748 | 2024-03-06 | Sashi           | L   | 0.197      | -            | -                | -                | -         |    -1.05 | avid, b0denmaster, PlesseN, robiin, twist |
|            6 |     3792 | 2024-03-05 | Viperio         | W   | 0.189      | -            | -                | -                | -         |     0.44 | avid, b0denmaster, PlesseN, robiin, twist |
|            5 |     3872 | 2024-03-01 | 9INE            | L   | 0.163      | -            | -                | -                | -         |    -4.53 | avid, b0denmaster, PlesseN, robiin, twist |
|            4 |     3899 | 2024-02-28 | Sangal          | W   | 0.150      | 0.143        | 0.219 (0.005)    | -                | -         |     3.99 | avid, b0denmaster, PlesseN, robiin, twist |
|            3 |     3954 | 2024-02-25 | ALTERNATE aTTaX | W   | 0.131      | 0.358        | 0.032 (0.001)    | 0.561 (0.026)    | -         |     2.81 | avid, b0denmaster, PlesseN, robiin, twist |
|            2 |     4125 | 2024-02-18 | Portugal        | W   | 0.084      | -            | -                | -                | -         |     0.75 | avid, b0denmaster, PlesseN, robiin, twist |
|            1 |     4353 | 2024-02-06 | 9INE            | W   | 0.003      | -            | -                | -                | -         |     0.01 | avid, b0denmaster, PlesseN, robiin, twist |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,498.58)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-16 |      0.877 | $2,000.00      | $1,755.00       |
| 2024-06-09 |      0.831 | $2,889.00      | $2,401.08       |
| 2024-05-18 |      0.685 | $500.00        | $342.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
