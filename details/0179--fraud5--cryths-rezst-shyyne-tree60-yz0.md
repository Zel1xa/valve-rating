### Roster Details<br />
Team Name: Fraud5<br />
Roster: cryths, Rezst, shyyne, Tree60, yz0<br />
Global Rank: [179](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [114]( ../standings_europe.md)<br />
<br />
Final Rank Value:  641.9<br />
<br />
Final Rank Value (641.9) = Starting Rank Value (646.6) + Head To Head Adjustments (-4.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.293[<sup>1</sup>](#table2)
- Bounty Collected: 0.174[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.013[<sup>2</sup>](#table1)

The average of these factors is 0.120<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 646.6
- 400 + ( ( 0.120 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 646.6


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
|           11 |     1188 | 2024-06-10 | K10            | L   | 0.828      | -            | -                | -                | -         |   -10.95 | cryths, Rezst, shyyne, Tree60, yz0    |
|           10 |     1479 | 2024-06-05 | RAPTORS EC     | W   | 0.795      | 0.282        | 0.000 (0.000)    | 0.034 (0.008)    | 0 (0.000) |    10.56 | cryths, Rezst, shyyne, Tree60, yz0    |
|            9 |     3293 | 2024-03-29 | The Neighbours | L   | 0.342      | -            | -                | -                | -         |    -4.63 | Kisynergy, Rezst, shyyne, Tree60, yz0 |
|            8 |     3476 | 2024-03-19 | RAPTORS EC     | W   | 0.275      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     2.49 | Kisynergy, Rezst, shyyne, Tree60, yz0 |
|            7 |     3717 | 2024-03-09 | Insilio        | L   | 0.207      | -            | -                | -                | -         |    -1.31 | Rezst, shyyne, SLY, Tree60, yz0       |
|            6 |     3731 | 2024-03-09 | ex-Preasy      | L   | 0.206      | -            | -                | -                | -         |    -2.00 | Rezst, shyyne, SLY, Tree60, yz0       |
|            5 |     3741 | 2024-03-08 | MOUZ NXT       | L   | 0.201      | -            | -                | -                | -         |    -0.62 | Rezst, shyyne, SLY, Tree60, yz0       |
|            4 |     3804 | 2024-03-06 | Passion UA     | L   | 0.186      | -            | -                | -                | -         |    -0.45 | Rezst, shyyne, SLY, Tree60, yz0       |
|            3 |     3855 | 2024-03-04 | Secret         | W   | 0.174      | 0.371        | 0.000 (0.000)    | 0.057 (0.004)    | 0 (0.000) |     1.94 | Rezst, shyyne, SLY, Tree60, yz0       |
|            2 |     4011 | 2024-02-25 | The Neighbours | L   | 0.120      | -            | -                | -                | -         |    -1.71 | Rezst, shyyne, SLY, Tree60, yz0       |
|            1 |     4039 | 2024-02-24 | The Neighbours | W   | 0.114      | 0.307        | 0.003 (0.000)    | 0.034 (0.001)    | 1 (0.114) |     1.99 | Rezst, shyyne, SLY, Tree60, yz0       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,259.13)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.828 | $954.00        | $789.97         |
| 2024-03-29 |      0.342 | $951.00        | $325.19         |
| 2024-02-25 |      0.120 | $1,197.00      | $143.97         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
