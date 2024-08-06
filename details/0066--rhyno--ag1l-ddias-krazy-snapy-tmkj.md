### Roster Details<br />
Team Name: Rhyno<br />
Roster: Ag1l, DDias, krazy, snapy, TMKj<br />
Global Rank: [66](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [48]( ../standings_europe.md)<br />
<br />
Final Rank Value:  986.8<br />
<br />
Final Rank Value (986.8) = Starting Rank Value (964.8) + Head To Head Adjustments (21.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.465[<sup>1</sup>](#table2)
- Bounty Collected: 0.330[<sup>2</sup>](#table1)
- Opponent Network: 0.142[<sup>2</sup>](#table1)
- LAN Wins: 0.162[<sup>2</sup>](#table1)

The average of these factors is 0.275<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 964.8
- 400 + ( ( 0.275 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 964.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |       25 | 2024-08-05 | Meteor        | W   | 1.000      | 0.143        | 0.014 (0.002)    | -                | 0 (0.000) |     7.37 | Ag1l, DDias, krazy, snapy, TMKj        |
|           24 |      266 | 2024-07-30 | Enterprise    | L   | 1.000      | -            | -                | -                | -         |   -17.99 | Ag1l, DDias, krazy, snapy, TMKj        |
|           23 |      478 | 2024-07-23 | FAVBET        | W   | 1.000      | 0.143        | -                | 0.364 (0.052)    | 0 (0.000) |    10.08 | Ag1l, DDias, krazy, snapy, TMKj        |
|           22 |      586 | 2024-07-19 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -11.74 | Ag1l, DDias, krazy, snapy, TMKj        |
|           21 |      659 | 2024-07-18 | Nexus         | W   | 1.000      | 0.500        | 0.014 (0.007)    | 0.447 (0.223)    | 0 (0.000) |     6.30 | Ag1l, DDias, krazy, snapy, TMKj        |
|           20 |      729 | 2024-07-17 | HAVU          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.58 | Ag1l, DDias, krazy, snapy, TMKj        |
|           19 |      778 | 2024-07-16 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -12.18 | Ag1l, DDias, krazy, snapy, TMKj        |
|           18 |     1196 | 2024-06-11 | Nemiga        | L   | 0.827      | -            | -                | -                | -         |    -7.48 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           17 |     1218 | 2024-06-10 | CYBERSHOKE    | W   | 0.821      | 0.500        | 0.039 (0.016)    | 0.339 (0.139)    | 0 (0.000) |     8.78 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           16 |     1249 | 2024-06-09 | Rebels        | W   | 0.815      | 0.500        | 0.038 (0.016)    | 0.578 (0.236)    | 0 (0.000) |    14.12 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           15 |     1346 | 2024-06-08 | NAVI Junior   | W   | 0.807      | 0.500        | 0.003 (0.001)    | 0.115 (0.046)    | 0 (0.000) |     5.17 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           14 |     1438 | 2024-06-06 | MOUZ NXT      | L   | 0.795      | -            | -                | -                | -         |    -8.10 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           13 |     1549 | 2024-06-04 | Endpoint      | W   | 0.782      | 0.500        | 0.012 (0.005)    | 0.502 (0.196)    | -         |     9.75 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           12 |     1746 | 2024-05-28 | Sampi         | L   | 0.733      | -            | -                | -                | -         |   -13.98 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           11 |     1770 | 2024-05-27 | Endpoint      | W   | 0.727      | 0.435        | 0.012 (0.004)    | 0.502 (0.158)    | -         |     9.23 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           10 |     1811 | 2024-05-25 | Zero Tenacity | L   | 0.712      | -            | -                | -                | -         |    -7.85 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            9 |     1878 | 2024-05-22 | MOUZ NXT      | W   | 0.693      | 0.435        | 0.139 (0.042)    | 0.962 (0.290)    | -         |    12.57 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            8 |     1915 | 2024-05-21 | B8            | L   | 0.688      | -            | -                | -                | -         |    -6.19 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            7 |     2021 | 2024-05-18 | LEON          | W   | 0.666      | 0.143        | 0.007 (0.001)    | -                | -         |     3.54 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            6 |     2077 | 2024-05-16 | CPH Wolves    | W   | 0.654      | 0.143        | -                | 0.353 (0.033)    | -         |     5.36 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            5 |     2142 | 2024-05-15 | EYEBALLERS    | W   | 0.646      | 0.143        | -                | 0.488 (0.045)    | -         |     7.85 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            4 |     2237 | 2024-05-12 | AL QATRAO     | W   | 0.627      | 0.306        | 0.004 (0.001)    | -                | 1 (0.627) |     3.53 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            3 |     2273 | 2024-05-11 | ALL-IN        | W   | 0.619      | -            | -                | -                | 1 (0.619) |     1.58 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            2 |     3909 | 2024-03-03 | Portugal      | L   | 0.160      | -            | -                | -                | -         |    -4.19 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            1 |     3923 | 2024-03-02 | AL QATRAO     | W   | 0.154      | -            | -                | -                | 1 (0.154) |     0.84 | DDias, krazy, renatoohaxx, snapy, TMKj |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($22,634.80)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.827 | $25,000.00     | $20,685.19      |
| 2024-05-12 |      0.627 | $2,693.00      | $1,688.86       |
| 2024-03-03 |      0.160 | $1,625.00      | $260.75         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
