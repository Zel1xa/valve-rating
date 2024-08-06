### Roster Details<br />
Team Name: Alliance<br />
Roster: avid, b0denmaster, PlesseN, twist, upE<br />
Global Rank: [120](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [85]( ../standings_europe.md)<br />
<br />
Final Rank Value:  818.7<br />
<br />
Final Rank Value (818.7) = Starting Rank Value (850.4) + Head To Head Adjustments (-31.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.331[<sup>2</sup>](#table1)
- Opponent Network: 0.092[<sup>2</sup>](#table1)
- LAN Wins: 0.094[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.4
- 400 + ( ( 0.220 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 850.4


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
|           49 |       18 | 2024-08-05 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -13.73 | avid, b0denmaster, PlesseN, twist, upE    |
|           48 |       26 | 2024-08-04 | Young Ninjas    | L   | 1.000      | -            | -                | -                | -         |   -19.07 | avid, b0denmaster, PlesseN, twist, upE    |
|           47 |       79 | 2024-08-03 | RUSH B          | L   | 1.000      | -            | -                | -                | -         |   -11.47 | avid, b0denmaster, PlesseN, twist, upE    |
|           46 |      152 | 2024-08-01 | The Suspect     | W   | 1.000      | 0.342        | 0.008 (0.003)    | 0.227 (0.078)    | 0 (0.000) |    16.51 | avid, b0denmaster, PlesseN, twist, upE    |
|           45 |      280 | 2024-07-29 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -10.38 | avid, b0denmaster, PlesseN, twist, upE    |
|           44 |     1094 | 2024-06-14 | MIBR            | L   | 0.851      | -            | -                | -                | -         |    -1.24 | avid, b0denmaster, PlesseN, robiin, twist |
|           43 |     1110 | 2024-06-14 | Complexity      | L   | 0.849      | -            | -                | -                | -         |    -0.38 | avid, b0denmaster, PlesseN, robiin, twist |
|           42 |     1250 | 2024-06-09 | Johnny Speeds   | L   | 0.817      | -            | -                | -                | -         |    -2.74 | avid, b0denmaster, PlesseN, robiin, twist |
|           41 |     1273 | 2024-06-09 | Lilmix          | W   | 0.816      | 0.347        | 0.023 (0.006)    | 0.097 (0.027)    | 1 (0.816) |    13.38 | avid, b0denmaster, PlesseN, robiin, twist |
|           40 |     1669 | 2024-05-31 | VP.Prodigy      | L   | 0.756      | -            | -                | -                | -         |    -9.77 | avid, b0denmaster, PlesseN, robiin, twist |
|           39 |     1806 | 2024-05-24 | B8              | L   | 0.711      | -            | -                | -                | -         |    -3.62 | avid, b0denmaster, PlesseN, robiin, twist |
|           38 |     2180 | 2024-05-14 | kONO            | L   | 0.643      | -            | -                | -                | -         |   -10.51 | avid, b0denmaster, PlesseN, robiin, twist |
|           37 |     2484 | 2024-04-30 | B8              | L   | 0.550      | -            | -                | -                | -         |    -5.18 | avid, b0denmaster, PlesseN, robiin, twist |
|           36 |     2510 | 2024-04-29 | Endpoint        | W   | 0.542      | 0.384        | 0.012 (0.002)    | 0.514 (0.107)    | 0 (0.000) |     9.27 | avid, b0denmaster, PlesseN, robiin, twist |
|           35 |     2523 | 2024-04-28 | DMS             | W   | 0.537      | 0.500        | -                | 0.438 (0.118)    | 0 (0.000) |     9.28 | avid, b0denmaster, PlesseN, robiin, twist |
|           34 |     2562 | 2024-04-26 | B8              | L   | 0.525      | -            | -                | -                | -         |    -4.48 | avid, b0denmaster, PlesseN, robiin, twist |
|           33 |     2637 | 2024-04-23 | Metizport       | L   | 0.503      | -            | -                | -                | -         |    -7.59 | avid, b0denmaster, PlesseN, robiin, twist |
|           32 |     2654 | 2024-04-22 | B8              | W   | 0.496      | 0.384        | 0.164 (0.031)    | 0.934 (0.178)    | 0 (0.000) |    11.52 | avid, b0denmaster, PlesseN, robiin, twist |
|           31 |     2677 | 2024-04-21 | Sangal          | L   | 0.489      | -            | -                | -                | -         |    -2.65 | avid, b0denmaster, PlesseN, robiin, twist |
|           30 |     2758 | 2024-04-19 | 9 Pandas        | W   | 0.476      | 0.500        | 0.081 (0.019)    | 0.717 (0.170)    | 0 (0.000) |    10.08 | avid, b0denmaster, PlesseN, robiin, twist |
|           29 |     2830 | 2024-04-17 | Nemiga          | L   | 0.464      | -            | -                | -                | -         |    -2.21 | avid, b0denmaster, PlesseN, robiin, twist |
|           28 |     2842 | 2024-04-17 | ECLOT           | L   | 0.463      | -            | -                | -                | -         |    -2.00 | avid, b0denmaster, PlesseN, robiin, twist |
|           27 |     2889 | 2024-04-15 | HAVU            | W   | 0.450      | 0.384        | -                | 0.156 (0.027)    | 0 (0.000) |     4.14 | avid, b0denmaster, PlesseN, robiin, twist |
|           26 |     2893 | 2024-04-15 | MOUZ NXT        | L   | 0.449      | -            | -                | -                | -         |    -3.54 | avid, b0denmaster, PlesseN, robiin, twist |
|           25 |     2921 | 2024-04-13 | ALTERNATE aTTaX | L   | 0.436      | -            | -                | -                | -         |    -4.79 | avid, b0denmaster, PlesseN, robiin, twist |
|           24 |     2962 | 2024-04-11 | Zero Tenacity   | W   | 0.423      | 0.384        | 0.143 (0.023)    | 1.000 (0.163)    | 0 (0.000) |    10.39 | avid, b0denmaster, PlesseN, robiin, twist |
|           23 |     3055 | 2024-04-09 | BLEED           | L   | 0.411      | -            | -                | -                | -         |    -4.22 | avid, b0denmaster, PlesseN, robiin, twist |
|           22 |     3071 | 2024-04-09 | Astralis Talent | W   | 0.409      | 0.371        | 0.009 (0.001)    | 0.160 (0.024)    | 0 (0.000) |     5.11 | avid, b0denmaster, PlesseN, robiin, twist |
|           21 |     3116 | 2024-04-07 | Johnny Speeds   | L   | 0.398      | -            | -                | -                | -         |    -1.01 | avid, b0denmaster, PlesseN, robiin, twist |
|           20 |     3119 | 2024-04-07 | EYEBALLERS      | L   | 0.397      | -            | -                | -                | -         |    -5.48 | avid, b0denmaster, PlesseN, robiin, twist |
|           19 |     3128 | 2024-04-06 | Lilmix          | W   | 0.392      | -            | -                | -                | 0 (0.000) |     0.90 | avid, b0denmaster, PlesseN, robiin, twist |
|           18 |     3133 | 2024-04-06 | BetBoom         | L   | 0.390      | -            | -                | -                | -         |    -0.56 | avid, b0denmaster, PlesseN, robiin, twist |
|           17 |     3150 | 2024-04-05 | BLEED           | L   | 0.384      | -            | -                | -                | -         |    -4.10 | avid, b0denmaster, PlesseN, robiin, twist |
|           16 |     3183 | 2024-04-04 | BetBoom         | L   | 0.378      | -            | -                | -                | -         |    -0.56 | avid, b0denmaster, PlesseN, robiin, twist |
|           15 |     3193 | 2024-04-04 | Benched Heroes  | W   | 0.377      | -            | -                | -                | -         |     0.84 | avid, b0denmaster, PlesseN, robiin, twist |
|           14 |     3238 | 2024-04-03 | AMKAL           | L   | 0.369      | -            | -                | -                | -         |    -2.16 | avid, b0denmaster, PlesseN, robiin, twist |
|           13 |     3637 | 2024-03-13 | MOUZ NXT        | L   | 0.230      | -            | -                | -                | -         |    -1.92 | avid, b0denmaster, PlesseN, robiin, twist |
|           12 |     3669 | 2024-03-12 | Passion UA      | L   | 0.223      | -            | -                | -                | -         |    -1.62 | avid, b0denmaster, PlesseN, robiin, twist |
|           11 |     3709 | 2024-03-10 | EYEBALLERS      | W   | 0.210      | -            | -                | -                | -         |     3.72 | avid, b0denmaster, PlesseN, robiin, twist |
|           10 |     3719 | 2024-03-09 | BLUDS           | W   | 0.205      | -            | -                | -                | -         |     0.47 | avid, b0denmaster, PlesseN, robiin, twist |
|            9 |     3733 | 2024-03-09 | Johnny Speeds   | W   | 0.204      | 0.143        | 0.122 (0.004)    | 1.000 (0.029)    | -         |     5.92 | avid, b0denmaster, PlesseN, robiin, twist |
|            8 |     3740 | 2024-03-09 | Entropiq        | W   | 0.203      | -            | -                | -                | -         |     1.00 | avid, b0denmaster, PlesseN, robiin, twist |
|            7 |     3783 | 2024-03-07 | ex-Sprout       | W   | 0.189      | -            | -                | -                | -         |     0.75 | avid, b0denmaster, PlesseN, robiin, twist |
|            6 |     3814 | 2024-03-06 | Sashi           | L   | 0.183      | -            | -                | -                | -         |    -0.96 | avid, b0denmaster, PlesseN, robiin, twist |
|            5 |     3858 | 2024-03-05 | Viperio         | W   | 0.176      | -            | -                | -                | -         |     0.40 | avid, b0denmaster, PlesseN, robiin, twist |
|            4 |     3938 | 2024-03-01 | 9INE            | L   | 0.150      | -            | -                | -                | -         |    -4.14 | avid, b0denmaster, PlesseN, robiin, twist |
|            3 |     3965 | 2024-02-28 | Sangal          | W   | 0.136      | 0.143        | 0.219 (0.004)    | -                | -         |     3.64 | avid, b0denmaster, PlesseN, robiin, twist |
|            2 |     4020 | 2024-02-25 | ALTERNATE aTTaX | W   | 0.117      | 0.358        | 0.031 (0.001)    | -                | -         |     2.51 | avid, b0denmaster, PlesseN, robiin, twist |
|            1 |     4191 | 2024-02-18 | Portugal        | W   | 0.070      | -            | -                | -                | -         |     0.62 | avid, b0denmaster, PlesseN, robiin, twist |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,423.73)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-16 |      0.864 | $2,000.00      | $1,727.22       |
| 2024-06-09 |      0.817 | $2,889.00      | $2,360.96       |
| 2024-05-18 |      0.671 | $500.00        | $335.56         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
