### Roster Details<br />
Team Name: KOI<br />
Roster: adamS, dav1g, JUST, mopoz, stadodo<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [34]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1086.0<br />
<br />
Final Rank Value (1086.0) = Starting Rank Value (1084.9) + Head To Head Adjustments (1.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.448[<sup>1</sup>](#table2)
- Bounty Collected: 0.440[<sup>2</sup>](#table1)
- Opponent Network: 0.235[<sup>2</sup>](#table1)
- LAN Wins: 0.217[<sup>2</sup>](#table1)

The average of these factors is 0.335<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1084.9
- 400 + ( ( 0.335 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1084.9


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
|           45 |      165 | 2024-07-31 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -12.78 | adamS, dav1g, JUST, mopoz, stadodo |
|           44 |      327 | 2024-07-26 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.509 (0.254)    | 0 (0.000) |     5.65 | adamS, dav1g, JUST, mopoz, stadodo |
|           43 |      602 | 2024-07-18 | Monte           | L   | 1.000      | -            | -                | -                | -         |   -18.14 | adamS, dav1g, JUST, mopoz, stadodo |
|           42 |      736 | 2024-07-16 | Insilio         | W   | 1.000      | 0.500        | 0.023 (0.011)    | 0.561 (0.281)    | 0 (0.000) |     9.89 | adamS, dav1g, JUST, mopoz, stadodo |
|           41 |     1002 | 2024-06-16 | 9z              | L   | 0.871      | -            | -                | -                | -         |    -3.26 | adamS, dav1g, JUST, mopoz, stadodo |
|           40 |     1052 | 2024-06-14 | RED Canids      | W   | 0.860      | 0.548        | 0.077 (0.036)    | 0.758 (0.358)    | 1 (0.860) |    16.37 | adamS, dav1g, JUST, mopoz, stadodo |
|           39 |     1057 | 2024-06-14 | Imperial        | W   | 0.859      | 0.548        | 0.236 (0.111)    | 0.685 (0.323)    | 1 (0.859) |    20.67 | adamS, dav1g, JUST, mopoz, stadodo |
|           38 |     1223 | 2024-06-09 | Sangal          | L   | 0.824      | -            | -                | -                | -         |    -8.56 | adamS, dav1g, JUST, mopoz, stadodo |
|           37 |     1411 | 2024-06-06 | SINNERS         | W   | 0.804      | 0.500        | 0.037 (0.015)    | 0.797 (0.320)    | 0 (0.000) |    10.96 | adamS, dav1g, JUST, mopoz, stadodo |
|           36 |     1472 | 2024-06-05 | 3DMAX           | W   | 0.798      | 0.500        | 0.507 (0.202)    | 1.000 (0.399)    | 0 (0.000) |    23.52 | adamS, dav1g, JUST, mopoz, stadodo |
|           35 |     1601 | 2024-06-01 | ENCE            | L   | 0.771      | -            | -                | -                | -         |    -3.38 | adamS, dav1g, JUST, mopoz, stadodo |
|           34 |     1607 | 2024-06-01 | Zero Tenacity   | L   | 0.770      | -            | -                | -                | -         |    -9.99 | adamS, dav1g, JUST, mopoz, stadodo |
|           33 |     2277 | 2024-05-09 | B8              | L   | 0.616      | -            | -                | -                | -         |    -9.91 | adamS, dav1g, JUST, mopoz, stadodo |
|           32 |     2440 | 2024-05-01 | Zero Tenacity   | L   | 0.563      | -            | -                | -                | -         |    -9.06 | adamS, dav1g, JUST, mopoz, stadodo |
|           31 |     2756 | 2024-04-18 | ex-Guild Eagles | L   | 0.478      | -            | -                | -                | -         |   -12.13 | adamS, dav1g, JUST, mopoz, stadodo |
|           30 |     2767 | 2024-04-18 | fnatic          | W   | 0.477      | 0.143        | 0.371 (0.025)    | -                | 0 (0.000) |    13.95 | adamS, dav1g, JUST, mopoz, stadodo |
|           29 |     2841 | 2024-04-16 | BLEED           | L   | 0.464      | -            | -                | -                | -         |    -8.90 | adamS, dav1g, JUST, mopoz, stadodo |
|           28 |     2972 | 2024-04-10 | RUSH B          | W   | 0.425      | 0.500        | -                | 0.386 (0.082)    | -         |     3.23 | adamS, dav1g, JUST, mopoz, stadodo |
|           27 |     3027 | 2024-04-09 | Aurora          | W   | 0.418      | 0.500        | 0.423 (0.088)    | 0.792 (0.166)    | -         |    12.69 | adamS, dav1g, JUST, mopoz, stadodo |
|           26 |     3033 | 2024-04-09 | Apeks           | L   | 0.417      | -            | -                | -                | -         |    -9.43 | adamS, dav1g, JUST, mopoz, stadodo |
|           25 |     3060 | 2024-04-08 | GUN5            | W   | 0.411      | -            | -                | -                | -         |     0.29 | adamS, dav1g, JUST, mopoz, stadodo |
|           24 |     3061 | 2024-04-08 | fnatic          | L   | 0.410      | -            | -                | -                | -         |    -0.86 | adamS, dav1g, JUST, mopoz, stadodo |
|           23 |     3164 | 2024-04-04 | NOM             | W   | 0.384      | -            | -                | -                | -         |     0.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           22 |     3198 | 2024-04-03 | 9INE            | W   | 0.378      | -            | -                | -                | -         |     0.51 | adamS, dav1g, JUST, mopoz, stadodo |
|           21 |     3236 | 2024-04-02 | TSM             | W   | 0.371      | -            | -                | -                | -         |     1.15 | adamS, dav1g, JUST, mopoz, stadodo |
|           20 |     3303 | 2024-03-28 | EYEBALLERS      | L   | 0.337      | -            | -                | -                | -         |    -7.81 | adamS, dav1g, JUST, mopoz, stadodo |
|           19 |     3475 | 2024-03-18 | FURIA           | L   | 0.271      | -            | -                | -                | -         |    -0.25 | adamS, dav1g, JUST, mopoz, stadodo |
|           18 |     3490 | 2024-03-17 | ENCE            | L   | 0.265      | -            | -                | -                | -         |    -0.90 | adamS, dav1g, JUST, mopoz, stadodo |
|           17 |     3506 | 2024-03-17 | SAW             | L   | 0.264      | -            | -                | -                | -         |    -3.10 | adamS, dav1g, JUST, mopoz, stadodo |
|           16 |     3598 | 2024-03-13 | Sangal          | W   | 0.238      | 0.500        | 0.219 (0.026)    | 0.861 (0.103)    | -         |     4.39 | adamS, dav1g, JUST, mopoz, stadodo |
|           15 |     3652 | 2024-03-11 | B8              | L   | 0.225      | -            | -                | -                | -         |    -3.54 | adamS, dav1g, JUST, mopoz, stadodo |
|           14 |     3661 | 2024-03-11 | Apeks           | L   | 0.224      | -            | -                | -                | -         |    -5.18 | adamS, dav1g, JUST, mopoz, stadodo |
|           13 |     3773 | 2024-03-06 | 9 Pandas        | W   | 0.192      | 0.500        | 0.081 (0.008)    | 0.690 (0.066)    | -         |     2.30 | adamS, dav1g, JUST, mopoz, stadodo |
|           12 |     3809 | 2024-03-05 | FORZE           | W   | 0.185      | -            | -                | -                | -         |     1.58 | adamS, dav1g, JUST, mopoz, stadodo |
|           11 |     3815 | 2024-03-05 | Nemiga          | W   | 0.185      | 0.143        | 0.317 (0.008)    | -                | -         |     3.63 | adamS, dav1g, JUST, mopoz, stadodo |
|           10 |     3823 | 2024-03-05 | ex-Sprout       | W   | 0.184      | -            | -                | -                | -         |     0.23 | adamS, dav1g, JUST, mopoz, stadodo |
|            9 |     3863 | 2024-03-03 | The Chosen Few  | L   | 0.171      | -            | -                | -                | -         |    -4.92 | adamS, dav1g, JUST, mopoz, stadodo |
|            8 |     3918 | 2024-02-29 | Aurora          | L   | 0.152      | -            | -                | -                | -         |    -0.17 | adamS, dav1g, JUST, mopoz, stadodo |
|            7 |     3922 | 2024-02-29 | HAVU            | W   | 0.150      | -            | -                | -                | -         |     0.50 | adamS, dav1g, JUST, mopoz, stadodo |
|            6 |     3931 | 2024-02-28 | FORZE           | L   | 0.145      | -            | -                | -                | -         |    -3.42 | adamS, dav1g, JUST, mopoz, stadodo |
|            5 |     3935 | 2024-02-28 | kONO            | W   | 0.144      | -            | -                | -                | -         |     0.79 | adamS, dav1g, JUST, mopoz, stadodo |
|            4 |     4226 | 2024-02-16 | fnatic          | W   | 0.063      | -            | -                | -                | 1 (0.063) |     1.85 | adamS, dav1g, JUST, mopoz, stadodo |
|            3 |     4250 | 2024-02-15 | 9 Pandas        | W   | 0.056      | -            | -                | -                | 1 (0.056) |     0.67 | adamS, dav1g, JUST, mopoz, stadodo |
|            2 |     4279 | 2024-02-14 | 3DMAX           | W   | 0.051      | -            | -                | -                | 1 (0.051) |     1.56 | adamS, dav1g, JUST, mopoz, stadodo |
|            1 |     4293 | 2024-02-14 | Natus Vincere   | L   | 0.050      | -            | -                | -                | -         |    -0.01 | adamS, dav1g, JUST, mopoz, stadodo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,845.74)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.873 | $7,000.00      | $6,110.74       |
| 2024-06-09 |      0.824 | $12,000.00     | $9,889.17       |
| 2024-03-20 |      0.285 | $10,000.00     | $2,845.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
