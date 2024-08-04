### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, Gizmy, kRaSnaL, ryu, Woro2k<br />
Global Rank: [54](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [41]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1027.1<br />
<br />
Final Rank Value (1027.1) = Starting Rank Value (991.6) + Head To Head Adjustments (35.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.450[<sup>1</sup>](#table2)
- Bounty Collected: 0.401[<sup>2</sup>](#table1)
- Opponent Network: 0.097[<sup>2</sup>](#table1)
- LAN Wins: 0.210[<sup>2</sup>](#table1)

The average of these factors is 0.290<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 991.6
- 400 + ( ( 0.290 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 991.6


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
|           33 |     2269 | 2024-05-07 | FaZe              | L   | 0.612      | -            | -                | -                | -         |    -0.38 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           32 |     2308 | 2024-05-05 | FURIA             | W   | 0.598      | 0.889        | 0.284 (0.151)    | 0.491 (0.261)    | 1 (0.598) |    18.23 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           31 |     2332 | 2024-05-04 | FORZE             | W   | 0.590      | 0.889        | 0.058 (0.031)    | 0.179 (0.094)    | 1 (0.590) |     7.67 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           30 |     2362 | 2024-05-02 | ENCE              | L   | 0.579      | -            | -                | -                | -         |    -1.80 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           29 |     2385 | 2024-05-01 | Liquid            | L   | 0.572      | -            | -                | -                | -         |    -1.01 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           28 |     2409 | 2024-04-30 | FORZE             | W   | 0.565      | 0.889        | 0.058 (0.029)    | 0.179 (0.090)    | 1 (0.565) |     7.33 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           27 |     2663 | 2024-04-19 | OG                | L   | 0.492      | -            | -                | -                | -         |    -6.63 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           26 |     2729 | 2024-04-18 | paiN              | L   | 0.485      | -            | -                | -                | -         |    -1.45 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           25 |     2850 | 2024-04-13 | Rebels            | W   | 0.451      | 0.500        | 0.038 (0.009)    | 0.599 (0.135)    | 0 (0.000) |     7.14 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           24 |     2864 | 2024-04-12 | Sangal            | W   | 0.444      | 0.500        | 0.219 (0.049)    | 0.862 (0.191)    | 0 (0.000) |     9.54 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           23 |     3158 | 2024-04-03 | Metizport         | L   | 0.385      | -            | -                | -                | -         |    -7.16 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           22 |     3168 | 2024-04-03 | Apeks             | W   | 0.384      | -            | -                | -                | 0 (0.000) |     4.72 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           21 |     3196 | 2024-04-02 | GamerLegion       | W   | 0.379      | 0.143        | 0.174 (0.009)    | 0.271 (0.015)    | 0 (0.000) |     8.22 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           20 |     3205 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.377      | -            | -                | -                | -         |    -0.24 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           19 |     3229 | 2024-03-31 | RUSH B            | L   | 0.365      | -            | -                | -                | -         |    -7.88 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           18 |     3259 | 2024-03-28 | Betera            | L   | 0.345      | -            | -                | -                | -         |    -9.15 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           17 |     3327 | 2024-03-26 | System5           | W   | 0.332      | 0.500        | -                | 0.085 (0.014)    | 0 (0.000) |     1.48 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           16 |     3556 | 2024-03-13 | PERA              | W   | 0.246      | 0.500        | 0.048 (0.006)    | 0.453 (0.056)    | 0 (0.000) |     3.05 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           15 |     3658 | 2024-03-09 | Metizport         | L   | 0.218      | -            | -                | -                | -         |    -4.27 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           14 |     3698 | 2024-03-07 | Imperial          | W   | 0.206      | 0.535        | 0.238 (0.026)    | 0.685 (0.076)    | -         |     5.36 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           13 |     3770 | 2024-03-05 | SAW               | L   | 0.192      | -            | -                | -                | -         |    -1.68 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           12 |     3835 | 2024-03-03 | Gaimin Gladiators | L   | 0.176      | -            | -                | -                | -         |    -3.00 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           11 |     3840 | 2024-03-02 | 3DMAX             | L   | 0.172      | -            | -                | -                | -         |    -0.12 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           10 |     3883 | 2024-02-29 | PARIVISION        | W   | 0.157      | 0.500        | -                | 0.534 (0.042)    | -         |     3.19 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|            9 |     4051 | 2024-02-21 | Astralis          | L   | 0.103      | -            | -                | -                | -         |    -0.07 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            8 |     4081 | 2024-02-20 | Apeks             | L   | 0.097      | -            | -                | -                | -         |    -1.91 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            7 |     4096 | 2024-02-19 | Nexus             | W   | 0.092      | -            | -                | -                | 1 (0.092) |     0.84 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            6 |     4105 | 2024-02-19 | Gaimin Gladiators | L   | 0.090      | -            | -                | -                | -         |    -1.56 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            5 |     4115 | 2024-02-18 | Aurora            | W   | 0.086      | 0.143        | 0.424 (0.005)    | -                | -         |     2.64 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            4 |     4121 | 2024-02-18 | SINNERS           | W   | 0.085      | -            | -                | -                | -         |     1.67 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            3 |     4145 | 2024-02-17 | Aurora            | W   | 0.078      | 0.143        | 0.424 (0.005)    | -                | -         |     2.40 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            2 |     4150 | 2024-02-17 | The Chosen Few    | W   | 0.077      | -            | -                | -                | -         |     0.35 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            1 |     4350 | 2024-02-06 | G2                | L   | 0.004      | -            | -                | -                | -         |     0.00 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,400.89)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.831 | $4,000.00      | $3,325.28       |
| 2024-05-12 |      0.644 | $17,500.00     | $11,277.78      |
| 2024-04-20 |      0.499 | $5,000.00      | $2,496.76       |
| 2024-03-10 |      0.226 | $7,500.00      | $1,692.19       |
| 2024-02-11 |      0.038 | $16,000.00     | $608.89         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
