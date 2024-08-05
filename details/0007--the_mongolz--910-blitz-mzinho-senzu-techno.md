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
Final Rank Value (1698.6) = Starting Rank Value (1951.7) + Head To Head Adjustments (-253.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.619[<sup>2</sup>](#table1)
- Opponent Network: 0.408[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.757<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1951.7
- 400 + ( ( 0.757 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1951.7


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
|           53 |      296 | 2024-07-28 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -26.58 | 910, bLitz, mzinho, Senzu, Techno |
|           52 |      314 | 2024-07-28 | Eternal Fire      | W   | 1.000      | 0.650        | 0.740 (0.481)    | 0.449 (0.292)    | 1 (1.000) |    11.78 | 910, bLitz, mzinho, Senzu, Techno |
|           51 |      328 | 2024-07-27 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.465 (0.303)    | 1 (1.000) |     1.77 | 910, bLitz, mzinho, Senzu, Techno |
|           50 |      358 | 2024-07-26 | Aurora            | W   | 1.000      | 0.650        | 0.422 (0.274)    | 0.779 (0.506)    | 1 (1.000) |     6.46 | 910, bLitz, mzinho, Senzu, Techno |
|           49 |      396 | 2024-07-25 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -28.51 | 910, bLitz, mzinho, Senzu, Techno |
|           48 |      418 | 2024-07-24 | ENCE              | W   | 1.000      | 0.650        | -                | 0.432 (0.281)    | 1 (1.000) |     3.88 | 910, bLitz, mzinho, Senzu, Techno |
|           47 |      429 | 2024-07-24 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -30.77 | 910, bLitz, mzinho, Senzu, Techno |
|           46 |      476 | 2024-07-23 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           45 |      627 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |   -22.74 | 910, bLitz, mzinho, Senzu, Techno |
|           44 |      631 | 2024-07-18 | M80               | W   | 1.000      | 1.000        | 0.188 (0.188)    | 0.577 (0.577)    | 1 (1.000) |     1.65 | 910, bLitz, mzinho, Senzu, Techno |
|           43 |      643 | 2024-07-18 | MIBR              | W   | 1.000      | 1.000        | 0.208 (0.208)    | 0.649 (0.649)    | 1 (1.000) |     3.18 | 910, bLitz, mzinho, Senzu, Techno |
|           42 |      717 | 2024-07-17 | G2                | L   | 1.000      | -            | -                | -                | -         |    -9.14 | 910, bLitz, mzinho, Senzu, Techno |
|           41 |      872 | 2024-07-11 | CatEvil           | L   | 1.000      | -            | -                | -                | -         |   -31.46 | 910, bLitz, mzinho, Senzu, Techno |
|           40 |      875 | 2024-07-11 | Rare Atom         | L   | 1.000      | -            | -                | -                | -         |   -31.37 | 910, bLitz, mzinho, Senzu, Techno |
|           39 |      879 | 2024-07-11 | Steel Helmet      | W   | 1.000      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           38 |     1060 | 2024-06-15 | Falcons           | L   | 0.859      | -            | -                | -                | -         |   -25.03 | 910, bLitz, mzinho, Senzu, Techno |
|           37 |     1101 | 2024-06-14 | Aurora            | L   | 0.853      | -            | -                | -                | -         |   -24.97 | 910, bLitz, mzinho, Senzu, Techno |
|           36 |     1114 | 2024-06-14 | Party Astronauts  | W   | 0.851      | -            | -                | -                | 1 (0.851) |     0.15 | 910, bLitz, mzinho, Senzu, Techno |
|           35 |     1248 | 2024-06-09 | Ninjas in Pyjamas | W   | 0.819      | 0.715        | 0.254 (0.149)    | 0.544 (0.319)    | 1 (0.819) |     4.23 | 910, bLitz, mzinho, Senzu, Techno |
|           34 |     1326 | 2024-06-08 | Astralis          | W   | 0.812      | 0.715        | 0.389 (0.226)    | -                | 1 (0.812) |     7.31 | 910, bLitz, mzinho, Senzu, Techno |
|           33 |     1428 | 2024-06-06 | Astralis          | L   | 0.800      | -            | -                | -                | -         |   -18.57 | 910, bLitz, mzinho, Senzu, Techno |
|           32 |     1445 | 2024-06-06 | Ninjas in Pyjamas | W   | 0.799      | 0.715        | 0.254 (0.145)    | 0.544 (0.311)    | -         |     3.63 | 910, bLitz, mzinho, Senzu, Techno |
|           31 |     1467 | 2024-06-06 | HEROIC            | W   | 0.797      | 0.715        | 0.225 (0.128)    | -                | -         |     3.13 | 910, bLitz, mzinho, Senzu, Techno |
|           30 |     1497 | 2024-06-05 | ENCE              | W   | 0.793      | -            | -                | -                | -         |     1.08 | 910, bLitz, mzinho, Senzu, Techno |
|           29 |     1514 | 2024-06-05 | Sashi             | W   | 0.791      | 0.715        | -                | 0.983 (0.557)    | -         |     0.46 | 910, bLitz, mzinho, Senzu, Techno |
|           28 |     1600 | 2024-06-02 | BLEED             | W   | 0.772      | -            | -                | -                | -         |     1.30 | 910, bLitz, mzinho, Senzu, Techno |
|           27 |     1634 | 2024-06-01 | BLEED             | W   | 0.765      | -            | -                | -                | -         |     1.19 | 910, bLitz, mzinho, Senzu, Techno |
|           26 |     1713 | 2024-05-29 | Aurora            | W   | 0.745      | 0.500        | 0.422 (0.157)    | 0.779 (0.290)    | -         |     2.95 | 910, bLitz, mzinho, Senzu, Techno |
|           25 |     1734 | 2024-05-28 | Gaimin Gladiators | W   | 0.738      | -            | -                | -                | -         |     0.15 | 910, bLitz, mzinho, Senzu, Techno |
|           24 |     2008 | 2024-05-18 | ATOX              | W   | 0.671      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno |
|           23 |     2043 | 2024-05-16 | Chinggis Warriors | W   | 0.664      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|           22 |     2313 | 2024-05-08 | Virtus.pro        | L   | 0.607      | -            | -                | -                | -         |   -14.83 | 910, bLitz, mzinho, Senzu, Techno |
|           21 |     2522 | 2024-04-28 | Vitality          | L   | 0.538      | -            | -                | -                | -         |   -10.04 | 910, bLitz, mzinho, Senzu, Techno |
|           20 |     2599 | 2024-04-25 | G2                | W   | 0.518      | 0.889        | 1.000 (0.461)    | -                | -         |     9.46 | 910, bLitz, mzinho, Senzu, Techno |
|           19 |     2618 | 2024-04-24 | Falcons           | W   | 0.512      | -            | -                | -                | -         |     0.95 | 910, bLitz, mzinho, Senzu, Techno |
|           18 |     2745 | 2024-04-19 | Rare Atom         | W   | 0.479      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|           17 |     2794 | 2024-04-18 | TYLOO             | W   | 0.472      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           16 |     2805 | 2024-04-18 | Rare Atom         | W   | 0.471      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|           15 |     3234 | 2024-04-03 | Lynn Vision       | W   | 0.372      | -            | -                | -                | -         |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           14 |     3247 | 2024-04-03 | LYG               | W   | 0.371      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno |
|           13 |     3273 | 2024-04-02 | ATOX              | W   | 0.365      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           12 |     3277 | 2024-04-02 | LYG               | L   | 0.364      | -            | -                | -                | -         |   -11.46 | 910, bLitz, mzinho, Senzu, Techno |
|           11 |     3424 | 2024-03-22 | paiN              | L   | 0.293      | -            | -                | -                | -         |    -8.74 | 910, bLitz, mzinho, Senzu, Techno |
|           10 |     3446 | 2024-03-21 | Vitality          | L   | 0.287      | -            | -                | -                | -         |    -5.60 | 910, bLitz, mzinho, Senzu, Techno |
|            9 |     3456 | 2024-03-21 | Natus Vincere     | L   | 0.285      | -            | -                | -                | -         |    -4.05 | 910, bLitz, mzinho, Senzu, Techno |
|            8 |     3475 | 2024-03-20 | Legacy            | W   | 0.279      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|            7 |     3493 | 2024-03-19 | Lynn Vision       | W   | 0.272      | -            | -                | -                | -         |     0.06 | 910, bLitz, mzinho, Senzu, Techno |
|            6 |     3499 | 2024-03-18 | AMKAL             | W   | 0.266      | -            | -                | -                | -         |     0.09 | 910, bLitz, mzinho, Senzu, Techno |
|            5 |     3521 | 2024-03-17 | Gaimin Gladiators | L   | 0.260      | -            | -                | -                | -         |    -8.16 | 910, bLitz, mzinho, Senzu, Techno |
|            4 |     3534 | 2024-03-17 | Eternal Fire      | L   | 0.259      | -            | -                | -                | -         |    -6.57 | 910, bLitz, mzinho, Senzu, Techno |
|            3 |     3968 | 2024-02-27 | Lynn Vision       | W   | 0.136      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|            2 |     4004 | 2024-02-25 | FlyQuest          | W   | 0.124      | -            | -                | -                | -         |     0.04 | 910, bLitz, mzinho, Senzu, Techno |
|            1 |     4010 | 2024-02-25 | MAG               | W   | 0.122      | -            | -                | -                | -         |     0.00 | 910, bLitz, mzinho, Senzu, Techno |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($322,004.12)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $70,000.00     | $70,000.00      |
| 2024-07-21 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-16 |      0.866 | $3,000.00      | $2,597.50       |
| 2024-06-09 |      0.819 | $200,000.00    | $163,888.89     |
| 2024-06-02 |      0.772 | $50,000.00     | $38,575.23      |
| 2024-05-12 |      0.633 | $23,500.00     | $14,870.28      |
| 2024-03-31 |      0.354 | $20,000.00     | $7,072.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
