### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [43](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1108.1<br />
<br />
Final Rank Value (1108.1) = Starting Rank Value (1108.5) + Head To Head Adjustments (-0.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.363[<sup>1</sup>](#table2)
- Bounty Collected: 0.507[<sup>2</sup>](#table1)
- Opponent Network: 0.276[<sup>2</sup>](#table1)
- LAN Wins: 0.231[<sup>2</sup>](#table1)

The average of these factors is 0.344<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1108.5
- 400 + ( ( 0.344 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1108.5


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
|           51 |        0 | 2024-08-01 | 9 Pandas          | W   | 1.000      | 0.500        | 0.083 (0.041)    | 0.577 (0.289)    | 0 (0.000) |    13.40 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           50 |      106 | 2024-07-30 | Permitta          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.65 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           49 |      207 | 2024-07-26 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -6.62 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           48 |      220 | 2024-07-26 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.68 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           47 |      252 | 2024-07-25 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -5.90 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           46 |      290 | 2024-07-24 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.719 (0.468)    | 1 (1.000) |    30.74 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           45 |      297 | 2024-07-24 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -3.46 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           44 |      975 | 2024-06-14 | Permitta          | L   | 0.878      | -            | -                | -                | -         |   -19.69 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           43 |     1078 | 2024-06-10 | RUSH B            | W   | 0.852      | -            | -                | -                | 0 (0.000) |     8.01 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           42 |     1084 | 2024-06-10 | 3DMAX             | L   | 0.852      | -            | -                | -                | -         |    -3.75 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           41 |     1090 | 2024-06-10 | SINNERS           | L   | 0.851      | -            | -                | -                | -         |   -15.92 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           40 |     1121 | 2024-06-09 | Aurora            | L   | 0.846      | -            | -                | -                | -         |    -3.57 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           39 |     1127 | 2024-06-09 | 9 Pandas          | W   | 0.845      | -            | -                | -                | 0 (0.000) |    12.94 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           38 |     1138 | 2024-06-09 | Monte             | W   | 0.845      | -            | -                | -                | 0 (0.000) |    10.27 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           37 |     1141 | 2024-06-09 | SAW               | L   | 0.845      | -            | -                | -                | -         |   -10.12 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           36 |     1374 | 2024-06-05 | Aurora            | L   | 0.820      | -            | -                | -                | -         |    -2.19 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           35 |     1421 | 2024-06-04 | Monte             | W   | 0.813      | 0.500        | 0.081 (0.033)    | 0.614 (0.250)    | 0 (0.000) |    10.38 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           34 |     1848 | 2024-05-20 | Sangal            | L   | 0.712      | -            | -                | -                | -         |   -10.58 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           33 |     1934 | 2024-05-17 | Zero Tenacity     | W   | 0.693      | 0.500        | 0.139 (0.048)    | 1.000 (0.347)    | 0 (0.000) |    10.46 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           32 |     1965 | 2024-05-16 | Aurora            | L   | 0.687      | -            | -                | -                | -         |    -1.48 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           31 |     1981 | 2024-05-16 | Eternal Fire      | L   | 0.685      | -            | -                | -                | -         |    -0.71 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           30 |     2020 | 2024-05-15 | B8                | W   | 0.680      | 0.500        | 0.168 (0.057)    | 0.878 (0.298)    | 0 (0.000) |    11.54 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           29 |     2214 | 2024-05-09 | Endpoint          | L   | 0.639      | -            | -                | -                | -         |   -13.44 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     2375 | 2024-05-01 | Passion UA        | L   | 0.586      | -            | -                | -                | -         |   -11.01 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     2392 | 2024-05-01 | fnatic            | L   | 0.584      | -            | -                | -                | -         |    -3.68 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     2418 | 2024-04-29 | 3DMAX             | L   | 0.573      | -            | -                | -                | -         |    -0.94 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     2427 | 2024-04-29 | Zero Tenacity     | W   | 0.572      | 0.500        | 0.139 (0.040)    | 1.000 (0.286)    | -         |     8.15 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |     2463 | 2024-04-27 | Sangal            | W   | 0.559      | 0.500        | 0.221 (0.062)    | 0.823 (0.230)    | -         |     9.59 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |     2493 | 2024-04-26 | SINNERS           | W   | 0.552      | 0.435        | -                | 0.768 (0.184)    | -         |     8.20 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |     2522 | 2024-04-25 | ex-Guild Eagles   | W   | 0.546      | -            | -                | -                | -         |     4.23 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |     2541 | 2024-04-24 | MOUZ NXT          | W   | 0.539      | 0.435        | 0.141 (0.033)    | 1.000 (0.234)    | -         |     8.20 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |     2572 | 2024-04-23 | B8                | W   | 0.531      | 0.384        | 0.168 (0.034)    | 0.878 (0.179)    | -         |     8.18 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           19 |     2597 | 2024-04-21 | Nexus             | W   | 0.519      | -            | -                | -                | -         |     4.17 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           18 |     2600 | 2024-04-21 | B8                | L   | 0.518      | -            | -                | -                | -         |    -8.33 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           17 |     2659 | 2024-04-19 | Zero Tenacity     | L   | 0.507      | -            | -                | -                | -         |    -8.19 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           16 |     2760 | 2024-04-17 | HAVU              | W   | 0.493      | -            | -                | -                | -         |     1.76 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           15 |     2763 | 2024-04-17 | Permitta          | L   | 0.492      | -            | -                | -                | -         |   -10.24 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           14 |     2889 | 2024-04-11 | 500               | L   | 0.453      | -            | -                | -                | -         |   -12.31 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           13 |     2924 | 2024-04-10 | Aurora            | L   | 0.447      | -            | -                | -                | -         |    -0.62 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           12 |     2984 | 2024-04-09 | RUSH B            | L   | 0.440      | -            | -                | -                | -         |   -11.02 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           11 |     3155 | 2024-04-03 | MOUZ NXT          | L   | 0.400      | -            | -                | -                | -         |    -7.25 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           10 |     3171 | 2024-04-03 | Space             | W   | 0.399      | -            | -                | -                | -         |     2.15 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            9 |     3209 | 2024-04-02 | AMKAL             | L   | 0.393      | -            | -                | -                | -         |    -5.95 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     3216 | 2024-04-02 | Insilio           | L   | 0.392      | -            | -                | -                | -         |    -9.49 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     3228 | 2024-04-01 | Metizport         | W   | 0.386      | -            | -                | -                | -         |     3.02 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     3399 | 2024-03-21 | FORZE             | W   | 0.313      | -            | -                | -                | -         |     2.47 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     3585 | 2024-03-13 | 3DMAX             | W   | 0.259      | 0.500        | 0.505 (0.065)    | -                | -         |     7.83 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     3703 | 2024-03-08 | B8                | W   | 0.226      | -            | -                | -                | -         |     3.51 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     3759 | 2024-03-06 | Apeks             | W   | 0.213      | -            | -                | -                | -         |     1.80 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     3875 | 2024-03-02 | Gaimin Gladiators | L   | 0.185      | -            | -                | -                | -         |    -3.88 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     3908 | 2024-02-29 | Monte             | L   | 0.172      | -            | -                | -                | -         |    -3.42 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,795.66)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.846 | $6,500.00      | $5,499.27       |
| 2024-05-02 |      0.593 | $500.00        | $296.39         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
