### Roster Details<br />
Team Name: B8<br />
Roster: alex666, cptkurtka023, esenthial, headtr1ck, npl<br />
Global Rank: [33](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1158.4<br />
<br />
Final Rank Value (1158.4) = Starting Rank Value (1084.5) + Head To Head Adjustments (73.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.565[<sup>1</sup>](#table2)
- Bounty Collected: 0.470[<sup>2</sup>](#table1)
- Opponent Network: 0.295[<sup>2</sup>](#table1)
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
|           86 |       25 | 2024-08-05 | Permitta      | L   | 1.000      | -            | -                | -                | -         |   -23.80 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           85 |       51 | 2024-08-04 | BC.Game       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.29 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           84 |      121 | 2024-08-02 | Space         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.33 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           83 |      204 | 2024-07-31 | PERA          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.63 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           82 |      256 | 2024-07-30 | ARCRED        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.40 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           81 |      359 | 2024-07-27 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -12.43 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           80 |      407 | 2024-07-25 | SINNERS       | W   | 1.000      | 0.435        | -                | 0.800 (0.348)    | 0 (0.000) |     8.39 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           79 |      566 | 2024-07-20 | Zero Tenacity | L   | 1.000      | -            | -                | -                | -         |   -16.75 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           78 |      621 | 2024-07-19 | Rebels        | W   | 1.000      | 0.500        | -                | 0.578 (0.289)    | 0 (0.000) |     9.11 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           77 |      651 | 2024-07-18 | Aurora        | L   | 1.000      | -            | -                | -                | -         |    -5.49 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           76 |      731 | 2024-07-17 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -12.96 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           75 |      833 | 2024-07-15 | 9INE          | W   | 1.000      | 0.500        | -                | 0.523 (0.262)    | 0 (0.000) |     5.56 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           74 |     1048 | 2024-06-16 | 3DMAX         | W   | 0.860      | 0.435        | 0.510 (0.191)    | 1.000 (0.374)    | 0 (0.000) |    22.56 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           73 |     1058 | 2024-06-16 | Monte         | W   | 0.858      | 0.435        | 0.080 (0.030)    | -                | 0 (0.000) |    10.24 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           72 |     1092 | 2024-06-15 | Illuminar     | W   | 0.852      | -            | -                | -                | 0 (0.000) |     6.00 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           71 |     1172 | 2024-06-13 | MOUZ NXT      | W   | 0.838      | 0.435        | 0.139 (0.050)    | 0.961 (0.350)    | -         |    11.18 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           70 |     1192 | 2024-06-12 | BLEED         | L   | 0.832      | -            | -                | -                | -         |    -5.86 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           69 |     1289 | 2024-06-09 | AMKAL         | L   | 0.812      | -            | -                | -                | -         |   -10.67 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           68 |     1397 | 2024-06-07 | Verdant       | W   | 0.800      | -            | -                | -                | -         |     5.53 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           67 |     1398 | 2024-06-07 | PERA          | W   | 0.800      | -            | -                | -                | -         |     6.55 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           66 |     1414 | 2024-06-07 | Verdant       | L   | 0.799      | -            | -                | -                | -         |   -19.94 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           65 |     1707 | 2024-05-30 | SINNERS       | L   | 0.746      | -            | -                | -                | -         |   -14.07 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           64 |     1799 | 2024-05-26 | MOUZ NXT      | L   | 0.718      | -            | -                | -                | -         |   -14.63 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           63 |     1807 | 2024-05-25 | RUBY          | W   | 0.714      | -            | -                | -                | -         |     5.12 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           62 |     1814 | 2024-05-25 | BetBoom       | W   | 0.713      | 0.435        | 0.248 (0.077)    | -                | -         |    17.11 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           61 |     1829 | 2024-05-24 | Alliance      | W   | 0.707      | -            | -                | -                | -         |     3.58 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           60 |     1849 | 2024-05-23 | DMS           | W   | 0.699      | -            | -                | -                | -         |     5.02 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           59 |     1927 | 2024-05-21 | Rhyno         | W   | 0.687      | -            | -                | -                | -         |     6.17 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           58 |     1967 | 2024-05-20 | EYEBALLERS    | W   | 0.679      | -            | -                | -                | -         |     4.25 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           57 |     1994 | 2024-05-19 | Zero Tenacity | L   | 0.672      | -            | -                | -                | -         |   -12.75 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           56 |     2015 | 2024-05-18 | Sashi         | W   | 0.667      | 0.384        | 0.184 (0.047)    | 0.958 (0.245)    | -         |    12.38 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           55 |     2030 | 2024-05-18 | Rebels        | W   | 0.665      | -            | -                | -                | -         |     6.99 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           54 |     2061 | 2024-05-17 | 3DMAX         | W   | 0.659      | 0.500        | 0.510 (0.168)    | 1.000 (0.329)    | -         |    19.35 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           53 |     2088 | 2024-05-16 | DMS           | W   | 0.654      | -            | -                | -                | -         |     5.24 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           52 |     2100 | 2024-05-16 | Sampi         | W   | 0.652      | 0.384        | -                | 1.000 (0.250)    | -         |     5.51 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           51 |     2134 | 2024-05-15 | PARIVISION    | L   | 0.647      | -            | -                | -                | -         |   -10.41 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           50 |     2202 | 2024-05-14 | Verdant       | W   | 0.639      | -            | -                | -                | -         |     5.09 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           49 |     2208 | 2024-05-14 | MOUZ NXT      | W   | 0.638      | 0.384        | 0.139 (0.034)    | -                | -         |     8.71 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           48 |     2246 | 2024-05-12 | BetBoom       | W   | 0.627      | 0.435        | 0.248 (0.067)    | -                | -         |    16.50 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           47 |     2254 | 2024-05-12 | MOUZ NXT      | W   | 0.625      | 0.435        | 0.139 (0.038)    | 0.961 (0.261)    | -         |     9.37 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           46 |     2288 | 2024-05-11 | BLEED         | W   | 0.618      | -            | -                | -                | -         |     9.61 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           45 |     2324 | 2024-05-09 | KOI           | W   | 0.605      | -            | -                | -                | -         |     9.55 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           44 |     2381 | 2024-05-06 | Enterprise    | W   | 0.586      | -            | -                | -                | -         |     5.34 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           43 |     2417 | 2024-05-04 | GL Academy    | W   | 0.572      | -            | -                | -                | -         |     3.01 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           42 |     2466 | 2024-05-02 | Permitta      | W   | 0.558      | -            | -                | -                | -         |     6.88 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           41 |     2471 | 2024-05-01 | Nemiga        | L   | 0.554      | -            | -                | -                | -         |    -5.84 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           40 |     2475 | 2024-05-01 | V1dar         | W   | 0.553      | -            | -                | -                | -         |     0.93 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           39 |     2491 | 2024-05-01 | SINNERS       | W   | 0.551      | -            | -                | -                | -         |    10.05 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           38 |     2507 | 2024-04-30 | Alliance      | W   | 0.545      | -            | -                | -                | -         |     5.10 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           37 |     2512 | 2024-04-30 | Zero Tenacity | L   | 0.545      | -            | -                | -                | -         |    -7.82 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           36 |     2537 | 2024-04-28 | BLEED         | L   | 0.534      | -            | -                | -                | -         |    -7.77 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           35 |     2585 | 2024-04-26 | Alliance      | W   | 0.520      | -            | -                | -                | -         |     4.41 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           34 |     2657 | 2024-04-23 | BLEED         | L   | 0.500      | -            | -                | -                | -         |    -7.74 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           33 |     2671 | 2024-04-22 | Passion UA    | W   | 0.494      | 0.500        | 0.173 (0.043)    | 1.000 (0.247)    | -         |     7.74 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           32 |     2677 | 2024-04-22 | Alliance      | L   | 0.492      | -            | -                | -                | -         |   -11.48 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           31 |     2696 | 2024-04-21 | PARIVISION    | W   | 0.485      | -            | -                | -                | -         |     8.69 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           30 |     2774 | 2024-04-19 | HAVU          | W   | 0.472      | -            | -                | -                | -         |     1.92 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           29 |     2835 | 2024-04-18 | Zero Tenacity | W   | 0.465      | -            | -                | -                | -         |     7.84 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           28 |     2857 | 2024-04-17 | Zero Tenacity | L   | 0.459      | -            | -                | -                | -         |    -6.85 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           27 |     2897 | 2024-04-16 | AMKAL         | L   | 0.452      | -            | -                | -                | -         |    -5.32 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           26 |     2907 | 2024-04-15 | Sangal        | L   | 0.447      | -            | -                | -                | -         |    -5.00 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           25 |     3028 | 2024-04-10 | Nexus         | L   | 0.412      | -            | -                | -                | -         |    -9.83 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           24 |     3072 | 2024-04-09 | Rebels        | L   | 0.407      | -            | -                | -                | -         |    -7.64 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           23 |     3118 | 2024-04-08 | MOUZ NXT      | L   | 0.399      | -            | -                | -                | -         |    -6.75 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           22 |     3287 | 2024-04-02 | Metizport     | L   | 0.360      | -            | -                | -                | -         |    -8.08 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           21 |     3294 | 2024-04-02 | Apeks         | L   | 0.359      | -            | -                | -                | -         |    -8.43 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           20 |     3319 | 2024-03-31 | Apeks         | W   | 0.346      | -            | -                | -                | -         |     2.79 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           19 |     3332 | 2024-03-29 | Space         | L   | 0.333      | -            | -                | -                | -         |    -8.70 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           18 |     3379 | 2024-03-27 | Rebels        | W   | 0.321      | -            | -                | -                | -         |     3.70 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           17 |     3390 | 2024-03-27 | Sampi         | W   | 0.320      | -            | -                | -                | -         |     2.59 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           16 |     3422 | 2024-03-25 | FORZE         | W   | 0.307      | -            | -                | -                | -         |     2.71 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           15 |     3483 | 2024-03-21 | BetBoom       | L   | 0.278      | -            | -                | -                | -         |    -1.29 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           14 |     3520 | 2024-03-19 | ex-Sprout     | W   | 0.265      | -            | -                | -                | -         |     0.29 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           13 |     3587 | 2024-03-15 | 3DMAX         | L   | 0.240      | -            | -                | -                | -         |    -0.29 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           12 |     3681 | 2024-03-12 | Metizport     | L   | 0.221      | -            | -                | -                | -         |    -5.03 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           11 |     3688 | 2024-03-12 | ENCE          | W   | 0.219      | -            | -                | -                | -         |     6.21 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           10 |     3699 | 2024-03-11 | KOI           | W   | 0.214      | -            | -                | -                | -         |     3.31 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            9 |     3709 | 2024-03-11 | Virtus.pro    | L   | 0.213      | -            | -                | -                | -         |    -0.21 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            8 |     3773 | 2024-03-08 | PARIVISION    | L   | 0.193      | -            | -                | -                | -         |    -2.57 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            7 |     3860 | 2024-03-05 | Johnny Speeds | W   | 0.174      | -            | -                | -                | -         |     4.25 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            6 |     3863 | 2024-03-05 | Passion UA    | W   | 0.174      | -            | -                | -                | -         |     2.86 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            5 |     3873 | 2024-03-05 | UGANDA        | W   | 0.173      | -            | -                | -                | -         |     0.12 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            4 |     4001 | 2024-02-27 | DMS           | L   | 0.127      | -            | -                | -                | -         |    -2.93 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            3 |     4213 | 2024-02-18 | Aurora        | L   | 0.066      | -            | -                | -                | -         |    -0.07 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            2 |     4263 | 2024-02-16 | 500           | W   | 0.053      | -            | -                | -                | -         |     0.18 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            1 |     4269 | 2024-02-16 | PERA          | W   | 0.052      | -            | -                | -                | -         |     0.04 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($54,520.31)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.860 | $22,000.00     | $18,916.94      |
| 2024-06-09 |      0.813 | $1,500.00      | $1,219.69       |
| 2024-05-26 |      0.720 | $5,000.00      | $3,599.31       |
| 2024-05-18 |      0.667 | $10,000.00     | $6,668.06       |
| 2024-05-12 |      0.627 | $22,000.00     | $13,788.19      |
| 2024-04-24 |      0.506 | $12,500.00     | $6,328.13       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
