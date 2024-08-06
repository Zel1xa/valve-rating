### Roster Details<br />
Team Name: ENCE Athena<br />
Roster: Aida, Emmsan, Mileyyy, miLo, Waldee<br />
Global Rank: [186](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [117]( ../standings_europe.md)<br />
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
|           12 |     1348 | 2024-06-08 | Crescent fe       | L   | 0.806      | -            | -                | -                | -         |   -11.57 | Aida, Emmsan, Mileyyy, miLo, Waldee |
|           11 |     2564 | 2024-04-27 | NIP Impact        | L   | 0.526      | -            | -                | -                | -         |    -6.28 | Aida, Emmsan, miLo, Waldee, xia     |
|           10 |     2752 | 2024-04-19 | Astralis W        | W   | 0.474      | 0.331        | 0.001 (0.000)    | 0.019 (0.003)    | 0 (0.000) |     6.99 | Aida, Emmsan, miLo, Waldee, xia     |
|            9 |     3131 | 2024-04-07 | dream catchers fe | L   | 0.394      | -            | -                | -                | -         |    -4.83 | Aida, Emmsan, miLo, Waldee, xia     |
|            8 |     3155 | 2024-04-06 | Imperial fe       | L   | 0.386      | -            | -                | -                | -         |    -1.17 | Aida, Emmsan, miLo, Waldee, xia     |
|            7 |     3204 | 2024-04-04 | BIG EQUIPA        | L   | 0.374      | -            | -                | -                | -         |    -3.88 | Aida, Emmsan, miLo, Waldee, xia     |
|            6 |     3376 | 2024-03-27 | Imperial fe       | L   | 0.321      | -            | -                | -                | -         |    -1.01 | Aida, Emmsan, miLo, Waldee, xia     |
|            5 |     3492 | 2024-03-20 | NIP Impact        | L   | 0.274      | -            | -                | -                | -         |    -3.60 | Aida, Emmsan, miLo, Waldee, xia     |
|            4 |     3644 | 2024-03-13 | Astralis W        | W   | 0.228      | 0.331        | 0.002 (0.000)    | 0.060 (0.004)    | 0 (0.000) |     3.76 | Aida, Emmsan, miLo, Waldee, xia     |
|            3 |     4044 | 2024-02-25 | NAVI Javelins     | L   | 0.112      | -            | -                | -                | -         |    -0.95 | Aida, Emmsan, miLo, Waldee, xia     |
|            2 |     4074 | 2024-02-24 | Spirit fe         | W   | 0.106      | 0.238        | 0.005 (0.000)    | 0.136 (0.003)    | 0 (0.000) |     1.79 | Aida, Emmsan, miLo, Waldee, xia     |
|            1 |     4316 | 2024-02-14 | more whiskey      | W   | 0.042      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.27 | Aida, Emmsan, miLo, Waldee, xia     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($747.41)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.807 | $100.00        | $80.74          |
| 2024-04-27 |      0.527 | $107.00        | $56.35          |
| 2024-04-21 |      0.487 | $1,050.00      | $511.73         |
| 2024-04-07 |      0.394 | $250.00        | $98.59          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
