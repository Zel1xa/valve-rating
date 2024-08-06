### Roster Details<br />
Team Name: Complexity<br />
Roster: EliGE, floppy, Grim, hallzerk, JT<br />
Global Rank: [14](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [3]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1569.2<br />
<br />
Final Rank Value (1569.2) = Starting Rank Value (1650.7) + Head To Head Adjustments (-81.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.682[<sup>1</sup>](#table2)
- Bounty Collected: 0.588[<sup>2</sup>](#table1)
- Opponent Network: 0.224[<sup>2</sup>](#table1)
- LAN Wins: 0.944[<sup>2</sup>](#table1)

The average of these factors is 0.609<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1650.7
- 400 + ( ( 0.609 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1650.7


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
|           34 |       36 | 2024-08-04 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -4.12 | EliGE, floppy, Grim, hallzerk, JT |
|           33 |       85 | 2024-08-03 | Spirit        | L   | 1.000      | -            | -                | -                | -         |    -3.86 | EliGE, floppy, Grim, hallzerk, JT |
|           32 |      117 | 2024-08-02 | HEROIC        | W   | 1.000      | 0.581        | 0.225 (0.130)    | 0.363 (0.211)    | 1 (1.000) |    15.48 | EliGE, floppy, Grim, hallzerk, JT |
|           31 |      247 | 2024-07-30 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.37 | EliGE, floppy, Grim, hallzerk, JT |
|           30 |      277 | 2024-07-29 | HEROIC        | L   | 1.000      | -            | -                | -                | -         |   -15.80 | EliGE, floppy, Grim, hallzerk, JT |
|           29 |      649 | 2024-07-18 | M80           | L   | 1.000      | -            | -                | -                | -         |   -27.40 | EliGE, floppy, Grim, hallzerk, JT |
|           28 |      701 | 2024-07-17 | Virtus.pro    | L   | 1.000      | -            | -                | -                | -         |   -13.05 | EliGE, floppy, Grim, hallzerk, JT |
|           27 |     1033 | 2024-06-16 | Falcons       | W   | 0.861      | 0.500        | 0.220 (0.095)    | -                | 1 (0.861) |     7.45 | EliGE, floppy, Grim, hallzerk, JT |
|           26 |     1042 | 2024-06-16 | Aurora        | W   | 0.859      | 0.500        | 0.421 (0.181)    | 0.776 (0.333)    | 1 (0.859) |     7.77 | EliGE, floppy, Grim, hallzerk, JT |
|           25 |     1072 | 2024-06-15 | MIBR          | W   | 0.854      | 0.500        | 0.208 (0.089)    | 0.647 (0.276)    | 1 (0.854) |     6.54 | EliGE, floppy, Grim, hallzerk, JT |
|           24 |     1102 | 2024-06-14 | ENCE          | L   | 0.848      | -            | -                | -                | -         |   -21.13 | EliGE, floppy, Grim, hallzerk, JT |
|           23 |     1114 | 2024-06-14 | Alliance      | W   | 0.847      | -            | -                | -                | 1 (0.847) |     0.38 | EliGE, floppy, Grim, hallzerk, JT |
|           22 |     1434 | 2024-06-06 | FURIA         | L   | 0.795      | -            | -                | -                | -         |   -13.56 | EliGE, floppy, Grim, hallzerk, JT |
|           21 |     1454 | 2024-06-06 | BetBoom       | L   | 0.794      | -            | -                | -                | -         |   -20.10 | EliGE, floppy, Grim, hallzerk, JT |
|           20 |     1466 | 2024-06-06 | fnatic        | L   | 0.793      | -            | -                | -                | -         |   -18.84 | EliGE, floppy, Grim, hallzerk, JT |
|           19 |     1510 | 2024-06-05 | BIG           | W   | 0.788      | 0.715        | 0.154 (0.087)    | 0.297 (0.167)    | 1 (0.788) |     3.35 | EliGE, floppy, Grim, hallzerk, JT |
|           18 |     1523 | 2024-06-05 | Eternal Fire  | W   | 0.786      | 0.715        | 0.739 (0.415)    | 0.448 (0.252)    | 1 (0.786) |    13.23 | EliGE, floppy, Grim, hallzerk, JT |
|           17 |     1745 | 2024-05-27 | MOUZ          | L   | 0.731      | -            | -                | -                | -         |    -5.03 | EliGE, floppy, Grim, hallzerk, JT |
|           16 |     1755 | 2024-05-27 | Liquid        | L   | 0.729      | -            | -                | -                | -         |   -13.39 | EliGE, floppy, Grim, hallzerk, JT |
|           15 |     2250 | 2024-05-11 | MOUZ          | L   | 0.622      | -            | -                | -                | -         |    -4.92 | EliGE, floppy, Grim, hallzerk, JT |
|           14 |     2301 | 2024-05-09 | Virtus.pro    | W   | 0.608      | 0.889        | 0.498 (0.269)    | 0.316 (0.171)    | 1 (0.608) |    10.12 | EliGE, floppy, Grim, hallzerk, JT |
|           13 |     2369 | 2024-05-05 | Natus Vincere | W   | 0.582      | 0.889        | 1.000 (0.518)    | 0.365 (0.189)    | 1 (0.582) |    15.70 | EliGE, floppy, Grim, hallzerk, JT |
|           12 |     2436 | 2024-05-02 | HEROIC        | W   | 0.561      | 0.889        | 0.225 (0.112)    | 0.363 (0.181)    | -         |     7.09 | EliGE, floppy, Grim, hallzerk, JT |
|           11 |     2483 | 2024-04-30 | PERA          | W   | 0.548      | 0.889        | -                | 0.445 (0.217)    | -         |     0.28 | EliGE, floppy, Grim, hallzerk, JT |
|           10 |     3407 | 2024-03-24 | FaZe          | L   | 0.301      | -            | -                | -                | -         |    -4.34 | EliGE, floppy, Grim, hallzerk, JT |
|            9 |     3417 | 2024-03-23 | Vitality      | L   | 0.295      | -            | -                | -                | -         |    -2.27 | EliGE, floppy, Grim, hallzerk, JT |
|            8 |     3432 | 2024-03-22 | MOUZ          | L   | 0.288      | -            | -                | -                | -         |    -2.26 | EliGE, floppy, Grim, hallzerk, JT |
|            7 |     3450 | 2024-03-21 | HEROIC        | W   | 0.282      | -            | -                | -                | -         |     3.48 | EliGE, floppy, Grim, hallzerk, JT |
|            6 |     3459 | 2024-03-21 | paiN          | W   | 0.281      | 1.000        | 0.324 (0.091)    | 0.857 (0.241)    | -         |     1.84 | EliGE, floppy, Grim, hallzerk, JT |
|            5 |     3776 | 2024-03-07 | OG            | L   | 0.189      | -            | -                | -                | -         |    -5.81 | EliGE, floppy, Grim, hallzerk, JT |
|            4 |     3865 | 2024-03-04 | Liquid        | W   | 0.170      | -            | -                | -                | -         |     2.24 | EliGE, floppy, Grim, hallzerk, JT |
|            3 |     3880 | 2024-03-03 | FURIA         | L   | 0.163      | -            | -                | -                | -         |    -2.06 | EliGE, floppy, Grim, hallzerk, JT |
|            2 |     3918 | 2024-03-02 | BOSS          | W   | 0.155      | -            | -                | -                | -         |     0.04 | EliGE, floppy, Grim, hallzerk, JT |
|            1 |     3937 | 2024-03-01 | Elevate       | W   | 0.149      | -            | -                | -                | -         |     0.12 | EliGE, floppy, Grim, hallzerk, JT |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($109,435.35)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.34) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $10,500.00     | $10,500.00      |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.861 | $50,000.00     | $43,055.56      |
| 2024-06-09 |      0.815 | $8,000.00      | $6,517.78       |
| 2024-06-02 |      0.769 | $4,000.00      | $3,075.56       |
| 2024-05-12 |      0.628 | $45,000.00     | $28,262.50      |
| 2024-03-31 |      0.349 | $20,000.00     | $6,977.78       |
| 2024-03-10 |      0.209 | $5,000.00      | $1,046.18       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
