### Roster Details<br />
Team Name: AMKAL<br />
Roster: Forester, Krad, Sdaim, topo, TRAVIS<br />
Global Rank: [36](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [27]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1146.3<br />
<br />
Final Rank Value (1146.3) = Starting Rank Value (1145.7) + Head To Head Adjustments (0.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.530[<sup>1</sup>](#table2)
- Bounty Collected: 0.441[<sup>2</sup>](#table1)
- Opponent Network: 0.230[<sup>2</sup>](#table1)
- LAN Wins: 0.249[<sup>2</sup>](#table1)

The average of these factors is 0.363<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1145.7
- 400 + ( ( 0.363 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1145.7


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
|           57 |       56 | 2024-08-04 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -23.02 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           56 |      144 | 2024-08-01 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -28.93 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           55 |      203 | 2024-07-31 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -10.16 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           54 |      342 | 2024-07-27 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -1.77 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           53 |      374 | 2024-07-26 | DMS               | W   | 1.000      | 0.650        | -                | 0.428 (0.278)    | 1 (1.000) |     5.06 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           52 |      409 | 2024-07-25 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -2.75 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           51 |      434 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.259 (0.168)    | 1 (1.000) |     4.29 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           50 |      444 | 2024-07-24 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -9.23 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           49 |     1248 | 2024-06-09 | Monte             | W   | 0.815      | 0.143        | 0.080 (0.009)    | -                | 0 (0.000) |     7.11 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           48 |     1277 | 2024-06-09 | B8                | W   | 0.813      | 0.143        | 0.170 (0.020)    | 0.912 (0.106)    | 0 (0.000) |    10.66 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     1335 | 2024-06-08 | Monte             | W   | 0.807      | -            | -                | -                | 0 (0.000) |     6.90 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     1339 | 2024-06-08 | 1WIN              | W   | 0.807      | -            | -                | -                | 0 (0.000) |     6.37 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     1644 | 2024-06-01 | MOUZ NXT          | L   | 0.760      | -            | -                | -                | -         |   -15.11 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     1661 | 2024-05-31 | Permitta          | W   | 0.755      | 0.435        | -                | 0.919 (0.302)    | 0 (0.000) |     4.30 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     1910 | 2024-05-21 | GamerLegion       | L   | 0.688      | -            | -                | -                | -         |   -11.71 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     1977 | 2024-05-19 | paiN              | W   | 0.674      | 0.769        | 0.324 (0.168)    | 0.838 (0.434)    | -         |    15.55 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     1981 | 2024-05-19 | Liquid            | L   | 0.674      | -            | -                | -                | -         |    -2.07 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     2002 | 2024-05-18 | paiN              | W   | 0.668      | 0.769        | 0.324 (0.166)    | 0.838 (0.431)    | -         |    16.01 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2399 | 2024-05-04 | BetBoom           | W   | 0.574      | 0.435        | 0.248 (0.062)    | 0.514 (0.128)    | -         |    14.34 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     2409 | 2024-05-04 | Metizport         | W   | 0.573      | 0.435        | -                | 0.434 (0.108)    | -         |     4.40 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     2419 | 2024-05-03 | Gaimin Gladiators | W   | 0.567      | -            | -                | -                | -         |     5.22 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     2434 | 2024-05-02 | BLEED             | W   | 0.562      | 0.435        | 0.089 (0.022)    | -                | -         |     6.97 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     2467 | 2024-05-01 | fnatic            | L   | 0.554      | -            | -                | -                | -         |    -1.93 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     2485 | 2024-04-30 | Gaimin Gladiators | W   | 0.548      | -            | -                | -                | -         |     5.07 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     2510 | 2024-04-29 | Permitta          | W   | 0.540      | 0.384        | -                | 0.919 (0.191)    | -         |     4.66 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     2635 | 2024-04-24 | Nexus             | W   | 0.506      | -            | -                | -                | -         |     2.60 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     2682 | 2024-04-21 | Gaimin Gladiators | L   | 0.487      | -            | -                | -                | -         |   -10.11 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     2757 | 2024-04-19 | ENCE              | W   | 0.474      | 0.384        | 0.173 (0.032)    | -                | -         |    12.58 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     2801 | 2024-04-18 | Apeks             | L   | 0.468      | -            | -                | -                | -         |   -11.36 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     2810 | 2024-04-18 | ex-Guild Eagles   | W   | 0.467      | -            | -                | -                | -         |     2.18 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           27 |     2885 | 2024-04-16 | B8                | W   | 0.453      | 0.384        | 0.170 (0.030)    | 0.912 (0.159)    | -         |     5.34 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           26 |     2937 | 2024-04-12 | Aurora            | L   | 0.428      | -            | -                | -                | -         |    -0.73 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           25 |     2974 | 2024-04-11 | BetBoom           | W   | 0.420      | 0.143        | 0.248 (0.015)    | -                | -         |    10.97 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           24 |     3006 | 2024-04-10 | Apeks             | W   | 0.415      | -            | -                | -                | -         |     3.23 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           23 |     3020 | 2024-04-10 | Enterprise        | L   | 0.413      | -            | -                | -                | -         |    -9.99 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           22 |     3229 | 2024-04-03 | Insilio           | W   | 0.368      | -            | -                | -                | -         |     2.67 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           21 |     3240 | 2024-04-03 | ex-Guild Eagles   | W   | 0.367      | -            | -                | -                | -         |     1.67 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           20 |     3249 | 2024-04-03 | Alliance          | W   | 0.366      | -            | -                | -                | -         |     2.13 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           19 |     3278 | 2024-04-02 | PARIVISION        | W   | 0.361      | -            | -                | -                | -         |     5.55 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           18 |     3279 | 2024-04-02 | ex-Guild Eagles   | L   | 0.360      | -            | -                | -                | -         |    -9.75 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           17 |     3290 | 2024-04-02 | ALTERNATE aTTaX   | W   | 0.359      | -            | -                | -                | -         |     3.36 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           16 |     3513 | 2024-03-18 | The MongolZ       | L   | 0.260      | -            | -                | -                | -         |    -0.09 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           15 |     3530 | 2024-03-17 | Apeks             | L   | 0.255      | -            | -                | -                | -         |    -6.28 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     3540 | 2024-03-17 | GamerLegion       | L   | 0.254      | -            | -                | -                | -         |    -7.07 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     3849 | 2024-03-05 | FORZE             | L   | 0.175      | -            | -                | -                | -         |    -4.38 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     3854 | 2024-03-05 | Zero Tenacity     | W   | 0.175      | -            | -                | -                | -         |     2.46 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     3950 | 2024-03-01 | BIG               | L   | 0.146      | -            | -                | -                | -         |    -1.31 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     3968 | 2024-02-28 | Young Ninjas      | L   | 0.134      | -            | -                | -                | -         |    -3.81 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     4231 | 2024-02-17 | 9 Pandas          | W   | 0.060      | -            | -                | -                | 1 (0.060) |     0.57 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     4260 | 2024-02-16 | Falcons           | W   | 0.053      | -            | -                | -                | 1 (0.053) |     1.37 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     4284 | 2024-02-15 | fnatic            | L   | 0.047      | -            | -                | -                | -         |    -0.13 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     4318 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.041      | -            | -                | -                | 1 (0.041) |     0.02 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     4322 | 2024-02-14 | Enterprise        | L   | 0.040      | -            | -                | -                | -         |    -0.99 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     4382 | 2024-02-10 | Sashi             | L   | 0.014      | -            | -                | -                | -         |    -0.21 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     4390 | 2024-02-09 | Nemiga            | L   | 0.008      | -            | -                | -                | -         |    -0.12 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     4407 | 2024-02-08 | RUBY              | W   | 0.002      | -            | -                | -                | -         |     0.01 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     4412 | 2024-02-08 | Insilio           | W   | 0.001      | -            | -                | -                | -         |     0.00 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($41,513.82)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-02 |      0.767 | $2,000.00      | $1,534.81       |
| 2024-05-23 |      0.700 | $12,500.00     | $8,754.05       |
| 2024-05-04 |      0.574 | $22,000.00     | $12,635.74      |
| 2024-05-02 |      0.561 | $1,500.00      | $841.53         |
| 2024-03-20 |      0.275 | $10,000.00     | $2,747.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
