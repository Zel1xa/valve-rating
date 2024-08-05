### Roster Details<br />
Team Name: Rhyno<br />
Roster: Ag1l, DDias, krazy, snapy, TMKj<br />
Global Rank: [66](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [48]( ../standings_europe.md)<br />
<br />
Final Rank Value:  984.2<br />
<br />
Final Rank Value (984.2) = Starting Rank Value (965.1) + Head To Head Adjustments (19.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.465[<sup>1</sup>](#table2)
- Bounty Collected: 0.330[<sup>2</sup>](#table1)
- Opponent Network: 0.144[<sup>2</sup>](#table1)
- LAN Wins: 0.163[<sup>2</sup>](#table1)

The average of these factors is 0.276<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 965.1
- 400 + ( ( 0.276 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 965.1


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
|           25 |       11 | 2024-08-05 | Meteor        | W   | 1.000      | 0.143        | 0.014 (0.002)    | -                | 0 (0.000) |     7.39 | Ag1l, DDias, krazy, snapy, TMKj        |
|           24 |      252 | 2024-07-30 | Enterprise    | L   | 1.000      | -            | -                | -                | -         |   -17.95 | Ag1l, DDias, krazy, snapy, TMKj        |
|           23 |      464 | 2024-07-23 | FAVBET        | W   | 1.000      | 0.143        | -                | 0.334 (0.048)    | 0 (0.000) |    10.07 | Ag1l, DDias, krazy, snapy, TMKj        |
|           22 |      572 | 2024-07-19 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -11.75 | Ag1l, DDias, krazy, snapy, TMKj        |
|           21 |      645 | 2024-07-18 | Nexus         | W   | 1.000      | 0.500        | 0.014 (0.007)    | 0.458 (0.229)    | 0 (0.000) |     6.28 | Ag1l, DDias, krazy, snapy, TMKj        |
|           20 |      715 | 2024-07-17 | HAVU          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.64 | Ag1l, DDias, krazy, snapy, TMKj        |
|           19 |      764 | 2024-07-16 | MOUZ NXT      | L   | 1.000      | -            | -                | -                | -         |   -12.18 | Ag1l, DDias, krazy, snapy, TMKj        |
|           18 |     1182 | 2024-06-11 | Nemiga        | L   | 0.833      | -            | -                | -                | -         |    -7.44 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           17 |     1204 | 2024-06-10 | CYBERSHOKE    | W   | 0.826      | 0.500        | 0.039 (0.016)    | 0.346 (0.143)    | 0 (0.000) |     8.90 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           16 |     1235 | 2024-06-09 | Rebels        | W   | 0.820      | 0.500        | 0.038 (0.016)    | 0.591 (0.242)    | 0 (0.000) |    14.28 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           15 |     1332 | 2024-06-08 | NAVI Junior   | W   | 0.812      | 0.500        | -                | 0.089 (0.036)    | 0 (0.000) |     2.46 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           14 |     1424 | 2024-06-06 | MOUZ NXT      | L   | 0.800      | -            | -                | -                | -         |    -8.24 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           13 |     1535 | 2024-06-04 | Endpoint      | W   | 0.787      | 0.500        | 0.012 (0.005)    | 0.514 (0.202)    | -         |     9.79 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           12 |     1732 | 2024-05-28 | Sampi         | L   | 0.739      | -            | -                | -                | -         |   -14.10 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           11 |     1756 | 2024-05-27 | Endpoint      | W   | 0.732      | 0.435        | 0.012 (0.004)    | 0.514 (0.164)    | -         |     9.27 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           10 |     1797 | 2024-05-25 | Zero Tenacity | L   | 0.718      | -            | -                | -                | -         |    -8.03 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            9 |     1864 | 2024-05-22 | MOUZ NXT      | W   | 0.699      | 0.435        | 0.139 (0.042)    | 0.987 (0.300)    | -         |    12.65 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            8 |     1901 | 2024-05-21 | B8            | L   | 0.694      | -            | -                | -                | -         |    -6.27 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            7 |     2007 | 2024-05-18 | LEON          | W   | 0.671      | 0.143        | 0.007 (0.001)    | -                | -         |     3.56 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            6 |     2063 | 2024-05-16 | CPH Wolves    | W   | 0.659      | 0.143        | -                | 0.361 (0.034)    | -         |     5.38 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            5 |     2128 | 2024-05-15 | EYEBALLERS    | W   | 0.651      | 0.143        | 0.005 (0.001)    | 0.500 (0.047)    | -         |     7.75 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            4 |     2223 | 2024-05-12 | AL QATRAO     | W   | 0.632      | 0.306        | 0.004 (0.001)    | -                | 1 (0.632) |     3.56 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            3 |     2259 | 2024-05-11 | ALL-IN        | W   | 0.625      | -            | -                | -                | 1 (0.625) |     1.59 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            2 |     3895 | 2024-03-03 | Portugal      | L   | 0.166      | -            | -                | -                | -         |    -4.33 | DDias, krazy, renatoohaxx, snapy, TMKj |
|            1 |     3909 | 2024-03-02 | AL QATRAO     | W   | 0.160      | -            | -                | -                | 1 (0.160) |     0.86 | DDias, krazy, renatoohaxx, snapy, TMKj |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($22,792.25)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-11 |      0.833 | $25,000.00     | $20,819.44      |
| 2024-05-12 |      0.632 | $2,693.00      | $1,703.32       |
| 2024-03-03 |      0.166 | $1,625.00      | $269.48         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
