### Roster Details<br />
Team Name: The Suspect<br />
Roster: BledarD, Caleyy, Dementor, HYPERI1, vAloN<br />
Global Rank: [92](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [66]( ../standings_europe.md)<br />
<br />
Final Rank Value:  877.4<br />
<br />
Final Rank Value (877.4) = Starting Rank Value (823.1) + Head To Head Adjustments (54.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.324[<sup>1</sup>](#table2)
- Bounty Collected: 0.276[<sup>2</sup>](#table1)
- Opponent Network: 0.040[<sup>2</sup>](#table1)
- LAN Wins: 0.187[<sup>2</sup>](#table1)

The average of these factors is 0.207<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 823.1
- 400 + ( ( 0.207 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 823.1


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
|           12 |       13 | 2024-08-04 | CPH Wolves      | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.365 (0.052)    | 0 (0.000) |    13.92 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|           11 |      124 | 2024-08-01 | Alliance        | L   | 1.000      | -            | -                | -                | -         |   -16.49 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|           10 |      796 | 2024-07-14 | ECLOT           | W   | 1.000      | 0.143        | 0.062 (0.009)    | 0.558 (0.080)    | 0 (0.000) |    25.51 | BledarD, Caleyy, deb0, Dementor, HYPERI1  |
|            9 |      798 | 2024-07-14 | ALTERNATE aTTaX | W   | 1.000      | 0.143        | 0.031 (0.004)    | 0.560 (0.080)    | 0 (0.000) |    17.94 | BledarD, Caleyy, deb0, Dementor, HYPERI1  |
|            8 |      807 | 2024-07-14 | ECLOT           | L   | 1.000      | -            | -                | -                | -         |    -5.04 | BledarD, Caleyy, deb0, Dementor, HYPERI1  |
|            7 |      814 | 2024-07-13 | Portugal        | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.120 (0.017)    | 0 (0.000) |     9.08 | BledarD, Caleyy, deb0, Dementor, HYPERI1  |
|            6 |      909 | 2024-07-08 | Latvia          | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.139 (0.020)    | 0 (0.000) |    16.79 | BledarD, Caleyy, deb0, Dementor, HYPERI1  |
|            5 |     1279 | 2024-06-08 | M1X KS          | L   | 0.820      | -            | -                | -                | -         |   -11.50 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|            4 |     1304 | 2024-06-08 | ALTERNATE aTTaX | W   | 0.819      | 0.337        | 0.031 (0.009)    | 0.560 (0.155)    | 1 (0.819) |    15.48 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|            3 |     1351 | 2024-06-07 | plusW KS        | W   | 0.813      | 0.337        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.813) |     2.33 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|            2 |     1768 | 2024-05-25 | ex-Guild Eagles | L   | 0.725      | -            | -                | -                | -         |    -9.94 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|            1 |     1780 | 2024-05-24 | Zero Tenacity   | L   | 0.720      | -            | -                | -                | -         |    -3.83 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,677.02)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
