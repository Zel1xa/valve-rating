### Roster Details<br />
Team Name: The MongolZ<br />
Roster: 910, bLitz, mzinho, Senzu, Techno<br />
Global Rank: [7](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [1]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1698.6<br />
<br />
Final Rank Value (1698.6) = Starting Rank Value (1950.4) + Head To Head Adjustments (-251.8)<br />

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
|           53 |      307 | 2024-07-28 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -26.51 | 910, bLitz, mzinho, Senzu, Techno |
|           52 |      325 | 2024-07-28 | Eternal Fire      | W   | 1.000      | 0.650        | 0.739 (0.480)    | 0.438 (0.285)    | 1 (1.000) |    11.78 | 910, bLitz, mzinho, Senzu, Techno |
|           51 |      339 | 2024-07-27 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.453 (0.294)    | 1 (1.000) |     1.78 | 910, bLitz, mzinho, Senzu, Techno |
|           50 |      369 | 2024-07-26 | Aurora            | W   | 1.000      | 0.650        | 0.421 (0.273)    | 0.759 (0.493)    | 1 (1.000) |     6.56 | 910, bLitz, mzinho, Senzu, Techno |
|           49 |      407 | 2024-07-25 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -28.50 | 910, bLitz, mzinho, Senzu, Techno |
|           48 |      429 | 2024-07-24 | ENCE              | W   | 1.000      | 0.650        | -                | 0.422 (0.274)    | 1 (1.000) |     3.90 | 910, bLitz, mzinho, Senzu, Techno |
|           47 |      440 | 2024-07-24 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -30.76 | 910, bLitz, mzinho, Senzu, Techno |
|           46 |      487 | 2024-07-23 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           45 |      638 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |   -22.74 | 910, bLitz, mzinho, Senzu, Techno |
|           44 |      642 | 2024-07-18 | M80               | W   | 1.000      | 1.000        | 0.188 (0.188)    | 0.563 (0.563)    | 1 (1.000) |     1.64 | 910, bLitz, mzinho, Senzu, Techno |
|           43 |      654 | 2024-07-18 | MIBR              | W   | 1.000      | 1.000        | 0.208 (0.208)    | 0.633 (0.633)    | 1 (1.000) |     3.15 | 910, bLitz, mzinho, Senzu, Techno |
|           42 |      728 | 2024-07-17 | G2                | L   | 1.000      | -            | -                | -                | -         |    -9.13 | 910, bLitz, mzinho, Senzu, Techno |
|           41 |      883 | 2024-07-11 | CatEvil           | L   | 1.000      | -            | -                | -                | -         |   -31.46 | 910, bLitz, mzinho, Senzu, Techno |
|           40 |      886 | 2024-07-11 | Rare Atom         | L   | 1.000      | -            | -                | -                | -         |   -31.36 | 910, bLitz, mzinho, Senzu, Techno |
|           39 |      890 | 2024-07-11 | Steel Helmet      | W   | 1.000      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           38 |     1071 | 2024-06-15 | Falcons           | L   | 0.854      | -            | -                | -                | -         |   -24.89 | 910, bLitz, mzinho, Senzu, Techno |
|           37 |     1112 | 2024-06-14 | Aurora            | L   | 0.848      | -            | -                | -                | -         |   -24.78 | 910, bLitz, mzinho, Senzu, Techno |
|           36 |     1125 | 2024-06-14 | Party Astronauts  | W   | 0.846      | -            | -                | -                | 1 (0.846) |     0.15 | 910, bLitz, mzinho, Senzu, Techno |
|           35 |     1259 | 2024-06-09 | Ninjas in Pyjamas | W   | 0.814      | 0.715        | 0.254 (0.148)    | 0.531 (0.310)    | 1 (0.814) |     4.20 | 910, bLitz, mzinho, Senzu, Techno |
|           34 |     1337 | 2024-06-08 | Astralis          | W   | 0.807      | 0.715        | 0.389 (0.224)    | -                | 1 (0.807) |     7.24 | 910, bLitz, mzinho, Senzu, Techno |
|           33 |     1439 | 2024-06-06 | Astralis          | L   | 0.795      | -            | -                | -                | -         |   -18.48 | 910, bLitz, mzinho, Senzu, Techno |
|           32 |     1456 | 2024-06-06 | Ninjas in Pyjamas | W   | 0.794      | 0.715        | 0.254 (0.144)    | 0.531 (0.302)    | -         |     3.60 | 910, bLitz, mzinho, Senzu, Techno |
|           31 |     1478 | 2024-06-06 | HEROIC            | W   | 0.792      | 0.715        | 0.225 (0.127)    | -                | -         |     3.08 | 910, bLitz, mzinho, Senzu, Techno |
|           30 |     1508 | 2024-06-05 | ENCE              | W   | 0.788      | -            | -                | -                | -         |     1.08 | 910, bLitz, mzinho, Senzu, Techno |
|           29 |     1525 | 2024-06-05 | Sashi             | W   | 0.786      | 0.715        | -                | 0.958 (0.539)    | -         |     0.46 | 910, bLitz, mzinho, Senzu, Techno |
|           28 |     1611 | 2024-06-02 | BLEED             | W   | 0.767      | -            | -                | -                | -         |     1.30 | 910, bLitz, mzinho, Senzu, Techno |
|           27 |     1645 | 2024-06-01 | BLEED             | W   | 0.760      | -            | -                | -                | -         |     1.19 | 910, bLitz, mzinho, Senzu, Techno |
|           26 |     1724 | 2024-05-29 | Aurora            | W   | 0.740      | 0.500        | 0.421 (0.156)    | 0.759 (0.281)    | -         |     3.00 | 910, bLitz, mzinho, Senzu, Techno |
|           25 |     1745 | 2024-05-28 | Gaimin Gladiators | W   | 0.733      | -            | -                | -                | -         |     0.15 | 910, bLitz, mzinho, Senzu, Techno |
|           24 |     2019 | 2024-05-18 | ATOX              | W   | 0.666      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno |
|           23 |     2054 | 2024-05-16 | Chinggis Warriors | W   | 0.659      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|           22 |     2324 | 2024-05-08 | Virtus.pro        | L   | 0.602      | -            | -                | -                | -         |   -14.73 | 910, bLitz, mzinho, Senzu, Techno |
|           21 |     2533 | 2024-04-28 | Vitality          | L   | 0.533      | -            | -                | -                | -         |    -9.96 | 910, bLitz, mzinho, Senzu, Techno |
|           20 |     2610 | 2024-04-25 | G2                | W   | 0.513      | 0.889        | 1.000 (0.456)    | -                | -         |     9.39 | 910, bLitz, mzinho, Senzu, Techno |
|           19 |     2629 | 2024-04-24 | Falcons           | W   | 0.507      | -            | -                | -                | -         |     0.93 | 910, bLitz, mzinho, Senzu, Techno |
|           18 |     2756 | 2024-04-19 | Rare Atom         | W   | 0.474      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|           17 |     2805 | 2024-04-18 | TYLOO             | W   | 0.467      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           16 |     2816 | 2024-04-18 | Rare Atom         | W   | 0.466      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|           15 |     3245 | 2024-04-03 | Lynn Vision       | W   | 0.367      | -            | -                | -                | -         |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           14 |     3258 | 2024-04-03 | LYG               | W   | 0.366      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno |
|           13 |     3284 | 2024-04-02 | ATOX              | W   | 0.360      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           12 |     3288 | 2024-04-02 | LYG               | L   | 0.359      | -            | -                | -                | -         |   -11.30 | 910, bLitz, mzinho, Senzu, Techno |
|           11 |     3435 | 2024-03-22 | paiN              | L   | 0.288      | -            | -                | -                | -         |    -8.60 | 910, bLitz, mzinho, Senzu, Techno |
|           10 |     3457 | 2024-03-21 | Vitality          | L   | 0.282      | -            | -                | -                | -         |    -5.50 | 910, bLitz, mzinho, Senzu, Techno |
|            9 |     3467 | 2024-03-21 | Natus Vincere     | L   | 0.280      | -            | -                | -                | -         |    -3.97 | 910, bLitz, mzinho, Senzu, Techno |
|            8 |     3486 | 2024-03-20 | Legacy            | W   | 0.274      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|            7 |     3504 | 2024-03-19 | Lynn Vision       | W   | 0.267      | -            | -                | -                | -         |     0.06 | 910, bLitz, mzinho, Senzu, Techno |
|            6 |     3510 | 2024-03-18 | AMKAL             | W   | 0.261      | -            | -                | -                | -         |     0.09 | 910, bLitz, mzinho, Senzu, Techno |
|            5 |     3532 | 2024-03-17 | Gaimin Gladiators | L   | 0.255      | -            | -                | -                | -         |    -8.01 | 910, bLitz, mzinho, Senzu, Techno |
|            4 |     3545 | 2024-03-17 | Eternal Fire      | L   | 0.254      | -            | -                | -                | -         |    -6.43 | 910, bLitz, mzinho, Senzu, Techno |
|            3 |     3979 | 2024-02-27 | Lynn Vision       | W   | 0.131      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|            2 |     4015 | 2024-02-25 | FlyQuest          | W   | 0.119      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|            1 |     4021 | 2024-02-25 | MAG               | W   | 0.117      | -            | -                | -                | -         |     0.00 | 910, bLitz, mzinho, Senzu, Techno |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($320,521.62)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $70,000.00     | $70,000.00      |
| 2024-07-21 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-16 |      0.861 | $3,000.00      | $2,582.50       |
| 2024-06-09 |      0.814 | $200,000.00    | $162,888.89     |
| 2024-06-02 |      0.767 | $50,000.00     | $38,325.23      |
| 2024-05-12 |      0.628 | $23,500.00     | $14,752.78      |
| 2024-03-31 |      0.349 | $20,000.00     | $6,972.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
