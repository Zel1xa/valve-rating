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
|           55 |       10 | 2024-08-05 | ENCE              | W   | 1.000      | 0.435        | 0.174 (0.076)    | 0.432 (0.188)    | 0 (0.000) |    25.61 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           54 |       25 | 2024-08-04 | Betera            | L   | 1.000      | -            | -                | -                | -         |   -29.39 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           53 |       65 | 2024-08-03 | GUN5              | L   | 1.000      | -            | -                | -                | -         |   -25.37 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           52 |       80 | 2024-08-03 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.08 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           51 |       91 | 2024-08-02 | TSM               | W   | 1.000      | 0.500        | -                | 0.430 (0.215)    | 0 (0.000) |    10.48 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           50 |      132 | 2024-08-01 | 9 Pandas          | W   | 1.000      | 0.500        | 0.081 (0.041)    | 0.717 (0.359)    | 0 (0.000) |    13.23 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           49 |      247 | 2024-07-30 | Permitta          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.85 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           48 |      347 | 2024-07-26 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -6.65 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           47 |      360 | 2024-07-26 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.52 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           46 |      392 | 2024-07-25 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -5.53 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           45 |      430 | 2024-07-24 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.710 (0.462)    | 1 (1.000) |    30.77 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           44 |      437 | 2024-07-24 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -3.38 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           43 |     1109 | 2024-06-14 | Permitta          | L   | 0.851      | -            | -                | -                | -         |   -18.88 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           42 |     1210 | 2024-06-10 | RUSH B            | W   | 0.825      | -            | -                | -                | 0 (0.000) |     8.07 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           41 |     1216 | 2024-06-10 | 3DMAX             | L   | 0.825      | -            | -                | -                | -         |    -3.40 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           40 |     1222 | 2024-06-10 | SINNERS           | L   | 0.824      | -            | -                | -                | -         |   -14.40 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           39 |     1253 | 2024-06-09 | Aurora            | L   | 0.819      | -            | -                | -                | -         |    -3.31 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           38 |     1259 | 2024-06-09 | 9 Pandas          | W   | 0.818      | -            | -                | -                | 0 (0.000) |    12.43 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           37 |     1270 | 2024-06-09 | Monte             | W   | 0.818      | -            | -                | -                | 0 (0.000) |    10.19 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           36 |     1272 | 2024-06-09 | SAW               | L   | 0.818      | -            | -                | -                | -         |    -9.98 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           35 |     1492 | 2024-06-05 | Aurora            | L   | 0.793      | -            | -                | -                | -         |    -2.06 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           34 |     1539 | 2024-06-04 | Monte             | W   | 0.786      | 0.500        | 0.080 (0.031)    | 0.611 (0.240)    | -         |    10.28 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           33 |     1944 | 2024-05-20 | Sangal            | L   | 0.685      | -            | -                | -                | -         |    -9.69 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           32 |     2023 | 2024-05-17 | Zero Tenacity     | W   | 0.667      | 0.500        | 0.143 (0.048)    | 1.000 (0.333)    | -         |    10.23 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           31 |     2054 | 2024-05-16 | Aurora            | L   | 0.661      | -            | -                | -                | -         |    -1.40 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           30 |     2070 | 2024-05-16 | Eternal Fire      | L   | 0.658      | -            | -                | -                | -         |    -0.73 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           29 |     2109 | 2024-05-15 | B8                | W   | 0.653      | 0.500        | 0.165 (0.054)    | 0.935 (0.305)    | -         |    11.27 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     2294 | 2024-05-09 | Endpoint          | L   | 0.612      | -            | -                | -                | -         |   -13.22 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     2451 | 2024-05-01 | Passion UA        | L   | 0.559      | -            | -                | -                | -         |   -10.22 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     2467 | 2024-05-01 | fnatic            | L   | 0.557      | -            | -                | -                | -         |    -1.50 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     2493 | 2024-04-29 | 3DMAX             | L   | 0.546      | -            | -                | -                | -         |    -0.84 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |     2502 | 2024-04-29 | Zero Tenacity     | W   | 0.545      | 0.500        | 0.143 (0.039)    | 1.000 (0.272)    | -         |     8.07 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |     2538 | 2024-04-27 | Sangal            | W   | 0.532      | 0.500        | 0.219 (0.058)    | 0.866 (0.231)    | -         |     9.52 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |     2568 | 2024-04-26 | SINNERS           | W   | 0.526      | -            | -                | -                | -         |     9.48 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |     2597 | 2024-04-25 | ex-Guild Eagles   | W   | 0.519      | -            | -                | -                | -         |     3.92 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |     2616 | 2024-04-24 | MOUZ NXT          | W   | 0.512      | 0.435        | 0.139 (0.031)    | 0.987 (0.220)    | -         |     7.76 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           19 |     2668 | 2024-04-21 | Nexus             | W   | 0.492      | -            | -                | -                | -         |     3.83 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           18 |     2671 | 2024-04-21 | B8                | L   | 0.492      | -            | -                | -                | -         |    -8.10 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           17 |     2727 | 2024-04-19 | Zero Tenacity     | L   | 0.480      | -            | -                | -                | -         |    -7.66 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           16 |     2826 | 2024-04-17 | HAVU              | W   | 0.467      | -            | -                | -                | -         |     1.59 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           15 |     2829 | 2024-04-17 | Permitta          | L   | 0.466      | -            | -                | -                | -         |    -9.34 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           14 |     2953 | 2024-04-11 | 500               | L   | 0.426      | -            | -                | -                | -         |   -11.83 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           13 |     2988 | 2024-04-10 | Aurora            | L   | 0.420      | -            | -                | -                | -         |    -0.59 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           12 |     3048 | 2024-04-09 | RUSH B            | L   | 0.413      | -            | -                | -                | -         |   -10.20 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           11 |     3217 | 2024-04-03 | MOUZ NXT          | L   | 0.373      | -            | -                | -                | -         |    -6.96 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           10 |     3229 | 2024-04-03 | Space             | W   | 0.372      | -            | -                | -                | -         |     1.94 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            9 |     3265 | 2024-04-02 | AMKAL             | L   | 0.366      | -            | -                | -                | -         |    -5.58 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     3272 | 2024-04-02 | Insilio           | L   | 0.365      | -            | -                | -                | -         |    -8.85 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     3284 | 2024-04-01 | Metizport         | W   | 0.359      | -            | -                | -                | -         |     2.13 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     3450 | 2024-03-21 | FORZE             | W   | 0.286      | -            | -                | -                | -         |     2.15 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     3632 | 2024-03-13 | 3DMAX             | W   | 0.232      | 0.500        | 0.508 (0.059)    | -                | -         |     7.02 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     3748 | 2024-03-08 | B8                | W   | 0.199      | -            | -                | -                | -         |     2.98 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     3804 | 2024-03-06 | Apeks             | W   | 0.186      | -            | -                | -                | -         |     1.44 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     3915 | 2024-03-02 | Gaimin Gladiators | L   | 0.158      | -            | -                | -                | -         |    -3.46 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     3947 | 2024-02-29 | Monte             | L   | 0.145      | -            | -                | -                | -         |    -3.02 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,608.02)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.819 | $6,500.00      | $5,325.03       |
| 2024-05-02 |      0.566 | $500.00        | $282.99         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
