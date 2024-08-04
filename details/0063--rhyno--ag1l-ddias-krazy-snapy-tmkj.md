### Roster Details<br />
Team Name: Rhyno<br />
Roster: Ag1l, DDias, krazy, snapy, TMKj<br />
Global Rank: [63](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [44]( ../standings_europe.md)<br />
<br />
Final Rank Value:  976.2<br />
<br />
Final Rank Value (976.2) = Starting Rank Value (966.3) + Head To Head Adjustments (9.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.465[<sup>1</sup>](#table2)
- Bounty Collected: 0.330[<sup>2</sup>](#table1)
- Opponent Network: 0.148[<sup>2</sup>](#table1)
- LAN Wins: 0.165[<sup>2</sup>](#table1)

The average of these factors is 0.277<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 966.3
- 400 + ( ( 0.277 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 966.3


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
|           24 |      194 | 2024-07-30 | Enterprise    | L   | 1.000      | -            | -                | -                | -         |   -18.08 | Ag1l, DDias, krazy, snapy, TMKj        |
|           23 |      407 | 2024-07-23 | FAVBET        | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.340 (0.049)    | 0 (0.000) |     9.90 | Ag1l, DDias, krazy, snapy, TMKj        |
|           22 |      515 | 2024-07-19 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -11.95 | Ag1l, DDias, krazy, snapy, TMKj        |
|           21 |      589 | 2024-07-18 | Nexus         | W   | 1.000      | 0.500        | 0.014 (0.007)    | 0.465 (0.233)    | 0 (0.000) |     6.22 | Ag1l, DDias, krazy, snapy, TMKj        |
|           20 |      655 | 2024-07-17 | HAVU          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.64 | Ag1l, DDias, krazy, snapy, TMKj        |
|           19 |      708 | 2024-07-16 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -12.40 | Ag1l, DDias, krazy, snapy, TMKj        |
|           18 |     1125 | 2024-06-11 | Nemiga        | L   | 0.841      | -            | -                | -                | -         |    -7.96 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           17 |     1147 | 2024-06-10 | CYBERSHOKE    | W   | 0.835      | 0.500        | 0.039 (0.016)    | 0.351 (0.146)    | 0 (0.000) |     8.89 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           16 |     1178 | 2024-06-09 | Rebels        | W   | 0.829      | 0.500        | 0.038 (0.016)    | 0.599 (0.248)    | 0 (0.000) |    14.41 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           15 |     1275 | 2024-06-08 | NAVI Junior   | W   | 0.821      | 0.500        | -                | 0.090 (0.037)    | 0 (0.000) |     2.48 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           14 |     1367 | 2024-06-06 | MOUZ NXT      | L   | 0.809      | -            | -                | -                | -         |    -8.52 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           13 |     1478 | 2024-06-04 | Endpoint      | W   | 0.796      | 0.500        | 0.012 (0.005)    | 0.522 (0.208)    | 0 (0.000) |     9.80 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           12 |     1675 | 2024-05-28 | Sampi         | L   | 0.747      | -            | -                | -                | -         |   -14.34 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           11 |     1699 | 2024-05-27 | Endpoint      | W   | 0.741      | 0.435        | 0.012 (0.004)    | 0.522 (0.168)    | -         |     9.28 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           10 |     1740 | 2024-05-25 | Zero Tenacity | L   | 0.726      | -            | -                | -                | -         |    -8.14 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            9 |     1807 | 2024-05-22 | MOUZ NXT      | W   | 0.707      | 0.435        | 0.139 (0.043)    | 1.000 (0.307)    | -         |    12.65 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            8 |     1844 | 2024-05-21 | B8            | L   | 0.702      | -            | -                | -                | -         |    -6.40 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            7 |     1950 | 2024-05-18 | LEON          | W   | 0.680      | 0.143        | 0.007 (0.001)    | -                | -         |     3.58 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            6 |     2006 | 2024-05-16 | CPH Wolves    | W   | 0.668      | 0.143        | -                | 0.364 (0.035)    | -         |     5.38 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            5 |     2071 | 2024-05-15 | EYEBALLERS    | W   | 0.660      | 0.143        | 0.006 (0.001)    | 0.510 (0.048)    | -         |     7.93 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            4 |     2166 | 2024-05-12 | AL QATRAO     | W   | 0.641      | 0.306        | 0.004 (0.001)    | -                | 1 (0.641) |     3.59 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            3 |     2202 | 2024-05-11 | ALL-IN        | W   | 0.633      | -            | -                | -                | 1 (0.633) |     1.61 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            2 |     3838 | 2024-03-03 | Portugal      | L   | 0.174      | -            | -                | -                | -         |    -4.56 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            1 |     3852 | 2024-03-02 | AL QATRAO     | W   | 0.168      | -            | -                | -                | 1 (0.168) |     0.90 | DDias, krazy, renatoohaxx, snapy, TMKj |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,044.71)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.841 | $25,000.00     | $21,034.72      |
| 2024-05-12 |      0.641 | $2,693.00      | $1,726.51       |
| 2024-03-03 |      0.174 | $1,625.00      | $283.47         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
