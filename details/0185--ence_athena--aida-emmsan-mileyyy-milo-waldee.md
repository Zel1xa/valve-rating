### Roster Details<br />
Team Name: ENCE Athena<br />
Roster: Aida, Emmsan, Mileyyy, miLo, Waldee<br />
Global Rank: [185](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [116]( ../standings_europe.md)<br />
<br />
Final Rank Value:  618.9<br />
<br />
Final Rank Value (618.9) = Starting Rank Value (639.4) + Head To Head Adjustments (-20.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.189[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.116<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 639.4
- 400 + ( ( 0.116 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 639.4


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
|           12 |     1338 | 2024-06-08 | Crescent fe       | L   | 0.807      | -            | -                | -                | -         |   -11.59 | Aida, Emmsan, Mileyyy, miLo, Waldee |
|           11 |     2554 | 2024-04-27 | NIP Impact        | L   | 0.527      | -            | -                | -                | -         |    -6.29 | Aida, Emmsan, miLo, Waldee, xia     |
|           10 |     2742 | 2024-04-19 | Astralis W        | W   | 0.475      | 0.331        | 0.001 (0.000)    | 0.019 (0.003)    | 0 (0.000) |     7.01 | Aida, Emmsan, miLo, Waldee, xia     |
|            9 |     3121 | 2024-04-07 | dream catchers fe | L   | 0.395      | -            | -                | -                | -         |    -4.84 | Aida, Emmsan, miLo, Waldee, xia     |
|            8 |     3145 | 2024-04-06 | Imperial fe       | L   | 0.387      | -            | -                | -                | -         |    -1.18 | Aida, Emmsan, miLo, Waldee, xia     |
|            7 |     3194 | 2024-04-04 | BIG EQUIPA        | L   | 0.375      | -            | -                | -                | -         |    -3.89 | Aida, Emmsan, miLo, Waldee, xia     |
|            6 |     3366 | 2024-03-27 | Imperial fe       | L   | 0.322      | -            | -                | -                | -         |    -1.01 | Aida, Emmsan, miLo, Waldee, xia     |
|            5 |     3482 | 2024-03-20 | NIP Impact        | L   | 0.275      | -            | -                | -                | -         |    -3.62 | Aida, Emmsan, miLo, Waldee, xia     |
|            4 |     3634 | 2024-03-13 | Astralis W        | W   | 0.229      | 0.331        | 0.002 (0.000)    | 0.060 (0.005)    | 0 (0.000) |     3.78 | Aida, Emmsan, miLo, Waldee, xia     |
|            3 |     4034 | 2024-02-25 | NAVI Javelins     | L   | 0.113      | -            | -                | -                | -         |    -0.96 | Aida, Emmsan, miLo, Waldee, xia     |
|            2 |     4064 | 2024-02-24 | Spirit fe         | W   | 0.107      | 0.238        | 0.005 (0.000)    | 0.136 (0.003)    | 0 (0.000) |     1.81 | Aida, Emmsan, miLo, Waldee, xia     |
|            1 |     4306 | 2024-02-14 | more whiskey      | W   | 0.043      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.28 | Aida, Emmsan, miLo, Waldee, xia     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($749.08)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.808 | $100.00        | $80.85          |
| 2024-04-27 |      0.528 | $107.00        | $56.47          |
| 2024-04-21 |      0.488 | $1,050.00      | $512.90         |
| 2024-04-07 |      0.395 | $250.00        | $98.87          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
