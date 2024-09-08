### Roster Details<br />
Team Name: Aurora<br />
Roster: deko, gr1ks, KENSI, Lack1, Norwi<br />
Global Rank: [25](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [19]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1212.4<br />
<br />
Final Rank Value (1212.4) = Starting Rank Value (1413.8) + Head To Head Adjustments (-201.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.650[<sup>1</sup>](#table2)
- Bounty Collected: 0.475[<sup>2</sup>](#table1)
- Opponent Network: 0.268[<sup>2</sup>](#table1)
- LAN Wins: 0.701[<sup>2</sup>](#table1)

The average of these factors is 0.524<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1413.8
- 400 + ( ( 0.524 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 1413.8


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
|           82 |      227 | 2024-08-30 | Monte              | L   | 1.000      | -            | -                | -                | -         |   -22.25 | deko, gr1ks, KENSI, Lack1, Norwi      |
|           81 |      233 | 2024-08-30 | Sashi              | W   | 1.000      | 0.143        | 0.151 (0.022)    | -                | -         |     8.77 | deko, gr1ks, KENSI, Lack1, Norwi      |
|           80 |      261 | 2024-08-29 | GenOne             | W   | 1.000      | -            | -                | -                | -         |     0.59 | deko, gr1ks, KENSI, Lack1, Norwi      |
|           79 |      275 | 2024-08-29 | GamerLegion        | L   | 1.000      | -            | -                | -                | -         |   -21.79 | deko, gr1ks, KENSI, Lack1, Norwi      |
|           78 |      468 | 2024-08-26 | FURIA              | L   | 1.000      | -            | -                | -                | -         |    -5.33 | clax, deko, KENSI, Lack1, Norwi       |
|           77 |      505 | 2024-08-25 | Eternal Fire       | L   | 1.000      | -            | -                | -                | -         |    -2.02 | clax, deko, KENSI, Lack1, Norwi       |
|           76 |      727 | 2024-08-19 | Sashi              | L   | 1.000      | -            | -                | -                | -         |   -23.25 | clax, deko, KENSI, Lack1, Norwi       |
|           75 |      922 | 2024-08-12 | TSM                | L   | 1.000      | -            | -                | -                | -         |   -25.57 | deko, KENSI, Lack1, Norwi, r3salt     |
|           74 |     1066 | 2024-08-07 | Space              | W   | 0.988      | 0.500        | -                | 0.463 (0.229)    | -         |     1.78 | deko, KENSI, Lack1, Norwi, r3salt     |
|           73 |     1139 | 2024-08-05 | ARCRED             | L   | 0.974      | -            | -                | -                | -         |   -27.27 | deko, KENSI, Lack1, Norwi, r3salt     |
|           72 |     1171 | 2024-08-04 | Nemiga             | L   | 0.967      | -            | -                | -                | -         |   -23.74 | deko, KENSI, Lack1, Norwi, r3salt     |
|           71 |     1449 | 2024-07-28 | 3DMAX              | L   | 0.919      | -            | -                | -                | -         |    -9.70 | deko, KENSI, Lack1, Norwi, r3salt     |
|           70 |     1497 | 2024-07-26 | The MongolZ        | L   | 0.906      | -            | -                | -                | -         |    -3.76 | deko, KENSI, Lack1, Norwi, r3salt     |
|           69 |     1502 | 2024-07-26 | BLEED              | W   | 0.905      | 0.650        | 0.101 (0.059)    | 0.541 (0.318)    | 1 (0.905) |     8.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           68 |     1528 | 2024-07-25 | True Rippers       | W   | 0.901      | -            | -                | -                | 1 (0.901) |     0.63 | deko, KENSI, Lack1, Norwi, r3salt     |
|           67 |     1540 | 2024-07-25 | ENCE               | W   | 0.898      | 0.650        | 0.130 (0.076)    | 0.330 (0.193)    | 1 (0.898) |     9.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           66 |     1575 | 2024-07-24 | PARIVISION         | W   | 0.892      | 0.650        | 0.046 (0.026)    | 0.730 (0.424)    | 1 (0.892) |     4.76 | deko, KENSI, Lack1, Norwi, r3salt     |
|           65 |     1764 | 2024-07-18 | B8                 | W   | 0.855      | 0.500        | 0.176 (0.075)    | 1.000 (0.427)    | -         |     5.93 | deko, KENSI, Lack1, Norwi, r3salt     |
|           64 |     1894 | 2024-07-16 | Qiang              | W   | 0.841      | 0.500        | -                | 0.389 (0.164)    | -         |     2.46 | deko, KENSI, Lack1, Norwi, r3salt     |
|           63 |     2177 | 2024-06-16 | Complexity         | L   | 0.639      | -            | -                | -                | -         |    -5.83 | deko, KENSI, Lack1, Norwi, r3salt     |
|           62 |     2243 | 2024-06-14 | The MongolZ        | W   | 0.627      | 0.500        | 0.864 (0.271)    | 0.695 (0.218)    | 1 (0.627) |    18.78 | deko, KENSI, Lack1, Norwi, r3salt     |
|           61 |     2253 | 2024-06-14 | Falcons            | W   | 0.626      | 0.500        | 0.297 (0.093)    | -                | 1 (0.626) |    14.51 | deko, KENSI, Lack1, Norwi, r3salt     |
|           60 |     2353 | 2024-06-10 | 9 Pandas           | W   | 0.600      | -            | -                | -                | -         |     3.85 | deko, KENSI, Lack1, Norwi, r3salt     |
|           59 |     2358 | 2024-06-10 | Monte              | W   | 0.600      | -            | -                | -                | -         |     2.67 | deko, KENSI, Lack1, Norwi, r3salt     |
|           58 |     2362 | 2024-06-10 | SAW                | L   | 0.599      | -            | -                | -                | -         |    -6.50 | deko, KENSI, Lack1, Norwi, r3salt     |
|           57 |     2387 | 2024-06-09 | Monte              | L   | 0.594      | -            | -                | -                | -         |   -16.19 | deko, KENSI, Lack1, Norwi, r3salt     |
|           56 |     2394 | 2024-06-09 | PARIVISION         | W   | 0.594      | -            | -                | -                | -         |     3.97 | deko, KENSI, Lack1, Norwi, r3salt     |
|           55 |     2402 | 2024-06-09 | RUSH B             | L   | 0.593      | -            | -                | -                | -         |   -17.38 | deko, KENSI, Lack1, Norwi, r3salt     |
|           54 |     2410 | 2024-06-09 | 3DMAX              | L   | 0.593      | -            | -                | -                | -         |    -3.77 | deko, KENSI, Lack1, Norwi, r3salt     |
|           53 |     2418 | 2024-06-09 | SINNERS            | L   | 0.593      | -            | -                | -                | -         |   -15.84 | deko, KENSI, Lack1, Norwi, r3salt     |
|           52 |     2505 | 2024-06-07 | Sangal             | L   | 0.581      | -            | -                | -                | -         |   -11.14 | deko, KENSI, Lack1, Norwi, r3salt     |
|           51 |     2520 | 2024-06-07 | Verdant            | W   | 0.580      | -            | -                | -                | -         |     1.02 | deko, KENSI, Lack1, Norwi, r3salt     |
|           50 |     2524 | 2024-06-07 | Qiang              | W   | 0.580      | -            | -                | -                | -         |     1.24 | deko, KENSI, Lack1, Norwi, r3salt     |
|           49 |     2571 | 2024-06-06 | RUSH B             | W   | 0.574      | -            | -                | -                | -         |     0.97 | deko, KENSI, Lack1, Norwi, r3salt     |
|           48 |     2633 | 2024-06-05 | PARIVISION         | W   | 0.568      | 0.500        | -                | 0.730 (0.207)    | -         |     3.00 | deko, KENSI, Lack1, Norwi, r3salt     |
|           47 |     2681 | 2024-06-04 | 3DMAX              | L   | 0.561      | -            | -                | -                | -         |    -3.21 | deko, KENSI, Lack1, Norwi, r3salt     |
|           46 |     2746 | 2024-06-01 | BLEED              | L   | 0.544      | -            | -                | -                | -         |   -12.24 | deko, KENSI, Lack1, Norwi, r3salt     |
|           45 |     2771 | 2024-06-01 | Lynn Vision        | W   | 0.540      | 0.500        | 0.073 (0.020)    | -                | 1 (0.540) |     1.19 | deko, KENSI, Lack1, Norwi, r3salt     |
|           44 |     2780 | 2024-05-31 | Chinggis Warriors  | W   | 0.538      | -            | -                | -                | 1 (0.538) |     1.08 | deko, KENSI, Lack1, Norwi, r3salt     |
|           43 |     2855 | 2024-05-29 | The MongolZ        | L   | 0.519      | -            | -                | -                | -         |    -0.96 | deko, KENSI, Lack1, Norwi, r3salt     |
|           42 |     2878 | 2024-05-28 | Lynn Vision        | W   | 0.512      | -            | -                | -                | 1 (0.512) |     1.06 | deko, KENSI, Lack1, Norwi, r3salt     |
|           41 |     3049 | 2024-05-21 | Astralis           | L   | 0.467      | -            | -                | -                | -         |    -4.07 | deko, KENSI, Lack1, Norwi, r3salt     |
|           40 |     3180 | 2024-05-17 | SAW                | W   | 0.439      | 0.769        | 0.330 (0.111)    | 0.747 (0.252)    | -         |     9.49 | deko, KENSI, Lack1, Norwi, r3salt     |
|           39 |     3195 | 2024-05-16 | PARIVISION         | W   | 0.435      | 0.769        | -                | 0.730 (0.244)    | -         |     2.17 | deko, KENSI, Lack1, Norwi, r3salt     |
|           38 |     3203 | 2024-05-16 | MIBR               | L   | 0.435      | -            | -                | -                | -         |    -6.27 | deko, KENSI, Lack1, Norwi, r3salt     |
|           37 |     3217 | 2024-05-16 | SAW                | L   | 0.432      | -            | -                | -                | -         |    -4.35 | deko, KENSI, Lack1, Norwi, r3salt     |
|           36 |     3267 | 2024-05-15 | Spirit             | L   | 0.426      | -            | -                | -                | -         |    -0.51 | deko, KENSI, Lack1, Norwi, r3salt     |
|           35 |     3410 | 2024-05-10 | MOUZ NXT           | L   | 0.395      | -            | -                | -                | -         |   -11.27 | deko, KENSI, Lack1, Norwi, r3salt     |
|           34 |     3667 | 2024-04-28 | MIBR               | L   | 0.312      | -            | -                | -                | -         |    -4.78 | deko, KENSI, Lack1, Norwi, r3salt     |
|           33 |     3669 | 2024-04-27 | Rebels             | W   | 0.312      | -            | -                | -                | 1 (0.312) |     0.68 | deko, KENSI, Lack1, Norwi, r3salt     |
|           32 |     3695 | 2024-04-27 | Party Astronauts   | W   | 0.305      | -            | -                | -                | -         |     0.49 | deko, KENSI, Lack1, Norwi, r3salt     |
|           31 |     3720 | 2024-04-25 | Apeks              | L   | 0.298      | -            | -                | -                | -         |    -9.10 | deko, KENSI, Lack1, Norwi, r3salt     |
|           30 |     3724 | 2024-04-25 | Party Astronauts   | W   | 0.297      | -            | -                | -                | -         |     0.45 | deko, KENSI, Lack1, Norwi, r3salt     |
|           29 |     3928 | 2024-04-18 | RUBY               | L   | 0.247      | -            | -                | -                | -         |    -7.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           28 |     4040 | 2024-04-14 | OG                 | W   | 0.220      | -            | -                | -                | -         |     0.55 | deko, KENSI, Lack1, Norwi, r3salt     |
|           27 |     4053 | 2024-04-13 | BetBoom            | W   | 0.214      | 0.684        | 0.229 (0.033)    | -                | -         |     1.83 | deko, KENSI, Lack1, Norwi, r3salt     |
|           26 |     4065 | 2024-04-12 | AMKAL              | W   | 0.208      | -            | -                | -                | -         |     0.99 | deko, KENSI, Lack1, Norwi, r3salt     |
|           25 |     4088 | 2024-04-11 | BetBoom            | W   | 0.202      | -            | -                | -                | -         |     1.75 | deko, KENSI, Lack1, Norwi, r3salt     |
|           24 |     4095 | 2024-04-11 | Apeks              | W   | 0.201      | -            | -                | -                | -         |     0.18 | deko, KENSI, Lack1, Norwi, r3salt     |
|           23 |     4100 | 2024-04-11 | FORZE              | W   | 0.200      | -            | -                | -                | -         |     0.21 | deko, KENSI, Lack1, Norwi, r3salt     |
|           22 |     4129 | 2024-04-10 | PARIVISION         | W   | 0.195      | -            | -                | -                | -         |     0.84 | deko, KENSI, Lack1, Norwi, r3salt     |
|           21 |     4141 | 2024-04-10 | BetBoom            | L   | 0.194      | -            | -                | -                | -         |    -4.47 | deko, KENSI, Lack1, Norwi, r3salt     |
|           20 |     4190 | 2024-04-09 | KOI                | L   | 0.188      | -            | -                | -                | -         |    -5.52 | deko, KENSI, Lack1, Norwi, r3salt     |
|           19 |     4198 | 2024-04-09 | 1WIN               | W   | 0.187      | -            | -                | -                | -         |     0.29 | deko, KENSI, Lack1, Norwi, r3salt     |
|           18 |     4206 | 2024-04-09 | 9 Pandas           | W   | 0.186      | -            | -                | -                | -         |     0.60 | deko, KENSI, Lack1, Norwi, r3salt     |
|           17 |     4216 | 2024-04-08 | Metizport          | W   | 0.182      | -            | -                | -                | -         |     0.15 | deko, KENSI, Lack1, Norwi, r3salt     |
|           16 |     4221 | 2024-04-08 | OG                 | W   | 0.181      | -            | -                | -                | -         |     0.40 | deko, KENSI, Lack1, Norwi, r3salt     |
|           15 |     4231 | 2024-04-08 | 1WIN               | L   | 0.180      | -            | -                | -                | -         |    -5.41 | deko, KENSI, Lack1, Norwi, r3salt     |
|           14 |     4324 | 2024-04-04 | Ninjas in Pyjamas  | W   | 0.155      | -            | -                | -                | -         |     2.62 | deko, KENSI, Lack1, Norwi, r3salt     |
|           13 |     4364 | 2024-04-03 | Ninjas in Pyjamas  | W   | 0.148      | -            | -                | -                | -         |     2.54 | deko, KENSI, Lack1, Norwi, r3salt     |
|           12 |     4402 | 2024-04-02 | Apeks              | W   | 0.141      | -            | -                | -                | -         |     0.11 | deko, KENSI, Lack1, Norwi, r3salt     |
|           11 |     4411 | 2024-04-02 | Metizport          | W   | 0.140      | -            | -                | -                | -         |     0.10 | deko, KENSI, Lack1, Norwi, r3salt     |
|           10 |     4423 | 2024-04-01 | SINNERS            | L   | 0.135      | -            | -                | -                | -         |    -3.49 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            9 |     4462 | 2024-03-28 | Apogee             | W   | 0.108      | -            | -                | -                | -         |     0.08 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            8 |     4493 | 2024-03-27 | Metizport          | W   | 0.102      | -            | -                | -                | -         |     0.07 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            7 |     4500 | 2024-03-27 | AURA               | W   | 0.102      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            6 |     4534 | 2024-03-25 | Rebels             | W   | 0.088      | -            | -                | -                | -         |     0.16 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            5 |     4550 | 2024-03-23 | ALTERNATE aTTaX    | W   | 0.075      | -            | -                | -                | -         |     0.27 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            4 |     4564 | 2024-03-22 | ex-Sprout          | W   | 0.068      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            3 |     4688 | 2024-03-16 | Gods Reign         | W   | 0.026      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            2 |     4709 | 2024-03-15 | Gods Reign         | W   | 0.019      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |
|            1 |     4744 | 2024-03-14 | Bad News Kangaroos | W   | 0.012      | -            | -                | -                | -         |     0.01 | BELCHONOKK, deko, KENSI, Lack1, Norwi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($88,013.95)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.29) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      0.921 | $35,000.00     | $32,229.17      |
| 2024-06-16 |      0.640 | $10,000.00     | $6,402.78       |
| 2024-06-09 |      0.594 | $8,500.00      | $5,049.83       |
| 2024-06-02 |      0.546 | $15,000.00     | $8,189.24       |
| 2024-05-23 |      0.480 | $12,500.00     | $6,001.74       |
| 2024-04-28 |      0.312 | $20,000.00     | $6,245.37       |
| 2024-04-14 |      0.220 | $105,000.00    | $23,143.75      |
| 2024-03-16 |      0.026 | $28,500.00     | $752.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
