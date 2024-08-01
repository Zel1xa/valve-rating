### Roster Details<br />
Team Name: B8<br />
Roster: alex666, cptkurtka023, esenthial, headtr1ck, npl<br />
Global Rank: [36](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [27]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1155.2<br />
<br />
Final Rank Value (1155.2) = Starting Rank Value (1093.5) + Head To Head Adjustments (61.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.563[<sup>1</sup>](#table2)
- Bounty Collected: 0.475[<sup>2</sup>](#table1)
- Opponent Network: 0.310[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.337<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1093.5
- 400 + ( ( 0.337 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1093.5


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
|           85 |       35 | 2024-07-31 | PERA          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.05 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           84 |       88 | 2024-07-30 | ARCRED        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.87 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           83 |      192 | 2024-07-27 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -13.39 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           82 |      240 | 2024-07-25 | SINNERS       | W   | 1.000      | 0.435        | -                | 0.768 (0.334)    | 0 (0.000) |     7.92 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           81 |      402 | 2024-07-20 | Zero Tenacity | L   | 1.000      | -            | -                | -                | -         |   -18.54 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           80 |      459 | 2024-07-19 | Rebels        | W   | 1.000      | 0.500        | -                | 0.635 (0.318)    | 0 (0.000) |     8.94 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           79 |      493 | 2024-07-18 | Aurora        | L   | 1.000      | -            | -                | -                | -         |    -5.50 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           78 |      573 | 2024-07-17 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -14.16 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           77 |      681 | 2024-07-15 | 9INE          | W   | 1.000      | 0.500        | -                | 0.521 (0.261)    | 0 (0.000) |     6.77 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           76 |      897 | 2024-06-16 | 3DMAX         | W   | 0.893      | 0.435        | 0.505 (0.196)    | 1.000 (0.388)    | 0 (0.000) |    23.33 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           75 |      906 | 2024-06-16 | Monte         | W   | 0.891      | 0.435        | 0.081 (0.031)    | -                | 0 (0.000) |    10.75 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           74 |      937 | 2024-06-15 | Illuminar     | W   | 0.885      | -            | -                | -                | 0 (0.000) |     6.92 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           73 |     1011 | 2024-06-13 | MOUZ NXT      | W   | 0.871      | 0.435        | 0.141 (0.053)    | 1.000 (0.378)    | 0 (0.000) |    12.07 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           72 |     1031 | 2024-06-12 | BLEED         | L   | 0.866      | -            | -                | -                | -         |    -5.71 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           71 |     1130 | 2024-06-09 | AMKAL         | L   | 0.845      | -            | -                | -                | -         |   -10.59 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           70 |     1247 | 2024-06-07 | Verdant       | W   | 0.833      | -            | -                | -                | 0 (0.000) |     6.08 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           69 |     1248 | 2024-06-07 | PERA          | W   | 0.833      | -            | -                | -                | -         |     7.26 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           68 |     1264 | 2024-06-07 | Verdant       | L   | 0.832      | -            | -                | -                | -         |   -20.42 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           67 |     1563 | 2024-05-30 | SINNERS       | L   | 0.779      | -            | -                | -                | -         |   -15.29 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           66 |     1657 | 2024-05-26 | MOUZ NXT      | L   | 0.751      | -            | -                | -                | -         |   -15.13 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           65 |     1665 | 2024-05-25 | RUBY          | W   | 0.747      | -            | -                | -                | -         |     5.88 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           64 |     1672 | 2024-05-25 | BetBoom       | W   | 0.746      | 0.435        | 0.257 (0.083)    | -                | -         |    18.45 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           63 |     1687 | 2024-05-24 | Alliance      | W   | 0.740      | -            | -                | -                | -         |     4.08 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           62 |     1707 | 2024-05-23 | DMS           | W   | 0.732      | -            | -                | -                | -         |     5.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           61 |     1799 | 2024-05-21 | Rhyno         | W   | 0.720      | -            | -                | -                | -         |     7.27 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           60 |     1845 | 2024-05-20 | EYEBALLERS    | W   | 0.712      | -            | -                | -                | -         |     4.83 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           59 |     1877 | 2024-05-19 | Zero Tenacity | L   | 0.705      | -            | -                | -                | -         |   -13.06 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           58 |     1898 | 2024-05-18 | Sashi         | W   | 0.700      | 0.384        | 0.187 (0.050)    | 0.970 (0.261)    | -         |    13.62 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           57 |     1909 | 2024-05-18 | MOUZ NXT      | L   | 0.699      | -            | -                | -                | -         |   -13.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           56 |     1914 | 2024-05-18 | Rebels        | W   | 0.698      | -            | -                | -                | -         |     7.72 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           55 |     1945 | 2024-05-17 | 3DMAX         | W   | 0.692      | 0.500        | 0.505 (0.175)    | 1.000 (0.346)    | -         |    20.28 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           54 |     1972 | 2024-05-16 | DMS           | W   | 0.687      | -            | -                | -                | -         |     5.64 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           53 |     1984 | 2024-05-16 | Sampi         | W   | 0.685      | 0.384        | -                | 1.000 (0.263)    | -         |     5.83 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           52 |     2018 | 2024-05-15 | PARIVISION    | L   | 0.680      | -            | -                | -                | -         |   -11.71 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           51 |     2092 | 2024-05-14 | Verdant       | W   | 0.672      | -            | -                | -                | -         |     5.58 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           50 |     2099 | 2024-05-14 | MOUZ NXT      | W   | 0.671      | 0.384        | 0.141 (0.036)    | -                | -         |     8.73 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           49 |     2139 | 2024-05-12 | BetBoom       | W   | 0.660      | 0.435        | 0.257 (0.074)    | -                | -         |    17.65 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           48 |     2147 | 2024-05-12 | MOUZ NXT      | W   | 0.658      | 0.435        | 0.141 (0.040)    | 1.000 (0.286)    | -         |     9.44 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           47 |     2181 | 2024-05-11 | BLEED         | W   | 0.651      | -            | -                | -                | -         |    10.32 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           46 |     2217 | 2024-05-09 | KOI           | W   | 0.638      | -            | -                | -                | -         |     7.09 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           45 |     2276 | 2024-05-06 | Enterprise    | W   | 0.619      | -            | -                | -                | -         |     5.64 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           44 |     2312 | 2024-05-04 | GL Academy    | W   | 0.605      | -            | -                | -                | -         |     3.39 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           43 |     2362 | 2024-05-02 | Permitta      | W   | 0.591      | -            | -                | -                | -         |     6.87 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           42 |     2368 | 2024-05-01 | Nemiga        | L   | 0.587      | -            | -                | -                | -         |    -6.38 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           41 |     2372 | 2024-05-01 | V1dar         | W   | 0.586      | -            | -                | -                | -         |     1.05 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           40 |     2388 | 2024-05-01 | SINNERS       | W   | 0.584      | -            | -                | -                | -         |     9.18 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           39 |     2405 | 2024-04-30 | Alliance      | W   | 0.579      | -            | -                | -                | -         |     5.62 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           38 |     2410 | 2024-04-30 | Zero Tenacity | L   | 0.578      | -            | -                | -                | -         |    -8.39 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           37 |     2435 | 2024-04-28 | BLEED         | L   | 0.567      | -            | -                | -                | -         |    -8.11 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           36 |     2484 | 2024-04-26 | Alliance      | W   | 0.554      | -            | -                | -                | -         |     4.85 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           35 |     2557 | 2024-04-23 | BLEED         | L   | 0.533      | -            | -                | -                | -         |    -7.92 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           34 |     2570 | 2024-04-23 | PARIVISION    | L   | 0.531      | -            | -                | -                | -         |    -8.35 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           33 |     2572 | 2024-04-22 | Passion UA    | W   | 0.527      | 0.500        | 0.173 (0.045)    | 1.000 (0.263)    | -         |     8.08 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           32 |     2578 | 2024-04-22 | Alliance      | L   | 0.525      | -            | -                | -                | -         |   -12.25 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           31 |     2598 | 2024-04-21 | PARIVISION    | W   | 0.519      | -            | -                | -                | -         |     8.16 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           30 |     2679 | 2024-04-19 | HAVU          | W   | 0.505      | -            | -                | -                | -         |     2.10 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           29 |     2741 | 2024-04-18 | Zero Tenacity | W   | 0.498      | -            | -                | -                | -         |     8.15 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           28 |     2764 | 2024-04-17 | Zero Tenacity | L   | 0.492      | -            | -                | -                | -         |    -7.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           27 |     2805 | 2024-04-16 | AMKAL         | L   | 0.485      | -            | -                | -                | -         |    -5.72 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           26 |     2815 | 2024-04-15 | Sangal        | L   | 0.480      | -            | -                | -                | -         |    -6.31 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           25 |     2937 | 2024-04-10 | Nexus         | L   | 0.446      | -            | -                | -                | -         |   -10.67 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           24 |     2981 | 2024-04-09 | Rebels        | L   | 0.440      | -            | -                | -                | -         |    -8.26 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           23 |     3027 | 2024-04-08 | MOUZ NXT      | L   | 0.432      | -            | -                | -                | -         |    -7.23 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           22 |     3204 | 2024-04-02 | Metizport     | L   | 0.393      | -            | -                | -                | -         |    -8.95 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           21 |     3211 | 2024-04-02 | Apeks         | L   | 0.392      | -            | -                | -                | -         |    -9.06 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           20 |     3236 | 2024-03-31 | Apeks         | W   | 0.379      | -            | -                | -                | -         |     3.21 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           19 |     3249 | 2024-03-29 | Space         | L   | 0.366      | -            | -                | -                | -         |    -9.64 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           18 |     3297 | 2024-03-27 | Rebels        | W   | 0.354      | -            | -                | -                | -         |     4.06 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           17 |     3308 | 2024-03-27 | Sampi         | W   | 0.354      | -            | -                | -                | -         |     2.82 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           16 |     3344 | 2024-03-25 | FORZE         | W   | 0.340      | -            | -                | -                | -         |     3.07 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           15 |     3405 | 2024-03-21 | BetBoom       | L   | 0.312      | -            | -                | -                | -         |    -1.37 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           14 |     3442 | 2024-03-19 | ex-Sprout     | W   | 0.298      | -            | -                | -                | -         |     0.37 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           13 |     3509 | 2024-03-15 | 3DMAX         | L   | 0.273      | -            | -                | -                | -         |    -0.35 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           12 |     3608 | 2024-03-12 | Metizport     | L   | 0.254      | -            | -                | -                | -         |    -5.87 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           11 |     3615 | 2024-03-12 | ENCE          | W   | 0.253      | -            | -                | -                | -         |     7.11 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           10 |     3626 | 2024-03-11 | KOI           | W   | 0.247      | -            | -                | -                | -         |     2.33 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            9 |     3636 | 2024-03-11 | Virtus.pro    | L   | 0.246      | -            | -                | -                | -         |    -0.23 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            8 |     3701 | 2024-03-08 | PARIVISION    | L   | 0.226      | -            | -                | -                | -         |    -3.60 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            7 |     3788 | 2024-03-05 | Johnny Speeds | W   | 0.207      | -            | -                | -                | -         |     5.00 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            6 |     3795 | 2024-03-05 | Passion UA    | W   | 0.207      | -            | -                | -                | -         |     3.36 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            5 |     3806 | 2024-03-05 | UGANDA        | W   | 0.207      | -            | -                | -                | -         |     0.13 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            4 |     3936 | 2024-02-27 | DMS           | L   | 0.160      | -            | -                | -                | -         |    -3.73 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            3 |     4156 | 2024-02-18 | Aurora        | L   | 0.099      | -            | -                | -                | -         |    -0.11 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            2 |     4206 | 2024-02-16 | 500           | W   | 0.086      | -            | -                | -                | -         |     0.31 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            1 |     4212 | 2024-02-16 | PERA          | W   | 0.086      | -            | -                | -                | -         |     0.05 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($54,943.51)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.893 | $22,000.00     | $19,647.22      |
| 2024-06-09 |      0.846 | $1,500.00      | $1,269.48       |
| 2024-05-26 |      0.753 | $5,000.00      | $3,765.28       |
| 2024-05-18 |      0.700 | $10,000.00     | $7,000.00       |
| 2024-05-12 |      0.660 | $22,000.00     | $14,518.47      |
| 2024-04-24 |      0.539 | $12,500.00     | $6,743.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
