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
Final Rank Value (1020.5) = Starting Rank Value (984.8) + Head To Head Adjustments (35.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.445[<sup>1</sup>](#table2)
- Bounty Collected: 0.398[<sup>2</sup>](#table1)
- Opponent Network: 0.091[<sup>2</sup>](#table1)
- LAN Wins: 0.205[<sup>2</sup>](#table1)

The average of these factors is 0.285<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 984.8
- 400 + ( ( 0.285 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 984.8


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
|           32 |     2337 | 2024-05-07 | FaZe              | L   | 0.595      | -            | -                | -                | -         |    -0.37 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           31 |     2376 | 2024-05-05 | FURIA             | W   | 0.581      | 0.889        | 0.284 (0.147)    | 0.479 (0.248)    | 1 (0.581) |    17.77 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           30 |     2400 | 2024-05-04 | FORZE             | W   | 0.574      | 0.889        | 0.057 (0.029)    | 0.168 (0.086)    | 1 (0.574) |     7.47 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           29 |     2430 | 2024-05-02 | ENCE              | L   | 0.562      | -            | -                | -                | -         |    -1.59 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           28 |     2453 | 2024-05-01 | Liquid            | L   | 0.555      | -            | -                | -                | -         |    -0.61 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           27 |     2477 | 2024-04-30 | FORZE             | W   | 0.549      | 0.889        | 0.057 (0.028)    | 0.168 (0.082)    | 1 (0.549) |     7.15 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           26 |     2732 | 2024-04-19 | OG                | L   | 0.476      | -            | -                | -                | -         |    -6.39 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           25 |     2798 | 2024-04-18 | paiN              | L   | 0.468      | -            | -                | -                | -         |    -1.41 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           24 |     2919 | 2024-04-13 | Rebels            | W   | 0.435      | 0.500        | 0.038 (0.008)    | 0.591 (0.128)    | 0 (0.000) |     7.00 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           23 |     2933 | 2024-04-12 | Sangal            | W   | 0.428      | 0.500        | 0.219 (0.047)    | 0.865 (0.185)    | 0 (0.000) |     9.41 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           22 |     3227 | 2024-04-03 | Metizport         | L   | 0.369      | -            | -                | -                | -         |    -6.78 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           21 |     3237 | 2024-04-03 | Apeks             | W   | 0.368      | -            | -                | -                | 0 (0.000) |     4.51 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           20 |     3265 | 2024-04-02 | GamerLegion       | W   | 0.362      | 0.143        | 0.173 (0.009)    | 0.265 (0.014)    | 0 (0.000) |     7.91 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           19 |     3274 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.361      | -            | -                | -                | -         |    -0.21 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           18 |     3298 | 2024-03-31 | RUSH B            | L   | 0.348      | -            | -                | -                | -         |    -7.24 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           17 |     3328 | 2024-03-28 | Betera            | L   | 0.329      | -            | -                | -                | -         |    -8.66 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           16 |     3396 | 2024-03-26 | System5           | W   | 0.316      | 0.500        | -                | 0.082 (0.013)    | 0 (0.000) |     1.46 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           15 |     3625 | 2024-03-13 | PERA              | W   | 0.229      | 0.500        | 0.048 (0.005)    | 0.445 (0.051)    | 0 (0.000) |     2.94 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           14 |     3728 | 2024-03-09 | Metizport         | L   | 0.202      | -            | -                | -                | -         |    -3.90 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           13 |     3768 | 2024-03-07 | Imperial          | W   | 0.190      | 0.535        | 0.233 (0.024)    | 0.673 (0.068)    | -         |     4.92 | DemQQ, kRaSnaL, leen, sdy, Woro2k   |
|           12 |     3840 | 2024-03-05 | SAW               | L   | 0.176      | -            | -                | -                | -         |    -1.52 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k  |
|           11 |     3905 | 2024-03-03 | Gaimin Gladiators | L   | 0.160      | -            | -                | -                | -         |    -2.72 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|           10 |     3910 | 2024-03-02 | 3DMAX             | L   | 0.156      | -            | -                | -                | -         |    -0.10 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|            9 |     3953 | 2024-02-29 | PARIVISION        | W   | 0.141      | 0.500        | -                | 0.564 (0.040)    | -         |     2.95 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k |
|            8 |     4121 | 2024-02-21 | Astralis          | L   | 0.087      | -            | -                | -                | -         |    -0.04 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            7 |     4151 | 2024-02-20 | Apeks             | L   | 0.080      | -            | -                | -                | -         |    -1.58 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            6 |     4166 | 2024-02-19 | Nexus             | W   | 0.075      | -            | -                | -                | 1 (0.075) |     0.72 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            5 |     4175 | 2024-02-19 | Gaimin Gladiators | L   | 0.074      | -            | -                | -                | -         |    -1.27 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k  |
|            4 |     4185 | 2024-02-18 | Aurora            | W   | 0.069      | 0.143        | 0.421 (0.004)    | -                | -         |     2.14 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            3 |     4191 | 2024-02-18 | SINNERS           | W   | 0.068      | -            | -                | -                | -         |     1.53 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            2 |     4216 | 2024-02-17 | Aurora            | W   | 0.062      | 0.143        | 0.421 (0.004)    | -                | -         |     1.90 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |
|            1 |     4221 | 2024-02-17 | The Chosen Few    | W   | 0.061      | -            | -                | -                | -         |     0.28 | br0, DemQQ, kRaSnaL, sdy, Woro2k    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,234.78)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.815 | $4,000.00      | $3,259.72       |
| 2024-05-12 |      0.628 | $17,500.00     | $10,990.97      |
| 2024-04-20 |      0.483 | $5,000.00      | $2,414.81       |
| 2024-03-10 |      0.209 | $7,500.00      | $1,569.27       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
