### Roster Details<br />
Team Name: Lilmix<br />
Roster: bq, dex, eraa, quix, SHiNE<br />
Global Rank: [116](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [82]( ../standings_europe.md)<br />
<br />
Final Rank Value:  827.1<br />
<br />
Final Rank Value (827.1) = Starting Rank Value (868.5) + Head To Head Adjustments (-41.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.378[<sup>1</sup>](#table2)
- Bounty Collected: 0.255[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.266[<sup>2</sup>](#table1)

The average of these factors is 0.228<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 868.5
- 400 + ( ( 0.228 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 868.5


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
|           11 |       11 | 2024-08-06 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -15.45 | bq, dex, eraa, quix, SHiNE  |
|           10 |      261 | 2024-07-30 | INFINITE        | L   | 1.000      | -            | -                | -                | -         |   -25.18 | bq, dex, L00m1, quix, SHiNE |
|            9 |      447 | 2024-07-24 | ALTERNATE aTTaX | L   | 1.000      | -            | -                | -                | -         |   -16.74 | bq, dex, L00m1, quix, SHiNE |
|            8 |      678 | 2024-07-18 | kONO            | W   | 1.000      | 0.143        | 0.028 (0.004)    | 0.553 (0.079)    | 0 (0.000) |    13.46 | bq, dex, L00m1, quix, SHiNE |
|            7 |     1080 | 2024-06-15 | Johnny Speeds   | L   | 0.853      | -            | -                | -                | -         |    -2.91 | bq, dex, poiii, quix, zyyx  |
|            6 |     1103 | 2024-06-14 | Young Gods      | W   | 0.848      | 0.377        | 0.007 (0.002)    | 0.032 (0.010)    | 1 (0.848) |     7.97 | bq, dex, poiii, quix, zyyx  |
|            5 |     1122 | 2024-06-14 | Johnny Speeds   | L   | 0.846      | -            | -                | -                | -         |    -2.85 | bq, dex, poiii, quix, zyyx  |
|            4 |     1154 | 2024-06-13 | Young Gods      | W   | 0.840      | 0.377        | 0.007 (0.002)    | 0.032 (0.010)    | 1 (0.840) |     8.07 | bq, dex, poiii, quix, zyyx  |
|            3 |     1289 | 2024-06-09 | Alliance        | L   | 0.813      | -            | -                | -                | -         |   -13.29 | bq, dex, poiii, quix, zyyx  |
|            2 |     2265 | 2024-05-11 | Johnny Speeds   | L   | 0.621      | -            | -                | -                | -         |    -1.73 | bq, dex, poiii, quix, zyyx  |
|            1 |     2274 | 2024-05-11 | AURA            | W   | 0.620      | 0.319        | 0.017 (0.003)    | 0.057 (0.011)    | 1 (0.620) |     7.24 | bq, dex, poiii, quix, zyyx  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,279.80)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-15 |      0.853 | $5,808.00      | $4,955.89       |
| 2024-06-09 |      0.814 | $1,445.00      | $1,175.53       |
| 2024-05-11 |      0.621 | $1,850.00      | $1,148.37       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
