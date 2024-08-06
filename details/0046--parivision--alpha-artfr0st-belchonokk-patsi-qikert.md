### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [46](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1098.9<br />
<br />
Final Rank Value (1098.9) = Starting Rank Value (1109.6) + Head To Head Adjustments (-10.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.362[<sup>1</sup>](#table2)
- Bounty Collected: 0.509[<sup>2</sup>](#table1)
- Opponent Network: 0.282[<sup>2</sup>](#table1)
- LAN Wins: 0.230[<sup>2</sup>](#table1)

The average of these factors is 0.346<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1109.6
- 400 + ( ( 0.346 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1109.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           55 |       12 | 2024-08-05 | ENCE              | W   | 1.000      | 0.435        | 0.174 (0.075)    | 0.432 (0.188)    | 0 (0.000) |    25.61 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           54 |       27 | 2024-08-04 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -29.39 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           53 |       67 | 2024-08-03 | GUN5              | L   | 1.000      | -            | -                | -                | -         |   -25.38 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           52 |       82 | 2024-08-03 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.08 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           51 |       93 | 2024-08-02 | TSM               | W   | 1.000      | 0.500        | -                | 0.431 (0.215)    | 0 (0.000) |    10.49 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           50 |      134 | 2024-08-01 | 9 Pandas          | W   | 1.000      | 0.500        | 0.081 (0.041)    | 0.717 (0.358)    | 0 (0.000) |    13.21 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           49 |      249 | 2024-07-30 | Permitta          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.84 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           48 |      349 | 2024-07-26 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -6.65 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           47 |      362 | 2024-07-26 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.51 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           46 |      394 | 2024-07-25 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -5.53 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           45 |      432 | 2024-07-24 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.710 (0.462)    | 1 (1.000) |    30.77 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           44 |      439 | 2024-07-24 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -3.37 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           43 |     1111 | 2024-06-14 | Permitta          | L   | 0.849      | -            | -                | -                | -         |   -18.84 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           42 |     1212 | 2024-06-10 | RUSH B            | W   | 0.823      | -            | -                | -                | 0 (0.000) |     8.05 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           41 |     1218 | 2024-06-10 | 3DMAX             | L   | 0.823      | -            | -                | -                | -         |    -3.38 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           40 |     1224 | 2024-06-10 | SINNERS           | L   | 0.823      | -            | -                | -                | -         |   -14.37 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           39 |     1255 | 2024-06-09 | Aurora            | L   | 0.817      | -            | -                | -                | -         |    -3.29 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           38 |     1261 | 2024-06-09 | 9 Pandas          | W   | 0.817      | -            | -                | -                | 0 (0.000) |    12.38 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           37 |     1272 | 2024-06-09 | Monte             | W   | 0.816      | -            | -                | -                | 0 (0.000) |    10.16 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           36 |     1274 | 2024-06-09 | SAW               | L   | 0.816      | -            | -                | -                | -         |    -9.98 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           35 |     1494 | 2024-06-05 | Aurora            | L   | 0.791      | -            | -                | -                | -         |    -2.05 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           34 |     1541 | 2024-06-04 | Monte             | W   | 0.784      | 0.500        | 0.080 (0.031)    | 0.611 (0.240)    | -         |    10.25 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           33 |     1946 | 2024-05-20 | Sangal            | L   | 0.683      | -            | -                | -                | -         |    -9.66 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           32 |     2025 | 2024-05-17 | Zero Tenacity     | W   | 0.665      | 0.500        | 0.143 (0.048)    | 1.000 (0.332)    | -         |    10.20 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           31 |     2056 | 2024-05-16 | Aurora            | L   | 0.659      | -            | -                | -                | -         |    -1.39 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           30 |     2072 | 2024-05-16 | Eternal Fire      | L   | 0.657      | -            | -                | -                | -         |    -0.73 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           29 |     2111 | 2024-05-15 | B8                | W   | 0.651      | 0.500        | 0.164 (0.054)    | 0.934 (0.304)    | -         |    11.23 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     2296 | 2024-05-09 | Endpoint          | L   | 0.611      | -            | -                | -                | -         |   -13.19 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     2453 | 2024-05-01 | Passion UA        | L   | 0.557      | -            | -                | -                | -         |   -10.18 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     2469 | 2024-05-01 | fnatic            | L   | 0.555      | -            | -                | -                | -         |    -1.50 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     2495 | 2024-04-29 | 3DMAX             | L   | 0.544      | -            | -                | -                | -         |    -0.83 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |     2504 | 2024-04-29 | Zero Tenacity     | W   | 0.543      | 0.500        | 0.143 (0.039)    | 1.000 (0.272)    | -         |     8.05 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |     2540 | 2024-04-27 | Sangal            | W   | 0.531      | 0.500        | 0.219 (0.058)    | 0.866 (0.230)    | -         |     9.49 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |     2570 | 2024-04-26 | SINNERS           | W   | 0.524      | -            | -                | -                | -         |     9.44 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |     2599 | 2024-04-25 | ex-Guild Eagles   | W   | 0.517      | -            | -                | -                | -         |     3.90 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |     2618 | 2024-04-24 | MOUZ NXT          | W   | 0.510      | 0.435        | 0.139 (0.031)    | 0.986 (0.219)    | -         |     7.73 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           19 |     2670 | 2024-04-21 | Nexus             | W   | 0.490      | -            | -                | -                | -         |     3.81 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           18 |     2673 | 2024-04-21 | B8                | L   | 0.490      | -            | -                | -                | -         |    -8.08 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           17 |     2729 | 2024-04-19 | Zero Tenacity     | L   | 0.478      | -            | -                | -                | -         |    -7.63 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           16 |     2828 | 2024-04-17 | HAVU              | W   | 0.465      | -            | -                | -                | -         |     1.58 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           15 |     2831 | 2024-04-17 | Permitta          | L   | 0.464      | -            | -                | -                | -         |    -9.31 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           14 |     2955 | 2024-04-11 | 500               | L   | 0.424      | -            | -                | -                | -         |   -11.78 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           13 |     2990 | 2024-04-10 | Aurora            | L   | 0.418      | -            | -                | -                | -         |    -0.58 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           12 |     3050 | 2024-04-09 | RUSH B            | L   | 0.411      | -            | -                | -                | -         |   -10.16 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           11 |     3219 | 2024-04-03 | MOUZ NXT          | L   | 0.372      | -            | -                | -                | -         |    -6.93 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           10 |     3231 | 2024-04-03 | Space             | W   | 0.370      | -            | -                | -                | -         |     1.93 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            9 |     3267 | 2024-04-02 | AMKAL             | L   | 0.364      | -            | -                | -                | -         |    -5.56 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     3274 | 2024-04-02 | Insilio           | L   | 0.363      | -            | -                | -                | -         |    -8.81 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     3286 | 2024-04-01 | Metizport         | W   | 0.357      | -            | -                | -                | -         |     2.11 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     3452 | 2024-03-21 | FORZE             | W   | 0.284      | -            | -                | -                | -         |     2.13 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     3634 | 2024-03-13 | 3DMAX             | W   | 0.231      | 0.500        | 0.509 (0.059)    | -                | -         |     6.96 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     3750 | 2024-03-08 | B8                | W   | 0.198      | -            | -                | -                | -         |     2.96 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     3806 | 2024-03-06 | Apeks             | W   | 0.184      | -            | -                | -                | -         |     1.42 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     3917 | 2024-03-02 | Gaimin Gladiators | L   | 0.157      | -            | -                | -                | -         |    -3.42 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     3949 | 2024-02-29 | Monte             | L   | 0.143      | -            | -                | -                | -         |    -2.99 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,595.38)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.817 | $6,500.00      | $5,313.30       |
| 2024-05-02 |      0.564 | $500.00        | $282.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
