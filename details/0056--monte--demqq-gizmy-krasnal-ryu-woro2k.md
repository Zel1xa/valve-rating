### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, Gizmy, kRaSnaL, ryu, Woro2k<br />
Global Rank: [56](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [40]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1021.2<br />
<br />
Final Rank Value (1021.2) = Starting Rank Value (986.5) + Head To Head Adjustments (34.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.446[<sup>1</sup>](#table2)
- Bounty Collected: 0.398[<sup>2</sup>](#table1)
- Opponent Network: 0.093[<sup>2</sup>](#table1)
- LAN Wins: 0.207[<sup>2</sup>](#table1)

The average of these factors is 0.286<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 986.5
- 400 + ( ( 0.286 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 986.5


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
|           32 |     2330 | 2024-05-07 | FaZe              | L   | 0.600      | -            | -                | -                | -         |    -0.36 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           31 |     2369 | 2024-05-05 | FURIA             | W   | 0.586      | 0.889        | 0.284 (0.148)    | 0.481 (0.251)    | 1 (0.586) |    17.91 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           30 |     2393 | 2024-05-04 | FORZE             | W   | 0.578      | 0.889        | 0.058 (0.030)    | 0.171 (0.088)    | 1 (0.578) |     7.57 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           29 |     2423 | 2024-05-02 | ENCE              | L   | 0.567      | -            | -                | -                | -         |    -1.62 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           28 |     2446 | 2024-05-01 | Liquid            | L   | 0.560      | -            | -                | -                | -         |    -0.61 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           27 |     2470 | 2024-04-30 | FORZE             | W   | 0.553      | 0.889        | 0.058 (0.028)    | 0.171 (0.084)    | 1 (0.553) |     7.24 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           26 |     2725 | 2024-04-19 | OG                | L   | 0.481      | -            | -                | -                | -         |    -6.42 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           25 |     2791 | 2024-04-18 | paiN              | L   | 0.473      | -            | -                | -                | -         |    -1.41 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           24 |     2912 | 2024-04-13 | Rebels            | W   | 0.439      | 0.500        | 0.038 (0.008)    | 0.591 (0.130)    | 0 (0.000) |     7.05 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           23 |     2926 | 2024-04-12 | Sangal            | W   | 0.433      | 0.500        | 0.219 (0.047)    | 0.866 (0.187)    | 0 (0.000) |     9.48 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           22 |     3220 | 2024-04-03 | Metizport         | L   | 0.373      | -            | -                | -                | -         |    -7.78 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           21 |     3230 | 2024-04-03 | Apeks             | W   | 0.372      | -            | -                | -                | 0 (0.000) |     4.57 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           20 |     3258 | 2024-04-02 | GamerLegion       | W   | 0.367      | 0.143        | 0.173 (0.009)    | 0.266 (0.014)    | 0 (0.000) |     8.02 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           19 |     3267 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.366      | -            | -                | -                | -         |    -0.21 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           18 |     3291 | 2024-03-31 | RUSH B            | L   | 0.353      | -            | -                | -                | -         |    -7.36 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           17 |     3321 | 2024-03-28 | Betera            | L   | 0.333      | -            | -                | -                | -         |    -8.80 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           16 |     3389 | 2024-03-26 | System5           | W   | 0.321      | 0.500        | -                | 0.083 (0.013)    | 0 (0.000) |     1.47 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           15 |     3618 | 2024-03-13 | PERA              | W   | 0.234      | 0.500        | 0.048 (0.006)    | 0.446 (0.052)    | 0 (0.000) |     2.99 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           14 |     3721 | 2024-03-09 | Metizport         | L   | 0.206      | -            | -                | -                | -         |    -4.54 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           13 |     3761 | 2024-03-07 | Imperial          | W   | 0.195      | 0.535        | 0.235 (0.024)    | 0.674 (0.070)    | -         |     5.05 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           12 |     3833 | 2024-03-05 | SAW               | L   | 0.181      | -            | -                | -                | -         |    -1.56 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           11 |     3898 | 2024-03-03 | Gaimin Gladiators | L   | 0.165      | -            | -                | -                | -         |    -2.80 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           10 |     3903 | 2024-03-02 | 3DMAX             | L   | 0.161      | -            | -                | -                | -         |    -0.11 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|            9 |     3946 | 2024-02-29 | PARIVISION        | W   | 0.146      | 0.500        | -                | 0.565 (0.041)    | -         |     3.03 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|            8 |     4114 | 2024-02-21 | Astralis          | L   | 0.092      | -            | -                | -                | -         |    -0.05 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            7 |     4144 | 2024-02-20 | Apeks             | L   | 0.085      | -            | -                | -                | -         |    -1.68 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            6 |     4159 | 2024-02-19 | Nexus             | W   | 0.080      | -            | -                | -                | 1 (0.080) |     0.75 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            5 |     4168 | 2024-02-19 | Gaimin Gladiators | L   | 0.079      | -            | -                | -                | -         |    -1.35 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            4 |     4178 | 2024-02-18 | Aurora            | W   | 0.074      | 0.143        | 0.422 (0.004)    | -                | -         |     2.28 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            3 |     4184 | 2024-02-18 | SINNERS           | W   | 0.073      | -            | -                | -                | -         |     1.64 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            2 |     4209 | 2024-02-17 | Aurora            | W   | 0.066      | 0.143        | 0.422 (0.004)    | -                | -         |     2.04 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            1 |     4214 | 2024-02-17 | The Chosen Few    | W   | 0.066      | -            | -                | -                | -         |     0.30 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,395.34)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.820 | $4,000.00      | $3,278.61       |
| 2024-05-12 |      0.633 | $17,500.00     | $11,073.61      |
| 2024-04-20 |      0.488 | $5,000.00      | $2,438.43       |
| 2024-03-10 |      0.214 | $7,500.00      | $1,604.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
