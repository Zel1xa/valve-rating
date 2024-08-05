### Roster Details<br />
Team Name: B8<br />
Roster: alex666, cptkurtka023, esenthial, headtr1ck, npl<br />
Global Rank: [36](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [27]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1169.6<br />
<br />
Final Rank Value (1169.6) = Starting Rank Value (1093.4) + Head To Head Adjustments (76.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.563[<sup>1</sup>](#table2)
- Bounty Collected: 0.475[<sup>2</sup>](#table1)
- Opponent Network: 0.308[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.336<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1093.4
- 400 + ( ( 0.336 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1093.4


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
|           83 |        4 | 2024-07-31 | PERA          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.69 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           82 |       56 | 2024-07-30 | ARCRED        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.42 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           81 |      159 | 2024-07-27 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -13.12 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           80 |      207 | 2024-07-25 | SINNERS       | W   | 1.000      | 0.435        | -                | 0.721 (0.313)    | 0 (0.000) |     7.21 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           79 |      366 | 2024-07-20 | Zero Tenacity | L   | 1.000      | -            | -                | -                | -         |   -16.96 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           78 |      421 | 2024-07-19 | Rebels        | W   | 1.000      | 0.500        | -                | 0.596 (0.298)    | 0 (0.000) |     9.13 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           77 |      451 | 2024-07-18 | Aurora        | L   | 1.000      | -            | -                | -                | -         |    -5.70 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           76 |      531 | 2024-07-17 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -13.91 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           75 |      633 | 2024-07-15 | 9INE          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.49 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           74 |      848 | 2024-06-16 | 3DMAX         | W   | 0.899      | 0.435        | 0.499 (0.195)    | 1.000 (0.391)    | 0 (0.000) |    23.28 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           73 |      858 | 2024-06-16 | Monte         | W   | 0.897      | 0.435        | 0.080 (0.031)    | -                | 0 (0.000) |    10.68 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           72 |      892 | 2024-06-15 | Illuminar     | W   | 0.891      | -            | -                | -                | 0 (0.000) |     6.14 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           71 |      972 | 2024-06-13 | MOUZ NXT      | W   | 0.877      | 0.435        | 0.140 (0.053)    | 1.000 (0.381)    | 0 (0.000) |    11.29 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           70 |      992 | 2024-06-12 | BLEED         | L   | 0.871      | -            | -                | -                | -         |    -6.15 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           69 |     1089 | 2024-06-09 | AMKAL         | L   | 0.851      | -            | -                | -                | -         |   -10.91 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           68 |     1197 | 2024-06-07 | Verdant       | W   | 0.839      | -            | -                | -                | 0 (0.000) |     5.62 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           67 |     1198 | 2024-06-07 | PERA          | W   | 0.839      | -            | -                | -                | -         |     6.93 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           66 |     1214 | 2024-06-07 | Verdant       | L   | 0.838      | -            | -                | -                | -         |   -21.08 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           65 |     1507 | 2024-05-30 | SINNERS       | L   | 0.785      | -            | -                | -                | -         |   -16.71 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           64 |     1599 | 2024-05-26 | MOUZ NXT      | L   | 0.757      | -            | -                | -                | -         |   -15.76 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           63 |     1607 | 2024-05-25 | RUBY          | W   | 0.753      | -            | -                | -                | -         |     5.33 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           62 |     1614 | 2024-05-25 | BetBoom       | W   | 0.752      | 0.435        | 0.256 (0.084)    | -                | -         |    18.34 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           61 |     1629 | 2024-05-24 | Alliance      | W   | 0.746      | -            | -                | -                | -         |     3.69 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           60 |     1649 | 2024-05-23 | DMS           | W   | 0.738      | -            | -                | -                | -         |     5.21 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           59 |     1727 | 2024-05-21 | Rhyno         | W   | 0.726      | -            | -                | -                | -         |     6.69 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           58 |     1767 | 2024-05-20 | EYEBALLERS    | W   | 0.718      | -            | -                | -                | -         |     4.43 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           57 |     1794 | 2024-05-19 | Zero Tenacity | L   | 0.711      | -            | -                | -                | -         |   -13.76 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           56 |     1815 | 2024-05-18 | Sashi         | W   | 0.706      | 0.384        | 0.185 (0.050)    | 0.973 (0.264)    | -         |    13.18 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           55 |     1830 | 2024-05-18 | Rebels        | W   | 0.704      | -            | -                | -                | -         |     7.49 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           54 |     1861 | 2024-05-17 | 3DMAX         | W   | 0.698      | 0.500        | 0.499 (0.174)    | 1.000 (0.349)    | -         |    20.43 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           53 |     1888 | 2024-05-16 | DMS           | W   | 0.692      | -            | -                | -                | -         |     5.51 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           52 |     1900 | 2024-05-16 | Sampi         | W   | 0.690      | 0.384        | -                | 1.000 (0.265)    | -         |     5.82 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           51 |     1934 | 2024-05-15 | PARIVISION    | L   | 0.686      | -            | -                | -                | -         |   -12.39 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           50 |     2002 | 2024-05-14 | Verdant       | W   | 0.678      | -            | -                | -                | -         |     5.25 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           49 |     2008 | 2024-05-14 | MOUZ NXT      | W   | 0.677      | 0.384        | 0.140 (0.036)    | 1.000 (0.260)    | -         |     9.01 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           48 |     2046 | 2024-05-12 | BetBoom       | W   | 0.666      | 0.435        | 0.256 (0.074)    | -                | -         |    17.78 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           47 |     2054 | 2024-05-12 | MOUZ NXT      | W   | 0.664      | 0.435        | 0.140 (0.040)    | 1.000 (0.288)    | -         |     9.76 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           46 |     2088 | 2024-05-11 | BLEED         | W   | 0.657      | -            | -                | -                | -         |    10.45 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           45 |     2124 | 2024-05-09 | KOI           | W   | 0.644      | -            | -                | -                | -         |    10.63 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           44 |     2181 | 2024-05-06 | Enterprise    | W   | 0.625      | -            | -                | -                | -         |     5.69 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           43 |     2217 | 2024-05-04 | GL Academy    | W   | 0.611      | -            | -                | -                | -         |     3.32 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           42 |     2266 | 2024-05-02 | Permitta      | W   | 0.597      | -            | -                | -                | -         |     6.63 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           41 |     2271 | 2024-05-01 | Nemiga        | L   | 0.593      | -            | -                | -                | -         |    -6.33 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           40 |     2275 | 2024-05-01 | V1dar         | W   | 0.592      | -            | -                | -                | -         |     1.02 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           39 |     2291 | 2024-05-01 | SINNERS       | W   | 0.590      | -            | -                | -                | -         |     8.61 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           38 |     2307 | 2024-04-30 | Alliance      | W   | 0.584      | -            | -                | -                | -         |     5.46 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           37 |     2312 | 2024-04-30 | Zero Tenacity | L   | 0.584      | -            | -                | -                | -         |    -8.64 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           36 |     2337 | 2024-04-28 | BLEED         | L   | 0.573      | -            | -                | -                | -         |    -8.04 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           35 |     2385 | 2024-04-26 | Alliance      | W   | 0.559      | -            | -                | -                | -         |     4.69 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           34 |     2457 | 2024-04-23 | BLEED         | L   | 0.539      | -            | -                | -                | -         |    -8.05 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           33 |     2471 | 2024-04-22 | Passion UA    | W   | 0.533      | 0.500        | 0.171 (0.045)    | 1.000 (0.266)    | -         |     7.97 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           32 |     2477 | 2024-04-22 | Alliance      | L   | 0.531      | -            | -                | -                | -         |   -12.44 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           31 |     2496 | 2024-04-21 | PARIVISION    | W   | 0.524      | -            | -                | -                | -         |     8.15 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           30 |     2574 | 2024-04-19 | HAVU          | W   | 0.511      | -            | -                | -                | -         |     2.11 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           29 |     2635 | 2024-04-18 | Zero Tenacity | W   | 0.504      | -            | -                | -                | -         |     8.33 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           28 |     2657 | 2024-04-17 | Zero Tenacity | L   | 0.498      | -            | -                | -                | -         |    -7.61 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           27 |     2697 | 2024-04-16 | AMKAL         | L   | 0.490      | -            | -                | -                | -         |    -5.70 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           26 |     2707 | 2024-04-15 | Sangal        | L   | 0.486      | -            | -                | -                | -         |    -6.38 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           25 |     2828 | 2024-04-10 | Nexus         | L   | 0.451      | -            | -                | -                | -         |   -10.82 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           24 |     2872 | 2024-04-09 | Rebels        | L   | 0.446      | -            | -                | -                | -         |    -8.39 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           23 |     2918 | 2024-04-08 | MOUZ NXT      | L   | 0.438      | -            | -                | -                | -         |    -7.54 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           22 |     3087 | 2024-04-02 | Metizport     | L   | 0.399      | -            | -                | -                | -         |    -9.02 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           21 |     3094 | 2024-04-02 | Apeks         | L   | 0.398      | -            | -                | -                | -         |    -9.12 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           20 |     3119 | 2024-03-31 | Apeks         | W   | 0.385      | -            | -                | -                | -         |     3.33 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           19 |     3132 | 2024-03-29 | Space         | L   | 0.372      | -            | -                | -                | -         |    -9.80 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           18 |     3179 | 2024-03-27 | Rebels        | W   | 0.360      | -            | -                | -                | -         |     4.11 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           17 |     3190 | 2024-03-27 | Sampi         | W   | 0.359      | -            | -                | -                | -         |     2.85 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           16 |     3222 | 2024-03-25 | FORZE         | W   | 0.345      | -            | -                | -                | -         |     3.16 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           15 |     3283 | 2024-03-21 | BetBoom       | L   | 0.317      | -            | -                | -                | -         |    -1.35 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           14 |     3320 | 2024-03-19 | ex-Sprout     | W   | 0.304      | -            | -                | -                | -         |     0.36 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           13 |     3387 | 2024-03-15 | 3DMAX         | L   | 0.279      | -            | -                | -                | -         |    -0.35 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           12 |     3481 | 2024-03-12 | Metizport     | L   | 0.260      | -            | -                | -                | -         |    -5.95 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           11 |     3488 | 2024-03-12 | ENCE          | W   | 0.258      | -            | -                | -                | -         |     7.31 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           10 |     3499 | 2024-03-11 | KOI           | W   | 0.253      | -            | -                | -                | -         |     4.06 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            9 |     3509 | 2024-03-11 | Virtus.pro    | L   | 0.252      | -            | -                | -                | -         |    -0.21 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            8 |     3573 | 2024-03-08 | PARIVISION    | L   | 0.232      | -            | -                | -                | -         |    -3.73 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            7 |     3660 | 2024-03-05 | Johnny Speeds | W   | 0.213      | -            | -                | -                | -         |     5.15 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            6 |     3663 | 2024-03-05 | Passion UA    | W   | 0.213      | -            | -                | -                | -         |     3.38 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            5 |     3673 | 2024-03-05 | UGANDA        | W   | 0.212      | -            | -                | -                | -         |     0.14 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            4 |     3801 | 2024-02-27 | DMS           | L   | 0.166      | -            | -                | -                | -         |    -3.84 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            3 |     4013 | 2024-02-18 | Aurora        | L   | 0.105      | -            | -                | -                | -         |    -0.11 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            2 |     4063 | 2024-02-16 | 500           | W   | 0.092      | -            | -                | -                | -         |     0.30 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            1 |     4069 | 2024-02-16 | PERA          | W   | 0.091      | -            | -                | -                | -         |     0.06 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,361.57)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.899 | $22,000.00     | $19,773.21      |
| 2024-06-09 |      0.852 | $1,500.00      | $1,278.07       |
| 2024-05-26 |      0.759 | $5,000.00      | $3,793.91       |
| 2024-05-18 |      0.706 | $10,000.00     | $7,057.27       |
| 2024-05-12 |      0.666 | $22,000.00     | $14,644.46      |
| 2024-04-24 |      0.545 | $12,500.00     | $6,814.64       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
