### Roster Details<br />
Team Name: The MongolZ<br />
Roster: 910, bLitz, mzinho, Senzu, Techno<br />
Global Rank: [7](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [1]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1696.1<br />
<br />
Final Rank Value (1696.1) = Starting Rank Value (1950.2) + Head To Head Adjustments (-254.1)<br />

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
- 400 + ( ( 0.758 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1950.2


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
|           53 |      271 | 2024-07-28 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -26.63 | 910, bLitz, mzinho, Senzu, Techno |
|           52 |      289 | 2024-07-28 | Eternal Fire      | W   | 1.000      | 0.650        | 0.742 (0.483)    | 0.458 (0.298)    | 1 (1.000) |    11.89 | 910, bLitz, mzinho, Senzu, Techno |
|           51 |      303 | 2024-07-27 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.475 (0.309)    | 1 (1.000) |     1.80 | 910, bLitz, mzinho, Senzu, Techno |
|           50 |      333 | 2024-07-26 | Aurora            | W   | 1.000      | 0.650        | 0.423 (0.275)    | 0.793 (0.515)    | 1 (1.000) |     6.40 | 910, bLitz, mzinho, Senzu, Techno |
|           49 |      371 | 2024-07-25 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -28.53 | 910, bLitz, mzinho, Senzu, Techno |
|           48 |      393 | 2024-07-24 | ENCE              | W   | 1.000      | 0.650        | -                | 0.400 (0.260)    | 1 (1.000) |     3.79 | 910, bLitz, mzinho, Senzu, Techno |
|           47 |      404 | 2024-07-24 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -30.77 | 910, bLitz, mzinho, Senzu, Techno |
|           46 |      451 | 2024-07-23 | True Rippers      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           45 |      602 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |   -22.73 | 910, bLitz, mzinho, Senzu, Techno |
|           44 |      606 | 2024-07-18 | M80               | W   | 1.000      | 1.000        | 0.188 (0.188)    | 0.587 (0.587)    | 1 (1.000) |     1.69 | 910, bLitz, mzinho, Senzu, Techno |
|           43 |      618 | 2024-07-18 | MIBR              | W   | 1.000      | 1.000        | 0.209 (0.209)    | 0.659 (0.659)    | 1 (1.000) |     3.25 | 910, bLitz, mzinho, Senzu, Techno |
|           42 |      692 | 2024-07-17 | G2                | L   | 1.000      | -            | -                | -                | -         |    -9.07 | 910, bLitz, mzinho, Senzu, Techno |
|           41 |      847 | 2024-07-11 | CatEvil           | L   | 1.000      | -            | -                | -                | -         |   -31.46 | 910, bLitz, mzinho, Senzu, Techno |
|           40 |      850 | 2024-07-11 | Rare Atom         | L   | 1.000      | -            | -                | -                | -         |   -31.43 | 910, bLitz, mzinho, Senzu, Techno |
|           39 |      854 | 2024-07-11 | Steel Helmet      | W   | 1.000      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           38 |     1035 | 2024-06-15 | Falcons           | L   | 0.866      | -            | -                | -                | -         |   -25.18 | 910, bLitz, mzinho, Senzu, Techno |
|           37 |     1076 | 2024-06-14 | Aurora            | L   | 0.859      | -            | -                | -                | -         |   -25.20 | 910, bLitz, mzinho, Senzu, Techno |
|           36 |     1089 | 2024-06-14 | Party Astronauts  | W   | 0.858      | -            | -                | -                | 1 (0.858) |     0.15 | 910, bLitz, mzinho, Senzu, Techno |
|           35 |     1223 | 2024-06-09 | Ninjas in Pyjamas | W   | 0.826      | 0.715        | 0.254 (0.150)    | 0.553 (0.327)    | 1 (0.826) |     4.28 | 910, bLitz, mzinho, Senzu, Techno |
|           34 |     1301 | 2024-06-08 | Astralis          | W   | 0.819      | 0.715        | 0.390 (0.229)    | -                | 1 (0.819) |     7.46 | 910, bLitz, mzinho, Senzu, Techno |
|           33 |     1403 | 2024-06-06 | Astralis          | L   | 0.807      | -            | -                | -                | -         |   -18.64 | 910, bLitz, mzinho, Senzu, Techno |
|           32 |     1420 | 2024-06-06 | Ninjas in Pyjamas | W   | 0.806      | 0.715        | 0.254 (0.147)    | 0.553 (0.319)    | -         |     3.67 | 910, bLitz, mzinho, Senzu, Techno |
|           31 |     1442 | 2024-06-06 | HEROIC            | W   | 0.804      | 0.715        | 0.229 (0.131)    | -                | -         |     3.22 | 910, bLitz, mzinho, Senzu, Techno |
|           30 |     1472 | 2024-06-05 | ENCE              | W   | 0.800      | -            | -                | -                | -         |     1.05 | 910, bLitz, mzinho, Senzu, Techno |
|           29 |     1489 | 2024-06-05 | Sashi             | W   | 0.798      | 0.715        | -                | 0.962 (0.549)    | -         |     0.47 | 910, bLitz, mzinho, Senzu, Techno |
|           28 |     1575 | 2024-06-02 | BLEED             | W   | 0.778      | -            | -                | -                | -         |     1.30 | 910, bLitz, mzinho, Senzu, Techno |
|           27 |     1609 | 2024-06-01 | BLEED             | W   | 0.772      | -            | -                | -                | -         |     1.19 | 910, bLitz, mzinho, Senzu, Techno |
|           26 |     1688 | 2024-05-29 | Aurora            | W   | 0.752      | 0.500        | 0.423 (0.159)    | 0.793 (0.298)    | -         |     2.94 | 910, bLitz, mzinho, Senzu, Techno |
|           25 |     1709 | 2024-05-28 | Gaimin Gladiators | W   | 0.745      | -            | -                | -                | -         |     0.15 | 910, bLitz, mzinho, Senzu, Techno |
|           24 |     1983 | 2024-05-18 | ATOX              | W   | 0.678      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno |
|           23 |     2018 | 2024-05-16 | Chinggis Warriors | W   | 0.671      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           22 |     2288 | 2024-05-08 | Virtus.pro        | L   | 0.614      | -            | -                | -                | -         |   -14.91 | 910, bLitz, mzinho, Senzu, Techno |
|           21 |     2497 | 2024-04-28 | Vitality          | L   | 0.545      | -            | -                | -                | -         |   -10.09 | 910, bLitz, mzinho, Senzu, Techno |
|           20 |     2574 | 2024-04-25 | G2                | W   | 0.525      | 0.889        | 1.000 (0.467)    | -                | -         |     9.63 | 910, bLitz, mzinho, Senzu, Techno |
|           19 |     2593 | 2024-04-24 | Falcons           | W   | 0.519      | -            | -                | -                | -         |     0.98 | 910, bLitz, mzinho, Senzu, Techno |
|           18 |     2720 | 2024-04-19 | Rare Atom         | W   | 0.486      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           17 |     2769 | 2024-04-18 | TYLOO             | W   | 0.479      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           16 |     2780 | 2024-04-18 | Rare Atom         | W   | 0.478      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           15 |     3209 | 2024-04-03 | Lynn Vision       | W   | 0.379      | -            | -                | -                | -         |     0.10 | 910, bLitz, mzinho, Senzu, Techno |
|           14 |     3222 | 2024-04-03 | LYG               | W   | 0.378      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           13 |     3248 | 2024-04-02 | ATOX              | W   | 0.372      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           12 |     3252 | 2024-04-02 | LYG               | L   | 0.371      | -            | -                | -                | -         |   -11.68 | 910, bLitz, mzinho, Senzu, Techno |
|           11 |     3399 | 2024-03-22 | paiN              | L   | 0.299      | -            | -                | -                | -         |    -8.93 | 910, bLitz, mzinho, Senzu, Techno |
|           10 |     3421 | 2024-03-21 | Vitality          | L   | 0.294      | -            | -                | -                | -         |    -5.70 | 910, bLitz, mzinho, Senzu, Techno |
|            9 |     3431 | 2024-03-21 | Natus Vincere     | L   | 0.292      | -            | -                | -                | -         |    -4.11 | 910, bLitz, mzinho, Senzu, Techno |
|            8 |     3450 | 2024-03-20 | Legacy            | W   | 0.285      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|            7 |     3468 | 2024-03-19 | Lynn Vision       | W   | 0.279      | -            | -                | -                | -         |     0.06 | 910, bLitz, mzinho, Senzu, Techno |
|            6 |     3474 | 2024-03-18 | AMKAL             | W   | 0.273      | -            | -                | -                | -         |     0.09 | 910, bLitz, mzinho, Senzu, Techno |
|            5 |     3496 | 2024-03-17 | Gaimin Gladiators | L   | 0.267      | -            | -                | -                | -         |    -8.38 | 910, bLitz, mzinho, Senzu, Techno |
|            4 |     3509 | 2024-03-17 | Eternal Fire      | L   | 0.265      | -            | -                | -                | -         |    -6.72 | 910, bLitz, mzinho, Senzu, Techno |
|            3 |     3943 | 2024-02-27 | Lynn Vision       | W   | 0.143      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|            2 |     3979 | 2024-02-25 | FlyQuest          | W   | 0.131      | -            | -                | -                | -         |     0.05 | 910, bLitz, mzinho, Senzu, Techno |
|            1 |     3985 | 2024-02-25 | MAG               | W   | 0.129      | -            | -                | -                | -         |     0.00 | 910, bLitz, mzinho, Senzu, Techno |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($324,028.83)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $70,000.00     | $70,000.00      |
| 2024-07-21 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-06-16 |      0.873 | $3,000.00      | $2,617.99       |
| 2024-06-09 |      0.826 | $200,000.00    | $165,254.63     |
| 2024-06-02 |      0.778 | $50,000.00     | $38,916.67      |
| 2024-05-12 |      0.640 | $23,500.00     | $15,030.75      |
| 2024-03-31 |      0.360 | $20,000.00     | $7,208.80       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
