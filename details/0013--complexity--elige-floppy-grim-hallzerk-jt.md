### Roster Details<br />
Team Name: Complexity<br />
Roster: EliGE, floppy, Grim, hallzerk, JT<br />
Global Rank: [13](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [2]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1549.8<br />
<br />
Final Rank Value (1549.8) = Starting Rank Value (1641.5) + Head To Head Adjustments (-91.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.668[<sup>1</sup>](#table2)
- Bounty Collected: 0.589[<sup>2</sup>](#table1)
- Opponent Network: 0.228[<sup>2</sup>](#table1)
- LAN Wins: 0.927[<sup>2</sup>](#table1)

The average of these factors is 0.603<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1641.5
- 400 + ( ( 0.603 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1641.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |       95 | 2024-07-30 | OG            | W   | 1.000      | 0.581        | 0.143 (0.083)    | -                | 1 (1.000) |     1.44 | EliGE, floppy, Grim, hallzerk, JT |
|           33 |      126 | 2024-07-29 | HEROIC        | L   | 1.000      | -            | -                | -                | -         |   -15.63 | EliGE, floppy, Grim, hallzerk, JT |
|           32 |      506 | 2024-07-18 | M80           | L   | 1.000      | -            | -                | -                | -         |   -26.71 | EliGE, floppy, Grim, hallzerk, JT |
|           31 |      561 | 2024-07-17 | Virtus.pro    | L   | 1.000      | -            | -                | -                | -         |   -12.31 | EliGE, floppy, Grim, hallzerk, JT |
|           30 |      895 | 2024-06-16 | Falcons       | W   | 0.894      | 0.500        | 0.206 (0.092)    | -                | 1 (0.894) |     8.72 | EliGE, floppy, Grim, hallzerk, JT |
|           29 |      905 | 2024-06-16 | Aurora        | W   | 0.892      | 0.500        | 0.432 (0.193)    | 0.798 (0.356)    | 1 (0.892) |     8.27 | EliGE, floppy, Grim, hallzerk, JT |
|           28 |      932 | 2024-06-15 | MIBR          | W   | 0.886      | 0.500        | 0.201 (0.089)    | 0.637 (0.282)    | 1 (0.886) |     5.78 | EliGE, floppy, Grim, hallzerk, JT |
|           27 |      956 | 2024-06-14 | ENCE          | L   | 0.881      | -            | -                | -                | -         |   -22.13 | EliGE, floppy, Grim, hallzerk, JT |
|           26 |      968 | 2024-06-14 | Alliance      | W   | 0.880      | 0.500        | -                | 0.319 (0.141)    | 1 (0.880) |     0.44 | EliGE, floppy, Grim, hallzerk, JT |
|           25 |     1301 | 2024-06-06 | FURIA         | L   | 0.828      | -            | -                | -                | -         |   -13.78 | EliGE, floppy, Grim, hallzerk, JT |
|           24 |     1321 | 2024-06-06 | BetBoom       | L   | 0.827      | -            | -                | -                | -         |   -20.57 | EliGE, floppy, Grim, hallzerk, JT |
|           23 |     1334 | 2024-06-06 | fnatic        | L   | 0.826      | -            | -                | -                | -         |   -22.34 | EliGE, floppy, Grim, hallzerk, JT |
|           22 |     1380 | 2024-06-05 | BIG           | W   | 0.821      | 0.715        | 0.132 (0.078)    | 0.299 (0.175)    | 1 (0.821) |     2.81 | EliGE, floppy, Grim, hallzerk, JT |
|           21 |     1393 | 2024-06-05 | Eternal Fire  | W   | 0.819      | 0.715        | 0.757 (0.444)    | 0.461 (0.270)    | 1 (0.819) |    14.53 | EliGE, floppy, Grim, hallzerk, JT |
|           20 |     1616 | 2024-05-27 | MOUZ          | L   | 0.763      | -            | -                | -                | -         |    -4.58 | EliGE, floppy, Grim, hallzerk, JT |
|           19 |     1626 | 2024-05-27 | Liquid        | L   | 0.762      | -            | -                | -                | -         |   -16.99 | EliGE, floppy, Grim, hallzerk, JT |
|           18 |     2158 | 2024-05-11 | MOUZ          | L   | 0.655      | -            | -                | -                | -         |    -4.54 | EliGE, floppy, Grim, hallzerk, JT |
|           17 |     2209 | 2024-05-09 | Virtus.pro    | W   | 0.641      | 0.889        | 0.483 (0.275)    | 0.326 (0.186)    | 1 (0.641) |    11.08 | EliGE, floppy, Grim, hallzerk, JT |
|           16 |     2279 | 2024-05-05 | Natus Vincere | W   | 0.615      | 0.889        | 1.000 (0.547)    | 0.331 (0.181)    | 1 (0.615) |    16.86 | EliGE, floppy, Grim, hallzerk, JT |
|           15 |     2347 | 2024-05-02 | HEROIC        | W   | 0.594      | 0.889        | 0.209 (0.110)    | 0.381 (0.201)    | 1 (0.594) |     7.86 | EliGE, floppy, Grim, hallzerk, JT |
|           14 |     2396 | 2024-04-30 | PERA          | W   | 0.581      | 0.889        | -                | 0.452 (0.233)    | -         |     0.31 | EliGE, floppy, Grim, hallzerk, JT |
|           13 |     3344 | 2024-03-24 | FaZe          | L   | 0.333      | -            | -                | -                | -         |    -4.10 | EliGE, floppy, Grim, hallzerk, JT |
|           12 |     3354 | 2024-03-23 | Vitality      | L   | 0.328      | -            | -                | -                | -         |    -2.48 | EliGE, floppy, Grim, hallzerk, JT |
|           11 |     3369 | 2024-03-22 | MOUZ          | L   | 0.321      | -            | -                | -                | -         |    -2.13 | EliGE, floppy, Grim, hallzerk, JT |
|           10 |     3387 | 2024-03-21 | HEROIC        | W   | 0.315      | -            | -                | -                | -         |     4.29 | EliGE, floppy, Grim, hallzerk, JT |
|            9 |     3396 | 2024-03-21 | paiN          | W   | 0.314      | 1.000        | 0.300 (0.094)    | 0.801 (0.251)    | -         |     1.82 | EliGE, floppy, Grim, hallzerk, JT |
|            8 |     3719 | 2024-03-07 | OG            | L   | 0.222      | -            | -                | -                | -         |    -6.80 | EliGE, floppy, Grim, hallzerk, JT |
|            7 |     3813 | 2024-03-04 | Liquid        | W   | 0.203      | -            | -                | -                | -         |     1.63 | EliGE, floppy, Grim, hallzerk, JT |
|            6 |     3828 | 2024-03-03 | FURIA         | L   | 0.195      | -            | -                | -                | -         |    -2.27 | EliGE, floppy, Grim, hallzerk, JT |
|            5 |     3866 | 2024-03-02 | BOSS          | W   | 0.188      | -            | -                | -                | -         |     0.06 | EliGE, floppy, Grim, hallzerk, JT |
|            4 |     3886 | 2024-03-01 | Elevate       | W   | 0.182      | -            | -                | -                | -         |     0.16 | EliGE, floppy, Grim, hallzerk, JT |
|            3 |     4394 | 2024-02-05 | Falcons       | L   | 0.015      | -            | -                | -                | -         |    -0.36 | EliGE, floppy, Grim, hallzerk, JT |
|            2 |     4415 | 2024-02-04 | Spirit        | L   | 0.008      | -            | -                | -                | -         |    -0.04 | EliGE, floppy, Grim, hallzerk, JT |
|            1 |     4434 | 2024-02-03 | Apeks         | W   | 0.002      | -            | -                | -                | -         |     0.00 | EliGE, floppy, Grim, hallzerk, JT |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($104,133.13)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.894 | $50,000.00     | $44,694.44      |
| 2024-06-09 |      0.848 | $8,000.00      | $6,780.00       |
| 2024-06-02 |      0.802 | $4,000.00      | $3,206.67       |
| 2024-05-12 |      0.661 | $45,000.00     | $29,737.50      |
| 2024-03-31 |      0.382 | $20,000.00     | $7,633.33       |
| 2024-03-10 |      0.242 | $5,000.00      | $1,210.07       |
| 2024-02-11 |      0.054 | $16,000.00     | $871.11         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
