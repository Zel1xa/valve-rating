### Roster Details<br />
Team Name: Lilmix<br />
Roster: bq, dex, L00m1, quix, SHiNE<br />
Global Rank: [109](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [80]( ../standings_europe.md)<br />
<br />
Final Rank Value:  848.7<br />
<br />
Final Rank Value (848.7) = Starting Rank Value (876.3) + Head To Head Adjustments (-27.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.380[<sup>1</sup>](#table2)
- Bounty Collected: 0.257[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.278[<sup>2</sup>](#table1)

The average of these factors is 0.231<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 876.3
- 400 + ( ( 0.231 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 876.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |       97 | 2024-07-30 | INFINITE        | L   | 1.000      | -            | -                | -                | -         |   -25.41 | bq, dex, L00m1, quix, SHiNE |
|            9 |      283 | 2024-07-24 | ALTERNATE aTTaX | L   | 1.000      | -            | -                | -                | -         |   -17.99 | bq, dex, L00m1, quix, SHiNE |
|            8 |      518 | 2024-07-18 | kONO            | W   | 1.000      | 0.143        | 0.029 (0.004)    | 0.547 (0.078)    | 0 (0.000) |    14.06 | bq, dex, L00m1, quix, SHiNE |
|            7 |      929 | 2024-06-15 | Johnny Speeds   | L   | 0.887      | -            | -                | -                | -         |    -3.19 | bq, dex, poiii, quix, zyyx  |
|            6 |      946 | 2024-06-14 | Young Gods      | W   | 0.882      | 0.377        | 0.007 (0.002)    | 0.034 (0.011)    | 1 (0.882) |     8.15 | bq, dex, poiii, quix, zyyx  |
|            5 |      964 | 2024-06-14 | Johnny Speeds   | L   | 0.880      | -            | -                | -                | -         |    -3.14 | bq, dex, poiii, quix, zyyx  |
|            4 |      996 | 2024-06-13 | Young Gods      | W   | 0.874      | 0.377        | 0.007 (0.002)    | 0.034 (0.011)    | 1 (0.874) |     8.25 | bq, dex, poiii, quix, zyyx  |
|            3 |     1133 | 2024-06-09 | Alliance        | L   | 0.847      | -            | -                | -                | -         |   -13.98 | bq, dex, poiii, quix, zyyx  |
|            2 |     2161 | 2024-05-11 | Johnny Speeds   | L   | 0.655      | -            | -                | -                | -         |    -1.91 | bq, dex, poiii, quix, zyyx  |
|            1 |     2170 | 2024-05-11 | AURA            | W   | 0.654      | 0.319        | 0.017 (0.004)    | 0.060 (0.012)    | 1 (0.654) |     7.56 | bq, dex, poiii, quix, zyyx  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,589.13)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-15 |      0.887 | $5,808.00      | $5,153.26       |
| 2024-06-09 |      0.848 | $1,445.00      | $1,224.64       |
| 2024-05-11 |      0.655 | $1,850.00      | $1,211.24       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
