### Roster Details<br />
Team Name: Complexity<br />
Roster: EliGE, floppy, Grim, hallzerk, JT<br />
Global Rank: [14](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [3]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1570.3<br />
<br />
Final Rank Value (1570.3) = Starting Rank Value (1652.4) + Head To Head Adjustments (-82.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.682[<sup>1</sup>](#table2)
- Bounty Collected: 0.589[<sup>2</sup>](#table1)
- Opponent Network: 0.229[<sup>2</sup>](#table1)
- LAN Wins: 0.946[<sup>2</sup>](#table1)

The average of these factors is 0.612<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1652.4
- 400 + ( ( 0.612 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1652.4


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
|           34 |       21 | 2024-08-04 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -4.13 | EliGE, floppy, Grim, hallzerk, JT |
|           33 |       70 | 2024-08-03 | Spirit        | L   | 1.000      | -            | -                | -                | -         |    -3.87 | EliGE, floppy, Grim, hallzerk, JT |
|           32 |      102 | 2024-08-02 | HEROIC        | W   | 1.000      | 0.581        | 0.225 (0.131)    | 0.370 (0.215)    | 1 (1.000) |    15.52 | EliGE, floppy, Grim, hallzerk, JT |
|           31 |      232 | 2024-07-30 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.37 | EliGE, floppy, Grim, hallzerk, JT |
|           30 |      262 | 2024-07-29 | HEROIC        | L   | 1.000      | -            | -                | -                | -         |   -15.76 | EliGE, floppy, Grim, hallzerk, JT |
|           29 |      634 | 2024-07-18 | M80           | L   | 1.000      | -            | -                | -                | -         |   -27.39 | EliGE, floppy, Grim, hallzerk, JT |
|           28 |      686 | 2024-07-17 | Virtus.pro    | L   | 1.000      | -            | -                | -                | -         |   -13.03 | EliGE, floppy, Grim, hallzerk, JT |
|           27 |     1018 | 2024-06-16 | Falcons       | W   | 0.867      | 0.500        | 0.222 (0.096)    | -                | 1 (0.867) |     7.52 | EliGE, floppy, Grim, hallzerk, JT |
|           26 |     1027 | 2024-06-16 | Aurora        | W   | 0.865      | 0.500        | 0.422 (0.183)    | 0.788 (0.341)    | 1 (0.865) |     7.65 | EliGE, floppy, Grim, hallzerk, JT |
|           25 |     1057 | 2024-06-15 | MIBR          | W   | 0.859      | 0.500        | 0.208 (0.090)    | 0.657 (0.282)    | 1 (0.859) |     6.61 | EliGE, floppy, Grim, hallzerk, JT |
|           24 |     1087 | 2024-06-14 | ENCE          | L   | 0.854      | -            | -                | -                | -         |   -21.38 | EliGE, floppy, Grim, hallzerk, JT |
|           23 |     1099 | 2024-06-14 | Alliance      | W   | 0.853      | -            | -                | -                | 1 (0.853) |     0.38 | EliGE, floppy, Grim, hallzerk, JT |
|           22 |     1419 | 2024-06-06 | FURIA         | L   | 0.801      | -            | -                | -                | -         |   -13.72 | EliGE, floppy, Grim, hallzerk, JT |
|           21 |     1439 | 2024-06-06 | BetBoom       | L   | 0.800      | -            | -                | -                | -         |   -20.26 | EliGE, floppy, Grim, hallzerk, JT |
|           20 |     1451 | 2024-06-06 | fnatic        | L   | 0.799      | -            | -                | -                | -         |   -19.02 | EliGE, floppy, Grim, hallzerk, JT |
|           19 |     1495 | 2024-06-05 | BIG           | W   | 0.794      | 0.715        | 0.155 (0.088)    | 0.302 (0.171)    | 1 (0.794) |     3.37 | EliGE, floppy, Grim, hallzerk, JT |
|           18 |     1508 | 2024-06-05 | Eternal Fire  | W   | 0.792      | 0.715        | 0.740 (0.419)    | 0.455 (0.258)    | 1 (0.792) |    13.30 | EliGE, floppy, Grim, hallzerk, JT |
|           17 |     1730 | 2024-05-27 | MOUZ          | L   | 0.737      | -            | -                | -                | -         |    -5.06 | EliGE, floppy, Grim, hallzerk, JT |
|           16 |     1740 | 2024-05-27 | Liquid        | L   | 0.735      | -            | -                | -                | -         |   -13.53 | EliGE, floppy, Grim, hallzerk, JT |
|           15 |     2235 | 2024-05-11 | MOUZ          | L   | 0.628      | -            | -                | -                | -         |    -4.95 | EliGE, floppy, Grim, hallzerk, JT |
|           14 |     2286 | 2024-05-09 | Virtus.pro    | W   | 0.614      | 0.889        | 0.498 (0.271)    | 0.321 (0.175)    | 1 (0.614) |    10.21 | EliGE, floppy, Grim, hallzerk, JT |
|           13 |     2354 | 2024-05-05 | Natus Vincere | W   | 0.588      | 0.889        | 1.000 (0.523)    | 0.370 (0.193)    | 1 (0.588) |    15.84 | EliGE, floppy, Grim, hallzerk, JT |
|           12 |     2421 | 2024-05-02 | HEROIC        | W   | 0.567      | 0.889        | 0.225 (0.114)    | 0.370 (0.186)    | -         |     7.19 | EliGE, floppy, Grim, hallzerk, JT |
|           11 |     2468 | 2024-04-30 | PERA          | W   | 0.554      | 0.889        | -                | 0.451 (0.222)    | -         |     0.28 | EliGE, floppy, Grim, hallzerk, JT |
|           10 |     3392 | 2024-03-24 | FaZe          | L   | 0.306      | -            | -                | -                | -         |    -4.39 | EliGE, floppy, Grim, hallzerk, JT |
|            9 |     3402 | 2024-03-23 | Vitality      | L   | 0.301      | -            | -                | -                | -         |    -2.32 | EliGE, floppy, Grim, hallzerk, JT |
|            8 |     3417 | 2024-03-22 | MOUZ          | L   | 0.294      | -            | -                | -                | -         |    -2.30 | EliGE, floppy, Grim, hallzerk, JT |
|            7 |     3435 | 2024-03-21 | HEROIC        | W   | 0.288      | -            | -                | -                | -         |     3.57 | EliGE, floppy, Grim, hallzerk, JT |
|            6 |     3444 | 2024-03-21 | paiN          | W   | 0.287      | 1.000        | 0.325 (0.093)    | 0.867 (0.249)    | -         |     1.90 | EliGE, floppy, Grim, hallzerk, JT |
|            5 |     3761 | 2024-03-07 | OG            | L   | 0.195      | -            | -                | -                | -         |    -5.99 | EliGE, floppy, Grim, hallzerk, JT |
|            4 |     3850 | 2024-03-04 | Liquid        | W   | 0.176      | -            | -                | -                | -         |     2.31 | EliGE, floppy, Grim, hallzerk, JT |
|            3 |     3865 | 2024-03-03 | FURIA         | L   | 0.169      | -            | -                | -                | -         |    -2.14 | EliGE, floppy, Grim, hallzerk, JT |
|            2 |     3903 | 2024-03-02 | BOSS          | W   | 0.161      | -            | -                | -                | -         |     0.05 | EliGE, floppy, Grim, hallzerk, JT |
|            1 |     3922 | 2024-03-01 | Elevate       | W   | 0.155      | -            | -                | -                | -         |     0.13 | EliGE, floppy, Grim, hallzerk, JT |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($110,205.35)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.34) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $10,500.00     | $10,500.00      |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.867 | $50,000.00     | $43,347.22      |
| 2024-06-09 |      0.821 | $8,000.00      | $6,564.44       |
| 2024-06-02 |      0.775 | $4,000.00      | $3,098.89       |
| 2024-05-12 |      0.634 | $45,000.00     | $28,525.00      |
| 2024-03-31 |      0.355 | $20,000.00     | $7,094.44       |
| 2024-03-10 |      0.215 | $5,000.00      | $1,075.35       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
