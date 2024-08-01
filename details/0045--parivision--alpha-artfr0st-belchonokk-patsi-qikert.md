### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [45](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1091.7<br />
<br />
Final Rank Value (1091.7) = Starting Rank Value (1100.1) + Head To Head Adjustments (-8.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.363[<sup>1</sup>](#table2)
- Bounty Collected: 0.505[<sup>2</sup>](#table1)
- Opponent Network: 0.261[<sup>2</sup>](#table1)
- LAN Wins: 0.231[<sup>2</sup>](#table1)

The average of these factors is 0.340<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1100.1
- 400 + ( ( 0.340 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1100.1


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
|           50 |      100 | 2024-07-30 | Permitta          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.74 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           49 |      201 | 2024-07-26 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -6.52 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           48 |      214 | 2024-07-26 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.75 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           47 |      246 | 2024-07-25 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -5.87 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           46 |      284 | 2024-07-24 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.719 (0.468)    | 1 (1.000) |    30.75 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           45 |      291 | 2024-07-24 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -3.42 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           44 |      969 | 2024-06-14 | Permitta          | L   | 0.880      | -            | -                | -                | -         |   -19.57 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           43 |     1072 | 2024-06-10 | RUSH B            | W   | 0.854      | -            | -                | -                | 0 (0.000) |     8.16 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           42 |     1078 | 2024-06-10 | 3DMAX             | L   | 0.853      | -            | -                | -                | -         |    -3.69 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           41 |     1084 | 2024-06-10 | SINNERS           | L   | 0.853      | -            | -                | -                | -         |   -15.79 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           40 |     1115 | 2024-06-09 | Aurora            | L   | 0.847      | -            | -                | -                | -         |    -3.52 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           39 |     1121 | 2024-06-09 | 9 Pandas          | W   | 0.847      | -            | -                | -                | 0 (0.000) |    13.14 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           38 |     1132 | 2024-06-09 | Monte             | W   | 0.847      | -            | -                | -                | 0 (0.000) |    10.45 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           37 |     1135 | 2024-06-09 | SAW               | L   | 0.846      | -            | -                | -                | -         |    -9.95 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           36 |     1368 | 2024-06-05 | Aurora            | L   | 0.821      | -            | -                | -                | -         |    -2.15 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           35 |     1415 | 2024-06-04 | Monte             | W   | 0.815      | 0.500        | 0.081 (0.033)    | 0.614 (0.250)    | 0 (0.000) |    10.59 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           34 |     1842 | 2024-05-20 | Sangal            | L   | 0.713      | -            | -                | -                | -         |   -10.48 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           33 |     1928 | 2024-05-17 | Zero Tenacity     | W   | 0.695      | 0.500        | 0.139 (0.048)    | 1.000 (0.347)    | 0 (0.000) |    10.64 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           32 |     1959 | 2024-05-16 | Aurora            | L   | 0.689      | -            | -                | -                | -         |    -1.45 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           31 |     1975 | 2024-05-16 | Eternal Fire      | L   | 0.687      | -            | -                | -                | -         |    -0.70 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           30 |     2014 | 2024-05-15 | B8                | W   | 0.682      | 0.500        | 0.168 (0.057)    | 0.878 (0.299)    | 0 (0.000) |    11.74 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           29 |     2208 | 2024-05-09 | Endpoint          | L   | 0.641      | -            | -                | -                | -         |   -13.32 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     2369 | 2024-05-01 | Passion UA        | L   | 0.588      | -            | -                | -                | -         |   -10.89 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     2386 | 2024-05-01 | fnatic            | L   | 0.586      | -            | -                | -                | -         |    -3.58 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     2412 | 2024-04-29 | 3DMAX             | L   | 0.575      | -            | -                | -                | -         |    -0.92 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     2421 | 2024-04-29 | Zero Tenacity     | W   | 0.573      | 0.500        | 0.139 (0.040)    | 1.000 (0.287)    | 0 (0.000) |     8.31 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |     2457 | 2024-04-27 | Sangal            | W   | 0.561      | 0.500        | 0.221 (0.062)    | 0.823 (0.231)    | -         |     9.78 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |     2487 | 2024-04-26 | SINNERS           | W   | 0.554      | 0.435        | -                | 0.768 (0.185)    | -         |     8.40 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |     2516 | 2024-04-25 | ex-Guild Eagles   | W   | 0.547      | -            | -                | -                | -         |     4.37 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |     2535 | 2024-04-24 | MOUZ NXT          | W   | 0.541      | 0.435        | 0.141 (0.033)    | 1.000 (0.235)    | -         |     8.40 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |     2566 | 2024-04-23 | B8                | W   | 0.532      | 0.384        | 0.168 (0.034)    | 0.878 (0.180)    | -         |     8.37 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           19 |     2591 | 2024-04-21 | Nexus             | W   | 0.521      | -            | -                | -                | -         |     4.31 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           18 |     2594 | 2024-04-21 | B8                | L   | 0.520      | -            | -                | -                | -         |    -8.18 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           17 |     2653 | 2024-04-19 | Zero Tenacity     | L   | 0.508      | -            | -                | -                | -         |    -8.06 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           16 |     2754 | 2024-04-17 | HAVU              | W   | 0.495      | -            | -                | -                | -         |     1.83 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           15 |     2757 | 2024-04-17 | Permitta          | L   | 0.494      | -            | -                | -                | -         |   -10.06 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           14 |     2883 | 2024-04-11 | 500               | L   | 0.454      | -            | -                | -                | -         |   -12.28 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           13 |     2918 | 2024-04-10 | Aurora            | L   | 0.448      | -            | -                | -                | -         |    -0.60 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           12 |     2978 | 2024-04-09 | RUSH B            | L   | 0.442      | -            | -                | -                | -         |   -10.96 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           11 |     3149 | 2024-04-03 | MOUZ NXT          | L   | 0.402      | -            | -                | -                | -         |    -7.13 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           10 |     3165 | 2024-04-03 | Space             | W   | 0.401      | -            | -                | -                | -         |     2.24 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            9 |     3203 | 2024-04-02 | AMKAL             | L   | 0.394      | -            | -                | -                | -         |    -5.82 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     3210 | 2024-04-02 | Insilio           | L   | 0.394      | -            | -                | -                | -         |    -9.42 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     3222 | 2024-04-01 | Metizport         | W   | 0.388      | -            | -                | -                | -         |     3.14 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     3393 | 2024-03-21 | FORZE             | W   | 0.314      | -            | -                | -                | -         |     2.58 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     3579 | 2024-03-13 | 3DMAX             | W   | 0.261      | 0.500        | 0.505 (0.066)    | 1.000 (0.130)    | -         |     7.90 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     3697 | 2024-03-08 | B8                | W   | 0.228      | 0.500        | 0.168 (0.019)    | -                | -         |     3.63 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     3753 | 2024-03-06 | Apeks             | W   | 0.214      | -            | -                | -                | -         |     1.89 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     3869 | 2024-03-02 | Gaimin Gladiators | L   | 0.187      | -            | -                | -                | -         |    -3.84 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     3902 | 2024-02-29 | Monte             | L   | 0.174      | -            | -                | -                | -         |    -3.38 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,807.33)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.848 | $6,500.00      | $5,510.10       |
| 2024-05-02 |      0.594 | $500.00        | $297.22         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
