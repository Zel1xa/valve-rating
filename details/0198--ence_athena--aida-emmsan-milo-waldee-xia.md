### Roster Details<br />
Team Name: ENCE Athena<br />
Roster: Aida, Emmsan, miLo, Waldee, xia<br />
Global Rank: [198](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [125]( ../standings_europe.md)<br />
<br />
Final Rank Value:  584.2<br />
<br />
Final Rank Value (584.2) = Starting Rank Value (612.1) + Head To Head Adjustments (-27.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.259[<sup>1</sup>](#table2)
- Bounty Collected: 0.179[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.110<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 612.1
- 400 + ( ( 0.110 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 612.1


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
|           12 |      311 | 2024-08-28 | NIP Impact        | L   | 1.000      | -            | -                | -                | -         |   -11.11 | Aida, Emmsan, miLo, Waldee, xia     |
|           11 |      952 | 2024-08-11 | OneDay fe         | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    11.94 | Aida, Emmsan, miLo, Waldee, xia     |
|           10 |     1115 | 2024-08-06 | Crescent fe       | L   | 0.981      | -            | -                | -                | -         |   -13.50 | Aida, Emmsan, miLo, Waldee, xia     |
|            9 |     2469 | 2024-06-08 | Crescent fe       | L   | 0.587      | -            | -                | -                | -         |    -8.50 | Aida, Emmsan, Mileyyy, miLo, Waldee |
|            8 |     3685 | 2024-04-27 | NIP Impact        | L   | 0.307      | -            | -                | -                | -         |    -3.95 | Aida, Emmsan, miLo, Waldee, xia     |
|            7 |     3873 | 2024-04-19 | Astralis W        | W   | 0.255      | 0.331        | 0.001 (0.000)    | 0.008 (0.001)    | 0 (0.000) |     3.01 | Aida, Emmsan, miLo, Waldee, xia     |
|            6 |     4252 | 2024-04-07 | dream catchers fe | L   | 0.175      | -            | -                | -                | -         |    -2.06 | Aida, Emmsan, miLo, Waldee, xia     |
|            5 |     4276 | 2024-04-06 | Imperial fe       | L   | 0.166      | -            | -                | -                | -         |    -0.84 | Aida, Emmsan, miLo, Waldee, xia     |
|            4 |     4325 | 2024-04-04 | BIG EQUIPA        | L   | 0.155      | -            | -                | -                | -         |    -1.77 | Aida, Emmsan, miLo, Waldee, xia     |
|            3 |     4497 | 2024-03-27 | Imperial fe       | L   | 0.102      | -            | -                | -                | -         |    -0.52 | Aida, Emmsan, miLo, Waldee, xia     |
|            2 |     4613 | 2024-03-20 | NIP Impact        | L   | 0.055      | -            | -                | -                | -         |    -0.72 | Aida, Emmsan, miLo, Waldee, xia     |
|            1 |     4765 | 2024-03-13 | Astralis W        | W   | 0.008      | 0.331        | 0.001 (0.000)    | 0.024 (0.000)    | 0 (0.000) |     0.13 | Aida, Emmsan, miLo, Waldee, xia     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($416.70)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.588 | $100.00        | $58.79          |
| 2024-04-27 |      0.307 | $107.00        | $32.87          |
| 2024-04-21 |      0.268 | $1,050.00      | $281.31         |
| 2024-04-07 |      0.175 | $250.00        | $43.73          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
