### Roster Details<br />
Team Name: KOI<br />
Roster: adamS, dav1g, JUST, mopoz, stadodo<br />
Global Rank: [49](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [36]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1085.6<br />
<br />
Final Rank Value (1085.6) = Starting Rank Value (1081.3) + Head To Head Adjustments (4.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.447[<sup>1</sup>](#table2)
- Bounty Collected: 0.439[<sup>2</sup>](#table1)
- Opponent Network: 0.226[<sup>2</sup>](#table1)
- LAN Wins: 0.212[<sup>2</sup>](#table1)

The average of these factors is 0.331<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1081.3
- 400 + ( ( 0.331 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1081.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           45 |      212 | 2024-07-31 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -12.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           44 |      374 | 2024-07-26 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.488 (0.244)    | 0 (0.000) |     5.85 | adamS, dav1g, JUST, mopoz, stadodo |
|           43 |      649 | 2024-07-18 | Monte           | L   | 1.000      | -            | -                | -                | -         |   -17.92 | adamS, dav1g, JUST, mopoz, stadodo |
|           42 |      783 | 2024-07-16 | Insilio         | W   | 1.000      | 0.500        | 0.023 (0.011)    | 0.539 (0.270)    | 0 (0.000) |    10.24 | adamS, dav1g, JUST, mopoz, stadodo |
|           41 |     1049 | 2024-06-16 | 9z              | L   | 0.860      | -            | -                | -                | -         |    -3.24 | adamS, dav1g, JUST, mopoz, stadodo |
|           40 |     1099 | 2024-06-14 | RED Canids      | W   | 0.849      | 0.548        | 0.076 (0.036)    | 0.732 (0.341)    | 1 (0.849) |    16.04 | adamS, dav1g, JUST, mopoz, stadodo |
|           39 |     1104 | 2024-06-14 | Imperial        | W   | 0.848      | 0.548        | 0.233 (0.108)    | 0.658 (0.306)    | 1 (0.848) |    20.28 | adamS, dav1g, JUST, mopoz, stadodo |
|           38 |     1270 | 2024-06-09 | Sangal          | L   | 0.813      | -            | -                | -                | -         |    -7.82 | adamS, dav1g, JUST, mopoz, stadodo |
|           37 |     1458 | 2024-06-06 | SINNERS         | W   | 0.793      | 0.500        | 0.037 (0.015)    | 0.800 (0.317)    | 0 (0.000) |    11.11 | adamS, dav1g, JUST, mopoz, stadodo |
|           36 |     1519 | 2024-06-05 | 3DMAX           | W   | 0.787      | 0.500        | 0.510 (0.201)    | 1.000 (0.393)    | 0 (0.000) |    23.28 | adamS, dav1g, JUST, mopoz, stadodo |
|           35 |     1648 | 2024-06-01 | ENCE            | L   | 0.760      | -            | -                | -                | -         |    -3.20 | adamS, dav1g, JUST, mopoz, stadodo |
|           34 |     1654 | 2024-06-01 | Zero Tenacity   | L   | 0.759      | -            | -                | -                | -         |    -9.55 | adamS, dav1g, JUST, mopoz, stadodo |
|           33 |     2324 | 2024-05-09 | B8              | L   | 0.605      | -            | -                | -                | -         |    -9.55 | adamS, dav1g, JUST, mopoz, stadodo |
|           32 |     2487 | 2024-05-01 | Zero Tenacity   | L   | 0.552      | -            | -                | -                | -         |    -8.68 | adamS, dav1g, JUST, mopoz, stadodo |
|           31 |     2803 | 2024-04-18 | ex-Guild Eagles | L   | 0.467      | -            | -                | -                | -         |   -11.76 | adamS, dav1g, JUST, mopoz, stadodo |
|           30 |     2814 | 2024-04-18 | fnatic          | W   | 0.467      | 0.143        | 0.371 (0.025)    | -                | 0 (0.000) |    13.65 | adamS, dav1g, JUST, mopoz, stadodo |
|           29 |     2888 | 2024-04-16 | BLEED           | L   | 0.453      | -            | -                | -                | -         |    -8.65 | adamS, dav1g, JUST, mopoz, stadodo |
|           28 |     3019 | 2024-04-10 | RUSH B          | W   | 0.414      | 0.500        | -                | 0.371 (0.077)    | -         |     3.22 | adamS, dav1g, JUST, mopoz, stadodo |
|           27 |     3074 | 2024-04-09 | Aurora          | W   | 0.407      | 0.500        | 0.420 (0.086)    | 0.758 (0.154)    | -         |    12.38 | adamS, dav1g, JUST, mopoz, stadodo |
|           26 |     3080 | 2024-04-09 | Apeks           | L   | 0.406      | -            | -                | -                | -         |    -9.18 | adamS, dav1g, JUST, mopoz, stadodo |
|           25 |     3107 | 2024-04-08 | GUN5            | W   | 0.400      | -            | -                | -                | -         |     0.28 | adamS, dav1g, JUST, mopoz, stadodo |
|           24 |     3108 | 2024-04-08 | fnatic          | L   | 0.399      | -            | -                | -                | -         |    -0.82 | adamS, dav1g, JUST, mopoz, stadodo |
|           23 |     3211 | 2024-04-04 | NOM             | W   | 0.373      | -            | -                | -                | -         |     0.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           22 |     3245 | 2024-04-03 | 9INE            | W   | 0.367      | -            | -                | -                | -         |     0.52 | adamS, dav1g, JUST, mopoz, stadodo |
|           21 |     3283 | 2024-04-02 | TSM             | W   | 0.360      | -            | -                | -                | -         |     1.13 | adamS, dav1g, JUST, mopoz, stadodo |
|           20 |     3350 | 2024-03-28 | EYEBALLERS      | L   | 0.326      | -            | -                | -                | -         |    -7.50 | adamS, dav1g, JUST, mopoz, stadodo |
|           19 |     3522 | 2024-03-18 | FURIA           | L   | 0.260      | -            | -                | -                | -         |    -0.24 | adamS, dav1g, JUST, mopoz, stadodo |
|           18 |     3537 | 2024-03-17 | ENCE            | L   | 0.254      | -            | -                | -                | -         |    -0.82 | adamS, dav1g, JUST, mopoz, stadodo |
|           17 |     3553 | 2024-03-17 | SAW             | L   | 0.253      | -            | -                | -                | -         |    -2.97 | adamS, dav1g, JUST, mopoz, stadodo |
|           16 |     3645 | 2024-03-13 | Sangal          | W   | 0.227      | 0.500        | 0.288 (0.033)    | 0.858 (0.098)    | -         |     4.52 | adamS, dav1g, JUST, mopoz, stadodo |
|           15 |     3699 | 2024-03-11 | B8              | L   | 0.214      | -            | -                | -                | -         |    -3.31 | adamS, dav1g, JUST, mopoz, stadodo |
|           14 |     3708 | 2024-03-11 | Apeks           | L   | 0.213      | -            | -                | -                | -         |    -4.93 | adamS, dav1g, JUST, mopoz, stadodo |
|           13 |     3820 | 2024-03-06 | 9 Pandas        | W   | 0.181      | 0.500        | 0.081 (0.007)    | 0.700 (0.063)    | -         |     2.24 | adamS, dav1g, JUST, mopoz, stadodo |
|           12 |     3856 | 2024-03-05 | FORZE           | W   | 0.174      | -            | -                | -                | -         |     1.50 | adamS, dav1g, JUST, mopoz, stadodo |
|           11 |     3862 | 2024-03-05 | Nemiga          | W   | 0.174      | 0.143        | 0.314 (0.008)    | -                | -         |     3.43 | adamS, dav1g, JUST, mopoz, stadodo |
|           10 |     3870 | 2024-03-05 | ex-Sprout       | W   | 0.173      | -            | -                | -                | -         |     0.21 | adamS, dav1g, JUST, mopoz, stadodo |
|            9 |     3910 | 2024-03-03 | The Chosen Few  | L   | 0.160      | -            | -                | -                | -         |    -4.59 | adamS, dav1g, JUST, mopoz, stadodo |
|            8 |     3965 | 2024-02-29 | Aurora          | L   | 0.141      | -            | -                | -                | -         |    -0.15 | adamS, dav1g, JUST, mopoz, stadodo |
|            7 |     3969 | 2024-02-29 | HAVU            | W   | 0.139      | -            | -                | -                | -         |     0.47 | adamS, dav1g, JUST, mopoz, stadodo |
|            6 |     3978 | 2024-02-28 | FORZE           | L   | 0.134      | -            | -                | -                | -         |    -3.15 | adamS, dav1g, JUST, mopoz, stadodo |
|            5 |     3982 | 2024-02-28 | kONO            | W   | 0.133      | -            | -                | -                | -         |     0.76 | adamS, dav1g, JUST, mopoz, stadodo |
|            4 |     4273 | 2024-02-16 | fnatic          | W   | 0.052      | -            | -                | -                | 1 (0.052) |     1.52 | adamS, dav1g, JUST, mopoz, stadodo |
|            3 |     4297 | 2024-02-15 | 9 Pandas        | W   | 0.045      | -            | -                | -                | 1 (0.045) |     0.56 | adamS, dav1g, JUST, mopoz, stadodo |
|            2 |     4326 | 2024-02-14 | 3DMAX           | W   | 0.040      | -            | -                | -                | 1 (0.040) |     1.23 | adamS, dav1g, JUST, mopoz, stadodo |
|            1 |     4340 | 2024-02-14 | Natus Vincere   | L   | 0.039      | -            | -                | -                | -         |    -0.01 | adamS, dav1g, JUST, mopoz, stadodo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,527.55)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.862 | $7,000.00      | $6,033.94       |
| 2024-06-09 |      0.813 | $12,000.00     | $9,757.50       |
| 2024-03-20 |      0.274 | $10,000.00     | $2,736.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
