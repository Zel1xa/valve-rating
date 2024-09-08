### Roster Details<br />
Team Name: The MongolZ<br />
Roster: 910, bLitz, mzinho, Senzu, Techno<br />
Global Rank: [8](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [1]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1654.2<br />
<br />
Final Rank Value (1654.2) = Starting Rank Value (1886.8) + Head To Head Adjustments (-232.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.940[<sup>1</sup>](#table2)
- Bounty Collected: 0.678[<sup>2</sup>](#table1)
- Opponent Network: 0.453[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.768<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1886.8
- 400 + ( ( 0.768 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 1886.8


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
|           61 |        2 | 2024-09-08 | 3DMAX             | W   | 1.000      | 0.889        | 0.509 (0.452)    | 0.951 (0.846)    | 1 (1.000) |     7.17 | 910, bLitz, mzinho, Senzu, Techno |
|           60 |       25 | 2024-09-07 | 9z                | W   | 1.000      | 0.889        | 0.362 (0.322)    | 0.530 (0.471)    | 1 (1.000) |     5.93 | 910, bLitz, mzinho, Senzu, Techno |
|           59 |       52 | 2024-09-06 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -5.50 | 910, bLitz, mzinho, Senzu, Techno |
|           58 |       91 | 2024-09-05 | KOI               | W   | 1.000      | 0.889        | -                | 0.317 (0.282)    | 1 (1.000) |     0.56 | 910, bLitz, mzinho, Senzu, Techno |
|           57 |      126 | 2024-09-04 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -25.35 | 910, bLitz, mzinho, Senzu, Techno |
|           56 |      925 | 2024-08-12 | paiN              | L   | 1.000      | -            | -                | -                | -         |   -21.14 | 910, bLitz, mzinho, Senzu, Techno |
|           55 |      956 | 2024-08-11 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -25.06 | 910, bLitz, mzinho, Senzu, Techno |
|           54 |      973 | 2024-08-10 | Spirit            | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.557 (0.557)    | 1 (1.000) |    25.12 | 910, bLitz, mzinho, Senzu, Techno |
|           53 |      998 | 2024-08-09 | Eternal Fire      | W   | 1.000      | 0.143        | 0.972 (0.139)    | -                | 1 (1.000) |    18.23 | 910, bLitz, mzinho, Senzu, Techno |
|           52 |     1035 | 2024-08-08 | FlyQuest          | W   | 0.993      | -            | -                | -                | 1 (0.993) |     0.86 | 910, bLitz, mzinho, Senzu, Techno |
|           51 |     1093 | 2024-08-07 | SAW               | L   | 0.985      | -            | -                | -                | -         |   -25.87 | 910, bLitz, mzinho, Senzu, Techno |
|           50 |     1435 | 2024-07-28 | 3DMAX             | L   | 0.921      | -            | -                | -                | -         |   -22.35 | 910, bLitz, mzinho, Senzu, Techno |
|           49 |     1453 | 2024-07-28 | Eternal Fire      | W   | 0.919      | 0.650        | 0.972 (0.580)    | 0.700 (0.418)    | 1 (0.919) |    17.16 | 910, bLitz, mzinho, Senzu, Techno |
|           48 |     1467 | 2024-07-27 | AMKAL             | W   | 0.913      | 0.650        | -                | 0.397 (0.235)    | 1 (0.913) |     1.25 | 910, bLitz, mzinho, Senzu, Techno |
|           47 |     1497 | 2024-07-26 | Aurora            | W   | 0.906      | 0.650        | 0.290 (0.171)    | 0.603 (0.355)    | 1 (0.906) |     3.76 | 910, bLitz, mzinho, Senzu, Techno |
|           46 |     1535 | 2024-07-25 | BLEED             | L   | 0.899      | -            | -                | -                | -         |   -26.87 | 910, bLitz, mzinho, Senzu, Techno |
|           45 |     1557 | 2024-07-24 | ENCE              | W   | 0.894      | -            | -                | -                | 1 (0.894) |     1.62 | 910, bLitz, mzinho, Senzu, Techno |
|           44 |     1568 | 2024-07-24 | PARIVISION        | L   | 0.893      | -            | -                | -                | -         |   -27.48 | 910, bLitz, mzinho, Senzu, Techno |
|           43 |     1615 | 2024-07-23 | True Rippers      | W   | 0.885      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno |
|           42 |     1766 | 2024-07-18 | FURIA             | L   | 0.855      | -            | -                | -                | -         |   -20.12 | 910, bLitz, mzinho, Senzu, Techno |
|           41 |     1770 | 2024-07-18 | M80               | W   | 0.854      | 1.000        | 0.169 (0.145)    | 0.521 (0.445)    | -         |     0.81 | 910, bLitz, mzinho, Senzu, Techno |
|           40 |     1782 | 2024-07-18 | MIBR              | W   | 0.853      | 1.000        | 0.156 (0.133)    | 0.644 (0.550)    | -         |     2.45 | 910, bLitz, mzinho, Senzu, Techno |
|           39 |     1856 | 2024-07-17 | G2                | L   | 0.846      | -            | -                | -                | -         |    -7.15 | 910, bLitz, mzinho, Senzu, Techno |
|           38 |     2014 | 2024-07-11 | CatEvil           | L   | 0.807      | -            | -                | -                | -         |   -25.38 | 910, bLitz, mzinho, Senzu, Techno |
|           37 |     2017 | 2024-07-11 | Rare Atom         | L   | 0.806      | -            | -                | -                | -         |   -25.28 | 910, bLitz, mzinho, Senzu, Techno |
|           36 |     2021 | 2024-07-11 | Steel Helmet      | W   | 0.805      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           35 |     2202 | 2024-06-15 | Falcons           | L   | 0.634      | -            | -                | -                | -         |   -17.48 | 910, bLitz, mzinho, Senzu, Techno |
|           34 |     2243 | 2024-06-14 | Aurora            | L   | 0.627      | -            | -                | -                | -         |   -18.78 | 910, bLitz, mzinho, Senzu, Techno |
|           33 |     2256 | 2024-06-14 | Party Astronauts  | W   | 0.625      | -            | -                | -                | -         |     0.09 | 910, bLitz, mzinho, Senzu, Techno |
|           32 |     2390 | 2024-06-09 | Ninjas in Pyjamas | W   | 0.594      | -            | -                | -                | -         |     1.52 | 910, bLitz, mzinho, Senzu, Techno |
|           31 |     2468 | 2024-06-08 | Astralis          | W   | 0.587      | 0.715        | 0.343 (0.144)    | -                | -         |     2.68 | 910, bLitz, mzinho, Senzu, Techno |
|           30 |     2570 | 2024-06-06 | Astralis          | L   | 0.574      | -            | -                | -                | -         |   -15.77 | 910, bLitz, mzinho, Senzu, Techno |
|           29 |     2587 | 2024-06-06 | Ninjas in Pyjamas | W   | 0.574      | -            | -                | -                | -         |     1.24 | 910, bLitz, mzinho, Senzu, Techno |
|           28 |     2609 | 2024-06-06 | HEROIC            | W   | 0.572      | -            | -                | -                | -         |     1.22 | 910, bLitz, mzinho, Senzu, Techno |
|           27 |     2639 | 2024-06-05 | ENCE              | W   | 0.567      | -            | -                | -                | -         |     0.37 | 910, bLitz, mzinho, Senzu, Techno |
|           26 |     2656 | 2024-06-05 | Sashi             | W   | 0.566      | 0.715        | -                | 0.926 (0.375)    | -         |     0.24 | 910, bLitz, mzinho, Senzu, Techno |
|           25 |     2742 | 2024-06-02 | BLEED             | W   | 0.546      | -            | -                | -                | -         |     0.43 | 910, bLitz, mzinho, Senzu, Techno |
|           24 |     2776 | 2024-06-01 | BLEED             | W   | 0.539      | -            | -                | -                | -         |     0.40 | 910, bLitz, mzinho, Senzu, Techno |
|           23 |     2855 | 2024-05-29 | Aurora            | W   | 0.519      | -            | -                | -                | -         |     0.96 | 910, bLitz, mzinho, Senzu, Techno |
|           22 |     2876 | 2024-05-28 | Gaimin Gladiators | W   | 0.513      | -            | -                | -                | -         |     0.07 | 910, bLitz, mzinho, Senzu, Techno |
|           21 |     3150 | 2024-05-18 | ATOX              | W   | 0.445      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           20 |     3185 | 2024-05-16 | Chinggis Warriors | W   | 0.438      | -            | -                | -                | -         |     0.06 | 910, bLitz, mzinho, Senzu, Techno |
|           19 |     3455 | 2024-05-08 | Virtus.pro        | L   | 0.381      | -            | -                | -                | -         |   -10.59 | 910, bLitz, mzinho, Senzu, Techno |
|           18 |     3664 | 2024-04-28 | Vitality          | L   | 0.313      | -            | -                | -                | -         |    -4.54 | 910, bLitz, mzinho, Senzu, Techno |
|           17 |     3741 | 2024-04-25 | G2                | W   | 0.293      | 0.889        | 1.000 (0.260)    | -                | -         |     5.70 | 910, bLitz, mzinho, Senzu, Techno |
|           16 |     3760 | 2024-04-24 | Falcons           | W   | 0.286      | -            | -                | -                | -         |     1.03 | 910, bLitz, mzinho, Senzu, Techno |
|           15 |     3887 | 2024-04-19 | Rare Atom         | W   | 0.253      | -            | -                | -                | -         |     0.03 | 910, bLitz, mzinho, Senzu, Techno |
|           14 |     3936 | 2024-04-18 | TYLOO             | W   | 0.247      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno |
|           13 |     3947 | 2024-04-18 | Rare Atom         | W   | 0.246      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           12 |     4376 | 2024-04-03 | Lynn Vision       | W   | 0.147      | -            | -                | -                | -         |     0.02 | 910, bLitz, mzinho, Senzu, Techno |
|           11 |     4389 | 2024-04-03 | LYG               | W   | 0.145      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno |
|           10 |     4415 | 2024-04-02 | ATOX              | W   | 0.140      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno |
|            9 |     4419 | 2024-04-02 | LYG               | L   | 0.139      | -            | -                | -                | -         |    -4.37 | 910, bLitz, mzinho, Senzu, Techno |
|            8 |     4566 | 2024-03-22 | paiN              | L   | 0.067      | -            | -                | -                | -         |    -1.58 | 910, bLitz, mzinho, Senzu, Techno |
|            7 |     4588 | 2024-03-21 | Vitality          | L   | 0.061      | -            | -                | -                | -         |    -0.89 | 910, bLitz, mzinho, Senzu, Techno |
|            6 |     4598 | 2024-03-21 | Natus Vincere     | L   | 0.060      | -            | -                | -                | -         |    -0.65 | 910, bLitz, mzinho, Senzu, Techno |
|            5 |     4617 | 2024-03-20 | Legacy            | W   | 0.053      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno |
|            4 |     4635 | 2024-03-19 | Lynn Vision       | W   | 0.046      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno |
|            3 |     4641 | 2024-03-18 | AMKAL             | W   | 0.040      | -            | -                | -                | -         |     0.01 | 910, bLitz, mzinho, Senzu, Techno |
|            2 |     4663 | 2024-03-17 | Gaimin Gladiators | L   | 0.035      | -            | -                | -                | -         |    -1.09 | 910, bLitz, mzinho, Senzu, Techno |
|            1 |     4676 | 2024-03-17 | Eternal Fire      | L   | 0.033      | -            | -                | -                | -         |    -0.55 | 910, bLitz, mzinho, Senzu, Techno |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($262,453.29)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.86) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-18 |      1.000 | $16,000.00     | $16,000.00      |
| 2024-07-28 |      0.921 | $70,000.00     | $64,458.33      |
| 2024-07-21 |      0.875 | $25,000.00     | $21,868.06      |
| 2024-06-16 |      0.640 | $3,000.00      | $1,920.83       |
| 2024-06-09 |      0.594 | $200,000.00    | $118,777.78     |
| 2024-06-02 |      0.546 | $50,000.00     | $27,297.45      |
| 2024-05-12 |      0.407 | $23,500.00     | $9,569.72       |
| 2024-03-31 |      0.128 | $20,000.00     | $2,561.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
