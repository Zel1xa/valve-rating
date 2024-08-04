### Roster Details<br />
Team Name: Complexity<br />
Roster: EliGE, floppy, Grim, hallzerk, JT<br />
Global Rank: [14](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [3]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1567.3<br />
<br />
Final Rank Value (1567.3) = Starting Rank Value (1644.8) + Head To Head Adjustments (-77.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.663[<sup>1</sup>](#table2)
- Bounty Collected: 0.592[<sup>2</sup>](#table1)
- Opponent Network: 0.232[<sup>2</sup>](#table1)
- LAN Wins: 0.949[<sup>2</sup>](#table1)

The average of these factors is 0.609<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1644.8
- 400 + ( ( 0.609 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1644.8


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
|           33 |       19 | 2024-08-03 | Spirit        | L   | 1.000      | -            | -                | -                | -         |    -3.75 | EliGE, floppy, Grim, hallzerk, JT |
|           32 |       52 | 2024-08-02 | HEROIC        | W   | 1.000      | 0.581        | 0.229 (0.133)    | 0.375 (0.218)    | 1 (1.000) |    15.70 | EliGE, floppy, Grim, hallzerk, JT |
|           31 |      180 | 2024-07-30 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.43 | EliGE, floppy, Grim, hallzerk, JT |
|           30 |      210 | 2024-07-29 | HEROIC        | L   | 1.000      | -            | -                | -                | -         |   -15.56 | EliGE, floppy, Grim, hallzerk, JT |
|           29 |      582 | 2024-07-18 | M80           | L   | 1.000      | -            | -                | -                | -         |   -27.18 | EliGE, floppy, Grim, hallzerk, JT |
|           28 |      637 | 2024-07-17 | Virtus.pro    | L   | 1.000      | -            | -                | -                | -         |   -12.80 | EliGE, floppy, Grim, hallzerk, JT |
|           27 |      965 | 2024-06-16 | Falcons       | W   | 0.877      | 0.500        | 0.225 (0.099)    | -                | 1 (0.877) |     7.90 | EliGE, floppy, Grim, hallzerk, JT |
|           26 |      974 | 2024-06-16 | Aurora        | W   | 0.876      | 0.500        | 0.424 (0.186)    | 0.794 (0.348)    | 1 (0.876) |     7.80 | EliGE, floppy, Grim, hallzerk, JT |
|           25 |     1004 | 2024-06-15 | MIBR          | W   | 0.870      | 0.500        | 0.210 (0.091)    | 0.659 (0.287)    | 1 (0.870) |     7.00 | EliGE, floppy, Grim, hallzerk, JT |
|           24 |     1034 | 2024-06-14 | ENCE          | L   | 0.865      | -            | -                | -                | -         |   -21.65 | EliGE, floppy, Grim, hallzerk, JT |
|           23 |     1046 | 2024-06-14 | Alliance      | W   | 0.863      | -            | -                | -                | 1 (0.863) |     0.40 | EliGE, floppy, Grim, hallzerk, JT |
|           22 |     1366 | 2024-06-06 | FURIA         | L   | 0.812      | -            | -                | -                | -         |   -13.81 | EliGE, floppy, Grim, hallzerk, JT |
|           21 |     1386 | 2024-06-06 | BetBoom       | L   | 0.810      | -            | -                | -                | -         |   -20.29 | EliGE, floppy, Grim, hallzerk, JT |
|           20 |     1398 | 2024-06-06 | fnatic        | L   | 0.810      | -            | -                | -                | -         |   -19.11 | EliGE, floppy, Grim, hallzerk, JT |
|           19 |     1442 | 2024-06-05 | BIG           | W   | 0.804      | 0.715        | 0.155 (0.089)    | 0.305 (0.175)    | 1 (0.804) |     3.58 | EliGE, floppy, Grim, hallzerk, JT |
|           18 |     1455 | 2024-06-05 | Eternal Fire  | W   | 0.803      | 0.715        | 0.743 (0.427)    | 0.458 (0.263)    | 1 (0.803) |    13.71 | EliGE, floppy, Grim, hallzerk, JT |
|           17 |     1677 | 2024-05-27 | MOUZ          | L   | 0.747      | -            | -                | -                | -         |    -4.97 | EliGE, floppy, Grim, hallzerk, JT |
|           16 |     1687 | 2024-05-27 | Liquid        | L   | 0.746      | -            | -                | -                | -         |   -15.74 | EliGE, floppy, Grim, hallzerk, JT |
|           15 |     2182 | 2024-05-11 | MOUZ          | L   | 0.639      | -            | -                | -                | -         |    -4.93 | EliGE, floppy, Grim, hallzerk, JT |
|           14 |     2233 | 2024-05-09 | Virtus.pro    | W   | 0.624      | 0.889        | 0.496 (0.275)    | 0.324 (0.180)    | 1 (0.624) |    10.55 | EliGE, floppy, Grim, hallzerk, JT |
|           13 |     2301 | 2024-05-05 | Natus Vincere | W   | 0.599      | 0.889        | 1.000 (0.532)    | 0.331 (0.176)    | 1 (0.599) |    16.19 | EliGE, floppy, Grim, hallzerk, JT |
|           12 |     2368 | 2024-05-02 | HEROIC        | W   | 0.578      | 0.889        | 0.229 (0.118)    | 0.375 (0.192)    | -         |     7.49 | EliGE, floppy, Grim, hallzerk, JT |
|           11 |     2415 | 2024-04-30 | PERA          | W   | 0.564      | 0.889        | -                | 0.453 (0.227)    | -         |     0.29 | EliGE, floppy, Grim, hallzerk, JT |
|           10 |     3338 | 2024-03-24 | FaZe          | L   | 0.317      | -            | -                | -                | -         |    -4.37 | EliGE, floppy, Grim, hallzerk, JT |
|            9 |     3348 | 2024-03-23 | Vitality      | L   | 0.311      | -            | -                | -                | -         |    -2.35 | EliGE, floppy, Grim, hallzerk, JT |
|            8 |     3363 | 2024-03-22 | MOUZ          | L   | 0.304      | -            | -                | -                | -         |    -2.30 | EliGE, floppy, Grim, hallzerk, JT |
|            7 |     3381 | 2024-03-21 | HEROIC        | W   | 0.299      | -            | -                | -                | -         |     3.82 | EliGE, floppy, Grim, hallzerk, JT |
|            6 |     3390 | 2024-03-21 | paiN          | W   | 0.298      | 1.000        | 0.328 (0.098)    | 0.865 (0.257)    | -         |     2.09 | EliGE, floppy, Grim, hallzerk, JT |
|            5 |     3706 | 2024-03-07 | OG            | L   | 0.205      | -            | -                | -                | -         |    -6.30 | EliGE, floppy, Grim, hallzerk, JT |
|            4 |     3795 | 2024-03-04 | Liquid        | W   | 0.186      | -            | -                | -                | -         |     1.79 | EliGE, floppy, Grim, hallzerk, JT |
|            3 |     3810 | 2024-03-03 | FURIA         | L   | 0.179      | -            | -                | -                | -         |    -2.24 | EliGE, floppy, Grim, hallzerk, JT |
|            2 |     3848 | 2024-03-02 | BOSS          | W   | 0.171      | -            | -                | -                | -         |     0.05 | EliGE, floppy, Grim, hallzerk, JT |
|            1 |     3867 | 2024-03-01 | Elevate       | W   | 0.166      | -            | -                | -                | -         |     0.14 | EliGE, floppy, Grim, hallzerk, JT |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($101,098.68)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.31) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.877 | $50,000.00     | $43,875.00      |
| 2024-06-09 |      0.831 | $8,000.00      | $6,648.89       |
| 2024-06-02 |      0.785 | $4,000.00      | $3,141.11       |
| 2024-05-12 |      0.644 | $45,000.00     | $29,000.00      |
| 2024-03-31 |      0.365 | $20,000.00     | $7,305.56       |
| 2024-03-10 |      0.226 | $5,000.00      | $1,128.13       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
