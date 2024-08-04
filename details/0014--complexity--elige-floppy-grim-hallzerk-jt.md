### Roster Details<br />
Team Name: Complexity<br />
Roster: EliGE, floppy, Grim, hallzerk, JT<br />
Global Rank: [14](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [3]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1571.2<br />
<br />
Final Rank Value (1571.2) = Starting Rank Value (1654.3) + Head To Head Adjustments (-83.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.682[<sup>1</sup>](#table2)
- Bounty Collected: 0.591[<sup>2</sup>](#table1)
- Opponent Network: 0.233[<sup>2</sup>](#table1)
- LAN Wins: 0.948[<sup>2</sup>](#table1)

The average of these factors is 0.613<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1654.3
- 400 + ( ( 0.613 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1654.3


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
|           34 |        3 | 2024-08-04 | Natus Vincere | L   | 1.000      | -            | -                | -                | -         |    -4.15 | EliGE, floppy, Grim, hallzerk, JT |
|           33 |       52 | 2024-08-03 | Spirit        | L   | 1.000      | -            | -                | -                | -         |    -3.87 | EliGE, floppy, Grim, hallzerk, JT |
|           32 |       85 | 2024-08-02 | HEROIC        | W   | 1.000      | 0.581        | 0.229 (0.133)    | 0.373 (0.217)    | 1 (1.000) |    15.52 | EliGE, floppy, Grim, hallzerk, JT |
|           31 |      214 | 2024-07-30 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.37 | EliGE, floppy, Grim, hallzerk, JT |
|           30 |      245 | 2024-07-29 | HEROIC        | L   | 1.000      | -            | -                | -                | -         |   -15.76 | EliGE, floppy, Grim, hallzerk, JT |
|           29 |      616 | 2024-07-18 | M80           | L   | 1.000      | -            | -                | -                | -         |   -27.39 | EliGE, floppy, Grim, hallzerk, JT |
|           28 |      668 | 2024-07-17 | Virtus.pro    | L   | 1.000      | -            | -                | -                | -         |   -13.01 | EliGE, floppy, Grim, hallzerk, JT |
|           27 |     1000 | 2024-06-16 | Falcons       | W   | 0.873      | 0.500        | 0.223 (0.098)    | -                | 1 (0.873) |     7.58 | EliGE, floppy, Grim, hallzerk, JT |
|           26 |     1009 | 2024-06-16 | Aurora        | W   | 0.871      | 0.500        | 0.423 (0.184)    | 0.793 (0.345)    | 1 (0.871) |     7.57 | EliGE, floppy, Grim, hallzerk, JT |
|           25 |     1039 | 2024-06-15 | MIBR          | W   | 0.865      | 0.500        | 0.209 (0.090)    | 0.659 (0.285)    | 1 (0.865) |     6.67 | EliGE, floppy, Grim, hallzerk, JT |
|           24 |     1069 | 2024-06-14 | ENCE          | L   | 0.860      | -            | -                | -                | -         |   -21.67 | EliGE, floppy, Grim, hallzerk, JT |
|           23 |     1081 | 2024-06-14 | Alliance      | W   | 0.859      | -            | -                | -                | 1 (0.859) |     0.38 | EliGE, floppy, Grim, hallzerk, JT |
|           22 |     1401 | 2024-06-06 | FURIA         | L   | 0.807      | -            | -                | -                | -         |   -13.96 | EliGE, floppy, Grim, hallzerk, JT |
|           21 |     1421 | 2024-06-06 | BetBoom       | L   | 0.806      | -            | -                | -                | -         |   -20.42 | EliGE, floppy, Grim, hallzerk, JT |
|           20 |     1433 | 2024-06-06 | fnatic        | L   | 0.805      | -            | -                | -                | -         |   -19.22 | EliGE, floppy, Grim, hallzerk, JT |
|           19 |     1477 | 2024-06-05 | BIG           | W   | 0.800      | 0.715        | 0.155 (0.089)    | 0.304 (0.174)    | 1 (0.800) |     3.38 | EliGE, floppy, Grim, hallzerk, JT |
|           18 |     1490 | 2024-06-05 | Eternal Fire  | W   | 0.798      | 0.715        | 0.742 (0.424)    | 0.458 (0.261)    | 1 (0.798) |    13.39 | EliGE, floppy, Grim, hallzerk, JT |
|           17 |     1712 | 2024-05-27 | MOUZ          | L   | 0.743      | -            | -                | -                | -         |    -5.13 | EliGE, floppy, Grim, hallzerk, JT |
|           16 |     1722 | 2024-05-27 | Liquid        | L   | 0.741      | -            | -                | -                | -         |   -13.70 | EliGE, floppy, Grim, hallzerk, JT |
|           15 |     2217 | 2024-05-11 | MOUZ          | L   | 0.634      | -            | -                | -                | -         |    -5.04 | EliGE, floppy, Grim, hallzerk, JT |
|           14 |     2268 | 2024-05-09 | Virtus.pro    | W   | 0.620      | 0.889        | 0.497 (0.274)    | 0.323 (0.178)    | 1 (0.620) |    10.30 | EliGE, floppy, Grim, hallzerk, JT |
|           13 |     2336 | 2024-05-05 | Natus Vincere | W   | 0.594      | 0.889        | 1.000 (0.528)    | 0.371 (0.196)    | 1 (0.594) |    15.98 | EliGE, floppy, Grim, hallzerk, JT |
|           12 |     2403 | 2024-05-02 | HEROIC        | W   | 0.573      | 0.889        | 0.229 (0.116)    | 0.373 (0.190)    | -         |     7.25 | EliGE, floppy, Grim, hallzerk, JT |
|           11 |     2450 | 2024-04-30 | PERA          | W   | 0.560      | 0.889        | -                | 0.453 (0.225)    | -         |     0.28 | EliGE, floppy, Grim, hallzerk, JT |
|           10 |     3374 | 2024-03-24 | FaZe          | L   | 0.312      | -            | -                | -                | -         |    -4.45 | EliGE, floppy, Grim, hallzerk, JT |
|            9 |     3384 | 2024-03-23 | Vitality      | L   | 0.307      | -            | -                | -                | -         |    -2.37 | EliGE, floppy, Grim, hallzerk, JT |
|            8 |     3399 | 2024-03-22 | MOUZ          | L   | 0.300      | -            | -                | -                | -         |    -2.36 | EliGE, floppy, Grim, hallzerk, JT |
|            7 |     3417 | 2024-03-21 | HEROIC        | W   | 0.294      | -            | -                | -                | -         |     3.64 | EliGE, floppy, Grim, hallzerk, JT |
|            6 |     3426 | 2024-03-21 | paiN          | W   | 0.293      | 1.000        | 0.327 (0.096)    | 0.867 (0.254)    | -         |     1.95 | EliGE, floppy, Grim, hallzerk, JT |
|            5 |     3743 | 2024-03-07 | OG            | L   | 0.201      | -            | -                | -                | -         |    -6.17 | EliGE, floppy, Grim, hallzerk, JT |
|            4 |     3832 | 2024-03-04 | Liquid        | W   | 0.182      | -            | -                | -                | -         |     2.37 | EliGE, floppy, Grim, hallzerk, JT |
|            3 |     3847 | 2024-03-03 | FURIA         | L   | 0.175      | -            | -                | -                | -         |    -2.25 | EliGE, floppy, Grim, hallzerk, JT |
|            2 |     3885 | 2024-03-02 | BOSS          | W   | 0.167      | -            | -                | -                | -         |     0.05 | EliGE, floppy, Grim, hallzerk, JT |
|            1 |     3904 | 2024-03-01 | Elevate       | W   | 0.161      | -            | -                | -                | -         |     0.13 | EliGE, floppy, Grim, hallzerk, JT |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($110,999.79)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.34) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $10,500.00     | $10,500.00      |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.873 | $50,000.00     | $43,648.15      |
| 2024-06-09 |      0.827 | $8,000.00      | $6,612.59       |
| 2024-06-02 |      0.781 | $4,000.00      | $3,122.96       |
| 2024-05-12 |      0.640 | $45,000.00     | $28,795.83      |
| 2024-03-31 |      0.361 | $20,000.00     | $7,214.81       |
| 2024-03-10 |      0.221 | $5,000.00      | $1,105.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
