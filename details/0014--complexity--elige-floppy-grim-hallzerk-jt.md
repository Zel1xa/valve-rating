### Roster Details<br />
Team Name: Complexity<br />
Roster: EliGE, floppy, Grim, hallzerk, JT<br />
Global Rank: [14](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [3]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1569.1<br />
<br />
Final Rank Value (1569.1) = Starting Rank Value (1650.5) + Head To Head Adjustments (-81.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.682[<sup>1</sup>](#table2)
- Bounty Collected: 0.587[<sup>2</sup>](#table1)
- Opponent Network: 0.218[<sup>2</sup>](#table1)
- LAN Wins: 0.944[<sup>2</sup>](#table1)

The average of these factors is 0.608<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1650.5
- 400 + ( ( 0.608 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1650.5


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
|           34 |       48 | 2024-08-04 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -4.12 | EliGE, floppy, Grim, hallzerk, JT |
|           33 |       97 | 2024-08-03 | Spirit        | L   | 1.000      | -            | -                | -                | -         |    -3.86 | EliGE, floppy, Grim, hallzerk, JT |
|           32 |      129 | 2024-08-02 | HEROIC        | W   | 1.000      | 0.581        | 0.224 (0.130)    | 0.354 (0.206)    | 1 (1.000) |    15.46 | EliGE, floppy, Grim, hallzerk, JT |
|           31 |      259 | 2024-07-30 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.40 | EliGE, floppy, Grim, hallzerk, JT |
|           30 |      289 | 2024-07-29 | HEROIC        | L   | 1.000      | -            | -                | -                | -         |   -15.83 | EliGE, floppy, Grim, hallzerk, JT |
|           29 |      661 | 2024-07-18 | M80           | L   | 1.000      | -            | -                | -                | -         |   -27.41 | EliGE, floppy, Grim, hallzerk, JT |
|           28 |      713 | 2024-07-17 | Virtus.pro    | L   | 1.000      | -            | -                | -                | -         |   -13.07 | EliGE, floppy, Grim, hallzerk, JT |
|           27 |     1045 | 2024-06-16 | Falcons       | W   | 0.860      | 0.500        | 0.219 (0.094)    | -                | 1 (0.860) |     7.44 | EliGE, floppy, Grim, hallzerk, JT |
|           26 |     1054 | 2024-06-16 | Aurora        | W   | 0.858      | 0.500        | 0.420 (0.180)    | 0.758 (0.325)    | 1 (0.858) |     7.84 | EliGE, floppy, Grim, hallzerk, JT |
|           25 |     1084 | 2024-06-15 | MIBR          | W   | 0.852      | 0.500        | 0.208 (0.088)    | 0.633 (0.270)    | 1 (0.852) |     6.50 | EliGE, floppy, Grim, hallzerk, JT |
|           24 |     1114 | 2024-06-14 | ENCE          | L   | 0.847      | -            | -                | -                | -         |   -21.08 | EliGE, floppy, Grim, hallzerk, JT |
|           23 |     1126 | 2024-06-14 | Alliance      | W   | 0.846      | -            | -                | -                | 1 (0.846) |     0.38 | EliGE, floppy, Grim, hallzerk, JT |
|           22 |     1446 | 2024-06-06 | FURIA         | L   | 0.794      | -            | -                | -                | -         |   -13.55 | EliGE, floppy, Grim, hallzerk, JT |
|           21 |     1466 | 2024-06-06 | BetBoom       | L   | 0.793      | -            | -                | -                | -         |   -20.08 | EliGE, floppy, Grim, hallzerk, JT |
|           20 |     1478 | 2024-06-06 | fnatic        | L   | 0.792      | -            | -                | -                | -         |   -18.81 | EliGE, floppy, Grim, hallzerk, JT |
|           19 |     1522 | 2024-06-05 | BIG           | W   | 0.787      | 0.715        | 0.154 (0.087)    | 0.290 (0.163)    | 1 (0.787) |     3.34 | EliGE, floppy, Grim, hallzerk, JT |
|           18 |     1535 | 2024-06-05 | Eternal Fire  | W   | 0.785      | 0.715        | 0.738 (0.415)    | 0.438 (0.246)    | 1 (0.785) |    13.24 | EliGE, floppy, Grim, hallzerk, JT |
|           17 |     1757 | 2024-05-27 | MOUZ          | L   | 0.729      | -            | -                | -                | -         |    -5.04 | EliGE, floppy, Grim, hallzerk, JT |
|           16 |     1767 | 2024-05-27 | Liquid        | L   | 0.728      | -            | -                | -                | -         |   -13.36 | EliGE, floppy, Grim, hallzerk, JT |
|           15 |     2262 | 2024-05-11 | MOUZ          | L   | 0.621      | -            | -                | -                | -         |    -4.92 | EliGE, floppy, Grim, hallzerk, JT |
|           14 |     2313 | 2024-05-09 | Virtus.pro    | W   | 0.607      | 0.889        | 0.498 (0.269)    | 0.308 (0.166)    | 1 (0.607) |    10.08 | EliGE, floppy, Grim, hallzerk, JT |
|           13 |     2381 | 2024-05-05 | Natus Vincere | W   | 0.581      | 0.889        | 1.000 (0.517)    | 0.357 (0.184)    | 1 (0.581) |    15.67 | EliGE, floppy, Grim, hallzerk, JT |
|           12 |     2448 | 2024-05-02 | HEROIC        | W   | 0.560      | 0.889        | 0.224 (0.112)    | 0.354 (0.176)    | -         |     7.05 | EliGE, floppy, Grim, hallzerk, JT |
|           11 |     2495 | 2024-04-30 | PERA          | W   | 0.547      | 0.889        | -                | 0.435 (0.212)    | -         |     0.28 | EliGE, floppy, Grim, hallzerk, JT |
|           10 |     3419 | 2024-03-24 | FaZe          | L   | 0.299      | -            | -                | -                | -         |    -4.33 | EliGE, floppy, Grim, hallzerk, JT |
|            9 |     3429 | 2024-03-23 | Vitality      | L   | 0.294      | -            | -                | -                | -         |    -2.26 | EliGE, floppy, Grim, hallzerk, JT |
|            8 |     3444 | 2024-03-22 | MOUZ          | L   | 0.287      | -            | -                | -                | -         |    -2.25 | EliGE, floppy, Grim, hallzerk, JT |
|            7 |     3462 | 2024-03-21 | HEROIC        | W   | 0.281      | -            | -                | -                | -         |     3.46 | EliGE, floppy, Grim, hallzerk, JT |
|            6 |     3471 | 2024-03-21 | paiN          | W   | 0.280      | 1.000        | 0.324 (0.091)    | 0.839 (0.235)    | -         |     1.82 | EliGE, floppy, Grim, hallzerk, JT |
|            5 |     3788 | 2024-03-07 | OG            | L   | 0.188      | -            | -                | -                | -         |    -5.77 | EliGE, floppy, Grim, hallzerk, JT |
|            4 |     3877 | 2024-03-04 | Liquid        | W   | 0.169      | -            | -                | -                | -         |     2.22 | EliGE, floppy, Grim, hallzerk, JT |
|            3 |     3892 | 2024-03-03 | FURIA         | L   | 0.162      | -            | -                | -                | -         |    -2.06 | EliGE, floppy, Grim, hallzerk, JT |
|            2 |     3930 | 2024-03-02 | BOSS          | W   | 0.154      | -            | -                | -                | -         |     0.04 | EliGE, floppy, Grim, hallzerk, JT |
|            1 |     3949 | 2024-03-01 | Elevate       | W   | 0.148      | -            | -                | -                | -         |     0.12 | EliGE, floppy, Grim, hallzerk, JT |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($109,276.46)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.34) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $10,500.00     | $10,500.00      |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.860 | $50,000.00     | $42,995.37      |
| 2024-06-09 |      0.814 | $8,000.00      | $6,508.15       |
| 2024-06-02 |      0.768 | $4,000.00      | $3,070.74       |
| 2024-05-12 |      0.627 | $45,000.00     | $28,208.33      |
| 2024-03-31 |      0.348 | $20,000.00     | $6,953.70       |
| 2024-03-10 |      0.208 | $5,000.00      | $1,040.16       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
