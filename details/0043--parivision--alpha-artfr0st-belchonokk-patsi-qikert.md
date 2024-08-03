### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [43](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1094.1<br />
<br />
Final Rank Value (1094.1) = Starting Rank Value (1105.7) + Head To Head Adjustments (-11.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.363[<sup>1</sup>](#table2)
- Bounty Collected: 0.504[<sup>2</sup>](#table1)
- Opponent Network: 0.285[<sup>2</sup>](#table1)
- LAN Wins: 0.228[<sup>2</sup>](#table1)

The average of these factors is 0.345<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1105.7
- 400 + ( ( 0.345 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1105.7


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
|           53 |        3 | 2024-08-03 | GUN5              | L   | 1.000      | -            | -                | -                | -         |   -25.37 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           52 |       18 | 2024-08-03 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.14 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           51 |       25 | 2024-08-02 | TSM               | W   | 1.000      | 0.500        | 0.039 (0.020)    | 0.364 (0.182)    | 0 (0.000) |    10.43 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           50 |       53 | 2024-08-01 | 9 Pandas          | W   | 1.000      | 0.500        | 0.082 (0.041)    | 0.715 (0.357)    | 0 (0.000) |    13.55 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           49 |      162 | 2024-07-30 | Permitta          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.43 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           48 |      263 | 2024-07-26 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -6.57 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           47 |      276 | 2024-07-26 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.72 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           46 |      308 | 2024-07-25 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -5.81 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           45 |      346 | 2024-07-24 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.745 (0.485)    | 1 (1.000) |    30.77 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           44 |      353 | 2024-07-24 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -3.37 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           43 |      997 | 2024-06-14 | Permitta          | L   | 0.865      | -            | -                | -                | -         |   -19.43 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           42 |     1094 | 2024-06-10 | RUSH B            | W   | 0.839      | -            | -                | -                | 0 (0.000) |     8.13 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           41 |     1100 | 2024-06-10 | 3DMAX             | L   | 0.839      | -            | -                | -                | -         |    -3.59 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           40 |     1106 | 2024-06-10 | SINNERS           | L   | 0.838      | -            | -                | -                | -         |   -15.39 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           39 |     1136 | 2024-06-09 | Aurora            | L   | 0.833      | -            | -                | -                | -         |    -3.39 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           38 |     1142 | 2024-06-09 | 9 Pandas          | W   | 0.832      | -            | -                | -                | 0 (0.000) |    12.89 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           37 |     1153 | 2024-06-09 | Monte             | W   | 0.832      | -            | -                | -                | 0 (0.000) |    10.26 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           36 |     1155 | 2024-06-09 | SAW               | L   | 0.832      | -            | -                | -                | -         |    -9.98 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           35 |     1370 | 2024-06-05 | Aurora            | L   | 0.807      | -            | -                | -                | -         |    -2.08 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           34 |     1416 | 2024-06-04 | Monte             | W   | 0.800      | 0.500        | 0.080 (0.032)    | 0.639 (0.255)    | 0 (0.000) |    10.37 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           33 |     1817 | 2024-05-20 | Sangal            | L   | 0.699      | -            | -                | -                | -         |   -10.59 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           32 |     1896 | 2024-05-17 | Zero Tenacity     | W   | 0.680      | 0.500        | 0.137 (0.047)    | 1.000 (0.340)    | -         |    10.50 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           31 |     1927 | 2024-05-16 | Aurora            | L   | 0.674      | -            | -                | -                | -         |    -1.41 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           30 |     1943 | 2024-05-16 | Eternal Fire      | L   | 0.672      | -            | -                | -                | -         |    -0.72 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           29 |     1982 | 2024-05-15 | B8                | W   | 0.667      | 0.500        | 0.166 (0.055)    | 0.945 (0.315)    | -         |    11.62 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     2167 | 2024-05-09 | Endpoint          | L   | 0.626      | -            | -                | -                | -         |   -13.31 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     2323 | 2024-05-01 | Passion UA        | L   | 0.573      | -            | -                | -                | -         |   -10.65 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     2339 | 2024-05-01 | fnatic            | L   | 0.571      | -            | -                | -                | -         |    -3.53 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     2365 | 2024-04-29 | 3DMAX             | L   | 0.560      | -            | -                | -                | -         |    -0.90 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |     2374 | 2024-04-29 | Zero Tenacity     | W   | 0.559      | 0.500        | 0.137 (0.038)    | 1.000 (0.279)    | -         |     8.23 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |     2410 | 2024-04-27 | Sangal            | W   | 0.546      | 0.500        | 0.219 (0.060)    | 0.823 (0.225)    | -         |     9.68 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |     2439 | 2024-04-26 | SINNERS           | W   | 0.539      | 0.435        | -                | 0.784 (0.184)    | -         |     8.70 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |     2468 | 2024-04-25 | ex-Guild Eagles   | W   | 0.533      | -            | -                | -                | -         |     4.17 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |     2487 | 2024-04-24 | MOUZ NXT          | W   | 0.526      | 0.435        | 0.139 (0.032)    | 1.000 (0.229)    | -         |     7.88 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           19 |     2539 | 2024-04-21 | Nexus             | W   | 0.506      | -            | -                | -                | -         |     4.05 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           18 |     2542 | 2024-04-21 | B8                | L   | 0.505      | -            | -                | -                | -         |    -8.21 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           17 |     2598 | 2024-04-19 | Zero Tenacity     | L   | 0.494      | -            | -                | -                | -         |    -7.90 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           16 |     2697 | 2024-04-17 | HAVU              | W   | 0.480      | -            | -                | -                | -         |     1.69 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           15 |     2700 | 2024-04-17 | Permitta          | L   | 0.479      | -            | -                | -                | -         |    -9.76 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           14 |     2824 | 2024-04-11 | 500               | L   | 0.440      | -            | -                | -                | -         |   -12.16 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           13 |     2859 | 2024-04-10 | Aurora            | L   | 0.434      | -            | -                | -                | -         |    -0.61 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           12 |     2919 | 2024-04-09 | RUSH B            | L   | 0.427      | -            | -                | -                | -         |   -10.64 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           11 |     3088 | 2024-04-03 | MOUZ NXT          | L   | 0.387      | -            | -                | -                | -         |    -7.34 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           10 |     3100 | 2024-04-03 | Space             | W   | 0.386      | -            | -                | -                | -         |     2.10 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            9 |     3136 | 2024-04-02 | AMKAL             | L   | 0.380      | -            | -                | -                | -         |    -5.70 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     3143 | 2024-04-02 | Insilio           | L   | 0.379      | -            | -                | -                | -         |    -9.16 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     3155 | 2024-04-01 | Metizport         | W   | 0.373      | -            | -                | -                | -         |     2.95 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     3316 | 2024-03-21 | FORZE             | W   | 0.299      | -            | -                | -                | -         |     2.31 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     3496 | 2024-03-13 | 3DMAX             | W   | 0.246      | 0.500        | 0.504 (0.062)    | -                | -         |     7.43 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     3611 | 2024-03-08 | B8                | W   | 0.213      | -            | -                | -                | -         |     3.26 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     3667 | 2024-03-06 | Apeks             | W   | 0.200      | -            | -                | -                | -         |     1.61 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     3778 | 2024-03-02 | Gaimin Gladiators | L   | 0.172      | -            | -                | -                | -         |    -3.67 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     3810 | 2024-02-29 | Monte             | L   | 0.159      | -            | -                | -                | -         |    -3.23 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,704.59)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.833 | $6,500.00      | $5,414.71       |
| 2024-05-02 |      0.580 | $500.00        | $289.88         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
