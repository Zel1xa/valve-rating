### Roster Details<br />
Team Name: KOI<br />
Roster: adamS, dav1g, JUST, mopoz, stadodo<br />
Global Rank: [49](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [36]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1084.2<br />
<br />
Final Rank Value (1084.2) = Starting Rank Value (1080.8) + Head To Head Adjustments (3.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.447[<sup>1</sup>](#table2)
- Bounty Collected: 0.438[<sup>2</sup>](#table1)
- Opponent Network: 0.226[<sup>2</sup>](#table1)
- LAN Wins: 0.213[<sup>2</sup>](#table1)

The average of these factors is 0.331<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1080.8
- 400 + ( ( 0.331 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1080.8


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
|           45 |      200 | 2024-07-31 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -12.52 | adamS, dav1g, JUST, mopoz, stadodo |
|           44 |      362 | 2024-07-26 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.488 (0.244)    | 0 (0.000) |     5.84 | adamS, dav1g, JUST, mopoz, stadodo |
|           43 |      637 | 2024-07-18 | Monte           | L   | 1.000      | -            | -                | -                | -         |   -17.98 | adamS, dav1g, JUST, mopoz, stadodo |
|           42 |      771 | 2024-07-16 | Insilio         | W   | 1.000      | 0.500        | 0.023 (0.011)    | 0.539 (0.270)    | 0 (0.000) |    10.21 | adamS, dav1g, JUST, mopoz, stadodo |
|           41 |     1037 | 2024-06-16 | 9z              | L   | 0.861      | -            | -                | -                | -         |    -3.22 | adamS, dav1g, JUST, mopoz, stadodo |
|           40 |     1087 | 2024-06-14 | RED Canids      | W   | 0.851      | 0.548        | 0.076 (0.036)    | 0.732 (0.341)    | 1 (0.851) |    16.12 | adamS, dav1g, JUST, mopoz, stadodo |
|           39 |     1092 | 2024-06-14 | Imperial        | W   | 0.850      | 0.548        | 0.233 (0.109)    | 0.658 (0.307)    | 1 (0.850) |    20.36 | adamS, dav1g, JUST, mopoz, stadodo |
|           38 |     1258 | 2024-06-09 | Sangal          | L   | 0.814      | -            | -                | -                | -         |    -8.25 | adamS, dav1g, JUST, mopoz, stadodo |
|           37 |     1446 | 2024-06-06 | SINNERS         | W   | 0.795      | 0.500        | 0.037 (0.015)    | 0.790 (0.314)    | 0 (0.000) |    11.08 | adamS, dav1g, JUST, mopoz, stadodo |
|           36 |     1507 | 2024-06-05 | 3DMAX           | W   | 0.788      | 0.500        | 0.510 (0.201)    | 1.000 (0.394)    | 0 (0.000) |    23.31 | adamS, dav1g, JUST, mopoz, stadodo |
|           35 |     1636 | 2024-06-01 | ENCE            | L   | 0.761      | -            | -                | -                | -         |    -3.21 | adamS, dav1g, JUST, mopoz, stadodo |
|           34 |     1642 | 2024-06-01 | Zero Tenacity   | L   | 0.760      | -            | -                | -                | -         |    -9.64 | adamS, dav1g, JUST, mopoz, stadodo |
|           33 |     2312 | 2024-05-09 | B8              | L   | 0.606      | -            | -                | -                | -         |    -9.59 | adamS, dav1g, JUST, mopoz, stadodo |
|           32 |     2475 | 2024-05-01 | Zero Tenacity   | L   | 0.553      | -            | -                | -                | -         |    -8.75 | adamS, dav1g, JUST, mopoz, stadodo |
|           31 |     2791 | 2024-04-18 | ex-Guild Eagles | L   | 0.468      | -            | -                | -                | -         |   -11.81 | adamS, dav1g, JUST, mopoz, stadodo |
|           30 |     2802 | 2024-04-18 | fnatic          | W   | 0.468      | 0.143        | 0.371 (0.025)    | -                | 0 (0.000) |    13.68 | adamS, dav1g, JUST, mopoz, stadodo |
|           29 |     2876 | 2024-04-16 | BLEED           | L   | 0.455      | -            | -                | -                | -         |    -8.69 | adamS, dav1g, JUST, mopoz, stadodo |
|           28 |     3007 | 2024-04-10 | RUSH B          | W   | 0.415      | 0.500        | -                | 0.371 (0.077)    | -         |     3.21 | adamS, dav1g, JUST, mopoz, stadodo |
|           27 |     3062 | 2024-04-09 | Aurora          | W   | 0.408      | 0.500        | 0.420 (0.086)    | 0.759 (0.155)    | -         |    12.42 | adamS, dav1g, JUST, mopoz, stadodo |
|           26 |     3068 | 2024-04-09 | Apeks           | L   | 0.407      | -            | -                | -                | -         |    -9.19 | adamS, dav1g, JUST, mopoz, stadodo |
|           25 |     3095 | 2024-04-08 | GUN5            | W   | 0.401      | -            | -                | -                | -         |     0.29 | adamS, dav1g, JUST, mopoz, stadodo |
|           24 |     3096 | 2024-04-08 | fnatic          | L   | 0.401      | -            | -                | -                | -         |    -0.83 | adamS, dav1g, JUST, mopoz, stadodo |
|           23 |     3199 | 2024-04-04 | NOM             | W   | 0.374      | -            | -                | -                | -         |     0.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           22 |     3233 | 2024-04-03 | 9INE            | W   | 0.368      | -            | -                | -                | -         |     0.51 | adamS, dav1g, JUST, mopoz, stadodo |
|           21 |     3271 | 2024-04-02 | TSM             | W   | 0.362      | -            | -                | -                | -         |     1.14 | adamS, dav1g, JUST, mopoz, stadodo |
|           20 |     3338 | 2024-03-28 | EYEBALLERS      | L   | 0.327      | -            | -                | -                | -         |    -7.53 | adamS, dav1g, JUST, mopoz, stadodo |
|           19 |     3510 | 2024-03-18 | FURIA           | L   | 0.261      | -            | -                | -                | -         |    -0.24 | adamS, dav1g, JUST, mopoz, stadodo |
|           18 |     3525 | 2024-03-17 | ENCE            | L   | 0.256      | -            | -                | -                | -         |    -0.82 | adamS, dav1g, JUST, mopoz, stadodo |
|           17 |     3541 | 2024-03-17 | SAW             | L   | 0.254      | -            | -                | -                | -         |    -3.00 | adamS, dav1g, JUST, mopoz, stadodo |
|           16 |     3633 | 2024-03-13 | Sangal          | W   | 0.229      | 0.500        | 0.219 (0.025)    | 0.846 (0.097)    | -         |     4.28 | adamS, dav1g, JUST, mopoz, stadodo |
|           15 |     3687 | 2024-03-11 | B8              | L   | 0.215      | -            | -                | -                | -         |    -3.33 | adamS, dav1g, JUST, mopoz, stadodo |
|           14 |     3696 | 2024-03-11 | Apeks           | L   | 0.214      | -            | -                | -                | -         |    -4.95 | adamS, dav1g, JUST, mopoz, stadodo |
|           13 |     3808 | 2024-03-06 | 9 Pandas        | W   | 0.182      | 0.500        | 0.081 (0.007)    | 0.700 (0.064)    | -         |     2.19 | adamS, dav1g, JUST, mopoz, stadodo |
|           12 |     3844 | 2024-03-05 | FORZE           | W   | 0.175      | -            | -                | -                | -         |     1.51 | adamS, dav1g, JUST, mopoz, stadodo |
|           11 |     3850 | 2024-03-05 | Nemiga          | W   | 0.175      | 0.143        | 0.314 (0.008)    | -                | -         |     3.45 | adamS, dav1g, JUST, mopoz, stadodo |
|           10 |     3858 | 2024-03-05 | ex-Sprout       | W   | 0.175      | -            | -                | -                | -         |     0.21 | adamS, dav1g, JUST, mopoz, stadodo |
|            9 |     3898 | 2024-03-03 | The Chosen Few  | L   | 0.161      | -            | -                | -                | -         |    -4.63 | adamS, dav1g, JUST, mopoz, stadodo |
|            8 |     3953 | 2024-02-29 | Aurora          | L   | 0.142      | -            | -                | -                | -         |    -0.15 | adamS, dav1g, JUST, mopoz, stadodo |
|            7 |     3957 | 2024-02-29 | HAVU            | W   | 0.141      | -            | -                | -                | -         |     0.47 | adamS, dav1g, JUST, mopoz, stadodo |
|            6 |     3966 | 2024-02-28 | FORZE           | L   | 0.135      | -            | -                | -                | -         |    -3.18 | adamS, dav1g, JUST, mopoz, stadodo |
|            5 |     3970 | 2024-02-28 | kONO            | W   | 0.134      | -            | -                | -                | -         |     0.77 | adamS, dav1g, JUST, mopoz, stadodo |
|            4 |     4261 | 2024-02-16 | fnatic          | W   | 0.053      | -            | -                | -                | 1 (0.053) |     1.56 | adamS, dav1g, JUST, mopoz, stadodo |
|            3 |     4285 | 2024-02-15 | 9 Pandas        | W   | 0.046      | -            | -                | -                | 1 (0.046) |     0.56 | adamS, dav1g, JUST, mopoz, stadodo |
|            2 |     4314 | 2024-02-14 | 3DMAX           | W   | 0.042      | -            | -                | -                | 1 (0.042) |     1.27 | adamS, dav1g, JUST, mopoz, stadodo |
|            1 |     4328 | 2024-02-14 | Natus Vincere   | L   | 0.040      | -            | -                | -                | -         |    -0.01 | adamS, dav1g, JUST, mopoz, stadodo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,561.11)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.863 | $7,000.00      | $6,042.04       |
| 2024-06-09 |      0.814 | $12,000.00     | $9,771.39       |
| 2024-03-20 |      0.275 | $10,000.00     | $2,747.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
