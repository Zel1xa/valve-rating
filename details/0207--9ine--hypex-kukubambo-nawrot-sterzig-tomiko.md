### Roster Details<br />
Team Name: 9INE<br />
Roster: hypex, KukuBambo, nawrot, Sterzig, tomiko<br />
Global Rank: [207](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [129]( ../standings_europe.md)<br />
<br />
Final Rank Value:  535.2<br />
<br />
Final Rank Value (535.2) = Starting Rank Value (515.0) + Head To Head Adjustments (20.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.059<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 515.0
- 400 + ( ( 0.059 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 515.0


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
|           10 |     2192 | 2024-06-15 | FAVBET        | L   | 0.634      | -            | -                | -                | -         |    -3.26 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|            9 |     2229 | 2024-06-14 | EYEBALLERS    | L   | 0.628      | -            | -                | -                | -         |    -3.23 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|            8 |     2264 | 2024-06-13 | Permitta      | W   | 0.621      | 0.143        | 0.032 (0.003)    | 0.968 (0.086)    | 0 (0.000) |    17.56 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|            7 |     2300 | 2024-06-12 | Zero Tenacity | L   | 0.614      | -            | -                | -                | -         |    -0.89 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|            6 |     2319 | 2024-06-11 | Verdant       | W   | 0.608      | 0.143        | 0.011 (0.001)    | 0.353 (0.031)    | 0 (0.000) |    16.65 | hypex, KukuBambo, nawrot, Sterzig, tomiko |
|            5 |     3259 | 2024-05-15 | EYEBALLERS    | L   | 0.427      | -            | -                | -                | -         |    -2.16 | hypex, KukuBambo, Sterzig, tomiko, zEden  |
|            4 |     3842 | 2024-04-20 | System5       | L   | 0.260      | -            | -                | -                | -         |    -2.72 | hypex, KukuBambo, Sterzig, tomiko, zEden  |
|            3 |     4361 | 2024-04-03 | KOI           | L   | 0.148      | -            | -                | -                | -         |    -0.37 | hypex, KukuBambo, Sterzig, tomiko, zEden  |
|            2 |     4373 | 2024-04-03 | 9 Pandas      | L   | 0.147      | -            | -                | -                | -         |    -0.24 | hypex, KukuBambo, Sterzig, tomiko, zEden  |
|            1 |     4457 | 2024-03-28 | TSM           | L   | 0.108      | -            | -                | -                | -         |    -1.17 | KEi, KukuBambo, mynio, nawrot, tomiko     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
