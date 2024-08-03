### Roster Details<br />
Team Name: Rhyno<br />
Roster: Ag1l, DDias, krazy, snapy, TMKj<br />
Global Rank: [62](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [43]( ../standings_europe.md)<br />
<br />
Final Rank Value:  976.7<br />
<br />
Final Rank Value (976.7) = Starting Rank Value (967.9) + Head To Head Adjustments (8.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.466[<sup>1</sup>](#table2)
- Bounty Collected: 0.330[<sup>2</sup>](#table1)
- Opponent Network: 0.149[<sup>2</sup>](#table1)
- LAN Wins: 0.166[<sup>2</sup>](#table1)

The average of these factors is 0.278<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 967.9
- 400 + ( ( 0.278 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 967.9


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
|           24 |      168 | 2024-07-30 | Enterprise    | L   | 1.000      | -            | -                | -                | -         |   -18.05 | Ag1l, DDias, krazy, snapy, TMKj        |
|           23 |      381 | 2024-07-23 | FAVBET        | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.353 (0.050)    | 0 (0.000) |     9.93 | Ag1l, DDias, krazy, snapy, TMKj        |
|           22 |      489 | 2024-07-19 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -12.26 | Ag1l, DDias, krazy, snapy, TMKj        |
|           21 |      562 | 2024-07-18 | Nexus         | W   | 1.000      | 0.500        | 0.014 (0.007)    | 0.441 (0.220)    | 0 (0.000) |     5.78 | Ag1l, DDias, krazy, snapy, TMKj        |
|           20 |      628 | 2024-07-17 | HAVU          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.65 | Ag1l, DDias, krazy, snapy, TMKj        |
|           19 |      679 | 2024-07-16 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -12.76 | Ag1l, DDias, krazy, snapy, TMKj        |
|           18 |     1067 | 2024-06-11 | Nemiga        | L   | 0.846      | -            | -                | -                | -         |    -8.01 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           17 |     1089 | 2024-06-10 | CYBERSHOKE    | W   | 0.839      | 0.500        | 0.039 (0.016)    | 0.327 (0.137)    | 0 (0.000) |     9.11 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           16 |     1119 | 2024-06-09 | Rebels        | W   | 0.834      | 0.500        | 0.038 (0.016)    | 0.605 (0.252)    | 0 (0.000) |    14.41 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           15 |     1211 | 2024-06-08 | NAVI Junior   | W   | 0.825      | 0.500        | -                | 0.094 (0.039)    | 0 (0.000) |     2.50 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           14 |     1303 | 2024-06-06 | MOUZ NXT      | L   | 0.814      | -            | -                | -                | -         |    -8.65 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           13 |     1414 | 2024-06-04 | Endpoint      | W   | 0.800      | 0.500        | 0.012 (0.005)    | 0.540 (0.216)    | 0 (0.000) |     9.88 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           12 |     1608 | 2024-05-28 | Sampi         | L   | 0.752      | -            | -                | -                | -         |   -14.39 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           11 |     1632 | 2024-05-27 | Endpoint      | W   | 0.745      | 0.435        | 0.012 (0.004)    | 0.540 (0.175)    | -         |     9.37 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           10 |     1672 | 2024-05-25 | Zero Tenacity | L   | 0.731      | -            | -                | -                | -         |    -8.28 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            9 |     1739 | 2024-05-22 | MOUZ NXT      | W   | 0.712      | 0.435        | 0.139 (0.043)    | 1.000 (0.309)    | -         |    12.64 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            8 |     1776 | 2024-05-21 | B8            | L   | 0.707      | -            | -                | -                | -         |    -6.51 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            7 |     1881 | 2024-05-18 | LEON          | W   | 0.684      | 0.143        | 0.007 (0.001)    | -                | -         |     3.59 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            6 |     1937 | 2024-05-16 | CPH Wolves    | W   | 0.673      | 0.143        | -                | 0.376 (0.036)    | -         |     5.41 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            5 |     2002 | 2024-05-15 | EYEBALLERS    | W   | 0.664      | 0.143        | 0.006 (0.001)    | 0.528 (0.050)    | -         |     7.95 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            4 |     2097 | 2024-05-12 | AL QATRAO     | W   | 0.646      | 0.306        | 0.004 (0.001)    | -                | 1 (0.646) |     3.60 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            3 |     2133 | 2024-05-11 | ALL-IN        | W   | 0.638      | -            | -                | -                | 1 (0.638) |     1.61 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            2 |     3759 | 2024-03-03 | Portugal      | L   | 0.179      | -            | -                | -                | -         |    -4.68 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            1 |     3773 | 2024-03-02 | AL QATRAO     | W   | 0.173      | -            | -                | -                | 1 (0.173) |     0.93 | DDias, krazy, renatoohaxx, snapy, TMKj |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,184.51)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.846 | $25,000.00     | $21,153.94      |
| 2024-05-12 |      0.646 | $2,693.00      | $1,739.35       |
| 2024-03-03 |      0.179 | $1,625.00      | $291.22         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
