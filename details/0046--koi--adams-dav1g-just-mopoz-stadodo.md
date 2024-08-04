### Roster Details<br />
Team Name: KOI<br />
Roster: adamS, dav1g, JUST, mopoz, stadodo<br />
Global Rank: [46](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [34]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1085.4<br />
<br />
Final Rank Value (1085.4) = Starting Rank Value (1085.0) + Head To Head Adjustments (0.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.448[<sup>1</sup>](#table2)
- Bounty Collected: 0.440[<sup>2</sup>](#table1)
- Opponent Network: 0.234[<sup>2</sup>](#table1)
- LAN Wins: 0.218[<sup>2</sup>](#table1)

The average of these factors is 0.335<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1085.0
- 400 + ( ( 0.335 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1085.0


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
|           45 |      137 | 2024-07-31 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -12.77 | adamS, dav1g, JUST, mopoz, stadodo |
|           44 |      298 | 2024-07-26 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.510 (0.255)    | 0 (0.000) |     5.71 | adamS, dav1g, JUST, mopoz, stadodo |
|           43 |      571 | 2024-07-18 | Monte           | L   | 1.000      | -            | -                | -                | -         |   -18.14 | adamS, dav1g, JUST, mopoz, stadodo |
|           42 |      706 | 2024-07-16 | Insilio         | W   | 1.000      | 0.500        | 0.023 (0.011)    | 0.561 (0.281)    | 0 (0.000) |     9.94 | adamS, dav1g, JUST, mopoz, stadodo |
|           41 |      974 | 2024-06-16 | 9z              | L   | 0.874      | -            | -                | -                | -         |    -3.26 | adamS, dav1g, JUST, mopoz, stadodo |
|           40 |     1024 | 2024-06-14 | RED Canids      | W   | 0.864      | 0.548        | 0.077 (0.037)    | 0.743 (0.352)    | 1 (0.864) |    16.49 | adamS, dav1g, JUST, mopoz, stadodo |
|           39 |     1029 | 2024-06-14 | Imperial        | W   | 0.863      | 0.548        | 0.237 (0.112)    | 0.685 (0.324)    | 1 (0.863) |    20.82 | adamS, dav1g, JUST, mopoz, stadodo |
|           38 |     1195 | 2024-06-09 | Sangal          | L   | 0.828      | -            | -                | -                | -         |    -8.65 | adamS, dav1g, JUST, mopoz, stadodo |
|           37 |     1383 | 2024-06-06 | SINNERS         | W   | 0.808      | 0.500        | 0.037 (0.015)    | 0.757 (0.306)    | 0 (0.000) |    10.24 | adamS, dav1g, JUST, mopoz, stadodo |
|           36 |     1444 | 2024-06-05 | 3DMAX           | W   | 0.801      | 0.500        | 0.506 (0.203)    | 1.000 (0.401)    | 0 (0.000) |    23.60 | adamS, dav1g, JUST, mopoz, stadodo |
|           35 |     1573 | 2024-06-01 | ENCE            | L   | 0.774      | -            | -                | -                | -         |    -3.49 | adamS, dav1g, JUST, mopoz, stadodo |
|           34 |     1579 | 2024-06-01 | Zero Tenacity   | L   | 0.773      | -            | -                | -                | -         |    -9.98 | adamS, dav1g, JUST, mopoz, stadodo |
|           33 |     2249 | 2024-05-09 | B8              | L   | 0.619      | -            | -                | -                | -         |    -9.99 | adamS, dav1g, JUST, mopoz, stadodo |
|           32 |     2412 | 2024-05-01 | Zero Tenacity   | L   | 0.566      | -            | -                | -                | -         |    -9.21 | adamS, dav1g, JUST, mopoz, stadodo |
|           31 |     2728 | 2024-04-18 | ex-Guild Eagles | L   | 0.481      | -            | -                | -                | -         |   -12.17 | adamS, dav1g, JUST, mopoz, stadodo |
|           30 |     2739 | 2024-04-18 | fnatic          | W   | 0.481      | 0.143        | 0.371 (0.025)    | -                | 0 (0.000) |    14.05 | adamS, dav1g, JUST, mopoz, stadodo |
|           29 |     2813 | 2024-04-16 | BLEED           | L   | 0.468      | -            | -                | -                | -         |    -8.98 | adamS, dav1g, JUST, mopoz, stadodo |
|           28 |     2944 | 2024-04-10 | RUSH B          | W   | 0.428      | 0.500        | -                | 0.386 (0.083)    | -         |     3.25 | adamS, dav1g, JUST, mopoz, stadodo |
|           27 |     2999 | 2024-04-09 | Aurora          | W   | 0.422      | 0.500        | 0.423 (0.089)    | 0.793 (0.167)    | -         |    12.79 | adamS, dav1g, JUST, mopoz, stadodo |
|           26 |     3005 | 2024-04-09 | Apeks           | L   | 0.421      | -            | -                | -                | -         |    -9.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           25 |     3032 | 2024-04-08 | GUN5            | W   | 0.414      | -            | -                | -                | -         |     0.29 | adamS, dav1g, JUST, mopoz, stadodo |
|           24 |     3033 | 2024-04-08 | fnatic          | L   | 0.414      | -            | -                | -                | -         |    -0.87 | adamS, dav1g, JUST, mopoz, stadodo |
|           23 |     3136 | 2024-04-04 | NOM             | W   | 0.387      | -            | -                | -                | -         |     0.48 | adamS, dav1g, JUST, mopoz, stadodo |
|           22 |     3170 | 2024-04-03 | 9INE            | W   | 0.382      | -            | -                | -                | -         |     0.52 | adamS, dav1g, JUST, mopoz, stadodo |
|           21 |     3208 | 2024-04-02 | TSM             | W   | 0.375      | -            | -                | -                | -         |     1.16 | adamS, dav1g, JUST, mopoz, stadodo |
|           20 |     3275 | 2024-03-28 | EYEBALLERS      | L   | 0.341      | -            | -                | -                | -         |    -7.89 | adamS, dav1g, JUST, mopoz, stadodo |
|           19 |     3447 | 2024-03-18 | FURIA           | L   | 0.275      | -            | -                | -                | -         |    -0.26 | adamS, dav1g, JUST, mopoz, stadodo |
|           18 |     3462 | 2024-03-17 | ENCE            | L   | 0.269      | -            | -                | -                | -         |    -0.94 | adamS, dav1g, JUST, mopoz, stadodo |
|           17 |     3478 | 2024-03-17 | SAW             | L   | 0.267      | -            | -                | -                | -         |    -3.13 | adamS, dav1g, JUST, mopoz, stadodo |
|           16 |     3570 | 2024-03-13 | Sangal          | W   | 0.242      | 0.500        | 0.219 (0.026)    | 0.861 (0.104)    | -         |     4.41 | adamS, dav1g, JUST, mopoz, stadodo |
|           15 |     3624 | 2024-03-11 | B8              | L   | 0.228      | -            | -                | -                | -         |    -3.60 | adamS, dav1g, JUST, mopoz, stadodo |
|           14 |     3633 | 2024-03-11 | Apeks           | L   | 0.227      | -            | -                | -                | -         |    -5.25 | adamS, dav1g, JUST, mopoz, stadodo |
|           13 |     3745 | 2024-03-06 | 9 Pandas        | W   | 0.195      | 0.500        | 0.082 (0.008)    | 0.690 (0.067)    | -         |     2.35 | adamS, dav1g, JUST, mopoz, stadodo |
|           12 |     3781 | 2024-03-05 | FORZE           | W   | 0.189      | -            | -                | -                | -         |     1.62 | adamS, dav1g, JUST, mopoz, stadodo |
|           11 |     3787 | 2024-03-05 | Nemiga          | W   | 0.188      | 0.143        | 0.317 (0.009)    | -                | -         |     3.52 | adamS, dav1g, JUST, mopoz, stadodo |
|           10 |     3795 | 2024-03-05 | ex-Sprout       | W   | 0.188      | -            | -                | -                | -         |     0.23 | adamS, dav1g, JUST, mopoz, stadodo |
|            9 |     3835 | 2024-03-03 | The Chosen Few  | L   | 0.175      | -            | -                | -                | -         |    -5.02 | adamS, dav1g, JUST, mopoz, stadodo |
|            8 |     3890 | 2024-02-29 | Aurora          | L   | 0.155      | -            | -                | -                | -         |    -0.18 | adamS, dav1g, JUST, mopoz, stadodo |
|            7 |     3894 | 2024-02-29 | HAVU            | W   | 0.154      | -            | -                | -                | -         |     0.51 | adamS, dav1g, JUST, mopoz, stadodo |
|            6 |     3903 | 2024-02-28 | FORZE           | L   | 0.148      | -            | -                | -                | -         |    -3.51 | adamS, dav1g, JUST, mopoz, stadodo |
|            5 |     3907 | 2024-02-28 | kONO            | W   | 0.147      | -            | -                | -                | -         |     0.80 | adamS, dav1g, JUST, mopoz, stadodo |
|            4 |     4198 | 2024-02-16 | fnatic          | W   | 0.066      | -            | -                | -                | 1 (0.066) |     1.95 | adamS, dav1g, JUST, mopoz, stadodo |
|            3 |     4222 | 2024-02-15 | 9 Pandas        | W   | 0.060      | -            | -                | -                | 1 (0.060) |     0.71 | adamS, dav1g, JUST, mopoz, stadodo |
|            2 |     4251 | 2024-02-14 | 3DMAX           | W   | 0.055      | -            | -                | -                | 1 (0.055) |     1.67 | adamS, dav1g, JUST, mopoz, stadodo |
|            1 |     4265 | 2024-02-14 | Natus Vincere   | L   | 0.053      | -            | -                | -                | -         |    -0.01 | adamS, dav1g, JUST, mopoz, stadodo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,945.76)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.876 | $7,000.00      | $6,134.88       |
| 2024-06-09 |      0.828 | $12,000.00     | $9,930.56       |
| 2024-03-20 |      0.288 | $10,000.00     | $2,880.32       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
