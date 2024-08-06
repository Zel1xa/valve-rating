### Roster Details<br />
Team Name: B8<br />
Roster: alex666, cptkurtka023, esenthial, headtr1ck, npl<br />
Global Rank: [33](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1156.2<br />
<br />
Final Rank Value (1156.2) = Starting Rank Value (1084.5) + Head To Head Adjustments (71.7)<br />

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
|           86 |       23 | 2024-08-05 | Permitta      | L   | 1.000      | -            | -                | -                | -         |   -23.79 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           85 |       49 | 2024-08-04 | BC.Game       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.34 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           84 |      119 | 2024-08-02 | Space         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.36 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           83 |      202 | 2024-07-31 | PERA          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.68 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           82 |      254 | 2024-07-30 | ARCRED        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.47 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           81 |      357 | 2024-07-27 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -12.75 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           80 |      405 | 2024-07-25 | SINNERS       | W   | 1.000      | 0.435        | -                | 0.800 (0.348)    | 0 (0.000) |     8.39 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           79 |      564 | 2024-07-20 | Zero Tenacity | L   | 1.000      | -            | -                | -                | -         |   -16.74 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           78 |      619 | 2024-07-19 | Rebels        | W   | 1.000      | 0.500        | -                | 0.578 (0.289)    | 0 (0.000) |     9.14 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           77 |      649 | 2024-07-18 | Aurora        | L   | 1.000      | -            | -                | -                | -         |    -5.46 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           76 |      729 | 2024-07-17 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -13.36 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           75 |      831 | 2024-07-15 | 9INE          | W   | 1.000      | 0.500        | -                | 0.523 (0.262)    | 0 (0.000) |     5.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           74 |     1046 | 2024-06-16 | 3DMAX         | W   | 0.860      | 0.435        | 0.510 (0.191)    | 1.000 (0.374)    | 0 (0.000) |    22.58 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           73 |     1056 | 2024-06-16 | Monte         | W   | 0.858      | 0.435        | 0.080 (0.030)    | -                | 0 (0.000) |    10.23 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           72 |     1090 | 2024-06-15 | Illuminar     | W   | 0.852      | -            | -                | -                | 0 (0.000) |     6.04 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           71 |     1170 | 2024-06-13 | MOUZ NXT      | W   | 0.838      | 0.435        | 0.139 (0.050)    | 0.961 (0.350)    | -         |    11.18 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           70 |     1190 | 2024-06-12 | BLEED         | L   | 0.832      | -            | -                | -                | -         |    -5.84 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           69 |     1287 | 2024-06-09 | AMKAL         | L   | 0.812      | -            | -                | -                | -         |   -10.63 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           68 |     1395 | 2024-06-07 | Verdant       | W   | 0.800      | -            | -                | -                | -         |     5.49 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           67 |     1396 | 2024-06-07 | PERA          | W   | 0.800      | -            | -                | -                | -         |     6.59 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           66 |     1412 | 2024-06-07 | Verdant       | L   | 0.799      | -            | -                | -                | -         |   -19.98 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           65 |     1705 | 2024-05-30 | SINNERS       | L   | 0.746      | -            | -                | -                | -         |   -14.05 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           64 |     1797 | 2024-05-26 | MOUZ NXT      | L   | 0.718      | -            | -                | -                | -         |   -14.64 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           63 |     1805 | 2024-05-25 | RUBY          | W   | 0.714      | -            | -                | -                | -         |     5.16 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           62 |     1812 | 2024-05-25 | BetBoom       | W   | 0.713      | 0.435        | 0.248 (0.077)    | -                | -         |    17.15 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           61 |     1827 | 2024-05-24 | Alliance      | W   | 0.707      | -            | -                | -                | -         |     3.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           60 |     1847 | 2024-05-23 | DMS           | W   | 0.699      | -            | -                | -                | -         |     5.02 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           59 |     1925 | 2024-05-21 | Rhyno         | W   | 0.687      | -            | -                | -                | -         |     6.22 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           58 |     1965 | 2024-05-20 | EYEBALLERS    | W   | 0.679      | -            | -                | -                | -         |     4.28 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           57 |     1992 | 2024-05-19 | Zero Tenacity | L   | 0.672      | -            | -                | -                | -         |   -12.77 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           56 |     2013 | 2024-05-18 | Sashi         | W   | 0.667      | 0.384        | 0.184 (0.047)    | 0.958 (0.245)    | -         |    12.42 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           55 |     2028 | 2024-05-18 | Rebels        | W   | 0.665      | -            | -                | -                | -         |     7.01 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           54 |     2059 | 2024-05-17 | 3DMAX         | W   | 0.659      | 0.500        | 0.510 (0.168)    | 1.000 (0.329)    | -         |    19.37 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           53 |     2086 | 2024-05-16 | DMS           | W   | 0.654      | -            | -                | -                | -         |     5.24 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           52 |     2098 | 2024-05-16 | Sampi         | W   | 0.652      | 0.384        | -                | 1.000 (0.250)    | -         |     5.55 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           51 |     2132 | 2024-05-15 | PARIVISION    | L   | 0.647      | -            | -                | -                | -         |   -11.11 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           50 |     2200 | 2024-05-14 | Verdant       | W   | 0.639      | -            | -                | -                | -         |     5.04 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           49 |     2206 | 2024-05-14 | MOUZ NXT      | W   | 0.638      | 0.384        | 0.139 (0.034)    | -                | -         |     8.70 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           48 |     2244 | 2024-05-12 | BetBoom       | W   | 0.627      | 0.435        | 0.248 (0.067)    | -                | -         |    16.52 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           47 |     2252 | 2024-05-12 | MOUZ NXT      | W   | 0.625      | 0.435        | 0.139 (0.038)    | 0.961 (0.261)    | -         |     9.35 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           46 |     2286 | 2024-05-11 | BLEED         | W   | 0.618      | -            | -                | -                | -         |     9.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           45 |     2322 | 2024-05-09 | KOI           | W   | 0.605      | -            | -                | -                | -         |     9.56 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           44 |     2379 | 2024-05-06 | Enterprise    | W   | 0.586      | -            | -                | -                | -         |     5.37 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           43 |     2415 | 2024-05-04 | GL Academy    | W   | 0.572      | -            | -                | -                | -         |     3.03 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           42 |     2464 | 2024-05-02 | Permitta      | W   | 0.558      | -            | -                | -                | -         |     6.89 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           41 |     2469 | 2024-05-01 | Nemiga        | L   | 0.554      | -            | -                | -                | -         |    -5.85 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           40 |     2473 | 2024-05-01 | V1dar         | W   | 0.553      | -            | -                | -                | -         |     0.94 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           39 |     2489 | 2024-05-01 | SINNERS       | W   | 0.551      | -            | -                | -                | -         |    10.06 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           38 |     2505 | 2024-04-30 | Alliance      | W   | 0.546      | -            | -                | -                | -         |     5.12 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           37 |     2510 | 2024-04-30 | Zero Tenacity | L   | 0.545      | -            | -                | -                | -         |    -7.84 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           36 |     2535 | 2024-04-28 | BLEED         | L   | 0.534      | -            | -                | -                | -         |    -7.79 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           35 |     2583 | 2024-04-26 | Alliance      | W   | 0.521      | -            | -                | -                | -         |     4.42 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           34 |     2655 | 2024-04-23 | BLEED         | L   | 0.500      | -            | -                | -                | -         |    -7.76 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           33 |     2669 | 2024-04-22 | Passion UA    | W   | 0.494      | 0.500        | 0.173 (0.043)    | 1.000 (0.247)    | -         |     7.77 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           32 |     2675 | 2024-04-22 | Alliance      | L   | 0.492      | -            | -                | -                | -         |   -11.47 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           31 |     2694 | 2024-04-21 | PARIVISION    | W   | 0.486      | -            | -                | -                | -         |     8.04 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           30 |     2772 | 2024-04-19 | HAVU          | W   | 0.472      | -            | -                | -                | -         |     1.92 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           29 |     2833 | 2024-04-18 | Zero Tenacity | W   | 0.465      | -            | -                | -                | -         |     7.84 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           28 |     2855 | 2024-04-17 | Zero Tenacity | L   | 0.459      | -            | -                | -                | -         |    -6.85 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           27 |     2895 | 2024-04-16 | AMKAL         | L   | 0.452      | -            | -                | -                | -         |    -5.32 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           26 |     2905 | 2024-04-15 | Sangal        | L   | 0.447      | -            | -                | -                | -         |    -5.38 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           25 |     3026 | 2024-04-10 | Nexus         | L   | 0.412      | -            | -                | -                | -         |    -9.83 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           24 |     3070 | 2024-04-09 | Rebels        | L   | 0.407      | -            | -                | -                | -         |    -7.66 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           23 |     3116 | 2024-04-08 | MOUZ NXT      | L   | 0.399      | -            | -                | -                | -         |    -6.78 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           22 |     3285 | 2024-04-02 | Metizport     | L   | 0.360      | -            | -                | -                | -         |    -8.11 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           21 |     3292 | 2024-04-02 | Apeks         | L   | 0.359      | -            | -                | -                | -         |    -8.44 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           20 |     3317 | 2024-03-31 | Apeks         | W   | 0.346      | -            | -                | -                | -         |     2.79 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           19 |     3330 | 2024-03-29 | Space         | L   | 0.333      | -            | -                | -                | -         |    -8.70 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           18 |     3377 | 2024-03-27 | Rebels        | W   | 0.321      | -            | -                | -                | -         |     3.68 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           17 |     3388 | 2024-03-27 | Sampi         | W   | 0.321      | -            | -                | -                | -         |     2.59 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           16 |     3420 | 2024-03-25 | FORZE         | W   | 0.307      | -            | -                | -                | -         |     2.71 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           15 |     3481 | 2024-03-21 | BetBoom       | L   | 0.279      | -            | -                | -                | -         |    -1.29 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           14 |     3518 | 2024-03-19 | ex-Sprout     | W   | 0.265      | -            | -                | -                | -         |     0.30 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           13 |     3585 | 2024-03-15 | 3DMAX         | L   | 0.240      | -            | -                | -                | -         |    -0.29 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           12 |     3679 | 2024-03-12 | Metizport     | L   | 0.221      | -            | -                | -                | -         |    -5.04 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           11 |     3686 | 2024-03-12 | ENCE          | W   | 0.220      | -            | -                | -                | -         |     6.21 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           10 |     3697 | 2024-03-11 | KOI           | W   | 0.214      | -            | -                | -                | -         |     3.31 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            9 |     3707 | 2024-03-11 | Virtus.pro    | L   | 0.213      | -            | -                | -                | -         |    -0.21 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            8 |     3771 | 2024-03-08 | PARIVISION    | L   | 0.193      | -            | -                | -                | -         |    -2.88 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            7 |     3858 | 2024-03-05 | Johnny Speeds | W   | 0.174      | -            | -                | -                | -         |     4.26 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            6 |     3861 | 2024-03-05 | Passion UA    | W   | 0.174      | -            | -                | -                | -         |     2.87 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            5 |     3871 | 2024-03-05 | UGANDA        | W   | 0.174      | -            | -                | -                | -         |     0.12 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            4 |     3999 | 2024-02-27 | DMS           | L   | 0.127      | -            | -                | -                | -         |    -2.94 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            3 |     4211 | 2024-02-18 | Aurora        | L   | 0.066      | -            | -                | -                | -         |    -0.07 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            2 |     4261 | 2024-02-16 | 500           | W   | 0.053      | -            | -                | -                | -         |     0.18 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            1 |     4267 | 2024-02-16 | PERA          | W   | 0.052      | -            | -                | -                | -         |     0.04 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($54,530.45)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.860 | $22,000.00     | $18,920.00      |
| 2024-06-09 |      0.813 | $1,500.00      | $1,219.90       |
| 2024-05-26 |      0.720 | $5,000.00      | $3,600.00       |
| 2024-05-18 |      0.667 | $10,000.00     | $6,669.44       |
| 2024-05-12 |      0.627 | $22,000.00     | $13,791.25      |
| 2024-04-24 |      0.506 | $12,500.00     | $6,329.86       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
