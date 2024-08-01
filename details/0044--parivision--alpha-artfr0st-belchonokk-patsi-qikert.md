### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [44](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1091.0<br />
<br />
Final Rank Value (1091.0) = Starting Rank Value (1099.1) + Head To Head Adjustments (-8.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.363[<sup>1</sup>](#table2)
- Bounty Collected: 0.504[<sup>2</sup>](#table1)
- Opponent Network: 0.261[<sup>2</sup>](#table1)
- LAN Wins: 0.231[<sup>2</sup>](#table1)

The average of these factors is 0.340<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1099.1
- 400 + ( ( 0.340 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1099.1


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
|           50 |      104 | 2024-07-30 | Permitta          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.79 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           49 |      205 | 2024-07-26 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -6.52 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           48 |      218 | 2024-07-26 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.76 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           47 |      250 | 2024-07-25 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -5.82 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           46 |      288 | 2024-07-24 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.719 (0.468)    | 1 (1.000) |    30.76 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           45 |      295 | 2024-07-24 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -3.40 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           44 |      973 | 2024-06-14 | Permitta          | L   | 0.878      | -            | -                | -                | -         |   -19.54 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           43 |     1076 | 2024-06-10 | RUSH B            | W   | 0.852      | -            | -                | -                | 0 (0.000) |     8.15 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           42 |     1082 | 2024-06-10 | 3DMAX             | L   | 0.852      | -            | -                | -                | -         |    -3.68 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           41 |     1088 | 2024-06-10 | SINNERS           | L   | 0.851      | -            | -                | -                | -         |   -15.76 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           40 |     1119 | 2024-06-09 | Aurora            | L   | 0.846      | -            | -                | -                | -         |    -3.50 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           39 |     1125 | 2024-06-09 | 9 Pandas          | W   | 0.846      | -            | -                | -                | 0 (0.000) |    13.11 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           38 |     1136 | 2024-06-09 | Monte             | W   | 0.845      | -            | -                | -                | 0 (0.000) |    10.44 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           37 |     1139 | 2024-06-09 | SAW               | L   | 0.845      | -            | -                | -                | -         |    -9.95 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           36 |     1372 | 2024-06-05 | Aurora            | L   | 0.820      | -            | -                | -                | -         |    -2.13 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           35 |     1419 | 2024-06-04 | Monte             | W   | 0.813      | 0.500        | 0.081 (0.033)    | 0.614 (0.250)    | 0 (0.000) |    10.57 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           34 |     1846 | 2024-05-20 | Sangal            | L   | 0.712      | -            | -                | -                | -         |   -10.42 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           33 |     1932 | 2024-05-17 | Zero Tenacity     | W   | 0.694      | 0.500        | 0.139 (0.048)    | 1.000 (0.347)    | 0 (0.000) |    10.62 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           32 |     1963 | 2024-05-16 | Aurora            | L   | 0.688      | -            | -                | -                | -         |    -1.44 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           31 |     1979 | 2024-05-16 | Eternal Fire      | L   | 0.685      | -            | -                | -                | -         |    -0.70 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           30 |     2018 | 2024-05-15 | B8                | W   | 0.680      | 0.500        | 0.168 (0.057)    | 0.878 (0.299)    | 0 (0.000) |    11.71 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           29 |     2212 | 2024-05-09 | Endpoint          | L   | 0.639      | -            | -                | -                | -         |   -13.29 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     2373 | 2024-05-01 | Passion UA        | L   | 0.586      | -            | -                | -                | -         |   -10.86 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     2390 | 2024-05-01 | fnatic            | L   | 0.584      | -            | -                | -                | -         |    -3.58 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     2416 | 2024-04-29 | 3DMAX             | L   | 0.573      | -            | -                | -                | -         |    -0.91 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     2425 | 2024-04-29 | Zero Tenacity     | W   | 0.572      | 0.500        | 0.139 (0.040)    | 1.000 (0.286)    | 0 (0.000) |     8.30 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |     2461 | 2024-04-27 | Sangal            | W   | 0.559      | 0.500        | 0.221 (0.062)    | 0.823 (0.230)    | -         |     9.75 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |     2491 | 2024-04-26 | SINNERS           | W   | 0.553      | 0.435        | -                | 0.768 (0.184)    | -         |     8.38 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |     2520 | 2024-04-25 | ex-Guild Eagles   | W   | 0.546      | -            | -                | -                | -         |     4.36 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |     2539 | 2024-04-24 | MOUZ NXT          | W   | 0.539      | 0.435        | 0.141 (0.033)    | 1.000 (0.234)    | -         |     8.38 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |     2570 | 2024-04-23 | B8                | W   | 0.531      | 0.384        | 0.168 (0.034)    | 0.878 (0.179)    | -         |     8.35 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           19 |     2595 | 2024-04-21 | Nexus             | W   | 0.519      | -            | -                | -                | -         |     4.30 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           18 |     2598 | 2024-04-21 | B8                | L   | 0.519      | -            | -                | -                | -         |    -8.16 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           17 |     2657 | 2024-04-19 | Zero Tenacity     | L   | 0.507      | -            | -                | -                | -         |    -8.04 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           16 |     2758 | 2024-04-17 | HAVU              | W   | 0.494      | -            | -                | -                | -         |     1.83 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           15 |     2761 | 2024-04-17 | Permitta          | L   | 0.493      | -            | -                | -                | -         |   -10.03 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           14 |     2887 | 2024-04-11 | 500               | L   | 0.453      | -            | -                | -                | -         |   -12.24 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           13 |     2922 | 2024-04-10 | Aurora            | L   | 0.447      | -            | -                | -                | -         |    -0.59 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           12 |     2982 | 2024-04-09 | RUSH B            | L   | 0.440      | -            | -                | -                | -         |   -10.93 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           11 |     3153 | 2024-04-03 | MOUZ NXT          | L   | 0.400      | -            | -                | -                | -         |    -7.10 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           10 |     3169 | 2024-04-03 | Space             | W   | 0.399      | -            | -                | -                | -         |     2.24 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            9 |     3207 | 2024-04-02 | AMKAL             | L   | 0.393      | -            | -                | -                | -         |    -5.80 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     3214 | 2024-04-02 | Insilio           | L   | 0.392      | -            | -                | -                | -         |    -9.38 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     3226 | 2024-04-01 | Metizport         | W   | 0.386      | -            | -                | -                | -         |     3.14 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     3397 | 2024-03-21 | FORZE             | W   | 0.313      | -            | -                | -                | -         |     2.57 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     3583 | 2024-03-13 | 3DMAX             | W   | 0.259      | 0.500        | 0.505 (0.066)    | 1.000 (0.130)    | -         |     7.86 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     3701 | 2024-03-08 | B8                | W   | 0.226      | 0.500        | 0.168 (0.019)    | -                | -         |     3.60 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     3757 | 2024-03-06 | Apeks             | W   | 0.213      | -            | -                | -                | -         |     1.87 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     3873 | 2024-03-02 | Gaimin Gladiators | L   | 0.186      | -            | -                | -                | -         |    -3.81 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     3906 | 2024-02-29 | Monte             | L   | 0.172      | -            | -                | -                | -         |    -3.36 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,797.60)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.846 | $6,500.00      | $5,501.08       |
| 2024-05-02 |      0.593 | $500.00        | $296.53         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
