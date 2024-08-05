### Roster Details<br />
Team Name: AMKAL<br />
Roster: Forester, Krad, Sdaim, topo, TRAVIS<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1144.4<br />
<br />
Final Rank Value (1144.4) = Starting Rank Value (1145.5) + Head To Head Adjustments (-1.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.530[<sup>1</sup>](#table2)
- Bounty Collected: 0.442[<sup>2</sup>](#table1)
- Opponent Network: 0.235[<sup>2</sup>](#table1)
- LAN Wins: 0.250[<sup>2</sup>](#table1)

The average of these factors is 0.364<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1145.5
- 400 + ( ( 0.364 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1145.5


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
|           57 |       34 | 2024-08-04 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -24.03 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           56 |      123 | 2024-08-01 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -28.94 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           55 |      182 | 2024-07-31 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -10.24 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           54 |      320 | 2024-07-27 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -1.77 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           53 |      352 | 2024-07-26 | DMS               | W   | 1.000      | 0.650        | -                | 0.444 (0.289)    | 1 (1.000) |     5.04 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           52 |      387 | 2024-07-25 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -2.74 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           51 |      412 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.267 (0.174)    | 1 (1.000) |     4.27 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           50 |      422 | 2024-07-24 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -9.37 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           49 |     1226 | 2024-06-09 | Monte             | W   | 0.821      | 0.143        | 0.080 (0.009)    | -                | 0 (0.000) |     7.19 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           48 |     1255 | 2024-06-09 | B8                | W   | 0.820      | 0.143        | 0.165 (0.019)    | 0.947 (0.111)    | 0 (0.000) |    10.71 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     1313 | 2024-06-08 | Monte             | W   | 0.814      | -            | -                | -                | 0 (0.000) |     6.98 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     1317 | 2024-06-08 | 1WIN              | W   | 0.813      | -            | -                | -                | 0 (0.000) |     6.39 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     1622 | 2024-06-01 | MOUZ NXT          | L   | 0.766      | -            | -                | -                | -         |   -15.24 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     1639 | 2024-05-31 | Permitta          | W   | 0.762      | 0.435        | -                | 0.873 (0.289)    | 0 (0.000) |     4.14 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     1888 | 2024-05-21 | GamerLegion       | L   | 0.695      | -            | -                | -                | -         |   -11.71 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     1955 | 2024-05-19 | paiN              | W   | 0.681      | 0.769        | 0.325 (0.170)    | 0.867 (0.453)    | -         |    15.81 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     1959 | 2024-05-19 | Liquid            | L   | 0.680      | -            | -                | -                | -         |    -2.08 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     1980 | 2024-05-18 | paiN              | W   | 0.675      | 0.769        | 0.325 (0.169)    | 0.867 (0.449)    | -         |    16.28 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2377 | 2024-05-04 | BetBoom           | W   | 0.581      | 0.435        | 0.249 (0.063)    | 0.536 (0.135)    | -         |    14.57 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     2387 | 2024-05-04 | Metizport         | W   | 0.579      | -            | -                | -                | -         |     3.61 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     2397 | 2024-05-03 | Gaimin Gladiators | W   | 0.574      | -            | -                | -                | -         |     5.34 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     2412 | 2024-05-02 | BLEED             | W   | 0.568      | 0.435        | 0.090 (0.022)    | 0.392 (0.097)    | -         |     7.10 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     2445 | 2024-05-01 | fnatic            | L   | 0.560      | -            | -                | -                | -         |    -1.93 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     2463 | 2024-04-30 | Gaimin Gladiators | W   | 0.554      | -            | -                | -                | -         |     5.20 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     2488 | 2024-04-29 | Permitta          | W   | 0.547      | 0.384        | -                | 0.873 (0.184)    | -         |     4.53 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     2613 | 2024-04-24 | Nexus             | W   | 0.512      | -            | -                | -                | -         |     2.61 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     2660 | 2024-04-21 | Gaimin Gladiators | L   | 0.494      | -            | -                | -                | -         |   -10.17 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     2735 | 2024-04-19 | ENCE              | W   | 0.480      | 0.384        | 0.168 (0.031)    | -                | -         |    12.71 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     2779 | 2024-04-18 | Apeks             | L   | 0.474      | -            | -                | -                | -         |   -11.48 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     2788 | 2024-04-18 | ex-Guild Eagles   | W   | 0.473      | -            | -                | -                | -         |     2.19 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           27 |     2863 | 2024-04-16 | B8                | W   | 0.459      | 0.384        | 0.165 (0.029)    | 0.947 (0.167)    | -         |     5.37 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           26 |     2915 | 2024-04-12 | Aurora            | L   | 0.435      | -            | -                | -                | -         |    -0.77 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           25 |     2952 | 2024-04-11 | BetBoom           | W   | 0.426      | 0.143        | 0.249 (0.015)    | -                | -         |    11.18 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           24 |     2984 | 2024-04-10 | Apeks             | W   | 0.421      | -            | -                | -                | -         |     3.31 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           23 |     2998 | 2024-04-10 | Enterprise        | L   | 0.419      | -            | -                | -                | -         |   -10.16 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           22 |     3207 | 2024-04-03 | Insilio           | W   | 0.375      | -            | -                | -                | -         |     2.70 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           21 |     3218 | 2024-04-03 | ex-Guild Eagles   | W   | 0.374      | -            | -                | -                | -         |     1.69 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           20 |     3227 | 2024-04-03 | Alliance          | W   | 0.373      | -            | -                | -                | -         |     2.18 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           19 |     3256 | 2024-04-02 | PARIVISION        | W   | 0.367      | -            | -                | -                | -         |     5.57 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           18 |     3257 | 2024-04-02 | ex-Guild Eagles   | L   | 0.367      | -            | -                | -                | -         |    -9.93 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           17 |     3268 | 2024-04-02 | ALTERNATE aTTaX   | W   | 0.366      | -            | -                | -                | -         |     3.41 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           16 |     3491 | 2024-03-18 | The MongolZ       | L   | 0.267      | -            | -                | -                | -         |    -0.09 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           15 |     3508 | 2024-03-17 | Apeks             | L   | 0.262      | -            | -                | -                | -         |    -6.42 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     3518 | 2024-03-17 | GamerLegion       | L   | 0.261      | -            | -                | -                | -         |    -7.24 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     3827 | 2024-03-05 | FORZE             | L   | 0.182      | -            | -                | -                | -         |    -4.53 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     3832 | 2024-03-05 | Zero Tenacity     | W   | 0.181      | -            | -                | -                | -         |     2.54 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     3928 | 2024-03-01 | BIG               | L   | 0.152      | -            | -                | -                | -         |    -1.36 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     3946 | 2024-02-28 | Young Ninjas      | L   | 0.141      | -            | -                | -                | -         |    -4.00 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     4209 | 2024-02-17 | 9 Pandas          | W   | 0.066      | -            | -                | -                | 1 (0.066) |     0.64 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     4238 | 2024-02-16 | Falcons           | W   | 0.059      | -            | -                | -                | 1 (0.059) |     1.54 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     4262 | 2024-02-15 | fnatic            | L   | 0.053      | -            | -                | -                | -         |    -0.15 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     4296 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.048      | -            | -                | -                | 1 (0.048) |     0.02 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     4300 | 2024-02-14 | Enterprise        | L   | 0.047      | -            | -                | -                | -         |    -1.15 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     4360 | 2024-02-10 | Sashi             | L   | 0.020      | -            | -                | -                | -         |    -0.31 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     4368 | 2024-02-09 | Nemiga            | L   | 0.015      | -            | -                | -                | -         |    -0.22 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     4385 | 2024-02-08 | RUBY              | W   | 0.008      | -            | -                | -                | -         |     0.06 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     4390 | 2024-02-08 | Insilio           | W   | 0.007      | -            | -                | -                | -         |     0.04 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($41,824.93)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-02 |      0.774 | $2,000.00      | $1,547.78       |
| 2024-05-23 |      0.707 | $12,500.00     | $8,835.07       |
| 2024-05-04 |      0.581 | $22,000.00     | $12,778.33      |
| 2024-05-02 |      0.568 | $1,500.00      | $851.25         |
| 2024-03-20 |      0.281 | $10,000.00     | $2,812.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
