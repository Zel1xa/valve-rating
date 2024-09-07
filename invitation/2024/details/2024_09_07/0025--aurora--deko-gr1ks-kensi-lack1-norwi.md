### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, gr1ks, KENSI, Lack1, Norwi<br />
Global Rank: [25](../../standings_global_2024_09_07.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_07.md)<br />
Regional Rank: [19]( ../../standings_europe_2024_09_07.md)<br />
<br />
Final Rank Value:  1221.0<br />
<br />
Final Rank Value (1221.0) = Starting Rank Value (1433.9) + Head To Head Adjustments (-212.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.652[<sup>1</sup>](#table2)
- Bounty Collected: 0.476[<sup>2</sup>](#table1)
- Opponent Network: 0.276[<sup>2</sup>](#table1)
- LAN Wins: 0.711[<sup>2</sup>](#table1)

The average of these factors is 0.529<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1433.9
- 400 + ( ( 0.529 - 0.000 ) / ( 0.818 - 0.000 ) ) * 1600 = 1433.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           82 |      195 | 2024-08-30 | Monte              | L   | 1.000      | -            | -                | -                | -         |   -22.36 | deko, gr1ks, KENSI, Lack1, Norwi      |
|           81 |      201 | 2024-08-30 | Sashi              | W   | 1.000      | 0.143        | 0.152 (0.022)    | -                | -         |     8.70 | deko, gr1ks, KENSI, Lack1, Norwi      |
|           80 |      229 | 2024-08-29 | GenOne             | W   | 1.000      | -            | -                | -                | -         |     0.57 | deko, gr1ks, KENSI, Lack1, Norwi      |
|           79 |      243 | 2024-08-29 | GamerLegion        | L   | 1.000      | -            | -                | -                | -         |   -22.12 | deko, gr1ks, KENSI, Lack1, Norwi      |
|           78 |      436 | 2024-08-26 | FURIA              | L   | 1.000      | -            | -                | -                | -         |    -5.23 | clax, deko, KENSI, Lack1, Norwi       |
|           77 |      473 | 2024-08-25 | Eternal Fire       | L   | 1.000      | -            | -                | -                | -         |    -2.01 | clax, deko, KENSI, Lack1, Norwi       |
|           76 |      695 | 2024-08-19 | Sashi              | L   | 1.000      | -            | -                | -                | -         |   -23.30 | clax, deko, KENSI, Lack1, Norwi       |
|           75 |      890 | 2024-08-12 | TSM                | L   | 1.000      | -            | -                | -                | -         |   -25.64 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1034 | 2024-08-07 | Space              | W   | 0.995      | 0.500        | -                | 0.479 (0.238)    | -         |     1.77 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1107 | 2024-08-05 | ARCRED             | L   | 0.982      | -            | -                | -                | -         |   -27.53 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1139 | 2024-08-04 | Nemiga             | L   | 0.975      | -            | -                | -                | -         |   -24.07 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1417 | 2024-07-28 | 3DMAX              | L   | 0.927      | -            | -                | -                | -         |   -11.28 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1465 | 2024-07-26 | The MongolZ        | L   | 0.914      | -            | -                | -                | -         |    -4.82 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1470 | 2024-07-26 | BLEED              | W   | 0.913      | 0.650        | 0.095 (0.056)    | 0.558 (0.332)    | 1 (0.913) |     8.32 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1496 | 2024-07-25 | True Rippers       | W   | 0.908      | -            | -                | -                | 1 (0.908) |     0.60 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1508 | 2024-07-25 | ENCE               | W   | 0.906      | 0.650        | 0.131 (0.077)    | 0.342 (0.202)    | 1 (0.906) |     9.30 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1543 | 2024-07-24 | PARIVISION         | W   | 0.900      | 0.650        | 0.045 (0.027)    | 0.754 (0.441)    | 1 (0.900) |     4.68 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1732 | 2024-07-18 | B8                 | W   | 0.863      | 0.500        | 0.176 (0.076)    | 1.000 (0.431)    | -         |     5.69 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1862 | 2024-07-16 | Qiang              | W   | 0.849      | 0.500        | -                | 0.403 (0.171)    | -         |     2.42 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     2145 | 2024-06-16 | Complexity         | L   | 0.647      | -            | -                | -                | -         |    -5.77 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     2211 | 2024-06-14 | The MongolZ        | W   | 0.635      | 0.500        | 0.864 (0.274)    | 0.641 (0.204)    | 1 (0.635) |    18.67 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     2221 | 2024-06-14 | Falcons            | W   | 0.634      | 0.500        | 0.296 (0.094)    | -                | 1 (0.634) |    14.73 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     2321 | 2024-06-10 | 9 Pandas           | W   | 0.608      | -            | -                | -                | -         |     3.79 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     2326 | 2024-06-10 | Monte              | W   | 0.608      | -            | -                | -                | -         |     2.66 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     2330 | 2024-06-10 | SAW                | L   | 0.607      | -            | -                | -                | -         |    -6.63 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     2355 | 2024-06-09 | Monte              | L   | 0.602      | -            | -                | -                | -         |   -16.46 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     2362 | 2024-06-09 | PARIVISION         | W   | 0.602      | -            | -                | -                | -         |     3.92 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     2370 | 2024-06-09 | RUSH B             | L   | 0.601      | -            | -                | -                | -         |   -17.65 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     2378 | 2024-06-09 | 3DMAX              | L   | 0.601      | -            | -                | -                | -         |    -4.81 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     2386 | 2024-06-09 | SINNERS            | L   | 0.600      | -            | -                | -                | -         |   -16.18 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     2473 | 2024-06-07 | Sangal             | L   | 0.589      | -            | -                | -                | -         |   -12.32 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     2488 | 2024-06-07 | Verdant            | W   | 0.588      | -            | -                | -                | -         |     0.98 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     2492 | 2024-06-07 | Qiang              | W   | 0.588      | -            | -                | -                | -         |     1.20 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     2539 | 2024-06-06 | RUSH B             | W   | 0.582      | -            | -                | -                | -         |     0.94 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2601 | 2024-06-05 | PARIVISION         | W   | 0.576      | 0.500        | -                | 0.754 (0.217)    | -         |     2.91 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2649 | 2024-06-04 | 3DMAX              | L   | 0.569      | -            | -                | -                | -         |    -4.20 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2714 | 2024-06-01 | BLEED              | L   | 0.552      | -            | -                | -                | -         |   -12.59 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2739 | 2024-06-01 | Lynn Vision        | W   | 0.548      | 0.500        | 0.073 (0.020)    | -                | 1 (0.548) |     1.15 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2748 | 2024-05-31 | Chinggis Warriors  | W   | 0.546      | -            | -                | -                | 1 (0.546) |     1.04 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2823 | 2024-05-29 | The MongolZ        | L   | 0.527      | -            | -                | -                | -         |    -1.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2846 | 2024-05-28 | Lynn Vision        | W   | 0.520      | -            | -                | -                | 1 (0.520) |     1.02 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     3017 | 2024-05-21 | Astralis           | L   | 0.474      | -            | -                | -                | -         |    -4.12 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     3148 | 2024-05-17 | SAW                | W   | 0.447      | 0.769        | 0.328 (0.113)    | 0.771 (0.265)    | -         |     9.59 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     3163 | 2024-05-16 | PARIVISION         | W   | 0.443      | 0.769        | -                | 0.754 (0.257)    | -         |     2.10 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     3171 | 2024-05-16 | MIBR               | L   | 0.442      | -            | -                | -                | -         |    -6.37 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     3185 | 2024-05-16 | SAW                | L   | 0.440      | -            | -                | -                | -         |    -4.51 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     3235 | 2024-05-15 | Spirit             | L   | 0.434      | -            | -                | -                | -         |    -0.53 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     3378 | 2024-05-10 | MOUZ NXT           | L   | 0.403      | -            | -                | -                | -         |   -11.56 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     3635 | 2024-04-28 | MIBR               | L   | 0.320      | -            | -                | -                | -         |    -4.89 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     3637 | 2024-04-27 | Rebels             | W   | 0.319      | -            | -                | -                | 1 (0.319) |     0.67 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     3663 | 2024-04-27 | Party Astronauts   | W   | 0.313      | -            | -                | -                | -         |     0.47 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     3688 | 2024-04-25 | Apeks              | L   | 0.306      | -            | -                | -                | -         |    -9.36 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     3692 | 2024-04-25 | Party Astronauts   | W   | 0.305      | -            | -                | -                | -         |     0.44 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     3896 | 2024-04-18 | RUBY               | L   | 0.255      | -            | -                | -                | -         |    -7.67 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     4008 | 2024-04-14 | OG                 | W   | 0.228      | -            | -                | -                | -         |     0.54 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     4021 | 2024-04-13 | BetBoom            | W   | 0.222      | 0.684        | 0.230 (0.035)    | -                | -         |     1.88 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     4033 | 2024-04-12 | AMKAL              | W   | 0.216      | -            | -                | -                | -         |     0.98 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     4056 | 2024-04-11 | BetBoom            | W   | 0.209      | -            | -                | -                | -         |     1.80 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     4063 | 2024-04-11 | Apeks              | W   | 0.209      | -            | -                | -                | -         |     0.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           23 |     4068 | 2024-04-11 | FORZE              | W   | 0.208      | -            | -                | -                | -         |     0.20 | deko, KENSI, Lack1, Norwi, r3salt     |
|           22 |     4097 | 2024-04-10 | PARIVISION         | W   | 0.203      | -            | -                | -                | -         |     0.83 | deko, KENSI, Lack1, Norwi, r3salt     |
|           21 |     4109 | 2024-04-10 | BetBoom            | L   | 0.202      | -            | -                | -                | -         |    -4.67 | deko, KENSI, Lack1, Norwi, r3salt     |
|           20 |     4158 | 2024-04-09 | KOI                | L   | 0.196      | -            | -                | -                | -         |    -5.77 | deko, KENSI, Lack1, Norwi, r3salt     |
|           19 |     4166 | 2024-04-09 | 1WIN               | W   | 0.195      | -            | -                | -                | -         |     0.28 | deko, KENSI, Lack1, Norwi, r3salt     |
|           18 |     4174 | 2024-04-09 | 9 Pandas           | W   | 0.194      | -            | -                | -                | -         |     0.59 | deko, KENSI, Lack1, Norwi, r3salt     |
|           17 |     4184 | 2024-04-08 | Metizport          | W   | 0.190      | -            | -                | -                | -         |     0.14 | deko, KENSI, Lack1, Norwi, r3salt     |
|           16 |     4189 | 2024-04-08 | OG                 | W   | 0.189      | -            | -                | -                | -         |     0.39 | deko, KENSI, Lack1, Norwi, r3salt     |
|           15 |     4199 | 2024-04-08 | 1WIN               | L   | 0.188      | -            | -                | -                | -         |    -5.66 | deko, KENSI, Lack1, Norwi, r3salt     |
|           14 |     4292 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.163      | -            | -                | -                | -         |     2.69 | deko, KENSI, Lack1, Norwi, r3salt     |
|           13 |     4332 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.156      | -            | -                | -                | -         |     2.62 | deko, KENSI, Lack1, Norwi, r3salt     |
|           12 |     4370 | 2024-04-02 | Apeks              | W   | 0.149      | -            | -                | -                | -         |     0.11 | deko, KENSI, Lack1, Norwi, r3salt     |
|           11 |     4379 | 2024-04-02 | Metizport          | W   | 0.148      | -            | -                | -                | -         |     0.10 | deko, KENSI, Lack1, Norwi, r3salt     |
|           10 |     4391 | 2024-04-01 | SINNERS            | L   | 0.143      | -            | -                | -                | -         |    -3.74 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     4430 | 2024-03-28 | Apogee             | W   | 0.116      | -            | -                | -                | -         |     0.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     4461 | 2024-03-27 | Metizport          | W   | 0.110      | -            | -                | -                | -         |     0.07 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     4468 | 2024-03-27 | AURA               | W   | 0.109      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     4502 | 2024-03-25 | Rebels             | W   | 0.096      | -            | -                | -                | -         |     0.17 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4518 | 2024-03-23 | ALTERNATE aTTaX    | W   | 0.083      | -            | -                | -                | -         |     0.28 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4532 | 2024-03-22 | ex-Sprout          | W   | 0.076      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4656 | 2024-03-16 | Gods Reign         | W   | 0.034      | -            | -                | -                | -         |     0.02 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4677 | 2024-03-15 | Gods Reign         | W   | 0.027      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4712 | 2024-03-14 | Bad News Kangaroos | W   | 0.020      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($89,870.41)
- Divide that value by the 5th highest value among all rosters ($307,186.12)
- The final value (0.29) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      0.929 | $35,000.00     | $32,506.25      |
| 2024-06-16 |      0.648 | $10,000.00     | $6,481.94       |
| 2024-06-09 |      0.602 | $8,500.00      | $5,117.12       |
| 2024-06-02 |      0.554 | $15,000.00     | $8,307.99       |
| 2024-05-23 |      0.488 | $12,500.00     | $6,100.69       |
| 2024-04-28 |      0.320 | $20,000.00     | $6,403.70       |
| 2024-04-14 |      0.228 | $105,000.00    | $23,975.00      |
| 2024-03-16 |      0.034 | $28,500.00     | $977.71         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
