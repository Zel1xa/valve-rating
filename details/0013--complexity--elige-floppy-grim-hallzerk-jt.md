### Roster Details<br />
Team Name: Complexity<br />
Roster: EliGE, floppy, Grim, hallzerk, JT<br />
Global Rank: [13](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [3]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1565.7<br />
<br />
Final Rank Value (1565.7) = Starting Rank Value (1651.1) + Head To Head Adjustments (-85.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.665[<sup>1</sup>](#table2)
- Bounty Collected: 0.593[<sup>2</sup>](#table1)
- Opponent Network: 0.239[<sup>2</sup>](#table1)
- LAN Wins: 0.949[<sup>2</sup>](#table1)

The average of these factors is 0.611<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1651.1
- 400 + ( ( 0.611 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1651.1


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
|           34 |       16 | 2024-08-03 | Spirit        | L   | 1.000      | -            | -                | -                | -         |    -3.65 | EliGE, floppy, Grim, hallzerk, JT |
|           33 |       44 | 2024-08-02 | HEROIC        | W   | 1.000      | 0.581        | 0.230 (0.134)    | 0.388 (0.226)    | 1 (1.000) |    15.56 | EliGE, floppy, Grim, hallzerk, JT |
|           32 |      157 | 2024-07-30 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.37 | EliGE, floppy, Grim, hallzerk, JT |
|           31 |      187 | 2024-07-29 | HEROIC        | L   | 1.000      | -            | -                | -                | -         |   -15.72 | EliGE, floppy, Grim, hallzerk, JT |
|           30 |      559 | 2024-07-18 | M80           | L   | 1.000      | -            | -                | -                | -         |   -27.13 | EliGE, floppy, Grim, hallzerk, JT |
|           29 |      611 | 2024-07-17 | Virtus.pro    | L   | 1.000      | -            | -                | -                | -         |   -12.84 | EliGE, floppy, Grim, hallzerk, JT |
|           28 |      927 | 2024-06-16 | Falcons       | W   | 0.879      | 0.500        | 0.225 (0.099)    | -                | 1 (0.879) |     8.07 | EliGE, floppy, Grim, hallzerk, JT |
|           27 |      937 | 2024-06-16 | Aurora        | W   | 0.878      | 0.500        | 0.425 (0.186)    | 0.809 (0.355)    | 1 (0.878) |     7.91 | EliGE, floppy, Grim, hallzerk, JT |
|           26 |      961 | 2024-06-15 | MIBR          | W   | 0.872      | 0.500        | 0.210 (0.091)    | 0.682 (0.297)    | 1 (0.872) |     6.71 | EliGE, floppy, Grim, hallzerk, JT |
|           25 |      984 | 2024-06-14 | ENCE          | L   | 0.866      | -            | -                | -                | -         |   -21.93 | EliGE, floppy, Grim, hallzerk, JT |
|           24 |      996 | 2024-06-14 | Alliance      | W   | 0.865      | -            | -                | -                | 1 (0.865) |     0.41 | EliGE, floppy, Grim, hallzerk, JT |
|           23 |     1306 | 2024-06-06 | FURIA         | L   | 0.813      | -            | -                | -                | -         |   -14.06 | EliGE, floppy, Grim, hallzerk, JT |
|           22 |     1326 | 2024-06-06 | BetBoom       | L   | 0.812      | -            | -                | -                | -         |   -20.45 | EliGE, floppy, Grim, hallzerk, JT |
|           21 |     1338 | 2024-06-06 | fnatic        | L   | 0.811      | -            | -                | -                | -         |   -22.14 | EliGE, floppy, Grim, hallzerk, JT |
|           20 |     1381 | 2024-06-05 | BIG           | W   | 0.806      | 0.715        | 0.156 (0.090)    | 0.316 (0.182)    | 1 (0.806) |     3.60 | EliGE, floppy, Grim, hallzerk, JT |
|           19 |     1395 | 2024-06-05 | Eternal Fire  | W   | 0.804      | 0.715        | 0.746 (0.429)    | 0.474 (0.273)    | 1 (0.804) |    13.65 | EliGE, floppy, Grim, hallzerk, JT |
|           18 |     1614 | 2024-05-27 | MOUZ          | L   | 0.749      | -            | -                | -                | -         |    -6.11 | EliGE, floppy, Grim, hallzerk, JT |
|           17 |     1624 | 2024-05-27 | Liquid        | L   | 0.747      | -            | -                | -                | -         |   -15.78 | EliGE, floppy, Grim, hallzerk, JT |
|           16 |     2117 | 2024-05-11 | MOUZ          | L   | 0.640      | -            | -                | -                | -         |    -6.16 | EliGE, floppy, Grim, hallzerk, JT |
|           15 |     2168 | 2024-05-09 | Virtus.pro    | W   | 0.626      | 0.889        | 0.496 (0.276)    | 0.335 (0.187)    | 1 (0.626) |    10.37 | EliGE, floppy, Grim, hallzerk, JT |
|           14 |     2235 | 2024-05-05 | Natus Vincere | W   | 0.600      | 0.889        | 1.000 (0.534)    | 0.343 (0.183)    | 1 (0.600) |    16.24 | EliGE, floppy, Grim, hallzerk, JT |
|           13 |     2302 | 2024-05-02 | HEROIC        | W   | 0.579      | 0.889        | 0.230 (0.118)    | 0.388 (0.200)    | -         |     7.30 | EliGE, floppy, Grim, hallzerk, JT |
|           12 |     2349 | 2024-04-30 | PERA          | W   | 0.566      | 0.889        | -                | 0.468 (0.235)    | -         |     0.28 | EliGE, floppy, Grim, hallzerk, JT |
|           11 |     3269 | 2024-03-24 | FaZe          | L   | 0.319      | -            | -                | -                | -         |    -4.37 | EliGE, floppy, Grim, hallzerk, JT |
|           10 |     3278 | 2024-03-23 | Vitality      | L   | 0.313      | -            | -                | -                | -         |    -2.34 | EliGE, floppy, Grim, hallzerk, JT |
|            9 |     3292 | 2024-03-22 | MOUZ          | L   | 0.306      | -            | -                | -                | -         |    -2.99 | EliGE, floppy, Grim, hallzerk, JT |
|            8 |     3310 | 2024-03-21 | HEROIC        | W   | 0.300      | -            | -                | -                | -         |     3.80 | EliGE, floppy, Grim, hallzerk, JT |
|            7 |     3319 | 2024-03-21 | paiN          | W   | 0.299      | 1.000        | 0.324 (0.097)    | 0.859 (0.257)    | -         |     1.66 | EliGE, floppy, Grim, hallzerk, JT |
|            6 |     3633 | 2024-03-07 | OG            | L   | 0.207      | -            | -                | -                | -         |    -6.37 | EliGE, floppy, Grim, hallzerk, JT |
|            5 |     3722 | 2024-03-04 | Liquid        | W   | 0.188      | -            | -                | -                | -         |     1.80 | EliGE, floppy, Grim, hallzerk, JT |
|            4 |     3737 | 2024-03-03 | FURIA         | L   | 0.181      | -            | -                | -                | -         |    -2.30 | EliGE, floppy, Grim, hallzerk, JT |
|            3 |     3775 | 2024-03-02 | BOSS          | W   | 0.173      | -            | -                | -                | -         |     0.05 | EliGE, floppy, Grim, hallzerk, JT |
|            2 |     3794 | 2024-03-01 | Elevate       | W   | 0.167      | -            | -                | -                | -         |     0.10 | EliGE, floppy, Grim, hallzerk, JT |
|            1 |     4282 | 2024-02-05 | Falcons       | L   | 0.000      | -            | -                | -                | -         |    -0.01 | EliGE, floppy, Grim, hallzerk, JT |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($101,961.09)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.31) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.879 | $50,000.00     | $43,960.65      |
| 2024-06-09 |      0.833 | $8,000.00      | $6,662.59       |
| 2024-06-02 |      0.787 | $4,000.00      | $3,147.96       |
| 2024-05-12 |      0.646 | $45,000.00     | $29,077.08      |
| 2024-03-31 |      0.367 | $20,000.00     | $7,339.81       |
| 2024-03-10 |      0.227 | $5,000.00      | $1,136.69       |
| 2024-02-11 |      0.040 | $16,000.00     | $636.30         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
