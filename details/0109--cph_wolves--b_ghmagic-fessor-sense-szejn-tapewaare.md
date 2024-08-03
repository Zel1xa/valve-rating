### Roster Details<br />
Team Name: CPH Wolves<br />
Roster: BøghmagiC, Fessor, sense, szejn, Tapewaare<br />
Global Rank: [109](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [81]( ../standings_europe.md)<br />
<br />
Final Rank Value:  835.2<br />
<br />
Final Rank Value (835.2) = Starting Rank Value (779.5) + Head To Head Adjustments (55.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.292[<sup>1</sup>](#table2)
- Bounty Collected: 0.342[<sup>2</sup>](#table1)
- Opponent Network: 0.108[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 779.5
- 400 + ( ( 0.185 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 779.5


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
|           22 |      148 | 2024-07-30 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |    -6.68 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           21 |      214 | 2024-07-28 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -13.03 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           20 |      239 | 2024-07-27 | 1WIN             | L   | 1.000      | -            | -                | -                | -         |   -11.28 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           19 |      349 | 2024-07-24 | Space            | W   | 1.000      | 0.435        | 0.006 (0.003)    | 0.420 (0.183)    | 0 (0.000) |    19.02 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           18 |      375 | 2024-07-23 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -13.77 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           17 |      397 | 2024-07-22 | TSM              | W   | 1.000      | 0.143        | 0.039 (0.006)    | 0.364 (0.052)    | 0 (0.000) |    22.58 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           16 |      407 | 2024-07-22 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |   -10.42 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           15 |      452 | 2024-07-20 | INFINITE         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.193 (0.028)    | 0 (0.000) |     6.22 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           14 |      464 | 2024-07-20 | Space            | L   | 1.000      | -            | -                | -                | -         |   -12.00 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           13 |      499 | 2024-07-19 | Heimo            | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.089 (0.013)    | 0 (0.000) |     7.64 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           12 |      573 | 2024-07-18 | Passion UA       | W   | 1.000      | 0.435        | 0.172 (0.075)    | 1.000 (0.435)    | 0 (0.000) |    23.00 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           11 |      670 | 2024-07-16 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -12.42 | BøghmagiC, Fessor, sense, shadiy, Tapewaare |
|           10 |      726 | 2024-07-15 | GUN5             | W   | 1.000      | 0.435        | 0.073 (0.032)    | 0.588 (0.256)    | 0 (0.000) |    22.28 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|            9 |      932 | 2024-06-16 | 777              | W   | 0.879      | 0.143        | 0.014 (0.002)    | 0.184 (0.023)    | 0 (0.000) |    10.19 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            8 |      986 | 2024-06-14 | FLuffy Gangsters | W   | 0.866      | 0.143        | -                | 0.229 (0.028)    | 0 (0.000) |     6.57 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            7 |     1028 | 2024-06-13 | INFINITE         | W   | 0.859      | 0.143        | -                | 0.193 (0.024)    | 0 (0.000) |     5.69 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            6 |     1042 | 2024-06-12 | Sashi            | L   | 0.853      | -            | -                | -                | -         |    -2.47 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            5 |     1051 | 2024-06-12 | WOPA             | W   | 0.853      | 0.340        | 0.001 (0.000)    | 0.131 (0.038)    | 0 (0.000) |     7.34 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            4 |     1875 | 2024-05-18 | VP.Prodigy       | L   | 0.685      | -            | -                | -                | -         |    -8.15 | Basso, BøghmagiC, Fessor, szejn, vigg0      |
|            3 |     1901 | 2024-05-17 | MASONIC          | W   | 0.680      | 0.143        | 0.009 (0.001)    | -                | -         |    10.48 | Basso, BøghmagiC, Fessor, szejn, vigg0      |
|            2 |     1937 | 2024-05-16 | Rhyno            | L   | 0.673      | -            | -                | -                | -         |    -5.41 | Basso, BøghmagiC, Fessor, szejn, vigg0      |
|            1 |     1994 | 2024-05-15 | MASONIC          | W   | 0.665      | 0.143        | 0.009 (0.001)    | -                | -         |    10.31 | Basso, BøghmagiC, Fessor, szejn, vigg0      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,229.82)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
