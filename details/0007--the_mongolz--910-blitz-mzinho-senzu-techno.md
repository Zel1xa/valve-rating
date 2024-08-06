### Roster Details<br />
Team Name: The MongolZ<br />
Roster: 910, bLitz, mzinho, Senzu, Techno<br />
Global Rank: [7](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [1]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1698.9<br />
<br />
Final Rank Value (1698.9) = Starting Rank Value (1950.4) + Head To Head Adjustments (-251.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.618[<sup>2</sup>](#table1)
- Opponent Network: 0.397[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.754<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1950.4
- 400 + ( ( 0.754 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1950.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           53 |      317 | 2024-07-28 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -26.49 | 910, bLitz, mzinho, Senzu, Techno |
|           52 |      335 | 2024-07-28 | Eternal Fire      | W   | 1.000      | 0.650        | 0.738 (0.480)    | 0.438 (0.285)    | 1 (1.000) |    11.76 | 910, bLitz, mzinho, Senzu, Techno |
|           51 |      349 | 2024-07-27 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.452 (0.294)    | 1 (1.000) |     1.78 | 910, bLitz, mzinho, Senzu, Techno |
|           50 |      379 | 2024-07-26 | Aurora            | W   | 1.000      | 0.650        | 0.420 (0.273)    | 0.758 (0.493)    | 1 (1.000) |     6.58 | 910, bLitz, mzinho, Senzu, Techno |
|           49 |      417 | 2024-07-25 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -28.47 | 910, bLitz, mzinho, Senzu, Techno |
|           48 |      439 | 2024-07-24 | ENCE              | W   | 1.000      | 0.650        | -                | 0.422 (0.274)    | 1 (1.000) |     3.90 | 910, bLitz, mzinho, Senzu, Techno |
|           47 |      450 | 2024-07-24 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -30.75 | 910, bLitz, mzinho, Senzu, Techno |
|           46 |      497 | 2024-07-23 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           45 |      648 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |   -22.75 | 910, bLitz, mzinho, Senzu, Techno |
|           44 |      652 | 2024-07-18 | M80               | W   | 1.000      | 1.000        | 0.188 (0.188)    | 0.563 (0.563)    | 1 (1.000) |     1.64 | 910, bLitz, mzinho, Senzu, Techno |
|           43 |      664 | 2024-07-18 | MIBR              | W   | 1.000      | 1.000        | 0.208 (0.208)    | 0.633 (0.633)    | 1 (1.000) |     3.14 | 910, bLitz, mzinho, Senzu, Techno |
|           42 |      738 | 2024-07-17 | G2                | L   | 1.000      | -            | -                | -                | -         |    -9.14 | 910, bLitz, mzinho, Senzu, Techno |
|           41 |      893 | 2024-07-11 | CatEvil           | L   | 1.000      | -            | -                | -                | -         |   -31.46 | 910, bLitz, mzinho, Senzu, Techno |
|           40 |      896 | 2024-07-11 | Rare Atom         | L   | 1.000      | -            | -                | -                | -         |   -31.36 | 910, bLitz, mzinho, Senzu, Techno |
|           39 |      900 | 2024-07-11 | Steel Helmet      | W   | 1.000      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           38 |     1081 | 2024-06-15 | Falcons           | L   | 0.853      | -            | -                | -                | -         |   -24.87 | 910, bLitz, mzinho, Senzu, Techno |
|           37 |     1122 | 2024-06-14 | Aurora            | L   | 0.846      | -            | -                | -                | -         |   -24.74 | 910, bLitz, mzinho, Senzu, Techno |
|           36 |     1135 | 2024-06-14 | Party Astronauts  | W   | 0.845      | -            | -                | -                | 1 (0.845) |     0.14 | 910, bLitz, mzinho, Senzu, Techno |
|           35 |     1269 | 2024-06-09 | Ninjas in Pyjamas | W   | 0.813      | 0.715        | 0.253 (0.147)    | 0.531 (0.309)    | 1 (0.813) |     4.19 | 910, bLitz, mzinho, Senzu, Techno |
|           34 |     1347 | 2024-06-08 | Astralis          | W   | 0.806      | 0.715        | 0.389 (0.224)    | -                | 1 (0.806) |     7.22 | 910, bLitz, mzinho, Senzu, Techno |
|           33 |     1449 | 2024-06-06 | Astralis          | L   | 0.794      | -            | -                | -                | -         |   -18.47 | 910, bLitz, mzinho, Senzu, Techno |
|           32 |     1466 | 2024-06-06 | Ninjas in Pyjamas | W   | 0.793      | 0.715        | 0.253 (0.144)    | 0.531 (0.301)    | -         |     3.59 | 910, bLitz, mzinho, Senzu, Techno |
|           31 |     1488 | 2024-06-06 | HEROIC            | W   | 0.791      | 0.715        | 0.224 (0.127)    | -                | -         |     3.07 | 910, bLitz, mzinho, Senzu, Techno |
|           30 |     1518 | 2024-06-05 | ENCE              | W   | 0.787      | -            | -                | -                | -         |     1.08 | 910, bLitz, mzinho, Senzu, Techno |
|           29 |     1535 | 2024-06-05 | Sashi             | W   | 0.785      | 0.715        | -                | 0.958 (0.538)    | -         |     0.46 | 910, bLitz, mzinho, Senzu, Techno |
|           28 |     1621 | 2024-06-02 | BLEED             | W   | 0.765      | -            | -                | -                | -         |     1.30 | 910, bLitz, mzinho, Senzu, Techno |
|           27 |     1655 | 2024-06-01 | BLEED             | W   | 0.759      | -            | -                | -                | -         |     1.19 | 910, bLitz, mzinho, Senzu, Techno |
|           26 |     1734 | 2024-05-29 | Aurora            | W   | 0.739      | 0.500        | 0.420 (0.155)    | 0.758 (0.280)    | -         |     2.99 | 910, bLitz, mzinho, Senzu, Techno |
|           25 |     1755 | 2024-05-28 | Gaimin Gladiators | W   | 0.732      | -            | -                | -                | -         |     0.15 | 910, bLitz, mzinho, Senzu, Techno |
|           24 |     2029 | 2024-05-18 | ATOX              | W   | 0.665      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno |
|           23 |     2064 | 2024-05-16 | Chinggis Warriors | W   | 0.658      | -            | -                | -                | -         |     0.13 | 910, bLitz, mzinho, Senzu, Techno |
|           22 |     2334 | 2024-05-08 | Virtus.pro        | L   | 0.601      | -            | -                | -                | -         |   -14.71 | 910, bLitz, mzinho, Senzu, Techno |
|           21 |     2543 | 2024-04-28 | Vitality          | L   | 0.532      | -            | -                | -                | -         |    -9.94 | 910, bLitz, mzinho, Senzu, Techno |
|           20 |     2620 | 2024-04-25 | G2                | W   | 0.512      | 0.889        | 1.000 (0.455)    | -                | -         |     9.37 | 910, bLitz, mzinho, Senzu, Techno |
|           19 |     2639 | 2024-04-24 | Falcons           | W   | 0.506      | -            | -                | -                | -         |     0.93 | 910, bLitz, mzinho, Senzu, Techno |
|           18 |     2766 | 2024-04-19 | Rare Atom         | W   | 0.473      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|           17 |     2815 | 2024-04-18 | TYLOO             | W   | 0.466      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           16 |     2826 | 2024-04-18 | Rare Atom         | W   | 0.465      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|           15 |     3255 | 2024-04-03 | Lynn Vision       | W   | 0.366      | -            | -                | -                | -         |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           14 |     3268 | 2024-04-03 | LYG               | W   | 0.365      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno |
|           13 |     3294 | 2024-04-02 | ATOX              | W   | 0.359      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           12 |     3298 | 2024-04-02 | LYG               | L   | 0.358      | -            | -                | -                | -         |   -11.27 | 910, bLitz, mzinho, Senzu, Techno |
|           11 |     3445 | 2024-03-22 | paiN              | L   | 0.286      | -            | -                | -                | -         |    -8.56 | 910, bLitz, mzinho, Senzu, Techno |
|           10 |     3467 | 2024-03-21 | Vitality          | L   | 0.281      | -            | -                | -                | -         |    -5.48 | 910, bLitz, mzinho, Senzu, Techno |
|            9 |     3477 | 2024-03-21 | Natus Vincere     | L   | 0.279      | -            | -                | -                | -         |    -3.96 | 910, bLitz, mzinho, Senzu, Techno |
|            8 |     3496 | 2024-03-20 | Legacy            | W   | 0.273      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|            7 |     3514 | 2024-03-19 | Lynn Vision       | W   | 0.266      | -            | -                | -                | -         |     0.06 | 910, bLitz, mzinho, Senzu, Techno |
|            6 |     3520 | 2024-03-18 | AMKAL             | W   | 0.260      | -            | -                | -                | -         |     0.09 | 910, bLitz, mzinho, Senzu, Techno |
|            5 |     3542 | 2024-03-17 | Gaimin Gladiators | L   | 0.254      | -            | -                | -                | -         |    -7.97 | 910, bLitz, mzinho, Senzu, Techno |
|            4 |     3555 | 2024-03-17 | Eternal Fire      | L   | 0.253      | -            | -                | -                | -         |    -6.41 | 910, bLitz, mzinho, Senzu, Techno |
|            3 |     3989 | 2024-02-27 | Lynn Vision       | W   | 0.130      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|            2 |     4025 | 2024-02-25 | FlyQuest          | W   | 0.118      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|            1 |     4031 | 2024-02-25 | MAG               | W   | 0.116      | -            | -                | -                | -         |     0.00 | 910, bLitz, mzinho, Senzu, Techno |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($320,192.18)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $70,000.00     | $70,000.00      |
| 2024-07-21 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-16 |      0.860 | $3,000.00      | $2,579.17       |
| 2024-06-09 |      0.813 | $200,000.00    | $162,666.67     |
| 2024-06-02 |      0.765 | $50,000.00     | $38,269.68      |
| 2024-05-12 |      0.627 | $23,500.00     | $14,726.67      |
| 2024-03-31 |      0.347 | $20,000.00     | $6,950.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
