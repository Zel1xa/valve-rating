### Roster Details<br />
Team Name: Alliance<br />
Roster: avid, b0denmaster, PlesseN, twist, upE<br />
Global Rank: [101](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [75]( ../standings_europe.md)<br />
<br />
Final Rank Value:  852.2<br />
<br />
Final Rank Value (852.2) = Starting Rank Value (852.1) + Head To Head Adjustments (0.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.333[<sup>2</sup>](#table1)
- Opponent Network: 0.096[<sup>2</sup>](#table1)
- LAN Wins: 0.095[<sup>2</sup>](#table1)

The average of these factors is 0.221<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 852.1
- 400 + ( ( 0.221 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 852.1


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
|           48 |       15 | 2024-08-03 | RUSH B          | L   | 1.000      | -            | -                | -                | -         |   -11.90 | avid, b0denmaster, PlesseN, twist, upE    |
|           47 |       67 | 2024-08-01 | The Suspect     | W   | 1.000      | 0.342        | 0.008 (0.003)    | 0.195 (0.067)    | 0 (0.000) |    16.38 | avid, b0denmaster, PlesseN, twist, upE    |
|           46 |      192 | 2024-07-29 | SINNERS         | L   | 1.000      | -            | -                | -                | -         |   -11.42 | avid, b0denmaster, PlesseN, twist, upE    |
|           45 |      982 | 2024-06-14 | MIBR            | L   | 0.867      | -            | -                | -                | -         |    -1.34 | avid, b0denmaster, PlesseN, robiin, twist |
|           44 |      996 | 2024-06-14 | Complexity      | L   | 0.865      | -            | -                | -                | -         |    -0.41 | avid, b0denmaster, PlesseN, robiin, twist |
|           43 |     1131 | 2024-06-09 | Johnny Speeds   | L   | 0.833      | -            | -                | -                | -         |    -2.92 | avid, b0denmaster, PlesseN, robiin, twist |
|           42 |     1154 | 2024-06-09 | Lilmix          | W   | 0.832      | 0.347        | 0.023 (0.007)    | 0.101 (0.029)    | 1 (0.832) |    13.55 | avid, b0denmaster, PlesseN, robiin, twist |
|           41 |     1542 | 2024-05-31 | VP.Prodigy      | L   | 0.771      | -            | -                | -                | -         |   -10.04 | avid, b0denmaster, PlesseN, robiin, twist |
|           40 |     1678 | 2024-05-24 | B8              | L   | 0.727      | -            | -                | -                | -         |    -3.77 | avid, b0denmaster, PlesseN, robiin, twist |
|           39 |     2051 | 2024-05-14 | kONO            | L   | 0.659      | -            | -                | -                | -         |   -10.79 | avid, b0denmaster, PlesseN, robiin, twist |
|           38 |     2354 | 2024-04-30 | B8              | L   | 0.565      | -            | -                | -                | -         |    -5.39 | avid, b0denmaster, PlesseN, robiin, twist |
|           37 |     2380 | 2024-04-29 | Endpoint        | W   | 0.558      | 0.384        | 0.012 (0.003)    | 0.540 (0.116)    | 0 (0.000) |     9.50 | avid, b0denmaster, PlesseN, robiin, twist |
|           36 |     2393 | 2024-04-28 | DMS             | W   | 0.552      | 0.500        | -                | 0.462 (0.127)    | 0 (0.000) |     9.48 | avid, b0denmaster, PlesseN, robiin, twist |
|           35 |     2432 | 2024-04-26 | B8              | L   | 0.540      | -            | -                | -                | -         |    -4.66 | avid, b0denmaster, PlesseN, robiin, twist |
|           34 |     2506 | 2024-04-23 | Metizport       | L   | 0.519      | -            | -                | -                | -         |    -6.62 | avid, b0denmaster, PlesseN, robiin, twist |
|           33 |     2523 | 2024-04-22 | B8              | W   | 0.512      | 0.384        | 0.166 (0.033)    | 0.945 (0.186)    | 0 (0.000) |    11.87 | avid, b0denmaster, PlesseN, robiin, twist |
|           32 |     2546 | 2024-04-21 | Sangal          | L   | 0.504      | -            | -                | -                | -         |    -2.86 | avid, b0denmaster, PlesseN, robiin, twist |
|           31 |     2627 | 2024-04-19 | 9 Pandas        | W   | 0.491      | 0.500        | 0.082 (0.020)    | 0.715 (0.176)    | 0 (0.000) |    10.36 | avid, b0denmaster, PlesseN, robiin, twist |
|           30 |     2699 | 2024-04-17 | Nemiga          | L   | 0.479      | -            | -                | -                | -         |    -2.49 | avid, b0denmaster, PlesseN, robiin, twist |
|           29 |     2711 | 2024-04-17 | ECLOT           | L   | 0.478      | -            | -                | -                | -         |    -2.08 | avid, b0denmaster, PlesseN, robiin, twist |
|           28 |     2758 | 2024-04-15 | HAVU            | W   | 0.466      | 0.384        | -                | 0.166 (0.030)    | 0 (0.000) |     4.29 | avid, b0denmaster, PlesseN, robiin, twist |
|           27 |     2762 | 2024-04-15 | MOUZ NXT        | L   | 0.464      | -            | -                | -                | -         |    -3.84 | avid, b0denmaster, PlesseN, robiin, twist |
|           26 |     2790 | 2024-04-13 | ALTERNATE aTTaX | L   | 0.452      | -            | -                | -                | -         |    -4.98 | avid, b0denmaster, PlesseN, robiin, twist |
|           25 |     2831 | 2024-04-11 | Zero Tenacity   | W   | 0.439      | 0.384        | 0.137 (0.023)    | 1.000 (0.169)    | 0 (0.000) |    10.67 | avid, b0denmaster, PlesseN, robiin, twist |
|           24 |     2924 | 2024-04-09 | BLEED           | L   | 0.426      | -            | -                | -                | -         |    -4.34 | avid, b0denmaster, PlesseN, robiin, twist |
|           23 |     2940 | 2024-04-09 | Astralis Talent | W   | 0.424      | 0.371        | 0.007 (0.001)    | -                | 0 (0.000) |     5.25 | avid, b0denmaster, PlesseN, robiin, twist |
|           22 |     2985 | 2024-04-07 | Johnny Speeds   | L   | 0.413      | -            | -                | -                | -         |    -1.11 | avid, b0denmaster, PlesseN, robiin, twist |
|           21 |     2988 | 2024-04-07 | EYEBALLERS      | L   | 0.412      | -            | -                | -                | -         |    -5.74 | avid, b0denmaster, PlesseN, robiin, twist |
|           20 |     2997 | 2024-04-06 | Lilmix          | W   | 0.407      | -            | -                | -                | 0 (0.000) |     0.92 | avid, b0denmaster, PlesseN, robiin, twist |
|           19 |     3002 | 2024-04-06 | BetBoom         | L   | 0.406      | -            | -                | -                | -         |    -0.58 | avid, b0denmaster, PlesseN, robiin, twist |
|           18 |     3019 | 2024-04-05 | BLEED           | L   | 0.399      | -            | -                | -                | -         |    -4.23 | avid, b0denmaster, PlesseN, robiin, twist |
|           17 |     3052 | 2024-04-04 | BetBoom         | L   | 0.394      | -            | -                | -                | -         |    -0.58 | avid, b0denmaster, PlesseN, robiin, twist |
|           16 |     3062 | 2024-04-04 | Benched Heroes  | W   | 0.393      | -            | -                | -                | -         |     0.87 | avid, b0denmaster, PlesseN, robiin, twist |
|           15 |     3107 | 2024-04-03 | AMKAL           | L   | 0.385      | -            | -                | -                | -         |    -2.24 | avid, b0denmaster, PlesseN, robiin, twist |
|           14 |     3499 | 2024-03-13 | MOUZ NXT        | L   | 0.245      | -            | -                | -                | -         |    -2.16 | avid, b0denmaster, PlesseN, robiin, twist |
|           13 |     3530 | 2024-03-12 | Passion UA      | L   | 0.239      | -            | -                | -                | -         |    -1.81 | avid, b0denmaster, PlesseN, robiin, twist |
|           12 |     3570 | 2024-03-10 | EYEBALLERS      | W   | 0.226      | -            | -                | -                | -         |     3.99 | avid, b0denmaster, PlesseN, robiin, twist |
|           11 |     3580 | 2024-03-09 | BLUDS           | W   | 0.220      | -            | -                | -                | -         |     0.49 | avid, b0denmaster, PlesseN, robiin, twist |
|           10 |     3594 | 2024-03-09 | Johnny Speeds   | W   | 0.219      | 0.143        | 0.122 (0.004)    | 0.930 (0.029)    | -         |     6.35 | avid, b0denmaster, PlesseN, robiin, twist |
|            9 |     3601 | 2024-03-09 | Entropiq        | W   | 0.218      | -            | -                | -                | -         |     1.08 | avid, b0denmaster, PlesseN, robiin, twist |
|            8 |     3644 | 2024-03-07 | ex-Sprout       | W   | 0.205      | -            | -                | -                | -         |     0.83 | avid, b0denmaster, PlesseN, robiin, twist |
|            7 |     3676 | 2024-03-06 | Sashi           | L   | 0.198      | -            | -                | -                | -         |    -1.06 | avid, b0denmaster, PlesseN, robiin, twist |
|            6 |     3719 | 2024-03-05 | Viperio         | W   | 0.191      | -            | -                | -                | -         |     0.43 | avid, b0denmaster, PlesseN, robiin, twist |
|            5 |     3799 | 2024-03-01 | 9INE            | L   | 0.165      | -            | -                | -                | -         |    -4.58 | avid, b0denmaster, PlesseN, robiin, twist |
|            4 |     3826 | 2024-02-28 | Sangal          | W   | 0.152      | 0.143        | 0.219 (0.005)    | -                | -         |     4.03 | avid, b0denmaster, PlesseN, robiin, twist |
|            3 |     3881 | 2024-02-25 | ALTERNATE aTTaX | W   | 0.133      | 0.358        | 0.032 (0.002)    | 0.580 (0.028)    | -         |     2.85 | avid, b0denmaster, PlesseN, robiin, twist |
|            2 |     4052 | 2024-02-18 | Portugal        | W   | 0.085      | -            | -                | -                | -         |     0.76 | avid, b0denmaster, PlesseN, robiin, twist |
|            1 |     4280 | 2024-02-06 | 9INE            | W   | 0.005      | -            | -                | -                | -         |     0.02 | avid, b0denmaster, PlesseN, robiin, twist |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,507.81)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-16 |      0.879 | $2,000.00      | $1,758.43       |
| 2024-06-09 |      0.833 | $2,889.00      | $2,406.03       |
| 2024-05-18 |      0.687 | $500.00        | $343.36         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
