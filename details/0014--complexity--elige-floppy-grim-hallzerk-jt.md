### Roster Details<br />
Team Name: Complexity<br />
Roster: EliGE, floppy, Grim, hallzerk, JT<br />
Global Rank: [14](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [3]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1570.8<br />
<br />
Final Rank Value (1570.8) = Starting Rank Value (1653.4) + Head To Head Adjustments (-82.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.682[<sup>1</sup>](#table2)
- Bounty Collected: 0.590[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
- LAN Wins: 0.947[<sup>2</sup>](#table1)

The average of these factors is 0.613<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1653.4
- 400 + ( ( 0.613 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1653.4


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
|           34 |        8 | 2024-08-04 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -4.14 | EliGE, floppy, Grim, hallzerk, JT |
|           33 |       57 | 2024-08-03 | Spirit        | L   | 1.000      | -            | -                | -                | -         |    -3.87 | EliGE, floppy, Grim, hallzerk, JT |
|           32 |       89 | 2024-08-02 | HEROIC        | W   | 1.000      | 0.581        | 0.226 (0.131)    | 0.372 (0.216)    | 1 (1.000) |    15.51 | EliGE, floppy, Grim, hallzerk, JT |
|           31 |      219 | 2024-07-30 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.37 | EliGE, floppy, Grim, hallzerk, JT |
|           30 |      250 | 2024-07-29 | HEROIC        | L   | 1.000      | -            | -                | -                | -         |   -15.77 | EliGE, floppy, Grim, hallzerk, JT |
|           29 |      621 | 2024-07-18 | M80           | L   | 1.000      | -            | -                | -                | -         |   -27.39 | EliGE, floppy, Grim, hallzerk, JT |
|           28 |      673 | 2024-07-17 | Virtus.pro    | L   | 1.000      | -            | -                | -                | -         |   -13.02 | EliGE, floppy, Grim, hallzerk, JT |
|           27 |     1005 | 2024-06-16 | Falcons       | W   | 0.870      | 0.500        | 0.223 (0.097)    | -                | 1 (0.870) |     7.57 | EliGE, floppy, Grim, hallzerk, JT |
|           26 |     1014 | 2024-06-16 | Aurora        | W   | 0.869      | 0.500        | 0.423 (0.184)    | 0.792 (0.344)    | 1 (0.869) |     7.63 | EliGE, floppy, Grim, hallzerk, JT |
|           25 |     1044 | 2024-06-15 | MIBR          | W   | 0.863      | 0.500        | 0.209 (0.090)    | 0.659 (0.284)    | 1 (0.863) |     6.65 | EliGE, floppy, Grim, hallzerk, JT |
|           24 |     1074 | 2024-06-14 | ENCE          | L   | 0.857      | -            | -                | -                | -         |   -21.49 | EliGE, floppy, Grim, hallzerk, JT |
|           23 |     1086 | 2024-06-14 | Alliance      | W   | 0.856      | -            | -                | -                | 1 (0.856) |     0.38 | EliGE, floppy, Grim, hallzerk, JT |
|           22 |     1406 | 2024-06-06 | FURIA         | L   | 0.804      | -            | -                | -                | -         |   -13.86 | EliGE, floppy, Grim, hallzerk, JT |
|           21 |     1426 | 2024-06-06 | BetBoom       | L   | 0.803      | -            | -                | -                | -         |   -20.36 | EliGE, floppy, Grim, hallzerk, JT |
|           20 |     1438 | 2024-06-06 | fnatic        | L   | 0.802      | -            | -                | -                | -         |   -19.13 | EliGE, floppy, Grim, hallzerk, JT |
|           19 |     1482 | 2024-06-05 | BIG           | W   | 0.797      | 0.715        | 0.155 (0.088)    | 0.303 (0.173)    | 1 (0.797) |     3.37 | EliGE, floppy, Grim, hallzerk, JT |
|           18 |     1495 | 2024-06-05 | Eternal Fire  | W   | 0.795      | 0.715        | 0.741 (0.422)    | 0.457 (0.260)    | 1 (0.795) |    13.35 | EliGE, floppy, Grim, hallzerk, JT |
|           17 |     1717 | 2024-05-27 | MOUZ          | L   | 0.740      | -            | -                | -                | -         |    -5.11 | EliGE, floppy, Grim, hallzerk, JT |
|           16 |     1727 | 2024-05-27 | Liquid        | L   | 0.738      | -            | -                | -                | -         |   -13.61 | EliGE, floppy, Grim, hallzerk, JT |
|           15 |     2222 | 2024-05-11 | MOUZ          | L   | 0.631      | -            | -                | -                | -         |    -5.01 | EliGE, floppy, Grim, hallzerk, JT |
|           14 |     2273 | 2024-05-09 | Virtus.pro    | W   | 0.617      | 0.889        | 0.497 (0.273)    | 0.323 (0.177)    | 1 (0.617) |    10.26 | EliGE, floppy, Grim, hallzerk, JT |
|           13 |     2341 | 2024-05-05 | Natus Vincere | W   | 0.591      | 0.889        | 1.000 (0.526)    | 0.371 (0.195)    | 1 (0.591) |    15.92 | EliGE, floppy, Grim, hallzerk, JT |
|           12 |     2408 | 2024-05-02 | HEROIC        | W   | 0.570      | 0.889        | 0.226 (0.114)    | 0.372 (0.189)    | -         |     7.22 | EliGE, floppy, Grim, hallzerk, JT |
|           11 |     2455 | 2024-04-30 | PERA          | W   | 0.557      | 0.889        | -                | 0.453 (0.224)    | -         |     0.28 | EliGE, floppy, Grim, hallzerk, JT |
|           10 |     3379 | 2024-03-24 | FaZe          | L   | 0.310      | -            | -                | -                | -         |    -4.42 | EliGE, floppy, Grim, hallzerk, JT |
|            9 |     3389 | 2024-03-23 | Vitality      | L   | 0.304      | -            | -                | -                | -         |    -2.35 | EliGE, floppy, Grim, hallzerk, JT |
|            8 |     3404 | 2024-03-22 | MOUZ          | L   | 0.297      | -            | -                | -                | -         |    -2.34 | EliGE, floppy, Grim, hallzerk, JT |
|            7 |     3422 | 2024-03-21 | HEROIC        | W   | 0.292      | -            | -                | -                | -         |     3.60 | EliGE, floppy, Grim, hallzerk, JT |
|            6 |     3431 | 2024-03-21 | paiN          | W   | 0.290      | 1.000        | 0.326 (0.095)    | 0.868 (0.252)    | -         |     1.93 | EliGE, floppy, Grim, hallzerk, JT |
|            5 |     3748 | 2024-03-07 | OG            | L   | 0.198      | -            | -                | -                | -         |    -6.09 | EliGE, floppy, Grim, hallzerk, JT |
|            4 |     3837 | 2024-03-04 | Liquid        | W   | 0.179      | -            | -                | -                | -         |     2.35 | EliGE, floppy, Grim, hallzerk, JT |
|            3 |     3852 | 2024-03-03 | FURIA         | L   | 0.172      | -            | -                | -                | -         |    -2.20 | EliGE, floppy, Grim, hallzerk, JT |
|            2 |     3890 | 2024-03-02 | BOSS          | W   | 0.164      | -            | -                | -                | -         |     0.05 | EliGE, floppy, Grim, hallzerk, JT |
|            1 |     3909 | 2024-03-01 | Elevate       | W   | 0.158      | -            | -                | -                | -         |     0.13 | EliGE, floppy, Grim, hallzerk, JT |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($110,645.35)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.34) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $10,500.00     | $10,500.00      |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.870 | $50,000.00     | $43,513.89      |
| 2024-06-09 |      0.824 | $8,000.00      | $6,591.11       |
| 2024-06-02 |      0.778 | $4,000.00      | $3,112.22       |
| 2024-05-12 |      0.637 | $45,000.00     | $28,675.00      |
| 2024-03-31 |      0.358 | $20,000.00     | $7,161.11       |
| 2024-03-10 |      0.218 | $5,000.00      | $1,092.01       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
