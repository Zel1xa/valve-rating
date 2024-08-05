### Roster Details<br />
Team Name: Latvia<br />
Roster: Frip, keen, prelideN, rud, shadiy<br />
Global Rank: [96](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [69]( ../standings_europe.md)<br />
<br />
Final Rank Value:  861.6<br />
<br />
Final Rank Value (861.6) = Starting Rank Value (860.7) + Head To Head Adjustments (0.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.308[<sup>1</sup>](#table2)
- Bounty Collected: 0.320[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.256[<sup>2</sup>](#table1)

The average of these factors is 0.225<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 860.7
- 400 + ( ( 0.225 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 860.7


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
|           10 |      806 | 2024-07-14 | ALTERNATE aTTaX | L   | 1.000      | -            | -                | -                | -         |   -15.24 | Frip, keen, prelideN, rud, shadiy    |
|            9 |      869 | 2024-07-10 | Norway          | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.107 (0.015)    | 0 (0.000) |     7.90 | Frip, keen, prelideN, rud, shadiy    |
|            8 |      905 | 2024-07-08 | 3DMAX           | W   | 1.000      | 0.143        | 0.507 (0.072)    | 1.000 (0.143)    | 0 (0.000) |    30.03 | Frip, keen, prelideN, rud, shadiy    |
|            7 |      913 | 2024-07-08 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -16.78 | Frip, keen, prelideN, rud, shadiy    |
|            6 |     1260 | 2024-06-09 | Esprots         | L   | 0.822      | -            | -                | -                | -         |   -18.12 | Frip, keen, prelideN, raw, shadiy    |
|            5 |     1278 | 2024-06-08 | hypewrld        | W   | 0.818      | 0.334        | 0.002 (0.001)    | 0.028 (0.008)    | 1 (0.818) |     5.96 | Frip, keen, prelideN, raw, shadiy    |
|            4 |     2342 | 2024-05-05 | hypewrld        | W   | 0.591      | 0.257        | 0.002 (0.000)    | 0.028 (0.004)    | 1 (0.591) |     4.52 | flairr, Frip, Mairel, rud, shadiy    |
|            3 |     2349 | 2024-05-05 | MightyWolves    | W   | 0.590      | 0.257        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.590) |     1.29 | flairr, Frip, Mairel, rud, shadiy    |
|            2 |     4024 | 2024-02-24 | hypewrld        | W   | 0.118      | 0.262        | 0.002 (0.000)    | 0.028 (0.001)    | 1 (0.118) |     0.91 | EIZA, keen, prelideN, shadiy, shield |
|            1 |     4029 | 2024-02-24 | kloogarand      | W   | 0.117      | 0.262        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.117) |     0.43 | EIZA, keen, prelideN, shadiy, shield |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,828.07)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.823 | $1,340.00      | $1,102.80       |
| 2024-05-05 |      0.591 | $1,077.00      | $636.73         |
| 2024-02-24 |      0.118 | $750.00        | $88.54          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
