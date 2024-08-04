### Roster Details<br />
Team Name: The MongolZ<br />
Roster: 910, bLitz, mzinho, Senzu, Techno<br />
Global Rank: [6](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [1]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1691.4<br />
<br />
Final Rank Value (1691.4) = Starting Rank Value (1948.1) + Head To Head Adjustments (-256.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.617[<sup>2</sup>](#table1)
- Opponent Network: 0.414[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.758<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1948.1
- 400 + ( ( 0.758 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1948.1


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
|           53 |      236 | 2024-07-28 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -26.61 | 910, bLitz, mzinho, Senzu, Techno |
|           52 |      254 | 2024-07-28 | Eternal Fire      | W   | 1.000      | 0.650        | 0.743 (0.483)    | 0.458 (0.298)    | 1 (1.000) |    11.93 | 910, bLitz, mzinho, Senzu, Techno |
|           51 |      268 | 2024-07-27 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.477 (0.310)    | 1 (1.000) |     1.84 | 910, bLitz, mzinho, Senzu, Techno |
|           50 |      298 | 2024-07-26 | Aurora            | W   | 1.000      | 0.650        | 0.424 (0.276)    | 0.794 (0.516)    | 1 (1.000) |     6.42 | 910, bLitz, mzinho, Senzu, Techno |
|           49 |      336 | 2024-07-25 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -28.51 | 910, bLitz, mzinho, Senzu, Techno |
|           48 |      358 | 2024-07-24 | ENCE              | W   | 1.000      | 0.650        | -                | 0.401 (0.261)    | 1 (1.000) |     3.80 | 910, bLitz, mzinho, Senzu, Techno |
|           47 |      369 | 2024-07-24 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -30.77 | 910, bLitz, mzinho, Senzu, Techno |
|           46 |      416 | 2024-07-23 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           45 |      567 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |   -22.71 | 910, bLitz, mzinho, Senzu, Techno |
|           44 |      571 | 2024-07-18 | M80               | W   | 1.000      | 1.000        | 0.188 (0.188)    | 0.587 (0.587)    | 1 (1.000) |     1.75 | 910, bLitz, mzinho, Senzu, Techno |
|           43 |      583 | 2024-07-18 | MIBR              | W   | 1.000      | 1.000        | 0.210 (0.210)    | 0.659 (0.659)    | 1 (1.000) |     3.34 | 910, bLitz, mzinho, Senzu, Techno |
|           42 |      657 | 2024-07-17 | G2                | L   | 1.000      | -            | -                | -                | -         |    -8.98 | 910, bLitz, mzinho, Senzu, Techno |
|           41 |      811 | 2024-07-11 | CatEvil           | L   | 1.000      | -            | -                | -                | -         |   -31.46 | 910, bLitz, mzinho, Senzu, Techno |
|           40 |      814 | 2024-07-11 | Rare Atom         | L   | 1.000      | -            | -                | -                | -         |   -31.43 | 910, bLitz, mzinho, Senzu, Techno |
|           39 |      818 | 2024-07-11 | Steel Helmet      | W   | 1.000      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           38 |      999 | 2024-06-15 | Falcons           | L   | 0.871      | -            | -                | -                | -         |   -25.27 | 910, bLitz, mzinho, Senzu, Techno |
|           37 |     1040 | 2024-06-14 | Aurora            | L   | 0.864      | -            | -                | -                | -         |   -25.33 | 910, bLitz, mzinho, Senzu, Techno |
|           36 |     1053 | 2024-06-14 | Party Astronauts  | W   | 0.863      | -            | -                | -                | 1 (0.863) |     0.16 | 910, bLitz, mzinho, Senzu, Techno |
|           35 |     1187 | 2024-06-09 | Ninjas in Pyjamas | W   | 0.831      | 0.715        | 0.223 (0.132)    | 0.553 (0.329)    | 1 (0.831) |     4.20 | 910, bLitz, mzinho, Senzu, Techno |
|           34 |     1265 | 2024-06-08 | Astralis          | W   | 0.824      | 0.715        | 0.353 (0.208)    | -                | 1 (0.824) |     6.65 | 910, bLitz, mzinho, Senzu, Techno |
|           33 |     1367 | 2024-06-06 | Astralis          | L   | 0.812      | -            | -                | -                | -         |   -19.62 | 910, bLitz, mzinho, Senzu, Techno |
|           32 |     1384 | 2024-06-06 | Ninjas in Pyjamas | W   | 0.811      | 0.715        | 0.223 (0.129)    | 0.553 (0.321)    | -         |     3.55 | 910, bLitz, mzinho, Senzu, Techno |
|           31 |     1406 | 2024-06-06 | HEROIC            | W   | 0.809      | 0.715        | 0.229 (0.133)    | -                | -         |     3.22 | 910, bLitz, mzinho, Senzu, Techno |
|           30 |     1436 | 2024-06-05 | ENCE              | W   | 0.805      | -            | -                | -                | -         |     1.05 | 910, bLitz, mzinho, Senzu, Techno |
|           29 |     1453 | 2024-06-05 | Sashi             | W   | 0.803      | 0.715        | -                | 0.964 (0.554)    | -         |     0.48 | 910, bLitz, mzinho, Senzu, Techno |
|           28 |     1539 | 2024-06-02 | BLEED             | W   | 0.783      | -            | -                | -                | -         |     1.32 | 910, bLitz, mzinho, Senzu, Techno |
|           27 |     1573 | 2024-06-01 | BLEED             | W   | 0.776      | -            | -                | -                | -         |     1.21 | 910, bLitz, mzinho, Senzu, Techno |
|           26 |     1652 | 2024-05-29 | Aurora            | W   | 0.757      | 0.500        | 0.424 (0.161)    | 0.794 (0.300)    | -         |     2.95 | 910, bLitz, mzinho, Senzu, Techno |
|           25 |     1673 | 2024-05-28 | Gaimin Gladiators | W   | 0.750      | -            | -                | -                | -         |     0.16 | 910, bLitz, mzinho, Senzu, Techno |
|           24 |     1947 | 2024-05-18 | ATOX              | W   | 0.682      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno |
|           23 |     1982 | 2024-05-16 | Chinggis Warriors | W   | 0.675      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           22 |     2252 | 2024-05-08 | Virtus.pro        | L   | 0.619      | -            | -                | -                | -         |   -15.03 | 910, bLitz, mzinho, Senzu, Techno |
|           21 |     2461 | 2024-04-28 | Vitality          | L   | 0.550      | -            | -                | -                | -         |   -10.20 | 910, bLitz, mzinho, Senzu, Techno |
|           20 |     2537 | 2024-04-25 | G2                | W   | 0.530      | 0.889        | 1.000 (0.471)    | -                | -         |     9.75 | 910, bLitz, mzinho, Senzu, Techno |
|           19 |     2556 | 2024-04-24 | Falcons           | W   | 0.523      | -            | -                | -                | -         |     1.02 | 910, bLitz, mzinho, Senzu, Techno |
|           18 |     2683 | 2024-04-19 | Rare Atom         | W   | 0.491      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           17 |     2732 | 2024-04-18 | TYLOO             | W   | 0.484      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           16 |     2743 | 2024-04-18 | Rare Atom         | W   | 0.483      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           15 |     3172 | 2024-04-03 | Lynn Vision       | W   | 0.384      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno |
|           14 |     3185 | 2024-04-03 | LYG               | W   | 0.383      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           13 |     3211 | 2024-04-02 | ATOX              | W   | 0.377      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|           12 |     3215 | 2024-04-02 | LYG               | L   | 0.376      | -            | -                | -                | -         |   -11.83 | 910, bLitz, mzinho, Senzu, Techno |
|           11 |     3362 | 2024-03-22 | paiN              | L   | 0.304      | -            | -                | -                | -         |    -9.06 | 910, bLitz, mzinho, Senzu, Techno |
|           10 |     3384 | 2024-03-21 | Vitality          | L   | 0.298      | -            | -                | -                | -         |    -5.81 | 910, bLitz, mzinho, Senzu, Techno |
|            9 |     3394 | 2024-03-21 | Natus Vincere     | L   | 0.297      | -            | -                | -                | -         |    -4.19 | 910, bLitz, mzinho, Senzu, Techno |
|            8 |     3413 | 2024-03-20 | Legacy            | W   | 0.290      | -            | -                | -                | -         |     0.06 | 910, bLitz, mzinho, Senzu, Techno |
|            7 |     3431 | 2024-03-19 | Lynn Vision       | W   | 0.284      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|            6 |     3437 | 2024-03-18 | AMKAL             | W   | 0.277      | -            | -                | -                | -         |     0.09 | 910, bLitz, mzinho, Senzu, Techno |
|            5 |     3459 | 2024-03-17 | Gaimin Gladiators | L   | 0.272      | -            | -                | -                | -         |    -8.53 | 910, bLitz, mzinho, Senzu, Techno |
|            4 |     3472 | 2024-03-17 | Eternal Fire      | L   | 0.270      | -            | -                | -                | -         |    -6.83 | 910, bLitz, mzinho, Senzu, Techno |
|            3 |     3905 | 2024-02-27 | Lynn Vision       | W   | 0.147      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|            2 |     3941 | 2024-02-25 | FlyQuest          | W   | 0.135      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|            1 |     3947 | 2024-02-25 | MAG               | W   | 0.134      | -            | -                | -                | -         |     0.00 | 910, bLitz, mzinho, Senzu, Techno |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($325,463.29)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $70,000.00     | $70,000.00      |
| 2024-07-21 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-16 |      0.877 | $3,000.00      | $2,632.50       |
| 2024-06-09 |      0.831 | $200,000.00    | $166,222.22     |
| 2024-06-02 |      0.783 | $50,000.00     | $39,158.56      |
| 2024-05-12 |      0.644 | $23,500.00     | $15,144.44      |
| 2024-03-31 |      0.365 | $20,000.00     | $7,305.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
