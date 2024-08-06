### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, Gizmy, kRaSnaL, ryu, Woro2k<br />
Global Rank: [56](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [40]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1020.5<br />
<br />
Final Rank Value (1020.5) = Starting Rank Value (984.9) + Head To Head Adjustments (35.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.445[<sup>1</sup>](#table2)
- Bounty Collected: 0.397[<sup>2</sup>](#table1)
- Opponent Network: 0.090[<sup>2</sup>](#table1)
- LAN Wins: 0.205[<sup>2</sup>](#table1)

The average of these factors is 0.284<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 984.9
- 400 + ( ( 0.284 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 984.9


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
|           32 |     2344 | 2024-05-07 | FaZe              | L   | 0.595      | -            | -                | -                | -         |    -0.37 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           31 |     2383 | 2024-05-05 | FURIA             | W   | 0.581      | 0.889        | 0.284 (0.147)    | 0.469 (0.242)    | 1 (0.581) |    17.75 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           30 |     2407 | 2024-05-04 | FORZE             | W   | 0.573      | 0.889        | 0.057 (0.029)    | 0.164 (0.084)    | 1 (0.573) |     7.49 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           29 |     2437 | 2024-05-02 | ENCE              | L   | 0.562      | -            | -                | -                | -         |    -1.58 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           28 |     2460 | 2024-05-01 | Liquid            | L   | 0.555      | -            | -                | -                | -         |    -0.60 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           27 |     2484 | 2024-04-30 | FORZE             | W   | 0.548      | 0.889        | 0.057 (0.028)    | 0.164 (0.080)    | 1 (0.548) |     7.17 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           26 |     2739 | 2024-04-19 | OG                | L   | 0.475      | -            | -                | -                | -         |    -6.39 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           25 |     2805 | 2024-04-18 | paiN              | L   | 0.467      | -            | -                | -                | -         |    -1.42 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           24 |     2926 | 2024-04-13 | Rebels            | W   | 0.434      | 0.500        | 0.038 (0.008)    | 0.578 (0.125)    | 0 (0.000) |     7.00 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           23 |     2940 | 2024-04-12 | Sangal            | W   | 0.427      | 0.500        | 0.219 (0.047)    | 0.846 (0.181)    | 0 (0.000) |     9.40 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           22 |     3234 | 2024-04-03 | Metizport         | L   | 0.368      | -            | -                | -                | -         |    -6.76 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           21 |     3244 | 2024-04-03 | Apeks             | W   | 0.367      | -            | -                | -                | 0 (0.000) |     4.51 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           20 |     3272 | 2024-04-02 | GamerLegion       | W   | 0.362      | 0.143        | 0.173 (0.009)    | 0.259 (0.013)    | 0 (0.000) |     7.88 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           19 |     3281 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.360      | -            | -                | -                | -         |    -0.21 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           18 |     3305 | 2024-03-31 | RUSH B            | L   | 0.348      | -            | -                | -                | -         |    -7.23 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           17 |     3335 | 2024-03-28 | Betera            | L   | 0.328      | -            | -                | -                | -         |    -8.64 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           16 |     3403 | 2024-03-26 | System5           | W   | 0.315      | 0.500        | -                | 0.081 (0.013)    | 0 (0.000) |     1.46 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           15 |     3632 | 2024-03-13 | PERA              | W   | 0.229      | 0.500        | 0.048 (0.005)    | 0.435 (0.050)    | 0 (0.000) |     2.93 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           14 |     3735 | 2024-03-09 | Metizport         | L   | 0.201      | -            | -                | -                | -         |    -3.88 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           13 |     3775 | 2024-03-07 | Imperial          | W   | 0.189      | 0.535        | 0.233 (0.024)    | 0.658 (0.067)    | -         |     4.90 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           12 |     3847 | 2024-03-05 | SAW               | L   | 0.175      | -            | -                | -                | -         |    -1.52 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           11 |     3912 | 2024-03-03 | Gaimin Gladiators | L   | 0.159      | -            | -                | -                | -         |    -2.71 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           10 |     3917 | 2024-03-02 | 3DMAX             | L   | 0.155      | -            | -                | -                | -         |    -0.10 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|            9 |     3960 | 2024-02-29 | PARIVISION        | W   | 0.140      | 0.500        | -                | 0.590 (0.041)    | -         |     2.94 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|            8 |     4128 | 2024-02-21 | Astralis          | L   | 0.086      | -            | -                | -                | -         |    -0.04 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            7 |     4158 | 2024-02-20 | Apeks             | L   | 0.080      | -            | -                | -                | -         |    -1.57 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            6 |     4173 | 2024-02-19 | Nexus             | W   | 0.075      | -            | -                | -                | 1 (0.075) |     0.71 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            5 |     4182 | 2024-02-19 | Gaimin Gladiators | L   | 0.073      | -            | -                | -                | -         |    -1.26 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            4 |     4192 | 2024-02-18 | Aurora            | W   | 0.069      | 0.143        | 0.420 (0.004)    | -                | -         |     2.12 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            3 |     4198 | 2024-02-18 | SINNERS           | W   | 0.068      | -            | -                | -                | -         |     1.52 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            2 |     4223 | 2024-02-17 | Aurora            | W   | 0.061      | 0.143        | 0.420 (0.004)    | -                | -         |     1.88 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            1 |     4228 | 2024-02-17 | The Chosen Few    | W   | 0.060      | -            | -                | -                | -         |     0.28 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,212.74)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.814 | $4,000.00      | $3,257.13       |
| 2024-05-12 |      0.627 | $17,500.00     | $10,979.63      |
| 2024-04-20 |      0.482 | $5,000.00      | $2,411.57       |
| 2024-03-10 |      0.209 | $7,500.00      | $1,564.41       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
