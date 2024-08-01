### Roster Details<br />
Team Name: Rhyno<br />
Roster: Ag1l, DDias, krazy, snapy, TMKj<br />
Global Rank: [62](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [43]( ../standings_europe.md)<br />
<br />
Final Rank Value:  987.1<br />
<br />
Final Rank Value (987.1) = Starting Rank Value (981.0) + Head To Head Adjustments (6.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.467[<sup>1</sup>](#table2)
- Bounty Collected: 0.332[<sup>2</sup>](#table1)
- Opponent Network: 0.157[<sup>2</sup>](#table1)
- LAN Wins: 0.173[<sup>2</sup>](#table1)

The average of these factors is 0.282<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 981.0
- 400 + ( ( 0.282 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 981.0


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
|           26 |      107 | 2024-07-30 | Enterprise    | L   | 1.000      | -            | -                | -                | -         |   -18.06 | Ag1l, DDias, krazy, snapy, TMKj        |
|           25 |      319 | 2024-07-23 | FAVBET        | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.343 (0.049)    | 0 (0.000) |     9.66 | Ag1l, DDias, krazy, snapy, TMKj        |
|           24 |      431 | 2024-07-19 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -12.10 | Ag1l, DDias, krazy, snapy, TMKj        |
|           23 |      509 | 2024-07-18 | Nexus         | W   | 1.000      | 0.500        | 0.014 (0.007)    | 0.504 (0.252)    | 0 (0.000) |     6.63 | Ag1l, DDias, krazy, snapy, TMKj        |
|           22 |      577 | 2024-07-17 | HAVU          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.52 | Ag1l, DDias, krazy, snapy, TMKj        |
|           21 |      631 | 2024-07-16 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -12.48 | Ag1l, DDias, krazy, snapy, TMKj        |
|           20 |     1044 | 2024-06-11 | Nemiga        | L   | 0.861      | -            | -                | -                | -         |    -8.49 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           19 |     1067 | 2024-06-10 | CYBERSHOKE    | W   | 0.854      | 0.500        | 0.040 (0.017)    | 0.348 (0.149)    | 0 (0.000) |     8.89 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           18 |     1098 | 2024-06-09 | Rebels        | W   | 0.848      | 0.500        | 0.040 (0.017)    | 0.635 (0.269)    | 0 (0.000) |    14.68 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           17 |     1198 | 2024-06-08 | NAVI Junior   | W   | 0.840      | 0.500        | -                | 0.091 (0.038)    | 0 (0.000) |     2.45 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           16 |     1298 | 2024-06-06 | MOUZ NXT      | L   | 0.828      | -            | -                | -                | -         |    -8.66 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           15 |     1412 | 2024-06-04 | Endpoint      | W   | 0.815      | 0.500        | 0.012 (0.005)    | 0.555 (0.226)    | 0 (0.000) |    10.09 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           14 |     1610 | 2024-05-28 | Sampi         | L   | 0.767      | -            | -                | -                | -         |   -15.13 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           13 |     1635 | 2024-05-27 | Endpoint      | W   | 0.760      | 0.435        | 0.012 (0.004)    | 0.555 (0.183)    | -         |     9.57 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           12 |     1677 | 2024-05-25 | Zero Tenacity | L   | 0.746      | -            | -                | -                | -         |    -9.39 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           11 |     1754 | 2024-05-22 | MOUZ NXT      | W   | 0.727      | 0.435        | 0.141 (0.044)    | 1.000 (0.316)    | -         |    12.58 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           10 |     1795 | 2024-05-21 | B8            | L   | 0.722      | -            | -                | -                | -         |    -7.28 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            9 |     1913 | 2024-05-18 | LEON          | W   | 0.699      | 0.143        | 0.007 (0.001)    | -                | -         |     3.50 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            8 |     1969 | 2024-05-16 | CPH Wolves    | W   | 0.688      | 0.143        | -                | 0.360 (0.035)    | -         |     5.29 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            7 |     2038 | 2024-05-15 | EYEBALLERS    | W   | 0.679      | 0.143        | 0.006 (0.001)    | 0.513 (0.050)    | -         |     7.88 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            6 |     2138 | 2024-05-12 | AL QATRAO     | W   | 0.661      | 0.306        | 0.004 (0.001)    | -                | 1 (0.661) |     3.55 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            5 |     2174 | 2024-05-11 | ALL-IN        | W   | 0.653      | -            | -                | -                | 1 (0.653) |     1.55 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            4 |     3850 | 2024-03-03 | Portugal      | L   | 0.194      | -            | -                | -                | -         |    -5.10 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            3 |     3864 | 2024-03-02 | AL QATRAO     | W   | 0.188      | -            | -                | -                | 1 (0.188) |     0.96 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            2 |     4417 | 2024-02-04 | SAW           | L   | 0.007      | -            | -                | -                | -         |    -0.06 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            1 |     4441 | 2024-02-03 | Portugal      | W   | 0.002      | -            | -                | -                | -         |     0.01 | DDias, krazy, renatoohaxx, snapy, TMKj |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,614.78)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.861 | $25,000.00     | $21,520.83      |
| 2024-05-12 |      0.661 | $2,693.00      | $1,778.88       |
| 2024-03-03 |      0.194 | $1,625.00      | $315.07         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
