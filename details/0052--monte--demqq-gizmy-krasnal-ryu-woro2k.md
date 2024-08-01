### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, Gizmy, kRaSnaL, ryu, Woro2k<br />
Global Rank: [52](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1040.6<br />
<br />
Final Rank Value (1040.6) = Starting Rank Value (1006.4) + Head To Head Adjustments (34.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.452[<sup>1</sup>](#table2)
- Bounty Collected: 0.404[<sup>2</sup>](#table1)
- Opponent Network: 0.101[<sup>2</sup>](#table1)
- LAN Wins: 0.221[<sup>2</sup>](#table1)

The average of these factors is 0.295<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1006.4
- 400 + ( ( 0.295 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1006.4


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
|           35 |     2253 | 2024-05-07 | FaZe              | L   | 0.627      | -            | -                | -                | -         |    -0.36 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           34 |     2292 | 2024-05-05 | FURIA             | W   | 0.612      | 0.889        | 0.286 (0.156)    | 0.494 (0.269)    | 1 (0.612) |    18.66 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           33 |     2316 | 2024-05-04 | FORZE             | W   | 0.605      | 0.889        | 0.060 (0.032)    | 0.186 (0.100)    | 1 (0.605) |     7.77 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           32 |     2346 | 2024-05-02 | ENCE              | L   | 0.593      | -            | -                | -                | -         |    -1.89 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           31 |     2371 | 2024-05-01 | Liquid            | L   | 0.587      | -            | -                | -                | -         |    -0.99 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           30 |     2396 | 2024-04-30 | FORZE             | W   | 0.580      | 0.889        | 0.060 (0.031)    | 0.186 (0.096)    | 1 (0.580) |     7.43 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           29 |     2658 | 2024-04-19 | OG                | L   | 0.507      | -            | -                | -                | -         |    -7.09 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           28 |     2725 | 2024-04-18 | paiN              | L   | 0.499      | -            | -                | -                | -         |    -1.97 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           27 |     2848 | 2024-04-13 | Rebels            | W   | 0.466      | 0.500        | 0.040 (0.009)    | 0.635 (0.148)    | 0 (0.000) |     7.24 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           26 |     2862 | 2024-04-12 | Sangal            | W   | 0.459      | 0.500        | 0.221 (0.051)    | 0.823 (0.189)    | 0 (0.000) |     9.45 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           25 |     3159 | 2024-04-03 | Metizport         | L   | 0.400      | -            | -                | -                | -         |    -7.63 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           24 |     3173 | 2024-04-03 | Apeks             | W   | 0.399      | -            | -                | -                | 0 (0.000) |     4.87 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           23 |     3203 | 2024-04-02 | GamerLegion       | W   | 0.393      | 0.143        | 0.176 (0.010)    | 0.273 (0.015)    | 0 (0.000) |     8.43 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           22 |     3212 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.392      | -            | -                | -                | -         |    -0.51 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           21 |     3236 | 2024-03-31 | RUSH B            | L   | 0.379      | -            | -                | -                | -         |    -8.40 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           20 |     3266 | 2024-03-28 | Betera            | L   | 0.360      | -            | -                | -                | -         |    -9.63 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           19 |     3337 | 2024-03-26 | System5           | W   | 0.347      | 0.500        | -                | 0.086 (0.015)    | 0 (0.000) |     1.47 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           18 |     3573 | 2024-03-13 | PERA              | W   | 0.260      | 0.500        | 0.048 (0.006)    | 0.452 (0.059)    | -         |     3.09 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           17 |     3678 | 2024-03-09 | Metizport         | L   | 0.233      | -            | -                | -                | -         |    -4.71 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           16 |     3717 | 2024-03-07 | Imperial          | W   | 0.221      | 0.535        | 0.239 (0.028)    | 0.719 (0.085)    | -         |     5.71 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           15 |     3789 | 2024-03-05 | SAW               | L   | 0.207      | -            | -                | -                | -         |    -1.82 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           14 |     3859 | 2024-03-03 | Gaimin Gladiators | L   | 0.191      | -            | -                | -                | -         |    -3.24 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           13 |     3864 | 2024-03-02 | 3DMAX             | L   | 0.187      | -            | -                | -                | -         |    -0.14 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           12 |     3908 | 2024-02-29 | PARIVISION        | W   | 0.172      | 0.500        | -                | 0.457 (0.039)    | -         |     3.42 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           11 |     4086 | 2024-02-21 | Astralis          | L   | 0.118      | -            | -                | -                | -         |    -0.08 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|           10 |     4115 | 2024-02-20 | Apeks             | L   | 0.111      | -            | -                | -                | -         |    -2.21 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            9 |     4130 | 2024-02-19 | Nexus             | W   | 0.107      | -            | -                | -                | 1 (0.107) |     0.93 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            8 |     4139 | 2024-02-19 | Gaimin Gladiators | L   | 0.105      | -            | -                | -                | -         |    -1.81 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            7 |     4149 | 2024-02-18 | Aurora            | W   | 0.100      | 0.143        | 0.431 (0.006)    | -                | -         |     3.09 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            6 |     4155 | 2024-02-18 | SINNERS           | W   | 0.099      | -            | -                | -                | -         |     1.76 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            5 |     4179 | 2024-02-17 | Aurora            | W   | 0.093      | 0.143        | 0.431 (0.006)    | -                | -         |     2.86 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            4 |     4184 | 2024-02-17 | The Chosen Few    | W   | 0.092      | -            | -                | -                | -         |     0.39 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            3 |     4395 | 2024-02-06 | G2                | L   | 0.018      | -            | -                | -                | -         |    -0.00 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            2 |     4405 | 2024-02-05 | Cloud9            | W   | 0.012      | -            | -                | -                | 1 (0.012) |     0.21 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            1 |     4427 | 2024-02-04 | GamerLegion       | L   | 0.005      | -            | -                | -                | -         |    -0.13 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,137.00)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.846 | $4,000.00      | $3,384.17       |
| 2024-05-12 |      0.659 | $17,500.00     | $11,535.42      |
| 2024-04-20 |      0.514 | $5,000.00      | $2,570.37       |
| 2024-03-10 |      0.240 | $7,500.00      | $1,802.60       |
| 2024-02-11 |      0.053 | $16,000.00     | $844.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
