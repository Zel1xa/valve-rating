### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, Gizmy, kRaSnaL, ryu, Woro2k<br />
Global Rank: [56](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [40]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1021.4<br />
<br />
Final Rank Value (1021.4) = Starting Rank Value (986.6) + Head To Head Adjustments (34.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.446[<sup>1</sup>](#table2)
- Bounty Collected: 0.399[<sup>2</sup>](#table1)
- Opponent Network: 0.094[<sup>2</sup>](#table1)
- LAN Wins: 0.207[<sup>2</sup>](#table1)

The average of these factors is 0.286<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 986.6
- 400 + ( ( 0.286 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 986.6


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
|           32 |     2322 | 2024-05-07 | FaZe              | L   | 0.601      | -            | -                | -                | -         |    -0.36 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           31 |     2361 | 2024-05-05 | FURIA             | W   | 0.587      | 0.889        | 0.284 (0.148)    | 0.487 (0.254)    | 1 (0.587) |    17.95 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           30 |     2385 | 2024-05-04 | FORZE             | W   | 0.580      | 0.889        | 0.058 (0.030)    | 0.173 (0.089)    | 1 (0.580) |     7.57 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           29 |     2415 | 2024-05-02 | ENCE              | L   | 0.568      | -            | -                | -                | -         |    -1.65 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           28 |     2438 | 2024-05-01 | Liquid            | L   | 0.561      | -            | -                | -                | -         |    -0.61 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           27 |     2462 | 2024-04-30 | FORZE             | W   | 0.555      | 0.889        | 0.058 (0.029)    | 0.173 (0.085)    | 1 (0.555) |     7.24 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           26 |     2717 | 2024-04-19 | OG                | L   | 0.482      | -            | -                | -                | -         |    -6.44 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           25 |     2783 | 2024-04-18 | paiN              | L   | 0.474      | -            | -                | -                | -         |    -1.41 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           24 |     2904 | 2024-04-13 | Rebels            | W   | 0.441      | 0.500        | 0.038 (0.008)    | 0.598 (0.132)    | 0 (0.000) |     7.08 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           23 |     2918 | 2024-04-12 | Sangal            | W   | 0.434      | 0.500        | 0.219 (0.047)    | 0.877 (0.190)    | 0 (0.000) |     9.49 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           22 |     3212 | 2024-04-03 | Metizport         | L   | 0.375      | -            | -                | -                | -         |    -7.81 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           21 |     3222 | 2024-04-03 | Apeks             | W   | 0.373      | -            | -                | -                | 0 (0.000) |     4.59 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           20 |     3250 | 2024-04-02 | GamerLegion       | W   | 0.368      | 0.143        | 0.173 (0.009)    | 0.269 (0.014)    | 0 (0.000) |     8.04 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           19 |     3259 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.367      | -            | -                | -                | -         |    -0.21 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           18 |     3283 | 2024-03-31 | RUSH B            | L   | 0.354      | -            | -                | -                | -         |    -7.39 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           17 |     3313 | 2024-03-28 | Betera            | L   | 0.334      | -            | -                | -                | -         |    -8.83 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           16 |     3381 | 2024-03-26 | System5           | W   | 0.322      | 0.500        | -                | 0.084 (0.014)    | 0 (0.000) |     1.47 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           15 |     3610 | 2024-03-13 | PERA              | W   | 0.235      | 0.500        | 0.048 (0.006)    | 0.451 (0.053)    | 0 (0.000) |     3.01 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           14 |     3713 | 2024-03-09 | Metizport         | L   | 0.208      | -            | -                | -                | -         |    -4.57 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           13 |     3753 | 2024-03-07 | Imperial          | W   | 0.196      | 0.535        | 0.235 (0.025)    | 0.683 (0.071)    | -         |     5.08 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           12 |     3825 | 2024-03-05 | SAW               | L   | 0.182      | -            | -                | -                | -         |    -1.56 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           11 |     3890 | 2024-03-03 | Gaimin Gladiators | L   | 0.166      | -            | -                | -                | -         |    -2.82 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           10 |     3895 | 2024-03-02 | 3DMAX             | L   | 0.162      | -            | -                | -                | -         |    -0.11 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|            9 |     3938 | 2024-02-29 | PARIVISION        | W   | 0.147      | 0.500        | -                | 0.532 (0.039)    | -         |     3.03 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|            8 |     4106 | 2024-02-21 | Astralis          | L   | 0.093      | -            | -                | -                | -         |    -0.05 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            7 |     4136 | 2024-02-20 | Apeks             | L   | 0.086      | -            | -                | -                | -         |    -1.70 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            6 |     4151 | 2024-02-19 | Nexus             | W   | 0.081      | -            | -                | -                | 1 (0.081) |     0.76 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            5 |     4160 | 2024-02-19 | Gaimin Gladiators | L   | 0.080      | -            | -                | -                | -         |    -1.37 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            4 |     4170 | 2024-02-18 | Aurora            | W   | 0.075      | 0.143        | 0.422 (0.005)    | -                | -         |     2.32 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            3 |     4176 | 2024-02-18 | SINNERS           | W   | 0.074      | -            | -                | -                | -         |     1.64 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            2 |     4201 | 2024-02-17 | Aurora            | W   | 0.067      | 0.143        | 0.422 (0.004)    | -                | -         |     2.08 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            1 |     4206 | 2024-02-17 | The Chosen Few    | W   | 0.067      | -            | -                | -                | -         |     0.30 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,433.11)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.821 | $4,000.00      | $3,283.06       |
| 2024-05-12 |      0.634 | $17,500.00     | $11,093.06      |
| 2024-04-20 |      0.489 | $5,000.00      | $2,443.98       |
| 2024-03-10 |      0.215 | $7,500.00      | $1,613.02       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
