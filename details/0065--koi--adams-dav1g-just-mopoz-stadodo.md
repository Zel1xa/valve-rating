### Roster Details<br />
Team Name: KOI<br />
Roster: adamS, dav1g, JUST, mopoz, stadodo<br />
Global Rank: [65](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [45]( ../standings_europe.md)<br />
<br />
Final Rank Value:  960.1<br />
<br />
Final Rank Value (960.1) = Starting Rank Value (927.8) + Head To Head Adjustments (32.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.416[<sup>2</sup>](#table1)
- Opponent Network: 0.177[<sup>2</sup>](#table1)
- LAN Wins: 0.022[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 927.8
- 400 + ( ( 0.258 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 927.8


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
|           42 |      104 | 2024-07-31 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |    -8.63 | adamS, dav1g, JUST, mopoz, stadodo |
|           41 |      265 | 2024-07-26 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.528 (0.264)    | 0 (0.000) |     9.83 | adamS, dav1g, JUST, mopoz, stadodo |
|           40 |      540 | 2024-07-18 | Monte           | L   | 1.000      | -            | -                | -                | -         |   -12.64 | adamS, dav1g, JUST, mopoz, stadodo |
|           39 |      671 | 2024-07-16 | Insilio         | W   | 1.000      | 0.500        | 0.023 (0.011)    | 0.581 (0.290)    | 0 (0.000) |    15.79 | adamS, dav1g, JUST, mopoz, stadodo |
|           38 |     1128 | 2024-06-09 | Sangal          | L   | 0.833      | -            | -                | -                | -         |    -6.00 | adamS, dav1g, JUST, mopoz, stadodo |
|           37 |     1311 | 2024-06-06 | SINNERS         | W   | 0.813      | 0.500        | 0.037 (0.015)    | 0.784 (0.319)    | 0 (0.000) |    14.39 | adamS, dav1g, JUST, mopoz, stadodo |
|           36 |     1372 | 2024-06-05 | 3DMAX           | W   | 0.807      | 0.500        | 0.504 (0.203)    | 1.000 (0.403)    | 0 (0.000) |    24.50 | adamS, dav1g, JUST, mopoz, stadodo |
|           35 |     1498 | 2024-06-01 | ENCE            | L   | 0.780      | -            | -                | -                | -         |    -2.07 | adamS, dav1g, JUST, mopoz, stadodo |
|           34 |     1504 | 2024-06-01 | Zero Tenacity   | L   | 0.779      | -            | -                | -                | -         |    -6.46 | adamS, dav1g, JUST, mopoz, stadodo |
|           33 |     2172 | 2024-05-09 | B8              | L   | 0.624      | -            | -                | -                | -         |    -6.72 | adamS, dav1g, JUST, mopoz, stadodo |
|           32 |     2334 | 2024-05-01 | Zero Tenacity   | L   | 0.572      | -            | -                | -                | -         |    -6.17 | adamS, dav1g, JUST, mopoz, stadodo |
|           31 |     2649 | 2024-04-18 | ex-Guild Eagles | L   | 0.487      | -            | -                | -                | -         |   -10.11 | adamS, dav1g, JUST, mopoz, stadodo |
|           30 |     2660 | 2024-04-18 | fnatic          | W   | 0.486      | 0.143        | 0.290 (0.020)    | 0.627 (0.044)    | 0 (0.000) |    13.84 | adamS, dav1g, JUST, mopoz, stadodo |
|           29 |     2734 | 2024-04-16 | BLEED           | L   | 0.473      | -            | -                | -                | -         |    -6.28 | adamS, dav1g, JUST, mopoz, stadodo |
|           28 |     2865 | 2024-04-10 | RUSH B          | W   | 0.434      | 0.500        | 0.017 (0.004)    | 0.399 (0.086)    | 0 (0.000) |     5.34 | adamS, dav1g, JUST, mopoz, stadodo |
|           27 |     2920 | 2024-04-09 | Aurora          | W   | 0.427      | 0.500        | 0.425 (0.091)    | 0.809 (0.173)    | 0 (0.000) |    13.22 | adamS, dav1g, JUST, mopoz, stadodo |
|           26 |     2926 | 2024-04-09 | Apeks           | L   | 0.426      | -            | -                | -                | -         |    -7.19 | adamS, dav1g, JUST, mopoz, stadodo |
|           25 |     2953 | 2024-04-08 | GUN5            | W   | 0.420      | -            | -                | -                | -         |     0.63 | adamS, dav1g, JUST, mopoz, stadodo |
|           24 |     2954 | 2024-04-08 | fnatic          | L   | 0.419      | -            | -                | -                | -         |    -1.14 | adamS, dav1g, JUST, mopoz, stadodo |
|           23 |     3057 | 2024-04-04 | NOM             | W   | 0.393      | -            | -                | -                | -         |     1.01 | adamS, dav1g, JUST, mopoz, stadodo |
|           22 |     3091 | 2024-04-03 | 9INE            | W   | 0.387      | -            | -                | -                | -         |     1.10 | adamS, dav1g, JUST, mopoz, stadodo |
|           21 |     3129 | 2024-04-02 | TSM             | W   | 0.380      | -            | -                | -                | -         |     2.33 | adamS, dav1g, JUST, mopoz, stadodo |
|           20 |     3196 | 2024-03-28 | EYEBALLERS      | L   | 0.346      | -            | -                | -                | -         |    -6.02 | adamS, dav1g, JUST, mopoz, stadodo |
|           19 |     3363 | 2024-03-18 | FURIA           | L   | 0.280      | -            | -                | -                | -         |    -0.12 | adamS, dav1g, JUST, mopoz, stadodo |
|           18 |     3378 | 2024-03-17 | ENCE            | L   | 0.274      | -            | -                | -                | -         |    -0.46 | adamS, dav1g, JUST, mopoz, stadodo |
|           17 |     3394 | 2024-03-17 | SAW             | L   | 0.273      | -            | -                | -                | -         |    -1.75 | adamS, dav1g, JUST, mopoz, stadodo |
|           16 |     3485 | 2024-03-13 | Sangal          | W   | 0.247      | 0.500        | 0.219 (0.027)    | 0.823 (0.102)    | -         |     5.89 | adamS, dav1g, JUST, mopoz, stadodo |
|           15 |     3537 | 2024-03-11 | B8              | L   | 0.234      | -            | -                | -                | -         |    -2.21 | adamS, dav1g, JUST, mopoz, stadodo |
|           14 |     3546 | 2024-03-11 | Apeks           | L   | 0.233      | -            | -                | -                | -         |    -3.97 | adamS, dav1g, JUST, mopoz, stadodo |
|           13 |     3658 | 2024-03-06 | 9 Pandas        | W   | 0.201      | 0.500        | 0.082 (0.008)    | 0.715 (0.072)    | -         |     3.72 | adamS, dav1g, JUST, mopoz, stadodo |
|           12 |     3694 | 2024-03-05 | FORZE           | W   | 0.194      | -            | -                | -                | -         |     2.88 | adamS, dav1g, JUST, mopoz, stadodo |
|           11 |     3700 | 2024-03-05 | Nemiga          | W   | 0.194      | 0.143        | 0.318 (0.009)    | 0.719 (0.020)    | -         |     4.75 | adamS, dav1g, JUST, mopoz, stadodo |
|           10 |     3708 | 2024-03-05 | ex-Sprout       | W   | 0.193      | -            | -                | -                | -         |     0.55 | adamS, dav1g, JUST, mopoz, stadodo |
|            9 |     3748 | 2024-03-03 | The Chosen Few  | L   | 0.180      | -            | -                | -                | -         |    -4.62 | adamS, dav1g, JUST, mopoz, stadodo |
|            8 |     3803 | 2024-02-29 | Aurora          | L   | 0.160      | -            | -                | -                | -         |    -0.08 | adamS, dav1g, JUST, mopoz, stadodo |
|            7 |     3807 | 2024-02-29 | HAVU            | W   | 0.159      | -            | -                | -                | -         |     1.10 | adamS, dav1g, JUST, mopoz, stadodo |
|            6 |     3816 | 2024-02-28 | FORZE           | L   | 0.154      | -            | -                | -                | -         |    -2.68 | adamS, dav1g, JUST, mopoz, stadodo |
|            5 |     3820 | 2024-02-28 | kONO            | W   | 0.153      | -            | -                | -                | -         |     1.62 | adamS, dav1g, JUST, mopoz, stadodo |
|            4 |     4110 | 2024-02-16 | fnatic          | W   | 0.072      | -            | -                | -                | 1 (0.072) |     2.07 | adamS, dav1g, JUST, mopoz, stadodo |
|            3 |     4134 | 2024-02-15 | 9 Pandas        | W   | 0.065      | -            | -                | -                | 1 (0.065) |     1.22 | adamS, dav1g, JUST, mopoz, stadodo |
|            2 |     4163 | 2024-02-14 | 3DMAX           | W   | 0.060      | 0.143        | 0.504 (0.004)    | -                | 1 (0.060) |     1.87 | adamS, dav1g, JUST, mopoz, stadodo |
|            1 |     4177 | 2024-02-14 | Natus Vincere   | L   | 0.059      | -            | -                | -                | -         |    -0.01 | adamS, dav1g, JUST, mopoz, stadodo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,931.57)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.833 | $12,000.00     | $9,996.39       |
| 2024-03-20 |      0.294 | $10,000.00     | $2,935.19       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
