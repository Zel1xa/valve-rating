### Roster Details<br />
Team Name: The Suspect<br />
Roster: BledarD, Caleyy, Dementor, HYPERI1, vAloN<br />
Global Rank: [92](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [66]( ../standings_europe.md)<br />
<br />
Final Rank Value:  877.3<br />
<br />
Final Rank Value (877.3) = Starting Rank Value (823.0) + Head To Head Adjustments (54.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.324[<sup>1</sup>](#table2)
- Bounty Collected: 0.276[<sup>2</sup>](#table1)
- Opponent Network: 0.040[<sup>2</sup>](#table1)
- LAN Wins: 0.187[<sup>2</sup>](#table1)

The average of these factors is 0.207<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 823.0
- 400 + ( ( 0.207 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 823.0


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
|           12 |       17 | 2024-08-04 | CPH Wolves      | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.365 (0.052)    | 0 (0.000) |    13.92 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|           11 |      128 | 2024-08-01 | Alliance        | L   | 1.000      | -            | -                | -                | -         |   -16.50 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|           10 |      800 | 2024-07-14 | ECLOT           | W   | 1.000      | 0.143        | 0.062 (0.009)    | 0.558 (0.080)    | 0 (0.000) |    25.51 | BledarD, Caleyy, deb0, Dementor, HYPERI1  |
|            9 |      802 | 2024-07-14 | ALTERNATE aTTaX | W   | 1.000      | 0.143        | 0.031 (0.004)    | 0.560 (0.080)    | 0 (0.000) |    17.94 | BledarD, Caleyy, deb0, Dementor, HYPERI1  |
|            8 |      811 | 2024-07-14 | ECLOT           | L   | 1.000      | -            | -                | -                | -         |    -5.04 | BledarD, Caleyy, deb0, Dementor, HYPERI1  |
|            7 |      818 | 2024-07-13 | Portugal        | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.120 (0.017)    | 0 (0.000) |     9.07 | BledarD, Caleyy, deb0, Dementor, HYPERI1  |
|            6 |      913 | 2024-07-08 | Latvia          | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.139 (0.020)    | 0 (0.000) |    16.78 | BledarD, Caleyy, deb0, Dementor, HYPERI1  |
|            5 |     1283 | 2024-06-08 | M1X KS          | L   | 0.818      | -            | -                | -                | -         |   -11.47 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|            4 |     1308 | 2024-06-08 | ALTERNATE aTTaX | W   | 0.817      | 0.337        | 0.031 (0.009)    | 0.560 (0.154)    | 1 (0.817) |    15.44 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|            3 |     1355 | 2024-06-07 | plusW KS        | W   | 0.811      | 0.337        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.811) |     2.32 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|            2 |     1772 | 2024-05-25 | ex-Guild Eagles | L   | 0.723      | -            | -                | -                | -         |    -9.93 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|            1 |     1784 | 2024-05-24 | Zero Tenacity   | L   | 0.717      | -            | -                | -                | -         |    -3.82 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,669.24)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
