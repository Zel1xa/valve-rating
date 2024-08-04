### Roster Details<br />
Team Name: PARIVISION<br />
Roster: alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert<br />
Global Rank: [44](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1095.7<br />
<br />
Final Rank Value (1095.7) = Starting Rank Value (1102.2) + Head To Head Adjustments (-6.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.363[<sup>1</sup>](#table2)
- Bounty Collected: 0.504[<sup>2</sup>](#table1)
- Opponent Network: 0.280[<sup>2</sup>](#table1)
- LAN Wins: 0.228[<sup>2</sup>](#table1)

The average of these factors is 0.344<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1102.2
- 400 + ( ( 0.344 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1102.2


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
|           53 |        5 | 2024-08-03 | GUN5              | L   | 1.000      | -            | -                | -                | -         |   -25.46 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           52 |       21 | 2024-08-03 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.17 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           51 |       30 | 2024-08-02 | TSM               | W   | 1.000      | 0.500        | 0.040 (0.020)    | 0.353 (0.176)    | 0 (0.000) |    10.29 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           50 |       72 | 2024-08-01 | 9 Pandas          | W   | 1.000      | 0.500        | 0.082 (0.041)    | 0.691 (0.345)    | 0 (0.000) |    13.57 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           49 |      185 | 2024-07-30 | Permitta          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.88 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           48 |      286 | 2024-07-26 | BLEED             | L   | 1.000      | -            | -                | -                | -         |    -6.66 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           47 |      299 | 2024-07-26 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.68 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           46 |      331 | 2024-07-25 | ENCE              | L   | 1.000      | -            | -                | -                | -         |    -5.62 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           45 |      369 | 2024-07-24 | The MongolZ       | W   | 1.000      | 0.650        | 1.000 (0.650)    | 0.720 (0.469)    | 1 (1.000) |    30.77 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           44 |      376 | 2024-07-24 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -3.41 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           43 |     1047 | 2024-06-14 | Permitta          | L   | 0.863      | -            | -                | -                | -         |   -19.13 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           42 |     1148 | 2024-06-10 | RUSH B            | W   | 0.837      | -            | -                | -                | 0 (0.000) |     8.07 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           41 |     1154 | 2024-06-10 | 3DMAX             | L   | 0.837      | -            | -                | -                | -         |    -3.51 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           40 |     1160 | 2024-06-10 | SINNERS           | L   | 0.836      | -            | -                | -                | -         |   -15.31 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           39 |     1191 | 2024-06-09 | Aurora            | L   | 0.831      | -            | -                | -                | -         |    -3.43 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           38 |     1197 | 2024-06-09 | 9 Pandas          | W   | 0.831      | -            | -                | -                | 0 (0.000) |    12.92 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           37 |     1208 | 2024-06-09 | Monte             | W   | 0.830      | -            | -                | -                | 0 (0.000) |    10.51 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           36 |     1210 | 2024-06-09 | SAW               | L   | 0.830      | -            | -                | -                | -         |    -9.84 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           35 |     1430 | 2024-06-05 | Aurora            | L   | 0.805      | -            | -                | -                | -         |    -2.12 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           34 |     1477 | 2024-06-04 | Monte             | W   | 0.798      | 0.500        | 0.080 (0.032)    | 0.618 (0.247)    | 0 (0.000) |    10.65 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           33 |     1882 | 2024-05-20 | Sangal            | L   | 0.697      | -            | -                | -                | -         |    -9.90 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           32 |     1961 | 2024-05-17 | Zero Tenacity     | W   | 0.679      | 0.500        | 0.137 (0.047)    | 1.000 (0.339)    | -         |    10.55 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           31 |     1992 | 2024-05-16 | Aurora            | L   | 0.673      | -            | -                | -                | -         |    -1.43 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           30 |     2008 | 2024-05-16 | Eternal Fire      | L   | 0.670      | -            | -                | -                | -         |    -0.72 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           29 |     2047 | 2024-05-15 | B8                | W   | 0.665      | 0.500        | 0.165 (0.055)    | 0.913 (0.304)    | -         |    11.66 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     2232 | 2024-05-09 | Endpoint          | L   | 0.624      | -            | -                | -                | -         |   -13.33 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     2389 | 2024-05-01 | Passion UA        | L   | 0.571      | -            | -                | -                | -         |   -10.64 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     2405 | 2024-05-01 | fnatic            | L   | 0.569      | -            | -                | -                | -         |    -1.49 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     2431 | 2024-04-29 | 3DMAX             | L   | 0.558      | -            | -                | -                | -         |    -0.86 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |     2440 | 2024-04-29 | Zero Tenacity     | W   | 0.557      | 0.500        | 0.137 (0.038)    | 1.000 (0.278)    | -         |     8.26 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |     2476 | 2024-04-27 | Sangal            | W   | 0.544      | 0.500        | 0.219 (0.060)    | 0.862 (0.235)    | -         |     9.76 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |     2505 | 2024-04-26 | SINNERS           | W   | 0.538      | 0.435        | -                | 0.758 (0.177)    | -         |     8.67 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |     2534 | 2024-04-25 | ex-Guild Eagles   | W   | 0.531      | -            | -                | -                | -         |     4.22 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |     2553 | 2024-04-24 | MOUZ NXT          | W   | 0.524      | 0.435        | 0.139 (0.032)    | 1.000 (0.228)    | -         |     8.02 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           19 |     2605 | 2024-04-21 | Nexus             | W   | 0.504      | -            | -                | -                | -         |     4.03 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           18 |     2608 | 2024-04-21 | B8                | L   | 0.504      | -            | -                | -                | -         |    -8.14 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           17 |     2664 | 2024-04-19 | Zero Tenacity     | L   | 0.492      | -            | -                | -                | -         |    -7.81 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           16 |     2763 | 2024-04-17 | HAVU              | W   | 0.479      | -            | -                | -                | -         |     1.70 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           15 |     2766 | 2024-04-17 | Permitta          | L   | 0.478      | -            | -                | -                | -         |    -9.68 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           14 |     2890 | 2024-04-11 | 500               | L   | 0.438      | -            | -                | -                | -         |   -12.09 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           13 |     2925 | 2024-04-10 | Aurora            | L   | 0.432      | -            | -                | -                | -         |    -0.61 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           12 |     2985 | 2024-04-09 | RUSH B            | L   | 0.425      | -            | -                | -                | -         |   -10.59 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           11 |     3154 | 2024-04-03 | MOUZ NXT          | L   | 0.385      | -            | -                | -                | -         |    -7.16 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           10 |     3166 | 2024-04-03 | Space             | W   | 0.384      | -            | -                | -                | -         |     2.10 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            9 |     3202 | 2024-04-02 | AMKAL             | L   | 0.378      | -            | -                | -                | -         |    -5.66 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     3209 | 2024-04-02 | Insilio           | L   | 0.377      | -            | -                | -                | -         |    -9.11 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     3221 | 2024-04-01 | Metizport         | W   | 0.371      | -            | -                | -                | -         |     2.97 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     3387 | 2024-03-21 | FORZE             | W   | 0.298      | -            | -                | -                | -         |     2.33 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     3568 | 2024-03-13 | 3DMAX             | W   | 0.244      | 0.500        | 0.505 (0.062)    | -                | -         |     7.38 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     3684 | 2024-03-08 | B8                | W   | 0.211      | -            | -                | -                | -         |     3.24 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     3740 | 2024-03-06 | Apeks             | W   | 0.198      | -            | -                | -                | -         |     1.62 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     3851 | 2024-03-02 | Gaimin Gladiators | L   | 0.171      | -            | -                | -                | -         |    -3.64 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     3883 | 2024-02-29 | Monte             | L   | 0.157      | -            | -                | -                | -         |    -3.19 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,692.60)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.831 | $6,500.00      | $5,403.58       |
| 2024-05-02 |      0.578 | $500.00        | $289.03         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
