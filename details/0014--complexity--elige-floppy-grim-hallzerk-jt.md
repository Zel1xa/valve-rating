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
Final Rank Value (1569.2) = Starting Rank Value (1650.8) + Head To Head Adjustments (-81.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.682[<sup>1</sup>](#table2)
- Bounty Collected: 0.588[<sup>2</sup>](#table1)
- Opponent Network: 0.219[<sup>2</sup>](#table1)
- LAN Wins: 0.944[<sup>2</sup>](#table1)

The average of these factors is 0.608<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1650.8
- 400 + ( ( 0.608 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1650.8


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
|           34 |       40 | 2024-08-04 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -4.12 | EliGE, floppy, Grim, hallzerk, JT |
|           33 |       89 | 2024-08-03 | Spirit        | L   | 1.000      | -            | -                | -                | -         |    -3.86 | EliGE, floppy, Grim, hallzerk, JT |
|           32 |      121 | 2024-08-02 | HEROIC        | W   | 1.000      | 0.581        | 0.225 (0.130)    | 0.355 (0.206)    | 1 (1.000) |    15.46 | EliGE, floppy, Grim, hallzerk, JT |
|           31 |      251 | 2024-07-30 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.37 | EliGE, floppy, Grim, hallzerk, JT |
|           30 |      281 | 2024-07-29 | HEROIC        | L   | 1.000      | -            | -                | -                | -         |   -15.82 | EliGE, floppy, Grim, hallzerk, JT |
|           29 |      653 | 2024-07-18 | M80           | L   | 1.000      | -            | -                | -                | -         |   -27.41 | EliGE, floppy, Grim, hallzerk, JT |
|           28 |      705 | 2024-07-17 | Virtus.pro    | L   | 1.000      | -            | -                | -                | -         |   -13.07 | EliGE, floppy, Grim, hallzerk, JT |
|           27 |     1037 | 2024-06-16 | Falcons       | W   | 0.861      | 0.500        | 0.220 (0.095)    | -                | 1 (0.861) |     7.46 | EliGE, floppy, Grim, hallzerk, JT |
|           26 |     1046 | 2024-06-16 | Aurora        | W   | 0.859      | 0.500        | 0.421 (0.181)    | 0.759 (0.326)    | 1 (0.859) |     7.82 | EliGE, floppy, Grim, hallzerk, JT |
|           25 |     1076 | 2024-06-15 | MIBR          | W   | 0.853      | 0.500        | 0.208 (0.089)    | 0.633 (0.270)    | 1 (0.853) |     6.51 | EliGE, floppy, Grim, hallzerk, JT |
|           24 |     1106 | 2024-06-14 | ENCE          | L   | 0.848      | -            | -                | -                | -         |   -21.11 | EliGE, floppy, Grim, hallzerk, JT |
|           23 |     1118 | 2024-06-14 | Alliance      | W   | 0.847      | -            | -                | -                | 1 (0.847) |     0.38 | EliGE, floppy, Grim, hallzerk, JT |
|           22 |     1438 | 2024-06-06 | FURIA         | L   | 0.795      | -            | -                | -                | -         |   -13.58 | EliGE, floppy, Grim, hallzerk, JT |
|           21 |     1458 | 2024-06-06 | BetBoom       | L   | 0.794      | -            | -                | -                | -         |   -20.10 | EliGE, floppy, Grim, hallzerk, JT |
|           20 |     1470 | 2024-06-06 | fnatic        | L   | 0.793      | -            | -                | -                | -         |   -18.84 | EliGE, floppy, Grim, hallzerk, JT |
|           19 |     1514 | 2024-06-05 | BIG           | W   | 0.787      | 0.715        | 0.154 (0.087)    | 0.290 (0.163)    | 1 (0.787) |     3.35 | EliGE, floppy, Grim, hallzerk, JT |
|           18 |     1527 | 2024-06-05 | Eternal Fire  | W   | 0.786      | 0.715        | 0.739 (0.415)    | 0.438 (0.246)    | 1 (0.786) |    13.25 | EliGE, floppy, Grim, hallzerk, JT |
|           17 |     1749 | 2024-05-27 | MOUZ          | L   | 0.730      | -            | -                | -                | -         |    -5.04 | EliGE, floppy, Grim, hallzerk, JT |
|           16 |     1759 | 2024-05-27 | Liquid        | L   | 0.729      | -            | -                | -                | -         |   -13.38 | EliGE, floppy, Grim, hallzerk, JT |
|           15 |     2254 | 2024-05-11 | MOUZ          | L   | 0.622      | -            | -                | -                | -         |    -4.93 | EliGE, floppy, Grim, hallzerk, JT |
|           14 |     2305 | 2024-05-09 | Virtus.pro    | W   | 0.608      | 0.889        | 0.498 (0.269)    | 0.309 (0.167)    | 1 (0.608) |    10.10 | EliGE, floppy, Grim, hallzerk, JT |
|           13 |     2373 | 2024-05-05 | Natus Vincere | W   | 0.582      | 0.889        | 1.000 (0.517)    | 0.357 (0.185)    | 1 (0.582) |    15.69 | EliGE, floppy, Grim, hallzerk, JT |
|           12 |     2440 | 2024-05-02 | HEROIC        | W   | 0.561      | 0.889        | 0.225 (0.112)    | 0.355 (0.177)    | -         |     7.07 | EliGE, floppy, Grim, hallzerk, JT |
|           11 |     2487 | 2024-04-30 | PERA          | W   | 0.548      | 0.889        | -                | 0.435 (0.212)    | -         |     0.28 | EliGE, floppy, Grim, hallzerk, JT |
|           10 |     3411 | 2024-03-24 | FaZe          | L   | 0.300      | -            | -                | -                | -         |    -4.34 | EliGE, floppy, Grim, hallzerk, JT |
|            9 |     3421 | 2024-03-23 | Vitality      | L   | 0.295      | -            | -                | -                | -         |    -2.27 | EliGE, floppy, Grim, hallzerk, JT |
|            8 |     3436 | 2024-03-22 | MOUZ          | L   | 0.288      | -            | -                | -                | -         |    -2.26 | EliGE, floppy, Grim, hallzerk, JT |
|            7 |     3454 | 2024-03-21 | HEROIC        | W   | 0.282      | -            | -                | -                | -         |     3.47 | EliGE, floppy, Grim, hallzerk, JT |
|            6 |     3463 | 2024-03-21 | paiN          | W   | 0.281      | 1.000        | 0.324 (0.091)    | 0.838 (0.235)    | -         |     1.83 | EliGE, floppy, Grim, hallzerk, JT |
|            5 |     3780 | 2024-03-07 | OG            | L   | 0.189      | -            | -                | -                | -         |    -5.80 | EliGE, floppy, Grim, hallzerk, JT |
|            4 |     3869 | 2024-03-04 | Liquid        | W   | 0.169      | -            | -                | -                | -         |     2.23 | EliGE, floppy, Grim, hallzerk, JT |
|            3 |     3884 | 2024-03-03 | FURIA         | L   | 0.162      | -            | -                | -                | -         |    -2.07 | EliGE, floppy, Grim, hallzerk, JT |
|            2 |     3922 | 2024-03-02 | BOSS          | W   | 0.155      | -            | -                | -                | -         |     0.04 | EliGE, floppy, Grim, hallzerk, JT |
|            1 |     3941 | 2024-03-01 | Elevate       | W   | 0.149      | -            | -                | -                | -         |     0.12 | EliGE, floppy, Grim, hallzerk, JT |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($109,398.68)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.34) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $10,500.00     | $10,500.00      |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.861 | $50,000.00     | $43,041.67      |
| 2024-06-09 |      0.814 | $8,000.00      | $6,515.56       |
| 2024-06-02 |      0.769 | $4,000.00      | $3,074.44       |
| 2024-05-12 |      0.628 | $45,000.00     | $28,250.00      |
| 2024-03-31 |      0.349 | $20,000.00     | $6,972.22       |
| 2024-03-10 |      0.209 | $5,000.00      | $1,044.79       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
