### Roster Details<br />
Team Name: Alliance<br />
Roster: avid, b0denmaster, PlesseN, twist, upE<br />
Global Rank: [119](../../standings_global_2024_08_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_08_06.md)<br />
Regional Rank: [84]( ../../standings_europe_2024_08_06.md)<br />
<br />
Final Rank Value:  821.4<br />
<br />
Final Rank Value (821.4) = Starting Rank Value (851.1) + Head To Head Adjustments (-29.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.332[<sup>2</sup>](#table1)
- Opponent Network: 0.090[<sup>2</sup>](#table1)
- LAN Wins: 0.094[<sup>2</sup>](#table1)

The average of these factors is 0.219<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 851.1
- 400 + ( ( 0.219 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 851.1


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
|           49 |       41 | 2024-08-05 | Sampi           | L   | 1.000      | -            | -                | -                | -         |   -13.43 | avid, b0denmaster, PlesseN, twist, upE    |
|           48 |       49 | 2024-08-04 | Young Ninjas    | L   | 1.000      | -            | -                | -                | -         |   -19.19 | avid, b0denmaster, PlesseN, twist, upE    |
|           47 |      102 | 2024-08-03 | RUSH B          | L   | 1.000      | -            | -                | -                | -         |   -11.46 | avid, b0denmaster, PlesseN, twist, upE    |
|           46 |      175 | 2024-08-01 | The Suspect     | W   | 1.000      | 0.342        | 0.008 (0.003)    | 0.223 (0.076)    | 0 (0.000) |    16.45 | avid, b0denmaster, PlesseN, twist, upE    |
|           45 |      303 | 2024-07-29 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -10.30 | avid, b0denmaster, PlesseN, twist, upE    |
|           44 |     1117 | 2024-06-14 | MIBR            | L   | 0.847      | -            | -                | -                | -         |    -1.26 | avid, b0denmaster, PlesseN, robiin, twist |
|           43 |     1133 | 2024-06-14 | Complexity      | L   | 0.845      | -            | -                | -                | -         |    -0.38 | avid, b0denmaster, PlesseN, robiin, twist |
|           42 |     1273 | 2024-06-09 | Johnny Speeds   | L   | 0.813      | -            | -                | -                | -         |    -2.71 | avid, b0denmaster, PlesseN, robiin, twist |
|           41 |     1296 | 2024-06-09 | Lilmix          | W   | 0.812      | 0.347        | 0.023 (0.006)    | 0.095 (0.027)    | 1 (0.812) |    13.25 | avid, b0denmaster, PlesseN, robiin, twist |
|           40 |     1692 | 2024-05-31 | VP.Prodigy      | L   | 0.751      | -            | -                | -                | -         |    -9.74 | avid, b0denmaster, PlesseN, robiin, twist |
|           39 |     1829 | 2024-05-24 | B8              | L   | 0.707      | -            | -                | -                | -         |    -3.58 | avid, b0denmaster, PlesseN, robiin, twist |
|           38 |     2203 | 2024-05-14 | kONO            | L   | 0.639      | -            | -                | -                | -         |   -10.38 | avid, b0denmaster, PlesseN, robiin, twist |
|           37 |     2507 | 2024-04-30 | B8              | L   | 0.545      | -            | -                | -                | -         |    -5.10 | avid, b0denmaster, PlesseN, robiin, twist |
|           36 |     2533 | 2024-04-29 | Endpoint        | W   | 0.538      | 0.384        | 0.012 (0.002)    | 0.540 (0.112)    | 0 (0.000) |     9.22 | avid, b0denmaster, PlesseN, robiin, twist |
|           35 |     2546 | 2024-04-28 | DMS             | W   | 0.532      | 0.500        | -                | 0.428 (0.114)    | 0 (0.000) |     9.18 | avid, b0denmaster, PlesseN, robiin, twist |
|           34 |     2585 | 2024-04-26 | B8              | L   | 0.520      | -            | -                | -                | -         |    -4.41 | avid, b0denmaster, PlesseN, robiin, twist |
|           33 |     2660 | 2024-04-23 | Metizport       | L   | 0.499      | -            | -                | -                | -         |    -6.30 | avid, b0denmaster, PlesseN, robiin, twist |
|           32 |     2677 | 2024-04-22 | B8              | W   | 0.492      | 0.384        | 0.170 (0.032)    | 0.912 (0.172)    | 0 (0.000) |    11.48 | avid, b0denmaster, PlesseN, robiin, twist |
|           31 |     2700 | 2024-04-21 | Sangal          | L   | 0.485      | -            | -                | -                | -         |    -2.33 | avid, b0denmaster, PlesseN, robiin, twist |
|           30 |     2781 | 2024-04-19 | 9 Pandas        | W   | 0.471      | 0.500        | 0.081 (0.019)    | 0.700 (0.165)    | 0 (0.000) |    10.13 | avid, b0denmaster, PlesseN, robiin, twist |
|           29 |     2853 | 2024-04-17 | Nemiga          | L   | 0.460      | -            | -                | -                | -         |    -2.20 | avid, b0denmaster, PlesseN, robiin, twist |
|           28 |     2865 | 2024-04-17 | ECLOT           | L   | 0.458      | -            | -                | -                | -         |    -1.97 | avid, b0denmaster, PlesseN, robiin, twist |
|           27 |     2912 | 2024-04-15 | HAVU            | W   | 0.446      | 0.384        | -                | 0.152 (0.026)    | 0 (0.000) |     4.09 | avid, b0denmaster, PlesseN, robiin, twist |
|           26 |     2916 | 2024-04-15 | MOUZ NXT        | L   | 0.445      | -            | -                | -                | -         |    -3.47 | avid, b0denmaster, PlesseN, robiin, twist |
|           25 |     2944 | 2024-04-13 | ALTERNATE aTTaX | L   | 0.432      | -            | -                | -                | -         |    -4.67 | avid, b0denmaster, PlesseN, robiin, twist |
|           24 |     2985 | 2024-04-11 | Zero Tenacity   | W   | 0.419      | 0.384        | 0.143 (0.023)    | 1.000 (0.161)    | 0 (0.000) |    10.27 | avid, b0denmaster, PlesseN, robiin, twist |
|           23 |     3078 | 2024-04-09 | BLEED           | L   | 0.407      | -            | -                | -                | -         |    -4.17 | avid, b0denmaster, PlesseN, robiin, twist |
|           22 |     3094 | 2024-04-09 | Astralis Talent | W   | 0.404      | 0.371        | 0.009 (0.001)    | 0.156 (0.023)    | 0 (0.000) |     5.06 | avid, b0denmaster, PlesseN, robiin, twist |
|           21 |     3139 | 2024-04-07 | Johnny Speeds   | L   | 0.393      | -            | -                | -                | -         |    -0.99 | avid, b0denmaster, PlesseN, robiin, twist |
|           20 |     3142 | 2024-04-07 | EYEBALLERS      | L   | 0.392      | -            | -                | -                | -         |    -5.41 | avid, b0denmaster, PlesseN, robiin, twist |
|           19 |     3151 | 2024-04-06 | Lilmix          | W   | 0.387      | -            | -                | -                | 0 (0.000) |     0.88 | avid, b0denmaster, PlesseN, robiin, twist |
|           18 |     3156 | 2024-04-06 | BetBoom         | L   | 0.386      | -            | -                | -                | -         |    -0.56 | avid, b0denmaster, PlesseN, robiin, twist |
|           17 |     3173 | 2024-04-05 | BLEED           | L   | 0.379      | -            | -                | -                | -         |    -4.04 | avid, b0denmaster, PlesseN, robiin, twist |
|           16 |     3206 | 2024-04-04 | BetBoom         | L   | 0.374      | -            | -                | -                | -         |    -0.56 | avid, b0denmaster, PlesseN, robiin, twist |
|           15 |     3216 | 2024-04-04 | Benched Heroes  | W   | 0.373      | -            | -                | -                | -         |     0.83 | avid, b0denmaster, PlesseN, robiin, twist |
|           14 |     3261 | 2024-04-03 | AMKAL           | L   | 0.365      | -            | -                | -                | -         |    -2.12 | avid, b0denmaster, PlesseN, robiin, twist |
|           13 |     3660 | 2024-03-13 | MOUZ NXT        | L   | 0.225      | -            | -                | -                | -         |    -1.87 | avid, b0denmaster, PlesseN, robiin, twist |
|           12 |     3692 | 2024-03-12 | Passion UA      | L   | 0.219      | -            | -                | -                | -         |    -1.58 | avid, b0denmaster, PlesseN, robiin, twist |
|           11 |     3732 | 2024-03-10 | EYEBALLERS      | W   | 0.206      | -            | -                | -                | -         |     3.65 | avid, b0denmaster, PlesseN, robiin, twist |
|           10 |     3742 | 2024-03-09 | BLUDS           | W   | 0.200      | -            | -                | -                | -         |     0.45 | avid, b0denmaster, PlesseN, robiin, twist |
|            9 |     3756 | 2024-03-09 | Johnny Speeds   | W   | 0.199      | 0.143        | 0.122 (0.003)    | 1.000 (0.028)    | -         |     5.80 | avid, b0denmaster, PlesseN, robiin, twist |
|            8 |     3763 | 2024-03-09 | Entropiq        | W   | 0.198      | -            | -                | -                | -         |     0.97 | avid, b0denmaster, PlesseN, robiin, twist |
|            7 |     3806 | 2024-03-07 | ex-Sprout       | W   | 0.185      | -            | -                | -                | -         |     0.71 | avid, b0denmaster, PlesseN, robiin, twist |
|            6 |     3837 | 2024-03-06 | Sashi           | L   | 0.178      | -            | -                | -                | -         |    -0.93 | avid, b0denmaster, PlesseN, robiin, twist |
|            5 |     3881 | 2024-03-05 | Viperio         | W   | 0.171      | -            | -                | -                | -         |     0.39 | avid, b0denmaster, PlesseN, robiin, twist |
|            4 |     3961 | 2024-03-01 | 9INE            | L   | 0.145      | -            | -                | -                | -         |    -4.03 | avid, b0denmaster, PlesseN, robiin, twist |
|            3 |     3988 | 2024-02-28 | Sangal          | W   | 0.132      | 0.143        | 0.288 (0.005)    | -                | -         |     3.61 | avid, b0denmaster, PlesseN, robiin, twist |
|            2 |     4043 | 2024-02-25 | ALTERNATE aTTaX | W   | 0.113      | 0.358        | 0.031 (0.001)    | -                | -         |     2.43 | avid, b0denmaster, PlesseN, robiin, twist |
|            1 |     4214 | 2024-02-18 | Portugal        | W   | 0.065      | -            | -                | -                | -         |     0.58 | avid, b0denmaster, PlesseN, robiin, twist |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,400.53)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-16 |      0.859 | $2,000.00      | $1,718.61       |
| 2024-06-09 |      0.813 | $2,889.00      | $2,348.52       |
| 2024-05-18 |      0.667 | $500.00        | $333.40         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
