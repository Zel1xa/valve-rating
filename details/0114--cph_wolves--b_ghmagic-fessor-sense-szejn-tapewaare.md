### Roster Details<br />
Team Name: CPH Wolves<br />
Roster: BøghmagiC, Fessor, sense, szejn, Tapewaare<br />
Global Rank: [114](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [83]( ../standings_europe.md)<br />
<br />
Final Rank Value:  824.6<br />
<br />
Final Rank Value (824.6) = Starting Rank Value (781.2) + Head To Head Adjustments (43.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.292[<sup>1</sup>](#table2)
- Bounty Collected: 0.342[<sup>2</sup>](#table1)
- Opponent Network: 0.107[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 781.2
- 400 + ( ( 0.185 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 781.2


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
|           23 |       51 | 2024-08-04 | The Suspect      | L   | 1.000      | -            | -                | -                | -         |   -14.00 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           22 |      240 | 2024-07-30 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |    -6.21 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           21 |      306 | 2024-07-28 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -12.81 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           20 |      331 | 2024-07-27 | 1WIN             | L   | 1.000      | -            | -                | -                | -         |   -10.28 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           19 |      441 | 2024-07-24 | Space            | W   | 1.000      | 0.435        | 0.006 (0.003)    | 0.429 (0.187)    | 0 (0.000) |    18.40 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           18 |      467 | 2024-07-23 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -13.54 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           17 |      489 | 2024-07-22 | TSM              | W   | 1.000      | 0.143        | 0.040 (0.006)    | 0.461 (0.066)    | 0 (0.000) |    22.88 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           16 |      499 | 2024-07-22 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |    -9.50 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           15 |      544 | 2024-07-20 | INFINITE         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.182 (0.026)    | 0 (0.000) |     6.24 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           14 |      556 | 2024-07-20 | Space            | L   | 1.000      | -            | -                | -                | -         |   -12.60 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           13 |      591 | 2024-07-19 | Heimo            | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.103 (0.015)    | 0 (0.000) |     7.59 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           12 |      667 | 2024-07-18 | Passion UA       | W   | 1.000      | 0.435        | 0.173 (0.075)    | 1.000 (0.435)    | 0 (0.000) |    23.61 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           11 |      765 | 2024-07-16 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -12.37 | BøghmagiC, Fessor, sense, shadiy, Tapewaare |
|           10 |      820 | 2024-07-15 | GUN5             | W   | 1.000      | 0.435        | 0.072 (0.031)    | 0.550 (0.239)    | 0 (0.000) |    22.19 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|            9 |     1039 | 2024-06-16 | 777              | W   | 0.860      | 0.143        | 0.015 (0.002)    | 0.173 (0.021)    | 0 (0.000) |    10.33 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            8 |     1107 | 2024-06-14 | FLuffy Gangsters | W   | 0.847      | 0.143        | -                | 0.216 (0.026)    | 0 (0.000) |     6.47 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            7 |     1148 | 2024-06-13 | INFINITE         | W   | 0.840      | 0.143        | -                | 0.182 (0.022)    | 0 (0.000) |     5.55 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            6 |     1163 | 2024-06-12 | Sashi            | L   | 0.834      | -            | -                | -                | -         |    -2.42 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            5 |     1173 | 2024-06-12 | WOPA             | W   | 0.834      | 0.340        | 0.001 (0.000)    | 0.121 (0.034)    | 0 (0.000) |     7.18 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            4 |     2010 | 2024-05-18 | VP.Prodigy       | L   | 0.666      | -            | -                | -                | -         |    -7.98 | Basso, BøghmagiC, Fessor, szejn, vigg0      |
|            3 |     2036 | 2024-05-17 | MASONIC          | W   | 0.661      | 0.143        | 0.009 (0.001)    | -                | -         |    10.13 | Basso, BøghmagiC, Fessor, szejn, vigg0      |
|            2 |     2072 | 2024-05-16 | Rhyno            | L   | 0.654      | -            | -                | -                | -         |    -5.35 | Basso, BøghmagiC, Fessor, szejn, vigg0      |
|            1 |     2129 | 2024-05-15 | MASONIC          | W   | 0.646      | 0.143        | 0.009 (0.001)    | -                | -         |     9.95 | Basso, BøghmagiC, Fessor, szejn, vigg0      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,202.40)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
