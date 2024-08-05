### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, Gizmy, kRaSnaL, ryu, Woro2k<br />
Global Rank: [56](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [40]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1022.6<br />
<br />
Final Rank Value (1022.6) = Starting Rank Value (987.6) + Head To Head Adjustments (35.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.446[<sup>1</sup>](#table2)
- Bounty Collected: 0.399[<sup>2</sup>](#table1)
- Opponent Network: 0.095[<sup>2</sup>](#table1)
- LAN Wins: 0.208[<sup>2</sup>](#table1)

The average of these factors is 0.287<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 987.6
- 400 + ( ( 0.287 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 987.6


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
|           32 |     2309 | 2024-05-07 | FaZe              | L   | 0.605      | -            | -                | -                | -         |    -0.36 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           31 |     2348 | 2024-05-05 | FURIA             | W   | 0.590      | 0.889        | 0.284 (0.149)    | 0.490 (0.257)    | 1 (0.590) |    18.04 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           30 |     2372 | 2024-05-04 | FORZE             | W   | 0.583      | 0.889        | 0.058 (0.030)    | 0.175 (0.091)    | 1 (0.583) |     7.62 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           29 |     2402 | 2024-05-02 | ENCE              | L   | 0.571      | -            | -                | -                | -         |    -1.68 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           28 |     2425 | 2024-05-01 | Liquid            | L   | 0.565      | -            | -                | -                | -         |    -0.62 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           27 |     2449 | 2024-04-30 | FORZE             | W   | 0.558      | 0.889        | 0.058 (0.029)    | 0.175 (0.087)    | 1 (0.558) |     7.29 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           26 |     2704 | 2024-04-19 | OG                | L   | 0.485      | -            | -                | -                | -         |    -6.47 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           25 |     2770 | 2024-04-18 | paiN              | L   | 0.477      | -            | -                | -                | -         |    -1.42 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           24 |     2891 | 2024-04-13 | Rebels            | W   | 0.444      | 0.500        | 0.038 (0.008)    | 0.600 (0.133)    | 0 (0.000) |     7.12 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           23 |     2905 | 2024-04-12 | Sangal            | W   | 0.437      | 0.500        | 0.219 (0.048)    | 0.861 (0.188)    | 0 (0.000) |     9.54 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           22 |     3199 | 2024-04-03 | Metizport         | L   | 0.378      | -            | -                | -                | -         |    -7.88 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           21 |     3209 | 2024-04-03 | Apeks             | W   | 0.377      | -            | -                | -                | 0 (0.000) |     4.63 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           20 |     3237 | 2024-04-02 | GamerLegion       | W   | 0.371      | 0.143        | 0.173 (0.009)    | 0.271 (0.014)    | 0 (0.000) |     8.12 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           19 |     3246 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.370      | -            | -                | -                | -         |    -0.21 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           18 |     3270 | 2024-03-31 | RUSH B            | L   | 0.357      | -            | -                | -                | -         |    -7.48 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           17 |     3300 | 2024-03-28 | Betera            | L   | 0.338      | -            | -                | -                | -         |    -8.93 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           16 |     3368 | 2024-03-26 | System5           | W   | 0.325      | 0.500        | -                | 0.084 (0.014)    | 0 (0.000) |     1.48 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           15 |     3597 | 2024-03-13 | PERA              | W   | 0.238      | 0.500        | 0.048 (0.006)    | 0.453 (0.054)    | 0 (0.000) |     3.03 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           14 |     3700 | 2024-03-09 | Metizport         | L   | 0.211      | -            | -                | -                | -         |    -4.65 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           13 |     3740 | 2024-03-07 | Imperial          | W   | 0.199      | 0.535        | 0.236 (0.025)    | 0.685 (0.073)    | -         |     5.17 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           12 |     3812 | 2024-03-05 | SAW               | L   | 0.185      | -            | -                | -                | -         |    -1.59 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           11 |     3877 | 2024-03-03 | Gaimin Gladiators | L   | 0.169      | -            | -                | -                | -         |    -2.87 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           10 |     3882 | 2024-03-02 | 3DMAX             | L   | 0.165      | -            | -                | -                | -         |    -0.11 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|            9 |     3925 | 2024-02-29 | PARIVISION        | W   | 0.150      | 0.500        | -                | 0.534 (0.040)    | -         |     3.08 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|            8 |     4093 | 2024-02-21 | Astralis          | L   | 0.096      | -            | -                | -                | -         |    -0.05 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            7 |     4123 | 2024-02-20 | Apeks             | L   | 0.089      | -            | -                | -                | -         |    -1.76 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            6 |     4138 | 2024-02-19 | Nexus             | W   | 0.085      | -            | -                | -                | 1 (0.085) |     0.78 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            5 |     4147 | 2024-02-19 | Gaimin Gladiators | L   | 0.083      | -            | -                | -                | -         |    -1.43 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            4 |     4157 | 2024-02-18 | Aurora            | W   | 0.078      | 0.143        | 0.423 (0.005)    | -                | -         |     2.42 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            3 |     4163 | 2024-02-18 | SINNERS           | W   | 0.077      | -            | -                | -                | -         |     1.72 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            2 |     4188 | 2024-02-17 | Aurora            | W   | 0.071      | 0.143        | 0.423 (0.004)    | -                | -         |     2.18 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            1 |     4193 | 2024-02-17 | The Chosen Few    | W   | 0.070      | -            | -                | -                | -         |     0.32 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,546.45)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.824 | $4,000.00      | $3,296.39       |
| 2024-05-12 |      0.637 | $17,500.00     | $11,151.39      |
| 2024-04-20 |      0.492 | $5,000.00      | $2,460.65       |
| 2024-03-10 |      0.218 | $7,500.00      | $1,638.02       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
