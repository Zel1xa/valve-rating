### Roster Details<br />
Team Name: ENCE Athena<br />
Roster: Aida, Emmsan, Mileyyy, miLo, Waldee<br />
Global Rank: [186](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [117]( ../standings_europe.md)<br />
<br />
Final Rank Value:  618.1<br />
<br />
Final Rank Value (618.1) = Starting Rank Value (638.8) + Head To Head Adjustments (-20.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.276[<sup>1</sup>](#table2)
- Bounty Collected: 0.190[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.117<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 638.8
- 400 + ( ( 0.117 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 638.8


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
|           12 |     1319 | 2024-06-08 | Crescent fe       | L   | 0.813      | -            | -                | -                | -         |   -11.68 | Aida, Emmsan, Mileyyy, miLo, Waldee |
|           11 |     2535 | 2024-04-27 | NIP Impact        | L   | 0.533      | -            | -                | -                | -         |    -6.36 | Aida, Emmsan, miLo, Waldee, xia     |
|           10 |     2723 | 2024-04-19 | Astralis W        | W   | 0.481      | 0.331        | 0.001 (0.000)    | 0.020 (0.003)    | 0 (0.000) |     7.10 | Aida, Emmsan, miLo, Waldee, xia     |
|            9 |     3102 | 2024-04-07 | dream catchers fe | L   | 0.402      | -            | -                | -                | -         |    -4.93 | Aida, Emmsan, miLo, Waldee, xia     |
|            8 |     3126 | 2024-04-06 | Imperial fe       | L   | 0.393      | -            | -                | -                | -         |    -1.20 | Aida, Emmsan, miLo, Waldee, xia     |
|            7 |     3175 | 2024-04-04 | BIG EQUIPA        | L   | 0.381      | -            | -                | -                | -         |    -3.95 | Aida, Emmsan, miLo, Waldee, xia     |
|            6 |     3347 | 2024-03-27 | Imperial fe       | L   | 0.328      | -            | -                | -                | -         |    -1.03 | Aida, Emmsan, miLo, Waldee, xia     |
|            5 |     3463 | 2024-03-20 | NIP Impact        | L   | 0.282      | -            | -                | -                | -         |    -3.70 | Aida, Emmsan, miLo, Waldee, xia     |
|            4 |     3615 | 2024-03-13 | Astralis W        | W   | 0.235      | 0.331        | 0.002 (0.000)    | 0.063 (0.005)    | 0 (0.000) |     3.88 | Aida, Emmsan, miLo, Waldee, xia     |
|            3 |     4015 | 2024-02-25 | NAVI Javelins     | L   | 0.119      | -            | -                | -                | -         |    -1.01 | Aida, Emmsan, miLo, Waldee, xia     |
|            2 |     4045 | 2024-02-24 | Spirit fe         | W   | 0.113      | 0.238        | 0.005 (0.000)    | 0.140 (0.004)    | 0 (0.000) |     1.92 | Aida, Emmsan, miLo, Waldee, xia     |
|            1 |     4287 | 2024-02-14 | more whiskey      | W   | 0.049      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.32 | Aida, Emmsan, miLo, Waldee, xia     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($758.29)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.815 | $100.00        | $81.46          |
| 2024-04-27 |      0.534 | $107.00        | $57.12          |
| 2024-04-21 |      0.495 | $1,050.00      | $519.31         |
| 2024-04-07 |      0.402 | $250.00        | $100.40         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
