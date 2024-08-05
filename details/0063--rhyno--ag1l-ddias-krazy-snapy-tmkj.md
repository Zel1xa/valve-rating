### Roster Details<br />
Team Name: Rhyno<br />
Roster: Ag1l, DDias, krazy, snapy, TMKj<br />
Global Rank: [63](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [44]( ../standings_europe.md)<br />
<br />
Final Rank Value:  985.6<br />
<br />
Final Rank Value (985.6) = Starting Rank Value (979.1) + Head To Head Adjustments (6.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.466[<sup>1</sup>](#table2)
- Bounty Collected: 0.332[<sup>2</sup>](#table1)
- Opponent Network: 0.151[<sup>2</sup>](#table1)
- LAN Wins: 0.174[<sup>2</sup>](#table1)

The average of these factors is 0.281<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 979.1
- 400 + ( ( 0.281 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 979.1


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
|           26 |       78 | 2024-07-30 | Enterprise    | L   | 1.000      | -            | -                | -                | -         |   -18.33 | Ag1l, DDias, krazy, snapy, TMKj        |
|           25 |      290 | 2024-07-23 | FAVBET        | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.344 (0.049)    | 0 (0.000) |     9.75 | Ag1l, DDias, krazy, snapy, TMKj        |
|           24 |      398 | 2024-07-19 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -12.25 | Ag1l, DDias, krazy, snapy, TMKj        |
|           23 |      471 | 2024-07-18 | Nexus         | W   | 1.000      | 0.500        | 0.014 (0.007)    | 0.465 (0.233)    | 0 (0.000) |     6.00 | Ag1l, DDias, krazy, snapy, TMKj        |
|           22 |      541 | 2024-07-17 | HAVU          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.53 | Ag1l, DDias, krazy, snapy, TMKj        |
|           21 |      590 | 2024-07-16 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -12.74 | Ag1l, DDias, krazy, snapy, TMKj        |
|           20 |     1008 | 2024-06-11 | Nemiga        | L   | 0.865      | -            | -                | -                | -         |    -8.18 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           19 |     1030 | 2024-06-10 | CYBERSHOKE    | W   | 0.859      | 0.500        | 0.039 (0.017)    | 0.347 (0.149)    | 0 (0.000) |     8.93 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           18 |     1061 | 2024-06-09 | Rebels        | W   | 0.853      | 0.500        | 0.040 (0.017)    | 0.596 (0.254)    | 0 (0.000) |    14.76 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           17 |     1158 | 2024-06-08 | NAVI Junior   | W   | 0.844      | 0.500        | -                | 0.091 (0.038)    | 0 (0.000) |     2.46 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           16 |     1250 | 2024-06-06 | MOUZ NXT      | L   | 0.833      | -            | -                | -                | -         |    -8.93 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           15 |     1361 | 2024-06-04 | Endpoint      | W   | 0.819      | 0.500        | 0.012 (0.005)    | 0.523 (0.214)    | 0 (0.000) |     9.84 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           14 |     1558 | 2024-05-28 | Sampi         | L   | 0.771      | -            | -                | -                | -         |   -15.06 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           13 |     1582 | 2024-05-27 | Endpoint      | W   | 0.764      | 0.435        | 0.012 (0.004)    | 0.523 (0.174)    | -         |     9.33 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           12 |     1623 | 2024-05-25 | Zero Tenacity | L   | 0.750      | -            | -                | -                | -         |    -8.63 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           11 |     1690 | 2024-05-22 | MOUZ NXT      | W   | 0.731      | 0.435        | 0.140 (0.044)    | 1.000 (0.318)    | -         |    12.79 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           10 |     1727 | 2024-05-21 | B8            | L   | 0.726      | -            | -                | -                | -         |    -6.69 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            9 |     1833 | 2024-05-18 | LEON          | W   | 0.704      | 0.143        | 0.007 (0.001)    | -                | -         |     3.55 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            8 |     1889 | 2024-05-16 | CPH Wolves    | W   | 0.692      | 0.143        | -                | 0.359 (0.035)    | -         |     5.35 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            7 |     1954 | 2024-05-15 | EYEBALLERS    | W   | 0.684      | 0.143        | 0.006 (0.001)    | 0.513 (0.050)    | -         |     8.02 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            6 |     2049 | 2024-05-12 | AL QATRAO     | W   | 0.665      | 0.306        | 0.004 (0.001)    | -                | 1 (0.665) |     3.61 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            5 |     2085 | 2024-05-11 | ALL-IN        | W   | 0.657      | -            | -                | -                | 1 (0.657) |     1.57 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            4 |     3721 | 2024-03-03 | Portugal      | L   | 0.198      | -            | -                | -                | -         |    -5.20 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            3 |     3735 | 2024-03-02 | AL QATRAO     | W   | 0.192      | -            | -                | -                | 1 (0.192) |     1.00 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            2 |     4268 | 2024-02-04 | SAW           | L   | 0.012      | -            | -                | -                | -         |    -0.09 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            1 |     4292 | 2024-02-03 | Portugal      | W   | 0.006      | -            | -                | -                | -         |     0.03 | DDias, krazy, renatoohaxx, snapy, TMKj |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,741.96)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.865 | $25,000.00     | $21,629.28      |
| 2024-05-12 |      0.665 | $2,693.00      | $1,790.56       |
| 2024-03-03 |      0.198 | $1,625.00      | $322.12         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
