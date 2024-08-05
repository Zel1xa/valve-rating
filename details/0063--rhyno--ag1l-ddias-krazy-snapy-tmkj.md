### Roster Details<br />
Team Name: Rhyno<br />
Roster: Ag1l, DDias, krazy, snapy, TMKj<br />
Global Rank: [63](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [45]( ../standings_europe.md)<br />
<br />
Final Rank Value:  984.1<br />
<br />
Final Rank Value (984.1) = Starting Rank Value (965.5) + Head To Head Adjustments (18.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.465[<sup>1</sup>](#table2)
- Bounty Collected: 0.330[<sup>2</sup>](#table1)
- Opponent Network: 0.146[<sup>2</sup>](#table1)
- LAN Wins: 0.163[<sup>2</sup>](#table1)

The average of these factors is 0.276<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 965.5
- 400 + ( ( 0.276 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 965.5


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
|           25 |        4 | 2024-08-05 | Meteor        | W   | 1.000      | 0.143        | 0.014 (0.002)    | -                | 0 (0.000) |     7.37 | Ag1l, DDias, krazy, snapy, TMKj        |
|           24 |      243 | 2024-07-30 | Enterprise    | L   | 1.000      | -            | -                | -                | -         |   -18.04 | Ag1l, DDias, krazy, snapy, TMKj        |
|           23 |      456 | 2024-07-23 | FAVBET        | W   | 1.000      | 0.143        | -                | 0.338 (0.048)    | 0 (0.000) |     9.95 | Ag1l, DDias, krazy, snapy, TMKj        |
|           22 |      564 | 2024-07-19 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -11.79 | Ag1l, DDias, krazy, snapy, TMKj        |
|           21 |      637 | 2024-07-18 | Nexus         | W   | 1.000      | 0.500        | 0.014 (0.007)    | 0.464 (0.232)    | 0 (0.000) |     6.26 | Ag1l, DDias, krazy, snapy, TMKj        |
|           20 |      707 | 2024-07-17 | HAVU          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.64 | Ag1l, DDias, krazy, snapy, TMKj        |
|           19 |      756 | 2024-07-16 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -12.23 | Ag1l, DDias, krazy, snapy, TMKj        |
|           18 |     1174 | 2024-06-11 | Nemiga        | L   | 0.834      | -            | -                | -                | -         |    -7.46 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           17 |     1196 | 2024-06-10 | CYBERSHOKE    | W   | 0.827      | 0.500        | 0.039 (0.016)    | 0.351 (0.145)    | 0 (0.000) |     8.90 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           16 |     1227 | 2024-06-09 | Rebels        | W   | 0.821      | 0.500        | 0.038 (0.016)    | 0.598 (0.246)    | 0 (0.000) |    14.30 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           15 |     1324 | 2024-06-08 | NAVI Junior   | W   | 0.813      | 0.500        | -                | 0.090 (0.037)    | 0 (0.000) |     2.46 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           14 |     1416 | 2024-06-06 | MOUZ NXT      | L   | 0.801      | -            | -                | -                | -         |    -8.28 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           13 |     1527 | 2024-06-04 | Endpoint      | W   | 0.788      | 0.500        | 0.012 (0.005)    | 0.520 (0.205)    | -         |     9.79 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           12 |     1724 | 2024-05-28 | Sampi         | L   | 0.740      | -            | -                | -                | -         |   -14.13 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           11 |     1748 | 2024-05-27 | Endpoint      | W   | 0.733      | 0.435        | 0.012 (0.004)    | 0.520 (0.166)    | -         |     9.27 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           10 |     1789 | 2024-05-25 | Zero Tenacity | L   | 0.719      | -            | -                | -                | -         |    -8.04 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            9 |     1856 | 2024-05-22 | MOUZ NXT      | W   | 0.700      | 0.435        | 0.139 (0.042)    | 1.000 (0.304)    | -         |    12.64 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            8 |     1893 | 2024-05-21 | B8            | L   | 0.695      | -            | -                | -                | -         |    -6.30 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            7 |     1999 | 2024-05-18 | LEON          | W   | 0.672      | 0.143        | 0.007 (0.001)    | -                | -         |     3.55 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            6 |     2055 | 2024-05-16 | CPH Wolves    | W   | 0.661      | 0.143        | -                | 0.365 (0.034)    | -         |     5.38 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            5 |     2120 | 2024-05-15 | EYEBALLERS    | W   | 0.652      | 0.143        | 0.005 (0.001)    | 0.507 (0.047)    | -         |     7.74 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            4 |     2215 | 2024-05-12 | AL QATRAO     | W   | 0.634      | 0.306        | 0.004 (0.001)    | -                | 1 (0.634) |     3.55 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            3 |     2251 | 2024-05-11 | ALL-IN        | W   | 0.626      | -            | -                | -                | 1 (0.626) |     1.59 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            2 |     3887 | 2024-03-03 | Portugal      | L   | 0.167      | -            | -                | -                | -         |    -4.36 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            1 |     3901 | 2024-03-02 | AL QATRAO     | W   | 0.161      | -            | -                | -                | 1 (0.161) |     0.87 | DDias, krazy, renatoohaxx, snapy, TMKj |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($22,824.82)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.834 | $25,000.00     | $20,847.22      |
| 2024-05-12 |      0.634 | $2,693.00      | $1,706.31       |
| 2024-03-03 |      0.167 | $1,625.00      | $271.28         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
