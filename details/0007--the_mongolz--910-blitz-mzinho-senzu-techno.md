### Roster Details<br />
Team Name: The MongolZ<br />
Roster: 910, bLitz, mzinho, Senzu, Techno<br />
Global Rank: [7](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [1]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1690.7<br />
<br />
Final Rank Value (1690.7) = Starting Rank Value (1955.8) + Head To Head Adjustments (-265.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.618[<sup>2</sup>](#table1)
- Opponent Network: 0.404[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.755<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1955.8
- 400 + ( ( 0.755 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1955.8


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
|           53 |      151 | 2024-07-28 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -26.63 | 910, bLitz, mzinho, Senzu, Techno |
|           52 |      169 | 2024-07-28 | Eternal Fire      | W   | 1.000      | 0.650        | 0.757 (0.492)    | 0.461 (0.300)    | 1 (1.000) |    12.24 | 910, bLitz, mzinho, Senzu, Techno |
|           51 |      183 | 2024-07-27 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.482 (0.314)    | 1 (1.000) |     1.85 | 910, bLitz, mzinho, Senzu, Techno |
|           50 |      213 | 2024-07-26 | Aurora            | W   | 1.000      | 0.650        | 0.432 (0.281)    | 0.798 (0.519)    | 1 (1.000) |     6.51 | 910, bLitz, mzinho, Senzu, Techno |
|           49 |      251 | 2024-07-25 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -28.37 | 910, bLitz, mzinho, Senzu, Techno |
|           48 |      273 | 2024-07-24 | ENCE              | W   | 1.000      | 0.650        | -                | 0.403 (0.262)    | 1 (1.000) |     3.69 | 910, bLitz, mzinho, Senzu, Techno |
|           47 |      284 | 2024-07-24 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -30.75 | 910, bLitz, mzinho, Senzu, Techno |
|           46 |      331 | 2024-07-23 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           45 |      491 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |   -22.75 | 910, bLitz, mzinho, Senzu, Techno |
|           44 |      495 | 2024-07-18 | M80               | W   | 1.000      | 1.000        | 0.190 (0.190)    | 0.641 (0.641)    | 1 (1.000) |     1.91 | 910, bLitz, mzinho, Senzu, Techno |
|           43 |      507 | 2024-07-18 | MIBR              | W   | 1.000      | 1.000        | 0.201 (0.201)    | 0.637 (0.637)    | 1 (1.000) |     2.55 | 910, bLitz, mzinho, Senzu, Techno |
|           42 |      581 | 2024-07-17 | G2                | L   | 1.000      | -            | -                | -                | -         |    -9.03 | 910, bLitz, mzinho, Senzu, Techno |
|           41 |      744 | 2024-07-11 | CatEvil           | L   | 1.000      | -            | -                | -                | -         |   -31.46 | 910, bLitz, mzinho, Senzu, Techno |
|           40 |      747 | 2024-07-11 | Rare Atom         | L   | 1.000      | -            | -                | -                | -         |   -31.44 | 910, bLitz, mzinho, Senzu, Techno |
|           39 |      751 | 2024-07-11 | Steel Helmet      | W   | 1.000      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           38 |      928 | 2024-06-15 | Falcons           | L   | 0.887      | -            | -                | -                | -         |   -25.57 | 910, bLitz, mzinho, Senzu, Techno |
|           37 |      962 | 2024-06-14 | Aurora            | L   | 0.881      | -            | -                | -                | -         |   -25.78 | 910, bLitz, mzinho, Senzu, Techno |
|           36 |      975 | 2024-06-14 | Party Astronauts  | W   | 0.879      | -            | -                | -                | 1 (0.879) |     0.17 | 910, bLitz, mzinho, Senzu, Techno |
|           35 |     1111 | 2024-06-09 | Ninjas in Pyjamas | W   | 0.848      | 0.715        | 0.207 (0.126)    | 0.409 (0.248)    | 1 (0.848) |     2.23 | 910, bLitz, mzinho, Senzu, Techno |
|           34 |     1193 | 2024-06-08 | Astralis          | W   | 0.840      | 0.715        | 0.359 (0.216)    | -                | 1 (0.840) |     6.66 | 910, bLitz, mzinho, Senzu, Techno |
|           33 |     1302 | 2024-06-06 | Astralis          | L   | 0.828      | -            | -                | -                | -         |   -20.13 | 910, bLitz, mzinho, Senzu, Techno |
|           32 |     1319 | 2024-06-06 | Ninjas in Pyjamas | W   | 0.827      | 0.715        | 0.207 (0.123)    | -                | -         |     1.75 | 910, bLitz, mzinho, Senzu, Techno |
|           31 |     1342 | 2024-06-06 | HEROIC            | W   | 0.826      | 0.715        | 0.209 (0.123)    | -                | -         |     3.09 | 910, bLitz, mzinho, Senzu, Techno |
|           30 |     1374 | 2024-06-05 | ENCE              | W   | 0.821      | -            | -                | -                | -         |     1.00 | 910, bLitz, mzinho, Senzu, Techno |
|           29 |     1391 | 2024-06-05 | Sashi             | W   | 0.819      | 0.715        | -                | 0.971 (0.569)    | -         |     0.49 | 910, bLitz, mzinho, Senzu, Techno |
|           28 |     1478 | 2024-06-02 | BLEED             | W   | 0.800      | -            | -                | -                | -         |     1.39 | 910, bLitz, mzinho, Senzu, Techno |
|           27 |     1512 | 2024-06-01 | BLEED             | W   | 0.793      | -            | -                | -                | -         |     1.27 | 910, bLitz, mzinho, Senzu, Techno |
|           26 |     1591 | 2024-05-29 | Aurora            | W   | 0.773      | 0.500        | 0.432 (0.167)    | 0.798 (0.309)    | -         |     3.03 | 910, bLitz, mzinho, Senzu, Techno |
|           25 |     1612 | 2024-05-28 | Gaimin Gladiators | W   | 0.766      | -            | -                | -                | -         |     0.17 | 910, bLitz, mzinho, Senzu, Techno |
|           24 |     1914 | 2024-05-18 | ATOX              | W   | 0.699      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno |
|           23 |     1949 | 2024-05-16 | Chinggis Warriors | W   | 0.692      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           22 |     2230 | 2024-05-08 | Virtus.pro        | L   | 0.635      | -            | -                | -                | -         |   -15.39 | 910, bLitz, mzinho, Senzu, Techno |
|           21 |     2442 | 2024-04-28 | Vitality          | L   | 0.567      | -            | -                | -                | -         |   -10.73 | 910, bLitz, mzinho, Senzu, Techno |
|           20 |     2519 | 2024-04-25 | G2                | W   | 0.547      | 0.889        | 1.000 (0.486)    | 0.500 (0.243)    | -         |     9.89 | 910, bLitz, mzinho, Senzu, Techno |
|           19 |     2538 | 2024-04-24 | Falcons           | W   | 0.540      | -            | -                | -                | -         |     1.12 | 910, bLitz, mzinho, Senzu, Techno |
|           18 |     2672 | 2024-04-19 | Rare Atom         | W   | 0.507      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno |
|           17 |     2722 | 2024-04-18 | TYLOO             | W   | 0.500      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           16 |     2733 | 2024-04-18 | Rare Atom         | W   | 0.499      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno |
|           15 |     3171 | 2024-04-03 | Lynn Vision       | W   | 0.400      | -            | -                | -                | -         |     0.08 | 910, bLitz, mzinho, Senzu, Techno |
|           14 |     3186 | 2024-04-03 | LYG               | W   | 0.399      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           13 |     3212 | 2024-04-02 | ATOX              | W   | 0.393      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|           12 |     3216 | 2024-04-02 | LYG               | L   | 0.392      | -            | -                | -                | -         |   -12.35 | 910, bLitz, mzinho, Senzu, Techno |
|           11 |     3368 | 2024-03-22 | paiN              | L   | 0.321      | -            | -                | -                | -         |    -9.68 | 910, bLitz, mzinho, Senzu, Techno |
|           10 |     3390 | 2024-03-21 | Vitality          | L   | 0.315      | -            | -                | -                | -         |    -6.28 | 910, bLitz, mzinho, Senzu, Techno |
|            9 |     3400 | 2024-03-21 | Natus Vincere     | L   | 0.313      | -            | -                | -                | -         |    -4.30 | 910, bLitz, mzinho, Senzu, Techno |
|            8 |     3419 | 2024-03-20 | Legacy            | W   | 0.307      | -            | -                | -                | -         |     0.06 | 910, bLitz, mzinho, Senzu, Techno |
|            7 |     3437 | 2024-03-19 | Lynn Vision       | W   | 0.300      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|            6 |     3443 | 2024-03-18 | AMKAL             | W   | 0.294      | -            | -                | -                | -         |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|            5 |     3465 | 2024-03-17 | Gaimin Gladiators | L   | 0.288      | -            | -                | -                | -         |    -9.04 | 910, bLitz, mzinho, Senzu, Techno |
|            4 |     3478 | 2024-03-17 | Eternal Fire      | L   | 0.287      | -            | -                | -                | -         |    -7.15 | 910, bLitz, mzinho, Senzu, Techno |
|            3 |     3925 | 2024-02-27 | Lynn Vision       | W   | 0.164      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|            2 |     3962 | 2024-02-25 | FlyQuest          | W   | 0.152      | -            | -                | -                | -         |     0.06 | 910, bLitz, mzinho, Senzu, Techno |
|            1 |     3968 | 2024-02-25 | MAG               | W   | 0.151      | -            | -                | -                | -         |     0.00 | 910, bLitz, mzinho, Senzu, Techno |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($330,322.59)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $70,000.00     | $70,000.00      |
| 2024-07-21 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-16 |      0.894 | $3,000.00      | $2,681.67       |
| 2024-06-09 |      0.848 | $200,000.00    | $169,500.00     |
| 2024-06-02 |      0.800 | $50,000.00     | $39,978.01      |
| 2024-05-12 |      0.661 | $23,500.00     | $15,529.58      |
| 2024-03-31 |      0.382 | $20,000.00     | $7,633.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
