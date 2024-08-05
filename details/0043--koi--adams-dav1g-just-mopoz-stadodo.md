### Roster Details<br />
Team Name: KOI<br />
Roster: adamS, dav1g, JUST, mopoz, stadodo<br />
Global Rank: [43](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1098.2<br />
<br />
Final Rank Value (1098.2) = Starting Rank Value (1102.4) + Head To Head Adjustments (-4.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.449[<sup>1</sup>](#table2)
- Bounty Collected: 0.444[<sup>2</sup>](#table1)
- Opponent Network: 0.236[<sup>2</sup>](#table1)
- LAN Wins: 0.233[<sup>2</sup>](#table1)

The average of these factors is 0.341<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1102.4
- 400 + ( ( 0.341 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1102.4


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
|           46 |       12 | 2024-07-31 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -13.12 | adamS, dav1g, JUST, mopoz, stadodo |
|           45 |      174 | 2024-07-26 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.513 (0.257)    | 0 (0.000) |     5.46 | adamS, dav1g, JUST, mopoz, stadodo |
|           44 |      449 | 2024-07-18 | Monte           | L   | 1.000      | -            | -                | -                | -         |   -18.44 | adamS, dav1g, JUST, mopoz, stadodo |
|           43 |      583 | 2024-07-16 | Insilio         | W   | 1.000      | 0.500        | 0.023 (0.012)    | 0.554 (0.277)    | 0 (0.000) |     9.60 | adamS, dav1g, JUST, mopoz, stadodo |
|           42 |      849 | 2024-06-16 | 9z              | L   | 0.899      | -            | -                | -                | -         |    -3.40 | adamS, dav1g, JUST, mopoz, stadodo |
|           41 |      899 | 2024-06-14 | RED Canids      | W   | 0.888      | 0.548        | 0.079 (0.038)    | 0.738 (0.360)    | 1 (0.888) |    16.78 | adamS, dav1g, JUST, mopoz, stadodo |
|           40 |      904 | 2024-06-14 | Imperial        | W   | 0.887      | 0.548        | 0.243 (0.118)    | 0.685 (0.333)    | 1 (0.887) |    21.50 | adamS, dav1g, JUST, mopoz, stadodo |
|           39 |     1070 | 2024-06-09 | Sangal          | L   | 0.852      | -            | -                | -                | -         |    -9.35 | adamS, dav1g, JUST, mopoz, stadodo |
|           38 |     1258 | 2024-06-06 | SINNERS         | W   | 0.832      | 0.500        | 0.038 (0.016)    | 0.721 (0.300)    | 0 (0.000) |     9.48 | adamS, dav1g, JUST, mopoz, stadodo |
|           37 |     1319 | 2024-06-05 | 3DMAX           | W   | 0.826      | 0.500        | 0.499 (0.206)    | 1.000 (0.413)    | 0 (0.000) |    24.23 | adamS, dav1g, JUST, mopoz, stadodo |
|           36 |     1448 | 2024-06-01 | ENCE            | L   | 0.799      | -            | -                | -                | -         |    -3.60 | adamS, dav1g, JUST, mopoz, stadodo |
|           35 |     1454 | 2024-06-01 | Zero Tenacity   | L   | 0.798      | -            | -                | -                | -         |   -10.63 | adamS, dav1g, JUST, mopoz, stadodo |
|           34 |     2124 | 2024-05-09 | B8              | L   | 0.644      | -            | -                | -                | -         |   -10.63 | adamS, dav1g, JUST, mopoz, stadodo |
|           33 |     2287 | 2024-05-01 | Zero Tenacity   | L   | 0.591      | -            | -                | -                | -         |   -10.00 | adamS, dav1g, JUST, mopoz, stadodo |
|           32 |     2603 | 2024-04-18 | ex-Guild Eagles | L   | 0.506      | -            | -                | -                | -         |   -12.85 | adamS, dav1g, JUST, mopoz, stadodo |
|           31 |     2614 | 2024-04-18 | fnatic          | W   | 0.505      | 0.143        | 0.371 (0.027)    | -                | 0 (0.000) |    14.79 | adamS, dav1g, JUST, mopoz, stadodo |
|           30 |     2688 | 2024-04-16 | BLEED           | L   | 0.492      | -            | -                | -                | -         |    -9.52 | adamS, dav1g, JUST, mopoz, stadodo |
|           29 |     2819 | 2024-04-10 | RUSH B          | W   | 0.453      | 0.500        | -                | 0.308 (0.070)    | -         |     3.03 | adamS, dav1g, JUST, mopoz, stadodo |
|           28 |     2874 | 2024-04-09 | Aurora          | W   | 0.446      | 0.500        | 0.429 (0.096)    | 0.800 (0.178)    | -         |    13.53 | adamS, dav1g, JUST, mopoz, stadodo |
|           27 |     2880 | 2024-04-09 | Apeks           | L   | 0.445      | -            | -                | -                | -         |    -9.95 | adamS, dav1g, JUST, mopoz, stadodo |
|           26 |     2907 | 2024-04-08 | GUN5            | W   | 0.439      | -            | -                | -                | -         |     0.28 | adamS, dav1g, JUST, mopoz, stadodo |
|           25 |     2908 | 2024-04-08 | fnatic          | L   | 0.438      | -            | -                | -                | -         |    -0.90 | adamS, dav1g, JUST, mopoz, stadodo |
|           24 |     3011 | 2024-04-04 | NOM             | W   | 0.412      | -            | -                | -                | -         |     0.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           23 |     3045 | 2024-04-03 | 9INE            | W   | 0.406      | -            | -                | -                | -         |     0.51 | adamS, dav1g, JUST, mopoz, stadodo |
|           22 |     3083 | 2024-04-02 | TSM             | W   | 0.399      | -            | -                | -                | -         |     1.18 | adamS, dav1g, JUST, mopoz, stadodo |
|           21 |     3150 | 2024-03-28 | EYEBALLERS      | L   | 0.365      | -            | -                | -                | -         |    -8.59 | adamS, dav1g, JUST, mopoz, stadodo |
|           20 |     3322 | 2024-03-18 | FURIA           | L   | 0.299      | -            | -                | -                | -         |    -0.27 | adamS, dav1g, JUST, mopoz, stadodo |
|           19 |     3337 | 2024-03-17 | ENCE            | L   | 0.293      | -            | -                | -                | -         |    -1.00 | adamS, dav1g, JUST, mopoz, stadodo |
|           18 |     3353 | 2024-03-17 | SAW             | L   | 0.292      | -            | -                | -                | -         |    -3.41 | adamS, dav1g, JUST, mopoz, stadodo |
|           17 |     3445 | 2024-03-13 | Sangal          | W   | 0.266      | 0.500        | 0.219 (0.029)    | 0.824 (0.110)    | -         |     4.57 | adamS, dav1g, JUST, mopoz, stadodo |
|           16 |     3499 | 2024-03-11 | B8              | L   | 0.253      | -            | -                | -                | -         |    -4.06 | adamS, dav1g, JUST, mopoz, stadodo |
|           15 |     3508 | 2024-03-11 | Apeks           | L   | 0.252      | -            | -                | -                | -         |    -5.79 | adamS, dav1g, JUST, mopoz, stadodo |
|           14 |     3620 | 2024-03-06 | 9 Pandas        | W   | 0.220      | 0.500        | 0.082 (0.009)    | 0.579 (0.064)    | -         |     2.58 | adamS, dav1g, JUST, mopoz, stadodo |
|           13 |     3656 | 2024-03-05 | FORZE           | W   | 0.213      | -            | -                | -                | -         |     1.80 | adamS, dav1g, JUST, mopoz, stadodo |
|           12 |     3662 | 2024-03-05 | Nemiga          | W   | 0.213      | 0.143        | 0.322 (0.010)    | -                | -         |     3.97 | adamS, dav1g, JUST, mopoz, stadodo |
|           11 |     3670 | 2024-03-05 | ex-Sprout       | W   | 0.212      | -            | -                | -                | -         |     0.26 | adamS, dav1g, JUST, mopoz, stadodo |
|           10 |     3710 | 2024-03-03 | The Chosen Few  | L   | 0.199      | -            | -                | -                | -         |    -5.76 | adamS, dav1g, JUST, mopoz, stadodo |
|            9 |     3765 | 2024-02-29 | Aurora          | L   | 0.179      | -            | -                | -                | -         |    -0.21 | adamS, dav1g, JUST, mopoz, stadodo |
|            8 |     3769 | 2024-02-29 | HAVU            | W   | 0.178      | -            | -                | -                | -         |     0.56 | adamS, dav1g, JUST, mopoz, stadodo |
|            7 |     3778 | 2024-02-28 | FORZE           | L   | 0.173      | -            | -                | -                | -         |    -4.12 | adamS, dav1g, JUST, mopoz, stadodo |
|            6 |     3782 | 2024-02-28 | kONO            | W   | 0.172      | -            | -                | -                | -         |     0.88 | adamS, dav1g, JUST, mopoz, stadodo |
|            5 |     4073 | 2024-02-16 | fnatic          | W   | 0.091      | -            | -                | -                | 1 (0.091) |     2.67 | adamS, dav1g, JUST, mopoz, stadodo |
|            4 |     4097 | 2024-02-15 | 9 Pandas        | W   | 0.084      | -            | -                | -                | 1 (0.084) |     0.98 | adamS, dav1g, JUST, mopoz, stadodo |
|            3 |     4126 | 2024-02-14 | 3DMAX           | W   | 0.079      | -            | -                | -                | 1 (0.079) |     2.41 | adamS, dav1g, JUST, mopoz, stadodo |
|            2 |     4140 | 2024-02-14 | Natus Vincere   | L   | 0.078      | -            | -                | -                | -         |    -0.02 | adamS, dav1g, JUST, mopoz, stadodo |
|            1 |     4299 | 2024-02-03 | SAW             | L   | 0.005      | -            | -                | -                | -         |    -0.06 | adamS, dav1g, JUST, mopoz, stadodo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,656.26)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.901 | $7,000.00      | $6,306.38       |
| 2024-06-09 |      0.852 | $12,000.00     | $10,224.56      |
| 2024-03-20 |      0.313 | $10,000.00     | $3,125.32       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
