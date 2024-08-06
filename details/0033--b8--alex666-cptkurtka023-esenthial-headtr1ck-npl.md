### Roster Details<br />
Team Name: B8<br />
Roster: alex666, cptkurtka023, esenthial, headtr1ck, npl<br />
Global Rank: [33](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1155.1<br />
<br />
Final Rank Value (1155.1) = Starting Rank Value (1084.4) + Head To Head Adjustments (70.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.565[<sup>1</sup>](#table2)
- Bounty Collected: 0.470[<sup>2</sup>](#table1)
- Opponent Network: 0.295[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.333<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1084.4
- 400 + ( ( 0.333 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1084.4


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
|           86 |       12 | 2024-08-05 | Permitta      | L   | 1.000      | -            | -                | -                | -         |   -23.92 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           85 |       38 | 2024-08-04 | BC.Game       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.31 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           84 |      108 | 2024-08-02 | Space         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.33 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           83 |      191 | 2024-07-31 | PERA          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.70 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           82 |      243 | 2024-07-30 | ARCRED        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.46 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           81 |      346 | 2024-07-27 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -12.82 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           80 |      394 | 2024-07-25 | SINNERS       | W   | 1.000      | 0.435        | -                | 0.790 (0.343)    | 0 (0.000) |     8.38 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           79 |      553 | 2024-07-20 | Zero Tenacity | L   | 1.000      | -            | -                | -                | -         |   -16.75 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           78 |      608 | 2024-07-19 | Rebels        | W   | 1.000      | 0.500        | -                | 0.578 (0.289)    | 0 (0.000) |     9.14 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           77 |      638 | 2024-07-18 | Aurora        | L   | 1.000      | -            | -                | -                | -         |    -5.47 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           76 |      718 | 2024-07-17 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -13.44 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           75 |      820 | 2024-07-15 | 9INE          | W   | 1.000      | 0.500        | -                | 0.523 (0.261)    | 0 (0.000) |     5.58 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           74 |     1035 | 2024-06-16 | 3DMAX         | W   | 0.861      | 0.435        | 0.510 (0.191)    | 1.000 (0.374)    | 0 (0.000) |    22.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           73 |     1045 | 2024-06-16 | Monte         | W   | 0.859      | 0.435        | 0.080 (0.030)    | -                | 0 (0.000) |    10.24 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           72 |     1079 | 2024-06-15 | Illuminar     | W   | 0.853      | -            | -                | -                | 0 (0.000) |     5.99 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           71 |     1159 | 2024-06-13 | MOUZ NXT      | W   | 0.839      | 0.435        | 0.139 (0.051)    | 0.962 (0.351)    | -         |    11.13 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           70 |     1179 | 2024-06-12 | BLEED         | L   | 0.833      | -            | -                | -                | -         |    -5.87 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           69 |     1276 | 2024-06-09 | AMKAL         | L   | 0.813      | -            | -                | -                | -         |   -10.66 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           68 |     1384 | 2024-06-07 | Verdant       | W   | 0.801      | -            | -                | -                | -         |     5.50 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           67 |     1385 | 2024-06-07 | PERA          | W   | 0.801      | -            | -                | -                | -         |     6.62 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           66 |     1401 | 2024-06-07 | Verdant       | L   | 0.800      | -            | -                | -                | -         |   -20.00 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           65 |     1694 | 2024-05-30 | SINNERS       | L   | 0.747      | -            | -                | -                | -         |   -14.09 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           64 |     1786 | 2024-05-26 | MOUZ NXT      | L   | 0.719      | -            | -                | -                | -         |   -14.66 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           63 |     1794 | 2024-05-25 | RUBY          | W   | 0.715      | -            | -                | -                | -         |     5.13 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           62 |     1801 | 2024-05-25 | BetBoom       | W   | 0.714      | 0.435        | 0.248 (0.077)    | -                | -         |    17.19 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           61 |     1816 | 2024-05-24 | Alliance      | W   | 0.708      | -            | -                | -                | -         |     3.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           60 |     1836 | 2024-05-23 | DMS           | W   | 0.700      | -            | -                | -                | -         |     5.03 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           59 |     1914 | 2024-05-21 | Rhyno         | W   | 0.688      | -            | -                | -                | -         |     6.18 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           58 |     1954 | 2024-05-20 | EYEBALLERS    | W   | 0.680      | -            | -                | -                | -         |     4.27 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           57 |     1981 | 2024-05-19 | Zero Tenacity | L   | 0.673      | -            | -                | -                | -         |   -12.79 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           56 |     2002 | 2024-05-18 | Sashi         | W   | 0.668      | 0.384        | 0.184 (0.047)    | 0.958 (0.246)    | -         |    12.43 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           55 |     2017 | 2024-05-18 | Rebels        | W   | 0.666      | -            | -                | -                | -         |     7.03 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           54 |     2048 | 2024-05-17 | 3DMAX         | W   | 0.660      | 0.500        | 0.510 (0.168)    | 1.000 (0.330)    | -         |    19.40 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           53 |     2075 | 2024-05-16 | DMS           | W   | 0.655      | -            | -                | -                | -         |     5.26 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           52 |     2087 | 2024-05-16 | Sampi         | W   | 0.653      | 0.384        | -                | 1.000 (0.251)    | -         |     5.54 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           51 |     2121 | 2024-05-15 | PARIVISION    | L   | 0.648      | -            | -                | -                | -         |   -11.14 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           50 |     2189 | 2024-05-14 | Verdant       | W   | 0.640      | -            | -                | -                | -         |     5.05 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           49 |     2195 | 2024-05-14 | MOUZ NXT      | W   | 0.639      | 0.384        | 0.139 (0.034)    | -                | -         |     8.71 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           48 |     2233 | 2024-05-12 | BetBoom       | W   | 0.628      | 0.435        | 0.248 (0.068)    | -                | -         |    16.56 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           47 |     2241 | 2024-05-12 | MOUZ NXT      | W   | 0.626      | 0.435        | 0.139 (0.038)    | 0.962 (0.262)    | -         |     9.36 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           46 |     2275 | 2024-05-11 | BLEED         | W   | 0.619      | -            | -                | -                | -         |     9.61 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           45 |     2311 | 2024-05-09 | KOI           | W   | 0.606      | -            | -                | -                | -         |     9.60 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           44 |     2368 | 2024-05-06 | Enterprise    | W   | 0.587      | -            | -                | -                | -         |     5.37 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           43 |     2404 | 2024-05-04 | GL Academy    | W   | 0.573      | -            | -                | -                | -         |     3.03 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           42 |     2453 | 2024-05-02 | Permitta      | W   | 0.559      | -            | -                | -                | -         |     6.66 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           41 |     2458 | 2024-05-01 | Nemiga        | L   | 0.555      | -            | -                | -                | -         |    -5.85 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           40 |     2462 | 2024-05-01 | V1dar         | W   | 0.554      | -            | -                | -                | -         |     0.94 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           39 |     2478 | 2024-05-01 | SINNERS       | W   | 0.552      | -            | -                | -                | -         |    10.06 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           38 |     2494 | 2024-04-30 | Alliance      | W   | 0.547      | -            | -                | -                | -         |     5.12 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           37 |     2499 | 2024-04-30 | Zero Tenacity | L   | 0.546      | -            | -                | -                | -         |    -7.85 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           36 |     2524 | 2024-04-28 | BLEED         | L   | 0.535      | -            | -                | -                | -         |    -7.80 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           35 |     2572 | 2024-04-26 | Alliance      | W   | 0.522      | -            | -                | -                | -         |     4.43 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           34 |     2644 | 2024-04-23 | BLEED         | L   | 0.501      | -            | -                | -                | -         |    -7.76 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           33 |     2658 | 2024-04-22 | Passion UA    | W   | 0.495      | 0.500        | 0.173 (0.043)    | 1.000 (0.247)    | -         |     7.77 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           32 |     2664 | 2024-04-22 | Alliance      | L   | 0.493      | -            | -                | -                | -         |   -11.49 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           31 |     2683 | 2024-04-21 | PARIVISION    | W   | 0.487      | -            | -                | -                | -         |     8.04 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           30 |     2761 | 2024-04-19 | HAVU          | W   | 0.473      | -            | -                | -                | -         |     1.93 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           29 |     2822 | 2024-04-18 | Zero Tenacity | W   | 0.466      | -            | -                | -                | -         |     7.87 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           28 |     2844 | 2024-04-17 | Zero Tenacity | L   | 0.460      | -            | -                | -                | -         |    -6.86 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           27 |     2884 | 2024-04-16 | AMKAL         | L   | 0.453      | -            | -                | -                | -         |    -5.34 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           26 |     2894 | 2024-04-15 | Sangal        | L   | 0.448      | -            | -                | -                | -         |    -5.49 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           25 |     3015 | 2024-04-10 | Nexus         | L   | 0.414      | -            | -                | -                | -         |    -9.87 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           24 |     3059 | 2024-04-09 | Rebels        | L   | 0.408      | -            | -                | -                | -         |    -7.68 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           23 |     3105 | 2024-04-08 | MOUZ NXT      | L   | 0.400      | -            | -                | -                | -         |    -6.80 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           22 |     3274 | 2024-04-02 | Metizport     | L   | 0.361      | -            | -                | -                | -         |    -8.17 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           21 |     3281 | 2024-04-02 | Apeks         | L   | 0.360      | -            | -                | -                | -         |    -8.45 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           20 |     3306 | 2024-03-31 | Apeks         | W   | 0.347      | -            | -                | -                | -         |     2.81 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           19 |     3319 | 2024-03-29 | Space         | L   | 0.334      | -            | -                | -                | -         |    -8.76 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           18 |     3366 | 2024-03-27 | Rebels        | W   | 0.322      | -            | -                | -                | -         |     3.70 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           17 |     3377 | 2024-03-27 | Sampi         | W   | 0.322      | -            | -                | -                | -         |     2.59 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           16 |     3409 | 2024-03-25 | FORZE         | W   | 0.308      | -            | -                | -                | -         |     2.71 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           15 |     3470 | 2024-03-21 | BetBoom       | L   | 0.280      | -            | -                | -                | -         |    -1.29 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           14 |     3507 | 2024-03-19 | ex-Sprout     | W   | 0.266      | -            | -                | -                | -         |     0.30 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           13 |     3574 | 2024-03-15 | 3DMAX         | L   | 0.241      | -            | -                | -                | -         |    -0.29 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           12 |     3668 | 2024-03-12 | Metizport     | L   | 0.222      | -            | -                | -                | -         |    -5.09 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           11 |     3675 | 2024-03-12 | ENCE          | W   | 0.221      | -            | -                | -                | -         |     6.24 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           10 |     3686 | 2024-03-11 | KOI           | W   | 0.215      | -            | -                | -                | -         |     3.33 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            9 |     3696 | 2024-03-11 | Virtus.pro    | L   | 0.214      | -            | -                | -                | -         |    -0.21 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            8 |     3760 | 2024-03-08 | PARIVISION    | L   | 0.194      | -            | -                | -                | -         |    -2.90 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            7 |     3847 | 2024-03-05 | Johnny Speeds | W   | 0.175      | -            | -                | -                | -         |     4.28 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            6 |     3850 | 2024-03-05 | Passion UA    | W   | 0.175      | -            | -                | -                | -         |     2.88 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            5 |     3860 | 2024-03-05 | UGANDA        | W   | 0.175      | -            | -                | -                | -         |     0.12 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            4 |     3988 | 2024-02-27 | DMS           | L   | 0.128      | -            | -                | -                | -         |    -2.96 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            3 |     4200 | 2024-02-18 | Aurora        | L   | 0.067      | -            | -                | -                | -         |    -0.07 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            2 |     4250 | 2024-02-16 | 500           | W   | 0.054      | -            | -                | -                | -         |     0.18 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            1 |     4256 | 2024-02-16 | PERA          | W   | 0.054      | -            | -                | -                | -         |     0.04 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($54,604.80)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.861 | $22,000.00     | $18,942.41      |
| 2024-06-09 |      0.814 | $1,500.00      | $1,221.42       |
| 2024-05-26 |      0.721 | $5,000.00      | $3,605.09       |
| 2024-05-18 |      0.668 | $10,000.00     | $6,679.63       |
| 2024-05-12 |      0.628 | $22,000.00     | $13,813.66      |
| 2024-04-24 |      0.507 | $12,500.00     | $6,342.59       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
