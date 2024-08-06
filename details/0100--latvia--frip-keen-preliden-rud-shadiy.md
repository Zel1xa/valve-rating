### Roster Details<br />
Team Name: Latvia<br />
Roster: Frip, keen, prelideN, rud, shadiy<br />
Global Rank: [100](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [71]( ../standings_europe.md)<br />
<br />
Final Rank Value:  862.2<br />
<br />
Final Rank Value (862.2) = Starting Rank Value (861.2) + Head To Head Adjustments (1.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.308[<sup>1</sup>](#table2)
- Bounty Collected: 0.320[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.252[<sup>2</sup>](#table1)

The average of these factors is 0.224<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 861.2
- 400 + ( ( 0.224 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 861.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      838 | 2024-07-14 | ALTERNATE aTTaX | L   | 1.000      | -            | -                | -                | -         |   -15.14 | Frip, keen, prelideN, rud, shadiy    |
|            9 |      901 | 2024-07-10 | Norway          | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.103 (0.015)    | 0 (0.000) |     7.91 | Frip, keen, prelideN, rud, shadiy    |
|            8 |      937 | 2024-07-08 | 3DMAX           | W   | 1.000      | 0.143        | 0.510 (0.073)    | 1.000 (0.143)    | 0 (0.000) |    30.08 | Frip, keen, prelideN, rud, shadiy    |
|            7 |      945 | 2024-07-08 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -16.76 | Frip, keen, prelideN, rud, shadiy    |
|            6 |     1292 | 2024-06-09 | Esprots         | L   | 0.813      | -            | -                | -                | -         |   -17.89 | Frip, keen, prelideN, raw, shadiy    |
|            5 |     1310 | 2024-06-08 | hypewrld        | W   | 0.809      | 0.334        | 0.002 (0.001)    | 0.026 (0.007)    | 1 (0.809) |     5.89 | Frip, keen, prelideN, raw, shadiy    |
|            4 |     2374 | 2024-05-05 | hypewrld        | W   | 0.582      | 0.257        | 0.002 (0.000)    | 0.026 (0.004)    | 1 (0.582) |     4.44 | flairr, Frip, Mairel, rud, shadiy    |
|            3 |     2381 | 2024-05-05 | MightyWolves    | W   | 0.581      | 0.257        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.581) |     1.27 | flairr, Frip, Mairel, rud, shadiy    |
|            2 |     4056 | 2024-02-24 | hypewrld        | W   | 0.109      | 0.262        | 0.002 (0.000)    | 0.026 (0.001)    | 1 (0.109) |     0.84 | EIZA, keen, prelideN, shadiy, shield |
|            1 |     4061 | 2024-02-24 | kloogarand      | W   | 0.108      | 0.262        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.108) |     0.39 | EIZA, keen, prelideN, shadiy, shield |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,798.16)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.814 | $1,340.00      | $1,090.15       |
| 2024-05-05 |      0.582 | $1,077.00      | $626.55         |
| 2024-02-24 |      0.109 | $750.00        | $81.46          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />