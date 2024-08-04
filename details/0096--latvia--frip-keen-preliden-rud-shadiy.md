### Roster Details<br />
Team Name: Latvia<br />
Roster: Frip, keen, prelideN, rud, shadiy<br />
Global Rank: [96](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [69]( ../standings_europe.md)<br />
<br />
Final Rank Value:  861.9<br />
<br />
Final Rank Value (861.9) = Starting Rank Value (861.1) + Head To Head Adjustments (0.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.308[<sup>1</sup>](#table2)
- Bounty Collected: 0.320[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.257[<sup>2</sup>](#table1)

The average of these factors is 0.225<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 861.1
- 400 + ( ( 0.225 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 861.1


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
|           10 |      802 | 2024-07-14 | ALTERNATE aTTaX | L   | 1.000      | -            | -                | -                | -         |   -15.25 | Frip, keen, prelideN, rud, shadiy    |
|            9 |      865 | 2024-07-10 | Norway          | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.107 (0.015)    | 0 (0.000) |     7.90 | Frip, keen, prelideN, rud, shadiy    |
|            8 |      901 | 2024-07-08 | 3DMAX           | W   | 1.000      | 0.143        | 0.506 (0.072)    | 1.000 (0.143)    | 0 (0.000) |    30.02 | Frip, keen, prelideN, rud, shadiy    |
|            7 |      909 | 2024-07-08 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -16.79 | Frip, keen, prelideN, rud, shadiy    |
|            6 |     1256 | 2024-06-09 | Esprots         | L   | 0.824      | -            | -                | -                | -         |   -18.18 | Frip, keen, prelideN, raw, shadiy    |
|            5 |     1274 | 2024-06-08 | hypewrld        | W   | 0.821      | 0.334        | 0.002 (0.001)    | 0.028 (0.008)    | 1 (0.821) |     5.98 | Frip, keen, prelideN, raw, shadiy    |
|            4 |     2338 | 2024-05-05 | hypewrld        | W   | 0.594      | 0.257        | 0.002 (0.000)    | 0.028 (0.004)    | 1 (0.594) |     4.54 | flairr, Frip, Mairel, rud, shadiy    |
|            3 |     2345 | 2024-05-05 | MightyWolves    | W   | 0.593      | 0.257        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.593) |     1.30 | flairr, Frip, Mairel, rud, shadiy    |
|            2 |     4020 | 2024-02-24 | hypewrld        | W   | 0.120      | 0.262        | 0.002 (0.000)    | 0.028 (0.001)    | 1 (0.120) |     0.93 | EIZA, keen, prelideN, shadiy, shield |
|            1 |     4025 | 2024-02-24 | kloogarand      | W   | 0.119      | 0.262        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.119) |     0.43 | EIZA, keen, prelideN, shadiy, shield |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,835.62)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.825 | $1,340.00      | $1,106.00       |
| 2024-05-05 |      0.594 | $1,077.00      | $639.29         |
| 2024-02-24 |      0.120 | $750.00        | $90.33          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
