### Roster Details<br />
Team Name: Complexity<br />
Roster: EliGE, floppy, Grim, hallzerk, JT<br />
Global Rank: [14](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [3]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1549.9<br />
<br />
Final Rank Value (1549.9) = Starting Rank Value (1639.3) + Head To Head Adjustments (-89.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.668[<sup>1</sup>](#table2)
- Bounty Collected: 0.589[<sup>2</sup>](#table1)
- Opponent Network: 0.227[<sup>2</sup>](#table1)
- LAN Wins: 0.926[<sup>2</sup>](#table1)

The average of these factors is 0.602<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1639.3
- 400 + ( ( 0.602 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1639.3


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
|           34 |       99 | 2024-07-30 | OG            | W   | 1.000      | 0.581        | 0.143 (0.083)    | -                | 1 (1.000) |     1.44 | EliGE, floppy, Grim, hallzerk, JT |
|           33 |      130 | 2024-07-29 | HEROIC        | L   | 1.000      | -            | -                | -                | -         |   -15.50 | EliGE, floppy, Grim, hallzerk, JT |
|           32 |      510 | 2024-07-18 | M80           | L   | 1.000      | -            | -                | -                | -         |   -26.71 | EliGE, floppy, Grim, hallzerk, JT |
|           31 |      565 | 2024-07-17 | Virtus.pro    | L   | 1.000      | -            | -                | -                | -         |   -12.38 | EliGE, floppy, Grim, hallzerk, JT |
|           30 |      899 | 2024-06-16 | Falcons       | W   | 0.892      | 0.500        | 0.205 (0.092)    | -                | 1 (0.892) |     8.69 | EliGE, floppy, Grim, hallzerk, JT |
|           29 |      909 | 2024-06-16 | Aurora        | W   | 0.891      | 0.500        | 0.431 (0.192)    | 0.798 (0.355)    | 1 (0.891) |     8.26 | EliGE, floppy, Grim, hallzerk, JT |
|           28 |      936 | 2024-06-15 | MIBR          | W   | 0.885      | 0.500        | 0.201 (0.089)    | 0.637 (0.282)    | 1 (0.885) |     5.74 | EliGE, floppy, Grim, hallzerk, JT |
|           27 |      960 | 2024-06-14 | ENCE          | L   | 0.880      | -            | -                | -                | -         |   -22.06 | EliGE, floppy, Grim, hallzerk, JT |
|           26 |      972 | 2024-06-14 | Alliance      | W   | 0.878      | 0.500        | -                | 0.319 (0.140)    | 1 (0.878) |     0.43 | EliGE, floppy, Grim, hallzerk, JT |
|           25 |     1305 | 2024-06-06 | FURIA         | L   | 0.827      | -            | -                | -                | -         |   -13.76 | EliGE, floppy, Grim, hallzerk, JT |
|           24 |     1325 | 2024-06-06 | BetBoom       | L   | 0.825      | -            | -                | -                | -         |   -20.56 | EliGE, floppy, Grim, hallzerk, JT |
|           23 |     1338 | 2024-06-06 | fnatic        | L   | 0.825      | -            | -                | -                | -         |   -22.33 | EliGE, floppy, Grim, hallzerk, JT |
|           22 |     1384 | 2024-06-05 | BIG           | W   | 0.819      | 0.715        | 0.132 (0.077)    | 0.299 (0.175)    | 1 (0.819) |     2.78 | EliGE, floppy, Grim, hallzerk, JT |
|           21 |     1397 | 2024-06-05 | Eternal Fire  | W   | 0.818      | 0.715        | 0.757 (0.442)    | 0.461 (0.270)    | 1 (0.818) |    14.51 | EliGE, floppy, Grim, hallzerk, JT |
|           20 |     1620 | 2024-05-27 | MOUZ          | L   | 0.762      | -            | -                | -                | -         |    -4.58 | EliGE, floppy, Grim, hallzerk, JT |
|           19 |     1630 | 2024-05-27 | Liquid        | L   | 0.761      | -            | -                | -                | -         |   -15.34 | EliGE, floppy, Grim, hallzerk, JT |
|           18 |     2162 | 2024-05-11 | MOUZ          | L   | 0.654      | -            | -                | -                | -         |    -4.50 | EliGE, floppy, Grim, hallzerk, JT |
|           17 |     2213 | 2024-05-09 | Virtus.pro    | W   | 0.639      | 0.889        | 0.484 (0.275)    | 0.326 (0.185)    | 1 (0.639) |    11.04 | EliGE, floppy, Grim, hallzerk, JT |
|           16 |     2283 | 2024-05-05 | Natus Vincere | W   | 0.614      | 0.889        | 1.000 (0.546)    | 0.331 (0.181)    | 1 (0.614) |    16.81 | EliGE, floppy, Grim, hallzerk, JT |
|           15 |     2351 | 2024-05-02 | HEROIC        | W   | 0.593      | 0.889        | 0.208 (0.110)    | 0.380 (0.200)    | 1 (0.593) |     7.91 | EliGE, floppy, Grim, hallzerk, JT |
|           14 |     2400 | 2024-04-30 | PERA          | W   | 0.579      | 0.889        | -                | 0.452 (0.233)    | -         |     0.31 | EliGE, floppy, Grim, hallzerk, JT |
|           13 |     3348 | 2024-03-24 | FaZe          | L   | 0.332      | -            | -                | -                | -         |    -4.10 | EliGE, floppy, Grim, hallzerk, JT |
|           12 |     3358 | 2024-03-23 | Vitality      | L   | 0.326      | -            | -                | -                | -         |    -2.47 | EliGE, floppy, Grim, hallzerk, JT |
|           11 |     3373 | 2024-03-22 | MOUZ          | L   | 0.319      | -            | -                | -                | -         |    -2.12 | EliGE, floppy, Grim, hallzerk, JT |
|           10 |     3391 | 2024-03-21 | HEROIC        | W   | 0.314      | -            | -                | -                | -         |     4.27 | EliGE, floppy, Grim, hallzerk, JT |
|            9 |     3400 | 2024-03-21 | paiN          | W   | 0.313      | 1.000        | 0.300 (0.094)    | 0.801 (0.250)    | -         |     1.81 | EliGE, floppy, Grim, hallzerk, JT |
|            8 |     3723 | 2024-03-07 | OG            | L   | 0.220      | -            | -                | -                | -         |    -6.76 | EliGE, floppy, Grim, hallzerk, JT |
|            7 |     3817 | 2024-03-04 | Liquid        | W   | 0.201      | -            | -                | -                | -         |     2.16 | EliGE, floppy, Grim, hallzerk, JT |
|            6 |     3832 | 2024-03-03 | FURIA         | L   | 0.194      | -            | -                | -                | -         |    -2.25 | EliGE, floppy, Grim, hallzerk, JT |
|            5 |     3870 | 2024-03-02 | BOSS          | W   | 0.186      | -            | -                | -                | -         |     0.06 | EliGE, floppy, Grim, hallzerk, JT |
|            4 |     3890 | 2024-03-01 | Elevate       | W   | 0.181      | -            | -                | -                | -         |     0.16 | EliGE, floppy, Grim, hallzerk, JT |
|            3 |     4398 | 2024-02-05 | Falcons       | L   | 0.014      | -            | -                | -                | -         |    -0.33 | EliGE, floppy, Grim, hallzerk, JT |
|            2 |     4419 | 2024-02-04 | Spirit        | L   | 0.006      | -            | -                | -                | -         |    -0.04 | EliGE, floppy, Grim, hallzerk, JT |
|            1 |     4438 | 2024-02-03 | Apeks         | W   | 0.000      | -            | -                | -                | -         |     0.00 | EliGE, floppy, Grim, hallzerk, JT |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($103,927.57)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.892 | $50,000.00     | $44,625.00      |
| 2024-06-09 |      0.846 | $8,000.00      | $6,768.89       |
| 2024-06-02 |      0.800 | $4,000.00      | $3,201.11       |
| 2024-05-12 |      0.659 | $45,000.00     | $29,675.00      |
| 2024-03-31 |      0.380 | $20,000.00     | $7,605.56       |
| 2024-03-10 |      0.241 | $5,000.00      | $1,203.13       |
| 2024-02-11 |      0.053 | $16,000.00     | $848.89         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
