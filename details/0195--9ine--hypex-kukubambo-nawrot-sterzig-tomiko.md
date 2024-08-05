### Roster Details<br />
Team Name: 9INE<br />
Roster: hypex, KukuBambo, nawrot, Sterzig, tomiko<br />
Global Rank: [195](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [123]( ../standings_europe.md)<br />
<br />
Final Rank Value:  550.9<br />
<br />
Final Rank Value (550.9) = Starting Rank Value (525.3) + Head To Head Adjustments (25.6)<br />

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
- 400 + ( ( 0.061 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 525.3


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
|           12 |     1042 | 2024-06-15 | FAVBET        | L   | 0.861      | -            | -                | -                | -         |    -4.66 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|           11 |     1079 | 2024-06-14 | EYEBALLERS    | L   | 0.854      | -            | -                | -                | -         |    -3.67 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|           10 |     1114 | 2024-06-13 | Permitta      | W   | 0.848      | 0.143        | 0.024 (0.003)    | 0.873 (0.106)    | 0 (0.000) |    23.89 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|            9 |     1150 | 2024-06-12 | Zero Tenacity | L   | 0.841      | -            | -                | -                | -         |    -1.11 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|            8 |     1169 | 2024-06-11 | Verdant       | W   | 0.834      | 0.143        | 0.015 (0.002)    | 0.298 (0.036)    | 0 (0.000) |    23.39 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|            7 |     2109 | 2024-05-15 | EYEBALLERS    | L   | 0.653      | -            | -                | -                | -         |    -2.41 | hypex, KukuBambo, Sterzig, tomiko, zEden  |
|            6 |     2692 | 2024-04-20 | System5       | L   | 0.487      | -            | -                | -                | -         |    -4.63 | hypex, KukuBambo, Sterzig, tomiko, zEden  |
|            5 |     3211 | 2024-04-03 | KOI           | L   | 0.375      | -            | -                | -                | -         |    -0.51 | hypex, KukuBambo, Sterzig, tomiko, zEden  |
|            4 |     3223 | 2024-04-03 | 9 Pandas      | L   | 0.373      | -            | -                | -                | -         |    -0.73 | hypex, KukuBambo, Sterzig, tomiko, zEden  |
|            3 |     3307 | 2024-03-28 | TSM           | L   | 0.335      | -            | -                | -                | -         |    -3.17 | KEi, KukuBambo, mynio, nawrot, tomiko     |
|            2 |     3788 | 2024-03-06 | EYEBALLERS    | L   | 0.188      | -            | -                | -                | -         |    -0.64 | KEi, KukuBambo, mynio, nawrot, tomiko     |
|            1 |     3961 | 2024-02-27 | Sangal        | L   | 0.135      | -            | -                | -                | -         |    -0.12 | KEi, KukuBambo, mynio, nawrot, tomiko     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
