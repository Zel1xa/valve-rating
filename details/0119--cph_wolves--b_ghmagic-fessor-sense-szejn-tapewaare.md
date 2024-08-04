### Roster Details<br />
Team Name: CPH Wolves<br />
Roster: BøghmagiC, Fessor, sense, szejn, Tapewaare<br />
Global Rank: [119](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [85]( ../standings_europe.md)<br />
<br />
Final Rank Value:  821.8<br />
<br />
Final Rank Value (821.8) = Starting Rank Value (778.7) + Head To Head Adjustments (43.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.292[<sup>1</sup>](#table2)
- Bounty Collected: 0.342[<sup>2</sup>](#table1)
- Opponent Network: 0.107[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 778.7
- 400 + ( ( 0.185 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 778.7


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
|           23 |       12 | 2024-08-04 | The Suspect      | L   | 1.000      | -            | -                | -                | -         |   -13.92 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           22 |      205 | 2024-07-30 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |    -6.22 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           21 |      271 | 2024-07-28 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -13.11 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           20 |      296 | 2024-07-27 | 1WIN             | L   | 1.000      | -            | -                | -                | -         |   -10.43 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           19 |      406 | 2024-07-24 | Space            | W   | 1.000      | 0.435        | 0.006 (0.003)    | 0.406 (0.177)    | 0 (0.000) |    18.34 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           18 |      432 | 2024-07-23 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -13.89 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           17 |      454 | 2024-07-22 | TSM              | W   | 1.000      | 0.143        | 0.040 (0.006)    | 0.394 (0.056)    | 0 (0.000) |    22.56 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           16 |      464 | 2024-07-22 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |    -9.58 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           15 |      509 | 2024-07-20 | INFINITE         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.187 (0.027)    | 0 (0.000) |     6.26 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           14 |      521 | 2024-07-20 | Space            | L   | 1.000      | -            | -                | -                | -         |   -12.70 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           13 |      556 | 2024-07-19 | Heimo            | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.107 (0.015)    | 0 (0.000) |     7.60 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           12 |      632 | 2024-07-18 | Passion UA       | W   | 1.000      | 0.435        | 0.172 (0.075)    | 1.000 (0.435)    | 0 (0.000) |    23.53 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           11 |      730 | 2024-07-16 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -12.43 | BøghmagiC, Fessor, sense, shadiy, Tapewaare |
|           10 |      785 | 2024-07-15 | GUN5             | W   | 1.000      | 0.435        | 0.073 (0.032)    | 0.570 (0.248)    | 0 (0.000) |    22.25 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|            9 |     1004 | 2024-06-16 | 777              | W   | 0.872      | 0.143        | 0.015 (0.002)    | 0.181 (0.023)    | 0 (0.000) |    10.56 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            8 |     1072 | 2024-06-14 | FLuffy Gangsters | W   | 0.860      | 0.143        | -                | 0.222 (0.027)    | 0 (0.000) |     6.55 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            7 |     1113 | 2024-06-13 | INFINITE         | W   | 0.852      | 0.143        | -                | 0.187 (0.023)    | 0 (0.000) |     5.66 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            6 |     1128 | 2024-06-12 | Sashi            | L   | 0.847      | -            | -                | -                | -         |    -2.43 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            5 |     1138 | 2024-06-12 | WOPA             | W   | 0.847      | 0.340        | 0.001 (0.000)    | 0.127 (0.036)    | 0 (0.000) |     7.31 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            4 |     1975 | 2024-05-18 | VP.Prodigy       | L   | 0.679      | -            | -                | -                | -         |    -8.08 | Basso, BøghmagiC, Fessor, szejn, vigg0      |
|            3 |     2001 | 2024-05-17 | MASONIC          | W   | 0.673      | 0.143        | 0.009 (0.001)    | -                | -         |    10.40 | Basso, BøghmagiC, Fessor, szejn, vigg0      |
|            2 |     2037 | 2024-05-16 | Rhyno            | L   | 0.667      | -            | -                | -                | -         |    -5.39 | Basso, BøghmagiC, Fessor, szejn, vigg0      |
|            1 |     2094 | 2024-05-15 | MASONIC          | W   | 0.659      | 0.143        | 0.009 (0.001)    | -                | -         |    10.23 | Basso, BøghmagiC, Fessor, szejn, vigg0      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,220.81)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
