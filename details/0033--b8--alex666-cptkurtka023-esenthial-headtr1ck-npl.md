### Roster Details<br />
Team Name: B8<br />
Roster: alex666, cptkurtka023, esenthial, headtr1ck, npl<br />
Global Rank: [33](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1155.0<br />
<br />
Final Rank Value (1155.0) = Starting Rank Value (1084.5) + Head To Head Adjustments (70.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.565[<sup>1</sup>](#table2)
- Bounty Collected: 0.470[<sup>2</sup>](#table1)
- Opponent Network: 0.296[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.333<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1084.5
- 400 + ( ( 0.333 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1084.5


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
|           86 |       10 | 2024-08-05 | Permitta      | L   | 1.000      | -            | -                | -                | -         |   -23.92 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           85 |       36 | 2024-08-04 | BC.Game       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.29 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           84 |      106 | 2024-08-02 | Space         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.33 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           83 |      189 | 2024-07-31 | PERA          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.70 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           82 |      241 | 2024-07-30 | ARCRED        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.46 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           81 |      344 | 2024-07-27 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -12.84 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           80 |      392 | 2024-07-25 | SINNERS       | W   | 1.000      | 0.435        | -                | 0.790 (0.343)    | 0 (0.000) |     8.38 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           79 |      551 | 2024-07-20 | Zero Tenacity | L   | 1.000      | -            | -                | -                | -         |   -16.77 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           78 |      606 | 2024-07-19 | Rebels        | W   | 1.000      | 0.500        | -                | 0.578 (0.289)    | 0 (0.000) |     9.14 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           77 |      636 | 2024-07-18 | Aurora        | L   | 1.000      | -            | -                | -                | -         |    -5.47 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           76 |      716 | 2024-07-17 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -13.46 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           75 |      818 | 2024-07-15 | 9INE          | W   | 1.000      | 0.500        | -                | 0.523 (0.261)    | 0 (0.000) |     5.56 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           74 |     1033 | 2024-06-16 | 3DMAX         | W   | 0.861      | 0.435        | 0.510 (0.191)    | 1.000 (0.374)    | 0 (0.000) |    22.61 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           73 |     1043 | 2024-06-16 | Monte         | W   | 0.860      | 0.435        | 0.080 (0.030)    | -                | 0 (0.000) |    10.24 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           72 |     1077 | 2024-06-15 | Illuminar     | W   | 0.853      | -            | -                | -                | 0 (0.000) |     5.97 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           71 |     1157 | 2024-06-13 | MOUZ NXT      | W   | 0.839      | 0.435        | 0.139 (0.051)    | 0.962 (0.351)    | -         |    11.11 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           70 |     1177 | 2024-06-12 | BLEED         | L   | 0.834      | -            | -                | -                | -         |    -5.87 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           69 |     1274 | 2024-06-09 | AMKAL         | L   | 0.814      | -            | -                | -                | -         |   -10.66 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           68 |     1382 | 2024-06-07 | Verdant       | W   | 0.802      | -            | -                | -                | -         |     5.48 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           67 |     1383 | 2024-06-07 | PERA          | W   | 0.801      | -            | -                | -                | -         |     6.62 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           66 |     1399 | 2024-06-07 | Verdant       | L   | 0.800      | -            | -                | -                | -         |   -20.04 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           65 |     1692 | 2024-05-30 | SINNERS       | L   | 0.748      | -            | -                | -                | -         |   -14.10 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           64 |     1784 | 2024-05-26 | MOUZ NXT      | L   | 0.720      | -            | -                | -                | -         |   -14.67 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           63 |     1792 | 2024-05-25 | RUBY          | W   | 0.716      | -            | -                | -                | -         |     5.13 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           62 |     1799 | 2024-05-25 | BetBoom       | W   | 0.714      | 0.435        | 0.248 (0.077)    | -                | -         |    17.20 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           61 |     1814 | 2024-05-24 | Alliance      | W   | 0.708      | -            | -                | -                | -         |     3.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           60 |     1834 | 2024-05-23 | DMS           | W   | 0.700      | -            | -                | -                | -         |     5.03 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           59 |     1912 | 2024-05-21 | Rhyno         | W   | 0.689      | -            | -                | -                | -         |     6.18 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           58 |     1952 | 2024-05-20 | EYEBALLERS    | W   | 0.681      | -            | -                | -                | -         |     4.27 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           57 |     1979 | 2024-05-19 | Zero Tenacity | L   | 0.674      | -            | -                | -                | -         |   -12.80 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           56 |     2000 | 2024-05-18 | Sashi         | W   | 0.668      | 0.384        | 0.184 (0.047)    | 0.958 (0.246)    | -         |    12.44 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           55 |     2015 | 2024-05-18 | Rebels        | W   | 0.666      | -            | -                | -                | -         |     7.04 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           54 |     2046 | 2024-05-17 | 3DMAX         | W   | 0.660      | 0.500        | 0.510 (0.168)    | 1.000 (0.330)    | -         |    19.41 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           53 |     2073 | 2024-05-16 | DMS           | W   | 0.655      | -            | -                | -                | -         |     5.26 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           52 |     2085 | 2024-05-16 | Sampi         | W   | 0.653      | 0.384        | -                | 1.000 (0.251)    | -         |     5.54 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           51 |     2119 | 2024-05-15 | PARIVISION    | L   | 0.649      | -            | -                | -                | -         |   -11.15 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           50 |     2187 | 2024-05-14 | Verdant       | W   | 0.641      | -            | -                | -                | -         |     5.05 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           49 |     2193 | 2024-05-14 | MOUZ NXT      | W   | 0.640      | 0.384        | 0.139 (0.034)    | -                | -         |     8.71 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           48 |     2231 | 2024-05-12 | BetBoom       | W   | 0.628      | 0.435        | 0.248 (0.068)    | -                | -         |    16.57 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           47 |     2239 | 2024-05-12 | MOUZ NXT      | W   | 0.626      | 0.435        | 0.139 (0.038)    | 0.962 (0.262)    | -         |     9.36 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           46 |     2273 | 2024-05-11 | BLEED         | W   | 0.619      | -            | -                | -                | -         |     9.62 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           45 |     2309 | 2024-05-09 | KOI           | W   | 0.606      | -            | -                | -                | -         |     9.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           44 |     2366 | 2024-05-06 | Enterprise    | W   | 0.587      | -            | -                | -                | -         |     5.37 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           43 |     2402 | 2024-05-04 | GL Academy    | W   | 0.574      | -            | -                | -                | -         |     3.03 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           42 |     2451 | 2024-05-02 | Permitta      | W   | 0.559      | -            | -                | -                | -         |     6.67 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           41 |     2456 | 2024-05-01 | Nemiga        | L   | 0.555      | -            | -                | -                | -         |    -5.85 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           40 |     2460 | 2024-05-01 | V1dar         | W   | 0.554      | -            | -                | -                | -         |     0.94 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           39 |     2476 | 2024-05-01 | SINNERS       | W   | 0.553      | -            | -                | -                | -         |    10.06 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           38 |     2492 | 2024-04-30 | Alliance      | W   | 0.547      | -            | -                | -                | -         |     5.13 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           37 |     2497 | 2024-04-30 | Zero Tenacity | L   | 0.546      | -            | -                | -                | -         |    -7.86 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           36 |     2522 | 2024-04-28 | BLEED         | L   | 0.535      | -            | -                | -                | -         |    -7.80 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           35 |     2570 | 2024-04-26 | Alliance      | W   | 0.522      | -            | -                | -                | -         |     4.43 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           34 |     2642 | 2024-04-23 | BLEED         | L   | 0.501      | -            | -                | -                | -         |    -7.76 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           33 |     2656 | 2024-04-22 | Passion UA    | W   | 0.495      | 0.500        | 0.173 (0.043)    | 1.000 (0.248)    | -         |     7.77 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           32 |     2662 | 2024-04-22 | Alliance      | L   | 0.494      | -            | -                | -                | -         |   -11.50 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           31 |     2681 | 2024-04-21 | PARIVISION    | W   | 0.487      | -            | -                | -                | -         |     8.04 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           30 |     2759 | 2024-04-19 | HAVU          | W   | 0.474      | -            | -                | -                | -         |     1.93 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           29 |     2820 | 2024-04-18 | Zero Tenacity | W   | 0.466      | -            | -                | -                | -         |     7.87 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           28 |     2842 | 2024-04-17 | Zero Tenacity | L   | 0.460      | -            | -                | -                | -         |    -6.87 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           27 |     2882 | 2024-04-16 | AMKAL         | L   | 0.453      | -            | -                | -                | -         |    -5.34 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           26 |     2892 | 2024-04-15 | Sangal        | L   | 0.449      | -            | -                | -                | -         |    -5.52 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           25 |     3013 | 2024-04-10 | Nexus         | L   | 0.414      | -            | -                | -                | -         |    -9.88 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           24 |     3057 | 2024-04-09 | Rebels        | L   | 0.409      | -            | -                | -                | -         |    -7.68 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           23 |     3103 | 2024-04-08 | MOUZ NXT      | L   | 0.400      | -            | -                | -                | -         |    -6.80 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           22 |     3272 | 2024-04-02 | Metizport     | L   | 0.362      | -            | -                | -                | -         |    -8.18 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           21 |     3279 | 2024-04-02 | Apeks         | L   | 0.361      | -            | -                | -                | -         |    -8.46 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           20 |     3304 | 2024-03-31 | Apeks         | W   | 0.347      | -            | -                | -                | -         |     2.81 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           19 |     3317 | 2024-03-29 | Space         | L   | 0.335      | -            | -                | -                | -         |    -8.77 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           18 |     3364 | 2024-03-27 | Rebels        | W   | 0.322      | -            | -                | -                | -         |     3.70 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           17 |     3375 | 2024-03-27 | Sampi         | W   | 0.322      | -            | -                | -                | -         |     2.59 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           16 |     3407 | 2024-03-25 | FORZE         | W   | 0.308      | -            | -                | -                | -         |     2.71 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           15 |     3468 | 2024-03-21 | BetBoom       | L   | 0.280      | -            | -                | -                | -         |    -1.30 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           14 |     3505 | 2024-03-19 | ex-Sprout     | W   | 0.267      | -            | -                | -                | -         |     0.30 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           13 |     3572 | 2024-03-15 | 3DMAX         | L   | 0.241      | -            | -                | -                | -         |    -0.29 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           12 |     3666 | 2024-03-12 | Metizport     | L   | 0.222      | -            | -                | -                | -         |    -5.09 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           11 |     3673 | 2024-03-12 | ENCE          | W   | 0.221      | -            | -                | -                | -         |     6.25 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           10 |     3684 | 2024-03-11 | KOI           | W   | 0.216      | -            | -                | -                | -         |     3.33 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            9 |     3694 | 2024-03-11 | Virtus.pro    | L   | 0.214      | -            | -                | -                | -         |    -0.21 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            8 |     3758 | 2024-03-08 | PARIVISION    | L   | 0.195      | -            | -                | -                | -         |    -2.91 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            7 |     3845 | 2024-03-05 | Johnny Speeds | W   | 0.176      | -            | -                | -                | -         |     4.28 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            6 |     3848 | 2024-03-05 | Passion UA    | W   | 0.175      | -            | -                | -                | -         |     2.89 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            5 |     3858 | 2024-03-05 | UGANDA        | W   | 0.175      | -            | -                | -                | -         |     0.12 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            4 |     3986 | 2024-02-27 | DMS           | L   | 0.128      | -            | -                | -                | -         |    -2.97 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            3 |     4198 | 2024-02-18 | Aurora        | L   | 0.067      | -            | -                | -                | -         |    -0.07 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            2 |     4248 | 2024-02-16 | 500           | W   | 0.055      | -            | -                | -                | -         |     0.18 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            1 |     4254 | 2024-02-16 | PERA          | W   | 0.054      | -            | -                | -                | -         |     0.04 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($54,631.84)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.861 | $22,000.00     | $18,950.56      |
| 2024-06-09 |      0.815 | $1,500.00      | $1,221.98       |
| 2024-05-26 |      0.721 | $5,000.00      | $3,606.94       |
| 2024-05-18 |      0.668 | $10,000.00     | $6,683.33       |
| 2024-05-12 |      0.628 | $22,000.00     | $13,821.81      |
| 2024-04-24 |      0.508 | $12,500.00     | $6,347.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
