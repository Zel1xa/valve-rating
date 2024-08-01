### Roster Details<br />
Team Name: CPH Wolves<br />
Roster: BøghmagiC, Fessor, sense, szejn, Tapewaare<br />
Global Rank: [111](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [82]( ../standings_europe.md)<br />
<br />
Final Rank Value:  838.4<br />
<br />
Final Rank Value (838.4) = Starting Rank Value (780.7) + Head To Head Adjustments (57.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.293[<sup>1</sup>](#table2)
- Bounty Collected: 0.342[<sup>2</sup>](#table1)
- Opponent Network: 0.105[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 780.7
- 400 + ( ( 0.185 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 780.7


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
|           22 |       89 | 2024-07-30 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |    -6.36 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           21 |      156 | 2024-07-28 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -13.07 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           20 |      181 | 2024-07-27 | 1WIN             | L   | 1.000      | -            | -                | -                | -         |   -11.34 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           19 |      291 | 2024-07-24 | Space            | W   | 1.000      | 0.435        | 0.006 (0.003)    | 0.406 (0.177)    | 0 (0.000) |    18.48 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           18 |      317 | 2024-07-23 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -13.93 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           17 |      340 | 2024-07-22 | TSM              | W   | 1.000      | 0.143        | 0.039 (0.006)    | 0.347 (0.050)    | 0 (0.000) |    22.40 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           16 |      350 | 2024-07-22 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |   -10.51 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           15 |      397 | 2024-07-20 | INFINITE         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.184 (0.026)    | 0 (0.000) |     6.17 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           14 |      409 | 2024-07-20 | Space            | L   | 1.000      | -            | -                | -                | -         |   -12.59 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           13 |      445 | 2024-07-19 | Heimo            | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.086 (0.012)    | 0 (0.000) |     7.58 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           12 |      524 | 2024-07-18 | Passion UA       | W   | 1.000      | 0.435        | 0.173 (0.075)    | 1.000 (0.435)    | 0 (0.000) |    23.04 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|           11 |      627 | 2024-07-16 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -11.15 | BøghmagiC, Fessor, sense, shadiy, Tapewaare |
|           10 |      687 | 2024-07-15 | GUN5             | W   | 1.000      | 0.435        | 0.074 (0.032)    | 0.555 (0.241)    | 0 (0.000) |    22.81 | BøghmagiC, Fessor, sense, szejn, Tapewaare  |
|            9 |      904 | 2024-06-16 | 777              | W   | 0.892      | 0.143        | 0.015 (0.002)    | 0.182 (0.023)    | 0 (0.000) |    10.81 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            8 |      962 | 2024-06-14 | FLuffy Gangsters | W   | 0.879      | 0.143        | -                | 0.219 (0.028)    | 0 (0.000) |     6.65 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            7 |     1004 | 2024-06-13 | INFINITE         | W   | 0.872      | 0.143        | -                | 0.184 (0.023)    | 0 (0.000) |     5.75 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            6 |     1019 | 2024-06-12 | Sashi            | L   | 0.867      | -            | -                | -                | -         |    -2.53 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            5 |     1029 | 2024-06-12 | WOPA             | W   | 0.866      | 0.340        | 0.001 (0.000)    | 0.127 (0.037)    | 0 (0.000) |     7.44 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ   |
|            4 |     1911 | 2024-05-18 | VP.Prodigy       | L   | 0.699      | -            | -                | -                | -         |    -8.25 | Basso, BøghmagiC, Fessor, szejn, vigg0      |
|            3 |     1937 | 2024-05-17 | MASONIC          | W   | 0.693      | 0.143        | 0.009 (0.001)    | -                | -         |    10.87 | Basso, BøghmagiC, Fessor, szejn, vigg0      |
|            2 |     1973 | 2024-05-16 | Rhyno            | L   | 0.686      | -            | -                | -                | -         |    -5.29 | Basso, BøghmagiC, Fessor, szejn, vigg0      |
|            1 |     2034 | 2024-05-15 | MASONIC          | W   | 0.679      | 0.143        | 0.009 (0.001)    | -                | -         |    10.71 | Basso, BøghmagiC, Fessor, szejn, vigg0      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,248.97)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
