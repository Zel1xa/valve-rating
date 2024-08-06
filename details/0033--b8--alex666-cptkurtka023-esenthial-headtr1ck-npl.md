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
|           86 |       20 | 2024-08-05 | Permitta      | L   | 1.000      | -            | -                | -                | -         |   -23.79 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           85 |       46 | 2024-08-04 | BC.Game       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.34 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           84 |      116 | 2024-08-02 | Space         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.36 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           83 |      199 | 2024-07-31 | PERA          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.68 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           82 |      251 | 2024-07-30 | ARCRED        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.46 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           81 |      354 | 2024-07-27 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -12.75 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           80 |      402 | 2024-07-25 | SINNERS       | W   | 1.000      | 0.435        | -                | 0.800 (0.348)    | 0 (0.000) |     8.39 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           79 |      561 | 2024-07-20 | Zero Tenacity | L   | 1.000      | -            | -                | -                | -         |   -16.74 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           78 |      616 | 2024-07-19 | Rebels        | W   | 1.000      | 0.500        | -                | 0.578 (0.289)    | 0 (0.000) |     9.14 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           77 |      646 | 2024-07-18 | Aurora        | L   | 1.000      | -            | -                | -                | -         |    -5.46 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           76 |      726 | 2024-07-17 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -13.36 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           75 |      828 | 2024-07-15 | 9INE          | W   | 1.000      | 0.500        | -                | 0.523 (0.262)    | 0 (0.000) |     5.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           74 |     1043 | 2024-06-16 | 3DMAX         | W   | 0.860      | 0.435        | 0.510 (0.191)    | 1.000 (0.374)    | 0 (0.000) |    22.59 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           73 |     1053 | 2024-06-16 | Monte         | W   | 0.859      | 0.435        | 0.080 (0.030)    | -                | 0 (0.000) |    10.24 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           72 |     1087 | 2024-06-15 | Illuminar     | W   | 0.852      | -            | -                | -                | 0 (0.000) |     6.03 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           71 |     1167 | 2024-06-13 | MOUZ NXT      | W   | 0.838      | 0.435        | 0.139 (0.050)    | 0.962 (0.350)    | -         |    11.18 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           70 |     1187 | 2024-06-12 | BLEED         | L   | 0.833      | -            | -                | -                | -         |    -5.84 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           69 |     1284 | 2024-06-09 | AMKAL         | L   | 0.813      | -            | -                | -                | -         |   -10.63 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           68 |     1392 | 2024-06-07 | Verdant       | W   | 0.800      | -            | -                | -                | -         |     5.49 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           67 |     1393 | 2024-06-07 | PERA          | W   | 0.800      | -            | -                | -                | -         |     6.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           66 |     1409 | 2024-06-07 | Verdant       | L   | 0.799      | -            | -                | -                | -         |   -19.99 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           65 |     1702 | 2024-05-30 | SINNERS       | L   | 0.747      | -            | -                | -                | -         |   -14.06 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           64 |     1794 | 2024-05-26 | MOUZ NXT      | L   | 0.719      | -            | -                | -                | -         |   -14.64 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           63 |     1802 | 2024-05-25 | RUBY          | W   | 0.714      | -            | -                | -                | -         |     5.16 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           62 |     1809 | 2024-05-25 | BetBoom       | W   | 0.713      | 0.435        | 0.248 (0.077)    | -                | -         |    17.16 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           61 |     1824 | 2024-05-24 | Alliance      | W   | 0.707      | -            | -                | -                | -         |     3.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           60 |     1844 | 2024-05-23 | DMS           | W   | 0.699      | -            | -                | -                | -         |     5.02 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           59 |     1922 | 2024-05-21 | Rhyno         | W   | 0.688      | -            | -                | -                | -         |     6.20 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           58 |     1962 | 2024-05-20 | EYEBALLERS    | W   | 0.680      | -            | -                | -                | -         |     4.28 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           57 |     1989 | 2024-05-19 | Zero Tenacity | L   | 0.672      | -            | -                | -                | -         |   -12.78 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           56 |     2010 | 2024-05-18 | Sashi         | W   | 0.667      | 0.384        | 0.184 (0.047)    | 0.958 (0.246)    | -         |    12.43 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           55 |     2025 | 2024-05-18 | Rebels        | W   | 0.665      | -            | -                | -                | -         |     7.01 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           54 |     2056 | 2024-05-17 | 3DMAX         | W   | 0.659      | 0.500        | 0.510 (0.168)    | 1.000 (0.330)    | -         |    19.37 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           53 |     2083 | 2024-05-16 | DMS           | W   | 0.654      | -            | -                | -                | -         |     5.24 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           52 |     2095 | 2024-05-16 | Sampi         | W   | 0.652      | 0.384        | -                | 1.000 (0.251)    | -         |     5.55 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           51 |     2129 | 2024-05-15 | PARIVISION    | L   | 0.647      | -            | -                | -                | -         |   -11.13 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           50 |     2197 | 2024-05-14 | Verdant       | W   | 0.640      | -            | -                | -                | -         |     5.04 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           49 |     2203 | 2024-05-14 | MOUZ NXT      | W   | 0.639      | 0.384        | 0.139 (0.034)    | -                | -         |     8.70 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           48 |     2241 | 2024-05-12 | BetBoom       | W   | 0.627      | 0.435        | 0.248 (0.067)    | -                | -         |    16.53 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           47 |     2249 | 2024-05-12 | MOUZ NXT      | W   | 0.625      | 0.435        | 0.139 (0.038)    | 0.962 (0.261)    | -         |     9.35 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           46 |     2283 | 2024-05-11 | BLEED         | W   | 0.618      | -            | -                | -                | -         |     9.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           45 |     2319 | 2024-05-09 | KOI           | W   | 0.605      | -            | -                | -                | -         |     9.57 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           44 |     2376 | 2024-05-06 | Enterprise    | W   | 0.586      | -            | -                | -                | -         |     5.37 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           43 |     2412 | 2024-05-04 | GL Academy    | W   | 0.573      | -            | -                | -                | -         |     3.04 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           42 |     2461 | 2024-05-02 | Permitta      | W   | 0.558      | -            | -                | -                | -         |     6.90 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           41 |     2466 | 2024-05-01 | Nemiga        | L   | 0.554      | -            | -                | -                | -         |    -5.85 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           40 |     2470 | 2024-05-01 | V1dar         | W   | 0.553      | -            | -                | -                | -         |     0.94 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           39 |     2486 | 2024-05-01 | SINNERS       | W   | 0.552      | -            | -                | -                | -         |    10.06 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           38 |     2502 | 2024-04-30 | Alliance      | W   | 0.546      | -            | -                | -                | -         |     5.12 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           37 |     2507 | 2024-04-30 | Zero Tenacity | L   | 0.545      | -            | -                | -                | -         |    -7.84 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           36 |     2532 | 2024-04-28 | BLEED         | L   | 0.534      | -            | -                | -                | -         |    -7.79 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           35 |     2580 | 2024-04-26 | Alliance      | W   | 0.521      | -            | -                | -                | -         |     4.42 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           34 |     2652 | 2024-04-23 | BLEED         | L   | 0.500      | -            | -                | -                | -         |    -7.76 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           33 |     2666 | 2024-04-22 | Passion UA    | W   | 0.494      | 0.500        | 0.173 (0.043)    | 1.000 (0.247)    | -         |     7.77 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           32 |     2672 | 2024-04-22 | Alliance      | L   | 0.492      | -            | -                | -                | -         |   -11.48 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           31 |     2691 | 2024-04-21 | PARIVISION    | W   | 0.486      | -            | -                | -                | -         |     8.03 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           30 |     2769 | 2024-04-19 | HAVU          | W   | 0.473      | -            | -                | -                | -         |     1.92 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           29 |     2830 | 2024-04-18 | Zero Tenacity | W   | 0.465      | -            | -                | -                | -         |     7.85 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           28 |     2852 | 2024-04-17 | Zero Tenacity | L   | 0.459      | -            | -                | -                | -         |    -6.85 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           27 |     2892 | 2024-04-16 | AMKAL         | L   | 0.452      | -            | -                | -                | -         |    -5.32 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           26 |     2902 | 2024-04-15 | Sangal        | L   | 0.448      | -            | -                | -                | -         |    -5.39 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           25 |     3023 | 2024-04-10 | Nexus         | L   | 0.413      | -            | -                | -                | -         |    -9.84 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           24 |     3067 | 2024-04-09 | Rebels        | L   | 0.407      | -            | -                | -                | -         |    -7.67 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           23 |     3113 | 2024-04-08 | MOUZ NXT      | L   | 0.399      | -            | -                | -                | -         |    -6.79 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           22 |     3282 | 2024-04-02 | Metizport     | L   | 0.361      | -            | -                | -                | -         |    -8.12 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           21 |     3289 | 2024-04-02 | Apeks         | L   | 0.360      | -            | -                | -                | -         |    -8.44 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           20 |     3314 | 2024-03-31 | Apeks         | W   | 0.346      | -            | -                | -                | -         |     2.80 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           19 |     3327 | 2024-03-29 | Space         | L   | 0.334      | -            | -                | -                | -         |    -8.71 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           18 |     3374 | 2024-03-27 | Rebels        | W   | 0.321      | -            | -                | -                | -         |     3.69 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           17 |     3385 | 2024-03-27 | Sampi         | W   | 0.321      | -            | -                | -                | -         |     2.59 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           16 |     3417 | 2024-03-25 | FORZE         | W   | 0.307      | -            | -                | -                | -         |     2.71 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           15 |     3478 | 2024-03-21 | BetBoom       | L   | 0.279      | -            | -                | -                | -         |    -1.29 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           14 |     3515 | 2024-03-19 | ex-Sprout     | W   | 0.266      | -            | -                | -                | -         |     0.30 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           13 |     3582 | 2024-03-15 | 3DMAX         | L   | 0.240      | -            | -                | -                | -         |    -0.29 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           12 |     3676 | 2024-03-12 | Metizport     | L   | 0.221      | -            | -                | -                | -         |    -5.05 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           11 |     3683 | 2024-03-12 | ENCE          | W   | 0.220      | -            | -                | -                | -         |     6.21 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           10 |     3694 | 2024-03-11 | KOI           | W   | 0.214      | -            | -                | -                | -         |     3.31 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            9 |     3704 | 2024-03-11 | Virtus.pro    | L   | 0.213      | -            | -                | -                | -         |    -0.21 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            8 |     3768 | 2024-03-08 | PARIVISION    | L   | 0.194      | -            | -                | -                | -         |    -2.89 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            7 |     3855 | 2024-03-05 | Johnny Speeds | W   | 0.174      | -            | -                | -                | -         |     4.26 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            6 |     3858 | 2024-03-05 | Passion UA    | W   | 0.174      | -            | -                | -                | -         |     2.87 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            5 |     3868 | 2024-03-05 | UGANDA        | W   | 0.174      | -            | -                | -                | -         |     0.12 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            4 |     3996 | 2024-02-27 | DMS           | L   | 0.127      | -            | -                | -                | -         |    -2.95 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            3 |     4208 | 2024-02-18 | Aurora        | L   | 0.066      | -            | -                | -                | -         |    -0.07 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            2 |     4258 | 2024-02-16 | 500           | W   | 0.054      | -            | -                | -                | -         |     0.18 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            1 |     4264 | 2024-02-16 | PERA          | W   | 0.053      | -            | -                | -                | -         |     0.04 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($54,550.73)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.860 | $22,000.00     | $18,926.11      |
| 2024-06-09 |      0.814 | $1,500.00      | $1,220.31       |
| 2024-05-26 |      0.720 | $5,000.00      | $3,601.39       |
| 2024-05-18 |      0.667 | $10,000.00     | $6,672.22       |
| 2024-05-12 |      0.627 | $22,000.00     | $13,797.36      |
| 2024-04-24 |      0.507 | $12,500.00     | $6,333.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
