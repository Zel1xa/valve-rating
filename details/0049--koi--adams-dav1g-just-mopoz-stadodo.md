### Roster Details<br />
Team Name: KOI<br />
Roster: adamS, dav1g, JUST, mopoz, stadodo<br />
Global Rank: [49](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [36]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1085.0<br />
<br />
Final Rank Value (1085.0) = Starting Rank Value (1082.7) + Head To Head Adjustments (2.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.447[<sup>1</sup>](#table2)
- Bounty Collected: 0.439[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
- LAN Wins: 0.214[<sup>2</sup>](#table1)

The average of these factors is 0.333<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1082.7
- 400 + ( ( 0.333 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1082.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           45 |      189 | 2024-07-31 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -12.67 | adamS, dav1g, JUST, mopoz, stadodo |
|           44 |      351 | 2024-07-26 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.500 (0.250)    | 0 (0.000) |     5.74 | adamS, dav1g, JUST, mopoz, stadodo |
|           43 |      626 | 2024-07-18 | Monte           | L   | 1.000      | -            | -                | -                | -         |   -18.05 | adamS, dav1g, JUST, mopoz, stadodo |
|           42 |      760 | 2024-07-16 | Insilio         | W   | 1.000      | 0.500        | 0.023 (0.011)    | 0.552 (0.276)    | 0 (0.000) |    10.09 | adamS, dav1g, JUST, mopoz, stadodo |
|           41 |     1026 | 2024-06-16 | 9z              | L   | 0.864      | -            | -                | -                | -         |    -3.23 | adamS, dav1g, JUST, mopoz, stadodo |
|           40 |     1076 | 2024-06-14 | RED Canids      | W   | 0.854      | 0.548        | 0.077 (0.036)    | 0.748 (0.350)    | 1 (0.854) |    16.21 | adamS, dav1g, JUST, mopoz, stadodo |
|           39 |     1081 | 2024-06-14 | Imperial        | W   | 0.853      | 0.548        | 0.234 (0.109)    | 0.674 (0.315)    | 1 (0.853) |    20.46 | adamS, dav1g, JUST, mopoz, stadodo |
|           38 |     1247 | 2024-06-09 | Sangal          | L   | 0.817      | -            | -                | -                | -         |    -8.36 | adamS, dav1g, JUST, mopoz, stadodo |
|           37 |     1435 | 2024-06-06 | SINNERS         | W   | 0.798      | 0.500        | 0.037 (0.015)    | 0.808 (0.322)    | 0 (0.000) |    11.06 | adamS, dav1g, JUST, mopoz, stadodo |
|           36 |     1496 | 2024-06-05 | 3DMAX           | W   | 0.791      | 0.500        | 0.509 (0.201)    | 1.000 (0.396)    | 0 (0.000) |    23.38 | adamS, dav1g, JUST, mopoz, stadodo |
|           35 |     1625 | 2024-06-01 | ENCE            | L   | 0.764      | -            | -                | -                | -         |    -3.27 | adamS, dav1g, JUST, mopoz, stadodo |
|           34 |     1631 | 2024-06-01 | Zero Tenacity   | L   | 0.763      | -            | -                | -                | -         |    -9.84 | adamS, dav1g, JUST, mopoz, stadodo |
|           33 |     2301 | 2024-05-09 | B8              | L   | 0.609      | -            | -                | -                | -         |    -9.74 | adamS, dav1g, JUST, mopoz, stadodo |
|           32 |     2464 | 2024-05-01 | Zero Tenacity   | L   | 0.556      | -            | -                | -                | -         |    -8.84 | adamS, dav1g, JUST, mopoz, stadodo |
|           31 |     2780 | 2024-04-18 | ex-Guild Eagles | L   | 0.471      | -            | -                | -                | -         |   -11.94 | adamS, dav1g, JUST, mopoz, stadodo |
|           30 |     2791 | 2024-04-18 | fnatic          | W   | 0.471      | 0.143        | 0.371 (0.025)    | -                | 0 (0.000) |    13.77 | adamS, dav1g, JUST, mopoz, stadodo |
|           29 |     2865 | 2024-04-16 | BLEED           | L   | 0.458      | -            | -                | -                | -         |    -8.77 | adamS, dav1g, JUST, mopoz, stadodo |
|           28 |     2996 | 2024-04-10 | RUSH B          | W   | 0.418      | 0.500        | -                | 0.380 (0.079)    | -         |     3.21 | adamS, dav1g, JUST, mopoz, stadodo |
|           27 |     3051 | 2024-04-09 | Aurora          | W   | 0.411      | 0.500        | 0.421 (0.087)    | 0.777 (0.160)    | -         |    12.50 | adamS, dav1g, JUST, mopoz, stadodo |
|           26 |     3057 | 2024-04-09 | Apeks           | L   | 0.411      | -            | -                | -                | -         |    -9.28 | adamS, dav1g, JUST, mopoz, stadodo |
|           25 |     3084 | 2024-04-08 | GUN5            | W   | 0.404      | -            | -                | -                | -         |     0.29 | adamS, dav1g, JUST, mopoz, stadodo |
|           24 |     3085 | 2024-04-08 | fnatic          | L   | 0.404      | -            | -                | -                | -         |    -0.84 | adamS, dav1g, JUST, mopoz, stadodo |
|           23 |     3188 | 2024-04-04 | NOM             | W   | 0.377      | -            | -                | -                | -         |     0.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           22 |     3222 | 2024-04-03 | 9INE            | W   | 0.371      | -            | -                | -                | -         |     0.51 | adamS, dav1g, JUST, mopoz, stadodo |
|           21 |     3260 | 2024-04-02 | TSM             | W   | 0.365      | -            | -                | -                | -         |     1.14 | adamS, dav1g, JUST, mopoz, stadodo |
|           20 |     3327 | 2024-03-28 | EYEBALLERS      | L   | 0.331      | -            | -                | -                | -         |    -7.63 | adamS, dav1g, JUST, mopoz, stadodo |
|           19 |     3499 | 2024-03-18 | FURIA           | L   | 0.264      | -            | -                | -                | -         |    -0.24 | adamS, dav1g, JUST, mopoz, stadodo |
|           18 |     3514 | 2024-03-17 | ENCE            | L   | 0.259      | -            | -                | -                | -         |    -0.85 | adamS, dav1g, JUST, mopoz, stadodo |
|           17 |     3530 | 2024-03-17 | SAW             | L   | 0.257      | -            | -                | -                | -         |    -3.02 | adamS, dav1g, JUST, mopoz, stadodo |
|           16 |     3622 | 2024-03-13 | Sangal          | W   | 0.232      | 0.500        | 0.219 (0.025)    | 0.866 (0.100)    | -         |     4.31 | adamS, dav1g, JUST, mopoz, stadodo |
|           15 |     3676 | 2024-03-11 | B8              | L   | 0.218      | -            | -                | -                | -         |    -3.41 | adamS, dav1g, JUST, mopoz, stadodo |
|           14 |     3685 | 2024-03-11 | Apeks           | L   | 0.217      | -            | -                | -                | -         |    -5.03 | adamS, dav1g, JUST, mopoz, stadodo |
|           13 |     3797 | 2024-03-06 | 9 Pandas        | W   | 0.185      | 0.500        | 0.081 (0.008)    | 0.717 (0.066)    | -         |     2.22 | adamS, dav1g, JUST, mopoz, stadodo |
|           12 |     3833 | 2024-03-05 | FORZE           | W   | 0.179      | -            | -                | -                | -         |     1.53 | adamS, dav1g, JUST, mopoz, stadodo |
|           11 |     3839 | 2024-03-05 | Nemiga          | W   | 0.178      | 0.143        | 0.315 (0.008)    | -                | -         |     3.50 | adamS, dav1g, JUST, mopoz, stadodo |
|           10 |     3847 | 2024-03-05 | ex-Sprout       | W   | 0.178      | -            | -                | -                | -         |     0.22 | adamS, dav1g, JUST, mopoz, stadodo |
|            9 |     3887 | 2024-03-03 | The Chosen Few  | L   | 0.164      | -            | -                | -                | -         |    -4.72 | adamS, dav1g, JUST, mopoz, stadodo |
|            8 |     3942 | 2024-02-29 | Aurora          | L   | 0.145      | -            | -                | -                | -         |    -0.16 | adamS, dav1g, JUST, mopoz, stadodo |
|            7 |     3946 | 2024-02-29 | HAVU            | W   | 0.144      | -            | -                | -                | -         |     0.48 | adamS, dav1g, JUST, mopoz, stadodo |
|            6 |     3955 | 2024-02-28 | FORZE           | L   | 0.138      | -            | -                | -                | -         |    -3.26 | adamS, dav1g, JUST, mopoz, stadodo |
|            5 |     3959 | 2024-02-28 | kONO            | W   | 0.137      | -            | -                | -                | -         |     0.76 | adamS, dav1g, JUST, mopoz, stadodo |
|            4 |     4250 | 2024-02-16 | fnatic          | W   | 0.056      | -            | -                | -                | 1 (0.056) |     1.65 | adamS, dav1g, JUST, mopoz, stadodo |
|            3 |     4274 | 2024-02-15 | 9 Pandas        | W   | 0.049      | -            | -                | -                | 1 (0.049) |     0.59 | adamS, dav1g, JUST, mopoz, stadodo |
|            2 |     4303 | 2024-02-14 | 3DMAX           | W   | 0.045      | -            | -                | -                | 1 (0.045) |     1.36 | adamS, dav1g, JUST, mopoz, stadodo |
|            1 |     4317 | 2024-02-14 | Natus Vincere   | L   | 0.043      | -            | -                | -                | -         |    -0.01 | adamS, dav1g, JUST, mopoz, stadodo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,652.41)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.866 | $7,000.00      | $6,064.07       |
| 2024-06-09 |      0.817 | $12,000.00     | $9,809.17       |
| 2024-03-20 |      0.278 | $10,000.00     | $2,779.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
