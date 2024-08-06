### Roster Details<br />
Team Name: GR<br />
Roster: 7nation, mediocrity, Overdue, SALO_MUX, weqt2<br />
Global Rank: [189](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [119]( ../standings_europe.md)<br />
<br />
Final Rank Value:  608.1<br />
<br />
Final Rank Value (608.1) = Starting Rank Value (673.9) + Head To Head Adjustments (-65.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.209[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.133<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 673.9
- 400 + ( ( 0.133 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 673.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |      288 | 2024-07-29 | Bromo             | L   | 1.000      | -            | -                | -                | -         |   -19.94 | 7nation, mediocrity, Overdue, SALO_MUX, weqt2 |
|           12 |      319 | 2024-07-28 | AY                | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.87 | 7nation, mediocrity, Overdue, SALO_MUX, weqt2 |
|           11 |      366 | 2024-07-26 | NomadS            | L   | 1.000      | -            | -                | -                | -         |   -20.71 | 7nation, mediocrity, Overdue, SALO_MUX, weqt2 |
|           10 |      869 | 2024-07-12 | Alter Ego         | L   | 1.000      | -            | -                | -                | -         |   -21.64 | 7nation, mediocrity, Runnin, SALO_MUX, weqt2  |
|            9 |      873 | 2024-07-12 | Chinggis Warriors | L   | 1.000      | -            | -                | -                | -         |    -9.08 | 7nation, mediocrity, Runnin, SALO_MUX, weqt2  |
|            8 |     1397 | 2024-06-07 | TYLOO             | L   | 0.800      | -            | -                | -                | -         |    -6.24 | mediocrity, qqGOD, SALO_MUX, uwrr, weqt2      |
|            7 |     1468 | 2024-06-06 | Clutch            | W   | 0.793      | 0.416        | 0.005 (0.002)    | 0.060 (0.020)    | 0 (0.000) |    12.83 | mediocrity, qqGOD, SALO_MUX, uwrr, weqt2      |
|            6 |     1525 | 2024-06-05 | ATOX              | L   | 0.787      | -            | -                | -                | -         |    -5.81 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2    |
|            5 |     4233 | 2024-02-16 | FlyQuest          | L   | 0.058      | -            | -                | -                | -         |    -0.12 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2  |
|            4 |     4259 | 2024-02-16 | MAG               | L   | 0.053      | -            | -                | -                | -         |    -1.25 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2  |
|            3 |     4263 | 2024-02-16 | Newhappy          | L   | 0.052      | -            | -                | -                | -         |    -1.19 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2  |
|            2 |     4287 | 2024-02-15 | The Huns          | W   | 0.046      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     0.26 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2  |
|            1 |     4327 | 2024-02-14 | ZEUS              | W   | 0.040      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.22 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,469.81)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.813 | $3,000.00      | $2,438.06       |
| 2024-02-17 |      0.064 | $500.00        | $31.76          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
