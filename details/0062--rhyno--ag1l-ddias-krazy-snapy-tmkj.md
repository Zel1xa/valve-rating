### Roster Details<br />
Team Name: Rhyno<br />
Roster: Ag1l, DDias, krazy, snapy, TMKj<br />
Global Rank: [62](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [43]( ../standings_europe.md)<br />
<br />
Final Rank Value:  986.2<br />
<br />
Final Rank Value (986.2) = Starting Rank Value (980.0) + Head To Head Adjustments (6.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.467[<sup>1</sup>](#table2)
- Bounty Collected: 0.332[<sup>2</sup>](#table1)
- Opponent Network: 0.156[<sup>2</sup>](#table1)
- LAN Wins: 0.173[<sup>2</sup>](#table1)

The average of these factors is 0.282<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 980.0
- 400 + ( ( 0.282 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 980.0


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
|           25 |      112 | 2024-07-30 | Enterprise    | L   | 1.000      | -            | -                | -                | -         |   -18.06 | Ag1l, DDias, krazy, snapy, TMKj        |
|           24 |      325 | 2024-07-23 | FAVBET        | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.343 (0.049)    | 0 (0.000) |     9.66 | Ag1l, DDias, krazy, snapy, TMKj        |
|           23 |      437 | 2024-07-19 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -12.07 | Ag1l, DDias, krazy, snapy, TMKj        |
|           22 |      515 | 2024-07-18 | Nexus         | W   | 1.000      | 0.500        | 0.014 (0.007)    | 0.504 (0.252)    | 0 (0.000) |     6.64 | Ag1l, DDias, krazy, snapy, TMKj        |
|           21 |      583 | 2024-07-17 | HAVU          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.52 | Ag1l, DDias, krazy, snapy, TMKj        |
|           20 |      637 | 2024-07-16 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -12.47 | Ag1l, DDias, krazy, snapy, TMKj        |
|           19 |     1050 | 2024-06-11 | Nemiga        | L   | 0.859      | -            | -                | -                | -         |    -8.48 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           18 |     1073 | 2024-06-10 | CYBERSHOKE    | W   | 0.853      | 0.500        | 0.040 (0.017)    | 0.348 (0.148)    | 0 (0.000) |     8.89 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           17 |     1104 | 2024-06-09 | Rebels        | W   | 0.847      | 0.500        | 0.040 (0.017)    | 0.635 (0.269)    | 0 (0.000) |    14.65 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           16 |     1204 | 2024-06-08 | NAVI Junior   | W   | 0.838      | 0.500        | -                | 0.091 (0.038)    | 0 (0.000) |     2.45 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           15 |     1304 | 2024-06-06 | MOUZ NXT      | L   | 0.827      | -            | -                | -                | -         |    -8.64 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           14 |     1418 | 2024-06-04 | Endpoint      | W   | 0.813      | 0.500        | 0.012 (0.005)    | 0.555 (0.226)    | 0 (0.000) |    10.08 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           13 |     1616 | 2024-05-28 | Sampi         | L   | 0.765      | -            | -                | -                | -         |   -15.09 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           12 |     1641 | 2024-05-27 | Endpoint      | W   | 0.758      | 0.435        | 0.012 (0.004)    | 0.555 (0.183)    | -         |     9.56 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           11 |     1683 | 2024-05-25 | Zero Tenacity | L   | 0.744      | -            | -                | -                | -         |    -9.34 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           10 |     1760 | 2024-05-22 | MOUZ NXT      | W   | 0.725      | 0.435        | 0.141 (0.044)    | 1.000 (0.315)    | -         |    12.56 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            9 |     1801 | 2024-05-21 | B8            | L   | 0.720      | -            | -                | -                | -         |    -7.25 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            8 |     1919 | 2024-05-18 | LEON          | W   | 0.698      | 0.143        | 0.007 (0.001)    | -                | -         |     3.50 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            7 |     1975 | 2024-05-16 | CPH Wolves    | W   | 0.686      | 0.143        | -                | 0.360 (0.035)    | -         |     5.29 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            6 |     2044 | 2024-05-15 | EYEBALLERS    | W   | 0.677      | 0.143        | 0.006 (0.001)    | 0.512 (0.050)    | -         |     7.87 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            5 |     2144 | 2024-05-12 | AL QATRAO     | W   | 0.659      | 0.306        | 0.004 (0.001)    | -                | 1 (0.659) |     3.55 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            4 |     2180 | 2024-05-11 | ALL-IN        | W   | 0.651      | -            | -                | -                | 1 (0.651) |     1.55 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            3 |     3856 | 2024-03-03 | Portugal      | L   | 0.192      | -            | -                | -                | -         |    -5.06 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            2 |     3870 | 2024-03-02 | AL QATRAO     | W   | 0.186      | -            | -                | -                | 1 (0.186) |     0.96 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            1 |     4423 | 2024-02-04 | SAW           | L   | 0.006      | -            | -                | -                | -         |    -0.04 | DDias, krazy, renatoohaxx, snapy, TMKj |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,565.92)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.859 | $25,000.00     | $21,479.17      |
| 2024-05-12 |      0.659 | $2,693.00      | $1,774.39       |
| 2024-03-03 |      0.192 | $1,625.00      | $312.36         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
