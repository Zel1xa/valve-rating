### Roster Details<br />
Team Name: B8<br />
Roster: alex666, cptkurtka023, esenthial, headtr1ck, npl<br />
Global Rank: [34](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [25]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1153.8<br />
<br />
Final Rank Value (1153.8) = Starting Rank Value (1083.1) + Head To Head Adjustments (70.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.561[<sup>1</sup>](#table2)
- Bounty Collected: 0.471[<sup>2</sup>](#table1)
- Opponent Network: 0.301[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.333<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1083.1
- 400 + ( ( 0.333 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1083.1


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
|           86 |        0 | 2024-08-05 | Permitta      | L   | 1.000      | -            | -                | -                | -         |   -24.04 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           85 |       26 | 2024-08-04 | BC.Game       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.06 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           84 |       96 | 2024-08-02 | Space         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.25 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           83 |      179 | 2024-07-31 | PERA          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.72 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           82 |      231 | 2024-07-30 | ARCRED        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.48 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           81 |      334 | 2024-07-27 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -12.82 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           80 |      382 | 2024-07-25 | SINNERS       | W   | 1.000      | 0.435        | -                | 0.809 (0.351)    | 0 (0.000) |     8.37 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           79 |      541 | 2024-07-20 | Zero Tenacity | L   | 1.000      | -            | -                | -                | -         |   -16.82 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           78 |      596 | 2024-07-19 | Rebels        | W   | 1.000      | 0.500        | -                | 0.591 (0.296)    | 0 (0.000) |     9.14 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           77 |      626 | 2024-07-18 | Aurora        | L   | 1.000      | -            | -                | -                | -         |    -5.54 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           76 |      706 | 2024-07-17 | Sangal        | L   | 1.000      | -            | -                | -                | -         |   -13.46 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           75 |      808 | 2024-07-15 | 9INE          | W   | 1.000      | 0.500        | -                | 0.533 (0.266)    | 0 (0.000) |     5.57 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           74 |     1023 | 2024-06-16 | 3DMAX         | W   | 0.866      | 0.435        | 0.508 (0.191)    | 1.000 (0.376)    | 0 (0.000) |    22.68 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           73 |     1033 | 2024-06-16 | Monte         | W   | 0.864      | 0.435        | 0.080 (0.030)    | -                | 0 (0.000) |    10.32 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           72 |     1067 | 2024-06-15 | Illuminar     | W   | 0.858      | -            | -                | -                | 0 (0.000) |     6.01 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           71 |     1147 | 2024-06-13 | MOUZ NXT      | W   | 0.844      | 0.435        | 0.139 (0.051)    | 0.987 (0.362)    | -         |    11.19 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           70 |     1167 | 2024-06-12 | BLEED         | L   | 0.838      | -            | -                | -                | -         |    -5.89 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           69 |     1264 | 2024-06-09 | AMKAL         | L   | 0.818      | -            | -                | -                | -         |   -10.70 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           68 |     1372 | 2024-06-07 | Verdant       | W   | 0.806      | -            | -                | -                | -         |     5.50 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           67 |     1373 | 2024-06-07 | PERA          | W   | 0.806      | -            | -                | -                | -         |     6.68 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           66 |     1389 | 2024-06-07 | Verdant       | L   | 0.805      | -            | -                | -                | -         |   -20.16 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           65 |     1682 | 2024-05-30 | SINNERS       | L   | 0.752      | -            | -                | -                | -         |   -14.17 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           64 |     1774 | 2024-05-26 | MOUZ NXT      | L   | 0.724      | -            | -                | -                | -         |   -14.75 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           63 |     1782 | 2024-05-25 | RUBY          | W   | 0.720      | -            | -                | -                | -         |     5.08 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           62 |     1789 | 2024-05-25 | BetBoom       | W   | 0.719      | 0.435        | 0.249 (0.078)    | -                | -         |    17.34 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           61 |     1804 | 2024-05-24 | Alliance      | W   | 0.713      | -            | -                | -                | -         |     3.63 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           60 |     1824 | 2024-05-23 | DMS           | W   | 0.705      | -            | -                | -                | -         |     5.09 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           59 |     1902 | 2024-05-21 | Rhyno         | W   | 0.693      | -            | -                | -                | -         |     6.26 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           58 |     1942 | 2024-05-20 | EYEBALLERS    | W   | 0.685      | -            | -                | -                | -         |     4.23 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           57 |     1969 | 2024-05-19 | Zero Tenacity | L   | 0.678      | -            | -                | -                | -         |   -12.90 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           56 |     1990 | 2024-05-18 | Sashi         | W   | 0.673      | 0.384        | 0.184 (0.048)    | 0.983 (0.254)    | -         |    12.56 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           55 |     2005 | 2024-05-18 | Rebels        | W   | 0.671      | -            | -                | -                | -         |     7.09 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           54 |     2036 | 2024-05-17 | 3DMAX         | W   | 0.665      | 0.500        | 0.508 (0.169)    | 1.000 (0.332)    | -         |    19.53 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           53 |     2063 | 2024-05-16 | DMS           | W   | 0.660      | -            | -                | -                | -         |     5.34 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           52 |     2075 | 2024-05-16 | Sampi         | W   | 0.658      | 0.384        | -                | 1.000 (0.253)    | -         |     5.62 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           51 |     2109 | 2024-05-15 | PARIVISION    | L   | 0.653      | -            | -                | -                | -         |   -11.27 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           50 |     2177 | 2024-05-14 | Verdant       | W   | 0.645      | -            | -                | -                | -         |     5.08 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           49 |     2183 | 2024-05-14 | MOUZ NXT      | W   | 0.644      | 0.384        | 0.139 (0.034)    | -                | -         |     8.80 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           48 |     2221 | 2024-05-12 | BetBoom       | W   | 0.633      | 0.435        | 0.249 (0.068)    | -                | -         |    16.72 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           47 |     2229 | 2024-05-12 | MOUZ NXT      | W   | 0.631      | 0.435        | 0.139 (0.038)    | 0.987 (0.271)    | -         |     9.47 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           46 |     2263 | 2024-05-11 | BLEED         | W   | 0.624      | -            | -                | -                | -         |     9.77 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           45 |     2299 | 2024-05-09 | KOI           | W   | 0.611      | -            | -                | -                | -         |     9.78 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           44 |     2356 | 2024-05-06 | Enterprise    | W   | 0.592      | -            | -                | -                | -         |     5.44 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           43 |     2392 | 2024-05-04 | GL Academy    | W   | 0.578      | -            | -                | -                | -         |     3.08 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           42 |     2441 | 2024-05-02 | Permitta      | W   | 0.564      | -            | -                | -                | -         |     6.76 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           41 |     2446 | 2024-05-01 | Nemiga        | L   | 0.560      | -            | -                | -                | -         |    -5.83 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           40 |     2450 | 2024-05-01 | V1dar         | W   | 0.559      | -            | -                | -                | -         |     0.96 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           39 |     2466 | 2024-05-01 | SINNERS       | W   | 0.557      | -            | -                | -                | -         |    10.19 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           38 |     2482 | 2024-04-30 | Alliance      | W   | 0.552      | -            | -                | -                | -         |     5.20 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           37 |     2487 | 2024-04-30 | Zero Tenacity | L   | 0.551      | -            | -                | -                | -         |    -7.87 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           36 |     2512 | 2024-04-28 | BLEED         | L   | 0.540      | -            | -                | -                | -         |    -7.77 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           35 |     2560 | 2024-04-26 | Alliance      | W   | 0.527      | -            | -                | -                | -         |     4.50 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           34 |     2632 | 2024-04-23 | BLEED         | L   | 0.506      | -            | -                | -                | -         |    -7.75 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           33 |     2646 | 2024-04-22 | Passion UA    | W   | 0.500      | 0.500        | 0.173 (0.043)    | 1.000 (0.250)    | -         |     7.87 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           32 |     2652 | 2024-04-22 | Alliance      | L   | 0.498      | -            | -                | -                | -         |   -11.56 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           31 |     2671 | 2024-04-21 | PARIVISION    | W   | 0.492      | -            | -                | -                | -         |     8.10 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           30 |     2749 | 2024-04-19 | HAVU          | W   | 0.478      | -            | -                | -                | -         |     1.98 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           29 |     2810 | 2024-04-18 | Zero Tenacity | W   | 0.471      | -            | -                | -                | -         |     8.01 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           28 |     2832 | 2024-04-17 | Zero Tenacity | L   | 0.465      | -            | -                | -                | -         |    -6.87 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           27 |     2872 | 2024-04-16 | AMKAL         | L   | 0.458      | -            | -                | -                | -         |    -5.35 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           26 |     2882 | 2024-04-15 | Sangal        | L   | 0.453      | -            | -                | -                | -         |    -5.53 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           25 |     3003 | 2024-04-10 | Nexus         | L   | 0.418      | -            | -                | -                | -         |    -9.98 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           24 |     3047 | 2024-04-09 | Rebels        | L   | 0.413      | -            | -                | -                | -         |    -7.74 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           23 |     3093 | 2024-04-08 | MOUZ NXT      | L   | 0.405      | -            | -                | -                | -         |    -6.84 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           22 |     3262 | 2024-04-02 | Metizport     | L   | 0.366      | -            | -                | -                | -         |    -8.99 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           21 |     3269 | 2024-04-02 | Apeks         | L   | 0.365      | -            | -                | -                | -         |    -8.54 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           20 |     3294 | 2024-03-31 | Apeks         | W   | 0.352      | -            | -                | -                | -         |     2.88 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           19 |     3307 | 2024-03-29 | Space         | L   | 0.339      | -            | -                | -                | -         |    -8.89 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           18 |     3354 | 2024-03-27 | Rebels        | W   | 0.327      | -            | -                | -                | -         |     3.76 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           17 |     3365 | 2024-03-27 | Sampi         | W   | 0.327      | -            | -                | -                | -         |     2.65 | baz, cptkurtka023, esenthial, npl, OWNER         |
|           16 |     3397 | 2024-03-25 | FORZE         | W   | 0.313      | -            | -                | -                | -         |     2.79 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           15 |     3458 | 2024-03-21 | BetBoom       | L   | 0.285      | -            | -                | -                | -         |    -1.29 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           14 |     3495 | 2024-03-19 | ex-Sprout     | W   | 0.271      | -            | -                | -                | -         |     0.32 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           13 |     3562 | 2024-03-15 | 3DMAX         | L   | 0.246      | -            | -                | -                | -         |    -0.30 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           12 |     3656 | 2024-03-12 | Metizport     | L   | 0.227      | -            | -                | -                | -         |    -5.65 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           11 |     3663 | 2024-03-12 | ENCE          | W   | 0.226      | -            | -                | -                | -         |     6.38 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           10 |     3674 | 2024-03-11 | KOI           | W   | 0.220      | -            | -                | -                | -         |     3.44 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            9 |     3684 | 2024-03-11 | Virtus.pro    | L   | 0.219      | -            | -                | -                | -         |    -0.21 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            8 |     3748 | 2024-03-08 | PARIVISION    | L   | 0.199      | -            | -                | -                | -         |    -2.98 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            7 |     3835 | 2024-03-05 | Johnny Speeds | W   | 0.180      | -            | -                | -                | -         |     4.40 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            6 |     3838 | 2024-03-05 | Passion UA    | W   | 0.180      | -            | -                | -                | -         |     2.97 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            5 |     3848 | 2024-03-05 | UGANDA        | W   | 0.180      | -            | -                | -                | -         |     0.12 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            4 |     3976 | 2024-02-27 | DMS           | L   | 0.133      | -            | -                | -                | -         |    -3.07 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            3 |     4188 | 2024-02-18 | Aurora        | L   | 0.072      | -            | -                | -                | -         |    -0.08 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            2 |     4238 | 2024-02-16 | 500           | W   | 0.059      | -            | -                | -                | -         |     0.20 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            1 |     4244 | 2024-02-16 | PERA          | W   | 0.058      | -            | -                | -                | -         |     0.04 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($52,966.42)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.16) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.866 | $22,000.00     | $19,051.39      |
| 2024-06-09 |      0.819 | $1,500.00      | $1,228.85       |
| 2024-05-26 |      0.726 | $5,000.00      | $3,629.86       |
| 2024-05-18 |      0.673 | $10,000.00     | $6,729.17       |
| 2024-05-12 |      0.633 | $22,000.00     | $13,922.64      |
| 2024-04-24 |      0.512 | $12,500.00     | $6,404.51       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
