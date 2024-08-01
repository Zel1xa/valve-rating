### Roster Details<br />
Team Name: Fraud5<br />
Roster: cryths, Rezst, shyyne, Tree60, yz0<br />
Global Rank: [178](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [113]( ../standings_europe.md)<br />
<br />
Final Rank Value:  647.7<br />
<br />
Final Rank Value (647.7) = Starting Rank Value (652.6) + Head To Head Adjustments (-4.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.295[<sup>1</sup>](#table2)
- Bounty Collected: 0.178[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.016[<sup>2</sup>](#table1)

The average of these factors is 0.123<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 652.6
- 400 + ( ( 0.123 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 652.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     1059 | 2024-06-10 | K10            | L   | 0.855      | -            | -                | -                | -         |   -11.39 | cryths, Rezst, shyyne, Tree60, yz0    |
|           10 |     1363 | 2024-06-05 | RAPTORS EC     | W   | 0.822      | 0.282        | 0.000 (0.000)    | 0.035 (0.008)    | 0 (0.000) |    10.92 | cryths, Rezst, shyyne, Tree60, yz0    |
|            9 |     3240 | 2024-03-29 | The Neighbours | L   | 0.369      | -            | -                | -                | -         |    -4.92 | Kisynergy, Rezst, shyyne, Tree60, yz0 |
|            8 |     3428 | 2024-03-19 | RAPTORS EC     | W   | 0.302      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     2.69 | Kisynergy, Rezst, shyyne, Tree60, yz0 |
|            7 |     3675 | 2024-03-09 | Insilio        | L   | 0.234      | -            | -                | -                | -         |    -1.49 | Rezst, shyyne, SLY, Tree60, yz0       |
|            6 |     3689 | 2024-03-09 | ex-Preasy      | L   | 0.233      | -            | -                | -                | -         |    -2.18 | Rezst, shyyne, SLY, Tree60, yz0       |
|            5 |     3699 | 2024-03-08 | MOUZ NXT       | L   | 0.228      | -            | -                | -                | -         |    -0.67 | Rezst, shyyne, SLY, Tree60, yz0       |
|            4 |     3761 | 2024-03-06 | Passion UA     | L   | 0.213      | -            | -                | -                | -         |    -0.52 | Rezst, shyyne, SLY, Tree60, yz0       |
|            3 |     3818 | 2024-03-04 | Secret         | W   | 0.201      | 0.371        | 0.000 (0.000)    | 0.060 (0.004)    | 0 (0.000) |     2.21 | Rezst, shyyne, SLY, Tree60, yz0       |
|            2 |     3978 | 2024-02-25 | The Neighbours | L   | 0.147      | -            | -                | -                | -         |    -2.07 | Rezst, shyyne, SLY, Tree60, yz0       |
|            1 |     4006 | 2024-02-24 | The Neighbours | W   | 0.141      | 0.307        | 0.003 (0.000)    | 0.036 (0.002)    | 1 (0.141) |     2.48 | Rezst, shyyne, SLY, Tree60, yz0       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,342.71)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.855 | $954.00        | $815.67         |
| 2024-03-29 |      0.369 | $951.00        | $350.81         |
| 2024-02-25 |      0.147 | $1,197.00      | $176.23         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
