### Roster Details<br />
Team Name: KOI<br />
Roster: adamS, dav1g, JUST, mopoz, stadodo<br />
Global Rank: [45](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1086.0<br />
<br />
Final Rank Value (1086.0) = Starting Rank Value (1086.4) + Head To Head Adjustments (-0.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.448[<sup>1</sup>](#table2)
- Bounty Collected: 0.441[<sup>2</sup>](#table1)
- Opponent Network: 0.235[<sup>2</sup>](#table1)
- LAN Wins: 0.220[<sup>2</sup>](#table1)

The average of these factors is 0.336<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1086.4
- 400 + ( ( 0.336 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1086.4


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
|           45 |      126 | 2024-07-31 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -12.84 | adamS, dav1g, JUST, mopoz, stadodo |
|           44 |      287 | 2024-07-26 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.510 (0.255)    | 0 (0.000) |     5.68 | adamS, dav1g, JUST, mopoz, stadodo |
|           43 |      560 | 2024-07-18 | Monte           | L   | 1.000      | -            | -                | -                | -         |   -18.20 | adamS, dav1g, JUST, mopoz, stadodo |
|           42 |      695 | 2024-07-16 | Insilio         | W   | 1.000      | 0.500        | 0.023 (0.011)    | 0.561 (0.281)    | 0 (0.000) |     9.86 | adamS, dav1g, JUST, mopoz, stadodo |
|           41 |      962 | 2024-06-16 | 9z              | L   | 0.878      | -            | -                | -                | -         |    -3.33 | adamS, dav1g, JUST, mopoz, stadodo |
|           40 |     1012 | 2024-06-14 | RED Canids      | W   | 0.868      | 0.548        | 0.077 (0.037)    | 0.743 (0.353)    | 1 (0.868) |    16.55 | adamS, dav1g, JUST, mopoz, stadodo |
|           39 |     1017 | 2024-06-14 | Imperial        | W   | 0.867      | 0.548        | 0.238 (0.113)    | 0.685 (0.325)    | 1 (0.867) |    20.92 | adamS, dav1g, JUST, mopoz, stadodo |
|           38 |     1183 | 2024-06-09 | Sangal          | L   | 0.831      | -            | -                | -                | -         |    -8.73 | adamS, dav1g, JUST, mopoz, stadodo |
|           37 |     1371 | 2024-06-06 | SINNERS         | W   | 0.812      | 0.500        | 0.037 (0.015)    | 0.758 (0.308)    | 0 (0.000) |    10.22 | adamS, dav1g, JUST, mopoz, stadodo |
|           36 |     1432 | 2024-06-05 | 3DMAX           | W   | 0.805      | 0.500        | 0.505 (0.203)    | 1.000 (0.403)    | 0 (0.000) |    23.68 | adamS, dav1g, JUST, mopoz, stadodo |
|           35 |     1561 | 2024-06-01 | ENCE            | L   | 0.778      | -            | -                | -                | -         |    -3.58 | adamS, dav1g, JUST, mopoz, stadodo |
|           34 |     1567 | 2024-06-01 | Zero Tenacity   | L   | 0.777      | -            | -                | -                | -         |   -10.08 | adamS, dav1g, JUST, mopoz, stadodo |
|           33 |     2237 | 2024-05-09 | B8              | L   | 0.623      | -            | -                | -                | -         |   -10.07 | adamS, dav1g, JUST, mopoz, stadodo |
|           32 |     2400 | 2024-05-01 | Zero Tenacity   | L   | 0.570      | -            | -                | -                | -         |    -9.30 | adamS, dav1g, JUST, mopoz, stadodo |
|           31 |     2715 | 2024-04-18 | ex-Guild Eagles | L   | 0.485      | -            | -                | -                | -         |   -12.27 | adamS, dav1g, JUST, mopoz, stadodo |
|           30 |     2726 | 2024-04-18 | fnatic          | W   | 0.485      | 0.143        | 0.371 (0.026)    | -                | 0 (0.000) |    14.15 | adamS, dav1g, JUST, mopoz, stadodo |
|           29 |     2800 | 2024-04-16 | BLEED           | L   | 0.472      | -            | -                | -                | -         |    -9.05 | adamS, dav1g, JUST, mopoz, stadodo |
|           28 |     2931 | 2024-04-10 | RUSH B          | W   | 0.432      | 0.500        | -                | 0.386 (0.083)    | -         |     3.09 | adamS, dav1g, JUST, mopoz, stadodo |
|           27 |     2986 | 2024-04-09 | Aurora          | W   | 0.425      | 0.500        | 0.424 (0.090)    | 0.794 (0.169)    | -         |    12.90 | adamS, dav1g, JUST, mopoz, stadodo |
|           26 |     2992 | 2024-04-09 | Apeks           | L   | 0.424      | -            | -                | -                | -         |    -9.54 | adamS, dav1g, JUST, mopoz, stadodo |
|           25 |     3019 | 2024-04-08 | GUN5            | W   | 0.418      | -            | -                | -                | -         |     0.29 | adamS, dav1g, JUST, mopoz, stadodo |
|           24 |     3020 | 2024-04-08 | fnatic          | L   | 0.418      | -            | -                | -                | -         |    -0.89 | adamS, dav1g, JUST, mopoz, stadodo |
|           23 |     3123 | 2024-04-04 | NOM             | W   | 0.391      | -            | -                | -                | -         |     0.48 | adamS, dav1g, JUST, mopoz, stadodo |
|           22 |     3157 | 2024-04-03 | 9INE            | W   | 0.385      | -            | -                | -                | -         |     0.52 | adamS, dav1g, JUST, mopoz, stadodo |
|           21 |     3195 | 2024-04-02 | TSM             | W   | 0.379      | -            | -                | -                | -         |     1.17 | adamS, dav1g, JUST, mopoz, stadodo |
|           20 |     3262 | 2024-03-28 | EYEBALLERS      | L   | 0.344      | -            | -                | -                | -         |    -7.99 | adamS, dav1g, JUST, mopoz, stadodo |
|           19 |     3434 | 2024-03-18 | FURIA           | L   | 0.278      | -            | -                | -                | -         |    -0.26 | adamS, dav1g, JUST, mopoz, stadodo |
|           18 |     3449 | 2024-03-17 | ENCE            | L   | 0.273      | -            | -                | -                | -         |    -0.96 | adamS, dav1g, JUST, mopoz, stadodo |
|           17 |     3465 | 2024-03-17 | SAW             | L   | 0.271      | -            | -                | -                | -         |    -3.18 | adamS, dav1g, JUST, mopoz, stadodo |
|           16 |     3557 | 2024-03-13 | Sangal          | W   | 0.246      | 0.500        | 0.219 (0.027)    | 0.862 (0.106)    | -         |     4.46 | adamS, dav1g, JUST, mopoz, stadodo |
|           15 |     3610 | 2024-03-11 | B8              | L   | 0.232      | -            | -                | -                | -         |    -3.67 | adamS, dav1g, JUST, mopoz, stadodo |
|           14 |     3619 | 2024-03-11 | Apeks           | L   | 0.231      | -            | -                | -                | -         |    -5.34 | adamS, dav1g, JUST, mopoz, stadodo |
|           13 |     3731 | 2024-03-06 | 9 Pandas        | W   | 0.199      | 0.500        | 0.082 (0.008)    | 0.691 (0.069)    | -         |     2.38 | adamS, dav1g, JUST, mopoz, stadodo |
|           12 |     3767 | 2024-03-05 | FORZE           | W   | 0.192      | -            | -                | -                | -         |     1.65 | adamS, dav1g, JUST, mopoz, stadodo |
|           11 |     3773 | 2024-03-05 | Nemiga          | W   | 0.192      | 0.143        | 0.318 (0.009)    | -                | -         |     3.59 | adamS, dav1g, JUST, mopoz, stadodo |
|           10 |     3781 | 2024-03-05 | ex-Sprout       | W   | 0.192      | -            | -                | -                | -         |     0.24 | adamS, dav1g, JUST, mopoz, stadodo |
|            9 |     3821 | 2024-03-03 | The Chosen Few  | L   | 0.178      | -            | -                | -                | -         |    -5.13 | adamS, dav1g, JUST, mopoz, stadodo |
|            8 |     3876 | 2024-02-29 | Aurora          | L   | 0.159      | -            | -                | -                | -         |    -0.19 | adamS, dav1g, JUST, mopoz, stadodo |
|            7 |     3880 | 2024-02-29 | HAVU            | W   | 0.158      | -            | -                | -                | -         |     0.52 | adamS, dav1g, JUST, mopoz, stadodo |
|            6 |     3889 | 2024-02-28 | FORZE           | L   | 0.152      | -            | -                | -                | -         |    -3.60 | adamS, dav1g, JUST, mopoz, stadodo |
|            5 |     3893 | 2024-02-28 | kONO            | W   | 0.151      | -            | -                | -                | -         |     0.82 | adamS, dav1g, JUST, mopoz, stadodo |
|            4 |     4183 | 2024-02-16 | fnatic          | W   | 0.070      | -            | -                | -                | 1 (0.070) |     2.06 | adamS, dav1g, JUST, mopoz, stadodo |
|            3 |     4207 | 2024-02-15 | 9 Pandas        | W   | 0.063      | -            | -                | -                | 1 (0.063) |     0.76 | adamS, dav1g, JUST, mopoz, stadodo |
|            2 |     4236 | 2024-02-14 | 3DMAX           | W   | 0.059      | -            | -                | -                | 1 (0.059) |     1.78 | adamS, dav1g, JUST, mopoz, stadodo |
|            1 |     4250 | 2024-02-14 | Natus Vincere   | L   | 0.057      | -            | -                | -                | -         |    -0.01 | adamS, dav1g, JUST, mopoz, stadodo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,055.19)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.880 | $7,000.00      | $6,161.30       |
| 2024-06-09 |      0.831 | $12,000.00     | $9,975.83       |
| 2024-03-20 |      0.292 | $10,000.00     | $2,918.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
