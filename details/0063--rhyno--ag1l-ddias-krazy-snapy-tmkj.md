### Roster Details<br />
Team Name: Rhyno<br />
Roster: Ag1l, DDias, krazy, snapy, TMKj<br />
Global Rank: [63](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [44]( ../standings_europe.md)<br />
<br />
Final Rank Value:  976.7<br />
<br />
Final Rank Value (976.7) = Starting Rank Value (966.8) + Head To Head Adjustments (9.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.465[<sup>1</sup>](#table2)
- Bounty Collected: 0.330[<sup>2</sup>](#table1)
- Opponent Network: 0.148[<sup>2</sup>](#table1)
- LAN Wins: 0.166[<sup>2</sup>](#table1)

The average of these factors is 0.277<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 966.8
- 400 + ( ( 0.277 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 966.8


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
|           24 |      191 | 2024-07-30 | Enterprise    | L   | 1.000      | -            | -                | -                | -         |   -18.09 | Ag1l, DDias, krazy, snapy, TMKj        |
|           23 |      404 | 2024-07-23 | FAVBET        | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.341 (0.049)    | 0 (0.000) |     9.90 | Ag1l, DDias, krazy, snapy, TMKj        |
|           22 |      512 | 2024-07-19 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -11.95 | Ag1l, DDias, krazy, snapy, TMKj        |
|           21 |      586 | 2024-07-18 | Nexus         | W   | 1.000      | 0.500        | 0.014 (0.007)    | 0.465 (0.233)    | 0 (0.000) |     6.21 | Ag1l, DDias, krazy, snapy, TMKj        |
|           20 |      652 | 2024-07-17 | HAVU          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.64 | Ag1l, DDias, krazy, snapy, TMKj        |
|           19 |      705 | 2024-07-16 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -12.40 | Ag1l, DDias, krazy, snapy, TMKj        |
|           18 |     1121 | 2024-06-11 | Nemiga        | L   | 0.844      | -            | -                | -                | -         |    -7.99 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           17 |     1143 | 2024-06-10 | CYBERSHOKE    | W   | 0.838      | 0.500        | 0.039 (0.016)    | 0.350 (0.147)    | 0 (0.000) |     8.91 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           16 |     1174 | 2024-06-09 | Rebels        | W   | 0.832      | 0.500        | 0.038 (0.016)    | 0.599 (0.249)    | 0 (0.000) |    14.47 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           15 |     1271 | 2024-06-08 | NAVI Junior   | W   | 0.824      | 0.500        | -                | 0.090 (0.037)    | 0 (0.000) |     2.49 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           14 |     1363 | 2024-06-06 | MOUZ NXT      | L   | 0.812      | -            | -                | -                | -         |    -8.54 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           13 |     1474 | 2024-06-04 | Endpoint      | W   | 0.799      | 0.500        | 0.012 (0.005)    | 0.522 (0.209)    | 0 (0.000) |     9.83 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           12 |     1671 | 2024-05-28 | Sampi         | L   | 0.750      | -            | -                | -                | -         |   -14.40 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           11 |     1695 | 2024-05-27 | Endpoint      | W   | 0.744      | 0.435        | 0.012 (0.004)    | 0.522 (0.169)    | -         |     9.31 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           10 |     1736 | 2024-05-25 | Zero Tenacity | L   | 0.729      | -            | -                | -                | -         |    -8.18 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            9 |     1803 | 2024-05-22 | MOUZ NXT      | W   | 0.710      | 0.435        | 0.139 (0.043)    | 1.000 (0.309)    | -         |    12.71 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            8 |     1840 | 2024-05-21 | B8            | L   | 0.705      | -            | -                | -                | -         |    -6.42 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            7 |     1946 | 2024-05-18 | LEON          | W   | 0.683      | 0.143        | 0.007 (0.001)    | -                | -         |     3.58 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            6 |     2002 | 2024-05-16 | CPH Wolves    | W   | 0.671      | 0.143        | -                | 0.363 (0.035)    | -         |     5.39 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            5 |     2067 | 2024-05-15 | EYEBALLERS    | W   | 0.663      | 0.143        | 0.006 (0.001)    | 0.510 (0.048)    | -         |     7.97 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            4 |     2162 | 2024-05-12 | AL QATRAO     | W   | 0.644      | 0.306        | 0.004 (0.001)    | -                | 1 (0.644) |     3.60 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            3 |     2198 | 2024-05-11 | ALL-IN        | W   | 0.637      | -            | -                | -                | 1 (0.637) |     1.61 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            2 |     3832 | 2024-03-03 | Portugal      | L   | 0.177      | -            | -                | -                | -         |    -4.64 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            1 |     3846 | 2024-03-02 | AL QATRAO     | W   | 0.171      | -            | -                | -                | 1 (0.171) |     0.92 | DDias, krazy, renatoohaxx, snapy, TMKj |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,134.29)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.844 | $25,000.00     | $21,111.11      |
| 2024-05-12 |      0.644 | $2,693.00      | $1,734.74       |
| 2024-03-03 |      0.177 | $1,625.00      | $288.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
