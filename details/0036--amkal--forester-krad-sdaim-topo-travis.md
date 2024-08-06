### Roster Details<br />
Team Name: AMKAL<br />
Roster: Forester, Krad, Sdaim, topo, TRAVIS<br />
Global Rank: [36](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [27]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1145.7<br />
<br />
Final Rank Value (1145.7) = Starting Rank Value (1145.7) + Head To Head Adjustments (-0.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.530[<sup>1</sup>](#table2)
- Bounty Collected: 0.441[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
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
|           57 |       53 | 2024-08-04 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -23.63 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           56 |      141 | 2024-08-01 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -28.93 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           55 |      200 | 2024-07-31 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -10.19 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           54 |      339 | 2024-07-27 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -1.78 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           53 |      371 | 2024-07-26 | DMS               | W   | 1.000      | 0.650        | -                | 0.428 (0.278)    | 1 (1.000) |     5.06 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           52 |      406 | 2024-07-25 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -2.75 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           51 |      431 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.259 (0.168)    | 1 (1.000) |     4.29 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           50 |      441 | 2024-07-24 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -9.24 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           49 |     1245 | 2024-06-09 | Monte             | W   | 0.815      | 0.143        | 0.080 (0.009)    | -                | 0 (0.000) |     7.12 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           48 |     1274 | 2024-06-09 | B8                | W   | 0.814      | 0.143        | 0.170 (0.020)    | 0.912 (0.106)    | 0 (0.000) |    10.66 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     1332 | 2024-06-08 | Monte             | W   | 0.808      | -            | -                | -                | 0 (0.000) |     6.90 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     1336 | 2024-06-08 | 1WIN              | W   | 0.807      | -            | -                | -                | 0 (0.000) |     6.38 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     1641 | 2024-06-01 | MOUZ NXT          | L   | 0.760      | -            | -                | -                | -         |   -15.12 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     1658 | 2024-05-31 | Permitta          | W   | 0.755      | 0.435        | -                | 0.919 (0.302)    | 0 (0.000) |     4.23 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     1907 | 2024-05-21 | GamerLegion       | L   | 0.689      | -            | -                | -                | -         |   -11.72 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     1974 | 2024-05-19 | paiN              | W   | 0.675      | 0.769        | 0.324 (0.168)    | 0.838 (0.435)    | -         |    15.56 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     1978 | 2024-05-19 | Liquid            | L   | 0.674      | -            | -                | -                | -         |    -2.08 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     1999 | 2024-05-18 | paiN              | W   | 0.668      | 0.769        | 0.324 (0.166)    | 0.838 (0.431)    | -         |    16.02 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2396 | 2024-05-04 | BetBoom           | W   | 0.575      | 0.435        | 0.248 (0.062)    | 0.514 (0.128)    | -         |    14.35 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     2406 | 2024-05-04 | Metizport         | W   | 0.573      | 0.435        | -                | 0.434 (0.108)    | -         |     4.40 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     2416 | 2024-05-03 | Gaimin Gladiators | W   | 0.568      | -            | -                | -                | -         |     5.23 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     2431 | 2024-05-02 | BLEED             | W   | 0.562      | 0.435        | 0.090 (0.022)    | -                | -         |     6.98 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     2464 | 2024-05-01 | fnatic            | L   | 0.554      | -            | -                | -                | -         |    -1.93 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     2482 | 2024-04-30 | Gaimin Gladiators | W   | 0.548      | -            | -                | -                | -         |     5.08 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     2507 | 2024-04-29 | Permitta          | W   | 0.541      | 0.384        | -                | 0.919 (0.191)    | -         |     4.66 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     2632 | 2024-04-24 | Nexus             | W   | 0.506      | -            | -                | -                | -         |     2.60 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     2679 | 2024-04-21 | Gaimin Gladiators | L   | 0.487      | -            | -                | -                | -         |   -10.12 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     2754 | 2024-04-19 | ENCE              | W   | 0.474      | 0.384        | 0.173 (0.032)    | -                | -         |    12.59 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     2798 | 2024-04-18 | Apeks             | L   | 0.468      | -            | -                | -                | -         |   -11.37 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     2807 | 2024-04-18 | ex-Guild Eagles   | W   | 0.467      | -            | -                | -                | -         |     2.18 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           27 |     2882 | 2024-04-16 | B8                | W   | 0.453      | 0.384        | 0.170 (0.030)    | 0.912 (0.159)    | -         |     5.34 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           26 |     2934 | 2024-04-12 | Aurora            | L   | 0.429      | -            | -                | -                | -         |    -0.73 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           25 |     2971 | 2024-04-11 | BetBoom           | W   | 0.420      | 0.143        | 0.248 (0.015)    | -                | -         |    10.98 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           24 |     3003 | 2024-04-10 | Apeks             | W   | 0.415      | -            | -                | -                | -         |     3.23 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           23 |     3017 | 2024-04-10 | Enterprise        | L   | 0.413      | -            | -                | -                | -         |   -10.00 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           22 |     3226 | 2024-04-03 | Insilio           | W   | 0.369      | -            | -                | -                | -         |     2.67 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           21 |     3237 | 2024-04-03 | ex-Guild Eagles   | W   | 0.368      | -            | -                | -                | -         |     1.67 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           20 |     3246 | 2024-04-03 | Alliance          | W   | 0.367      | -            | -                | -                | -         |     2.13 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           19 |     3275 | 2024-04-02 | PARIVISION        | W   | 0.361      | -            | -                | -                | -         |     5.55 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           18 |     3276 | 2024-04-02 | ex-Guild Eagles   | L   | 0.361      | -            | -                | -                | -         |    -9.76 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           17 |     3287 | 2024-04-02 | ALTERNATE aTTaX   | W   | 0.360      | -            | -                | -                | -         |     3.37 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           16 |     3510 | 2024-03-18 | The MongolZ       | L   | 0.261      | -            | -                | -                | -         |    -0.09 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           15 |     3527 | 2024-03-17 | Apeks             | L   | 0.256      | -            | -                | -                | -         |    -6.29 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     3537 | 2024-03-17 | GamerLegion       | L   | 0.254      | -            | -                | -                | -         |    -7.08 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     3846 | 2024-03-05 | FORZE             | L   | 0.175      | -            | -                | -                | -         |    -4.38 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     3851 | 2024-03-05 | Zero Tenacity     | W   | 0.175      | -            | -                | -                | -         |     2.46 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     3947 | 2024-03-01 | BIG               | L   | 0.146      | -            | -                | -                | -         |    -1.31 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     3965 | 2024-02-28 | Young Ninjas      | L   | 0.135      | -            | -                | -                | -         |    -3.82 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     4228 | 2024-02-17 | 9 Pandas          | W   | 0.060      | -            | -                | -                | 1 (0.060) |     0.57 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     4257 | 2024-02-16 | Falcons           | W   | 0.053      | -            | -                | -                | 1 (0.053) |     1.38 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     4281 | 2024-02-15 | fnatic            | L   | 0.047      | -            | -                | -                | -         |    -0.13 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     4315 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.041      | -            | -                | -                | 1 (0.041) |     0.02 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     4319 | 2024-02-14 | Enterprise        | L   | 0.041      | -            | -                | -                | -         |    -1.00 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     4379 | 2024-02-10 | Sashi             | L   | 0.014      | -            | -                | -                | -         |    -0.22 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     4387 | 2024-02-09 | Nemiga            | L   | 0.009      | -            | -                | -                | -         |    -0.13 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     4404 | 2024-02-08 | RUBY              | W   | 0.002      | -            | -                | -                | -         |     0.01 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     4409 | 2024-02-08 | Insilio           | W   | 0.001      | -            | -                | -                | -         |     0.01 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($41,531.60)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-02 |      0.768 | $2,000.00      | $1,535.56       |
| 2024-05-23 |      0.701 | $12,500.00     | $8,758.68       |
| 2024-05-04 |      0.575 | $22,000.00     | $12,643.89      |
| 2024-05-02 |      0.561 | $1,500.00      | $842.08         |
| 2024-03-20 |      0.275 | $10,000.00     | $2,751.39       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
