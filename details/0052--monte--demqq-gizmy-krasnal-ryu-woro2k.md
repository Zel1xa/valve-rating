### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, Gizmy, kRaSnaL, ryu, Woro2k<br />
Global Rank: [52](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1041.5<br />
<br />
Final Rank Value (1041.5) = Starting Rank Value (1007.9) + Head To Head Adjustments (33.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.453[<sup>1</sup>](#table2)
- Bounty Collected: 0.404[<sup>2</sup>](#table1)
- Opponent Network: 0.102[<sup>2</sup>](#table1)
- LAN Wins: 0.222[<sup>2</sup>](#table1)

The average of these factors is 0.295<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1007.9
- 400 + ( ( 0.295 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1007.9


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
|           35 |     2247 | 2024-05-07 | FaZe              | L   | 0.628      | -            | -                | -                | -         |    -0.36 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           34 |     2286 | 2024-05-05 | FURIA             | W   | 0.614      | 0.889        | 0.286 (0.156)    | 0.495 (0.270)    | 1 (0.614) |    18.71 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           33 |     2310 | 2024-05-04 | FORZE             | W   | 0.607      | 0.889        | 0.060 (0.032)    | 0.186 (0.100)    | 1 (0.607) |     7.80 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           32 |     2340 | 2024-05-02 | ENCE              | L   | 0.595      | -            | -                | -                | -         |    -1.89 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           31 |     2365 | 2024-05-01 | Liquid            | L   | 0.588      | -            | -                | -                | -         |    -1.40 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           30 |     2390 | 2024-04-30 | FORZE             | W   | 0.582      | 0.889        | 0.060 (0.031)    | 0.186 (0.096)    | 1 (0.582) |     7.45 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           29 |     2652 | 2024-04-19 | OG                | L   | 0.509      | -            | -                | -                | -         |    -7.12 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           28 |     2719 | 2024-04-18 | paiN              | L   | 0.501      | -            | -                | -                | -         |    -1.97 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           27 |     2842 | 2024-04-13 | Rebels            | W   | 0.468      | 0.500        | 0.040 (0.009)    | 0.635 (0.148)    | 0 (0.000) |     7.26 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           26 |     2856 | 2024-04-12 | Sangal            | W   | 0.461      | 0.500        | 0.221 (0.051)    | 0.823 (0.190)    | 0 (0.000) |     9.48 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           25 |     3153 | 2024-04-03 | Metizport         | L   | 0.402      | -            | -                | -                | -         |    -7.68 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           24 |     3167 | 2024-04-03 | Apeks             | W   | 0.400      | -            | -                | -                | 0 (0.000) |     4.89 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           23 |     3197 | 2024-04-02 | GamerLegion       | W   | 0.395      | 0.143        | 0.176 (0.010)    | 0.273 (0.015)    | 0 (0.000) |     8.45 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           22 |     3206 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.394      | -            | -                | -                | -         |    -0.70 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           21 |     3230 | 2024-03-31 | RUSH B            | L   | 0.381      | -            | -                | -                | -         |    -8.45 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           20 |     3260 | 2024-03-28 | Betera            | L   | 0.361      | -            | -                | -                | -         |    -9.69 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           19 |     3331 | 2024-03-26 | System5           | W   | 0.349      | 0.500        | -                | 0.086 (0.015)    | 0 (0.000) |     1.47 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           18 |     3567 | 2024-03-13 | PERA              | W   | 0.262      | 0.500        | 0.048 (0.006)    | 0.452 (0.059)    | -         |     3.09 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           17 |     3672 | 2024-03-09 | Metizport         | L   | 0.235      | -            | -                | -                | -         |    -4.75 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           16 |     3711 | 2024-03-07 | Imperial          | W   | 0.223      | 0.535        | 0.240 (0.029)    | 0.719 (0.086)    | -         |     5.75 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           15 |     3783 | 2024-03-05 | SAW               | L   | 0.209      | -            | -                | -                | -         |    -1.83 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           14 |     3853 | 2024-03-03 | Gaimin Gladiators | L   | 0.193      | -            | -                | -                | -         |    -3.27 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           13 |     3858 | 2024-03-02 | 3DMAX             | L   | 0.189      | -            | -                | -                | -         |    -0.14 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           12 |     3902 | 2024-02-29 | PARIVISION        | W   | 0.174      | 0.500        | -                | 0.451 (0.039)    | -         |     3.38 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           11 |     4080 | 2024-02-21 | Astralis          | L   | 0.120      | -            | -                | -                | -         |    -0.08 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|           10 |     4109 | 2024-02-20 | Apeks             | L   | 0.113      | -            | -                | -                | -         |    -2.25 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            9 |     4124 | 2024-02-19 | Nexus             | W   | 0.108      | -            | -                | -                | 1 (0.108) |     0.94 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            8 |     4133 | 2024-02-19 | Gaimin Gladiators | L   | 0.107      | -            | -                | -                | -         |    -1.84 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            7 |     4143 | 2024-02-18 | Aurora            | W   | 0.102      | 0.143        | 0.432 (0.006)    | -                | -         |     3.15 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            6 |     4149 | 2024-02-18 | SINNERS           | W   | 0.101      | -            | -                | -                | -         |     1.78 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            5 |     4173 | 2024-02-17 | Aurora            | W   | 0.094      | 0.143        | 0.432 (0.006)    | -                | -         |     2.91 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            4 |     4178 | 2024-02-17 | The Chosen Few    | W   | 0.094      | -            | -                | -                | -         |     0.40 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            3 |     4389 | 2024-02-06 | G2                | L   | 0.020      | -            | -                | -                | -         |    -0.00 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            2 |     4399 | 2024-02-05 | Cloud9            | W   | 0.013      | -            | -                | -                | 1 (0.013) |     0.24 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            1 |     4421 | 2024-02-04 | GamerLegion       | L   | 0.007      | -            | -                | -                | -         |    -0.17 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,220.34)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.848 | $4,000.00      | $3,390.83       |
| 2024-05-12 |      0.661 | $17,500.00     | $11,564.58      |
| 2024-04-20 |      0.516 | $5,000.00      | $2,578.70       |
| 2024-03-10 |      0.242 | $7,500.00      | $1,815.10       |
| 2024-02-11 |      0.054 | $16,000.00     | $871.11         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
