### Roster Details<br />
Team Name: Complexity<br />
Roster: EliGE, floppy, Grim, hallzerk, JT<br />
Global Rank: [14](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [3]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1566.6<br />
<br />
Final Rank Value (1566.6) = Starting Rank Value (1643.8) + Head To Head Adjustments (-77.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.663[<sup>1</sup>](#table2)
- Bounty Collected: 0.591[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
- LAN Wins: 0.948[<sup>2</sup>](#table1)

The average of these factors is 0.608<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1643.8
- 400 + ( ( 0.608 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1643.8


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
|           33 |       22 | 2024-08-03 | Spirit        | L   | 1.000      | -            | -                | -                | -         |    -3.75 | EliGE, floppy, Grim, hallzerk, JT |
|           32 |       55 | 2024-08-02 | HEROIC        | W   | 1.000      | 0.581        | 0.229 (0.133)    | 0.374 (0.217)    | 1 (1.000) |    15.69 | EliGE, floppy, Grim, hallzerk, JT |
|           31 |      183 | 2024-07-30 | OG            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.43 | EliGE, floppy, Grim, hallzerk, JT |
|           30 |      213 | 2024-07-29 | HEROIC        | L   | 1.000      | -            | -                | -                | -         |   -15.58 | EliGE, floppy, Grim, hallzerk, JT |
|           29 |      585 | 2024-07-18 | M80           | L   | 1.000      | -            | -                | -                | -         |   -27.17 | EliGE, floppy, Grim, hallzerk, JT |
|           28 |      640 | 2024-07-17 | Virtus.pro    | L   | 1.000      | -            | -                | -                | -         |   -12.80 | EliGE, floppy, Grim, hallzerk, JT |
|           27 |      969 | 2024-06-16 | Falcons       | W   | 0.874      | 0.500        | 0.224 (0.098)    | -                | 1 (0.874) |     7.85 | EliGE, floppy, Grim, hallzerk, JT |
|           26 |      978 | 2024-06-16 | Aurora        | W   | 0.873      | 0.500        | 0.424 (0.185)    | 0.793 (0.346)    | 1 (0.873) |     7.81 | EliGE, floppy, Grim, hallzerk, JT |
|           25 |     1008 | 2024-06-15 | MIBR          | W   | 0.867      | 0.500        | 0.209 (0.091)    | 0.659 (0.286)    | 1 (0.867) |     6.97 | EliGE, floppy, Grim, hallzerk, JT |
|           24 |     1038 | 2024-06-14 | ENCE          | L   | 0.862      | -            | -                | -                | -         |   -21.57 | EliGE, floppy, Grim, hallzerk, JT |
|           23 |     1050 | 2024-06-14 | Alliance      | W   | 0.860      | -            | -                | -                | 1 (0.860) |     0.40 | EliGE, floppy, Grim, hallzerk, JT |
|           22 |     1370 | 2024-06-06 | FURIA         | L   | 0.809      | -            | -                | -                | -         |   -13.73 | EliGE, floppy, Grim, hallzerk, JT |
|           21 |     1390 | 2024-06-06 | BetBoom       | L   | 0.807      | -            | -                | -                | -         |   -20.22 | EliGE, floppy, Grim, hallzerk, JT |
|           20 |     1402 | 2024-06-06 | fnatic        | L   | 0.807      | -            | -                | -                | -         |   -19.01 | EliGE, floppy, Grim, hallzerk, JT |
|           19 |     1446 | 2024-06-05 | BIG           | W   | 0.801      | 0.715        | 0.155 (0.089)    | 0.304 (0.174)    | 1 (0.801) |     3.57 | EliGE, floppy, Grim, hallzerk, JT |
|           18 |     1459 | 2024-06-05 | Eternal Fire  | W   | 0.799      | 0.715        | 0.743 (0.425)    | 0.458 (0.262)    | 1 (0.799) |    13.67 | EliGE, floppy, Grim, hallzerk, JT |
|           17 |     1681 | 2024-05-27 | MOUZ          | L   | 0.744      | -            | -                | -                | -         |    -4.95 | EliGE, floppy, Grim, hallzerk, JT |
|           16 |     1691 | 2024-05-27 | Liquid        | L   | 0.742      | -            | -                | -                | -         |   -15.68 | EliGE, floppy, Grim, hallzerk, JT |
|           15 |     2186 | 2024-05-11 | MOUZ          | L   | 0.636      | -            | -                | -                | -         |    -4.91 | EliGE, floppy, Grim, hallzerk, JT |
|           14 |     2237 | 2024-05-09 | Virtus.pro    | W   | 0.621      | 0.889        | 0.497 (0.274)    | 0.323 (0.179)    | 1 (0.621) |    10.51 | EliGE, floppy, Grim, hallzerk, JT |
|           13 |     2305 | 2024-05-05 | Natus Vincere | W   | 0.596      | 0.889        | 1.000 (0.529)    | 0.331 (0.175)    | 1 (0.596) |    16.11 | EliGE, floppy, Grim, hallzerk, JT |
|           12 |     2372 | 2024-05-02 | HEROIC        | W   | 0.575      | 0.889        | 0.229 (0.117)    | 0.374 (0.191)    | -         |     7.44 | EliGE, floppy, Grim, hallzerk, JT |
|           11 |     2419 | 2024-04-30 | PERA          | W   | 0.561      | 0.889        | -                | 0.453 (0.226)    | -         |     0.29 | EliGE, floppy, Grim, hallzerk, JT |
|           10 |     3343 | 2024-03-24 | FaZe          | L   | 0.314      | -            | -                | -                | -         |    -4.34 | EliGE, floppy, Grim, hallzerk, JT |
|            9 |     3353 | 2024-03-23 | Vitality      | L   | 0.308      | -            | -                | -                | -         |    -2.32 | EliGE, floppy, Grim, hallzerk, JT |
|            8 |     3368 | 2024-03-22 | MOUZ          | L   | 0.301      | -            | -                | -                | -         |    -2.28 | EliGE, floppy, Grim, hallzerk, JT |
|            7 |     3386 | 2024-03-21 | HEROIC        | W   | 0.296      | -            | -                | -                | -         |     3.77 | EliGE, floppy, Grim, hallzerk, JT |
|            6 |     3395 | 2024-03-21 | paiN          | W   | 0.294      | 1.000        | 0.327 (0.096)    | 0.866 (0.255)    | -         |     2.06 | EliGE, floppy, Grim, hallzerk, JT |
|            5 |     3712 | 2024-03-07 | OG            | L   | 0.202      | -            | -                | -                | -         |    -6.21 | EliGE, floppy, Grim, hallzerk, JT |
|            4 |     3801 | 2024-03-04 | Liquid        | W   | 0.183      | -            | -                | -                | -         |     1.76 | EliGE, floppy, Grim, hallzerk, JT |
|            3 |     3816 | 2024-03-03 | FURIA         | L   | 0.176      | -            | -                | -                | -         |    -2.20 | EliGE, floppy, Grim, hallzerk, JT |
|            2 |     3854 | 2024-03-02 | BOSS          | W   | 0.168      | -            | -                | -                | -         |     0.05 | EliGE, floppy, Grim, hallzerk, JT |
|            1 |     3873 | 2024-03-01 | Elevate       | W   | 0.163      | -            | -                | -                | -         |     0.13 | EliGE, floppy, Grim, hallzerk, JT |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($100,695.35)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.31) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.874 | $50,000.00     | $43,722.22      |
| 2024-06-09 |      0.828 | $8,000.00      | $6,624.44       |
| 2024-06-02 |      0.782 | $4,000.00      | $3,128.89       |
| 2024-05-12 |      0.641 | $45,000.00     | $28,862.50      |
| 2024-03-31 |      0.362 | $20,000.00     | $7,244.44       |
| 2024-03-10 |      0.223 | $5,000.00      | $1,112.85       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
