### Roster Details<br />
Team Name: B8<br />
Roster: alex666, cptkurtka023, esenthial, headtr1ck, npl<br />
Global Rank: [36](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [27]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1156.0<br />
<br />
Final Rank Value (1156.0) = Starting Rank Value (1094.5) + Head To Head Adjustments (61.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.564[<sup>1</sup>](#table2)
- Bounty Collected: 0.475[<sup>2</sup>](#table1)
- Opponent Network: 0.310[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.337<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1094.5
- 400 + ( ( 0.337 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1094.5


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
|           85 |       31 | 2024-07-31 | PERA          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.03 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           84 |       84 | 2024-07-30 | ARCRED        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.86 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           83 |      188 | 2024-07-27 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -13.42 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           82 |      236 | 2024-07-25 | SINNERS       | W   | 1.000      | 0.435        | -                | 0.768 (0.334)    | 0 (0.000) |     7.90 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           81 |      398 | 2024-07-20 | Zero Tenacity | L   | 1.000      | -            | -                | -                | -         |   -18.55 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           80 |      455 | 2024-07-19 | Rebels        | W   | 1.000      | 0.500        | -                | 0.635 (0.318)    | 0 (0.000) |     8.94 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           79 |      489 | 2024-07-18 | Aurora        | L   | 1.000      | -            | -                | -                | -         |    -5.53 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           78 |      569 | 2024-07-17 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -14.20 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           77 |      677 | 2024-07-15 | 9INE          | W   | 1.000      | 0.500        | -                | 0.521 (0.260)    | 0 (0.000) |     6.76 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           76 |      893 | 2024-06-16 | 3DMAX         | W   | 0.894      | 0.435        | 0.505 (0.196)    | 1.000 (0.389)    | 0 (0.000) |    23.36 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           75 |      902 | 2024-06-16 | Monte         | W   | 0.893      | 0.435        | 0.081 (0.031)    | -                | 0 (0.000) |    10.76 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           74 |      933 | 2024-06-15 | Illuminar     | W   | 0.886      | -            | -                | -                | 0 (0.000) |     6.92 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           73 |     1007 | 2024-06-13 | MOUZ NXT      | W   | 0.872      | 0.435        | 0.141 (0.053)    | 1.000 (0.379)    | 0 (0.000) |    12.09 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           72 |     1027 | 2024-06-12 | BLEED         | L   | 0.867      | -            | -                | -                | -         |    -5.71 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           71 |     1126 | 2024-06-09 | AMKAL         | L   | 0.847      | -            | -                | -                | -         |   -10.62 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           70 |     1243 | 2024-06-07 | Verdant       | W   | 0.835      | -            | -                | -                | 0 (0.000) |     6.08 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           69 |     1244 | 2024-06-07 | PERA          | W   | 0.834      | -            | -                | -                | -         |     7.24 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           68 |     1260 | 2024-06-07 | Verdant       | L   | 0.833      | -            | -                | -                | -         |   -20.46 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           67 |     1559 | 2024-05-30 | SINNERS       | L   | 0.781      | -            | -                | -                | -         |   -15.32 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           66 |     1653 | 2024-05-26 | MOUZ NXT      | L   | 0.753      | -            | -                | -                | -         |   -15.16 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           65 |     1661 | 2024-05-25 | RUBY          | W   | 0.749      | -            | -                | -                | -         |     5.88 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           64 |     1668 | 2024-05-25 | BetBoom       | W   | 0.747      | 0.435        | 0.257 (0.084)    | -                | -         |    18.47 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           63 |     1683 | 2024-05-24 | Alliance      | W   | 0.741      | -            | -                | -                | -         |     4.09 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           62 |     1703 | 2024-05-23 | DMS           | W   | 0.733      | -            | -                | -                | -         |     5.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           61 |     1795 | 2024-05-21 | Rhyno         | W   | 0.722      | -            | -                | -                | -         |     7.28 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           60 |     1841 | 2024-05-20 | EYEBALLERS    | W   | 0.714      | -            | -                | -                | -         |     4.83 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           59 |     1873 | 2024-05-19 | Zero Tenacity | L   | 0.707      | -            | -                | -                | -         |   -13.10 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           58 |     1894 | 2024-05-18 | Sashi         | W   | 0.701      | 0.384        | 0.187 (0.050)    | 0.971 (0.262)    | -         |    13.65 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           57 |     1905 | 2024-05-18 | MOUZ NXT      | L   | 0.700      | -            | -                | -                | -         |   -13.63 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           56 |     1910 | 2024-05-18 | Rebels        | W   | 0.699      | -            | -                | -                | -         |     7.73 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           55 |     1941 | 2024-05-17 | 3DMAX         | W   | 0.693      | 0.500        | 0.505 (0.175)    | 1.000 (0.347)    | -         |    20.32 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           54 |     1968 | 2024-05-16 | DMS           | W   | 0.688      | -            | -                | -                | -         |     5.65 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           53 |     1980 | 2024-05-16 | Sampi         | W   | 0.686      | 0.384        | -                | 1.000 (0.264)    | -         |     5.83 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           52 |     2014 | 2024-05-15 | PARIVISION    | L   | 0.682      | -            | -                | -                | -         |   -11.74 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           51 |     2088 | 2024-05-14 | Verdant       | W   | 0.674      | -            | -                | -                | -         |     5.58 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           50 |     2095 | 2024-05-14 | MOUZ NXT      | W   | 0.673      | 0.384        | 0.141 (0.036)    | -                | -         |     8.75 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           49 |     2135 | 2024-05-12 | BetBoom       | W   | 0.661      | 0.435        | 0.257 (0.074)    | -                | -         |    17.68 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           48 |     2143 | 2024-05-12 | MOUZ NXT      | W   | 0.659      | 0.435        | 0.141 (0.040)    | 1.000 (0.287)    | -         |     9.46 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           47 |     2177 | 2024-05-11 | BLEED         | W   | 0.652      | -            | -                | -                | -         |    10.35 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           46 |     2213 | 2024-05-09 | KOI           | W   | 0.639      | -            | -                | -                | -         |     7.11 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           45 |     2272 | 2024-05-06 | Enterprise    | W   | 0.620      | -            | -                | -                | -         |     5.65 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           44 |     2308 | 2024-05-04 | GL Academy    | W   | 0.607      | -            | -                | -                | -         |     3.39 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           43 |     2358 | 2024-05-02 | Permitta      | W   | 0.593      | -            | -                | -                | -         |     6.89 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           42 |     2364 | 2024-05-01 | Nemiga        | L   | 0.588      | -            | -                | -                | -         |    -6.39 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           41 |     2368 | 2024-05-01 | V1dar         | W   | 0.588      | -            | -                | -                | -         |     1.05 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           40 |     2384 | 2024-05-01 | SINNERS       | W   | 0.586      | -            | -                | -                | -         |     9.21 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           39 |     2401 | 2024-04-30 | Alliance      | W   | 0.580      | -            | -                | -                | -         |     5.64 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           38 |     2406 | 2024-04-30 | Zero Tenacity | L   | 0.579      | -            | -                | -                | -         |    -8.41 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           37 |     2431 | 2024-04-28 | BLEED         | L   | 0.568      | -            | -                | -                | -         |    -8.12 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           36 |     2480 | 2024-04-26 | Alliance      | W   | 0.555      | -            | -                | -                | -         |     4.86 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           35 |     2553 | 2024-04-23 | BLEED         | L   | 0.534      | -            | -                | -                | -         |    -7.93 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           34 |     2566 | 2024-04-23 | PARIVISION    | L   | 0.532      | -            | -                | -                | -         |    -8.37 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           33 |     2568 | 2024-04-22 | Passion UA    | W   | 0.528      | 0.500        | 0.172 (0.046)    | 1.000 (0.264)    | -         |     8.10 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           32 |     2574 | 2024-04-22 | Alliance      | L   | 0.527      | -            | -                | -                | -         |   -12.28 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           31 |     2594 | 2024-04-21 | PARIVISION    | W   | 0.520      | -            | -                | -                | -         |     8.18 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           30 |     2675 | 2024-04-19 | HAVU          | W   | 0.507      | -            | -                | -                | -         |     2.10 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           29 |     2737 | 2024-04-18 | Zero Tenacity | W   | 0.499      | -            | -                | -                | -         |     8.17 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           28 |     2760 | 2024-04-17 | Zero Tenacity | L   | 0.493      | -            | -                | -                | -         |    -7.62 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           27 |     2801 | 2024-04-16 | AMKAL         | L   | 0.486      | -            | -                | -                | -         |    -5.73 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           26 |     2811 | 2024-04-15 | Sangal        | L   | 0.482      | -            | -                | -                | -         |    -6.33 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           25 |     2933 | 2024-04-10 | Nexus         | L   | 0.447      | -            | -                | -                | -         |   -10.70 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           24 |     2977 | 2024-04-09 | Rebels        | L   | 0.442      | -            | -                | -                | -         |    -8.29 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           23 |     3023 | 2024-04-08 | MOUZ NXT      | L   | 0.433      | -            | -                | -                | -         |    -7.25 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           22 |     3200 | 2024-04-02 | Metizport     | L   | 0.395      | -            | -                | -                | -         |    -8.99 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           21 |     3207 | 2024-04-02 | Apeks         | L   | 0.394      | -            | -                | -                | -         |    -9.09 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           20 |     3232 | 2024-03-31 | Apeks         | W   | 0.380      | -            | -                | -                | -         |     3.22 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           19 |     3245 | 2024-03-29 | Space         | L   | 0.368      | -            | -                | -                | -         |    -9.68 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           18 |     3293 | 2024-03-27 | Rebels        | W   | 0.355      | -            | -                | -                | -         |     4.08 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           17 |     3304 | 2024-03-27 | Sampi         | W   | 0.355      | -            | -                | -                | -         |     2.83 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           16 |     3340 | 2024-03-25 | FORZE         | W   | 0.341      | -            | -                | -                | -         |     3.09 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           15 |     3401 | 2024-03-21 | BetBoom       | L   | 0.313      | -            | -                | -                | -         |    -1.37 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           14 |     3438 | 2024-03-19 | ex-Sprout     | W   | 0.300      | -            | -                | -                | -         |     0.37 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           13 |     3505 | 2024-03-15 | 3DMAX         | L   | 0.274      | -            | -                | -                | -         |    -0.35 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           12 |     3604 | 2024-03-12 | Metizport     | L   | 0.255      | -            | -                | -                | -         |    -5.90 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           11 |     3611 | 2024-03-12 | ENCE          | W   | 0.254      | -            | -                | -                | -         |     7.15 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           10 |     3622 | 2024-03-11 | KOI           | W   | 0.249      | -            | -                | -                | -         |     2.34 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            9 |     3632 | 2024-03-11 | Virtus.pro    | L   | 0.247      | -            | -                | -                | -         |    -0.23 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            8 |     3697 | 2024-03-08 | PARIVISION    | L   | 0.228      | -            | -                | -                | -         |    -3.63 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            7 |     3784 | 2024-03-05 | Johnny Speeds | W   | 0.209      | -            | -                | -                | -         |     5.04 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            6 |     3791 | 2024-03-05 | Passion UA    | W   | 0.208      | -            | -                | -                | -         |     3.38 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            5 |     3802 | 2024-03-05 | UGANDA        | W   | 0.208      | -            | -                | -                | -         |     0.13 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            4 |     3932 | 2024-02-27 | DMS           | L   | 0.161      | -            | -                | -                | -         |    -3.76 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            3 |     4152 | 2024-02-18 | Aurora        | L   | 0.100      | -            | -                | -                | -         |    -0.11 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            2 |     4202 | 2024-02-16 | 500           | W   | 0.088      | -            | -                | -                | -         |     0.32 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            1 |     4208 | 2024-02-16 | PERA          | W   | 0.087      | -            | -                | -                | -         |     0.06 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55,044.90)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.894 | $22,000.00     | $19,677.78      |
| 2024-06-09 |      0.848 | $1,500.00      | $1,271.56       |
| 2024-05-26 |      0.754 | $5,000.00      | $3,772.22       |
| 2024-05-18 |      0.701 | $10,000.00     | $7,013.89       |
| 2024-05-12 |      0.661 | $22,000.00     | $14,549.03      |
| 2024-04-24 |      0.541 | $12,500.00     | $6,760.42       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
