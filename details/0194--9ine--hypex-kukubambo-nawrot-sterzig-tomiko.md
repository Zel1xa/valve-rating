### Roster Details<br />
Team Name: 9INE<br />
Roster: hypex, KukuBambo, nawrot, Sterzig, tomiko<br />
Global Rank: [194](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [122]( ../standings_europe.md)<br />
<br />
Final Rank Value:  551.0<br />
<br />
Final Rank Value (551.0) = Starting Rank Value (525.3) + Head To Head Adjustments (25.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.231[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.061<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 525.3
- 400 + ( ( 0.061 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 525.3


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
|           12 |      993 | 2024-06-15 | FAVBET        | L   | 0.869      | -            | -                | -                | -         |    -4.74 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|           11 |     1030 | 2024-06-14 | EYEBALLERS    | L   | 0.862      | -            | -                | -                | -         |    -3.68 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|           10 |     1065 | 2024-06-13 | Permitta      | W   | 0.856      | 0.143        | 0.024 (0.003)    | 0.876 (0.107)    | 0 (0.000) |    24.07 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|            9 |     1101 | 2024-06-12 | Zero Tenacity | L   | 0.849      | -            | -                | -                | -         |    -1.13 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|            8 |     1120 | 2024-06-11 | Verdant       | W   | 0.842      | 0.143        | 0.015 (0.002)    | 0.299 (0.036)    | 0 (0.000) |    23.57 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|            7 |     2060 | 2024-05-15 | EYEBALLERS    | L   | 0.661      | -            | -                | -                | -         |    -2.38 | hypex, KukuBambo, Sterzig, tomiko, zEden  |
|            6 |     2643 | 2024-04-20 | System5       | L   | 0.494      | -            | -                | -                | -         |    -4.70 | hypex, KukuBambo, Sterzig, tomiko, zEden  |
|            5 |     3162 | 2024-04-03 | KOI           | L   | 0.382      | -            | -                | -                | -         |    -0.52 | hypex, KukuBambo, Sterzig, tomiko, zEden  |
|            4 |     3174 | 2024-04-03 | 9 Pandas      | L   | 0.381      | -            | -                | -                | -         |    -0.74 | hypex, KukuBambo, Sterzig, tomiko, zEden  |
|            3 |     3258 | 2024-03-28 | TSM           | L   | 0.343      | -            | -                | -                | -         |    -3.24 | KEi, KukuBambo, mynio, nawrot, tomiko     |
|            2 |     3739 | 2024-03-06 | EYEBALLERS    | L   | 0.196      | -            | -                | -                | -         |    -0.67 | KEi, KukuBambo, mynio, nawrot, tomiko     |
|            1 |     3912 | 2024-02-27 | Sangal        | L   | 0.142      | -            | -                | -                | -         |    -0.13 | KEi, KukuBambo, mynio, nawrot, tomiko     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
