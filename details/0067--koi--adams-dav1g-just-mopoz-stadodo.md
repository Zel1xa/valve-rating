### Roster Details<br />
Team Name: KOI<br />
Roster: adamS, dav1g, JUST, mopoz, stadodo<br />
Global Rank: [67](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [47]( ../standings_europe.md)<br />
<br />
Final Rank Value:  965.6<br />
<br />
Final Rank Value (965.6) = Starting Rank Value (934.3) + Head To Head Adjustments (31.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.418[<sup>1</sup>](#table2)
- Bounty Collected: 0.418[<sup>2</sup>](#table1)
- Opponent Network: 0.174[<sup>2</sup>](#table1)
- LAN Wins: 0.028[<sup>2</sup>](#table1)

The average of these factors is 0.259<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 934.3
- 400 + ( ( 0.259 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 934.3


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
|           43 |       40 | 2024-07-31 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |    -9.56 | adamS, dav1g, JUST, mopoz, stadodo |
|           42 |      202 | 2024-07-26 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.513 (0.256)    | 0 (0.000) |     9.68 | adamS, dav1g, JUST, mopoz, stadodo |
|           41 |      484 | 2024-07-18 | Monte           | L   | 1.000      | -            | -                | -                | -         |   -12.84 | adamS, dav1g, JUST, mopoz, stadodo |
|           40 |      621 | 2024-07-16 | Insilio         | W   | 1.000      | 0.500        | 0.023 (0.012)    | 0.554 (0.277)    | 0 (0.000) |    15.64 | adamS, dav1g, JUST, mopoz, stadodo |
|           39 |     1107 | 2024-06-09 | Sangal          | L   | 0.848      | -            | -                | -                | -         |    -6.23 | adamS, dav1g, JUST, mopoz, stadodo |
|           38 |     1306 | 2024-06-06 | SINNERS         | W   | 0.828      | 0.500        | 0.038 (0.016)    | 0.768 (0.318)    | 0 (0.000) |    14.41 | adamS, dav1g, JUST, mopoz, stadodo |
|           37 |     1370 | 2024-06-05 | 3DMAX           | W   | 0.821      | 0.500        | 0.505 (0.207)    | 1.000 (0.411)    | 0 (0.000) |    24.92 | adamS, dav1g, JUST, mopoz, stadodo |
|           36 |     1500 | 2024-06-01 | ENCE            | L   | 0.794      | -            | -                | -                | -         |    -2.10 | adamS, dav1g, JUST, mopoz, stadodo |
|           35 |     1506 | 2024-06-01 | Zero Tenacity   | L   | 0.794      | -            | -                | -                | -         |    -7.04 | adamS, dav1g, JUST, mopoz, stadodo |
|           34 |     2213 | 2024-05-09 | B8              | L   | 0.639      | -            | -                | -                | -         |    -7.11 | adamS, dav1g, JUST, mopoz, stadodo |
|           33 |     2380 | 2024-05-01 | Zero Tenacity   | L   | 0.586      | -            | -                | -                | -         |    -6.53 | adamS, dav1g, JUST, mopoz, stadodo |
|           32 |     2705 | 2024-04-18 | ex-Guild Eagles | L   | 0.501      | -            | -                | -                | -         |   -10.40 | adamS, dav1g, JUST, mopoz, stadodo |
|           31 |     2716 | 2024-04-18 | fnatic          | W   | 0.501      | 0.143        | 0.292 (0.021)    | 0.529 (0.038)    | 0 (0.000) |    14.24 | adamS, dav1g, JUST, mopoz, stadodo |
|           30 |     2791 | 2024-04-16 | BLEED           | L   | 0.488      | -            | -                | -                | -         |    -6.50 | adamS, dav1g, JUST, mopoz, stadodo |
|           29 |     2924 | 2024-04-10 | RUSH B          | W   | 0.448      | 0.500        | 0.017 (0.004)    | 0.308 (0.069)    | 0 (0.000) |     5.35 | adamS, dav1g, JUST, mopoz, stadodo |
|           28 |     2979 | 2024-04-09 | Aurora          | W   | 0.442      | 0.500        | 0.432 (0.095)    | 0.798 (0.176)    | 0 (0.000) |    13.67 | adamS, dav1g, JUST, mopoz, stadodo |
|           27 |     2985 | 2024-04-09 | Apeks           | L   | 0.441      | -            | -                | -                | -         |    -7.31 | adamS, dav1g, JUST, mopoz, stadodo |
|           26 |     3012 | 2024-04-08 | GUN5            | W   | 0.434      | -            | -                | -                | -         |     0.62 | adamS, dav1g, JUST, mopoz, stadodo |
|           25 |     3013 | 2024-04-08 | fnatic          | L   | 0.434      | -            | -                | -                | -         |    -1.19 | adamS, dav1g, JUST, mopoz, stadodo |
|           24 |     3116 | 2024-04-04 | NOM             | W   | 0.408      | -            | -                | -                | -         |     1.02 | adamS, dav1g, JUST, mopoz, stadodo |
|           23 |     3152 | 2024-04-03 | 9INE            | W   | 0.402      | -            | -                | -                | -         |     1.10 | adamS, dav1g, JUST, mopoz, stadodo |
|           22 |     3196 | 2024-04-02 | TSM             | W   | 0.395      | -            | -                | -                | -         |     2.39 | adamS, dav1g, JUST, mopoz, stadodo |
|           21 |     3263 | 2024-03-28 | EYEBALLERS      | L   | 0.361      | -            | -                | -                | -         |    -6.32 | adamS, dav1g, JUST, mopoz, stadodo |
|           20 |     3440 | 2024-03-18 | FURIA           | L   | 0.295      | -            | -                | -                | -         |    -0.12 | adamS, dav1g, JUST, mopoz, stadodo |
|           19 |     3455 | 2024-03-17 | ENCE            | L   | 0.289      | -            | -                | -                | -         |    -0.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           18 |     3471 | 2024-03-17 | SAW             | L   | 0.287      | -            | -                | -                | -         |    -1.81 | adamS, dav1g, JUST, mopoz, stadodo |
|           17 |     3568 | 2024-03-13 | Sangal          | W   | 0.262      | 0.500        | 0.221 (0.029)    | 0.823 (0.108)    | -         |     6.12 | adamS, dav1g, JUST, mopoz, stadodo |
|           16 |     3622 | 2024-03-11 | B8              | L   | 0.249      | -            | -                | -                | -         |    -2.34 | adamS, dav1g, JUST, mopoz, stadodo |
|           15 |     3631 | 2024-03-11 | Apeks           | L   | 0.247      | -            | -                | -                | -         |    -4.14 | adamS, dav1g, JUST, mopoz, stadodo |
|           14 |     3744 | 2024-03-06 | 9 Pandas        | W   | 0.215      | 0.500        | 0.083 (0.009)    | 0.578 (0.062)    | -         |     3.98 | adamS, dav1g, JUST, mopoz, stadodo |
|           13 |     3780 | 2024-03-05 | FORZE           | W   | 0.209      | -            | -                | -                | -         |     3.12 | adamS, dav1g, JUST, mopoz, stadodo |
|           12 |     3786 | 2024-03-05 | Nemiga          | W   | 0.208      | 0.143        | 0.324 (0.010)    | 0.697 (0.021)    | -         |     5.14 | adamS, dav1g, JUST, mopoz, stadodo |
|           11 |     3799 | 2024-03-05 | ex-Sprout       | W   | 0.208      | -            | -                | -                | -         |     0.61 | adamS, dav1g, JUST, mopoz, stadodo |
|           10 |     3839 | 2024-03-03 | The Chosen Few  | L   | 0.195      | -            | -                | -                | -         |    -5.02 | adamS, dav1g, JUST, mopoz, stadodo |
|            9 |     3895 | 2024-02-29 | Aurora          | L   | 0.175      | -            | -                | -                | -         |    -0.08 | adamS, dav1g, JUST, mopoz, stadodo |
|            8 |     3899 | 2024-02-29 | HAVU            | W   | 0.174      | -            | -                | -                | -         |     1.20 | adamS, dav1g, JUST, mopoz, stadodo |
|            7 |     3908 | 2024-02-28 | FORZE           | L   | 0.168      | -            | -                | -                | -         |    -2.92 | adamS, dav1g, JUST, mopoz, stadodo |
|            6 |     3913 | 2024-02-28 | kONO            | W   | 0.167      | -            | -                | -                | -         |     1.79 | adamS, dav1g, JUST, mopoz, stadodo |
|            5 |     4212 | 2024-02-16 | fnatic          | W   | 0.086      | -            | -                | -                | 1 (0.086) |     2.51 | adamS, dav1g, JUST, mopoz, stadodo |
|            4 |     4236 | 2024-02-15 | 9 Pandas        | W   | 0.080      | -            | -                | -                | 1 (0.080) |     1.49 | adamS, dav1g, JUST, mopoz, stadodo |
|            3 |     4265 | 2024-02-14 | 3DMAX           | W   | 0.075      | 0.143        | 0.505 (0.005)    | -                | 1 (0.075) |     2.33 | adamS, dav1g, JUST, mopoz, stadodo |
|            2 |     4279 | 2024-02-14 | Natus Vincere   | L   | 0.073      | -            | -                | -                | -         |    -0.01 | adamS, dav1g, JUST, mopoz, stadodo |
|            1 |     4448 | 2024-02-03 | SAW             | L   | 0.001      | -            | -                | -                | -         |    -0.00 | adamS, dav1g, JUST, mopoz, stadodo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,254.44)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.848 | $12,000.00     | $10,172.50      |
| 2024-03-20 |      0.308 | $10,000.00     | $3,081.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
