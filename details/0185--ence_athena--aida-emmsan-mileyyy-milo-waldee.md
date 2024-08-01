### Roster Details<br />
Team Name: ENCE Athena<br />
Roster: Aida, Emmsan, Mileyyy, miLo, Waldee<br />
Global Rank: [185](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [117]( ../standings_europe.md)<br />
<br />
Final Rank Value:  620.4<br />
<br />
Final Rank Value (620.4) = Starting Rank Value (641.7) + Head To Head Adjustments (-21.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.277[<sup>1</sup>](#table2)
- Bounty Collected: 0.192[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.117<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 641.7
- 400 + ( ( 0.117 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 641.7


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
|           12 |     1197 | 2024-06-08 | Crescent fe       | L   | 0.839      | -            | -                | -                | -         |   -12.00 | Aida, Emmsan, Mileyyy, miLo, Waldee |
|           11 |     2470 | 2024-04-27 | NIP Impact        | L   | 0.559      | -            | -                | -                | -         |    -6.71 | Aida, Emmsan, miLo, Waldee, xia     |
|           10 |     2664 | 2024-04-19 | Astralis W        | W   | 0.507      | 0.331        | 0.001 (0.000)    | 0.022 (0.004)    | 0 (0.000) |     7.47 | Aida, Emmsan, miLo, Waldee, xia     |
|            9 |     3047 | 2024-04-07 | dream catchers fe | L   | 0.427      | -            | -                | -                | -         |    -5.29 | Aida, Emmsan, miLo, Waldee, xia     |
|            8 |     3071 | 2024-04-06 | Imperial fe       | L   | 0.418      | -            | -                | -                | -         |    -1.23 | Aida, Emmsan, miLo, Waldee, xia     |
|            7 |     3120 | 2024-04-04 | BIG EQUIPA        | L   | 0.407      | -            | -                | -                | -         |    -4.17 | Aida, Emmsan, miLo, Waldee, xia     |
|            6 |     3301 | 2024-03-27 | Imperial fe       | L   | 0.353      | -            | -                | -                | -         |    -1.08 | Aida, Emmsan, miLo, Waldee, xia     |
|            5 |     3421 | 2024-03-20 | NIP Impact        | L   | 0.307      | -            | -                | -                | -         |    -4.11 | Aida, Emmsan, miLo, Waldee, xia     |
|            4 |     3579 | 2024-03-13 | ex-GUILD fe       | W   | 0.260      | 0.331        | 0.003 (0.000)    | 0.066 (0.006)    | 0 (0.000) |     4.29 | Aida, Emmsan, miLo, Waldee, xia     |
|            3 |     3988 | 2024-02-25 | NAVI Javelins     | L   | 0.145      | -            | -                | -                | -         |    -1.20 | Aida, Emmsan, miLo, Waldee, xia     |
|            2 |     4020 | 2024-02-24 | Spirit fe         | W   | 0.139      | 0.238        | 0.005 (0.000)    | 0.101 (0.003)    | 0 (0.000) |     2.30 | Aida, Emmsan, miLo, Waldee, xia     |
|            1 |     4266 | 2024-02-14 | more whiskey      | W   | 0.074      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.48 | Aida, Emmsan, miLo, Waldee, xia     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($796.38)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.840 | $100.00        | $83.99          |
| 2024-04-27 |      0.559 | $107.00        | $59.83          |
| 2024-04-21 |      0.520 | $1,050.00      | $545.85         |
| 2024-04-07 |      0.427 | $250.00        | $106.72         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
