### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, Gizmy, kRaSnaL, ryu, Woro2k<br />
Global Rank: [56](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [41]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1025.0<br />
<br />
Final Rank Value (1025.0) = Starting Rank Value (988.8) + Head To Head Adjustments (36.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.446[<sup>1</sup>](#table2)
- Bounty Collected: 0.400[<sup>2</sup>](#table1)
- Opponent Network: 0.096[<sup>2</sup>](#table1)
- LAN Wins: 0.209[<sup>2</sup>](#table1)

The average of these factors is 0.288<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 988.8
- 400 + ( ( 0.288 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 988.8


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
|           32 |     2281 | 2024-05-07 | FaZe              | L   | 0.608      | -            | -                | -                | -         |    -0.37 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           31 |     2320 | 2024-05-05 | FURIA             | W   | 0.594      | 0.889        | 0.284 (0.150)    | 0.490 (0.259)    | 1 (0.594) |    18.13 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           30 |     2344 | 2024-05-04 | FORZE             | W   | 0.586      | 0.889        | 0.058 (0.030)    | 0.177 (0.092)    | 1 (0.586) |     7.63 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           29 |     2374 | 2024-05-02 | ENCE              | L   | 0.575      | -            | -                | -                | -         |    -1.76 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           28 |     2397 | 2024-05-01 | Liquid            | L   | 0.568      | -            | -                | -                | -         |    -0.64 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           27 |     2421 | 2024-04-30 | FORZE             | W   | 0.561      | 0.889        | 0.058 (0.029)    | 0.177 (0.088)    | 1 (0.561) |     7.30 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           26 |     2676 | 2024-04-19 | OG                | L   | 0.488      | -            | -                | -                | -         |    -6.55 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           25 |     2742 | 2024-04-18 | paiN              | L   | 0.481      | -            | -                | -                | -         |    -1.43 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           24 |     2863 | 2024-04-13 | Rebels            | W   | 0.447      | 0.500        | 0.038 (0.009)    | 0.599 (0.134)    | 0 (0.000) |     7.12 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           23 |     2877 | 2024-04-12 | Sangal            | W   | 0.441      | 0.500        | 0.219 (0.048)    | 0.861 (0.190)    | 0 (0.000) |     9.51 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           22 |     3171 | 2024-04-03 | Metizport         | L   | 0.381      | -            | -                | -                | -         |    -7.04 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           21 |     3181 | 2024-04-03 | Apeks             | W   | 0.380      | -            | -                | -                | 0 (0.000) |     4.68 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           20 |     3209 | 2024-04-02 | GamerLegion       | W   | 0.375      | 0.143        | 0.174 (0.009)    | 0.271 (0.015)    | 0 (0.000) |     8.15 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           19 |     3218 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.374      | -            | -                | -                | -         |    -0.22 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           18 |     3242 | 2024-03-31 | RUSH B            | L   | 0.361      | -            | -                | -                | -         |    -7.58 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           17 |     3272 | 2024-03-28 | Betera            | L   | 0.341      | -            | -                | -                | -         |    -9.03 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           16 |     3340 | 2024-03-26 | System5           | W   | 0.328      | 0.500        | -                | 0.085 (0.014)    | 0 (0.000) |     1.49 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           15 |     3569 | 2024-03-13 | PERA              | W   | 0.242      | 0.500        | 0.048 (0.006)    | 0.453 (0.055)    | 0 (0.000) |     3.06 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           14 |     3672 | 2024-03-09 | Metizport         | L   | 0.214      | -            | -                | -                | -         |    -4.17 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           13 |     3712 | 2024-03-07 | Imperial          | W   | 0.203      | 0.535        | 0.237 (0.026)    | 0.685 (0.074)    | -         |     5.27 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           12 |     3784 | 2024-03-05 | SAW               | L   | 0.188      | -            | -                | -                | -         |    -1.63 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           11 |     3849 | 2024-03-03 | Gaimin Gladiators | L   | 0.173      | -            | -                | -                | -         |    -2.93 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           10 |     3854 | 2024-03-02 | 3DMAX             | L   | 0.168      | -            | -                | -                | -         |    -0.12 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|            9 |     3897 | 2024-02-29 | PARIVISION        | W   | 0.153      | 0.500        | -                | 0.534 (0.041)    | -         |     3.13 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|            8 |     4065 | 2024-02-21 | Astralis          | L   | 0.100      | -            | -                | -                | -         |    -0.05 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            7 |     4095 | 2024-02-20 | Apeks             | L   | 0.093      | -            | -                | -                | -         |    -1.83 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            6 |     4110 | 2024-02-19 | Nexus             | W   | 0.088      | -            | -                | -                | 1 (0.088) |     0.81 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            5 |     4119 | 2024-02-19 | Gaimin Gladiators | L   | 0.087      | -            | -                | -                | -         |    -1.49 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            4 |     4129 | 2024-02-18 | Aurora            | W   | 0.082      | 0.143        | 0.423 (0.005)    | -                | -         |     2.52 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            3 |     4135 | 2024-02-18 | SINNERS           | W   | 0.081      | -            | -                | -                | -         |     1.60 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            2 |     4160 | 2024-02-17 | Aurora            | W   | 0.074      | 0.143        | 0.423 (0.004)    | -                | -         |     2.29 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            1 |     4165 | 2024-02-17 | The Chosen Few    | W   | 0.073      | -            | -                | -                | -         |     0.33 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,663.72)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.828 | $4,000.00      | $3,310.19       |
| 2024-05-12 |      0.641 | $17,500.00     | $11,211.75      |
| 2024-04-20 |      0.496 | $5,000.00      | $2,477.89       |
| 2024-03-10 |      0.222 | $7,500.00      | $1,663.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
