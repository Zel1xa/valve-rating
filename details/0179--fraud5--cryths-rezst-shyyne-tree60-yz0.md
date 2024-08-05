### Roster Details<br />
Team Name: Fraud5<br />
Roster: cryths, Rezst, shyyne, Tree60, yz0<br />
Global Rank: [179](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [114]( ../standings_europe.md)<br />
<br />
Final Rank Value:  642.2<br />
<br />
Final Rank Value (642.2) = Starting Rank Value (646.9) + Head To Head Adjustments (-4.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.294[<sup>1</sup>](#table2)
- Bounty Collected: 0.174[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.014[<sup>2</sup>](#table1)

The average of these factors is 0.121<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 646.9
- 400 + ( ( 0.121 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 646.9


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
|           11 |     1175 | 2024-06-10 | K10            | L   | 0.831      | -            | -                | -                | -         |   -11.01 | cryths, Rezst, shyyne, Tree60, yz0    |
|           10 |     1466 | 2024-06-05 | RAPTORS EC     | W   | 0.798      | 0.282        | 0.000 (0.000)    | 0.034 (0.008)    | 0 (0.000) |    10.61 | cryths, Rezst, shyyne, Tree60, yz0    |
|            9 |     3280 | 2024-03-29 | The Neighbours | L   | 0.345      | -            | -                | -                | -         |    -4.67 | Kisynergy, Rezst, shyyne, Tree60, yz0 |
|            8 |     3463 | 2024-03-19 | RAPTORS EC     | W   | 0.279      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     2.52 | Kisynergy, Rezst, shyyne, Tree60, yz0 |
|            7 |     3704 | 2024-03-09 | Insilio        | L   | 0.211      | -            | -                | -                | -         |    -1.33 | Rezst, shyyne, SLY, Tree60, yz0       |
|            6 |     3718 | 2024-03-09 | ex-Preasy      | L   | 0.209      | -            | -                | -                | -         |    -2.02 | Rezst, shyyne, SLY, Tree60, yz0       |
|            5 |     3728 | 2024-03-08 | MOUZ NXT       | L   | 0.204      | -            | -                | -                | -         |    -0.64 | Rezst, shyyne, SLY, Tree60, yz0       |
|            4 |     3791 | 2024-03-06 | Passion UA     | L   | 0.189      | -            | -                | -                | -         |    -0.46 | Rezst, shyyne, SLY, Tree60, yz0       |
|            3 |     3842 | 2024-03-04 | Secret         | W   | 0.177      | 0.371        | 0.000 (0.000)    | 0.058 (0.004)    | 0 (0.000) |     1.97 | Rezst, shyyne, SLY, Tree60, yz0       |
|            2 |     3998 | 2024-02-25 | The Neighbours | L   | 0.124      | -            | -                | -                | -         |    -1.75 | Rezst, shyyne, SLY, Tree60, yz0       |
|            1 |     4026 | 2024-02-24 | The Neighbours | W   | 0.118      | 0.307        | 0.003 (0.000)    | 0.034 (0.001)    | 1 (0.118) |     2.05 | Rezst, shyyne, SLY, Tree60, yz0       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,269.47)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.831 | $954.00        | $793.15         |
| 2024-03-29 |      0.345 | $951.00        | $328.36         |
| 2024-02-25 |      0.124 | $1,197.00      | $147.96         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
