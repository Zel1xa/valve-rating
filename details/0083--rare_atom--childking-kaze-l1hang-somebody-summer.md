### Roster Details<br />
Team Name: Rare Atom<br />
Roster: ChildKing, kaze, L1haNg, somebody, Summer<br />
Global Rank: [83](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [6]( ../standings_asia.md)<br />
<br />
Final Rank Value:  939.3<br />
<br />
Final Rank Value (939.3) = Starting Rank Value (859.5) + Head To Head Adjustments (79.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.326[<sup>1</sup>](#table2)
- Bounty Collected: 0.376[<sup>2</sup>](#table1)
- Opponent Network: 0.076[<sup>2</sup>](#table1)
- LAN Wins: 0.115[<sup>2</sup>](#table1)

The average of these factors is 0.223<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 859.5
- 400 + ( ( 0.223 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 859.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |       27 | 2024-08-05 | TYLOO       | L   | 1.000      | -            | -                | -                | -         |   -13.49 | ChildKing, kaze, L1haNg, somebody, Summer |
|           29 |       94 | 2024-08-03 | WDNMD       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.36 | ChildKing, kaze, L1haNg, somebody, Summer |
|           28 |      124 | 2024-08-02 | TYLOO       | W   | 1.000      | 0.143        | 0.056 (0.008)    | 0.283 (0.040)    | 0 (0.000) |    17.65 | ChildKing, kaze, L1haNg, somebody, Summer |
|           27 |      132 | 2024-08-02 | ATOX        | W   | 1.000      | 0.143        | 0.020 (0.003)    | 0.210 (0.030)    | 0 (0.000) |    13.73 | ChildKing, kaze, L1haNg, somebody, Summer |
|           26 |      164 | 2024-08-01 | TYLOO       | L   | 1.000      | -            | -                | -                | -         |   -13.06 | ChildKing, kaze, L1haNg, somebody, Summer |
|           25 |      173 | 2024-08-01 | ATOX        | W   | 1.000      | 0.143        | 0.020 (0.003)    | 0.210 (0.030)    | 0 (0.000) |    14.08 | ChildKing, kaze, L1haNg, somebody, Summer |
|           24 |      348 | 2024-07-27 | NomadS      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.38 | ChildKing, kaze, L1haNg, somebody, Summer |
|           23 |      350 | 2024-07-27 | CatEvil     | W   | 1.000      | 0.143        | -                | 0.231 (0.033)    | 0 (0.000) |     5.30 | ChildKing, kaze, L1haNg, somebody, Summer |
|           22 |      374 | 2024-07-26 | IHC         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.12 | ChildKing, kaze, L1haNg, somebody, Summer |
|           21 |      863 | 2024-07-13 | TYLOO       | W   | 1.000      | 0.143        | 0.056 (0.008)    | 0.283 (0.040)    | 0 (0.000) |    19.59 | ChildKing, kaze, L1haNg, somebody, Summer |
|           20 |      867 | 2024-07-13 | Alter Ego   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.39 | ChildKing, kaze, L1haNg, somebody, Summer |
|           19 |      894 | 2024-07-11 | The MongolZ | W   | 1.000      | 0.143        | 1.000 (0.143)    | 0.694 (0.099)    | 0 (0.000) |    31.36 | ChildKing, kaze, L1haNg, somebody, Summer |
|           18 |      896 | 2024-07-11 | CatEvil     | W   | 1.000      | 0.143        | -                | 0.231 (0.033)    | -         |     5.80 | ChildKing, kaze, L1haNg, somebody, Summer |
|           17 |     1203 | 2024-06-11 | Space       | L   | 0.827      | -            | -                | -                | -         |   -11.91 | ChildKing, L1haNg, Risk, somebody, Summer |
|           16 |     1242 | 2024-06-10 | SINNERS     | W   | 0.818      | 0.435        | 0.037 (0.013)    | 0.790 (0.281)    | -         |    19.77 | ChildKing, L1haNg, Risk, somebody, Summer |
|           15 |     1398 | 2024-06-07 | Passion UA  | L   | 0.800      | -            | -                | -                | -         |    -5.31 | ChildKing, L1haNg, Risk, somebody, Summer |
|           14 |     1537 | 2024-06-05 | RUBY        | W   | 0.785      | 0.435        | 0.095 (0.032)    | 0.479 (0.164)    | -         |    16.25 | ChildKing, L1haNg, Risk, somebody, Summer |
|           13 |     1599 | 2024-06-03 | Sampi       | L   | 0.772      | -            | -                | -                | -         |    -9.94 | ChildKing, L1haNg, Risk, somebody, Summer |
|           12 |     1843 | 2024-05-23 | MOUZ NXT    | L   | 0.699      | -            | -                | -                | -         |    -5.68 | ChildKing, L1haNg, Risk, somebody, Summer |
|           11 |     2019 | 2024-05-18 | Sangal      | L   | 0.666      | -            | -                | -                | -         |    -4.16 | ChildKing, L1haNg, Risk, somebody, Summer |
|           10 |     2040 | 2024-05-17 | NOM         | L   | 0.661      | -            | -                | -                | -         |   -17.45 | ChildKing, L1haNg, Risk, somebody, Summer |
|            9 |     2090 | 2024-05-16 | Metizport   | L   | 0.653      | -            | -                | -                | -         |    -7.66 | ChildKing, L1haNg, Risk, somebody, Summer |
|            8 |     2193 | 2024-05-14 | DMS         | L   | 0.640      | -            | -                | -                | -         |    -8.90 | ChildKing, L1haNg, Risk, somebody, Summer |
|            7 |     2223 | 2024-05-13 | NOM         | W   | 0.632      | -            | -                | -                | -         |     2.69 | ChildKing, L1haNg, Risk, somebody, Summer |
|            6 |     2764 | 2024-04-19 | The MongolZ | L   | 0.473      | -            | -                | -                | -         |    -0.05 | ChildKing, L1haNg, Risk, somebody, Summer |
|            5 |     2773 | 2024-04-19 | TYLOO       | W   | 0.472      | 0.143        | 0.019 (0.001)    | -                | -         |     5.33 | ChildKing, L1haNg, Risk, somebody, Summer |
|            4 |     2814 | 2024-04-18 | Lynn Vision | W   | 0.466      | 0.143        | 0.086 (0.006)    | 0.182 (0.012)    | -         |    10.87 | ChildKing, L1haNg, Risk, somebody, Summer |
|            3 |     2824 | 2024-04-18 | The MongolZ | L   | 0.465      | -            | -                | -                | -         |    -0.04 | ChildKing, L1haNg, Risk, somebody, Summer |
|            2 |     2854 | 2024-04-17 | NKT         | W   | 0.459      | -            | -                | -                | -         |     1.70 | ChildKing, L1haNg, Risk, somebody, Summer |
|            1 |     2859 | 2024-04-17 | MIRAI       | W   | 0.459      | 0.143        | 0.002 (0.000)    | -                | -         |     2.05 | ChildKing, L1haNg, Risk, somebody, Summer |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,756.00)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />