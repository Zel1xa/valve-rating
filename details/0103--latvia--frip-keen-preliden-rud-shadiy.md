### Roster Details<br />
Team Name: Latvia<br />
Roster: Frip, keen, prelideN, rud, shadiy<br />
Global Rank: [103](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [73]( ../standings_europe.md)<br />
<br />
Final Rank Value:  862.1<br />
<br />
Final Rank Value (862.1) = Starting Rank Value (860.9) + Head To Head Adjustments (1.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.308[<sup>1</sup>](#table2)
- Bounty Collected: 0.320[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.252[<sup>2</sup>](#table1)

The average of these factors is 0.224<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 860.9
- 400 + ( ( 0.224 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 860.9


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
|           10 |      852 | 2024-07-14 | ALTERNATE aTTaX | L   | 1.000      | -            | -                | -                | -         |   -15.00 | Frip, keen, prelideN, rud, shadiy    |
|            9 |      915 | 2024-07-10 | Norway          | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.103 (0.015)    | 0 (0.000) |     7.91 | Frip, keen, prelideN, rud, shadiy    |
|            8 |      951 | 2024-07-08 | 3DMAX           | W   | 1.000      | 0.143        | 0.510 (0.073)    | 1.000 (0.143)    | 0 (0.000) |    30.10 | Frip, keen, prelideN, rud, shadiy    |
|            7 |      959 | 2024-07-08 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -16.74 | Frip, keen, prelideN, rud, shadiy    |
|            6 |     1306 | 2024-06-09 | Esprots         | L   | 0.811      | -            | -                | -                | -         |   -17.85 | Frip, keen, prelideN, raw, shadiy    |
|            5 |     1324 | 2024-06-08 | hypewrld        | W   | 0.807      | 0.334        | 0.002 (0.001)    | 0.026 (0.007)    | 1 (0.807) |     5.88 | Frip, keen, prelideN, raw, shadiy    |
|            4 |     2388 | 2024-05-05 | hypewrld        | W   | 0.580      | 0.257        | 0.002 (0.000)    | 0.026 (0.004)    | 1 (0.580) |     4.43 | flairr, Frip, Mairel, rud, shadiy    |
|            3 |     2395 | 2024-05-05 | MightyWolves    | W   | 0.579      | 0.257        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.579) |     1.27 | flairr, Frip, Mairel, rud, shadiy    |
|            2 |     4070 | 2024-02-24 | hypewrld        | W   | 0.107      | 0.262        | 0.002 (0.000)    | 0.026 (0.001)    | 1 (0.107) |     0.82 | EIZA, keen, prelideN, shadiy, shield |
|            1 |     4075 | 2024-02-24 | kloogarand      | W   | 0.106      | 0.262        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.106) |     0.39 | EIZA, keen, prelideN, shadiy, shield |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,793.32)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.812 | $1,340.00      | $1,088.10       |
| 2024-05-05 |      0.580 | $1,077.00      | $624.91         |
| 2024-02-24 |      0.107 | $750.00        | $80.31          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
