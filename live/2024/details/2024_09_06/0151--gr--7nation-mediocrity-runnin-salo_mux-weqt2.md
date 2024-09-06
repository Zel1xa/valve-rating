### Roster Details<br />
Team Name: GR<br />
Roster: 7nation, mediocrity, Runnin, SALO_MUX, weqt2<br />
Global Rank: [151](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_06.md)<br />
Regional Rank: [101]( ../../standings_europe_2024_09_06.md)<br />
<br />
Final Rank Value:  701.0<br />
<br />
Final Rank Value (701.0) = Starting Rank Value (676.8) + Head To Head Adjustments (24.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.243[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.142<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 676.8
- 400 + ( ( 0.142 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 676.8


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
|           12 |      201 | 2024-08-30 | ATOX              | W   | 1.000      | 0.143        | 0.016 (0.002)    | 0.296 (0.042)    | 0 (0.000) |    20.35 | 7nation, mediocrity, Runnin, SALO_MUX, weqt2  |
|           11 |      254 | 2024-08-29 | Chinggis Warriors | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.193 (0.028)    | 0 (0.000) |    23.97 | 7nation, mediocrity, Runnin, SALO_MUX, weqt2  |
|           10 |      308 | 2024-08-28 | ATOX              | W   | 1.000      | 0.143        | 0.016 (0.002)    | 0.296 (0.042)    | 0 (0.000) |    21.81 | 7nation, mediocrity, Runnin, SALO_MUX, weqt2  |
|            9 |      318 | 2024-08-28 | -72c              | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.113 (0.016)    | 0 (0.000) |    14.79 | 7nation, mediocrity, Runnin, SALO_MUX, weqt2  |
|            8 |     1376 | 2024-07-29 | Bromo             | L   | 0.938      | -            | -                | -                | -         |   -19.13 | 7nation, mediocrity, Overdue, SALO_MUX, weqt2 |
|            7 |     1407 | 2024-07-28 | AY                | W   | 0.932      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.10 | 7nation, mediocrity, Overdue, SALO_MUX, weqt2 |
|            6 |     1454 | 2024-07-26 | NomadS            | L   | 0.919      | -            | -                | -                | -         |   -19.75 | 7nation, mediocrity, Overdue, SALO_MUX, weqt2 |
|            5 |     1960 | 2024-07-12 | Alter Ego         | L   | 0.825      | -            | -                | -                | -         |   -17.50 | 7nation, mediocrity, Runnin, SALO_MUX, weqt2  |
|            4 |     1964 | 2024-07-12 | Chinggis Warriors | L   | 0.824      | -            | -                | -                | -         |    -5.58 | 7nation, mediocrity, Runnin, SALO_MUX, weqt2  |
|            3 |     2488 | 2024-06-07 | TYLOO             | L   | 0.592      | -            | -                | -                | -         |    -3.51 | mediocrity, qqGOD, SALO_MUX, uwrr, weqt2      |
|            2 |     2559 | 2024-06-06 | Clutch            | W   | 0.585      | 0.416        | 0.004 (0.001)    | 0.044 (0.011)    | 0 (0.000) |     8.72 | mediocrity, qqGOD, SALO_MUX, uwrr, weqt2      |
|            1 |     2616 | 2024-06-05 | ATOX              | L   | 0.578      | -            | -                | -                | -         |    -6.04 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,813.26)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
