### Roster Details<br />
Team Name: ENCE Athena<br />
Roster: Aida, Emmsan, Mileyyy, miLo, Waldee<br />
Global Rank: [185](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [117]( ../standings_europe.md)<br />
<br />
Final Rank Value:  618.0<br />
<br />
Final Rank Value (618.0) = Starting Rank Value (639.0) + Head To Head Adjustments (-20.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.276[<sup>1</sup>](#table2)
- Bounty Collected: 0.191[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.117<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 639.0
- 400 + ( ( 0.117 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 639.0


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
|           12 |     1266 | 2024-06-08 | Crescent fe       | L   | 0.824      | -            | -                | -                | -         |   -11.79 | Aida, Emmsan, Mileyyy, miLo, Waldee |
|           11 |     2482 | 2024-04-27 | NIP Impact        | L   | 0.544      | -            | -                | -                | -         |    -6.53 | Aida, Emmsan, miLo, Waldee, xia     |
|           10 |     2669 | 2024-04-19 | Astralis W        | W   | 0.492      | 0.331        | 0.001 (0.000)    | 0.021 (0.003)    | 0 (0.000) |     7.25 | Aida, Emmsan, miLo, Waldee, xia     |
|            9 |     3048 | 2024-04-07 | dream catchers fe | L   | 0.412      | -            | -                | -                | -         |    -5.08 | Aida, Emmsan, miLo, Waldee, xia     |
|            8 |     3072 | 2024-04-06 | Imperial fe       | L   | 0.404      | -            | -                | -                | -         |    -1.22 | Aida, Emmsan, miLo, Waldee, xia     |
|            7 |     3121 | 2024-04-04 | BIG EQUIPA        | L   | 0.392      | -            | -                | -                | -         |    -4.06 | Aida, Emmsan, miLo, Waldee, xia     |
|            6 |     3293 | 2024-03-27 | Imperial fe       | L   | 0.339      | -            | -                | -                | -         |    -1.06 | Aida, Emmsan, miLo, Waldee, xia     |
|            5 |     3409 | 2024-03-20 | NIP Impact        | L   | 0.292      | -            | -                | -                | -         |    -3.88 | Aida, Emmsan, miLo, Waldee, xia     |
|            4 |     3561 | 2024-03-13 | Astralis W        | W   | 0.245      | 0.331        | 0.002 (0.000)    | 0.064 (0.005)    | 0 (0.000) |     4.05 | Aida, Emmsan, miLo, Waldee, xia     |
|            3 |     3960 | 2024-02-25 | NAVI Javelins     | L   | 0.130      | -            | -                | -                | -         |    -1.10 | Aida, Emmsan, miLo, Waldee, xia     |
|            2 |     3990 | 2024-02-24 | Spirit fe         | W   | 0.124      | 0.238        | 0.005 (0.000)    | 0.140 (0.004)    | 0 (0.000) |     2.09 | Aida, Emmsan, miLo, Waldee, xia     |
|            1 |     4231 | 2024-02-14 | more whiskey      | W   | 0.059      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.39 | Aida, Emmsan, miLo, Waldee, xia     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($774.20)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.825 | $100.00        | $82.51          |
| 2024-04-27 |      0.544 | $107.00        | $58.25          |
| 2024-04-21 |      0.505 | $1,050.00      | $530.40         |
| 2024-04-07 |      0.412 | $250.00        | $103.04         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
