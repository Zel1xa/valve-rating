### Roster Details<br />
Team Name: Complexity<br />
Roster: EliGE, floppy, Grim, hallzerk, JT<br />
Global Rank: [14](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [3]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1569.7<br />
<br />
Final Rank Value (1569.7) = Starting Rank Value (1651.4) + Head To Head Adjustments (-81.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.682[<sup>1</sup>](#table2)
- Bounty Collected: 0.588[<sup>2</sup>](#table1)
- Opponent Network: 0.225[<sup>2</sup>](#table1)
- LAN Wins: 0.945[<sup>2</sup>](#table1)

The average of these factors is 0.610<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1651.4
- 400 + ( ( 0.610 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1651.4


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
|           34 |       32 | 2024-08-04 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -4.13 | EliGE, floppy, Grim, hallzerk, JT |
|           33 |       81 | 2024-08-03 | Spirit        | L   | 1.000      | -            | -                | -                | -         |    -3.86 | EliGE, floppy, Grim, hallzerk, JT |
|           32 |      113 | 2024-08-02 | HEROIC        | W   | 1.000      | 0.581        | 0.225 (0.131)    | 0.364 (0.211)    | 1 (1.000) |    15.50 | EliGE, floppy, Grim, hallzerk, JT |
|           31 |      243 | 2024-07-30 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.37 | EliGE, floppy, Grim, hallzerk, JT |
|           30 |      273 | 2024-07-29 | HEROIC        | L   | 1.000      | -            | -                | -                | -         |   -15.79 | EliGE, floppy, Grim, hallzerk, JT |
|           29 |      645 | 2024-07-18 | M80           | L   | 1.000      | -            | -                | -                | -         |   -27.40 | EliGE, floppy, Grim, hallzerk, JT |
|           28 |      697 | 2024-07-17 | Virtus.pro    | L   | 1.000      | -            | -                | -                | -         |   -13.04 | EliGE, floppy, Grim, hallzerk, JT |
|           27 |     1029 | 2024-06-16 | Falcons       | W   | 0.864      | 0.500        | 0.221 (0.095)    | -                | 1 (0.864) |     7.49 | EliGE, floppy, Grim, hallzerk, JT |
|           26 |     1038 | 2024-06-16 | Aurora        | W   | 0.862      | 0.500        | 0.421 (0.182)    | 0.777 (0.335)    | 1 (0.862) |     7.73 | EliGE, floppy, Grim, hallzerk, JT |
|           25 |     1068 | 2024-06-15 | MIBR          | W   | 0.856      | 0.500        | 0.208 (0.089)    | 0.648 (0.277)    | 1 (0.856) |     6.57 | EliGE, floppy, Grim, hallzerk, JT |
|           24 |     1098 | 2024-06-14 | ENCE          | L   | 0.851      | -            | -                | -                | -         |   -21.23 | EliGE, floppy, Grim, hallzerk, JT |
|           23 |     1110 | 2024-06-14 | Alliance      | W   | 0.849      | -            | -                | -                | 1 (0.849) |     0.38 | EliGE, floppy, Grim, hallzerk, JT |
|           22 |     1430 | 2024-06-06 | FURIA         | L   | 0.798      | -            | -                | -                | -         |   -13.63 | EliGE, floppy, Grim, hallzerk, JT |
|           21 |     1450 | 2024-06-06 | BetBoom       | L   | 0.797      | -            | -                | -                | -         |   -20.18 | EliGE, floppy, Grim, hallzerk, JT |
|           20 |     1462 | 2024-06-06 | fnatic        | L   | 0.796      | -            | -                | -                | -         |   -18.92 | EliGE, floppy, Grim, hallzerk, JT |
|           19 |     1506 | 2024-06-05 | BIG           | W   | 0.790      | 0.715        | 0.154 (0.087)    | 0.297 (0.168)    | 1 (0.790) |     3.36 | EliGE, floppy, Grim, hallzerk, JT |
|           18 |     1519 | 2024-06-05 | Eternal Fire  | W   | 0.789      | 0.715        | 0.739 (0.417)    | 0.449 (0.253)    | 1 (0.789) |    13.27 | EliGE, floppy, Grim, hallzerk, JT |
|           17 |     1741 | 2024-05-27 | MOUZ          | L   | 0.733      | -            | -                | -                | -         |    -5.05 | EliGE, floppy, Grim, hallzerk, JT |
|           16 |     1751 | 2024-05-27 | Liquid        | L   | 0.732      | -            | -                | -                | -         |   -13.45 | EliGE, floppy, Grim, hallzerk, JT |
|           15 |     2246 | 2024-05-11 | MOUZ          | L   | 0.625      | -            | -                | -                | -         |    -4.93 | EliGE, floppy, Grim, hallzerk, JT |
|           14 |     2297 | 2024-05-09 | Virtus.pro    | W   | 0.610      | 0.889        | 0.498 (0.270)    | 0.316 (0.172)    | 1 (0.610) |    10.15 | EliGE, floppy, Grim, hallzerk, JT |
|           13 |     2365 | 2024-05-05 | Natus Vincere | W   | 0.585      | 0.889        | 1.000 (0.520)    | 0.365 (0.190)    | 1 (0.585) |    15.76 | EliGE, floppy, Grim, hallzerk, JT |
|           12 |     2432 | 2024-05-02 | HEROIC        | W   | 0.564      | 0.889        | 0.225 (0.113)    | 0.364 (0.182)    | -         |     7.13 | EliGE, floppy, Grim, hallzerk, JT |
|           11 |     2479 | 2024-04-30 | PERA          | W   | 0.550      | 0.889        | -                | 0.445 (0.218)    | -         |     0.28 | EliGE, floppy, Grim, hallzerk, JT |
|           10 |     3403 | 2024-03-24 | FaZe          | L   | 0.303      | -            | -                | -                | -         |    -4.36 | EliGE, floppy, Grim, hallzerk, JT |
|            9 |     3413 | 2024-03-23 | Vitality      | L   | 0.297      | -            | -                | -                | -         |    -2.29 | EliGE, floppy, Grim, hallzerk, JT |
|            8 |     3428 | 2024-03-22 | MOUZ          | L   | 0.290      | -            | -                | -                | -         |    -2.28 | EliGE, floppy, Grim, hallzerk, JT |
|            7 |     3446 | 2024-03-21 | HEROIC        | W   | 0.285      | -            | -                | -                | -         |     3.52 | EliGE, floppy, Grim, hallzerk, JT |
|            6 |     3455 | 2024-03-21 | paiN          | W   | 0.284      | 1.000        | 0.325 (0.092)    | 0.857 (0.243)    | -         |     1.86 | EliGE, floppy, Grim, hallzerk, JT |
|            5 |     3772 | 2024-03-07 | OG            | L   | 0.191      | -            | -                | -                | -         |    -5.88 | EliGE, floppy, Grim, hallzerk, JT |
|            4 |     3861 | 2024-03-04 | Liquid        | W   | 0.172      | -            | -                | -                | -         |     2.27 | EliGE, floppy, Grim, hallzerk, JT |
|            3 |     3876 | 2024-03-03 | FURIA         | L   | 0.165      | -            | -                | -                | -         |    -2.10 | EliGE, floppy, Grim, hallzerk, JT |
|            2 |     3914 | 2024-03-02 | BOSS          | W   | 0.158      | -            | -                | -                | -         |     0.04 | EliGE, floppy, Grim, hallzerk, JT |
|            1 |     3933 | 2024-03-01 | Elevate       | W   | 0.152      | -            | -                | -                | -         |     0.12 | EliGE, floppy, Grim, hallzerk, JT |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($109,765.35)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.34) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $10,500.00     | $10,500.00      |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.864 | $50,000.00     | $43,180.56      |
| 2024-06-09 |      0.817 | $8,000.00      | $6,537.78       |
| 2024-06-02 |      0.771 | $4,000.00      | $3,085.56       |
| 2024-05-12 |      0.631 | $45,000.00     | $28,375.00      |
| 2024-03-31 |      0.351 | $20,000.00     | $7,027.78       |
| 2024-03-10 |      0.212 | $5,000.00      | $1,058.68       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
