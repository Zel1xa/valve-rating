### Roster Details<br />
Team Name: The Suspect<br />
Roster: BledarD, Caleyy, Dementor, HYPERI1, vAloN<br />
Global Rank: [94](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [69]( ../standings_europe.md)<br />
<br />
Final Rank Value:  860.8<br />
<br />
Final Rank Value (860.8) = Starting Rank Value (820.1) + Head To Head Adjustments (40.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.324[<sup>1</sup>](#table2)
- Bounty Collected: 0.275[<sup>2</sup>](#table1)
- Opponent Network: 0.035[<sup>2</sup>](#table1)
- LAN Wins: 0.187[<sup>2</sup>](#table1)

The average of these factors is 0.205<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 820.1
- 400 + ( ( 0.205 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 820.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |       92 | 2024-08-01 | Alliance        | L   | 1.000      | -            | -                | -                | -         |   -16.41 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|           10 |      764 | 2024-07-14 | ECLOT           | W   | 1.000      | 0.143        | 0.062 (0.009)    | 0.559 (0.080)    | 0 (0.000) |    25.50 | BledarD, Caleyy, deb0, Dementor, HYPERI1  |
|            9 |      766 | 2024-07-14 | ALTERNATE aTTaX | W   | 1.000      | 0.143        | 0.031 (0.004)    | 0.560 (0.080)    | 0 (0.000) |    17.82 | BledarD, Caleyy, deb0, Dementor, HYPERI1  |
|            8 |      775 | 2024-07-14 | ECLOT           | L   | 1.000      | -            | -                | -                | -         |    -5.05 | BledarD, Caleyy, deb0, Dementor, HYPERI1  |
|            7 |      782 | 2024-07-13 | Portugal        | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.120 (0.017)    | 0 (0.000) |     9.17 | BledarD, Caleyy, deb0, Dementor, HYPERI1  |
|            6 |      877 | 2024-07-08 | Latvia          | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.139 (0.020)    | 0 (0.000) |    16.92 | BledarD, Caleyy, deb0, Dementor, HYPERI1  |
|            5 |     1247 | 2024-06-08 | M1X KS          | L   | 0.822      | -            | -                | -                | -         |   -11.44 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|            4 |     1272 | 2024-06-08 | ALTERNATE aTTaX | W   | 0.821      | 0.337        | 0.031 (0.009)    | 0.560 (0.155)    | 1 (0.821) |    15.39 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|            3 |     1319 | 2024-06-07 | plusW KS        | W   | 0.815      | 0.337        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.815) |     2.37 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|            2 |     1736 | 2024-05-25 | ex-Guild Eagles | L   | 0.727      | -            | -                | -                | -         |    -9.83 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|            1 |     1748 | 2024-05-24 | Zero Tenacity   | L   | 0.721      | -            | -                | -                | -         |    -3.77 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,682.84)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
