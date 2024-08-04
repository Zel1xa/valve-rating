### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, Gizmy, kRaSnaL, ryu, Woro2k<br />
Global Rank: [56](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [40]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1023.5<br />
<br />
Final Rank Value (1023.5) = Starting Rank Value (988.4) + Head To Head Adjustments (35.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.446[<sup>1</sup>](#table2)
- Bounty Collected: 0.400[<sup>2</sup>](#table1)
- Opponent Network: 0.096[<sup>2</sup>](#table1)
- LAN Wins: 0.209[<sup>2</sup>](#table1)

The average of these factors is 0.288<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 988.4
- 400 + ( ( 0.288 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 988.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |     2305 | 2024-05-07 | FaZe              | L   | 0.607      | -            | -                | -                | -         |    -0.36 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           31 |     2344 | 2024-05-05 | FURIA             | W   | 0.593      | 0.889        | 0.284 (0.150)    | 0.490 (0.258)    | 1 (0.593) |    18.10 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           30 |     2368 | 2024-05-04 | FORZE             | W   | 0.585      | 0.889        | 0.058 (0.030)    | 0.176 (0.092)    | 1 (0.585) |     7.64 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           29 |     2398 | 2024-05-02 | ENCE              | L   | 0.574      | -            | -                | -                | -         |    -1.74 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           28 |     2421 | 2024-05-01 | Liquid            | L   | 0.567      | -            | -                | -                | -         |    -0.63 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           27 |     2445 | 2024-04-30 | FORZE             | W   | 0.560      | 0.889        | 0.058 (0.029)    | 0.176 (0.088)    | 1 (0.560) |     7.31 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           26 |     2700 | 2024-04-19 | OG                | L   | 0.487      | -            | -                | -                | -         |    -6.51 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           25 |     2766 | 2024-04-18 | paiN              | L   | 0.480      | -            | -                | -                | -         |    -1.42 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           24 |     2887 | 2024-04-13 | Rebels            | W   | 0.446      | 0.500        | 0.038 (0.009)    | 0.600 (0.134)    | 0 (0.000) |     7.15 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           23 |     2901 | 2024-04-12 | Sangal            | W   | 0.440      | 0.500        | 0.219 (0.048)    | 0.861 (0.189)    | 0 (0.000) |     9.58 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           22 |     3195 | 2024-04-03 | Metizport         | L   | 0.380      | -            | -                | -                | -         |    -7.93 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           21 |     3205 | 2024-04-03 | Apeks             | W   | 0.379      | -            | -                | -                | 0 (0.000) |     4.67 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           20 |     3233 | 2024-04-02 | GamerLegion       | W   | 0.374      | 0.143        | 0.173 (0.009)    | 0.271 (0.014)    | 0 (0.000) |     8.14 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           19 |     3242 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.373      | -            | -                | -                | -         |    -0.21 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           18 |     3266 | 2024-03-31 | RUSH B            | L   | 0.360      | -            | -                | -                | -         |    -7.54 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           17 |     3296 | 2024-03-28 | Betera            | L   | 0.340      | -            | -                | -                | -         |    -9.00 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           16 |     3364 | 2024-03-26 | System5           | W   | 0.327      | 0.500        | -                | 0.085 (0.014)    | 0 (0.000) |     1.49 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           15 |     3593 | 2024-03-13 | PERA              | W   | 0.241      | 0.500        | 0.048 (0.006)    | 0.453 (0.054)    | 0 (0.000) |     3.06 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           14 |     3696 | 2024-03-09 | Metizport         | L   | 0.213      | -            | -                | -                | -         |    -4.70 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           13 |     3736 | 2024-03-07 | Imperial          | W   | 0.201      | 0.535        | 0.236 (0.025)    | 0.685 (0.074)    | -         |     5.24 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           12 |     3808 | 2024-03-05 | SAW               | L   | 0.187      | -            | -                | -                | -         |    -1.61 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           11 |     3873 | 2024-03-03 | Gaimin Gladiators | L   | 0.172      | -            | -                | -                | -         |    -2.90 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           10 |     3878 | 2024-03-02 | 3DMAX             | L   | 0.167      | -            | -                | -                | -         |    -0.11 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|            9 |     3921 | 2024-02-29 | PARIVISION        | W   | 0.152      | 0.500        | -                | 0.534 (0.041)    | -         |     3.12 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|            8 |     4089 | 2024-02-21 | Astralis          | L   | 0.098      | -            | -                | -                | -         |    -0.05 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            7 |     4119 | 2024-02-20 | Apeks             | L   | 0.092      | -            | -                | -                | -         |    -1.81 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            6 |     4134 | 2024-02-19 | Nexus             | W   | 0.087      | -            | -                | -                | 1 (0.087) |     0.80 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            5 |     4143 | 2024-02-19 | Gaimin Gladiators | L   | 0.086      | -            | -                | -                | -         |    -1.47 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            4 |     4153 | 2024-02-18 | Aurora            | W   | 0.081      | 0.143        | 0.423 (0.005)    | -                | -         |     2.49 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            3 |     4159 | 2024-02-18 | SINNERS           | W   | 0.080      | -            | -                | -                | -         |     1.77 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            2 |     4184 | 2024-02-17 | Aurora            | W   | 0.073      | 0.143        | 0.423 (0.004)    | -                | -         |     2.25 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            1 |     4189 | 2024-02-17 | The Chosen Few    | W   | 0.072      | -            | -                | -                | -         |     0.33 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,627.51)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.826 | $4,000.00      | $3,305.93       |
| 2024-05-12 |      0.640 | $17,500.00     | $11,193.11      |
| 2024-04-20 |      0.495 | $5,000.00      | $2,472.57       |
| 2024-03-10 |      0.221 | $7,500.00      | $1,655.90       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
