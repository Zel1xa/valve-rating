### Roster Details<br />
Team Name: 9INE<br />
Roster: hypex, KukuBambo, nawrot, Sterzig, tomiko<br />
Global Rank: [194](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [122]( ../standings_europe.md)<br />
<br />
Final Rank Value:  551.1<br />
<br />
Final Rank Value (551.1) = Starting Rank Value (525.4) + Head To Head Adjustments (25.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.231[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.061<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 525.4
- 400 + ( ( 0.061 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 525.4


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
|           12 |      989 | 2024-06-15 | FAVBET        | L   | 0.872      | -            | -                | -                | -         |    -4.75 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|           11 |     1026 | 2024-06-14 | EYEBALLERS    | L   | 0.865      | -            | -                | -                | -         |    -3.69 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|           10 |     1061 | 2024-06-13 | Permitta      | W   | 0.859      | 0.143        | 0.024 (0.003)    | 0.876 (0.107)    | 0 (0.000) |    24.15 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|            9 |     1097 | 2024-06-12 | Zero Tenacity | L   | 0.852      | -            | -                | -                | -         |    -1.14 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|            8 |     1116 | 2024-06-11 | Verdant       | W   | 0.845      | 0.143        | 0.015 (0.002)    | 0.299 (0.036)    | 0 (0.000) |    23.65 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|            7 |     2056 | 2024-05-15 | EYEBALLERS    | L   | 0.664      | -            | -                | -                | -         |    -2.39 | hypex, KukuBambo, Sterzig, tomiko, zEden  |
|            6 |     2638 | 2024-04-20 | System5       | L   | 0.497      | -            | -                | -                | -         |    -4.73 | hypex, KukuBambo, Sterzig, tomiko, zEden  |
|            5 |     3157 | 2024-04-03 | KOI           | L   | 0.385      | -            | -                | -                | -         |    -0.52 | hypex, KukuBambo, Sterzig, tomiko, zEden  |
|            4 |     3169 | 2024-04-03 | 9 Pandas      | L   | 0.384      | -            | -                | -                | -         |    -0.74 | hypex, KukuBambo, Sterzig, tomiko, zEden  |
|            3 |     3253 | 2024-03-28 | TSM           | L   | 0.346      | -            | -                | -                | -         |    -3.27 | KEi, KukuBambo, mynio, nawrot, tomiko     |
|            2 |     3733 | 2024-03-06 | EYEBALLERS    | L   | 0.199      | -            | -                | -                | -         |    -0.68 | KEi, KukuBambo, mynio, nawrot, tomiko     |
|            1 |     3906 | 2024-02-27 | Sangal        | L   | 0.146      | -            | -                | -                | -         |    -0.13 | KEi, KukuBambo, mynio, nawrot, tomiko     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
