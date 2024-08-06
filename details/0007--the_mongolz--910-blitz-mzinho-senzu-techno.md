### Roster Details<br />
Team Name: The MongolZ<br />
Roster: 910, bLitz, mzinho, Senzu, Techno<br />
Global Rank: [7](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [1]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1699.2<br />
<br />
Final Rank Value (1699.2) = Starting Rank Value (1951.6) + Head To Head Adjustments (-252.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.618[<sup>2</sup>](#table1)
- Opponent Network: 0.406[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.756<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1951.6
- 400 + ( ( 0.756 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1951.6


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
|           53 |      303 | 2024-07-28 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -26.53 | 910, bLitz, mzinho, Senzu, Techno |
|           52 |      321 | 2024-07-28 | Eternal Fire      | W   | 1.000      | 0.650        | 0.739 (0.480)    | 0.448 (0.291)    | 1 (1.000) |    11.72 | 910, bLitz, mzinho, Senzu, Techno |
|           51 |      335 | 2024-07-27 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.463 (0.301)    | 1 (1.000) |     1.76 | 910, bLitz, mzinho, Senzu, Techno |
|           50 |      365 | 2024-07-26 | Aurora            | W   | 1.000      | 0.650        | 0.421 (0.274)    | 0.776 (0.505)    | 1 (1.000) |     6.49 | 910, bLitz, mzinho, Senzu, Techno |
|           49 |      403 | 2024-07-25 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -28.51 | 910, bLitz, mzinho, Senzu, Techno |
|           48 |      425 | 2024-07-24 | ENCE              | W   | 1.000      | 0.650        | -                | 0.431 (0.280)    | 1 (1.000) |     3.88 | 910, bLitz, mzinho, Senzu, Techno |
|           47 |      436 | 2024-07-24 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -30.76 | 910, bLitz, mzinho, Senzu, Techno |
|           46 |      483 | 2024-07-23 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           45 |      634 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |   -22.75 | 910, bLitz, mzinho, Senzu, Techno |
|           44 |      638 | 2024-07-18 | M80               | W   | 1.000      | 1.000        | 0.188 (0.188)    | 0.576 (0.576)    | 1 (1.000) |     1.64 | 910, bLitz, mzinho, Senzu, Techno |
|           43 |      650 | 2024-07-18 | MIBR              | W   | 1.000      | 1.000        | 0.208 (0.208)    | 0.647 (0.647)    | 1 (1.000) |     3.15 | 910, bLitz, mzinho, Senzu, Techno |
|           42 |      724 | 2024-07-17 | G2                | L   | 1.000      | -            | -                | -                | -         |    -9.16 | 910, bLitz, mzinho, Senzu, Techno |
|           41 |      879 | 2024-07-11 | CatEvil           | L   | 1.000      | -            | -                | -                | -         |   -31.46 | 910, bLitz, mzinho, Senzu, Techno |
|           40 |      882 | 2024-07-11 | Rare Atom         | L   | 1.000      | -            | -                | -                | -         |   -31.37 | 910, bLitz, mzinho, Senzu, Techno |
|           39 |      886 | 2024-07-11 | Steel Helmet      | W   | 1.000      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           38 |     1067 | 2024-06-15 | Falcons           | L   | 0.855      | -            | -                | -                | -         |   -24.91 | 910, bLitz, mzinho, Senzu, Techno |
|           37 |     1108 | 2024-06-14 | Aurora            | L   | 0.848      | -            | -                | -                | -         |   -24.82 | 910, bLitz, mzinho, Senzu, Techno |
|           36 |     1121 | 2024-06-14 | Party Astronauts  | W   | 0.846      | -            | -                | -                | 1 (0.846) |     0.15 | 910, bLitz, mzinho, Senzu, Techno |
|           35 |     1255 | 2024-06-09 | Ninjas in Pyjamas | W   | 0.815      | 0.715        | 0.254 (0.148)    | 0.543 (0.317)    | 1 (0.815) |     4.19 | 910, bLitz, mzinho, Senzu, Techno |
|           34 |     1333 | 2024-06-08 | Astralis          | W   | 0.807      | 0.715        | 0.389 (0.225)    | -                | 1 (0.807) |     7.22 | 910, bLitz, mzinho, Senzu, Techno |
|           33 |     1435 | 2024-06-06 | Astralis          | L   | 0.795      | -            | -                | -                | -         |   -18.51 | 910, bLitz, mzinho, Senzu, Techno |
|           32 |     1452 | 2024-06-06 | Ninjas in Pyjamas | W   | 0.794      | 0.715        | 0.254 (0.144)    | 0.543 (0.309)    | -         |     3.59 | 910, bLitz, mzinho, Senzu, Techno |
|           31 |     1474 | 2024-06-06 | HEROIC            | W   | 0.793      | 0.715        | 0.225 (0.127)    | -                | -         |     3.08 | 910, bLitz, mzinho, Senzu, Techno |
|           30 |     1504 | 2024-06-05 | ENCE              | W   | 0.788      | -            | -                | -                | -         |     1.07 | 910, bLitz, mzinho, Senzu, Techno |
|           29 |     1521 | 2024-06-05 | Sashi             | W   | 0.787      | 0.715        | -                | 0.980 (0.551)    | -         |     0.46 | 910, bLitz, mzinho, Senzu, Techno |
|           28 |     1607 | 2024-06-02 | BLEED             | W   | 0.767      | -            | -                | -                | -         |     1.29 | 910, bLitz, mzinho, Senzu, Techno |
|           27 |     1641 | 2024-06-01 | BLEED             | W   | 0.760      | -            | -                | -                | -         |     1.18 | 910, bLitz, mzinho, Senzu, Techno |
|           26 |     1720 | 2024-05-29 | Aurora            | W   | 0.740      | 0.500        | 0.421 (0.156)    | 0.776 (0.287)    | -         |     2.95 | 910, bLitz, mzinho, Senzu, Techno |
|           25 |     1741 | 2024-05-28 | Gaimin Gladiators | W   | 0.733      | -            | -                | -                | -         |     0.15 | 910, bLitz, mzinho, Senzu, Techno |
|           24 |     2015 | 2024-05-18 | ATOX              | W   | 0.666      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno |
|           23 |     2050 | 2024-05-16 | Chinggis Warriors | W   | 0.659      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|           22 |     2320 | 2024-05-08 | Virtus.pro        | L   | 0.602      | -            | -                | -                | -         |   -14.75 | 910, bLitz, mzinho, Senzu, Techno |
|           21 |     2529 | 2024-04-28 | Vitality          | L   | 0.534      | -            | -                | -                | -         |    -9.98 | 910, bLitz, mzinho, Senzu, Techno |
|           20 |     2606 | 2024-04-25 | G2                | W   | 0.514      | 0.889        | 1.000 (0.457)    | -                | -         |     9.37 | 910, bLitz, mzinho, Senzu, Techno |
|           19 |     2625 | 2024-04-24 | Falcons           | W   | 0.507      | -            | -                | -                | -         |     0.92 | 910, bLitz, mzinho, Senzu, Techno |
|           18 |     2752 | 2024-04-19 | Rare Atom         | W   | 0.474      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|           17 |     2801 | 2024-04-18 | TYLOO             | W   | 0.468      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           16 |     2812 | 2024-04-18 | Rare Atom         | W   | 0.467      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|           15 |     3241 | 2024-04-03 | Lynn Vision       | W   | 0.367      | -            | -                | -                | -         |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           14 |     3254 | 2024-04-03 | LYG               | W   | 0.366      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno |
|           13 |     3280 | 2024-04-02 | ATOX              | W   | 0.361      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           12 |     3284 | 2024-04-02 | LYG               | L   | 0.360      | -            | -                | -                | -         |   -11.31 | 910, bLitz, mzinho, Senzu, Techno |
|           11 |     3431 | 2024-03-22 | paiN              | L   | 0.288      | -            | -                | -                | -         |    -8.60 | 910, bLitz, mzinho, Senzu, Techno |
|           10 |     3453 | 2024-03-21 | Vitality          | L   | 0.282      | -            | -                | -                | -         |    -5.52 | 910, bLitz, mzinho, Senzu, Techno |
|            9 |     3463 | 2024-03-21 | Natus Vincere     | L   | 0.281      | -            | -                | -                | -         |    -3.99 | 910, bLitz, mzinho, Senzu, Techno |
|            8 |     3482 | 2024-03-20 | Legacy            | W   | 0.274      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|            7 |     3500 | 2024-03-19 | Lynn Vision       | W   | 0.267      | -            | -                | -                | -         |     0.06 | 910, bLitz, mzinho, Senzu, Techno |
|            6 |     3506 | 2024-03-18 | AMKAL             | W   | 0.261      | -            | -                | -                | -         |     0.09 | 910, bLitz, mzinho, Senzu, Techno |
|            5 |     3528 | 2024-03-17 | Gaimin Gladiators | L   | 0.256      | -            | -                | -                | -         |    -8.02 | 910, bLitz, mzinho, Senzu, Techno |
|            4 |     3541 | 2024-03-17 | Eternal Fire      | L   | 0.254      | -            | -                | -                | -         |    -6.45 | 910, bLitz, mzinho, Senzu, Techno |
|            3 |     3975 | 2024-02-27 | Lynn Vision       | W   | 0.131      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|            2 |     4011 | 2024-02-25 | FlyQuest          | W   | 0.119      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|            1 |     4017 | 2024-02-25 | MAG               | W   | 0.118      | -            | -                | -                | -         |     0.00 | 910, bLitz, mzinho, Senzu, Techno |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($320,603.98)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $70,000.00     | $70,000.00      |
| 2024-07-21 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-16 |      0.861 | $3,000.00      | $2,583.33       |
| 2024-06-09 |      0.815 | $200,000.00    | $162,944.44     |
| 2024-06-02 |      0.767 | $50,000.00     | $38,339.12      |
| 2024-05-12 |      0.628 | $23,500.00     | $14,759.31      |
| 2024-03-31 |      0.349 | $20,000.00     | $6,977.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
