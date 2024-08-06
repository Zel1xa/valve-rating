### Roster Details<br />
Team Name: Rhyno<br />
Roster: Ag1l, DDias, krazy, snapy, TMKj<br />
Global Rank: [67](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [48]( ../standings_europe.md)<br />
<br />
Final Rank Value:  987.9<br />
<br />
Final Rank Value (987.9) = Starting Rank Value (966.1) + Head To Head Adjustments (21.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.465[<sup>1</sup>](#table2)
- Bounty Collected: 0.330[<sup>2</sup>](#table1)
- Opponent Network: 0.144[<sup>2</sup>](#table1)
- LAN Wins: 0.162[<sup>2</sup>](#table1)

The average of these factors is 0.275<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 966.1
- 400 + ( ( 0.275 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 966.1


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
|           25 |       31 | 2024-08-05 | Meteor        | W   | 1.000      | 0.143        | 0.014 (0.002)    | -                | 0 (0.000) |     7.44 | Ag1l, DDias, krazy, snapy, TMKj        |
|           24 |      273 | 2024-07-30 | Enterprise    | L   | 1.000      | -            | -                | -                | -         |   -18.00 | Ag1l, DDias, krazy, snapy, TMKj        |
|           23 |      485 | 2024-07-23 | FAVBET        | W   | 1.000      | 0.143        | -                | 0.364 (0.052)    | 0 (0.000) |    10.05 | Ag1l, DDias, krazy, snapy, TMKj        |
|           22 |      593 | 2024-07-19 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -11.75 | Ag1l, DDias, krazy, snapy, TMKj        |
|           21 |      666 | 2024-07-18 | Nexus         | W   | 1.000      | 0.500        | 0.014 (0.007)    | 0.447 (0.223)    | 0 (0.000) |     6.31 | Ag1l, DDias, krazy, snapy, TMKj        |
|           20 |      736 | 2024-07-17 | HAVU          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.56 | Ag1l, DDias, krazy, snapy, TMKj        |
|           19 |      785 | 2024-07-16 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -12.18 | Ag1l, DDias, krazy, snapy, TMKj        |
|           18 |     1203 | 2024-06-11 | Nemiga        | L   | 0.827      | -            | -                | -                | -         |    -7.50 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           17 |     1225 | 2024-06-10 | CYBERSHOKE    | W   | 0.820      | 0.500        | 0.039 (0.016)    | 0.339 (0.139)    | 0 (0.000) |     8.74 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           16 |     1256 | 2024-06-09 | Rebels        | W   | 0.814      | 0.500        | 0.038 (0.016)    | 0.578 (0.235)    | 0 (0.000) |    14.07 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           15 |     1353 | 2024-06-08 | NAVI Junior   | W   | 0.806      | 0.500        | 0.003 (0.001)    | 0.115 (0.046)    | 0 (0.000) |     5.16 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           14 |     1445 | 2024-06-06 | MOUZ NXT      | L   | 0.794      | -            | -                | -                | -         |    -8.11 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           13 |     1556 | 2024-06-04 | Endpoint      | W   | 0.781      | 0.500        | 0.012 (0.005)    | 0.540 (0.211)    | -         |     9.78 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           12 |     1753 | 2024-05-28 | Sampi         | L   | 0.733      | -            | -                | -                | -         |   -13.96 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           11 |     1777 | 2024-05-27 | Endpoint      | W   | 0.726      | 0.435        | 0.012 (0.004)    | 0.540 (0.170)    | -         |     9.25 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           10 |     1818 | 2024-05-25 | Zero Tenacity | L   | 0.712      | -            | -                | -                | -         |    -7.85 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            9 |     1885 | 2024-05-22 | MOUZ NXT      | W   | 0.693      | 0.435        | 0.139 (0.042)    | 0.962 (0.289)    | -         |    12.55 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            8 |     1922 | 2024-05-21 | B8            | L   | 0.688      | -            | -                | -                | -         |    -6.20 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            7 |     2028 | 2024-05-18 | LEON          | W   | 0.665      | 0.143        | 0.007 (0.001)    | -                | -         |     3.52 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            6 |     2084 | 2024-05-16 | CPH Wolves    | W   | 0.653      | 0.143        | -                | 0.353 (0.033)    | -         |     5.32 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            5 |     2149 | 2024-05-15 | EYEBALLERS    | W   | 0.645      | 0.143        | -                | 0.488 (0.045)    | -         |     7.83 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            4 |     2244 | 2024-05-12 | AL QATRAO     | W   | 0.626      | 0.306        | 0.004 (0.001)    | -                | 1 (0.626) |     3.51 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            3 |     2280 | 2024-05-11 | ALL-IN        | W   | 0.619      | -            | -                | -                | 1 (0.619) |     1.57 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            2 |     3916 | 2024-03-03 | Portugal      | L   | 0.160      | -            | -                | -                | -         |    -4.18 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            1 |     3930 | 2024-03-02 | AL QATRAO     | W   | 0.154      | -            | -                | -                | 1 (0.154) |     0.83 | DDias, krazy, renatoohaxx, snapy, TMKj |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($22,613.08)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.827 | $25,000.00     | $20,666.67      |
| 2024-05-12 |      0.626 | $2,693.00      | $1,686.87       |
| 2024-03-03 |      0.160 | $1,625.00      | $259.55         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
