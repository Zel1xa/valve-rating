### Roster Details<br />
Team Name: Rare Atom<br />
Roster: ChildKing, kaze, L1haNg, somebody, Summer<br />
Global Rank: [85](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [4]( ../standings_asia.md)<br />
<br />
Final Rank Value:  923.7<br />
<br />
Final Rank Value (923.7) = Starting Rank Value (857.6) + Head To Head Adjustments (66.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.326[<sup>1</sup>](#table2)
- Bounty Collected: 0.372[<sup>2</sup>](#table1)
- Opponent Network: 0.076[<sup>2</sup>](#table1)
- LAN Wins: 0.115[<sup>2</sup>](#table1)

The average of these factors is 0.222<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 857.6
- 400 + ( ( 0.222 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 857.6


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
|           30 |       22 | 2024-08-05 | TYLOO       | L   | 1.000      | -            | -                | -                | -         |   -16.55 | ChildKing, kaze, L1haNg, somebody, Summer |
|           29 |       89 | 2024-08-03 | WDNMD       | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.46 | ChildKing, kaze, L1haNg, somebody, Summer |
|           28 |      119 | 2024-08-02 | TYLOO       | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.283 (0.040)    | 0 (0.000) |    14.15 | ChildKing, kaze, L1haNg, somebody, Summer |
|           27 |      127 | 2024-08-02 | ATOX        | W   | 1.000      | 0.143        | 0.020 (0.003)    | 0.210 (0.030)    | 0 (0.000) |    14.08 | ChildKing, kaze, L1haNg, somebody, Summer |
|           26 |      159 | 2024-08-01 | TYLOO       | L   | 1.000      | -            | -                | -                | -         |   -16.86 | ChildKing, kaze, L1haNg, somebody, Summer |
|           25 |      168 | 2024-08-01 | ATOX        | W   | 1.000      | 0.143        | 0.020 (0.003)    | 0.210 (0.030)    | 0 (0.000) |    14.29 | ChildKing, kaze, L1haNg, somebody, Summer |
|           24 |      343 | 2024-07-27 | NomadS      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.48 | ChildKing, kaze, L1haNg, somebody, Summer |
|           23 |      345 | 2024-07-27 | CatEvil     | W   | 1.000      | 0.143        | -                | 0.230 (0.033)    | 0 (0.000) |     5.39 | ChildKing, kaze, L1haNg, somebody, Summer |
|           22 |      369 | 2024-07-26 | IHC         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.17 | ChildKing, kaze, L1haNg, somebody, Summer |
|           21 |      858 | 2024-07-13 | TYLOO       | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.283 (0.040)    | 0 (0.000) |    15.40 | ChildKing, kaze, L1haNg, somebody, Summer |
|           20 |      862 | 2024-07-13 | Alter Ego   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.14 | ChildKing, kaze, L1haNg, somebody, Summer |
|           19 |      889 | 2024-07-11 | The MongolZ | W   | 1.000      | 0.143        | 1.000 (0.143)    | 0.694 (0.099)    | 0 (0.000) |    31.36 | ChildKing, kaze, L1haNg, somebody, Summer |
|           18 |      891 | 2024-07-11 | CatEvil     | W   | 1.000      | 0.143        | -                | 0.230 (0.033)    | -         |     5.85 | ChildKing, kaze, L1haNg, somebody, Summer |
|           17 |     1198 | 2024-06-11 | Space       | L   | 0.827      | -            | -                | -                | -         |   -11.94 | ChildKing, L1haNg, Risk, somebody, Summer |
|           16 |     1237 | 2024-06-10 | SINNERS     | W   | 0.819      | 0.435        | 0.037 (0.013)    | 0.790 (0.281)    | -         |    19.81 | ChildKing, L1haNg, Risk, somebody, Summer |
|           15 |     1393 | 2024-06-07 | Passion UA  | L   | 0.800      | -            | -                | -                | -         |    -5.29 | ChildKing, L1haNg, Risk, somebody, Summer |
|           14 |     1532 | 2024-06-05 | RUBY        | W   | 0.785      | 0.435        | 0.095 (0.032)    | 0.480 (0.164)    | -         |    16.25 | ChildKing, L1haNg, Risk, somebody, Summer |
|           13 |     1594 | 2024-06-03 | Sampi       | L   | 0.772      | -            | -                | -                | -         |    -9.93 | ChildKing, L1haNg, Risk, somebody, Summer |
|           12 |     1838 | 2024-05-23 | MOUZ NXT    | L   | 0.700      | -            | -                | -                | -         |    -5.66 | ChildKing, L1haNg, Risk, somebody, Summer |
|           11 |     2014 | 2024-05-18 | Sangal      | L   | 0.667      | -            | -                | -                | -         |    -4.19 | ChildKing, L1haNg, Risk, somebody, Summer |
|           10 |     2035 | 2024-05-17 | NOM         | L   | 0.662      | -            | -                | -                | -         |   -17.44 | ChildKing, L1haNg, Risk, somebody, Summer |
|            9 |     2085 | 2024-05-16 | Metizport   | L   | 0.653      | -            | -                | -                | -         |    -7.68 | ChildKing, L1haNg, Risk, somebody, Summer |
|            8 |     2188 | 2024-05-14 | DMS         | L   | 0.641      | -            | -                | -                | -         |    -8.86 | ChildKing, L1haNg, Risk, somebody, Summer |
|            7 |     2218 | 2024-05-13 | NOM         | W   | 0.632      | -            | -                | -                | -         |     2.71 | ChildKing, L1haNg, Risk, somebody, Summer |
|            6 |     2759 | 2024-04-19 | The MongolZ | L   | 0.474      | -            | -                | -                | -         |    -0.05 | ChildKing, L1haNg, Risk, somebody, Summer |
|            5 |     2768 | 2024-04-19 | TYLOO       | W   | 0.473      | 0.143        | 0.019 (0.001)    | -                | -         |     5.37 | ChildKing, L1haNg, Risk, somebody, Summer |
|            4 |     2809 | 2024-04-18 | Lynn Vision | W   | 0.467      | 0.143        | 0.086 (0.006)    | 0.182 (0.012)    | -         |    10.78 | ChildKing, L1haNg, Risk, somebody, Summer |
|            3 |     2819 | 2024-04-18 | The MongolZ | L   | 0.466      | -            | -                | -                | -         |    -0.04 | ChildKing, L1haNg, Risk, somebody, Summer |
|            2 |     2849 | 2024-04-17 | NKT         | W   | 0.460      | -            | -                | -                | -         |     1.72 | ChildKing, L1haNg, Risk, somebody, Summer |
|            1 |     2854 | 2024-04-17 | MIRAI       | W   | 0.459      | 0.143        | 0.002 (0.000)    | -                | -         |     2.07 | ChildKing, L1haNg, Risk, somebody, Summer |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,756.00)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
