### Roster Details<br />
Team Name: CPH Wolves<br />
Roster: BøghmagiC, Fessor, sense, szejn, Tapewaare<br />
Global Rank: [113](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [81]( ../standings_europe.md)<br />
<br />
Final Rank Value:  835.5<br />
<br />
Final Rank Value (835.5) = Starting Rank Value (778.4) + Head To Head Adjustments (57.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.292[<sup>1</sup>](#table2)
- Bounty Collected: 0.342[<sup>2</sup>](#table1)
- Opponent Network: 0.106[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 778.4
- 400 + ( ( 0.185 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 778.4


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
|           22 |      182 | 2024-07-30 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |    -6.26 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           21 |      248 | 2024-07-28 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -12.94 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           20 |      273 | 2024-07-27 | 1WIN             | L   | 1.000      | -            | -                | -                | -         |   -10.59 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           19 |      383 | 2024-07-24 | Space            | W   | 1.000      | 0.435        | 0.006 (0.003)    | 0.406 (0.177)    | 0 (0.000) |    18.56 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           18 |      409 | 2024-07-23 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -13.70 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           17 |      431 | 2024-07-22 | TSM              | W   | 1.000      | 0.143        | 0.040 (0.006)    | 0.354 (0.051)    | 0 (0.000) |    22.55 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           16 |      441 | 2024-07-22 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |   -10.04 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           15 |      486 | 2024-07-20 | INFINITE         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.187 (0.027)    | 0 (0.000) |     6.26 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           14 |      498 | 2024-07-20 | Space            | L   | 1.000      | -            | -                | -                | -         |   -12.47 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           13 |      533 | 2024-07-19 | Heimo            | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.107 (0.015)    | 0 (0.000) |     7.61 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           12 |      610 | 2024-07-18 | Passion UA       | W   | 1.000      | 0.435        | 0.172 (0.075)    | 1.000 (0.435)    | 0 (0.000) |    23.46 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           11 |      708 | 2024-07-16 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -12.42 | BøghmagiC, Fessor, sense, shadiy, Tapewaare |
|           10 |      763 | 2024-07-15 | GUN5             | W   | 1.000      | 0.435        | 0.073 (0.032)    | 0.570 (0.248)    | 0 (0.000) |    22.20 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|            9 |      981 | 2024-06-16 | 777              | W   | 0.873      | 0.143        | 0.015 (0.002)    | 0.181 (0.023)    | 0 (0.000) |    10.58 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            8 |     1049 | 2024-06-14 | FLuffy Gangsters | W   | 0.861      | 0.143        | -                | 0.222 (0.027)    | 0 (0.000) |     6.54 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            7 |     1090 | 2024-06-13 | INFINITE         | W   | 0.853      | 0.143        | -                | 0.187 (0.023)    | 0 (0.000) |     5.67 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            6 |     1105 | 2024-06-12 | Sashi            | L   | 0.848      | -            | -                | -                | -         |    -2.44 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            5 |     1115 | 2024-06-12 | WOPA             | W   | 0.847      | 0.340        | 0.001 (0.000)    | 0.127 (0.037)    | 0 (0.000) |     7.32 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            4 |     1952 | 2024-05-18 | VP.Prodigy       | L   | 0.680      | -            | -                | -                | -         |    -8.10 | Basso, BøghmagiC, Fessor, szejn, vigg0      |
|            3 |     1978 | 2024-05-17 | MASONIC          | W   | 0.674      | 0.143        | 0.009 (0.001)    | -                | -         |    10.43 | Basso, BøghmagiC, Fessor, szejn, vigg0      |
|            2 |     2014 | 2024-05-16 | Rhyno            | L   | 0.667      | -            | -                | -                | -         |    -5.38 | Basso, BøghmagiC, Fessor, szejn, vigg0      |
|            1 |     2071 | 2024-05-15 | MASONIC          | W   | 0.660      | 0.143        | 0.009 (0.001)    | -                | -         |    10.25 | Basso, BøghmagiC, Fessor, szejn, vigg0      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,221.91)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
