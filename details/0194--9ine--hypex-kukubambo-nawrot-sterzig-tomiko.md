### Roster Details<br />
Team Name: 9INE<br />
Roster: hypex, KukuBambo, nawrot, Sterzig, tomiko<br />
Global Rank: [194](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [122]( ../standings_europe.md)<br />
<br />
Final Rank Value:  551.6<br />
<br />
Final Rank Value (551.6) = Starting Rank Value (525.8) + Head To Head Adjustments (25.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.061<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 525.8
- 400 + ( ( 0.061 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 525.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     1057 | 2024-06-15 | FAVBET        | L   | 0.855      | -            | -                | -                | -         |    -4.57 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|           11 |     1094 | 2024-06-14 | EYEBALLERS    | L   | 0.849      | -            | -                | -                | -         |    -3.58 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|           10 |     1129 | 2024-06-13 | Permitta      | W   | 0.842      | 0.143        | 0.023 (0.003)    | 0.940 (0.113)    | 0 (0.000) |    23.80 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|            9 |     1165 | 2024-06-12 | Zero Tenacity | L   | 0.835      | -            | -                | -                | -         |    -1.09 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|            8 |     1184 | 2024-06-11 | Verdant       | W   | 0.829      | 0.143        | 0.015 (0.002)    | 0.294 (0.035)    | 0 (0.000) |    23.25 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|            7 |     2124 | 2024-05-15 | EYEBALLERS    | L   | 0.648      | -            | -                | -                | -         |    -2.32 | hypex, KukuBambo, Sterzig, tomiko, zEden  |
|            6 |     2707 | 2024-04-20 | System5       | L   | 0.481      | -            | -                | -                | -         |    -4.58 | hypex, KukuBambo, Sterzig, tomiko, zEden  |
|            5 |     3226 | 2024-04-03 | KOI           | L   | 0.369      | -            | -                | -                | -         |    -0.51 | hypex, KukuBambo, Sterzig, tomiko, zEden  |
|            4 |     3238 | 2024-04-03 | 9 Pandas      | L   | 0.367      | -            | -                | -                | -         |    -0.73 | hypex, KukuBambo, Sterzig, tomiko, zEden  |
|            3 |     3322 | 2024-03-28 | TSM           | L   | 0.329      | -            | -                | -                | -         |    -3.13 | KEi, KukuBambo, mynio, nawrot, tomiko     |
|            2 |     3803 | 2024-03-06 | EYEBALLERS    | L   | 0.182      | -            | -                | -                | -         |    -0.62 | KEi, KukuBambo, mynio, nawrot, tomiko     |
|            1 |     3976 | 2024-02-27 | Sangal        | L   | 0.129      | -            | -                | -                | -         |    -0.11 | KEi, KukuBambo, mynio, nawrot, tomiko     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
