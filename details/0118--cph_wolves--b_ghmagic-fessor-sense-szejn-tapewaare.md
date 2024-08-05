### Roster Details<br />
Team Name: CPH Wolves<br />
Roster: BøghmagiC, Fessor, sense, szejn, Tapewaare<br />
Global Rank: [118](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [83]( ../standings_europe.md)<br />
<br />
Final Rank Value:  823.8<br />
<br />
Final Rank Value (823.8) = Starting Rank Value (780.4) + Head To Head Adjustments (43.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.292[<sup>1</sup>](#table2)
- Bounty Collected: 0.342[<sup>2</sup>](#table1)
- Opponent Network: 0.108[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.186<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 780.4
- 400 + ( ( 0.186 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 780.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |       40 | 2024-08-04 | The Suspect      | L   | 1.000      | -            | -                | -                | -         |   -13.99 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           22 |      232 | 2024-07-30 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |    -6.21 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           21 |      298 | 2024-07-28 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -13.03 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           20 |      323 | 2024-07-27 | 1WIN             | L   | 1.000      | -            | -                | -                | -         |   -10.28 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           19 |      433 | 2024-07-24 | Space            | W   | 1.000      | 0.435        | 0.006 (0.003)    | 0.439 (0.191)    | 0 (0.000) |    18.44 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           18 |      459 | 2024-07-23 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -13.78 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           17 |      481 | 2024-07-22 | TSM              | W   | 1.000      | 0.143        | 0.040 (0.006)    | 0.430 (0.061)    | 0 (0.000) |    22.87 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           16 |      491 | 2024-07-22 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |    -9.44 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           15 |      536 | 2024-07-20 | INFINITE         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.186 (0.027)    | 0 (0.000) |     6.24 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           14 |      548 | 2024-07-20 | Space            | L   | 1.000      | -            | -                | -                | -         |   -12.56 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           13 |      583 | 2024-07-19 | Heimo            | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.106 (0.015)    | 0 (0.000) |     7.59 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           12 |      659 | 2024-07-18 | Passion UA       | W   | 1.000      | 0.435        | 0.173 (0.075)    | 1.000 (0.435)    | 0 (0.000) |    23.59 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           11 |      757 | 2024-07-16 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -12.41 | BøghmagiC, Fessor, sense, shadiy, Tapewaare |
|           10 |      812 | 2024-07-15 | GUN5             | W   | 1.000      | 0.435        | 0.073 (0.032)    | 0.562 (0.244)    | 0 (0.000) |    22.23 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|            9 |     1031 | 2024-06-16 | 777              | W   | 0.865      | 0.143        | 0.015 (0.002)    | 0.177 (0.022)    | 0 (0.000) |    10.39 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            8 |     1099 | 2024-06-14 | FLuffy Gangsters | W   | 0.852      | 0.143        | -                | 0.220 (0.027)    | 0 (0.000) |     6.49 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            7 |     1140 | 2024-06-13 | INFINITE         | W   | 0.845      | 0.143        | -                | 0.186 (0.022)    | 0 (0.000) |     5.59 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            6 |     1155 | 2024-06-12 | Sashi            | L   | 0.840      | -            | -                | -                | -         |    -2.42 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            5 |     1165 | 2024-06-12 | WOPA             | W   | 0.839      | 0.340        | 0.001 (0.000)    | 0.124 (0.036)    | 0 (0.000) |     7.22 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            4 |     2002 | 2024-05-18 | VP.Prodigy       | L   | 0.672      | -            | -                | -                | -         |    -8.02 | Basso, BøghmagiC, Fessor, szejn, vigg0      |
|            3 |     2028 | 2024-05-17 | MASONIC          | W   | 0.666      | 0.143        | 0.009 (0.001)    | -                | -         |    10.23 | Basso, BøghmagiC, Fessor, szejn, vigg0      |
|            2 |     2064 | 2024-05-16 | Rhyno            | L   | 0.659      | -            | -                | -                | -         |    -5.38 | Basso, BøghmagiC, Fessor, szejn, vigg0      |
|            1 |     2121 | 2024-05-15 | MASONIC          | W   | 0.652      | 0.143        | 0.009 (0.001)    | -                | -         |    10.05 | Basso, BøghmagiC, Fessor, szejn, vigg0      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,209.94)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
