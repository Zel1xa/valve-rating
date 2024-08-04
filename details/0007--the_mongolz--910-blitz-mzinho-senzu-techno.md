### Roster Details<br />
Team Name: The MongolZ<br />
Roster: 910, bLitz, mzinho, Senzu, Techno<br />
Global Rank: [7](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [1]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1695.7<br />
<br />
Final Rank Value (1695.7) = Starting Rank Value (1950.2) + Head To Head Adjustments (-254.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.620[<sup>2</sup>](#table1)
- Opponent Network: 0.412[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.758<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1950.2
- 400 + ( ( 0.758 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1950.2


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
|           53 |      247 | 2024-07-28 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -26.65 | 910, bLitz, mzinho, Senzu, Techno |
|           52 |      265 | 2024-07-28 | Eternal Fire      | W   | 1.000      | 0.650        | 0.742 (0.483)    | 0.458 (0.298)    | 1 (1.000) |    11.89 | 910, bLitz, mzinho, Senzu, Techno |
|           51 |      279 | 2024-07-27 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.475 (0.309)    | 1 (1.000) |     1.81 | 910, bLitz, mzinho, Senzu, Techno |
|           50 |      309 | 2024-07-26 | Aurora            | W   | 1.000      | 0.650        | 0.423 (0.275)    | 0.793 (0.516)    | 1 (1.000) |     6.37 | 910, bLitz, mzinho, Senzu, Techno |
|           49 |      347 | 2024-07-25 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -28.55 | 910, bLitz, mzinho, Senzu, Techno |
|           48 |      369 | 2024-07-24 | ENCE              | W   | 1.000      | 0.650        | -                | 0.400 (0.260)    | 1 (1.000) |     3.78 | 910, bLitz, mzinho, Senzu, Techno |
|           47 |      380 | 2024-07-24 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -30.78 | 910, bLitz, mzinho, Senzu, Techno |
|           46 |      427 | 2024-07-23 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           45 |      578 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |   -22.76 | 910, bLitz, mzinho, Senzu, Techno |
|           44 |      582 | 2024-07-18 | M80               | W   | 1.000      | 1.000        | 0.188 (0.188)    | 0.587 (0.587)    | 1 (1.000) |     1.71 | 910, bLitz, mzinho, Senzu, Techno |
|           43 |      594 | 2024-07-18 | MIBR              | W   | 1.000      | 1.000        | 0.209 (0.209)    | 0.659 (0.659)    | 1 (1.000) |     3.25 | 910, bLitz, mzinho, Senzu, Techno |
|           42 |      668 | 2024-07-17 | G2                | L   | 1.000      | -            | -                | -                | -         |    -9.07 | 910, bLitz, mzinho, Senzu, Techno |
|           41 |      823 | 2024-07-11 | CatEvil           | L   | 1.000      | -            | -                | -                | -         |   -31.46 | 910, bLitz, mzinho, Senzu, Techno |
|           40 |      826 | 2024-07-11 | Rare Atom         | L   | 1.000      | -            | -                | -                | -         |   -31.43 | 910, bLitz, mzinho, Senzu, Techno |
|           39 |      830 | 2024-07-11 | Steel Helmet      | W   | 1.000      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           38 |     1011 | 2024-06-15 | Falcons           | L   | 0.867      | -            | -                | -                | -         |   -25.21 | 910, bLitz, mzinho, Senzu, Techno |
|           37 |     1052 | 2024-06-14 | Aurora            | L   | 0.860      | -            | -                | -                | -         |   -25.24 | 910, bLitz, mzinho, Senzu, Techno |
|           36 |     1065 | 2024-06-14 | Party Astronauts  | W   | 0.859      | -            | -                | -                | 1 (0.859) |     0.15 | 910, bLitz, mzinho, Senzu, Techno |
|           35 |     1199 | 2024-06-09 | Ninjas in Pyjamas | W   | 0.827      | 0.715        | 0.255 (0.151)    | 0.553 (0.327)    | 1 (0.827) |     4.30 | 910, bLitz, mzinho, Senzu, Techno |
|           34 |     1277 | 2024-06-08 | Astralis          | W   | 0.820      | 0.715        | 0.391 (0.229)    | -                | 1 (0.820) |     7.48 | 910, bLitz, mzinho, Senzu, Techno |
|           33 |     1379 | 2024-06-06 | Astralis          | L   | 0.808      | -            | -                | -                | -         |   -18.66 | 910, bLitz, mzinho, Senzu, Techno |
|           32 |     1396 | 2024-06-06 | Ninjas in Pyjamas | W   | 0.807      | 0.715        | 0.255 (0.147)    | 0.553 (0.319)    | -         |     3.69 | 910, bLitz, mzinho, Senzu, Techno |
|           31 |     1418 | 2024-06-06 | HEROIC            | W   | 0.805      | 0.715        | 0.229 (0.132)    | -                | -         |     3.21 | 910, bLitz, mzinho, Senzu, Techno |
|           30 |     1448 | 2024-06-05 | ENCE              | W   | 0.801      | -            | -                | -                | -         |     1.05 | 910, bLitz, mzinho, Senzu, Techno |
|           29 |     1465 | 2024-06-05 | Sashi             | W   | 0.799      | 0.715        | -                | 0.962 (0.550)    | -         |     0.47 | 910, bLitz, mzinho, Senzu, Techno |
|           28 |     1551 | 2024-06-02 | BLEED             | W   | 0.779      | -            | -                | -                | -         |     1.30 | 910, bLitz, mzinho, Senzu, Techno |
|           27 |     1585 | 2024-06-01 | BLEED             | W   | 0.773      | -            | -                | -                | -         |     1.19 | 910, bLitz, mzinho, Senzu, Techno |
|           26 |     1664 | 2024-05-29 | Aurora            | W   | 0.753      | 0.500        | 0.423 (0.159)    | 0.793 (0.298)    | -         |     2.93 | 910, bLitz, mzinho, Senzu, Techno |
|           25 |     1685 | 2024-05-28 | Gaimin Gladiators | W   | 0.746      | -            | -                | -                | -         |     0.15 | 910, bLitz, mzinho, Senzu, Techno |
|           24 |     1959 | 2024-05-18 | ATOX              | W   | 0.679      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno |
|           23 |     1994 | 2024-05-16 | Chinggis Warriors | W   | 0.672      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           22 |     2264 | 2024-05-08 | Virtus.pro        | L   | 0.615      | -            | -                | -                | -         |   -14.95 | 910, bLitz, mzinho, Senzu, Techno |
|           21 |     2473 | 2024-04-28 | Vitality          | L   | 0.546      | -            | -                | -                | -         |   -10.10 | 910, bLitz, mzinho, Senzu, Techno |
|           20 |     2550 | 2024-04-25 | G2                | W   | 0.526      | 0.889        | 1.000 (0.468)    | -                | -         |     9.64 | 910, bLitz, mzinho, Senzu, Techno |
|           19 |     2569 | 2024-04-24 | Falcons           | W   | 0.520      | -            | -                | -                | -         |     0.99 | 910, bLitz, mzinho, Senzu, Techno |
|           18 |     2696 | 2024-04-19 | Rare Atom         | W   | 0.487      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           17 |     2745 | 2024-04-18 | TYLOO             | W   | 0.480      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           16 |     2756 | 2024-04-18 | Rare Atom         | W   | 0.479      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           15 |     3185 | 2024-04-03 | Lynn Vision       | W   | 0.380      | -            | -                | -                | -         |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           14 |     3198 | 2024-04-03 | LYG               | W   | 0.379      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           13 |     3224 | 2024-04-02 | ATOX              | W   | 0.373      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           12 |     3228 | 2024-04-02 | LYG               | L   | 0.372      | -            | -                | -                | -         |   -11.71 | 910, bLitz, mzinho, Senzu, Techno |
|           11 |     3375 | 2024-03-22 | paiN              | L   | 0.300      | -            | -                | -                | -         |    -8.96 | 910, bLitz, mzinho, Senzu, Techno |
|           10 |     3397 | 2024-03-21 | Vitality          | L   | 0.295      | -            | -                | -                | -         |    -5.71 | 910, bLitz, mzinho, Senzu, Techno |
|            9 |     3407 | 2024-03-21 | Natus Vincere     | L   | 0.293      | -            | -                | -                | -         |    -4.16 | 910, bLitz, mzinho, Senzu, Techno |
|            8 |     3426 | 2024-03-20 | Legacy            | W   | 0.287      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|            7 |     3444 | 2024-03-19 | Lynn Vision       | W   | 0.280      | -            | -                | -                | -         |     0.06 | 910, bLitz, mzinho, Senzu, Techno |
|            6 |     3450 | 2024-03-18 | AMKAL             | W   | 0.274      | -            | -                | -                | -         |     0.09 | 910, bLitz, mzinho, Senzu, Techno |
|            5 |     3472 | 2024-03-17 | Gaimin Gladiators | L   | 0.268      | -            | -                | -                | -         |    -8.41 | 910, bLitz, mzinho, Senzu, Techno |
|            4 |     3485 | 2024-03-17 | Eternal Fire      | L   | 0.267      | -            | -                | -                | -         |    -6.75 | 910, bLitz, mzinho, Senzu, Techno |
|            3 |     3919 | 2024-02-27 | Lynn Vision       | W   | 0.144      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|            2 |     3955 | 2024-02-25 | FlyQuest          | W   | 0.132      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|            1 |     3961 | 2024-02-25 | MAG               | W   | 0.130      | -            | -                | -                | -         |     0.00 | 910, bLitz, mzinho, Senzu, Techno |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($324,344.55)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $70,000.00     | $70,000.00      |
| 2024-07-21 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-16 |      0.874 | $3,000.00      | $2,621.18       |
| 2024-06-09 |      0.827 | $200,000.00    | $165,467.59     |
| 2024-06-02 |      0.779 | $50,000.00     | $38,969.91      |
| 2024-05-12 |      0.641 | $23,500.00     | $15,055.78      |
| 2024-03-31 |      0.362 | $20,000.00     | $7,230.09       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
