### Roster Details<br />
Team Name: The MongolZ<br />
Roster: 910, bLitz, mzinho, Senzu, Techno<br />
Global Rank: [7](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [1]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1700.9<br />
<br />
Final Rank Value (1700.9) = Starting Rank Value (1961.3) + Head To Head Adjustments (-260.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.624[<sup>2</sup>](#table1)
- Opponent Network: 0.404[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.757<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1961.3
- 400 + ( ( 0.757 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1961.3


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
|           53 |      122 | 2024-07-28 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -26.71 | 910, bLitz, mzinho, Senzu, Techno |
|           52 |      140 | 2024-07-28 | Eternal Fire      | W   | 1.000      | 0.650        | 0.752 (0.489)    | 0.462 (0.300)    | 1 (1.000) |    12.39 | 910, bLitz, mzinho, Senzu, Techno |
|           51 |      154 | 2024-07-27 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.484 (0.315)    | 1 (1.000) |     1.85 | 910, bLitz, mzinho, Senzu, Techno |
|           50 |      184 | 2024-07-26 | Aurora            | W   | 1.000      | 0.650        | 0.429 (0.279)    | 0.800 (0.520)    | 1 (1.000) |     6.41 | 910, bLitz, mzinho, Senzu, Techno |
|           49 |      222 | 2024-07-25 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -28.51 | 910, bLitz, mzinho, Senzu, Techno |
|           48 |      244 | 2024-07-24 | ENCE              | W   | 1.000      | 0.650        | -                | 0.404 (0.263)    | 1 (1.000) |     3.93 | 910, bLitz, mzinho, Senzu, Techno |
|           47 |      255 | 2024-07-24 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -30.81 | 910, bLitz, mzinho, Senzu, Techno |
|           46 |      302 | 2024-07-23 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           45 |      453 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |   -22.46 | 910, bLitz, mzinho, Senzu, Techno |
|           44 |      457 | 2024-07-18 | M80               | W   | 1.000      | 1.000        | 0.189 (0.189)    | 0.551 (0.551)    | 1 (1.000) |     1.78 | 910, bLitz, mzinho, Senzu, Techno |
|           43 |      469 | 2024-07-18 | MIBR              | W   | 1.000      | 1.000        | 0.200 (0.200)    | 0.637 (0.637)    | 1 (1.000) |     3.36 | 910, bLitz, mzinho, Senzu, Techno |
|           42 |      543 | 2024-07-17 | G2                | L   | 1.000      | -            | -                | -                | -         |    -9.18 | 910, bLitz, mzinho, Senzu, Techno |
|           41 |      698 | 2024-07-11 | CatEvil           | L   | 1.000      | -            | -                | -                | -         |   -31.46 | 910, bLitz, mzinho, Senzu, Techno |
|           40 |      701 | 2024-07-11 | Rare Atom         | L   | 1.000      | -            | -                | -                | -         |   -31.45 | 910, bLitz, mzinho, Senzu, Techno |
|           39 |      705 | 2024-07-11 | Steel Helmet      | W   | 1.000      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           38 |      886 | 2024-06-15 | Falcons           | L   | 0.892      | -            | -                | -                | -         |   -25.64 | 910, bLitz, mzinho, Senzu, Techno |
|           37 |      927 | 2024-06-14 | Aurora            | L   | 0.885      | -            | -                | -                | -         |   -25.95 | 910, bLitz, mzinho, Senzu, Techno |
|           36 |      940 | 2024-06-14 | Party Astronauts  | W   | 0.883      | -            | -                | -                | 1 (0.883) |     0.16 | 910, bLitz, mzinho, Senzu, Techno |
|           35 |     1074 | 2024-06-09 | Ninjas in Pyjamas | W   | 0.852      | 0.715        | 0.256 (0.156)    | 0.477 (0.291)    | 1 (0.852) |     3.87 | 910, bLitz, mzinho, Senzu, Techno |
|           34 |     1152 | 2024-06-08 | Astralis          | W   | 0.845      | 0.715        | 0.394 (0.238)    | -                | 1 (0.845) |     7.00 | 910, bLitz, mzinho, Senzu, Techno |
|           33 |     1254 | 2024-06-06 | Astralis          | L   | 0.832      | -            | -                | -                | -         |   -19.95 | 910, bLitz, mzinho, Senzu, Techno |
|           32 |     1271 | 2024-06-06 | Ninjas in Pyjamas | W   | 0.832      | 0.715        | 0.256 (0.153)    | 0.477 (0.284)    | -         |     3.21 | 910, bLitz, mzinho, Senzu, Techno |
|           31 |     1293 | 2024-06-06 | HEROIC            | W   | 0.830      | 0.715        | 0.234 (0.139)    | -                | -         |     3.46 | 910, bLitz, mzinho, Senzu, Techno |
|           30 |     1323 | 2024-06-05 | ENCE              | W   | 0.825      | -            | -                | -                | -         |     1.10 | 910, bLitz, mzinho, Senzu, Techno |
|           29 |     1340 | 2024-06-05 | Sashi             | W   | 0.824      | 0.715        | -                | 0.973 (0.573)    | -         |     0.49 | 910, bLitz, mzinho, Senzu, Techno |
|           28 |     1426 | 2024-06-02 | BLEED             | W   | 0.804      | -            | -                | -                | -         |     1.36 | 910, bLitz, mzinho, Senzu, Techno |
|           27 |     1460 | 2024-06-01 | BLEED             | W   | 0.797      | -            | -                | -                | -         |     1.24 | 910, bLitz, mzinho, Senzu, Techno |
|           26 |     1539 | 2024-05-29 | Aurora            | W   | 0.777      | 0.500        | 0.429 (0.167)    | 0.800 (0.311)    | -         |     3.06 | 910, bLitz, mzinho, Senzu, Techno |
|           25 |     1560 | 2024-05-28 | Gaimin Gladiators | W   | 0.770      | -            | -                | -                | -         |     0.17 | 910, bLitz, mzinho, Senzu, Techno |
|           24 |     1834 | 2024-05-18 | ATOX              | W   | 0.703      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno |
|           23 |     1869 | 2024-05-16 | Chinggis Warriors | W   | 0.696      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           22 |     2139 | 2024-05-08 | Virtus.pro        | L   | 0.639      | -            | -                | -                | -         |   -15.16 | 910, bLitz, mzinho, Senzu, Techno |
|           21 |     2348 | 2024-04-28 | Vitality          | L   | 0.571      | -            | -                | -                | -         |   -10.56 | 910, bLitz, mzinho, Senzu, Techno |
|           20 |     2425 | 2024-04-25 | G2                | W   | 0.551      | 0.889        | 1.000 (0.490)    | -                | -         |     9.89 | 910, bLitz, mzinho, Senzu, Techno |
|           19 |     2444 | 2024-04-24 | Falcons           | W   | 0.544      | -            | -                | -                | -         |     1.18 | 910, bLitz, mzinho, Senzu, Techno |
|           18 |     2571 | 2024-04-19 | Rare Atom         | W   | 0.511      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno |
|           17 |     2620 | 2024-04-18 | TYLOO             | W   | 0.505      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           16 |     2631 | 2024-04-18 | Rare Atom         | W   | 0.504      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno |
|           15 |     3060 | 2024-04-03 | Lynn Vision       | W   | 0.404      | -            | -                | -                | -         |     0.08 | 910, bLitz, mzinho, Senzu, Techno |
|           14 |     3073 | 2024-04-03 | LYG               | W   | 0.403      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           13 |     3099 | 2024-04-02 | ATOX              | W   | 0.398      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|           12 |     3103 | 2024-04-02 | LYG               | L   | 0.397      | -            | -                | -                | -         |   -12.48 | 910, bLitz, mzinho, Senzu, Techno |
|           11 |     3250 | 2024-03-22 | paiN              | L   | 0.325      | -            | -                | -                | -         |    -9.65 | 910, bLitz, mzinho, Senzu, Techno |
|           10 |     3272 | 2024-03-21 | Vitality          | L   | 0.319      | -            | -                | -                | -         |    -6.23 | 910, bLitz, mzinho, Senzu, Techno |
|            9 |     3282 | 2024-03-21 | Natus Vincere     | L   | 0.318      | -            | -                | -                | -         |    -4.38 | 910, bLitz, mzinho, Senzu, Techno |
|            8 |     3301 | 2024-03-20 | Legacy            | W   | 0.311      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|            7 |     3319 | 2024-03-19 | Lynn Vision       | W   | 0.304      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|            6 |     3325 | 2024-03-18 | AMKAL             | W   | 0.298      | -            | -                | -                | -         |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|            5 |     3347 | 2024-03-17 | Gaimin Gladiators | L   | 0.293      | -            | -                | -                | -         |    -9.18 | 910, bLitz, mzinho, Senzu, Techno |
|            4 |     3360 | 2024-03-17 | Eternal Fire      | L   | 0.291      | -            | -                | -                | -         |    -7.24 | 910, bLitz, mzinho, Senzu, Techno |
|            3 |     3794 | 2024-02-27 | Lynn Vision       | W   | 0.168      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|            2 |     3830 | 2024-02-25 | FlyQuest          | W   | 0.156      | -            | -                | -                | -         |     0.06 | 910, bLitz, mzinho, Senzu, Techno |
|            1 |     3836 | 2024-02-25 | MAG               | W   | 0.155      | -            | -                | -                | -         |     0.00 | 910, bLitz, mzinho, Senzu, Techno |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($331,608.80)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $70,000.00     | $70,000.00      |
| 2024-07-21 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-16 |      0.898 | $3,000.00      | $2,694.68       |
| 2024-06-09 |      0.852 | $200,000.00    | $170,367.59     |
| 2024-06-02 |      0.804 | $50,000.00     | $40,194.91      |
| 2024-05-12 |      0.665 | $23,500.00     | $15,631.53      |
| 2024-03-31 |      0.386 | $20,000.00     | $7,720.09       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
