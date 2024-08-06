### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, Gizmy, kRaSnaL, ryu, Woro2k<br />
Global Rank: [55](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [40]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1022.2<br />
<br />
Final Rank Value (1022.2) = Starting Rank Value (986.3) + Head To Head Adjustments (35.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.445[<sup>1</sup>](#table2)
- Bounty Collected: 0.400[<sup>2</sup>](#table1)
- Opponent Network: 0.089[<sup>2</sup>](#table1)
- LAN Wins: 0.205[<sup>2</sup>](#table1)

The average of these factors is 0.285<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 986.3
- 400 + ( ( 0.285 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 986.3


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
|           32 |     2356 | 2024-05-07 | FaZe              | L   | 0.594      | -            | -                | -                | -         |    -0.37 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           31 |     2395 | 2024-05-05 | FURIA             | W   | 0.579      | 0.889        | 0.284 (0.146)    | 0.468 (0.241)    | 1 (0.579) |    17.71 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           30 |     2419 | 2024-05-04 | FORZE             | W   | 0.572      | 0.889        | 0.057 (0.029)    | 0.163 (0.083)    | 1 (0.572) |     7.44 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           29 |     2449 | 2024-05-02 | ENCE              | L   | 0.560      | -            | -                | -                | -         |    -1.58 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           28 |     2472 | 2024-05-01 | Liquid            | L   | 0.554      | -            | -                | -                | -         |    -0.61 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           27 |     2496 | 2024-04-30 | FORZE             | W   | 0.547      | 0.889        | 0.057 (0.028)    | 0.163 (0.079)    | 1 (0.547) |     7.11 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           26 |     2751 | 2024-04-19 | OG                | L   | 0.474      | -            | -                | -                | -         |    -6.42 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           25 |     2817 | 2024-04-18 | paiN              | L   | 0.466      | -            | -                | -                | -         |    -1.44 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           24 |     2938 | 2024-04-13 | Rebels            | W   | 0.433      | 0.500        | 0.038 (0.008)    | 0.578 (0.125)    | 0 (0.000) |     6.97 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           23 |     2952 | 2024-04-12 | Sangal            | W   | 0.426      | 0.500        | 0.288 (0.061)    | 0.858 (0.183)    | 0 (0.000) |     9.77 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           22 |     3246 | 2024-04-03 | Metizport         | L   | 0.367      | -            | -                | -                | -         |    -6.69 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           21 |     3256 | 2024-04-03 | Apeks             | W   | 0.366      | -            | -                | -                | 0 (0.000) |     4.47 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           20 |     3284 | 2024-04-02 | GamerLegion       | W   | 0.360      | 0.143        | 0.173 (0.009)    | 0.259 (0.013)    | 0 (0.000) |     7.84 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           19 |     3293 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.359      | -            | -                | -                | -         |    -0.21 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           18 |     3317 | 2024-03-31 | RUSH B            | L   | 0.347      | -            | -                | -                | -         |    -7.21 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           17 |     3347 | 2024-03-28 | Betera            | L   | 0.327      | -            | -                | -                | -         |    -8.62 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           16 |     3415 | 2024-03-26 | System5           | W   | 0.314      | 0.500        | -                | 0.080 (0.013)    | 0 (0.000) |     1.44 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           15 |     3644 | 2024-03-13 | PERA              | W   | 0.227      | 0.500        | 0.047 (0.005)    | 0.435 (0.049)    | 0 (0.000) |     2.90 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           14 |     3747 | 2024-03-09 | Metizport         | L   | 0.200      | -            | -                | -                | -         |    -3.83 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           13 |     3787 | 2024-03-07 | Imperial          | W   | 0.188      | 0.535        | 0.233 (0.023)    | 0.658 (0.066)    | -         |     4.86 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           12 |     3859 | 2024-03-05 | SAW               | L   | 0.174      | -            | -                | -                | -         |    -1.51 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           11 |     3924 | 2024-03-03 | Gaimin Gladiators | L   | 0.158      | -            | -                | -                | -         |    -2.70 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           10 |     3929 | 2024-03-02 | 3DMAX             | L   | 0.154      | -            | -                | -                | -         |    -0.10 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|            9 |     3972 | 2024-02-29 | PARIVISION        | W   | 0.139      | 0.500        | -                | 0.590 (0.041)    | -         |     3.11 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|            8 |     4140 | 2024-02-21 | Astralis          | L   | 0.085      | -            | -                | -                | -         |    -0.04 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            7 |     4170 | 2024-02-20 | Apeks             | L   | 0.078      | -            | -                | -                | -         |    -1.55 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            6 |     4185 | 2024-02-19 | Nexus             | W   | 0.074      | -            | -                | -                | 1 (0.074) |     0.70 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            5 |     4194 | 2024-02-19 | Gaimin Gladiators | L   | 0.072      | -            | -                | -                | -         |    -1.25 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            4 |     4204 | 2024-02-18 | Aurora            | W   | 0.068      | 0.143        | 0.420 (0.004)    | -                | -         |     2.08 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            3 |     4210 | 2024-02-18 | SINNERS           | W   | 0.067      | -            | -                | -                | -         |     1.49 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            2 |     4235 | 2024-02-17 | Aurora            | W   | 0.060      | 0.143        | 0.420 (0.004)    | -                | -         |     1.84 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            1 |     4240 | 2024-02-17 | The Chosen Few    | W   | 0.059      | -            | -                | -                | -         |     0.27 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,173.39)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.813 | $4,000.00      | $3,252.50       |
| 2024-05-12 |      0.626 | $17,500.00     | $10,959.38      |
| 2024-04-20 |      0.481 | $5,000.00      | $2,405.79       |
| 2024-03-10 |      0.207 | $7,500.00      | $1,555.73       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
