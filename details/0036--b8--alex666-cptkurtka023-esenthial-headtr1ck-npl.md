### Roster Details<br />
Team Name: B8<br />
Roster: alex666, cptkurtka023, esenthial, headtr1ck, npl<br />
Global Rank: [36](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [27]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1155.5<br />
<br />
Final Rank Value (1155.5) = Starting Rank Value (1093.4) + Head To Head Adjustments (62.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.563[<sup>1</sup>](#table2)
- Bounty Collected: 0.475[<sup>2</sup>](#table1)
- Opponent Network: 0.310[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.337<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1093.4
- 400 + ( ( 0.337 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1093.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           85 |       39 | 2024-07-31 | PERA          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.11 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           84 |       91 | 2024-07-30 | ARCRED        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.86 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           83 |      194 | 2024-07-27 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -13.39 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           82 |      242 | 2024-07-25 | SINNERS       | W   | 1.000      | 0.435        | -                | 0.768 (0.334)    | 0 (0.000) |     7.92 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           81 |      404 | 2024-07-20 | Zero Tenacity | L   | 1.000      | -            | -                | -                | -         |   -18.54 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           80 |      461 | 2024-07-19 | Rebels        | W   | 1.000      | 0.500        | -                | 0.635 (0.318)    | 0 (0.000) |     8.93 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           79 |      495 | 2024-07-18 | Aurora        | L   | 1.000      | -            | -                | -                | -         |    -5.49 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           78 |      575 | 2024-07-17 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -14.16 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           77 |      683 | 2024-07-15 | 9INE          | W   | 1.000      | 0.500        | -                | 0.522 (0.261)    | 0 (0.000) |     6.76 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           76 |      899 | 2024-06-16 | 3DMAX         | W   | 0.893      | 0.435        | 0.505 (0.196)    | 1.000 (0.388)    | 0 (0.000) |    23.32 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           75 |      908 | 2024-06-16 | Monte         | W   | 0.891      | 0.435        | 0.081 (0.031)    | -                | 0 (0.000) |    10.75 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           74 |      939 | 2024-06-15 | Illuminar     | W   | 0.885      | -            | -                | -                | 0 (0.000) |     6.91 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           73 |     1013 | 2024-06-13 | MOUZ NXT      | W   | 0.871      | 0.435        | 0.141 (0.053)    | 1.000 (0.378)    | 0 (0.000) |    12.06 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           72 |     1033 | 2024-06-12 | BLEED         | L   | 0.865      | -            | -                | -                | -         |    -5.71 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           71 |     1132 | 2024-06-09 | AMKAL         | L   | 0.845      | -            | -                | -                | -         |   -10.59 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           70 |     1249 | 2024-06-07 | Verdant       | W   | 0.833      | -            | -                | -                | 0 (0.000) |     6.08 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           69 |     1250 | 2024-06-07 | PERA          | W   | 0.833      | -            | -                | -                | -         |     7.25 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           68 |     1266 | 2024-06-07 | Verdant       | L   | 0.832      | -            | -                | -                | -         |   -20.42 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           67 |     1565 | 2024-05-30 | SINNERS       | L   | 0.779      | -            | -                | -                | -         |   -15.30 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           66 |     1659 | 2024-05-26 | MOUZ NXT      | L   | 0.751      | -            | -                | -                | -         |   -15.13 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           65 |     1667 | 2024-05-25 | RUBY          | W   | 0.747      | -            | -                | -                | -         |     5.87 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           64 |     1674 | 2024-05-25 | BetBoom       | W   | 0.746      | 0.435        | 0.257 (0.083)    | -                | -         |    18.45 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           63 |     1689 | 2024-05-24 | Alliance      | W   | 0.740      | -            | -                | -                | -         |     4.08 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           62 |     1709 | 2024-05-23 | DMS           | W   | 0.732      | -            | -                | -                | -         |     5.59 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           61 |     1801 | 2024-05-21 | Rhyno         | W   | 0.720      | -            | -                | -                | -         |     7.25 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           60 |     1847 | 2024-05-20 | EYEBALLERS    | W   | 0.712      | -            | -                | -                | -         |     4.82 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           59 |     1879 | 2024-05-19 | Zero Tenacity | L   | 0.705      | -            | -                | -                | -         |   -13.04 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           58 |     1900 | 2024-05-18 | Sashi         | W   | 0.700      | 0.384        | 0.186 (0.050)    | 0.970 (0.261)    | -         |    13.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           57 |     1911 | 2024-05-18 | MOUZ NXT      | L   | 0.698      | -            | -                | -                | -         |   -13.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           56 |     1916 | 2024-05-18 | Rebels        | W   | 0.698      | -            | -                | -                | -         |     7.70 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           55 |     1947 | 2024-05-17 | 3DMAX         | W   | 0.692      | 0.500        | 0.505 (0.175)    | 1.000 (0.346)    | -         |    20.27 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           54 |     1974 | 2024-05-16 | DMS           | W   | 0.686      | -            | -                | -                | -         |     5.63 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           53 |     1986 | 2024-05-16 | Sampi         | W   | 0.684      | 0.384        | -                | 1.000 (0.263)    | -         |     5.81 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           52 |     2020 | 2024-05-15 | PARIVISION    | L   | 0.680      | -            | -                | -                | -         |   -11.54 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           51 |     2094 | 2024-05-14 | Verdant       | W   | 0.672      | -            | -                | -                | -         |     5.57 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           50 |     2101 | 2024-05-14 | MOUZ NXT      | W   | 0.671      | 0.384        | 0.141 (0.036)    | -                | -         |     8.72 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           49 |     2141 | 2024-05-12 | BetBoom       | W   | 0.660      | 0.435        | 0.257 (0.074)    | -                | -         |    17.65 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           48 |     2149 | 2024-05-12 | MOUZ NXT      | W   | 0.658      | 0.435        | 0.141 (0.040)    | 1.000 (0.286)    | -         |     9.43 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           47 |     2183 | 2024-05-11 | BLEED         | W   | 0.651      | -            | -                | -                | -         |    10.30 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           46 |     2219 | 2024-05-09 | KOI           | W   | 0.637      | -            | -                | -                | -         |     7.08 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           45 |     2278 | 2024-05-06 | Enterprise    | W   | 0.619      | -            | -                | -                | -         |     5.63 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           44 |     2314 | 2024-05-04 | GL Academy    | W   | 0.605      | -            | -                | -                | -         |     3.38 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           43 |     2364 | 2024-05-02 | Permitta      | W   | 0.591      | -            | -                | -                | -         |     6.82 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           42 |     2370 | 2024-05-01 | Nemiga        | L   | 0.587      | -            | -                | -                | -         |    -6.39 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           41 |     2374 | 2024-05-01 | V1dar         | W   | 0.586      | -            | -                | -                | -         |     1.05 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           40 |     2390 | 2024-05-01 | SINNERS       | W   | 0.584      | -            | -                | -                | -         |     9.17 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           39 |     2407 | 2024-04-30 | Alliance      | W   | 0.578      | -            | -                | -                | -         |     5.61 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           38 |     2412 | 2024-04-30 | Zero Tenacity | L   | 0.578      | -            | -                | -                | -         |    -8.37 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           37 |     2437 | 2024-04-28 | BLEED         | L   | 0.567      | -            | -                | -                | -         |    -8.12 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           36 |     2486 | 2024-04-26 | Alliance      | W   | 0.553      | -            | -                | -                | -         |     4.84 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           35 |     2559 | 2024-04-23 | BLEED         | L   | 0.532      | -            | -                | -                | -         |    -7.93 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           34 |     2572 | 2024-04-23 | PARIVISION    | L   | 0.531      | -            | -                | -                | -         |    -8.18 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           33 |     2574 | 2024-04-22 | Passion UA    | W   | 0.527      | 0.500        | 0.173 (0.045)    | 1.000 (0.263)    | -         |     8.07 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           32 |     2580 | 2024-04-22 | Alliance      | L   | 0.525      | -            | -                | -                | -         |   -12.25 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           31 |     2600 | 2024-04-21 | PARIVISION    | W   | 0.518      | -            | -                | -                | -         |     8.33 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           30 |     2681 | 2024-04-19 | HAVU          | W   | 0.505      | -            | -                | -                | -         |     2.10 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           29 |     2743 | 2024-04-18 | Zero Tenacity | W   | 0.497      | -            | -                | -                | -         |     8.16 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           28 |     2766 | 2024-04-17 | Zero Tenacity | L   | 0.492      | -            | -                | -                | -         |    -7.58 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           27 |     2807 | 2024-04-16 | AMKAL         | L   | 0.484      | -            | -                | -                | -         |    -5.71 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           26 |     2817 | 2024-04-15 | Sangal        | L   | 0.480      | -            | -                | -                | -         |    -6.30 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           25 |     2939 | 2024-04-10 | Nexus         | L   | 0.445      | -            | -                | -                | -         |   -10.66 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           24 |     2983 | 2024-04-09 | Rebels        | L   | 0.440      | -            | -                | -                | -         |    -8.26 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           23 |     3029 | 2024-04-08 | MOUZ NXT      | L   | 0.432      | -            | -                | -                | -         |    -7.22 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           22 |     3206 | 2024-04-02 | Metizport     | L   | 0.393      | -            | -                | -                | -         |    -8.95 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           21 |     3213 | 2024-04-02 | Apeks         | L   | 0.392      | -            | -                | -                | -         |    -9.06 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           20 |     3238 | 2024-03-31 | Apeks         | W   | 0.379      | -            | -                | -                | -         |     3.20 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           19 |     3251 | 2024-03-29 | Space         | L   | 0.366      | -            | -                | -                | -         |    -9.63 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           18 |     3299 | 2024-03-27 | Rebels        | W   | 0.354      | -            | -                | -                | -         |     4.06 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           17 |     3310 | 2024-03-27 | Sampi         | W   | 0.353      | -            | -                | -                | -         |     2.82 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           16 |     3346 | 2024-03-25 | FORZE         | W   | 0.339      | -            | -                | -                | -         |     3.07 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           15 |     3407 | 2024-03-21 | BetBoom       | L   | 0.311      | -            | -                | -                | -         |    -1.36 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           14 |     3444 | 2024-03-19 | ex-Sprout     | W   | 0.298      | -            | -                | -                | -         |     0.37 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           13 |     3511 | 2024-03-15 | 3DMAX         | L   | 0.273      | -            | -                | -                | -         |    -0.35 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           12 |     3610 | 2024-03-12 | Metizport     | L   | 0.254      | -            | -                | -                | -         |    -5.86 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           11 |     3617 | 2024-03-12 | ENCE          | W   | 0.252      | -            | -                | -                | -         |     7.11 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           10 |     3628 | 2024-03-11 | KOI           | W   | 0.247      | -            | -                | -                | -         |     2.33 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            9 |     3638 | 2024-03-11 | Virtus.pro    | L   | 0.246      | -            | -                | -                | -         |    -0.23 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            8 |     3703 | 2024-03-08 | PARIVISION    | L   | 0.226      | -            | -                | -                | -         |    -3.51 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            7 |     3790 | 2024-03-05 | Johnny Speeds | W   | 0.207      | -            | -                | -                | -         |     5.00 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            6 |     3797 | 2024-03-05 | Passion UA    | W   | 0.207      | -            | -                | -                | -         |     3.35 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            5 |     3808 | 2024-03-05 | UGANDA        | W   | 0.206      | -            | -                | -                | -         |     0.13 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            4 |     3938 | 2024-02-27 | DMS           | L   | 0.160      | -            | -                | -                | -         |    -3.72 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            3 |     4158 | 2024-02-18 | Aurora        | L   | 0.099      | -            | -                | -                | -         |    -0.10 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            2 |     4208 | 2024-02-16 | 500           | W   | 0.086      | -            | -                | -                | -         |     0.31 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            1 |     4214 | 2024-02-16 | PERA          | W   | 0.085      | -            | -                | -                | -         |     0.05 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($54,923.23)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.893 | $22,000.00     | $19,641.11      |
| 2024-06-09 |      0.846 | $1,500.00      | $1,269.06       |
| 2024-05-26 |      0.753 | $5,000.00      | $3,763.89       |
| 2024-05-18 |      0.700 | $10,000.00     | $6,997.22       |
| 2024-05-12 |      0.660 | $22,000.00     | $14,512.36      |
| 2024-04-24 |      0.539 | $12,500.00     | $6,739.58       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
