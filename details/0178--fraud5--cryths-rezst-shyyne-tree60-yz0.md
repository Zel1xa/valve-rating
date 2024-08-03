### Roster Details<br />
Team Name: Fraud5<br />
Roster: cryths, Rezst, shyyne, Tree60, yz0<br />
Global Rank: [178](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [113]( ../standings_europe.md)<br />
<br />
Final Rank Value:  643.5<br />
<br />
Final Rank Value (643.5) = Starting Rank Value (648.4) + Head To Head Adjustments (-4.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.294[<sup>1</sup>](#table2)
- Bounty Collected: 0.176[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.014[<sup>2</sup>](#table1)

The average of these factors is 0.121<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 648.4
- 400 + ( ( 0.121 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 648.4


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
|           11 |     1081 | 2024-06-10 | K10            | L   | 0.840      | -            | -                | -                | -         |   -11.15 | cryths, Rezst, shyyne, Tree60, yz0    |
|           10 |     1366 | 2024-06-05 | RAPTORS EC     | W   | 0.807      | 0.282        | 0.000 (0.000)    | 0.036 (0.008)    | 0 (0.000) |    10.74 | cryths, Rezst, shyyne, Tree60, yz0    |
|            9 |     3173 | 2024-03-29 | The Neighbours | L   | 0.354      | -            | -                | -                | -         |    -4.77 | Kisynergy, Rezst, shyyne, Tree60, yz0 |
|            8 |     3351 | 2024-03-19 | RAPTORS EC     | W   | 0.288      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     2.59 | Kisynergy, Rezst, shyyne, Tree60, yz0 |
|            7 |     3589 | 2024-03-09 | Insilio        | L   | 0.219      | -            | -                | -                | -         |    -1.39 | Rezst, shyyne, SLY, Tree60, yz0       |
|            6 |     3603 | 2024-03-09 | ex-Preasy      | L   | 0.218      | -            | -                | -                | -         |    -2.10 | Rezst, shyyne, SLY, Tree60, yz0       |
|            5 |     3613 | 2024-03-08 | MOUZ NXT       | L   | 0.213      | -            | -                | -                | -         |    -0.70 | Rezst, shyyne, SLY, Tree60, yz0       |
|            4 |     3675 | 2024-03-06 | Passion UA     | L   | 0.198      | -            | -                | -                | -         |    -0.49 | Rezst, shyyne, SLY, Tree60, yz0       |
|            3 |     3727 | 2024-03-04 | Secret         | W   | 0.186      | 0.371        | 0.000 (0.000)    | 0.061 (0.004)    | 0 (0.000) |     2.07 | Rezst, shyyne, SLY, Tree60, yz0       |
|            2 |     3883 | 2024-02-25 | The Neighbours | L   | 0.133      | -            | -                | -                | -         |    -1.87 | Rezst, shyyne, SLY, Tree60, yz0       |
|            1 |     3911 | 2024-02-24 | The Neighbours | W   | 0.127      | 0.307        | 0.003 (0.000)    | 0.036 (0.001)    | 1 (0.127) |     2.21 | Rezst, shyyne, SLY, Tree60, yz0       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,297.18)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.840 | $954.00        | $801.67         |
| 2024-03-29 |      0.354 | $951.00        | $336.86         |
| 2024-02-25 |      0.133 | $1,197.00      | $158.66         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
