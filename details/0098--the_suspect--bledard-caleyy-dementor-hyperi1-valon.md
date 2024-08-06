### Roster Details<br />
Team Name: The Suspect<br />
Roster: BledarD, Caleyy, Dementor, HYPERI1, vAloN<br />
Global Rank: [98](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [69]( ../standings_europe.md)<br />
<br />
Final Rank Value:  866.7<br />
<br />
Final Rank Value (866.7) = Starting Rank Value (823.2) + Head To Head Adjustments (43.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.324[<sup>1</sup>](#table2)
- Bounty Collected: 0.275[<sup>2</sup>](#table1)
- Opponent Network: 0.039[<sup>2</sup>](#table1)
- LAN Wins: 0.186[<sup>2</sup>](#table1)

The average of these factors is 0.206<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 823.2
- 400 + ( ( 0.206 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 823.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |       26 | 2024-08-05 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -11.16 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|           12 |       46 | 2024-08-04 | CPH Wolves        | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.361 (0.052)    | 0 (0.000) |    14.04 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|           11 |      156 | 2024-08-01 | Alliance          | L   | 1.000      | -            | -                | -                | -         |   -16.48 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|           10 |      828 | 2024-07-14 | ECLOT             | W   | 1.000      | 0.143        | 0.061 (0.009)    | 0.549 (0.078)    | 0 (0.000) |    25.55 | BledarD, Caleyy, deb0, Dementor, HYPERI1  |
|            9 |      830 | 2024-07-14 | ALTERNATE aTTaX   | W   | 1.000      | 0.143        | 0.031 (0.004)    | 0.549 (0.078)    | 0 (0.000) |    18.02 | BledarD, Caleyy, deb0, Dementor, HYPERI1  |
|            8 |      839 | 2024-07-14 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |    -5.00 | BledarD, Caleyy, deb0, Dementor, HYPERI1  |
|            7 |      846 | 2024-07-13 | Portugal          | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.117 (0.017)    | 0 (0.000) |     9.04 | BledarD, Caleyy, deb0, Dementor, HYPERI1  |
|            6 |      941 | 2024-07-08 | Latvia            | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.137 (0.020)    | 0 (0.000) |    16.74 | BledarD, Caleyy, deb0, Dementor, HYPERI1  |
|            5 |     1311 | 2024-06-08 | M1X KS            | L   | 0.809      | -            | -                | -                | -         |   -11.35 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|            4 |     1336 | 2024-06-08 | ALTERNATE aTTaX   | W   | 0.807      | 0.337        | 0.031 (0.008)    | 0.549 (0.150)    | 1 (0.807) |    15.35 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|            3 |     1383 | 2024-06-07 | plusW KS          | W   | 0.801      | 0.337        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.801) |     2.29 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|            2 |     1800 | 2024-05-25 | ex-Guild Eagles   | L   | 0.714      | -            | -                | -                | -         |    -9.78 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |
|            1 |     1812 | 2024-05-24 | Zero Tenacity     | L   | 0.708      | -            | -                | -                | -         |    -3.69 | BledarD, Caleyy, Dementor, HYPERI1, vAloN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,639.33)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
