### Roster Details<br />
Team Name: B8<br />
Roster: alex666, cptkurtka023, esenthial, headtr1ck, npl<br />
Global Rank: [35](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [26]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1168.9<br />
<br />
Final Rank Value (1168.9) = Starting Rank Value (1083.3) + Head To Head Adjustments (85.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.561[<sup>1</sup>](#table2)
- Bounty Collected: 0.472[<sup>2</sup>](#table1)
- Opponent Network: 0.304[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.334<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1083.3
- 400 + ( ( 0.334 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1083.3


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
|           84 |       69 | 2024-08-02 | Space         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.21 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           83 |      152 | 2024-07-31 | PERA          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.80 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           82 |      204 | 2024-07-30 | ARCRED        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.59 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           81 |      307 | 2024-07-27 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -12.90 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           80 |      355 | 2024-07-25 | SINNERS       | W   | 1.000      | 0.435        | -                | 0.797 (0.346)    | 0 (0.000) |     8.24 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           79 |      514 | 2024-07-20 | Zero Tenacity | L   | 1.000      | -            | -                | -                | -         |   -16.87 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           78 |      569 | 2024-07-19 | Rebels        | W   | 1.000      | 0.500        | -                | 0.599 (0.300)    | 0 (0.000) |     9.16 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           77 |      599 | 2024-07-18 | Aurora        | L   | 1.000      | -            | -                | -                | -         |    -5.66 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           76 |      679 | 2024-07-17 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -13.57 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           75 |      781 | 2024-07-15 | 9INE          | W   | 1.000      | 0.500        | -                | 0.537 (0.269)    | 0 (0.000) |     5.54 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           74 |      996 | 2024-06-16 | 3DMAX         | W   | 0.874      | 0.435        | 0.506 (0.192)    | 1.000 (0.380)    | 0 (0.000) |    22.77 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           73 |     1006 | 2024-06-16 | Monte         | W   | 0.872      | 0.435        | 0.080 (0.030)    | -                | 0 (0.000) |    10.39 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           72 |     1040 | 2024-06-15 | Illuminar     | W   | 0.865      | -            | -                | -                | 0 (0.000) |     6.02 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           71 |     1120 | 2024-06-13 | MOUZ NXT      | W   | 0.851      | 0.435        | 0.139 (0.051)    | 1.000 (0.370)    | 0 (0.000) |    11.17 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           70 |     1140 | 2024-06-12 | BLEED         | L   | 0.846      | -            | -                | -                | -         |    -6.02 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           69 |     1237 | 2024-06-09 | AMKAL         | L   | 0.826      | -            | -                | -                | -         |   -10.76 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           68 |     1345 | 2024-06-07 | Verdant       | W   | 0.814      | -            | -                | -                | -         |     5.51 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           67 |     1346 | 2024-06-07 | PERA          | W   | 0.813      | -            | -                | -                | -         |     6.76 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           66 |     1362 | 2024-06-07 | Verdant       | L   | 0.812      | -            | -                | -                | -         |   -20.39 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           65 |     1655 | 2024-05-30 | SINNERS       | L   | 0.760      | -            | -                | -                | -         |   -14.45 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           64 |     1747 | 2024-05-26 | MOUZ NXT      | L   | 0.732      | -            | -                | -                | -         |   -15.04 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           63 |     1755 | 2024-05-25 | RUBY          | W   | 0.728      | -            | -                | -                | -         |     5.11 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           62 |     1762 | 2024-05-25 | BetBoom       | W   | 0.727      | 0.435        | 0.251 (0.079)    | -                | -         |    17.55 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           61 |     1777 | 2024-05-24 | Alliance      | W   | 0.720      | -            | -                | -                | -         |     3.66 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           60 |     1797 | 2024-05-23 | DMS           | W   | 0.712      | -            | -                | -                | -         |     5.08 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           59 |     1875 | 2024-05-21 | Rhyno         | W   | 0.701      | -            | -                | -                | -         |     6.35 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           58 |     1915 | 2024-05-20 | EYEBALLERS    | W   | 0.693      | -            | -                | -                | -         |     4.26 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           57 |     1942 | 2024-05-19 | Zero Tenacity | L   | 0.686      | -            | -                | -                | -         |   -13.07 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           56 |     1963 | 2024-05-18 | Sashi         | W   | 0.680      | 0.384        | 0.184 (0.048)    | 0.962 (0.252)    | -         |    12.70 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           55 |     1978 | 2024-05-18 | Rebels        | W   | 0.679      | -            | -                | -                | -         |     7.20 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           54 |     2009 | 2024-05-17 | 3DMAX         | W   | 0.672      | 0.500        | 0.506 (0.170)    | 1.000 (0.336)    | -         |    19.71 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           53 |     2036 | 2024-05-16 | DMS           | W   | 0.667      | -            | -                | -                | -         |     5.33 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           52 |     2048 | 2024-05-16 | Sampi         | W   | 0.665      | 0.384        | -                | 1.000 (0.256)    | -         |     5.70 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           51 |     2082 | 2024-05-15 | PARIVISION    | L   | 0.661      | -            | -                | -                | -         |   -11.54 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           50 |     2150 | 2024-05-14 | Verdant       | W   | 0.653      | -            | -                | -                | -         |     5.12 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           49 |     2156 | 2024-05-14 | MOUZ NXT      | W   | 0.652      | 0.384        | 0.139 (0.035)    | -                | -         |     8.85 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           48 |     2194 | 2024-05-12 | BetBoom       | W   | 0.640      | 0.435        | 0.251 (0.070)    | -                | -         |    16.95 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           47 |     2202 | 2024-05-12 | MOUZ NXT      | W   | 0.639      | 0.435        | 0.139 (0.039)    | 1.000 (0.277)    | -         |     9.54 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           46 |     2236 | 2024-05-11 | BLEED         | W   | 0.632      | -            | -                | -                | -         |     9.93 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           45 |     2272 | 2024-05-09 | KOI           | W   | 0.618      | -            | -                | -                | -         |     9.97 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           44 |     2329 | 2024-05-06 | Enterprise    | W   | 0.599      | -            | -                | -                | -         |     5.50 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           43 |     2365 | 2024-05-04 | GL Academy    | W   | 0.586      | -            | -                | -                | -         |     3.15 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           42 |     2414 | 2024-05-02 | Permitta      | W   | 0.572      | -            | -                | -                | -         |     6.64 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           41 |     2419 | 2024-05-01 | Nemiga        | L   | 0.567      | -            | -                | -                | -         |    -5.88 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           40 |     2423 | 2024-05-01 | V1dar         | W   | 0.567      | -            | -                | -                | -         |     0.98 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           39 |     2439 | 2024-05-01 | SINNERS       | W   | 0.565      | -            | -                | -                | -         |    10.20 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           38 |     2455 | 2024-04-30 | Alliance      | W   | 0.559      | -            | -                | -                | -         |     5.30 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           37 |     2460 | 2024-04-30 | Zero Tenacity | L   | 0.558      | -            | -                | -                | -         |    -8.05 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           36 |     2485 | 2024-04-28 | BLEED         | L   | 0.547      | -            | -                | -                | -         |    -7.82 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           35 |     2533 | 2024-04-26 | Alliance      | W   | 0.534      | -            | -                | -                | -         |     4.58 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           34 |     2605 | 2024-04-23 | BLEED         | L   | 0.513      | -            | -                | -                | -         |    -7.80 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           33 |     2619 | 2024-04-22 | Passion UA    | W   | 0.507      | 0.500        | 0.172 (0.044)    | 1.000 (0.254)    | -         |     7.88 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           32 |     2625 | 2024-04-22 | Alliance      | L   | 0.506      | -            | -                | -                | -         |   -11.72 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           31 |     2644 | 2024-04-21 | PARIVISION    | W   | 0.499      | -            | -                | -                | -         |     8.11 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           30 |     2722 | 2024-04-19 | HAVU          | W   | 0.486      | -            | -                | -                | -         |     2.02 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           29 |     2783 | 2024-04-18 | Zero Tenacity | W   | 0.478      | -            | -                | -                | -         |     8.05 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           28 |     2805 | 2024-04-17 | Zero Tenacity | L   | 0.472      | -            | -                | -                | -         |    -7.07 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           27 |     2845 | 2024-04-16 | AMKAL         | L   | 0.465      | -            | -                | -                | -         |    -5.43 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           26 |     2855 | 2024-04-15 | Sangal        | L   | 0.461      | -            | -                | -                | -         |    -5.69 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           25 |     2976 | 2024-04-10 | Nexus         | L   | 0.426      | -            | -                | -                | -         |   -10.16 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           24 |     3020 | 2024-04-09 | Rebels        | L   | 0.421      | -            | -                | -                | -         |    -7.87 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           23 |     3066 | 2024-04-08 | MOUZ NXT      | L   | 0.412      | -            | -                | -                | -         |    -7.04 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           22 |     3235 | 2024-04-02 | Metizport     | L   | 0.374      | -            | -                | -                | -         |    -9.16 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           21 |     3242 | 2024-04-02 | Apeks         | L   | 0.373      | -            | -                | -                | -         |    -8.68 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           20 |     3267 | 2024-03-31 | Apeks         | W   | 0.359      | -            | -                | -                | -         |     2.97 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           19 |     3280 | 2024-03-29 | Space         | L   | 0.347      | -            | -                | -                | -         |    -9.10 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           18 |     3327 | 2024-03-27 | Rebels        | W   | 0.334      | -            | -                | -                | -         |     3.85 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           17 |     3338 | 2024-03-27 | Sampi         | W   | 0.334      | -            | -                | -                | -         |     2.72 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           16 |     3370 | 2024-03-25 | FORZE         | W   | 0.320      | -            | -                | -                | -         |     2.87 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           15 |     3431 | 2024-03-21 | BetBoom       | L   | 0.292      | -            | -                | -                | -         |    -1.31 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           14 |     3468 | 2024-03-19 | ex-Sprout     | W   | 0.279      | -            | -                | -                | -         |     0.33 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           13 |     3535 | 2024-03-15 | 3DMAX         | L   | 0.253      | -            | -                | -                | -         |    -0.31 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           12 |     3629 | 2024-03-12 | Metizport     | L   | 0.234      | -            | -                | -                | -         |    -5.83 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           11 |     3636 | 2024-03-12 | ENCE          | W   | 0.233      | -            | -                | -                | -         |     6.55 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           10 |     3647 | 2024-03-11 | KOI           | W   | 0.228      | -            | -                | -                | -         |     3.58 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            9 |     3657 | 2024-03-11 | Virtus.pro    | L   | 0.226      | -            | -                | -                | -         |    -0.21 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            8 |     3721 | 2024-03-08 | PARIVISION    | L   | 0.207      | -            | -                | -                | -         |    -3.16 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            7 |     3808 | 2024-03-05 | Johnny Speeds | W   | 0.188      | -            | -                | -                | -         |     4.57 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            6 |     3811 | 2024-03-05 | Passion UA    | W   | 0.187      | -            | -                | -                | -         |     3.06 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            5 |     3821 | 2024-03-05 | UGANDA        | W   | 0.187      | -            | -                | -                | -         |     0.13 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            4 |     3949 | 2024-02-27 | DMS           | L   | 0.140      | -            | -                | -                | -         |    -3.24 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            3 |     4161 | 2024-02-18 | Aurora        | L   | 0.079      | -            | -                | -                | -         |    -0.09 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            2 |     4211 | 2024-02-16 | 500           | W   | 0.067      | -            | -                | -                | -         |     0.22 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            1 |     4217 | 2024-02-16 | PERA          | W   | 0.066      | -            | -                | -                | -         |     0.04 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($53,517.30)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.874 | $22,000.00     | $19,217.41      |
| 2024-06-09 |      0.827 | $1,500.00      | $1,240.17       |
| 2024-05-26 |      0.734 | $5,000.00      | $3,667.59       |
| 2024-05-18 |      0.680 | $10,000.00     | $6,804.63       |
| 2024-05-12 |      0.640 | $22,000.00     | $14,088.66      |
| 2024-04-24 |      0.520 | $12,500.00     | $6,498.84       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
