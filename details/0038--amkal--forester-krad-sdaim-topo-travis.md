### Roster Details<br />
Team Name: AMKAL<br />
Roster: Forester, Krad, Sdaim, topo, TRAVIS<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1145.2<br />
<br />
Final Rank Value (1145.2) = Starting Rank Value (1146.9) + Head To Head Adjustments (-1.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.530[<sup>1</sup>](#table2)
- Bounty Collected: 0.443[<sup>2</sup>](#table1)
- Opponent Network: 0.237[<sup>2</sup>](#table1)
- LAN Wins: 0.251[<sup>2</sup>](#table1)

The average of these factors is 0.365<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1146.9
- 400 + ( ( 0.365 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1146.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           57 |        5 | 2024-08-04 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -24.08 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           56 |       84 | 2024-08-01 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -28.96 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           55 |      141 | 2024-07-31 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -10.43 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           54 |      279 | 2024-07-27 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -1.81 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           53 |      311 | 2024-07-26 | DMS               | W   | 1.000      | 0.650        | -                | 0.446 (0.290)    | 1 (1.000) |     4.94 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           52 |      346 | 2024-07-25 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -2.75 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           51 |      371 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.267 (0.174)    | 1 (1.000) |     4.21 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           50 |      381 | 2024-07-24 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -9.61 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           49 |     1185 | 2024-06-09 | Monte             | W   | 0.828      | -            | -                | -                | 0 (0.000) |     7.16 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           48 |     1214 | 2024-06-09 | B8                | W   | 0.827      | 0.143        | 0.165 (0.020)    | 0.912 (0.108)    | 0 (0.000) |    10.70 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     1272 | 2024-06-08 | Monte             | W   | 0.820      | -            | -                | -                | 0 (0.000) |     6.96 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     1276 | 2024-06-08 | 1WIN              | W   | 0.820      | -            | -                | -                | 0 (0.000) |     6.14 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     1581 | 2024-06-01 | MOUZ NXT          | L   | 0.773      | -            | -                | -                | -         |   -15.56 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     1598 | 2024-05-31 | Permitta          | W   | 0.768      | 0.435        | -                | 0.876 (0.292)    | 0 (0.000) |     4.12 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     1847 | 2024-05-21 | GamerLegion       | L   | 0.702      | -            | -                | -                | -         |   -11.89 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     1914 | 2024-05-19 | paiN              | W   | 0.687      | 0.769        | 0.327 (0.173)    | 0.866 (0.458)    | -         |    15.97 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     1918 | 2024-05-19 | Liquid            | L   | 0.687      | -            | -                | -                | -         |    -2.15 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     1939 | 2024-05-18 | paiN              | W   | 0.681      | 0.769        | 0.327 (0.171)    | 0.866 (0.454)    | -         |    16.45 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2336 | 2024-05-04 | BetBoom           | W   | 0.588      | 0.435        | 0.251 (0.064)    | 0.541 (0.138)    | -         |    14.72 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     2346 | 2024-05-04 | Metizport         | W   | 0.586      | 0.435        | -                | 0.417 (0.106)    | -         |     4.53 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     2356 | 2024-05-03 | Gaimin Gladiators | W   | 0.580      | 0.435        | 0.038 (0.010)    | -                | -         |     5.39 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     2371 | 2024-05-02 | BLEED             | W   | 0.575      | 0.435        | 0.091 (0.023)    | -                | -         |     7.18 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     2404 | 2024-05-01 | fnatic            | L   | 0.567      | -            | -                | -                | -         |    -1.97 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     2422 | 2024-04-30 | Gaimin Gladiators | W   | 0.561      | -            | -                | -                | -         |     5.27 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     2447 | 2024-04-29 | Permitta          | W   | 0.554      | 0.384        | -                | 0.876 (0.186)    | -         |     4.56 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     2572 | 2024-04-24 | Nexus             | W   | 0.519      | -            | -                | -                | -         |     2.62 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     2619 | 2024-04-21 | Gaimin Gladiators | L   | 0.500      | -            | -                | -                | -         |   -10.29 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     2694 | 2024-04-19 | ENCE              | W   | 0.487      | 0.384        | 0.169 (0.032)    | -                | -         |    12.79 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     2738 | 2024-04-18 | Apeks             | L   | 0.481      | -            | -                | -                | -         |   -11.60 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     2747 | 2024-04-18 | ex-Guild Eagles   | W   | 0.480      | -            | -                | -                | -         |     2.26 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           27 |     2822 | 2024-04-16 | B8                | W   | 0.466      | 0.384        | 0.165 (0.030)    | 0.912 (0.163)    | -         |     5.44 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           26 |     2874 | 2024-04-12 | Aurora            | L   | 0.442      | -            | -                | -                | -         |    -0.80 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           25 |     2911 | 2024-04-11 | BetBoom           | W   | 0.433      | 0.143        | 0.251 (0.016)    | -                | -         |    11.36 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           24 |     2943 | 2024-04-10 | Apeks             | W   | 0.428      | -            | -                | -                | -         |     3.41 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           23 |     2957 | 2024-04-10 | Enterprise        | L   | 0.426      | -            | -                | -                | -         |   -10.33 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           22 |     3166 | 2024-04-03 | Insilio           | W   | 0.382      | -            | -                | -                | -         |     2.74 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           21 |     3177 | 2024-04-03 | ex-Guild Eagles   | W   | 0.380      | -            | -                | -                | -         |     1.74 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           20 |     3186 | 2024-04-03 | Alliance          | W   | 0.380      | -            | -                | -                | -         |     2.21 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           19 |     3215 | 2024-04-02 | PARIVISION        | W   | 0.374      | -            | -                | -                | -         |     5.61 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           18 |     3216 | 2024-04-02 | ex-Guild Eagles   | L   | 0.374      | -            | -                | -                | -         |   -10.09 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           17 |     3227 | 2024-04-02 | ALTERNATE aTTaX   | W   | 0.372      | -            | -                | -                | -         |     3.47 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           16 |     3450 | 2024-03-18 | The MongolZ       | L   | 0.274      | -            | -                | -                | -         |    -0.09 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           15 |     3467 | 2024-03-17 | Apeks             | L   | 0.268      | -            | -                | -                | -         |    -6.56 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     3477 | 2024-03-17 | GamerLegion       | L   | 0.267      | -            | -                | -                | -         |    -7.42 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     3786 | 2024-03-05 | FORZE             | L   | 0.188      | -            | -                | -                | -         |    -4.70 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     3791 | 2024-03-05 | Zero Tenacity     | W   | 0.188      | -            | -                | -                | -         |     2.61 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     3887 | 2024-03-01 | BIG               | L   | 0.159      | -            | -                | -                | -         |    -1.42 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     3905 | 2024-02-28 | Young Ninjas      | L   | 0.148      | -            | -                | -                | -         |    -4.20 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     4168 | 2024-02-17 | 9 Pandas          | W   | 0.073      | -            | -                | -                | 1 (0.073) |     0.70 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     4197 | 2024-02-16 | Falcons           | W   | 0.066      | -            | -                | -                | 1 (0.066) |     1.72 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     4221 | 2024-02-15 | fnatic            | L   | 0.060      | -            | -                | -                | -         |    -0.17 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     4255 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.054      | -            | -                | -                | 1 (0.054) |     0.03 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     4259 | 2024-02-14 | Enterprise        | L   | 0.054      | -            | -                | -                | -         |    -1.32 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     4319 | 2024-02-10 | Sashi             | L   | 0.027      | -            | -                | -                | -         |    -0.41 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     4327 | 2024-02-09 | Nemiga            | L   | 0.022      | -            | -                | -                | -         |    -0.34 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     4344 | 2024-02-08 | RUBY              | W   | 0.015      | -            | -                | -                | -         |     0.11 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     4349 | 2024-02-08 | Insilio           | W   | 0.014      | -            | -                | -                | -         |     0.08 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($42,150.49)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-02 |      0.781 | $2,000.00      | $1,561.34       |
| 2024-05-23 |      0.714 | $12,500.00     | $8,919.85       |
| 2024-05-04 |      0.588 | $22,000.00     | $12,927.55      |
| 2024-05-02 |      0.574 | $1,500.00      | $861.42         |
| 2024-03-20 |      0.288 | $10,000.00     | $2,880.32       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
