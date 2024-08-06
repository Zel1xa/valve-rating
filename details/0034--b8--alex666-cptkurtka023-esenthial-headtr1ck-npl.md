### Roster Details<br />
Team Name: B8<br />
Roster: alex666, cptkurtka023, esenthial, headtr1ck, npl<br />
Global Rank: [34](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [25]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1153.5<br />
<br />
Final Rank Value (1153.5) = Starting Rank Value (1082.8) + Head To Head Adjustments (70.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.561[<sup>1</sup>](#table2)
- Bounty Collected: 0.470[<sup>2</sup>](#table1)
- Opponent Network: 0.300[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.333<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1082.8
- 400 + ( ( 0.333 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1082.8


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
|           86 |        2 | 2024-08-05 | Permitta      | L   | 1.000      | -            | -                | -                | -         |   -24.04 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           85 |       28 | 2024-08-04 | BC.Game       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.07 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           84 |       98 | 2024-08-02 | Space         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.25 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           83 |      181 | 2024-07-31 | PERA          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.73 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           82 |      233 | 2024-07-30 | ARCRED        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.48 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           81 |      336 | 2024-07-27 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -12.82 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           80 |      384 | 2024-07-25 | SINNERS       | W   | 1.000      | 0.435        | -                | 0.808 (0.351)    | 0 (0.000) |     8.38 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           79 |      543 | 2024-07-20 | Zero Tenacity | L   | 1.000      | -            | -                | -                | -         |   -16.82 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           78 |      598 | 2024-07-19 | Rebels        | W   | 1.000      | 0.500        | -                | 0.591 (0.296)    | 0 (0.000) |     9.14 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           77 |      628 | 2024-07-18 | Aurora        | L   | 1.000      | -            | -                | -                | -         |    -5.52 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           76 |      708 | 2024-07-17 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -13.45 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           75 |      810 | 2024-07-15 | 9INE          | W   | 1.000      | 0.500        | -                | 0.533 (0.267)    | 0 (0.000) |     5.58 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           74 |     1025 | 2024-06-16 | 3DMAX         | W   | 0.864      | 0.435        | 0.509 (0.191)    | 1.000 (0.376)    | 0 (0.000) |    22.66 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           73 |     1035 | 2024-06-16 | Monte         | W   | 0.863      | 0.435        | 0.080 (0.030)    | -                | 0 (0.000) |    10.30 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           72 |     1069 | 2024-06-15 | Illuminar     | W   | 0.856      | -            | -                | -                | 0 (0.000) |     6.00 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           71 |     1149 | 2024-06-13 | MOUZ NXT      | W   | 0.842      | 0.435        | 0.139 (0.051)    | 0.986 (0.361)    | -         |    11.17 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           70 |     1169 | 2024-06-12 | BLEED         | L   | 0.837      | -            | -                | -                | -         |    -5.87 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           69 |     1266 | 2024-06-09 | AMKAL         | L   | 0.816      | -            | -                | -                | -         |   -10.68 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           68 |     1374 | 2024-06-07 | Verdant       | W   | 0.804      | -            | -                | -                | -         |     5.50 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           67 |     1375 | 2024-06-07 | PERA          | W   | 0.804      | -            | -                | -                | -         |     6.67 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           66 |     1391 | 2024-06-07 | Verdant       | L   | 0.803      | -            | -                | -                | -         |   -20.11 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           65 |     1684 | 2024-05-30 | SINNERS       | L   | 0.751      | -            | -                | -                | -         |   -14.13 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           64 |     1776 | 2024-05-26 | MOUZ NXT      | L   | 0.723      | -            | -                | -                | -         |   -14.71 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           63 |     1784 | 2024-05-25 | RUBY          | W   | 0.718      | -            | -                | -                | -         |     5.08 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           62 |     1791 | 2024-05-25 | BetBoom       | W   | 0.717      | 0.435        | 0.249 (0.077)    | -                | -         |    17.29 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           61 |     1806 | 2024-05-24 | Alliance      | W   | 0.711      | -            | -                | -                | -         |     3.62 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           60 |     1826 | 2024-05-23 | DMS           | W   | 0.703      | -            | -                | -                | -         |     5.08 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           59 |     1904 | 2024-05-21 | Rhyno         | W   | 0.691      | -            | -                | -                | -         |     6.25 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           58 |     1944 | 2024-05-20 | EYEBALLERS    | W   | 0.683      | -            | -                | -                | -         |     4.22 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           57 |     1971 | 2024-05-19 | Zero Tenacity | L   | 0.676      | -            | -                | -                | -         |   -12.85 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           56 |     1992 | 2024-05-18 | Sashi         | W   | 0.671      | 0.384        | 0.184 (0.047)    | 0.982 (0.253)    | -         |    12.53 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           55 |     2007 | 2024-05-18 | Rebels        | W   | 0.669      | -            | -                | -                | -         |     7.07 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           54 |     2038 | 2024-05-17 | 3DMAX         | W   | 0.663      | 0.500        | 0.509 (0.169)    | 1.000 (0.332)    | -         |    19.48 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           53 |     2065 | 2024-05-16 | DMS           | W   | 0.658      | -            | -                | -                | -         |     5.33 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           52 |     2077 | 2024-05-16 | Sampi         | W   | 0.656      | 0.384        | -                | 1.000 (0.252)    | -         |     5.61 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           51 |     2111 | 2024-05-15 | PARIVISION    | L   | 0.651      | -            | -                | -                | -         |   -11.23 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           50 |     2179 | 2024-05-14 | Verdant       | W   | 0.644      | -            | -                | -                | -         |     5.08 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           49 |     2185 | 2024-05-14 | MOUZ NXT      | W   | 0.642      | 0.384        | 0.139 (0.034)    | -                | -         |     8.78 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           48 |     2223 | 2024-05-12 | BetBoom       | W   | 0.631      | 0.435        | 0.249 (0.068)    | -                | -         |    16.66 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           47 |     2231 | 2024-05-12 | MOUZ NXT      | W   | 0.629      | 0.435        | 0.139 (0.038)    | 0.986 (0.270)    | -         |     9.44 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           46 |     2265 | 2024-05-11 | BLEED         | W   | 0.622      | -            | -                | -                | -         |     9.73 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           45 |     2301 | 2024-05-09 | KOI           | W   | 0.609      | -            | -                | -                | -         |     9.74 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           44 |     2358 | 2024-05-06 | Enterprise    | W   | 0.590      | -            | -                | -                | -         |     5.42 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           43 |     2394 | 2024-05-04 | GL Academy    | W   | 0.577      | -            | -                | -                | -         |     3.07 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           42 |     2443 | 2024-05-02 | Permitta      | W   | 0.562      | -            | -                | -                | -         |     6.74 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           41 |     2448 | 2024-05-01 | Nemiga        | L   | 0.558      | -            | -                | -                | -         |    -5.82 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           40 |     2452 | 2024-05-01 | V1dar         | W   | 0.557      | -            | -                | -                | -         |     0.96 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           39 |     2468 | 2024-05-01 | SINNERS       | W   | 0.556      | -            | -                | -                | -         |    10.16 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           38 |     2484 | 2024-04-30 | Alliance      | W   | 0.550      | -            | -                | -                | -         |     5.18 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           37 |     2489 | 2024-04-30 | Zero Tenacity | L   | 0.549      | -            | -                | -                | -         |    -7.84 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           36 |     2514 | 2024-04-28 | BLEED         | L   | 0.538      | -            | -                | -                | -         |    -7.76 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           35 |     2562 | 2024-04-26 | Alliance      | W   | 0.525      | -            | -                | -                | -         |     4.48 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           34 |     2634 | 2024-04-23 | BLEED         | L   | 0.504      | -            | -                | -                | -         |    -7.74 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           33 |     2648 | 2024-04-22 | Passion UA    | W   | 0.498      | 0.500        | 0.173 (0.043)    | 1.000 (0.249)    | -         |     7.85 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           32 |     2654 | 2024-04-22 | Alliance      | L   | 0.496      | -            | -                | -                | -         |   -11.52 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           31 |     2673 | 2024-04-21 | PARIVISION    | W   | 0.490      | -            | -                | -                | -         |     8.08 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           30 |     2751 | 2024-04-19 | HAVU          | W   | 0.477      | -            | -                | -                | -         |     1.97 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           29 |     2812 | 2024-04-18 | Zero Tenacity | W   | 0.469      | -            | -                | -                | -         |     7.98 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           28 |     2834 | 2024-04-17 | Zero Tenacity | L   | 0.463      | -            | -                | -                | -         |    -6.84 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           27 |     2874 | 2024-04-16 | AMKAL         | L   | 0.456      | -            | -                | -                | -         |    -5.33 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           26 |     2884 | 2024-04-15 | Sangal        | L   | 0.451      | -            | -                | -                | -         |    -5.50 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           25 |     3005 | 2024-04-10 | Nexus         | L   | 0.417      | -            | -                | -                | -         |    -9.94 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           24 |     3049 | 2024-04-09 | Rebels        | L   | 0.411      | -            | -                | -                | -         |    -7.71 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           23 |     3095 | 2024-04-08 | MOUZ NXT      | L   | 0.403      | -            | -                | -                | -         |    -6.81 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           22 |     3264 | 2024-04-02 | Metizport     | L   | 0.365      | -            | -                | -                | -         |    -8.95 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           21 |     3271 | 2024-04-02 | Apeks         | L   | 0.363      | -            | -                | -                | -         |    -8.50 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           20 |     3296 | 2024-03-31 | Apeks         | W   | 0.350      | -            | -                | -                | -         |     2.86 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           19 |     3309 | 2024-03-29 | Space         | L   | 0.338      | -            | -                | -                | -         |    -8.85 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           18 |     3356 | 2024-03-27 | Rebels        | W   | 0.325      | -            | -                | -                | -         |     3.74 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           17 |     3367 | 2024-03-27 | Sampi         | W   | 0.325      | -            | -                | -                | -         |     2.64 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           16 |     3399 | 2024-03-25 | FORZE         | W   | 0.311      | -            | -                | -                | -         |     2.77 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           15 |     3460 | 2024-03-21 | BetBoom       | L   | 0.283      | -            | -                | -                | -         |    -1.29 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           14 |     3497 | 2024-03-19 | ex-Sprout     | W   | 0.269      | -            | -                | -                | -         |     0.31 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           13 |     3564 | 2024-03-15 | 3DMAX         | L   | 0.244      | -            | -                | -                | -         |    -0.29 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           12 |     3658 | 2024-03-12 | Metizport     | L   | 0.225      | -            | -                | -                | -         |    -5.61 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           11 |     3665 | 2024-03-12 | ENCE          | W   | 0.224      | -            | -                | -                | -         |     6.33 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           10 |     3676 | 2024-03-11 | KOI           | W   | 0.218      | -            | -                | -                | -         |     3.41 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            9 |     3686 | 2024-03-11 | Virtus.pro    | L   | 0.217      | -            | -                | -                | -         |    -0.21 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            8 |     3750 | 2024-03-08 | PARIVISION    | L   | 0.198      | -            | -                | -                | -         |    -2.96 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            7 |     3837 | 2024-03-05 | Johnny Speeds | W   | 0.178      | -            | -                | -                | -         |     4.35 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            6 |     3840 | 2024-03-05 | Passion UA    | W   | 0.178      | -            | -                | -                | -         |     2.94 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            5 |     3850 | 2024-03-05 | UGANDA        | W   | 0.178      | -            | -                | -                | -         |     0.12 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            4 |     3978 | 2024-02-27 | DMS           | L   | 0.131      | -            | -                | -                | -         |    -3.02 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            3 |     4190 | 2024-02-18 | Aurora        | L   | 0.070      | -            | -                | -                | -         |    -0.07 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            2 |     4240 | 2024-02-16 | 500           | W   | 0.058      | -            | -                | -                | -         |     0.19 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            1 |     4246 | 2024-02-16 | PERA          | W   | 0.057      | -            | -                | -                | -         |     0.04 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($52,834.62)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.16) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.864 | $22,000.00     | $19,011.67      |
| 2024-06-09 |      0.817 | $1,500.00      | $1,226.15       |
| 2024-05-26 |      0.724 | $5,000.00      | $3,620.83       |
| 2024-05-18 |      0.671 | $10,000.00     | $6,711.11       |
| 2024-05-12 |      0.631 | $22,000.00     | $13,882.92      |
| 2024-04-24 |      0.511 | $12,500.00     | $6,381.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
