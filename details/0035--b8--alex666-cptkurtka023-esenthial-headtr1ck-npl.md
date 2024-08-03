### Roster Details<br />
Team Name: B8<br />
Roster: alex666, cptkurtka023, esenthial, headtr1ck, npl<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1163.9<br />
<br />
Final Rank Value (1163.9) = Starting Rank Value (1086.0) + Head To Head Adjustments (77.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.561[<sup>1</sup>](#table2)
- Bounty Collected: 0.472[<sup>2</sup>](#table1)
- Opponent Network: 0.307[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.335<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1086.0
- 400 + ( ( 0.335 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1086.0


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
|           84 |       30 | 2024-08-02 | Space         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.45 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           83 |       96 | 2024-07-31 | PERA          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.93 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           82 |      146 | 2024-07-30 | ARCRED        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.84 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           81 |      250 | 2024-07-27 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -14.00 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           80 |      298 | 2024-07-25 | SINNERS       | W   | 1.000      | 0.435        | -                | 0.784 (0.341)    | 0 (0.000) |     7.70 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           79 |      457 | 2024-07-20 | Zero Tenacity | L   | 1.000      | -            | -                | -                | -         |   -17.67 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           78 |      512 | 2024-07-19 | Rebels        | W   | 1.000      | 0.500        | -                | 0.605 (0.303)    | 0 (0.000) |     9.48 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           77 |      542 | 2024-07-18 | Aurora        | L   | 1.000      | -            | -                | -                | -         |    -5.63 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           76 |      621 | 2024-07-17 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -14.79 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           75 |      721 | 2024-07-15 | 9INE          | W   | 1.000      | 0.500        | -                | 0.553 (0.276)    | 0 (0.000) |     5.63 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           74 |      925 | 2024-06-16 | 3DMAX         | W   | 0.880      | 0.435        | 0.504 (0.193)    | 1.000 (0.382)    | 0 (0.000) |    22.80 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           73 |      934 | 2024-06-16 | Monte         | W   | 0.878      | 0.435        | 0.080 (0.031)    | -                | 0 (0.000) |    10.26 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           72 |      962 | 2024-06-15 | Illuminar     | W   | 0.872      | -            | -                | -                | 0 (0.000) |     6.16 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           71 |     1035 | 2024-06-13 | MOUZ NXT      | W   | 0.858      | 0.435        | 0.139 (0.052)    | 1.000 (0.373)    | 0 (0.000) |    11.00 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           70 |     1053 | 2024-06-12 | BLEED         | L   | 0.852      | -            | -                | -                | -         |    -5.97 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           69 |     1147 | 2024-06-09 | AMKAL         | L   | 0.832      | -            | -                | -                | -         |   -10.82 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           68 |     1250 | 2024-06-07 | Verdant       | W   | 0.820      | -            | -                | -                | -         |     5.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           67 |     1251 | 2024-06-07 | PERA          | W   | 0.820      | -            | -                | -                | -         |     6.82 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           66 |     1267 | 2024-06-07 | Verdant       | L   | 0.819      | -            | -                | -                | -         |   -20.50 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           65 |     1557 | 2024-05-30 | SINNERS       | L   | 0.766      | -            | -                | -                | -         |   -15.37 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           64 |     1648 | 2024-05-26 | MOUZ NXT      | L   | 0.738      | -            | -                | -                | -         |   -15.21 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           63 |     1656 | 2024-05-25 | RUBY          | W   | 0.734      | -            | -                | -                | -         |     5.33 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           62 |     1663 | 2024-05-25 | BetBoom       | W   | 0.733      | 0.435        | 0.252 (0.080)    | -                | -         |    17.73 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           61 |     1678 | 2024-05-24 | Alliance      | W   | 0.727      | -            | -                | -                | -         |     3.77 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           60 |     1698 | 2024-05-23 | DMS           | W   | 0.719      | -            | -                | -                | -         |     5.17 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           59 |     1776 | 2024-05-21 | Rhyno         | W   | 0.707      | -            | -                | -                | -         |     6.51 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           58 |     1816 | 2024-05-20 | EYEBALLERS    | W   | 0.699      | -            | -                | -                | -         |     4.42 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           57 |     1842 | 2024-05-19 | Zero Tenacity | L   | 0.692      | -            | -                | -                | -         |   -13.22 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           56 |     1863 | 2024-05-18 | Sashi         | W   | 0.687      | 0.384        | 0.184 (0.049)    | 0.998 (0.263)    | -         |    12.91 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           55 |     1878 | 2024-05-18 | Rebels        | W   | 0.685      | -            | -                | -                | -         |     7.27 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           54 |     1909 | 2024-05-17 | 3DMAX         | W   | 0.679      | 0.500        | 0.504 (0.171)    | 1.000 (0.339)    | -         |    19.85 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           53 |     1936 | 2024-05-16 | DMS           | W   | 0.673      | -            | -                | -                | -         |     5.43 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           52 |     1948 | 2024-05-16 | Sampi         | W   | 0.671      | 0.384        | -                | 1.000 (0.258)    | -         |     5.87 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           51 |     1982 | 2024-05-15 | PARIVISION    | L   | 0.667      | -            | -                | -                | -         |   -11.62 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           50 |     2050 | 2024-05-14 | Verdant       | W   | 0.659      | -            | -                | -                | -         |     5.23 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           49 |     2056 | 2024-05-14 | MOUZ NXT      | W   | 0.658      | 0.384        | 0.139 (0.035)    | -                | -         |     8.90 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           48 |     2094 | 2024-05-12 | BetBoom       | W   | 0.647      | 0.435        | 0.252 (0.071)    | -                | -         |    17.16 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           47 |     2102 | 2024-05-12 | MOUZ NXT      | W   | 0.645      | 0.435        | 0.139 (0.039)    | 1.000 (0.280)    | -         |     9.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           46 |     2136 | 2024-05-11 | BLEED         | W   | 0.638      | -            | -                | -                | -         |    10.11 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           45 |     2172 | 2024-05-09 | KOI           | W   | 0.624      | -            | -                | -                | -         |     6.72 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           44 |     2228 | 2024-05-06 | Enterprise    | W   | 0.606      | -            | -                | -                | -         |     5.58 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           43 |     2264 | 2024-05-04 | GL Academy    | W   | 0.592      | -            | -                | -                | -         |     3.21 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           42 |     2313 | 2024-05-02 | Permitta      | W   | 0.578      | -            | -                | -                | -         |     6.72 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           41 |     2318 | 2024-05-01 | Nemiga        | L   | 0.574      | -            | -                | -                | -         |    -6.29 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           40 |     2322 | 2024-05-01 | V1dar         | W   | 0.573      | -            | -                | -                | -         |     1.00 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           39 |     2338 | 2024-05-01 | SINNERS       | W   | 0.571      | -            | -                | -                | -         |     9.34 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           38 |     2354 | 2024-04-30 | Alliance      | W   | 0.565      | -            | -                | -                | -         |     5.39 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           37 |     2359 | 2024-04-30 | Zero Tenacity | L   | 0.564      | -            | -                | -                | -         |    -8.23 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           36 |     2384 | 2024-04-28 | BLEED         | L   | 0.554      | -            | -                | -                | -         |    -7.93 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           35 |     2432 | 2024-04-26 | Alliance      | W   | 0.540      | -            | -                | -                | -         |     4.66 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           34 |     2503 | 2024-04-23 | BLEED         | L   | 0.519      | -            | -                | -                | -         |    -7.91 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           33 |     2517 | 2024-04-22 | Passion UA    | W   | 0.514      | 0.500        | 0.172 (0.044)    | 1.000 (0.257)    | -         |     7.88 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           32 |     2523 | 2024-04-22 | Alliance      | L   | 0.512      | -            | -                | -                | -         |   -11.87 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           31 |     2542 | 2024-04-21 | PARIVISION    | W   | 0.505      | -            | -                | -                | -         |     8.21 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           30 |     2620 | 2024-04-19 | HAVU          | W   | 0.492      | -            | -                | -                | -         |     2.05 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           29 |     2681 | 2024-04-18 | Zero Tenacity | W   | 0.484      | -            | -                | -                | -         |     8.11 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           28 |     2703 | 2024-04-17 | Zero Tenacity | L   | 0.479      | -            | -                | -                | -         |    -7.21 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           27 |     2743 | 2024-04-16 | AMKAL         | L   | 0.471      | -            | -                | -                | -         |    -5.47 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           26 |     2753 | 2024-04-15 | Sangal        | L   | 0.467      | -            | -                | -                | -         |    -5.90 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           25 |     2874 | 2024-04-10 | Nexus         | L   | 0.432      | -            | -                | -                | -         |   -10.29 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           24 |     2918 | 2024-04-09 | Rebels        | L   | 0.427      | -            | -                | -                | -         |    -8.07 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           23 |     2964 | 2024-04-08 | MOUZ NXT      | L   | 0.419      | -            | -                | -                | -         |    -7.30 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           22 |     3133 | 2024-04-02 | Metizport     | L   | 0.380      | -            | -                | -                | -         |    -8.57 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           21 |     3140 | 2024-04-02 | Apeks         | L   | 0.379      | -            | -                | -                | -         |    -8.83 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           20 |     3165 | 2024-03-31 | Apeks         | W   | 0.366      | -            | -                | -                | -         |     3.02 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           19 |     3178 | 2024-03-29 | Space         | L   | 0.353      | -            | -                | -                | -         |    -9.22 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           18 |     3224 | 2024-03-27 | Rebels        | W   | 0.341      | -            | -                | -                | -         |     3.87 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           17 |     3234 | 2024-03-27 | Sampi         | W   | 0.340      | -            | -                | -                | -         |     2.77 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           16 |     3265 | 2024-03-25 | FORZE         | W   | 0.326      | -            | -                | -                | -         |     2.93 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           15 |     3324 | 2024-03-21 | BetBoom       | L   | 0.298      | -            | -                | -                | -         |    -1.33 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           14 |     3361 | 2024-03-19 | ex-Sprout     | W   | 0.285      | -            | -                | -                | -         |     0.34 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           13 |     3427 | 2024-03-15 | 3DMAX         | L   | 0.260      | -            | -                | -                | -         |    -0.33 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           12 |     3520 | 2024-03-12 | Metizport     | L   | 0.241      | -            | -                | -                | -         |    -5.50 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           11 |     3526 | 2024-03-12 | ENCE          | W   | 0.239      | -            | -                | -                | -         |     6.72 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           10 |     3537 | 2024-03-11 | KOI           | W   | 0.234      | -            | -                | -                | -         |     2.21 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            9 |     3547 | 2024-03-11 | Virtus.pro    | L   | 0.233      | -            | -                | -                | -         |    -0.22 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            8 |     3611 | 2024-03-08 | PARIVISION    | L   | 0.213      | -            | -                | -                | -         |    -3.26 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            7 |     3698 | 2024-03-05 | Johnny Speeds | W   | 0.194      | -            | -                | -                | -         |     4.67 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            6 |     3701 | 2024-03-05 | Passion UA    | W   | 0.194      | -            | -                | -                | -         |     3.12 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            5 |     3711 | 2024-03-05 | UGANDA        | W   | 0.193      | -            | -                | -                | -         |     0.13 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            4 |     3839 | 2024-02-27 | DMS           | L   | 0.147      | -            | -                | -                | -         |    -3.40 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            3 |     4051 | 2024-02-18 | Aurora        | L   | 0.086      | -            | -                | -                | -         |    -0.09 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            2 |     4100 | 2024-02-16 | 500           | W   | 0.073      | -            | -                | -                | -         |     0.24 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            1 |     4106 | 2024-02-16 | PERA          | W   | 0.072      | -            | -                | -                | -         |     0.05 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($53,973.55)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.880 | $22,000.00     | $19,354.91      |
| 2024-06-09 |      0.833 | $1,500.00      | $1,249.55       |
| 2024-05-26 |      0.740 | $5,000.00      | $3,698.84       |
| 2024-05-18 |      0.687 | $10,000.00     | $6,867.13       |
| 2024-05-12 |      0.647 | $22,000.00     | $14,226.16      |
| 2024-04-24 |      0.526 | $12,500.00     | $6,576.97       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
