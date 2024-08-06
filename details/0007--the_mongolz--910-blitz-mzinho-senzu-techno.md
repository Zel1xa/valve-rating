### Roster Details<br />
Team Name: The MongolZ<br />
Roster: 910, bLitz, mzinho, Senzu, Techno<br />
Global Rank: [7](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [1]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1698.7<br />
<br />
Final Rank Value (1698.7) = Starting Rank Value (1950.4) + Head To Head Adjustments (-251.7)<br />

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
|           53 |      310 | 2024-07-28 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -26.51 | 910, bLitz, mzinho, Senzu, Techno |
|           52 |      328 | 2024-07-28 | Eternal Fire      | W   | 1.000      | 0.650        | 0.739 (0.480)    | 0.438 (0.285)    | 1 (1.000) |    11.77 | 910, bLitz, mzinho, Senzu, Techno |
|           51 |      342 | 2024-07-27 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.453 (0.294)    | 1 (1.000) |     1.77 | 910, bLitz, mzinho, Senzu, Techno |
|           50 |      372 | 2024-07-26 | Aurora            | W   | 1.000      | 0.650        | 0.420 (0.273)    | 0.759 (0.493)    | 1 (1.000) |     6.56 | 910, bLitz, mzinho, Senzu, Techno |
|           49 |      410 | 2024-07-25 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -28.49 | 910, bLitz, mzinho, Senzu, Techno |
|           48 |      432 | 2024-07-24 | ENCE              | W   | 1.000      | 0.650        | -                | 0.422 (0.274)    | 1 (1.000) |     3.90 | 910, bLitz, mzinho, Senzu, Techno |
|           47 |      443 | 2024-07-24 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -30.76 | 910, bLitz, mzinho, Senzu, Techno |
|           46 |      490 | 2024-07-23 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           45 |      641 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |   -22.74 | 910, bLitz, mzinho, Senzu, Techno |
|           44 |      645 | 2024-07-18 | M80               | W   | 1.000      | 1.000        | 0.188 (0.188)    | 0.563 (0.563)    | 1 (1.000) |     1.64 | 910, bLitz, mzinho, Senzu, Techno |
|           43 |      657 | 2024-07-18 | MIBR              | W   | 1.000      | 1.000        | 0.208 (0.208)    | 0.633 (0.633)    | 1 (1.000) |     3.15 | 910, bLitz, mzinho, Senzu, Techno |
|           42 |      731 | 2024-07-17 | G2                | L   | 1.000      | -            | -                | -                | -         |    -9.13 | 910, bLitz, mzinho, Senzu, Techno |
|           41 |      886 | 2024-07-11 | CatEvil           | L   | 1.000      | -            | -                | -                | -         |   -31.46 | 910, bLitz, mzinho, Senzu, Techno |
|           40 |      889 | 2024-07-11 | Rare Atom         | L   | 1.000      | -            | -                | -                | -         |   -31.36 | 910, bLitz, mzinho, Senzu, Techno |
|           39 |      893 | 2024-07-11 | Steel Helmet      | W   | 1.000      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           38 |     1074 | 2024-06-15 | Falcons           | L   | 0.854      | -            | -                | -                | -         |   -24.89 | 910, bLitz, mzinho, Senzu, Techno |
|           37 |     1115 | 2024-06-14 | Aurora            | L   | 0.847      | -            | -                | -                | -         |   -24.77 | 910, bLitz, mzinho, Senzu, Techno |
|           36 |     1128 | 2024-06-14 | Party Astronauts  | W   | 0.845      | -            | -                | -                | 1 (0.845) |     0.15 | 910, bLitz, mzinho, Senzu, Techno |
|           35 |     1262 | 2024-06-09 | Ninjas in Pyjamas | W   | 0.814      | 0.715        | 0.254 (0.148)    | 0.531 (0.309)    | 1 (0.814) |     4.20 | 910, bLitz, mzinho, Senzu, Techno |
|           34 |     1340 | 2024-06-08 | Astralis          | W   | 0.807      | 0.715        | 0.389 (0.224)    | -                | 1 (0.807) |     7.24 | 910, bLitz, mzinho, Senzu, Techno |
|           33 |     1442 | 2024-06-06 | Astralis          | L   | 0.795      | -            | -                | -                | -         |   -18.48 | 910, bLitz, mzinho, Senzu, Techno |
|           32 |     1459 | 2024-06-06 | Ninjas in Pyjamas | W   | 0.794      | 0.715        | 0.254 (0.144)    | 0.531 (0.302)    | -         |     3.60 | 910, bLitz, mzinho, Senzu, Techno |
|           31 |     1481 | 2024-06-06 | HEROIC            | W   | 0.792      | 0.715        | 0.224 (0.127)    | -                | -         |     3.08 | 910, bLitz, mzinho, Senzu, Techno |
|           30 |     1511 | 2024-06-05 | ENCE              | W   | 0.787      | -            | -                | -                | -         |     1.08 | 910, bLitz, mzinho, Senzu, Techno |
|           29 |     1528 | 2024-06-05 | Sashi             | W   | 0.786      | 0.715        | -                | 0.958 (0.539)    | -         |     0.46 | 910, bLitz, mzinho, Senzu, Techno |
|           28 |     1614 | 2024-06-02 | BLEED             | W   | 0.766      | -            | -                | -                | -         |     1.30 | 910, bLitz, mzinho, Senzu, Techno |
|           27 |     1648 | 2024-06-01 | BLEED             | W   | 0.759      | -            | -                | -                | -         |     1.19 | 910, bLitz, mzinho, Senzu, Techno |
|           26 |     1727 | 2024-05-29 | Aurora            | W   | 0.740      | 0.500        | 0.420 (0.155)    | 0.759 (0.281)    | -         |     3.00 | 910, bLitz, mzinho, Senzu, Techno |
|           25 |     1748 | 2024-05-28 | Gaimin Gladiators | W   | 0.733      | -            | -                | -                | -         |     0.15 | 910, bLitz, mzinho, Senzu, Techno |
|           24 |     2022 | 2024-05-18 | ATOX              | W   | 0.665      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno |
|           23 |     2057 | 2024-05-16 | Chinggis Warriors | W   | 0.658      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|           22 |     2327 | 2024-05-08 | Virtus.pro        | L   | 0.602      | -            | -                | -                | -         |   -14.73 | 910, bLitz, mzinho, Senzu, Techno |
|           21 |     2536 | 2024-04-28 | Vitality          | L   | 0.533      | -            | -                | -                | -         |    -9.95 | 910, bLitz, mzinho, Senzu, Techno |
|           20 |     2613 | 2024-04-25 | G2                | W   | 0.513      | 0.889        | 1.000 (0.456)    | -                | -         |     9.38 | 910, bLitz, mzinho, Senzu, Techno |
|           19 |     2632 | 2024-04-24 | Falcons           | W   | 0.506      | -            | -                | -                | -         |     0.93 | 910, bLitz, mzinho, Senzu, Techno |
|           18 |     2759 | 2024-04-19 | Rare Atom         | W   | 0.474      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|           17 |     2808 | 2024-04-18 | TYLOO             | W   | 0.467      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           16 |     2819 | 2024-04-18 | Rare Atom         | W   | 0.466      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|           15 |     3248 | 2024-04-03 | Lynn Vision       | W   | 0.367      | -            | -                | -                | -         |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           14 |     3261 | 2024-04-03 | LYG               | W   | 0.366      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno |
|           13 |     3287 | 2024-04-02 | ATOX              | W   | 0.360      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           12 |     3291 | 2024-04-02 | LYG               | L   | 0.359      | -            | -                | -                | -         |   -11.29 | 910, bLitz, mzinho, Senzu, Techno |
|           11 |     3438 | 2024-03-22 | paiN              | L   | 0.287      | -            | -                | -                | -         |    -8.59 | 910, bLitz, mzinho, Senzu, Techno |
|           10 |     3460 | 2024-03-21 | Vitality          | L   | 0.281      | -            | -                | -                | -         |    -5.49 | 910, bLitz, mzinho, Senzu, Techno |
|            9 |     3470 | 2024-03-21 | Natus Vincere     | L   | 0.280      | -            | -                | -                | -         |    -3.96 | 910, bLitz, mzinho, Senzu, Techno |
|            8 |     3489 | 2024-03-20 | Legacy            | W   | 0.273      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|            7 |     3507 | 2024-03-19 | Lynn Vision       | W   | 0.267      | -            | -                | -                | -         |     0.06 | 910, bLitz, mzinho, Senzu, Techno |
|            6 |     3513 | 2024-03-18 | AMKAL             | W   | 0.260      | -            | -                | -                | -         |     0.09 | 910, bLitz, mzinho, Senzu, Techno |
|            5 |     3535 | 2024-03-17 | Gaimin Gladiators | L   | 0.255      | -            | -                | -                | -         |    -8.00 | 910, bLitz, mzinho, Senzu, Techno |
|            4 |     3548 | 2024-03-17 | Eternal Fire      | L   | 0.253      | -            | -                | -                | -         |    -6.42 | 910, bLitz, mzinho, Senzu, Techno |
|            3 |     3982 | 2024-02-27 | Lynn Vision       | W   | 0.130      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|            2 |     4018 | 2024-02-25 | FlyQuest          | W   | 0.118      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|            1 |     4024 | 2024-02-25 | MAG               | W   | 0.117      | -            | -                | -                | -         |     0.00 | 910, bLitz, mzinho, Senzu, Techno |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($320,411.81)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $70,000.00     | $70,000.00      |
| 2024-07-21 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-16 |      0.860 | $3,000.00      | $2,581.39       |
| 2024-06-09 |      0.814 | $200,000.00    | $162,814.81     |
| 2024-06-02 |      0.766 | $50,000.00     | $38,306.71      |
| 2024-05-12 |      0.627 | $23,500.00     | $14,744.07      |
| 2024-03-31 |      0.348 | $20,000.00     | $6,964.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
