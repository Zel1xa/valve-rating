### Roster Details<br />
Team Name: The MongolZ<br />
Roster: 910, bLitz, mzinho, Senzu, Techno<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [1]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1691.7<br />
<br />
Final Rank Value (1691.7) = Starting Rank Value (1948.0) + Head To Head Adjustments (-256.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.616[<sup>2</sup>](#table1)
- Opponent Network: 0.413[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.757<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1948.0
- 400 + ( ( 0.757 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1948.0


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
|           53 |      239 | 2024-07-28 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -26.59 | 910, bLitz, mzinho, Senzu, Techno |
|           52 |      257 | 2024-07-28 | Eternal Fire      | W   | 1.000      | 0.650        | 0.743 (0.483)    | 0.458 (0.298)    | 1 (1.000) |    11.90 | 910, bLitz, mzinho, Senzu, Techno |
|           51 |      271 | 2024-07-27 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.476 (0.309)    | 1 (1.000) |     1.83 | 910, bLitz, mzinho, Senzu, Techno |
|           50 |      301 | 2024-07-26 | Aurora            | W   | 1.000      | 0.650        | 0.424 (0.276)    | 0.793 (0.516)    | 1 (1.000) |     6.42 | 910, bLitz, mzinho, Senzu, Techno |
|           49 |      339 | 2024-07-25 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -28.51 | 910, bLitz, mzinho, Senzu, Techno |
|           48 |      361 | 2024-07-24 | ENCE              | W   | 1.000      | 0.650        | -                | 0.400 (0.260)    | 1 (1.000) |     3.79 | 910, bLitz, mzinho, Senzu, Techno |
|           47 |      372 | 2024-07-24 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -30.77 | 910, bLitz, mzinho, Senzu, Techno |
|           46 |      419 | 2024-07-23 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           45 |      570 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |   -22.71 | 910, bLitz, mzinho, Senzu, Techno |
|           44 |      574 | 2024-07-18 | M80               | W   | 1.000      | 1.000        | 0.188 (0.188)    | 0.587 (0.587)    | 1 (1.000) |     1.74 | 910, bLitz, mzinho, Senzu, Techno |
|           43 |      586 | 2024-07-18 | MIBR              | W   | 1.000      | 1.000        | 0.209 (0.209)    | 0.659 (0.659)    | 1 (1.000) |     3.32 | 910, bLitz, mzinho, Senzu, Techno |
|           42 |      660 | 2024-07-17 | G2                | L   | 1.000      | -            | -                | -                | -         |    -8.99 | 910, bLitz, mzinho, Senzu, Techno |
|           41 |      815 | 2024-07-11 | CatEvil           | L   | 1.000      | -            | -                | -                | -         |   -31.46 | 910, bLitz, mzinho, Senzu, Techno |
|           40 |      818 | 2024-07-11 | Rare Atom         | L   | 1.000      | -            | -                | -                | -         |   -31.43 | 910, bLitz, mzinho, Senzu, Techno |
|           39 |      822 | 2024-07-11 | Steel Helmet      | W   | 1.000      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           38 |     1003 | 2024-06-15 | Falcons           | L   | 0.868      | -            | -                | -                | -         |   -25.20 | 910, bLitz, mzinho, Senzu, Techno |
|           37 |     1044 | 2024-06-14 | Aurora            | L   | 0.861      | -            | -                | -                | -         |   -25.24 | 910, bLitz, mzinho, Senzu, Techno |
|           36 |     1057 | 2024-06-14 | Party Astronauts  | W   | 0.859      | -            | -                | -                | 1 (0.859) |     0.16 | 910, bLitz, mzinho, Senzu, Techno |
|           35 |     1191 | 2024-06-09 | Ninjas in Pyjamas | W   | 0.828      | 0.715        | 0.222 (0.132)    | 0.553 (0.328)    | 1 (0.828) |     4.17 | 910, bLitz, mzinho, Senzu, Techno |
|           34 |     1269 | 2024-06-08 | Astralis          | W   | 0.821      | 0.715        | 0.352 (0.207)    | -                | 1 (0.821) |     6.58 | 910, bLitz, mzinho, Senzu, Techno |
|           33 |     1371 | 2024-06-06 | Astralis          | L   | 0.809      | -            | -                | -                | -         |   -19.59 | 910, bLitz, mzinho, Senzu, Techno |
|           32 |     1388 | 2024-06-06 | Ninjas in Pyjamas | W   | 0.808      | 0.715        | 0.222 (0.128)    | 0.553 (0.320)    | -         |     3.52 | 910, bLitz, mzinho, Senzu, Techno |
|           31 |     1410 | 2024-06-06 | HEROIC            | W   | 0.806      | 0.715        | 0.229 (0.132)    | -                | -         |     3.19 | 910, bLitz, mzinho, Senzu, Techno |
|           30 |     1440 | 2024-06-05 | ENCE              | W   | 0.801      | -            | -                | -                | -         |     1.04 | 910, bLitz, mzinho, Senzu, Techno |
|           29 |     1457 | 2024-06-05 | Sashi             | W   | 0.800      | 0.715        | -                | 0.962 (0.551)    | -         |     0.47 | 910, bLitz, mzinho, Senzu, Techno |
|           28 |     1543 | 2024-06-02 | BLEED             | W   | 0.780      | -            | -                | -                | -         |     1.31 | 910, bLitz, mzinho, Senzu, Techno |
|           27 |     1577 | 2024-06-01 | BLEED             | W   | 0.773      | -            | -                | -                | -         |     1.20 | 910, bLitz, mzinho, Senzu, Techno |
|           26 |     1656 | 2024-05-29 | Aurora            | W   | 0.754      | 0.500        | 0.424 (0.160)    | 0.793 (0.299)    | -         |     2.94 | 910, bLitz, mzinho, Senzu, Techno |
|           25 |     1677 | 2024-05-28 | Gaimin Gladiators | W   | 0.747      | -            | -                | -                | -         |     0.15 | 910, bLitz, mzinho, Senzu, Techno |
|           24 |     1951 | 2024-05-18 | ATOX              | W   | 0.679      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno |
|           23 |     1986 | 2024-05-16 | Chinggis Warriors | W   | 0.672      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           22 |     2256 | 2024-05-08 | Virtus.pro        | L   | 0.616      | -            | -                | -                | -         |   -14.97 | 910, bLitz, mzinho, Senzu, Techno |
|           21 |     2465 | 2024-04-28 | Vitality          | L   | 0.547      | -            | -                | -                | -         |   -10.17 | 910, bLitz, mzinho, Senzu, Techno |
|           20 |     2542 | 2024-04-25 | G2                | W   | 0.527      | 0.889        | 1.000 (0.469)    | -                | -         |     9.69 | 910, bLitz, mzinho, Senzu, Techno |
|           19 |     2561 | 2024-04-24 | Falcons           | W   | 0.520      | -            | -                | -                | -         |     1.00 | 910, bLitz, mzinho, Senzu, Techno |
|           18 |     2688 | 2024-04-19 | Rare Atom         | W   | 0.488      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           17 |     2737 | 2024-04-18 | TYLOO             | W   | 0.481      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           16 |     2748 | 2024-04-18 | Rare Atom         | W   | 0.480      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           15 |     3177 | 2024-04-03 | Lynn Vision       | W   | 0.381      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno |
|           14 |     3190 | 2024-04-03 | LYG               | W   | 0.380      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           13 |     3216 | 2024-04-02 | ATOX              | W   | 0.374      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|           12 |     3220 | 2024-04-02 | LYG               | L   | 0.373      | -            | -                | -                | -         |   -11.73 | 910, bLitz, mzinho, Senzu, Techno |
|           11 |     3367 | 2024-03-22 | paiN              | L   | 0.301      | -            | -                | -                | -         |    -8.97 | 910, bLitz, mzinho, Senzu, Techno |
|           10 |     3389 | 2024-03-21 | Vitality          | L   | 0.295      | -            | -                | -                | -         |    -5.76 | 910, bLitz, mzinho, Senzu, Techno |
|            9 |     3399 | 2024-03-21 | Natus Vincere     | L   | 0.294      | -            | -                | -                | -         |    -4.15 | 910, bLitz, mzinho, Senzu, Techno |
|            8 |     3418 | 2024-03-20 | Legacy            | W   | 0.287      | -            | -                | -                | -         |     0.06 | 910, bLitz, mzinho, Senzu, Techno |
|            7 |     3436 | 2024-03-19 | Lynn Vision       | W   | 0.281      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|            6 |     3442 | 2024-03-18 | AMKAL             | W   | 0.274      | -            | -                | -                | -         |     0.09 | 910, bLitz, mzinho, Senzu, Techno |
|            5 |     3464 | 2024-03-17 | Gaimin Gladiators | L   | 0.269      | -            | -                | -                | -         |    -8.43 | 910, bLitz, mzinho, Senzu, Techno |
|            4 |     3477 | 2024-03-17 | Eternal Fire      | L   | 0.267      | -            | -                | -                | -         |    -6.76 | 910, bLitz, mzinho, Senzu, Techno |
|            3 |     3911 | 2024-02-27 | Lynn Vision       | W   | 0.144      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|            2 |     3947 | 2024-02-25 | FlyQuest          | W   | 0.132      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|            1 |     3953 | 2024-02-25 | MAG               | W   | 0.131      | -            | -                | -                | -         |     0.00 | 910, bLitz, mzinho, Senzu, Techno |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($324,557.31)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $70,000.00     | $70,000.00      |
| 2024-07-21 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-16 |      0.874 | $3,000.00      | $2,623.33       |
| 2024-06-09 |      0.828 | $200,000.00    | $165,611.11     |
| 2024-06-02 |      0.780 | $50,000.00     | $39,005.79      |
| 2024-05-12 |      0.641 | $23,500.00     | $15,072.64      |
| 2024-03-31 |      0.362 | $20,000.00     | $7,244.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
