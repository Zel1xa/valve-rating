### Roster Details<br />
Team Name: Latvia<br />
Roster: Frip, keen, prelideN, rud, shadiy<br />
Global Rank: [99](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [70]( ../standings_europe.md)<br />
<br />
Final Rank Value:  861.6<br />
<br />
Final Rank Value (861.6) = Starting Rank Value (860.5) + Head To Head Adjustments (1.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.308[<sup>1</sup>](#table2)
- Bounty Collected: 0.320[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.254[<sup>2</sup>](#table1)

The average of these factors is 0.225<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 860.5
- 400 + ( ( 0.225 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 860.5


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
|           10 |      830 | 2024-07-14 | ALTERNATE aTTaX | L   | 1.000      | -            | -                | -                | -         |   -15.17 | Frip, keen, prelideN, rud, shadiy    |
|            9 |      893 | 2024-07-10 | Norway          | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.106 (0.015)    | 0 (0.000) |     7.91 | Frip, keen, prelideN, rud, shadiy    |
|            8 |      929 | 2024-07-08 | 3DMAX           | W   | 1.000      | 0.143        | 0.509 (0.073)    | 1.000 (0.143)    | 0 (0.000) |    30.07 | Frip, keen, prelideN, rud, shadiy    |
|            7 |      937 | 2024-07-08 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -16.76 | Frip, keen, prelideN, rud, shadiy    |
|            6 |     1284 | 2024-06-09 | Esprots         | L   | 0.815      | -            | -                | -                | -         |   -17.95 | Frip, keen, prelideN, raw, shadiy    |
|            5 |     1302 | 2024-06-08 | hypewrld        | W   | 0.812      | 0.334        | 0.002 (0.001)    | 0.027 (0.007)    | 1 (0.812) |     5.92 | Frip, keen, prelideN, raw, shadiy    |
|            4 |     2366 | 2024-05-05 | hypewrld        | W   | 0.585      | 0.257        | 0.002 (0.000)    | 0.027 (0.004)    | 1 (0.585) |     4.47 | flairr, Frip, Mairel, rud, shadiy    |
|            3 |     2373 | 2024-05-05 | MightyWolves    | W   | 0.584      | 0.257        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.584) |     1.28 | flairr, Frip, Mairel, rud, shadiy    |
|            2 |     4048 | 2024-02-24 | hypewrld        | W   | 0.111      | 0.262        | 0.002 (0.000)    | 0.027 (0.001)    | 1 (0.111) |     0.86 | EIZA, keen, prelideN, shadiy, shield |
|            1 |     4053 | 2024-02-24 | kloogarand      | W   | 0.110      | 0.262        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.110) |     0.40 | EIZA, keen, prelideN, shadiy, shield |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,806.96)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.816 | $1,340.00      | $1,093.87       |
| 2024-05-05 |      0.585 | $1,077.00      | $629.55         |
| 2024-02-24 |      0.111 | $750.00        | $83.54          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
