### Roster Details<br />
Team Name: ENCE Athena<br />
Roster: Aida, Emmsan, Mileyyy, miLo, Waldee<br />
Global Rank: [186](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [117]( ../standings_europe.md)<br />
<br />
Final Rank Value:  618.4<br />
<br />
Final Rank Value (618.4) = Starting Rank Value (638.9) + Head To Head Adjustments (-20.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.189[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.116<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 638.9
- 400 + ( ( 0.116 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 638.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     1334 | 2024-06-08 | Crescent fe       | L   | 0.807      | -            | -                | -                | -         |   -11.59 | Aida, Emmsan, Mileyyy, miLo, Waldee |
|           11 |     2550 | 2024-04-27 | NIP Impact        | L   | 0.528      | -            | -                | -                | -         |    -6.30 | Aida, Emmsan, miLo, Waldee, xia     |
|           10 |     2738 | 2024-04-19 | Astralis W        | W   | 0.475      | 0.331        | 0.001 (0.000)    | 0.020 (0.003)    | 0 (0.000) |     7.01 | Aida, Emmsan, miLo, Waldee, xia     |
|            9 |     3117 | 2024-04-07 | dream catchers fe | L   | 0.396      | -            | -                | -                | -         |    -4.85 | Aida, Emmsan, miLo, Waldee, xia     |
|            8 |     3141 | 2024-04-06 | Imperial fe       | L   | 0.387      | -            | -                | -                | -         |    -1.18 | Aida, Emmsan, miLo, Waldee, xia     |
|            7 |     3190 | 2024-04-04 | BIG EQUIPA        | L   | 0.375      | -            | -                | -                | -         |    -3.89 | Aida, Emmsan, miLo, Waldee, xia     |
|            6 |     3362 | 2024-03-27 | Imperial fe       | L   | 0.322      | -            | -                | -                | -         |    -1.01 | Aida, Emmsan, miLo, Waldee, xia     |
|            5 |     3478 | 2024-03-20 | NIP Impact        | L   | 0.276      | -            | -                | -                | -         |    -3.62 | Aida, Emmsan, miLo, Waldee, xia     |
|            4 |     3630 | 2024-03-13 | Astralis W        | W   | 0.229      | 0.331        | 0.002 (0.000)    | 0.061 (0.005)    | 0 (0.000) |     3.79 | Aida, Emmsan, miLo, Waldee, xia     |
|            3 |     4030 | 2024-02-25 | NAVI Javelins     | L   | 0.114      | -            | -                | -                | -         |    -0.97 | Aida, Emmsan, miLo, Waldee, xia     |
|            2 |     4060 | 2024-02-24 | Spirit fe         | W   | 0.108      | 0.238        | 0.005 (0.000)    | 0.139 (0.004)    | 0 (0.000) |     1.82 | Aida, Emmsan, miLo, Waldee, xia     |
|            1 |     4302 | 2024-02-14 | more whiskey      | W   | 0.043      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.28 | Aida, Emmsan, miLo, Waldee, xia     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($749.50)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.809 | $100.00        | $80.88          |
| 2024-04-27 |      0.528 | $107.00        | $56.50          |
| 2024-04-21 |      0.489 | $1,050.00      | $513.19         |
| 2024-04-07 |      0.396 | $250.00        | $98.94          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />