### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, Gizmy, kRaSnaL, ryu, Woro2k<br />
Global Rank: [53](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [40]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1028.4<br />
<br />
Final Rank Value (1028.4) = Starting Rank Value (993.9) + Head To Head Adjustments (34.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.450[<sup>1</sup>](#table2)
- Bounty Collected: 0.401[<sup>2</sup>](#table1)
- Opponent Network: 0.099[<sup>2</sup>](#table1)
- LAN Wins: 0.211[<sup>2</sup>](#table1)

The average of these factors is 0.290<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 993.9
- 400 + ( ( 0.290 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 993.9


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
|           33 |     2203 | 2024-05-07 | FaZe              | L   | 0.614      | -            | -                | -                | -         |    -0.37 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           32 |     2242 | 2024-05-05 | FURIA             | W   | 0.599      | 0.889        | 0.284 (0.151)    | 0.508 (0.271)    | 1 (0.599) |    18.27 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           31 |     2266 | 2024-05-04 | FORZE             | W   | 0.592      | 0.889        | 0.059 (0.031)    | 0.186 (0.098)    | 1 (0.592) |     7.66 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           30 |     2296 | 2024-05-02 | ENCE              | L   | 0.580      | -            | -                | -                | -         |    -1.83 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           29 |     2319 | 2024-05-01 | Liquid            | L   | 0.574      | -            | -                | -                | -         |    -1.00 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           28 |     2343 | 2024-04-30 | FORZE             | W   | 0.567      | 0.889        | 0.059 (0.029)    | 0.186 (0.094)    | 1 (0.567) |     7.32 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           27 |     2597 | 2024-04-19 | OG                | L   | 0.494      | -            | -                | -                | -         |    -6.84 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           26 |     2663 | 2024-04-18 | paiN              | L   | 0.486      | -            | -                | -                | -         |    -1.81 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           25 |     2784 | 2024-04-13 | Rebels            | W   | 0.453      | 0.500        | 0.038 (0.009)    | 0.605 (0.137)    | 0 (0.000) |     7.08 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           24 |     2798 | 2024-04-12 | Sangal            | W   | 0.446      | 0.500        | 0.219 (0.049)    | 0.823 (0.184)    | 0 (0.000) |     9.50 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           23 |     3092 | 2024-04-03 | Metizport         | L   | 0.387      | -            | -                | -                | -         |    -7.21 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           22 |     3102 | 2024-04-03 | Apeks             | W   | 0.386      | -            | -                | -                | 0 (0.000) |     4.69 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           21 |     3130 | 2024-04-02 | GamerLegion       | W   | 0.380      | 0.143        | 0.174 (0.009)    | 0.281 (0.015)    | 0 (0.000) |     8.21 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           20 |     3139 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.379      | -            | -                | -                | -         |    -0.34 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           19 |     3163 | 2024-03-31 | RUSH B            | L   | 0.366      | -            | -                | -                | -         |    -7.91 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           18 |     3193 | 2024-03-28 | Betera            | L   | 0.347      | -            | -                | -                | -         |    -9.21 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           17 |     3258 | 2024-03-26 | System5           | W   | 0.334      | 0.500        | -                | 0.088 (0.015)    | 0 (0.000) |     1.48 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           16 |     3484 | 2024-03-13 | PERA              | W   | 0.247      | 0.500        | 0.048 (0.006)    | 0.468 (0.058)    | 0 (0.000) |     3.04 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           15 |     3586 | 2024-03-09 | Metizport         | L   | 0.220      | -            | -                | -                | -         |    -4.33 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           14 |     3625 | 2024-03-07 | Imperial          | W   | 0.208      | 0.535        | 0.234 (0.026)    | 0.708 (0.079)    | -         |     5.23 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           13 |     3697 | 2024-03-05 | SAW               | L   | 0.194      | -            | -                | -                | -         |    -1.68 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           12 |     3762 | 2024-03-03 | Gaimin Gladiators | L   | 0.178      | -            | -                | -                | -         |    -3.02 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           11 |     3767 | 2024-03-02 | 3DMAX             | L   | 0.174      | -            | -                | -                | -         |    -0.12 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           10 |     3810 | 2024-02-29 | PARIVISION        | W   | 0.159      | 0.500        | -                | 0.553 (0.044)    | -         |     3.23 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|            9 |     3979 | 2024-02-21 | Astralis          | L   | 0.105      | -            | -                | -                | -         |    -0.07 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            8 |     4008 | 2024-02-20 | Apeks             | L   | 0.098      | -            | -                | -                | -         |    -1.95 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            7 |     4023 | 2024-02-19 | Nexus             | W   | 0.094      | -            | -                | -                | 1 (0.094) |     0.85 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            6 |     4032 | 2024-02-19 | Gaimin Gladiators | L   | 0.092      | -            | -                | -                | -         |    -1.58 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            5 |     4042 | 2024-02-18 | Aurora            | W   | 0.087      | 0.143        | 0.425 (0.005)    | -                | -         |     2.69 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            4 |     4048 | 2024-02-18 | SINNERS           | W   | 0.086      | -            | -                | -                | -         |     1.71 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            3 |     4072 | 2024-02-17 | Aurora            | W   | 0.080      | 0.143        | 0.425 (0.005)    | -                | -         |     2.46 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            2 |     4077 | 2024-02-17 | The Chosen Few    | W   | 0.079      | -            | -                | -                | -         |     0.35 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            1 |     4277 | 2024-02-06 | G2                | L   | 0.005      | -            | -                | -                | -         |    -0.00 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,486.54)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.833 | $4,000.00      | $3,332.13       |
| 2024-05-12 |      0.646 | $17,500.00     | $11,307.75      |
| 2024-04-20 |      0.501 | $5,000.00      | $2,505.32       |
| 2024-03-10 |      0.227 | $7,500.00      | $1,705.03       |
| 2024-02-11 |      0.040 | $16,000.00     | $636.30         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
