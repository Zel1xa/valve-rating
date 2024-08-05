### Roster Details<br />
Team Name: Latvia<br />
Roster: Frip, keen, prelideN, rud, shadiy<br />
Global Rank: [99](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [70]( ../standings_europe.md)<br />
<br />
Final Rank Value:  861.8<br />
<br />
Final Rank Value (861.8) = Starting Rank Value (860.8) + Head To Head Adjustments (1.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.308[<sup>1</sup>](#table2)
- Bounty Collected: 0.320[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.254[<sup>2</sup>](#table1)

The average of these factors is 0.225<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 860.8
- 400 + ( ( 0.225 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 860.8


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
|           10 |      828 | 2024-07-14 | ALTERNATE aTTaX | L   | 1.000      | -            | -                | -                | -         |   -15.17 | Frip, keen, prelideN, rud, shadiy    |
|            9 |      891 | 2024-07-10 | Norway          | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.106 (0.015)    | 0 (0.000) |     7.91 | Frip, keen, prelideN, rud, shadiy    |
|            8 |      927 | 2024-07-08 | 3DMAX           | W   | 1.000      | 0.143        | 0.508 (0.073)    | 1.000 (0.143)    | 0 (0.000) |    30.06 | Frip, keen, prelideN, rud, shadiy    |
|            7 |      935 | 2024-07-08 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -16.77 | Frip, keen, prelideN, rud, shadiy    |
|            6 |     1282 | 2024-06-09 | Esprots         | L   | 0.817      | -            | -                | -                | -         |   -18.00 | Frip, keen, prelideN, raw, shadiy    |
|            5 |     1300 | 2024-06-08 | hypewrld        | W   | 0.813      | 0.334        | 0.002 (0.001)    | 0.027 (0.007)    | 1 (0.813) |     5.93 | Frip, keen, prelideN, raw, shadiy    |
|            4 |     2364 | 2024-05-05 | hypewrld        | W   | 0.586      | 0.257        | 0.002 (0.000)    | 0.027 (0.004)    | 1 (0.586) |     4.48 | flairr, Frip, Mairel, rud, shadiy    |
|            3 |     2371 | 2024-05-05 | MightyWolves    | W   | 0.585      | 0.257        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.585) |     1.28 | flairr, Frip, Mairel, rud, shadiy    |
|            2 |     4046 | 2024-02-24 | hypewrld        | W   | 0.113      | 0.262        | 0.002 (0.000)    | 0.027 (0.001)    | 1 (0.113) |     0.87 | EIZA, keen, prelideN, shadiy, shield |
|            1 |     4051 | 2024-02-24 | kloogarand      | W   | 0.112      | 0.262        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.112) |     0.41 | EIZA, keen, prelideN, shadiy, shield |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,812.67)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.818 | $1,340.00      | $1,096.29       |
| 2024-05-05 |      0.586 | $1,077.00      | $631.49         |
| 2024-02-24 |      0.113 | $750.00        | $84.90          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
