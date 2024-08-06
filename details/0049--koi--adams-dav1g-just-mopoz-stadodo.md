### Roster Details<br />
Team Name: KOI<br />
Roster: adamS, dav1g, JUST, mopoz, stadodo<br />
Global Rank: [49](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [36]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1084.7<br />
<br />
Final Rank Value (1084.7) = Starting Rank Value (1081.7) + Head To Head Adjustments (3.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.447[<sup>1</sup>](#table2)
- Bounty Collected: 0.438[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
- LAN Wins: 0.213[<sup>2</sup>](#table1)

The average of these factors is 0.332<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1081.7
- 400 + ( ( 0.332 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1081.7


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
|           45 |      193 | 2024-07-31 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -12.57 | adamS, dav1g, JUST, mopoz, stadodo |
|           44 |      355 | 2024-07-26 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.499 (0.249)    | 0 (0.000) |     5.82 | adamS, dav1g, JUST, mopoz, stadodo |
|           43 |      630 | 2024-07-18 | Monte           | L   | 1.000      | -            | -                | -                | -         |   -17.98 | adamS, dav1g, JUST, mopoz, stadodo |
|           42 |      764 | 2024-07-16 | Insilio         | W   | 1.000      | 0.500        | 0.023 (0.011)    | 0.552 (0.276)    | 0 (0.000) |    10.15 | adamS, dav1g, JUST, mopoz, stadodo |
|           41 |     1030 | 2024-06-16 | 9z              | L   | 0.862      | -            | -                | -                | -         |    -3.22 | adamS, dav1g, JUST, mopoz, stadodo |
|           40 |     1080 | 2024-06-14 | RED Canids      | W   | 0.851      | 0.548        | 0.076 (0.036)    | 0.748 (0.349)    | 1 (0.851) |    16.16 | adamS, dav1g, JUST, mopoz, stadodo |
|           39 |     1085 | 2024-06-14 | Imperial        | W   | 0.850      | 0.548        | 0.233 (0.109)    | 0.673 (0.314)    | 1 (0.850) |    20.39 | adamS, dav1g, JUST, mopoz, stadodo |
|           38 |     1251 | 2024-06-09 | Sangal          | L   | 0.815      | -            | -                | -                | -         |    -8.29 | adamS, dav1g, JUST, mopoz, stadodo |
|           37 |     1439 | 2024-06-06 | SINNERS         | W   | 0.795      | 0.500        | 0.037 (0.015)    | 0.808 (0.321)    | 0 (0.000) |    11.07 | adamS, dav1g, JUST, mopoz, stadodo |
|           36 |     1500 | 2024-06-05 | 3DMAX           | W   | 0.789      | 0.500        | 0.509 (0.201)    | 1.000 (0.394)    | 0 (0.000) |    23.32 | adamS, dav1g, JUST, mopoz, stadodo |
|           35 |     1629 | 2024-06-01 | ENCE            | L   | 0.762      | -            | -                | -                | -         |    -3.23 | adamS, dav1g, JUST, mopoz, stadodo |
|           34 |     1635 | 2024-06-01 | Zero Tenacity   | L   | 0.761      | -            | -                | -                | -         |    -9.67 | adamS, dav1g, JUST, mopoz, stadodo |
|           33 |     2305 | 2024-05-09 | B8              | L   | 0.606      | -            | -                | -                | -         |    -9.65 | adamS, dav1g, JUST, mopoz, stadodo |
|           32 |     2468 | 2024-05-01 | Zero Tenacity   | L   | 0.554      | -            | -                | -                | -         |    -8.77 | adamS, dav1g, JUST, mopoz, stadodo |
|           31 |     2784 | 2024-04-18 | ex-Guild Eagles | L   | 0.469      | -            | -                | -                | -         |   -11.84 | adamS, dav1g, JUST, mopoz, stadodo |
|           30 |     2795 | 2024-04-18 | fnatic          | W   | 0.468      | 0.143        | 0.371 (0.025)    | -                | 0 (0.000) |    13.70 | adamS, dav1g, JUST, mopoz, stadodo |
|           29 |     2869 | 2024-04-16 | BLEED           | L   | 0.455      | -            | -                | -                | -         |    -8.71 | adamS, dav1g, JUST, mopoz, stadodo |
|           28 |     3000 | 2024-04-10 | RUSH B          | W   | 0.416      | 0.500        | -                | 0.379 (0.079)    | -         |     3.21 | adamS, dav1g, JUST, mopoz, stadodo |
|           27 |     3055 | 2024-04-09 | Aurora          | W   | 0.409      | 0.500        | 0.421 (0.086)    | 0.776 (0.159)    | -         |    12.43 | adamS, dav1g, JUST, mopoz, stadodo |
|           26 |     3061 | 2024-04-09 | Apeks           | L   | 0.408      | -            | -                | -                | -         |    -9.22 | adamS, dav1g, JUST, mopoz, stadodo |
|           25 |     3088 | 2024-04-08 | GUN5            | W   | 0.402      | -            | -                | -                | -         |     0.29 | adamS, dav1g, JUST, mopoz, stadodo |
|           24 |     3089 | 2024-04-08 | fnatic          | L   | 0.401      | -            | -                | -                | -         |    -0.83 | adamS, dav1g, JUST, mopoz, stadodo |
|           23 |     3192 | 2024-04-04 | NOM             | W   | 0.375      | -            | -                | -                | -         |     0.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           22 |     3226 | 2024-04-03 | 9INE            | W   | 0.369      | -            | -                | -                | -         |     0.51 | adamS, dav1g, JUST, mopoz, stadodo |
|           21 |     3264 | 2024-04-02 | TSM             | W   | 0.362      | -            | -                | -                | -         |     1.13 | adamS, dav1g, JUST, mopoz, stadodo |
|           20 |     3331 | 2024-03-28 | EYEBALLERS      | L   | 0.328      | -            | -                | -                | -         |    -7.55 | adamS, dav1g, JUST, mopoz, stadodo |
|           19 |     3503 | 2024-03-18 | FURIA           | L   | 0.262      | -            | -                | -                | -         |    -0.24 | adamS, dav1g, JUST, mopoz, stadodo |
|           18 |     3518 | 2024-03-17 | ENCE            | L   | 0.256      | -            | -                | -                | -         |    -0.83 | adamS, dav1g, JUST, mopoz, stadodo |
|           17 |     3534 | 2024-03-17 | SAW             | L   | 0.255      | -            | -                | -                | -         |    -3.00 | adamS, dav1g, JUST, mopoz, stadodo |
|           16 |     3626 | 2024-03-13 | Sangal          | W   | 0.229      | 0.500        | 0.219 (0.025)    | 0.865 (0.099)    | -         |     4.28 | adamS, dav1g, JUST, mopoz, stadodo |
|           15 |     3680 | 2024-03-11 | B8              | L   | 0.216      | -            | -                | -                | -         |    -3.36 | adamS, dav1g, JUST, mopoz, stadodo |
|           14 |     3689 | 2024-03-11 | Apeks           | L   | 0.215      | -            | -                | -                | -         |    -4.97 | adamS, dav1g, JUST, mopoz, stadodo |
|           13 |     3801 | 2024-03-06 | 9 Pandas        | W   | 0.182      | 0.500        | 0.081 (0.007)    | 0.716 (0.065)    | -         |     2.19 | adamS, dav1g, JUST, mopoz, stadodo |
|           12 |     3837 | 2024-03-05 | FORZE           | W   | 0.176      | -            | -                | -                | -         |     1.51 | adamS, dav1g, JUST, mopoz, stadodo |
|           11 |     3843 | 2024-03-05 | Nemiga          | W   | 0.176      | 0.143        | 0.315 (0.008)    | -                | -         |     3.45 | adamS, dav1g, JUST, mopoz, stadodo |
|           10 |     3851 | 2024-03-05 | ex-Sprout       | W   | 0.175      | -            | -                | -                | -         |     0.21 | adamS, dav1g, JUST, mopoz, stadodo |
|            9 |     3891 | 2024-03-03 | The Chosen Few  | L   | 0.162      | -            | -                | -                | -         |    -4.65 | adamS, dav1g, JUST, mopoz, stadodo |
|            8 |     3946 | 2024-02-29 | Aurora          | L   | 0.142      | -            | -                | -                | -         |    -0.16 | adamS, dav1g, JUST, mopoz, stadodo |
|            7 |     3950 | 2024-02-29 | HAVU            | W   | 0.141      | -            | -                | -                | -         |     0.47 | adamS, dav1g, JUST, mopoz, stadodo |
|            6 |     3959 | 2024-02-28 | FORZE           | L   | 0.136      | -            | -                | -                | -         |    -3.20 | adamS, dav1g, JUST, mopoz, stadodo |
|            5 |     3963 | 2024-02-28 | kONO            | W   | 0.135      | -            | -                | -                | -         |     0.76 | adamS, dav1g, JUST, mopoz, stadodo |
|            4 |     4254 | 2024-02-16 | fnatic          | W   | 0.054      | -            | -                | -                | 1 (0.054) |     1.58 | adamS, dav1g, JUST, mopoz, stadodo |
|            3 |     4278 | 2024-02-15 | 9 Pandas        | W   | 0.047      | -            | -                | -                | 1 (0.047) |     0.56 | adamS, dav1g, JUST, mopoz, stadodo |
|            2 |     4307 | 2024-02-14 | 3DMAX           | W   | 0.042      | -            | -                | -                | 1 (0.042) |     1.29 | adamS, dav1g, JUST, mopoz, stadodo |
|            1 |     4321 | 2024-02-14 | Natus Vincere   | L   | 0.041      | -            | -                | -                | -         |    -0.01 | adamS, dav1g, JUST, mopoz, stadodo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,579.91)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.864 | $7,000.00      | $6,046.57       |
| 2024-06-09 |      0.815 | $12,000.00     | $9,779.17       |
| 2024-03-20 |      0.275 | $10,000.00     | $2,754.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
