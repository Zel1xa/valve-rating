### Roster Details<br />
Team Name: Fraud5<br />
Roster: cryths, Rezst, shyyne, Tree60, yz0<br />
Global Rank: [174](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [112]( ../standings_europe.md)<br />
<br />
Final Rank Value:  648.4<br />
<br />
Final Rank Value (648.4) = Starting Rank Value (653.4) + Head To Head Adjustments (-5.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.295[<sup>1</sup>](#table2)
- Bounty Collected: 0.178[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.017[<sup>2</sup>](#table1)

The average of these factors is 0.123<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 653.4
- 400 + ( ( 0.123 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 653.4


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
|           11 |     1022 | 2024-06-10 | K10            | L   | 0.859      | -            | -                | -                | -         |   -11.46 | cryths, Rezst, shyyne, Tree60, yz0    |
|           10 |     1313 | 2024-06-05 | RAPTORS EC     | W   | 0.826      | 0.282        | 0.000 (0.000)    | 0.035 (0.008)    | 0 (0.000) |    10.98 | cryths, Rezst, shyyne, Tree60, yz0    |
|            9 |     3127 | 2024-03-29 | The Neighbours | L   | 0.373      | -            | -                | -                | -         |    -4.96 | Kisynergy, Rezst, shyyne, Tree60, yz0 |
|            8 |     3310 | 2024-03-19 | RAPTORS EC     | W   | 0.307      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     2.72 | Kisynergy, Rezst, shyyne, Tree60, yz0 |
|            7 |     3551 | 2024-03-09 | Insilio        | L   | 0.239      | -            | -                | -                | -         |    -1.52 | Rezst, shyyne, SLY, Tree60, yz0       |
|            6 |     3565 | 2024-03-09 | ex-Preasy      | L   | 0.237      | -            | -                | -                | -         |    -2.19 | Rezst, shyyne, SLY, Tree60, yz0       |
|            5 |     3575 | 2024-03-08 | MOUZ NXT       | L   | 0.232      | -            | -                | -                | -         |    -0.73 | Rezst, shyyne, SLY, Tree60, yz0       |
|            4 |     3638 | 2024-03-06 | Passion UA     | L   | 0.217      | -            | -                | -                | -         |    -0.55 | Rezst, shyyne, SLY, Tree60, yz0       |
|            3 |     3689 | 2024-03-04 | Secret         | W   | 0.205      | 0.371        | 0.000 (0.000)    | 0.061 (0.005)    | 0 (0.000) |     2.26 | Rezst, shyyne, SLY, Tree60, yz0       |
|            2 |     3845 | 2024-02-25 | The Neighbours | L   | 0.152      | -            | -                | -                | -         |    -2.12 | Rezst, shyyne, SLY, Tree60, yz0       |
|            1 |     3873 | 2024-02-24 | The Neighbours | W   | 0.146      | 0.307        | 0.003 (0.000)    | 0.037 (0.002)    | 1 (0.146) |     2.56 | Rezst, shyyne, SLY, Tree60, yz0       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,356.16)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.859 | $954.00        | $819.81         |
| 2024-03-29 |      0.373 | $951.00        | $354.94         |
| 2024-02-25 |      0.152 | $1,197.00      | $181.42         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
