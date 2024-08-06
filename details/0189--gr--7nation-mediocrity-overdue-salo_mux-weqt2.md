### Roster Details<br />
Team Name: GR<br />
Roster: 7nation, mediocrity, Overdue, SALO_MUX, weqt2<br />
Global Rank: [189](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [119]( ../standings_europe.md)<br />
<br />
Final Rank Value:  607.4<br />
<br />
Final Rank Value (607.4) = Starting Rank Value (673.2) + Head To Head Adjustments (-65.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.209[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.133<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 673.2
- 400 + ( ( 0.133 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 673.2


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
|           13 |      277 | 2024-07-29 | Bromo             | L   | 1.000      | -            | -                | -                | -         |   -19.92 | 7nation, mediocrity, Overdue, SALO_MUX, weqt2 |
|           12 |      308 | 2024-07-28 | AY                | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.89 | 7nation, mediocrity, Overdue, SALO_MUX, weqt2 |
|           11 |      355 | 2024-07-26 | NomadS            | L   | 1.000      | -            | -                | -                | -         |   -20.69 | 7nation, mediocrity, Overdue, SALO_MUX, weqt2 |
|           10 |      858 | 2024-07-12 | Alter Ego         | L   | 1.000      | -            | -                | -                | -         |   -21.62 | 7nation, mediocrity, Runnin, SALO_MUX, weqt2  |
|            9 |      862 | 2024-07-12 | Chinggis Warriors | L   | 1.000      | -            | -                | -                | -         |    -9.07 | 7nation, mediocrity, Runnin, SALO_MUX, weqt2  |
|            8 |     1386 | 2024-06-07 | TYLOO             | L   | 0.803      | -            | -                | -                | -         |    -6.26 | mediocrity, qqGOD, SALO_MUX, uwrr, weqt2      |
|            7 |     1457 | 2024-06-06 | Clutch            | W   | 0.796      | 0.416        | 0.005 (0.002)    | 0.062 (0.020)    | 0 (0.000) |    12.88 | mediocrity, qqGOD, SALO_MUX, uwrr, weqt2      |
|            6 |     1514 | 2024-06-05 | ATOX              | L   | 0.790      | -            | -                | -                | -         |    -5.82 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2    |
|            5 |     4222 | 2024-02-16 | FlyQuest          | L   | 0.061      | -            | -                | -                | -         |    -0.12 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2  |
|            4 |     4248 | 2024-02-16 | MAG               | L   | 0.057      | -            | -                | -                | -         |    -1.32 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2  |
|            3 |     4252 | 2024-02-16 | Newhappy          | L   | 0.055      | -            | -                | -                | -         |    -1.26 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2  |
|            2 |     4276 | 2024-02-15 | The Huns          | W   | 0.049      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     0.28 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2  |
|            1 |     4316 | 2024-02-14 | ZEUS              | W   | 0.043      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.24 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,480.83)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.816 | $3,000.00      | $2,447.50       |
| 2024-02-17 |      0.067 | $500.00        | $33.33          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
