### Roster Details<br />
Team Name: Rhyno<br />
Roster: Ag1l, DDias, krazy, snapy, TMKj<br />
Global Rank: [62](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [44]( ../standings_europe.md)<br />
<br />
Final Rank Value:  976.9<br />
<br />
Final Rank Value (976.9) = Starting Rank Value (966.0) + Head To Head Adjustments (10.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.465[<sup>1</sup>](#table2)
- Bounty Collected: 0.330[<sup>2</sup>](#table1)
- Opponent Network: 0.148[<sup>2</sup>](#table1)
- LAN Wins: 0.165[<sup>2</sup>](#table1)

The average of these factors is 0.277<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 966.0
- 400 + ( ( 0.277 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 966.0


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
|           24 |      226 | 2024-07-30 | Enterprise    | L   | 1.000      | -            | -                | -                | -         |   -18.04 | Ag1l, DDias, krazy, snapy, TMKj        |
|           23 |      438 | 2024-07-23 | FAVBET        | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.340 (0.049)    | 0 (0.000) |     9.95 | Ag1l, DDias, krazy, snapy, TMKj        |
|           22 |      546 | 2024-07-19 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -11.90 | Ag1l, DDias, krazy, snapy, TMKj        |
|           21 |      619 | 2024-07-18 | Nexus         | W   | 1.000      | 0.500        | 0.014 (0.007)    | 0.465 (0.233)    | 0 (0.000) |     6.23 | Ag1l, DDias, krazy, snapy, TMKj        |
|           20 |      689 | 2024-07-17 | HAVU          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.64 | Ag1l, DDias, krazy, snapy, TMKj        |
|           19 |      738 | 2024-07-16 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -12.35 | Ag1l, DDias, krazy, snapy, TMKj        |
|           18 |     1156 | 2024-06-11 | Nemiga        | L   | 0.840      | -            | -                | -                | -         |    -7.53 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           17 |     1178 | 2024-06-10 | CYBERSHOKE    | W   | 0.833      | 0.500        | 0.039 (0.016)    | 0.351 (0.146)    | 0 (0.000) |     8.93 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           16 |     1209 | 2024-06-09 | Rebels        | W   | 0.827      | 0.500        | 0.038 (0.016)    | 0.599 (0.248)    | 0 (0.000) |    14.42 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           15 |     1306 | 2024-06-08 | NAVI Junior   | W   | 0.819      | 0.500        | -                | 0.090 (0.037)    | 0 (0.000) |     2.48 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           14 |     1398 | 2024-06-06 | MOUZ NXT      | L   | 0.807      | -            | -                | -                | -         |    -8.44 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           13 |     1509 | 2024-06-04 | Endpoint      | W   | 0.794      | 0.500        | 0.012 (0.005)    | 0.522 (0.207)    | 0 (0.000) |     9.84 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           12 |     1706 | 2024-05-28 | Sampi         | L   | 0.746      | -            | -                | -                | -         |   -14.24 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           11 |     1730 | 2024-05-27 | Endpoint      | W   | 0.739      | 0.435        | 0.012 (0.004)    | 0.522 (0.168)    | -         |     9.32 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           10 |     1771 | 2024-05-25 | Zero Tenacity | L   | 0.725      | -            | -                | -                | -         |    -8.16 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            9 |     1838 | 2024-05-22 | MOUZ NXT      | W   | 0.706      | 0.435        | 0.139 (0.043)    | 1.000 (0.307)    | -         |    12.69 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            8 |     1875 | 2024-05-21 | B8            | L   | 0.701      | -            | -                | -                | -         |    -6.35 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            7 |     1981 | 2024-05-18 | LEON          | W   | 0.678      | 0.143        | 0.007 (0.001)    | -                | -         |     3.58 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            6 |     2037 | 2024-05-16 | CPH Wolves    | W   | 0.667      | 0.143        | -                | 0.365 (0.035)    | -         |     5.39 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            5 |     2102 | 2024-05-15 | EYEBALLERS    | W   | 0.658      | 0.143        | 0.006 (0.001)    | 0.509 (0.048)    | -         |     7.80 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            4 |     2197 | 2024-05-12 | AL QATRAO     | W   | 0.640      | 0.306        | 0.004 (0.001)    | -                | 1 (0.640) |     3.58 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            3 |     2233 | 2024-05-11 | ALL-IN        | W   | 0.632      | -            | -                | -                | 1 (0.632) |     1.60 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            2 |     3869 | 2024-03-03 | Portugal      | L   | 0.173      | -            | -                | -                | -         |    -4.52 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            1 |     3883 | 2024-03-02 | AL QATRAO     | W   | 0.167      | -            | -                | -                | 1 (0.167) |     0.90 | DDias, krazy, renatoohaxx, snapy, TMKj |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,001.27)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.840 | $25,000.00     | $20,997.69      |
| 2024-05-12 |      0.640 | $2,693.00      | $1,722.52       |
| 2024-03-03 |      0.173 | $1,625.00      | $281.06         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
