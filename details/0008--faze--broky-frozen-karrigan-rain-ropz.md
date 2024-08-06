### Roster Details<br />
Team Name: FaZe<br />
Roster: broky, frozen, karrigan, rain, ropz<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1680.4<br />
<br />
Final Rank Value (1680.4) = Starting Rank Value (1676.5) + Head To Head Adjustments (3.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.830[<sup>1</sup>](#table2)
- Bounty Collected: 0.622[<sup>2</sup>](#table1)
- Opponent Network: 0.218[<sup>2</sup>](#table1)
- LAN Wins: 0.811[<sup>2</sup>](#table1)

The average of these factors is 0.620<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1676.5
- 400 + ( ( 0.620 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1676.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |      121 | 2024-08-02 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |   -20.61 | broky, frozen, karrigan, rain, ropz |
|           40 |      173 | 2024-08-01 | G2                | L   | 1.000      | -            | -                | -                | -         |    -6.12 | broky, frozen, karrigan, rain, ropz |
|           39 |      221 | 2024-07-31 | Cloud9            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.14 | broky, frozen, karrigan, rain, ropz |
|           38 |      590 | 2024-07-19 | Natus Vincere     | L   | 1.000      | -            | -                | -                | -         |    -7.29 | broky, frozen, karrigan, rain, ropz |
|           37 |      738 | 2024-07-17 | FlyQuest          | W   | 1.000      | 1.000        | 0.104 (0.104)    | 0.277 (0.277)    | 1 (1.000) |     1.51 | broky, frozen, karrigan, rain, ropz |
|           36 |     1118 | 2024-06-14 | Vitality          | L   | 0.846      | -            | -                | -                | -         |    -8.26 | broky, frozen, karrigan, rain, ropz |
|           35 |     1158 | 2024-06-13 | Natus Vincere     | L   | 0.839      | -            | -                | -                | -         |    -6.59 | broky, frozen, karrigan, rain, ropz |
|           34 |     1190 | 2024-06-12 | SAW               | W   | 0.832      | 0.729        | -                | 0.516 (0.313)    | 1 (0.832) |     1.09 | broky, frozen, karrigan, rain, ropz |
|           33 |     1666 | 2024-05-31 | G2                | L   | 0.755      | -            | -                | -                | -         |    -5.59 | broky, frozen, karrigan, rain, ropz |
|           32 |     1720 | 2024-05-29 | Spirit            | L   | 0.741      | -            | -                | -                | -         |    -6.31 | broky, frozen, karrigan, rain, ropz |
|           31 |     1743 | 2024-05-28 | Virtus.pro        | W   | 0.734      | 0.624        | 0.499 (0.229)    | 0.308 (0.141)    | 1 (0.734) |     9.45 | broky, frozen, karrigan, rain, ropz |
|           30 |     1767 | 2024-05-27 | M80               | W   | 0.728      | 0.624        | -                | 0.563 (0.256)    | 1 (0.728) |     1.41 | broky, frozen, karrigan, rain, ropz |
|           29 |     2292 | 2024-05-10 | Vitality          | L   | 0.614      | -            | -                | -                | -         |    -6.41 | broky, frozen, karrigan, rain, ropz |
|           28 |     2334 | 2024-05-08 | Natus Vincere     | W   | 0.601      | 0.889        | 1.000 (0.534)    | 0.357 (0.191)    | 1 (0.601) |    14.87 | broky, frozen, karrigan, rain, ropz |
|           27 |     2352 | 2024-05-07 | Monte             | W   | 0.594      | -            | -                | -                | 1 (0.594) |     0.37 | broky, frozen, karrigan, rain, ropz |
|           26 |     2584 | 2024-04-26 | Eternal Fire      | W   | 0.520      | 0.889        | 0.738 (0.341)    | 0.438 (0.202)    | 1 (0.520) |     7.72 | broky, frozen, karrigan, rain, ropz |
|           25 |     2613 | 2024-04-25 | Virtus.pro        | W   | 0.514      | 0.889        | 0.499 (0.228)    | -                | 1 (0.514) |     7.38 | broky, frozen, karrigan, rain, ropz |
|           24 |     2632 | 2024-04-24 | Astralis          | L   | 0.507      | -            | -                | -                | -         |    -7.45 | broky, frozen, karrigan, rain, ropz |
|           23 |     2650 | 2024-04-23 | Imperial          | W   | 0.500      | 0.889        | 0.233 (0.104)    | 0.658 (0.293)    | 1 (0.500) |     1.37 | broky, frozen, karrigan, rain, ropz |
|           22 |     2925 | 2024-04-14 | MOUZ              | W   | 0.438      | 0.624        | 1.000 (0.274)    | -                | -         |     9.75 | broky, frozen, karrigan, rain, ropz |
|           21 |     2939 | 2024-04-13 | Astralis          | W   | 0.432      | 0.624        | 0.389 (0.105)    | -                | -         |     7.49 | broky, frozen, karrigan, rain, ropz |
|           20 |     2953 | 2024-04-12 | Liquid            | W   | 0.425      | -            | -                | -                | -         |     5.00 | broky, frozen, karrigan, rain, ropz |
|           19 |     3026 | 2024-04-10 | FlyQuest          | W   | 0.412      | -            | -                | -                | -         |     0.67 | broky, frozen, karrigan, rain, ropz |
|           18 |     3042 | 2024-04-09 | Cloud9            | W   | 0.410      | -            | -                | -                | -         |     0.38 | broky, frozen, karrigan, rain, ropz |
|           17 |     3087 | 2024-04-09 | Astralis          | L   | 0.405      | -            | -                | -                | -         |    -5.84 | broky, frozen, karrigan, rain, ropz |
|           16 |     3118 | 2024-04-08 | Nemiga            | W   | 0.398      | 0.624        | -                | 0.704 (0.175)    | -         |     0.63 | broky, frozen, karrigan, rain, ropz |
|           15 |     3312 | 2024-03-31 | Natus Vincere     | L   | 0.347      | -            | -                | -                | -         |    -1.88 | broky, frozen, karrigan, rain, ropz |
|           14 |     3318 | 2024-03-30 | Vitality          | W   | 0.340      | 1.000        | 0.647 (0.220)    | -                | -         |     7.64 | broky, frozen, karrigan, rain, ropz |
|           13 |     3338 | 2024-03-28 | Spirit            | W   | 0.327      | 1.000        | 1.000 (0.327)    | 0.441 (0.144)    | -         |     8.08 | broky, frozen, karrigan, rain, ropz |
|           12 |     3422 | 2024-03-24 | Complexity        | W   | 0.299      | -            | -                | -                | -         |     4.33 | broky, frozen, karrigan, rain, ropz |
|           11 |     3436 | 2024-03-23 | Imperial          | W   | 0.292      | 1.000        | -                | 0.658 (0.192)    | -         |     0.84 | broky, frozen, karrigan, rain, ropz |
|           10 |     3450 | 2024-03-22 | Eternal Fire      | L   | 0.286      | -            | -                | -                | -         |    -4.19 | broky, frozen, karrigan, rain, ropz |
|            9 |     3460 | 2024-03-21 | FURIA             | W   | 0.281      | -            | -                | -                | -         |     4.85 | broky, frozen, karrigan, rain, ropz |
|            8 |     3472 | 2024-03-21 | HEROIC            | L   | 0.280      | -            | -                | -                | -         |    -5.76 | broky, frozen, karrigan, rain, ropz |
|            7 |     4264 | 2024-02-16 | Eternal Fire      | W   | 0.053      | -            | -                | -                | -         |     0.87 | broky, frozen, karrigan, rain, ropz |
|            6 |     4290 | 2024-02-15 | G2                | L   | 0.046      | -            | -                | -                | -         |    -0.20 | broky, frozen, karrigan, rain, ropz |
|            5 |     4323 | 2024-02-14 | Falcons           | W   | 0.040      | -            | -                | -                | -         |     0.24 | broky, frozen, karrigan, rain, ropz |
|            4 |     4339 | 2024-02-14 | 9 Pandas          | W   | 0.039      | -            | -                | -                | -         |     0.03 | broky, frozen, karrigan, rain, ropz |
|            3 |     4377 | 2024-02-11 | Spirit            | L   | 0.020      | -            | -                | -                | -         |    -0.14 | broky, frozen, karrigan, rain, ropz |
|            2 |     4388 | 2024-02-10 | MOUZ              | W   | 0.013      | -            | -                | -                | -         |     0.30 | broky, frozen, karrigan, rain, ropz |
|            1 |     4402 | 2024-02-09 | G2                | W   | 0.006      | -            | -                | -                | -         |     0.17 | broky, frozen, karrigan, rain, ropz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($199,882.87)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.62) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $8,500.00      | $8,500.00       |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-16 |      0.859 | $20,000.00     | $17,188.89      |
| 2024-06-02 |      0.767 | $10,000.00     | $7,672.22       |
| 2024-05-12 |      0.626 | $32,000.00     | $20,044.44      |
| 2024-04-14 |      0.438 | $100,000.00    | $43,849.54      |
| 2024-03-31 |      0.347 | $170,000.00    | $59,027.78      |
| 2024-02-11 |      0.020 | $180,000.00    | $3,600.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
