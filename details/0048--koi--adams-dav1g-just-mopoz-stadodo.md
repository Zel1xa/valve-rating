### Roster Details<br />
Team Name: KOI<br />
Roster: adamS, dav1g, JUST, mopoz, stadodo<br />
Global Rank: [48](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1086.7<br />
<br />
Final Rank Value (1086.7) = Starting Rank Value (1085.8) + Head To Head Adjustments (0.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.448[<sup>1</sup>](#table2)
- Bounty Collected: 0.440[<sup>2</sup>](#table1)
- Opponent Network: 0.236[<sup>2</sup>](#table1)
- LAN Wins: 0.218[<sup>2</sup>](#table1)

The average of these factors is 0.335<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1085.8
- 400 + ( ( 0.335 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1085.8


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
|           45 |      161 | 2024-07-31 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -12.80 | adamS, dav1g, JUST, mopoz, stadodo |
|           44 |      323 | 2024-07-26 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.509 (0.255)    | 0 (0.000) |     5.64 | adamS, dav1g, JUST, mopoz, stadodo |
|           43 |      598 | 2024-07-18 | Monte           | L   | 1.000      | -            | -                | -                | -         |   -18.16 | adamS, dav1g, JUST, mopoz, stadodo |
|           42 |      732 | 2024-07-16 | Insilio         | W   | 1.000      | 0.500        | 0.023 (0.011)    | 0.561 (0.281)    | 0 (0.000) |     9.89 | adamS, dav1g, JUST, mopoz, stadodo |
|           41 |      998 | 2024-06-16 | 9z              | L   | 0.873      | -            | -                | -                | -         |    -3.28 | adamS, dav1g, JUST, mopoz, stadodo |
|           40 |     1048 | 2024-06-14 | RED Canids      | W   | 0.863      | 0.548        | 0.077 (0.037)    | 0.758 (0.358)    | 1 (0.863) |    16.41 | adamS, dav1g, JUST, mopoz, stadodo |
|           39 |     1053 | 2024-06-14 | Imperial        | W   | 0.862      | 0.548        | 0.236 (0.112)    | 0.685 (0.324)    | 1 (0.862) |    20.74 | adamS, dav1g, JUST, mopoz, stadodo |
|           38 |     1219 | 2024-06-09 | Sangal          | L   | 0.826      | -            | -                | -                | -         |    -8.59 | adamS, dav1g, JUST, mopoz, stadodo |
|           37 |     1407 | 2024-06-06 | SINNERS         | W   | 0.807      | 0.500        | 0.037 (0.015)    | 0.797 (0.321)    | 0 (0.000) |    10.98 | adamS, dav1g, JUST, mopoz, stadodo |
|           36 |     1468 | 2024-06-05 | 3DMAX           | W   | 0.800      | 0.500        | 0.506 (0.203)    | 1.000 (0.400)    | 0 (0.000) |    23.57 | adamS, dav1g, JUST, mopoz, stadodo |
|           35 |     1597 | 2024-06-01 | ENCE            | L   | 0.773      | -            | -                | -                | -         |    -3.48 | adamS, dav1g, JUST, mopoz, stadodo |
|           34 |     1603 | 2024-06-01 | Zero Tenacity   | L   | 0.772      | -            | -                | -                | -         |   -10.03 | adamS, dav1g, JUST, mopoz, stadodo |
|           33 |     2273 | 2024-05-09 | B8              | L   | 0.618      | -            | -                | -                | -         |    -9.96 | adamS, dav1g, JUST, mopoz, stadodo |
|           32 |     2436 | 2024-05-01 | Zero Tenacity   | L   | 0.565      | -            | -                | -                | -         |    -9.12 | adamS, dav1g, JUST, mopoz, stadodo |
|           31 |     2752 | 2024-04-18 | ex-Guild Eagles | L   | 0.480      | -            | -                | -                | -         |   -12.19 | adamS, dav1g, JUST, mopoz, stadodo |
|           30 |     2763 | 2024-04-18 | fnatic          | W   | 0.480      | 0.143        | 0.371 (0.025)    | -                | 0 (0.000) |    14.02 | adamS, dav1g, JUST, mopoz, stadodo |
|           29 |     2837 | 2024-04-16 | BLEED           | L   | 0.467      | -            | -                | -                | -         |    -8.95 | adamS, dav1g, JUST, mopoz, stadodo |
|           28 |     2968 | 2024-04-10 | RUSH B          | W   | 0.427      | 0.500        | -                | 0.386 (0.082)    | -         |     3.24 | adamS, dav1g, JUST, mopoz, stadodo |
|           27 |     3023 | 2024-04-09 | Aurora          | W   | 0.420      | 0.500        | 0.423 (0.089)    | 0.793 (0.167)    | -         |    12.76 | adamS, dav1g, JUST, mopoz, stadodo |
|           26 |     3029 | 2024-04-09 | Apeks           | L   | 0.420      | -            | -                | -                | -         |    -9.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           25 |     3056 | 2024-04-08 | GUN5            | W   | 0.413      | -            | -                | -                | -         |     0.29 | adamS, dav1g, JUST, mopoz, stadodo |
|           24 |     3057 | 2024-04-08 | fnatic          | L   | 0.413      | -            | -                | -                | -         |    -0.87 | adamS, dav1g, JUST, mopoz, stadodo |
|           23 |     3160 | 2024-04-04 | NOM             | W   | 0.386      | -            | -                | -                | -         |     0.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           22 |     3194 | 2024-04-03 | 9INE            | W   | 0.380      | -            | -                | -                | -         |     0.51 | adamS, dav1g, JUST, mopoz, stadodo |
|           21 |     3232 | 2024-04-02 | TSM             | W   | 0.374      | -            | -                | -                | -         |     1.15 | adamS, dav1g, JUST, mopoz, stadodo |
|           20 |     3299 | 2024-03-28 | EYEBALLERS      | L   | 0.340      | -            | -                | -                | -         |    -7.88 | adamS, dav1g, JUST, mopoz, stadodo |
|           19 |     3471 | 2024-03-18 | FURIA           | L   | 0.273      | -            | -                | -                | -         |    -0.25 | adamS, dav1g, JUST, mopoz, stadodo |
|           18 |     3486 | 2024-03-17 | ENCE            | L   | 0.268      | -            | -                | -                | -         |    -0.93 | adamS, dav1g, JUST, mopoz, stadodo |
|           17 |     3502 | 2024-03-17 | SAW             | L   | 0.266      | -            | -                | -                | -         |    -3.12 | adamS, dav1g, JUST, mopoz, stadodo |
|           16 |     3594 | 2024-03-13 | Sangal          | W   | 0.241      | 0.500        | 0.219 (0.026)    | 0.861 (0.104)    | -         |     4.42 | adamS, dav1g, JUST, mopoz, stadodo |
|           15 |     3648 | 2024-03-11 | B8              | L   | 0.227      | -            | -                | -                | -         |    -3.58 | adamS, dav1g, JUST, mopoz, stadodo |
|           14 |     3657 | 2024-03-11 | Apeks           | L   | 0.226      | -            | -                | -                | -         |    -5.24 | adamS, dav1g, JUST, mopoz, stadodo |
|           13 |     3769 | 2024-03-06 | 9 Pandas        | W   | 0.194      | 0.500        | 0.081 (0.008)    | 0.690 (0.067)    | -         |     2.33 | adamS, dav1g, JUST, mopoz, stadodo |
|           12 |     3805 | 2024-03-05 | FORZE           | W   | 0.188      | -            | -                | -                | -         |     1.60 | adamS, dav1g, JUST, mopoz, stadodo |
|           11 |     3811 | 2024-03-05 | Nemiga          | W   | 0.187      | 0.143        | 0.317 (0.008)    | -                | -         |     3.67 | adamS, dav1g, JUST, mopoz, stadodo |
|           10 |     3819 | 2024-03-05 | ex-Sprout       | W   | 0.187      | -            | -                | -                | -         |     0.23 | adamS, dav1g, JUST, mopoz, stadodo |
|            9 |     3859 | 2024-03-03 | The Chosen Few  | L   | 0.173      | -            | -                | -                | -         |    -4.99 | adamS, dav1g, JUST, mopoz, stadodo |
|            8 |     3914 | 2024-02-29 | Aurora          | L   | 0.154      | -            | -                | -                | -         |    -0.18 | adamS, dav1g, JUST, mopoz, stadodo |
|            7 |     3918 | 2024-02-29 | HAVU            | W   | 0.153      | -            | -                | -                | -         |     0.50 | adamS, dav1g, JUST, mopoz, stadodo |
|            6 |     3927 | 2024-02-28 | FORZE           | L   | 0.147      | -            | -                | -                | -         |    -3.49 | adamS, dav1g, JUST, mopoz, stadodo |
|            5 |     3931 | 2024-02-28 | kONO            | W   | 0.146      | -            | -                | -                | -         |     0.80 | adamS, dav1g, JUST, mopoz, stadodo |
|            4 |     4222 | 2024-02-16 | fnatic          | W   | 0.065      | -            | -                | -                | 1 (0.065) |     1.92 | adamS, dav1g, JUST, mopoz, stadodo |
|            3 |     4246 | 2024-02-15 | 9 Pandas        | W   | 0.058      | -            | -                | -                | 1 (0.058) |     0.70 | adamS, dav1g, JUST, mopoz, stadodo |
|            2 |     4275 | 2024-02-14 | 3DMAX           | W   | 0.054      | -            | -                | -                | 1 (0.054) |     1.64 | adamS, dav1g, JUST, mopoz, stadodo |
|            1 |     4289 | 2024-02-14 | Natus Vincere   | L   | 0.052      | -            | -                | -                | -         |    -0.01 | adamS, dav1g, JUST, mopoz, stadodo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,914.88)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.875 | $7,000.00      | $6,127.43       |
| 2024-06-09 |      0.826 | $12,000.00     | $9,917.78       |
| 2024-03-20 |      0.287 | $10,000.00     | $2,869.68       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
