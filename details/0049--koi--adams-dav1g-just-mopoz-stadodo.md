### Roster Details<br />
Team Name: KOI<br />
Roster: adamS, dav1g, JUST, mopoz, stadodo<br />
Global Rank: [49](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [36]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1085.5<br />
<br />
Final Rank Value (1085.5) = Starting Rank Value (1083.5) + Head To Head Adjustments (2.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.447[<sup>1</sup>](#table2)
- Bounty Collected: 0.439[<sup>2</sup>](#table1)
- Opponent Network: 0.232[<sup>2</sup>](#table1)
- LAN Wins: 0.215[<sup>2</sup>](#table1)

The average of these factors is 0.333<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1083.5
- 400 + ( ( 0.333 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1083.5


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
|           45 |      186 | 2024-07-31 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |   -12.70 | adamS, dav1g, JUST, mopoz, stadodo |
|           44 |      348 | 2024-07-26 | EYEBALLERS      | W   | 1.000      | 0.500        | -                | 0.500 (0.250)    | 0 (0.000) |     5.71 | adamS, dav1g, JUST, mopoz, stadodo |
|           43 |      623 | 2024-07-18 | Monte           | L   | 1.000      | -            | -                | -                | -         |   -18.07 | adamS, dav1g, JUST, mopoz, stadodo |
|           42 |      757 | 2024-07-16 | Insilio         | W   | 1.000      | 0.500        | 0.023 (0.011)    | 0.553 (0.276)    | 0 (0.000) |    10.03 | adamS, dav1g, JUST, mopoz, stadodo |
|           41 |     1023 | 2024-06-16 | 9z              | L   | 0.866      | -            | -                | -                | -         |    -3.25 | adamS, dav1g, JUST, mopoz, stadodo |
|           40 |     1073 | 2024-06-14 | RED Canids      | W   | 0.856      | 0.548        | 0.077 (0.036)    | 0.748 (0.351)    | 1 (0.856) |    16.25 | adamS, dav1g, JUST, mopoz, stadodo |
|           39 |     1078 | 2024-06-14 | Imperial        | W   | 0.855      | 0.548        | 0.235 (0.110)    | 0.674 (0.316)    | 1 (0.855) |    20.52 | adamS, dav1g, JUST, mopoz, stadodo |
|           38 |     1244 | 2024-06-09 | Sangal          | L   | 0.820      | -            | -                | -                | -         |    -8.41 | adamS, dav1g, JUST, mopoz, stadodo |
|           37 |     1432 | 2024-06-06 | SINNERS         | W   | 0.800      | 0.500        | 0.037 (0.015)    | 0.809 (0.324)    | 0 (0.000) |    11.06 | adamS, dav1g, JUST, mopoz, stadodo |
|           36 |     1493 | 2024-06-05 | 3DMAX           | W   | 0.793      | 0.500        | 0.508 (0.202)    | 1.000 (0.397)    | 0 (0.000) |    23.42 | adamS, dav1g, JUST, mopoz, stadodo |
|           35 |     1622 | 2024-06-01 | ENCE            | L   | 0.766      | -            | -                | -                | -         |    -3.29 | adamS, dav1g, JUST, mopoz, stadodo |
|           34 |     1628 | 2024-06-01 | Zero Tenacity   | L   | 0.766      | -            | -                | -                | -         |    -9.89 | adamS, dav1g, JUST, mopoz, stadodo |
|           33 |     2298 | 2024-05-09 | B8              | L   | 0.611      | -            | -                | -                | -         |    -9.79 | adamS, dav1g, JUST, mopoz, stadodo |
|           32 |     2461 | 2024-05-01 | Zero Tenacity   | L   | 0.558      | -            | -                | -                | -         |    -8.90 | adamS, dav1g, JUST, mopoz, stadodo |
|           31 |     2777 | 2024-04-18 | ex-Guild Eagles | L   | 0.473      | -            | -                | -                | -         |   -12.00 | adamS, dav1g, JUST, mopoz, stadodo |
|           30 |     2788 | 2024-04-18 | fnatic          | W   | 0.473      | 0.143        | 0.371 (0.025)    | -                | 0 (0.000) |    13.83 | adamS, dav1g, JUST, mopoz, stadodo |
|           29 |     2862 | 2024-04-16 | BLEED           | L   | 0.460      | -            | -                | -                | -         |    -8.83 | adamS, dav1g, JUST, mopoz, stadodo |
|           28 |     2993 | 2024-04-10 | RUSH B          | W   | 0.420      | 0.500        | -                | 0.380 (0.080)    | -         |     3.22 | adamS, dav1g, JUST, mopoz, stadodo |
|           27 |     3048 | 2024-04-09 | Aurora          | W   | 0.414      | 0.500        | 0.422 (0.087)    | 0.779 (0.161)    | -         |    12.57 | adamS, dav1g, JUST, mopoz, stadodo |
|           26 |     3054 | 2024-04-09 | Apeks           | L   | 0.413      | -            | -                | -                | -         |    -9.33 | adamS, dav1g, JUST, mopoz, stadodo |
|           25 |     3081 | 2024-04-08 | GUN5            | W   | 0.406      | -            | -                | -                | -         |     0.29 | adamS, dav1g, JUST, mopoz, stadodo |
|           24 |     3082 | 2024-04-08 | fnatic          | L   | 0.406      | -            | -                | -                | -         |    -0.85 | adamS, dav1g, JUST, mopoz, stadodo |
|           23 |     3185 | 2024-04-04 | NOM             | W   | 0.380      | -            | -                | -                | -         |     0.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           22 |     3219 | 2024-04-03 | 9INE            | W   | 0.374      | -            | -                | -                | -         |     0.51 | adamS, dav1g, JUST, mopoz, stadodo |
|           21 |     3257 | 2024-04-02 | TSM             | W   | 0.367      | -            | -                | -                | -         |     1.14 | adamS, dav1g, JUST, mopoz, stadodo |
|           20 |     3324 | 2024-03-28 | EYEBALLERS      | L   | 0.333      | -            | -                | -                | -         |    -7.69 | adamS, dav1g, JUST, mopoz, stadodo |
|           19 |     3496 | 2024-03-18 | FURIA           | L   | 0.267      | -            | -                | -                | -         |    -0.24 | adamS, dav1g, JUST, mopoz, stadodo |
|           18 |     3511 | 2024-03-17 | ENCE            | L   | 0.261      | -            | -                | -                | -         |    -0.86 | adamS, dav1g, JUST, mopoz, stadodo |
|           17 |     3527 | 2024-03-17 | SAW             | L   | 0.259      | -            | -                | -                | -         |    -3.05 | adamS, dav1g, JUST, mopoz, stadodo |
|           16 |     3619 | 2024-03-13 | Sangal          | W   | 0.234      | 0.500        | 0.219 (0.026)    | 0.866 (0.101)    | -         |     4.33 | adamS, dav1g, JUST, mopoz, stadodo |
|           15 |     3673 | 2024-03-11 | B8              | L   | 0.221      | -            | -                | -                | -         |    -3.45 | adamS, dav1g, JUST, mopoz, stadodo |
|           14 |     3682 | 2024-03-11 | Apeks           | L   | 0.219      | -            | -                | -                | -         |    -5.08 | adamS, dav1g, JUST, mopoz, stadodo |
|           13 |     3794 | 2024-03-06 | 9 Pandas        | W   | 0.187      | 0.500        | 0.081 (0.008)    | 0.718 (0.067)    | -         |     2.25 | adamS, dav1g, JUST, mopoz, stadodo |
|           12 |     3830 | 2024-03-05 | FORZE           | W   | 0.181      | -            | -                | -                | -         |     1.55 | adamS, dav1g, JUST, mopoz, stadodo |
|           11 |     3836 | 2024-03-05 | Nemiga          | W   | 0.180      | 0.143        | 0.316 (0.008)    | -                | -         |     3.54 | adamS, dav1g, JUST, mopoz, stadodo |
|           10 |     3844 | 2024-03-05 | ex-Sprout       | W   | 0.180      | -            | -                | -                | -         |     0.22 | adamS, dav1g, JUST, mopoz, stadodo |
|            9 |     3884 | 2024-03-03 | The Chosen Few  | L   | 0.167      | -            | -                | -                | -         |    -4.79 | adamS, dav1g, JUST, mopoz, stadodo |
|            8 |     3939 | 2024-02-29 | Aurora          | L   | 0.147      | -            | -                | -                | -         |    -0.17 | adamS, dav1g, JUST, mopoz, stadodo |
|            7 |     3943 | 2024-02-29 | HAVU            | W   | 0.146      | -            | -                | -                | -         |     0.48 | adamS, dav1g, JUST, mopoz, stadodo |
|            6 |     3952 | 2024-02-28 | FORZE           | L   | 0.140      | -            | -                | -                | -         |    -3.31 | adamS, dav1g, JUST, mopoz, stadodo |
|            5 |     3956 | 2024-02-28 | kONO            | W   | 0.139      | -            | -                | -                | -         |     0.77 | adamS, dav1g, JUST, mopoz, stadodo |
|            4 |     4247 | 2024-02-16 | fnatic          | W   | 0.058      | -            | -                | -                | 1 (0.058) |     1.72 | adamS, dav1g, JUST, mopoz, stadodo |
|            3 |     4271 | 2024-02-15 | 9 Pandas        | W   | 0.052      | -            | -                | -                | 1 (0.052) |     0.62 | adamS, dav1g, JUST, mopoz, stadodo |
|            2 |     4300 | 2024-02-14 | 3DMAX           | W   | 0.047      | -            | -                | -                | 1 (0.047) |     1.43 | adamS, dav1g, JUST, mopoz, stadodo |
|            1 |     4314 | 2024-02-14 | Natus Vincere   | L   | 0.045      | -            | -                | -                | -         |    -0.01 | adamS, dav1g, JUST, mopoz, stadodo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,716.85)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.869 | $7,000.00      | $6,079.63       |
| 2024-06-09 |      0.820 | $12,000.00     | $9,835.83       |
| 2024-03-20 |      0.280 | $10,000.00     | $2,801.39       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
