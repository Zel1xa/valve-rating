### Roster Details<br />
Team Name: GR<br />
Roster: 7nation, mediocrity, Overdue, SALO_MUX, weqt2<br />
Global Rank: [189](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [119]( ../standings_europe.md)<br />
<br />
Final Rank Value:  600.7<br />
<br />
Final Rank Value (600.7) = Starting Rank Value (673.0) + Head To Head Adjustments (-72.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.322[<sup>1</sup>](#table2)
- Bounty Collected: 0.210[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.133<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 673.0
- 400 + ( ( 0.133 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 673.0


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
|           13 |      191 | 2024-07-29 | Bromo             | L   | 1.000      | -            | -                | -                | -         |   -19.65 | 7nation, mediocrity, Overdue, SALO_MUX, weqt2 |
|           12 |      222 | 2024-07-28 | AY                | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.10 | 7nation, mediocrity, Overdue, SALO_MUX, weqt2 |
|           11 |      269 | 2024-07-26 | NomadS            | L   | 1.000      | -            | -                | -                | -         |   -20.41 | 7nation, mediocrity, Overdue, SALO_MUX, weqt2 |
|           10 |      765 | 2024-07-12 | Alter Ego         | L   | 1.000      | -            | -                | -                | -         |   -21.47 | 7nation, mediocrity, Runnin, SALO_MUX, weqt2  |
|            9 |      769 | 2024-07-12 | Chinggis Warriors | L   | 1.000      | -            | -                | -                | -         |   -11.41 | 7nation, mediocrity, Runnin, SALO_MUX, weqt2  |
|            8 |     1262 | 2024-06-07 | TYLOO             | L   | 0.819      | -            | -                | -                | -         |   -10.89 | mediocrity, qqGOD, SALO_MUX, uwrr, weqt2      |
|            7 |     1333 | 2024-06-06 | Clutch            | W   | 0.812      | 0.416        | 0.005 (0.002)    | 0.065 (0.022)    | 0 (0.000) |    13.15 | mediocrity, qqGOD, SALO_MUX, uwrr, weqt2      |
|            6 |     1390 | 2024-06-05 | ATOX              | L   | 0.805      | -            | -                | -                | -         |    -5.97 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2    |
|            5 |     4082 | 2024-02-16 | FlyQuest          | L   | 0.077      | -            | -                | -                | -         |    -0.15 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2  |
|            4 |     4108 | 2024-02-16 | MAG               | L   | 0.072      | -            | -                | -                | -         |    -1.68 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2  |
|            3 |     4112 | 2024-02-16 | Newhappy          | L   | 0.071      | -            | -                | -                | -         |    -1.62 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2  |
|            2 |     4136 | 2024-02-15 | The Huns          | W   | 0.065      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     0.36 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2  |
|            1 |     4176 | 2024-02-14 | ZEUS              | W   | 0.059      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.33 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,535.44)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.831 | $3,000.00      | $2,494.31       |
| 2024-02-17 |      0.082 | $500.00        | $41.13          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
