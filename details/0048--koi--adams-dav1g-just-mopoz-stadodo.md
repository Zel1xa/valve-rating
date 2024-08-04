### Roster Details<br />
Team Name: KOI<br />
Roster: adamS, dav1g, JUST, mopoz, stadodo<br />
Global Rank: [48](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1086.6<br />
<br />
Final Rank Value (1086.6) = Starting Rank Value (1085.9) + Head To Head Adjustments (0.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.448[<sup>1</sup>](#table2)
- Bounty Collected: 0.440[<sup>2</sup>](#table1)
- Opponent Network: 0.236[<sup>2</sup>](#table1)
- LAN Wins: 0.218[<sup>2</sup>](#table1)

The average of these factors is 0.335<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1085.9
- 400 + ( ( 0.335 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1085.9


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
|           45 |      160 | 2024-07-31 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -12.81 | adamS, dav1g, JUST, mopoz, stadodo |
|           44 |      322 | 2024-07-26 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.509 (0.255)    | 0 (0.000) |     5.64 | adamS, dav1g, JUST, mopoz, stadodo |
|           43 |      597 | 2024-07-18 | Monte           | L   | 1.000      | -            | -                | -                | -         |   -18.16 | adamS, dav1g, JUST, mopoz, stadodo |
|           42 |      731 | 2024-07-16 | Insilio         | W   | 1.000      | 0.500        | 0.023 (0.011)    | 0.561 (0.281)    | 0 (0.000) |     9.89 | adamS, dav1g, JUST, mopoz, stadodo |
|           41 |      997 | 2024-06-16 | 9z              | L   | 0.874      | -            | -                | -                | -         |    -3.28 | adamS, dav1g, JUST, mopoz, stadodo |
|           40 |     1047 | 2024-06-14 | RED Canids      | W   | 0.863      | 0.548        | 0.077 (0.037)    | 0.758 (0.359)    | 1 (0.863) |    16.42 | adamS, dav1g, JUST, mopoz, stadodo |
|           39 |     1052 | 2024-06-14 | Imperial        | W   | 0.862      | 0.548        | 0.236 (0.112)    | 0.685 (0.324)    | 1 (0.862) |    20.75 | adamS, dav1g, JUST, mopoz, stadodo |
|           38 |     1218 | 2024-06-09 | Sangal          | L   | 0.827      | -            | -                | -                | -         |    -8.63 | adamS, dav1g, JUST, mopoz, stadodo |
|           37 |     1406 | 2024-06-06 | SINNERS         | W   | 0.807      | 0.500        | 0.037 (0.015)    | 0.797 (0.322)    | 0 (0.000) |    10.97 | adamS, dav1g, JUST, mopoz, stadodo |
|           36 |     1467 | 2024-06-05 | 3DMAX           | W   | 0.800      | 0.500        | 0.506 (0.203)    | 1.000 (0.400)    | 0 (0.000) |    23.58 | adamS, dav1g, JUST, mopoz, stadodo |
|           35 |     1596 | 2024-06-01 | ENCE            | L   | 0.773      | -            | -                | -                | -         |    -3.49 | adamS, dav1g, JUST, mopoz, stadodo |
|           34 |     1602 | 2024-06-01 | Zero Tenacity   | L   | 0.773      | -            | -                | -                | -         |   -10.06 | adamS, dav1g, JUST, mopoz, stadodo |
|           33 |     2272 | 2024-05-09 | B8              | L   | 0.618      | -            | -                | -                | -         |    -9.97 | adamS, dav1g, JUST, mopoz, stadodo |
|           32 |     2435 | 2024-05-01 | Zero Tenacity   | L   | 0.565      | -            | -                | -                | -         |    -9.16 | adamS, dav1g, JUST, mopoz, stadodo |
|           31 |     2751 | 2024-04-18 | ex-Guild Eagles | L   | 0.481      | -            | -                | -                | -         |   -12.20 | adamS, dav1g, JUST, mopoz, stadodo |
|           30 |     2762 | 2024-04-18 | fnatic          | W   | 0.480      | 0.143        | 0.371 (0.025)    | -                | 0 (0.000) |    14.03 | adamS, dav1g, JUST, mopoz, stadodo |
|           29 |     2836 | 2024-04-16 | BLEED           | L   | 0.467      | -            | -                | -                | -         |    -8.97 | adamS, dav1g, JUST, mopoz, stadodo |
|           28 |     2967 | 2024-04-10 | RUSH B          | W   | 0.427      | 0.500        | -                | 0.386 (0.082)    | -         |     3.24 | adamS, dav1g, JUST, mopoz, stadodo |
|           27 |     3022 | 2024-04-09 | Aurora          | W   | 0.421      | 0.500        | 0.423 (0.089)    | 0.793 (0.167)    | -         |    12.77 | adamS, dav1g, JUST, mopoz, stadodo |
|           26 |     3028 | 2024-04-09 | Apeks           | L   | 0.420      | -            | -                | -                | -         |    -9.48 | adamS, dav1g, JUST, mopoz, stadodo |
|           25 |     3055 | 2024-04-08 | GUN5            | W   | 0.413      | -            | -                | -                | -         |     0.29 | adamS, dav1g, JUST, mopoz, stadodo |
|           24 |     3056 | 2024-04-08 | fnatic          | L   | 0.413      | -            | -                | -                | -         |    -0.87 | adamS, dav1g, JUST, mopoz, stadodo |
|           23 |     3159 | 2024-04-04 | NOM             | W   | 0.387      | -            | -                | -                | -         |     0.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           22 |     3193 | 2024-04-03 | 9INE            | W   | 0.381      | -            | -                | -                | -         |     0.51 | adamS, dav1g, JUST, mopoz, stadodo |
|           21 |     3231 | 2024-04-02 | TSM             | W   | 0.374      | -            | -                | -                | -         |     1.15 | adamS, dav1g, JUST, mopoz, stadodo |
|           20 |     3298 | 2024-03-28 | EYEBALLERS      | L   | 0.340      | -            | -                | -                | -         |    -7.88 | adamS, dav1g, JUST, mopoz, stadodo |
|           19 |     3470 | 2024-03-18 | FURIA           | L   | 0.274      | -            | -                | -                | -         |    -0.25 | adamS, dav1g, JUST, mopoz, stadodo |
|           18 |     3485 | 2024-03-17 | ENCE            | L   | 0.268      | -            | -                | -                | -         |    -0.94 | adamS, dav1g, JUST, mopoz, stadodo |
|           17 |     3501 | 2024-03-17 | SAW             | L   | 0.267      | -            | -                | -                | -         |    -3.12 | adamS, dav1g, JUST, mopoz, stadodo |
|           16 |     3593 | 2024-03-13 | Sangal          | W   | 0.241      | 0.500        | 0.219 (0.026)    | 0.861 (0.104)    | -         |     4.41 | adamS, dav1g, JUST, mopoz, stadodo |
|           15 |     3647 | 2024-03-11 | B8              | L   | 0.228      | -            | -                | -                | -         |    -3.58 | adamS, dav1g, JUST, mopoz, stadodo |
|           14 |     3656 | 2024-03-11 | Apeks           | L   | 0.226      | -            | -                | -                | -         |    -5.25 | adamS, dav1g, JUST, mopoz, stadodo |
|           13 |     3768 | 2024-03-06 | 9 Pandas        | W   | 0.194      | 0.500        | 0.081 (0.008)    | 0.690 (0.067)    | -         |     2.33 | adamS, dav1g, JUST, mopoz, stadodo |
|           12 |     3804 | 2024-03-05 | FORZE           | W   | 0.188      | -            | -                | -                | -         |     1.60 | adamS, dav1g, JUST, mopoz, stadodo |
|           11 |     3810 | 2024-03-05 | Nemiga          | W   | 0.188      | 0.143        | 0.317 (0.008)    | -                | -         |     3.67 | adamS, dav1g, JUST, mopoz, stadodo |
|           10 |     3818 | 2024-03-05 | ex-Sprout       | W   | 0.187      | -            | -                | -                | -         |     0.23 | adamS, dav1g, JUST, mopoz, stadodo |
|            9 |     3858 | 2024-03-03 | The Chosen Few  | L   | 0.174      | -            | -                | -                | -         |    -5.00 | adamS, dav1g, JUST, mopoz, stadodo |
|            8 |     3913 | 2024-02-29 | Aurora          | L   | 0.154      | -            | -                | -                | -         |    -0.18 | adamS, dav1g, JUST, mopoz, stadodo |
|            7 |     3917 | 2024-02-29 | HAVU            | W   | 0.153      | -            | -                | -                | -         |     0.50 | adamS, dav1g, JUST, mopoz, stadodo |
|            6 |     3926 | 2024-02-28 | FORZE           | L   | 0.148      | -            | -                | -                | -         |    -3.49 | adamS, dav1g, JUST, mopoz, stadodo |
|            5 |     3930 | 2024-02-28 | kONO            | W   | 0.146      | -            | -                | -                | -         |     0.80 | adamS, dav1g, JUST, mopoz, stadodo |
|            4 |     4221 | 2024-02-16 | fnatic          | W   | 0.065      | -            | -                | -                | 1 (0.065) |     1.93 | adamS, dav1g, JUST, mopoz, stadodo |
|            3 |     4245 | 2024-02-15 | 9 Pandas        | W   | 0.059      | -            | -                | -                | 1 (0.059) |     0.70 | adamS, dav1g, JUST, mopoz, stadodo |
|            2 |     4274 | 2024-02-14 | 3DMAX           | W   | 0.054      | -            | -                | -                | 1 (0.054) |     1.64 | adamS, dav1g, JUST, mopoz, stadodo |
|            1 |     4288 | 2024-02-14 | Natus Vincere   | L   | 0.052      | -            | -                | -                | -         |    -0.01 | adamS, dav1g, JUST, mopoz, stadodo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,923.61)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.876 | $7,000.00      | $6,129.54       |
| 2024-06-09 |      0.827 | $12,000.00     | $9,921.39       |
| 2024-03-20 |      0.287 | $10,000.00     | $2,872.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
