### Roster Details<br />
Team Name: ENCE Athena<br />
Roster: Aida, Emmsan, Mileyyy, miLo, Waldee<br />
Global Rank: [184](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [116]( ../standings_europe.md)<br />
<br />
Final Rank Value:  620.7<br />
<br />
Final Rank Value (620.7) = Starting Rank Value (642.0) + Head To Head Adjustments (-21.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.277[<sup>1</sup>](#table2)
- Bounty Collected: 0.192[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.118<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 642.0
- 400 + ( ( 0.118 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 642.0


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
|           12 |     1191 | 2024-06-08 | Crescent fe       | L   | 0.840      | -            | -                | -                | -         |   -12.02 | Aida, Emmsan, Mileyyy, miLo, Waldee |
|           11 |     2464 | 2024-04-27 | NIP Impact        | L   | 0.560      | -            | -                | -                | -         |    -6.72 | Aida, Emmsan, miLo, Waldee, xia     |
|           10 |     2658 | 2024-04-19 | Astralis W        | W   | 0.508      | 0.331        | 0.001 (0.000)    | 0.022 (0.004)    | 0 (0.000) |     7.49 | Aida, Emmsan, miLo, Waldee, xia     |
|            9 |     3041 | 2024-04-07 | dream catchers fe | L   | 0.429      | -            | -                | -                | -         |    -5.32 | Aida, Emmsan, miLo, Waldee, xia     |
|            8 |     3065 | 2024-04-06 | Imperial fe       | L   | 0.420      | -            | -                | -                | -         |    -1.24 | Aida, Emmsan, miLo, Waldee, xia     |
|            7 |     3114 | 2024-04-04 | BIG EQUIPA        | L   | 0.408      | -            | -                | -                | -         |    -4.18 | Aida, Emmsan, miLo, Waldee, xia     |
|            6 |     3295 | 2024-03-27 | Imperial fe       | L   | 0.355      | -            | -                | -                | -         |    -1.08 | Aida, Emmsan, miLo, Waldee, xia     |
|            5 |     3415 | 2024-03-20 | NIP Impact        | L   | 0.308      | -            | -                | -                | -         |    -4.13 | Aida, Emmsan, miLo, Waldee, xia     |
|            4 |     3573 | 2024-03-13 | ex-GUILD fe       | W   | 0.262      | 0.331        | 0.003 (0.000)    | 0.066 (0.006)    | 0 (0.000) |     4.32 | Aida, Emmsan, miLo, Waldee, xia     |
|            3 |     3982 | 2024-02-25 | NAVI Javelins     | L   | 0.146      | -            | -                | -                | -         |    -1.22 | Aida, Emmsan, miLo, Waldee, xia     |
|            2 |     4014 | 2024-02-24 | Spirit fe         | W   | 0.140      | 0.238        | 0.005 (0.000)    | 0.101 (0.003)    | 0 (0.000) |     2.33 | Aida, Emmsan, miLo, Waldee, xia     |
|            1 |     4260 | 2024-02-14 | more whiskey      | W   | 0.076      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.49 | Aida, Emmsan, miLo, Waldee, xia     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($798.90)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.842 | $100.00        | $84.15          |
| 2024-04-27 |      0.561 | $107.00        | $60.00          |
| 2024-04-21 |      0.522 | $1,050.00      | $547.60         |
| 2024-04-07 |      0.429 | $250.00        | $107.14         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
