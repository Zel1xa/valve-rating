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
Final Rank Value (618.4) = Starting Rank Value (639.0) + Head To Head Adjustments (-20.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.276[<sup>1</sup>](#table2)
- Bounty Collected: 0.190[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.117<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 639.0
- 400 + ( ( 0.117 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 639.0


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
|           12 |     1327 | 2024-06-08 | Crescent fe       | L   | 0.812      | -            | -                | -                | -         |   -11.66 | Aida, Emmsan, Mileyyy, miLo, Waldee |
|           11 |     2543 | 2024-04-27 | NIP Impact        | L   | 0.532      | -            | -                | -                | -         |    -6.35 | Aida, Emmsan, miLo, Waldee, xia     |
|           10 |     2731 | 2024-04-19 | Astralis W        | W   | 0.480      | 0.331        | 0.001 (0.000)    | 0.020 (0.003)    | 0 (0.000) |     7.08 | Aida, Emmsan, miLo, Waldee, xia     |
|            9 |     3110 | 2024-04-07 | dream catchers fe | L   | 0.400      | -            | -                | -                | -         |    -4.92 | Aida, Emmsan, miLo, Waldee, xia     |
|            8 |     3134 | 2024-04-06 | Imperial fe       | L   | 0.392      | -            | -                | -                | -         |    -1.19 | Aida, Emmsan, miLo, Waldee, xia     |
|            7 |     3183 | 2024-04-04 | BIG EQUIPA        | L   | 0.380      | -            | -                | -                | -         |    -3.94 | Aida, Emmsan, miLo, Waldee, xia     |
|            6 |     3355 | 2024-03-27 | Imperial fe       | L   | 0.327      | -            | -                | -                | -         |    -1.03 | Aida, Emmsan, miLo, Waldee, xia     |
|            5 |     3471 | 2024-03-20 | NIP Impact        | L   | 0.280      | -            | -                | -                | -         |    -3.68 | Aida, Emmsan, miLo, Waldee, xia     |
|            4 |     3623 | 2024-03-13 | Astralis W        | W   | 0.234      | 0.331        | 0.002 (0.000)    | 0.062 (0.005)    | 0 (0.000) |     3.86 | Aida, Emmsan, miLo, Waldee, xia     |
|            3 |     4023 | 2024-02-25 | NAVI Javelins     | L   | 0.118      | -            | -                | -                | -         |    -1.00 | Aida, Emmsan, miLo, Waldee, xia     |
|            2 |     4053 | 2024-02-24 | Spirit fe         | W   | 0.112      | 0.238        | 0.005 (0.000)    | 0.139 (0.004)    | 0 (0.000) |     1.90 | Aida, Emmsan, miLo, Waldee, xia     |
|            1 |     4295 | 2024-02-14 | more whiskey      | W   | 0.048      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.31 | Aida, Emmsan, miLo, Waldee, xia     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($756.62)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.813 | $100.00        | $81.35          |
| 2024-04-27 |      0.533 | $107.00        | $57.00          |
| 2024-04-21 |      0.493 | $1,050.00      | $518.15         |
| 2024-04-07 |      0.400 | $250.00        | $100.12         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
