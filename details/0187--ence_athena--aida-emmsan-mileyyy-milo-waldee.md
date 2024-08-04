### Roster Details<br />
Team Name: ENCE Athena<br />
Roster: Aida, Emmsan, Mileyyy, miLo, Waldee<br />
Global Rank: [187](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [118]( ../standings_europe.md)<br />
<br />
Final Rank Value:  618.1<br />
<br />
Final Rank Value (618.1) = Starting Rank Value (638.9) + Head To Head Adjustments (-20.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.276[<sup>1</sup>](#table2)
- Bounty Collected: 0.190[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.117<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 638.9
- 400 + ( ( 0.117 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 638.9


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
|           12 |     1301 | 2024-06-08 | Crescent fe       | L   | 0.819      | -            | -                | -                | -         |   -11.77 | Aida, Emmsan, Mileyyy, miLo, Waldee |
|           11 |     2517 | 2024-04-27 | NIP Impact        | L   | 0.539      | -            | -                | -                | -         |    -6.42 | Aida, Emmsan, miLo, Waldee, xia     |
|           10 |     2705 | 2024-04-19 | Astralis W        | W   | 0.487      | 0.331        | 0.001 (0.000)    | 0.021 (0.003)    | 0 (0.000) |     7.19 | Aida, Emmsan, miLo, Waldee, xia     |
|            9 |     3084 | 2024-04-07 | dream catchers fe | L   | 0.408      | -            | -                | -                | -         |    -5.02 | Aida, Emmsan, miLo, Waldee, xia     |
|            8 |     3108 | 2024-04-06 | Imperial fe       | L   | 0.399      | -            | -                | -                | -         |    -1.21 | Aida, Emmsan, miLo, Waldee, xia     |
|            7 |     3157 | 2024-04-04 | BIG EQUIPA        | L   | 0.387      | -            | -                | -                | -         |    -4.01 | Aida, Emmsan, miLo, Waldee, xia     |
|            6 |     3329 | 2024-03-27 | Imperial fe       | L   | 0.334      | -            | -                | -                | -         |    -1.05 | Aida, Emmsan, miLo, Waldee, xia     |
|            5 |     3445 | 2024-03-20 | NIP Impact        | L   | 0.288      | -            | -                | -                | -         |    -3.78 | Aida, Emmsan, miLo, Waldee, xia     |
|            4 |     3597 | 2024-03-13 | Astralis W        | W   | 0.241      | 0.331        | 0.002 (0.000)    | 0.064 (0.005)    | 0 (0.000) |     3.98 | Aida, Emmsan, miLo, Waldee, xia     |
|            3 |     3997 | 2024-02-25 | NAVI Javelins     | L   | 0.125      | -            | -                | -                | -         |    -1.07 | Aida, Emmsan, miLo, Waldee, xia     |
|            2 |     4027 | 2024-02-24 | Spirit fe         | W   | 0.119      | 0.238        | 0.005 (0.000)    | 0.141 (0.004)    | 0 (0.000) |     2.01 | Aida, Emmsan, miLo, Waldee, xia     |
|            1 |     4269 | 2024-02-14 | more whiskey      | W   | 0.055      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.36 | Aida, Emmsan, miLo, Waldee, xia     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($767.36)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.821 | $100.00        | $82.06          |
| 2024-04-27 |      0.540 | $107.00        | $57.77          |
| 2024-04-21 |      0.501 | $1,050.00      | $525.63         |
| 2024-04-07 |      0.408 | $250.00        | $101.90         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
