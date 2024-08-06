### Roster Details<br />
Team Name: B8<br />
Roster: alex666, cptkurtka023, esenthial, headtr1ck, npl<br />
Global Rank: [33](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1154.7<br />
<br />
Final Rank Value (1154.7) = Starting Rank Value (1082.4) + Head To Head Adjustments (72.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.560[<sup>1</sup>](#table2)
- Bounty Collected: 0.470[<sup>2</sup>](#table1)
- Opponent Network: 0.300[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.333<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1082.4
- 400 + ( ( 0.333 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1082.4


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
|           86 |        6 | 2024-08-05 | Permitta      | L   | 1.000      | -            | -                | -                | -         |   -23.91 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           85 |       32 | 2024-08-04 | BC.Game       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.32 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           84 |      102 | 2024-08-02 | Space         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.34 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           83 |      185 | 2024-07-31 | PERA          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.71 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           82 |      237 | 2024-07-30 | ARCRED        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.48 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           81 |      340 | 2024-07-27 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -12.80 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           80 |      388 | 2024-07-25 | SINNERS       | W   | 1.000      | 0.435        | -                | 0.808 (0.351)    | 0 (0.000) |     8.40 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           79 |      547 | 2024-07-20 | Zero Tenacity | L   | 1.000      | -            | -                | -                | -         |   -16.74 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           78 |      602 | 2024-07-19 | Rebels        | W   | 1.000      | 0.500        | -                | 0.591 (0.295)    | 0 (0.000) |     9.15 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           77 |      632 | 2024-07-18 | Aurora        | L   | 1.000      | -            | -                | -                | -         |    -5.50 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           76 |      712 | 2024-07-17 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -13.43 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           75 |      814 | 2024-07-15 | 9INE          | W   | 1.000      | 0.500        | -                | 0.534 (0.267)    | 0 (0.000) |     5.57 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           74 |     1029 | 2024-06-16 | 3DMAX         | W   | 0.862      | 0.435        | 0.509 (0.191)    | 1.000 (0.374)    | 0 (0.000) |    22.62 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           73 |     1039 | 2024-06-16 | Monte         | W   | 0.860      | 0.435        | 0.080 (0.030)    | -                | 0 (0.000) |    10.29 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           72 |     1073 | 2024-06-15 | Illuminar     | W   | 0.854      | -            | -                | -                | 0 (0.000) |     5.97 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           71 |     1153 | 2024-06-13 | MOUZ NXT      | W   | 0.839      | 0.435        | 0.139 (0.051)    | 0.984 (0.359)    | -         |    11.14 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           70 |     1173 | 2024-06-12 | BLEED         | L   | 0.834      | -            | -                | -                | -         |    -5.86 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           69 |     1270 | 2024-06-09 | AMKAL         | L   | 0.814      | -            | -                | -                | -         |   -10.62 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           68 |     1378 | 2024-06-07 | Verdant       | W   | 0.802      | -            | -                | -                | -         |     5.48 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           67 |     1379 | 2024-06-07 | PERA          | W   | 0.802      | -            | -                | -                | -         |     6.64 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           66 |     1395 | 2024-06-07 | Verdant       | L   | 0.801      | -            | -                | -                | -         |   -20.05 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           65 |     1688 | 2024-05-30 | SINNERS       | L   | 0.748      | -            | -                | -                | -         |   -14.09 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           64 |     1780 | 2024-05-26 | MOUZ NXT      | L   | 0.720      | -            | -                | -                | -         |   -14.66 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           63 |     1788 | 2024-05-25 | RUBY          | W   | 0.716      | -            | -                | -                | -         |     5.15 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           62 |     1795 | 2024-05-25 | BetBoom       | W   | 0.715      | 0.435        | 0.248 (0.077)    | -                | -         |    17.23 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           61 |     1810 | 2024-05-24 | Alliance      | W   | 0.709      | -            | -                | -                | -         |     3.61 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           60 |     1830 | 2024-05-23 | DMS           | W   | 0.701      | -            | -                | -                | -         |     5.06 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           59 |     1908 | 2024-05-21 | Rhyno         | W   | 0.689      | -            | -                | -                | -         |     6.21 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           58 |     1948 | 2024-05-20 | EYEBALLERS    | W   | 0.681      | -            | -                | -                | -         |     4.29 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           57 |     1975 | 2024-05-19 | Zero Tenacity | L   | 0.674      | -            | -                | -                | -         |   -12.78 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           56 |     1996 | 2024-05-18 | Sashi         | W   | 0.669      | 0.384        | 0.184 (0.047)    | 0.980 (0.252)    | -         |    12.47 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           55 |     2011 | 2024-05-18 | Rebels        | W   | 0.667      | -            | -                | -                | -         |     7.05 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           54 |     2042 | 2024-05-17 | 3DMAX         | W   | 0.661      | 0.500        | 0.509 (0.168)    | 1.000 (0.330)    | -         |    19.42 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           53 |     2069 | 2024-05-16 | DMS           | W   | 0.655      | -            | -                | -                | -         |     5.29 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           52 |     2081 | 2024-05-16 | Sampi         | W   | 0.653      | 0.384        | -                | 1.000 (0.251)    | -         |     5.58 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           51 |     2115 | 2024-05-15 | PARIVISION    | L   | 0.649      | -            | -                | -                | -         |   -11.16 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           50 |     2183 | 2024-05-14 | Verdant       | W   | 0.641      | -            | -                | -                | -         |     5.05 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           49 |     2189 | 2024-05-14 | MOUZ NXT      | W   | 0.640      | 0.384        | 0.139 (0.034)    | -                | -         |     8.74 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           48 |     2227 | 2024-05-12 | BetBoom       | W   | 0.629      | 0.435        | 0.248 (0.068)    | -                | -         |    16.59 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           47 |     2235 | 2024-05-12 | MOUZ NXT      | W   | 0.627      | 0.435        | 0.139 (0.038)    | 0.984 (0.268)    | -         |     9.40 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           46 |     2269 | 2024-05-11 | BLEED         | W   | 0.620      | -            | -                | -                | -         |     9.66 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           45 |     2305 | 2024-05-09 | KOI           | W   | 0.606      | -            | -                | -                | -         |     9.65 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           44 |     2362 | 2024-05-06 | Enterprise    | W   | 0.588      | -            | -                | -                | -         |     5.41 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           43 |     2398 | 2024-05-04 | GL Academy    | W   | 0.574      | -            | -                | -                | -         |     3.05 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           42 |     2447 | 2024-05-02 | Permitta      | W   | 0.560      | -            | -                | -                | -         |     6.70 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           41 |     2452 | 2024-05-01 | Nemiga        | L   | 0.556      | -            | -                | -                | -         |    -5.83 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           40 |     2456 | 2024-05-01 | V1dar         | W   | 0.555      | -            | -                | -                | -         |     0.95 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           39 |     2472 | 2024-05-01 | SINNERS       | W   | 0.553      | -            | -                | -                | -         |    10.10 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           38 |     2488 | 2024-04-30 | Alliance      | W   | 0.547      | -            | -                | -                | -         |     5.15 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           37 |     2493 | 2024-04-30 | Zero Tenacity | L   | 0.546      | -            | -                | -                | -         |    -7.82 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           36 |     2518 | 2024-04-28 | BLEED         | L   | 0.536      | -            | -                | -                | -         |    -7.76 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           35 |     2566 | 2024-04-26 | Alliance      | W   | 0.522      | -            | -                | -                | -         |     4.46 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           34 |     2638 | 2024-04-23 | BLEED         | L   | 0.501      | -            | -                | -                | -         |    -7.73 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           33 |     2652 | 2024-04-22 | Passion UA    | W   | 0.496      | 0.500        | 0.173 (0.043)    | 1.000 (0.248)    | -         |     7.82 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           32 |     2658 | 2024-04-22 | Alliance      | L   | 0.494      | -            | -                | -                | -         |   -11.49 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           31 |     2677 | 2024-04-21 | PARIVISION    | W   | 0.487      | -            | -                | -                | -         |     8.05 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           30 |     2755 | 2024-04-19 | HAVU          | W   | 0.474      | -            | -                | -                | -         |     1.95 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           29 |     2816 | 2024-04-18 | Zero Tenacity | W   | 0.466      | -            | -                | -                | -         |     7.92 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           28 |     2838 | 2024-04-17 | Zero Tenacity | L   | 0.461      | -            | -                | -                | -         |    -6.82 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           27 |     2878 | 2024-04-16 | AMKAL         | L   | 0.453      | -            | -                | -                | -         |    -5.30 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           26 |     2888 | 2024-04-15 | Sangal        | L   | 0.449      | -            | -                | -                | -         |    -5.47 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           25 |     3009 | 2024-04-10 | Nexus         | L   | 0.414      | -            | -                | -                | -         |    -9.86 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           24 |     3053 | 2024-04-09 | Rebels        | L   | 0.409      | -            | -                | -                | -         |    -7.67 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           23 |     3099 | 2024-04-08 | MOUZ NXT      | L   | 0.401      | -            | -                | -                | -         |    -6.77 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           22 |     3268 | 2024-04-02 | Metizport     | L   | 0.362      | -            | -                | -                | -         |    -8.16 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           21 |     3275 | 2024-04-02 | Apeks         | L   | 0.361      | -            | -                | -                | -         |    -8.45 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           20 |     3300 | 2024-03-31 | Apeks         | W   | 0.347      | -            | -                | -                | -         |     2.83 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           19 |     3313 | 2024-03-29 | Space         | L   | 0.335      | -            | -                | -                | -         |    -8.75 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           18 |     3360 | 2024-03-27 | Rebels        | W   | 0.323      | -            | -                | -                | -         |     3.72 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           17 |     3371 | 2024-03-27 | Sampi         | W   | 0.322      | -            | -                | -                | -         |     2.62 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           16 |     3403 | 2024-03-25 | FORZE         | W   | 0.308      | -            | -                | -                | -         |     2.73 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           15 |     3464 | 2024-03-21 | BetBoom       | L   | 0.280      | -            | -                | -                | -         |    -1.28 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           14 |     3501 | 2024-03-19 | ex-Sprout     | W   | 0.267      | -            | -                | -                | -         |     0.30 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           13 |     3568 | 2024-03-15 | 3DMAX         | L   | 0.242      | -            | -                | -                | -         |    -0.29 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           12 |     3662 | 2024-03-12 | Metizport     | L   | 0.222      | -            | -                | -                | -         |    -5.08 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           11 |     3669 | 2024-03-12 | ENCE          | W   | 0.221      | -            | -                | -                | -         |     6.26 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           10 |     3680 | 2024-03-11 | KOI           | W   | 0.216      | -            | -                | -                | -         |     3.36 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            9 |     3690 | 2024-03-11 | Virtus.pro    | L   | 0.215      | -            | -                | -                | -         |    -0.21 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            8 |     3754 | 2024-03-08 | PARIVISION    | L   | 0.195      | -            | -                | -                | -         |    -2.90 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            7 |     3841 | 2024-03-05 | Johnny Speeds | W   | 0.176      | -            | -                | -                | -         |     4.30 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            6 |     3844 | 2024-03-05 | Passion UA    | W   | 0.176      | -            | -                | -                | -         |     2.91 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            5 |     3854 | 2024-03-05 | UGANDA        | W   | 0.175      | -            | -                | -                | -         |     0.12 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            4 |     3982 | 2024-02-27 | DMS           | L   | 0.129      | -            | -                | -                | -         |    -2.97 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            3 |     4194 | 2024-02-18 | Aurora        | L   | 0.068      | -            | -                | -                | -         |    -0.07 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            2 |     4244 | 2024-02-16 | 500           | W   | 0.055      | -            | -                | -                | -         |     0.18 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            1 |     4250 | 2024-02-16 | PERA          | W   | 0.054      | -            | -                | -                | -         |     0.04 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($52,652.12)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.16) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.862 | $22,000.00     | $18,956.67      |
| 2024-06-09 |      0.815 | $1,500.00      | $1,222.40       |
| 2024-05-26 |      0.722 | $5,000.00      | $3,608.33       |
| 2024-05-18 |      0.669 | $10,000.00     | $6,686.11       |
| 2024-05-12 |      0.629 | $22,000.00     | $13,827.92      |
| 2024-04-24 |      0.508 | $12,500.00     | $6,350.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
