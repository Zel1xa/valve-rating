### Roster Details<br />
Team Name: AMKAL<br />
Roster: Forester, Krad, Sdaim, topo, TRAVIS<br />
Global Rank: [36](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [27]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1147.2<br />
<br />
Final Rank Value (1147.2) = Starting Rank Value (1146.7) + Head To Head Adjustments (0.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.530[<sup>1</sup>](#table2)
- Bounty Collected: 0.441[<sup>2</sup>](#table1)
- Opponent Network: 0.232[<sup>2</sup>](#table1)
- LAN Wins: 0.248[<sup>2</sup>](#table1)

The average of these factors is 0.363<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1146.7
- 400 + ( ( 0.363 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1146.7


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
|           56 |       66 | 2024-08-04 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -23.03 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           55 |      154 | 2024-08-01 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -28.94 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           54 |      213 | 2024-07-31 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -10.15 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           53 |      352 | 2024-07-27 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -1.78 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           52 |      384 | 2024-07-26 | DMS               | W   | 1.000      | 0.650        | -                | 0.428 (0.278)    | 1 (1.000) |     5.05 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           51 |      419 | 2024-07-25 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -2.76 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           50 |      444 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.259 (0.169)    | 1 (1.000) |     4.28 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           49 |      454 | 2024-07-24 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -9.23 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           48 |     1258 | 2024-06-09 | Monte             | W   | 0.814      | -            | -                | -                | 0 (0.000) |     7.10 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     1287 | 2024-06-09 | B8                | W   | 0.812      | 0.143        | 0.170 (0.020)    | 0.912 (0.106)    | 0 (0.000) |    10.63 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     1345 | 2024-06-08 | Monte             | W   | 0.806      | -            | -                | -                | 0 (0.000) |     6.88 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     1349 | 2024-06-08 | 1WIN              | W   | 0.806      | -            | -                | -                | 0 (0.000) |     6.38 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     1654 | 2024-06-01 | MOUZ NXT          | L   | 0.759      | -            | -                | -                | -         |   -15.09 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     1671 | 2024-05-31 | Permitta          | W   | 0.754      | 0.435        | 0.039 (0.013)    | 0.919 (0.301)    | 0 (0.000) |     4.42 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     1920 | 2024-05-21 | GamerLegion       | L   | 0.687      | -            | -                | -                | -         |   -11.71 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     1987 | 2024-05-19 | paiN              | W   | 0.673      | 0.769        | 0.324 (0.167)    | 0.839 (0.434)    | -         |    15.50 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     1991 | 2024-05-19 | Liquid            | L   | 0.672      | -            | -                | -                | -         |    -2.08 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2012 | 2024-05-18 | paiN              | W   | 0.667      | 0.769        | 0.324 (0.166)    | 0.839 (0.430)    | -         |    15.95 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     2409 | 2024-05-04 | BetBoom           | W   | 0.573      | 0.435        | 0.248 (0.062)    | 0.513 (0.128)    | -         |    14.29 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     2419 | 2024-05-04 | Metizport         | W   | 0.572      | 0.435        | -                | 0.510 (0.127)    | -         |     4.42 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     2429 | 2024-05-03 | Gaimin Gladiators | W   | 0.566      | -            | -                | -                | -         |     5.20 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     2444 | 2024-05-02 | BLEED             | W   | 0.561      | 0.435        | 0.089 (0.022)    | -                | -         |     6.95 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     2477 | 2024-05-01 | fnatic            | L   | 0.553      | -            | -                | -                | -         |    -1.93 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     2495 | 2024-04-30 | Gaimin Gladiators | W   | 0.547      | -            | -                | -                | -         |     5.04 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     2520 | 2024-04-29 | Permitta          | W   | 0.539      | 0.384        | -                | 0.919 (0.191)    | -         |     4.85 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     2645 | 2024-04-24 | Nexus             | W   | 0.505      | -            | -                | -                | -         |     2.61 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     2692 | 2024-04-21 | Gaimin Gladiators | L   | 0.486      | -            | -                | -                | -         |   -10.11 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     2767 | 2024-04-19 | ENCE              | W   | 0.473      | 0.384        | 0.173 (0.031)    | -                | -         |    12.54 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     2811 | 2024-04-18 | Apeks             | L   | 0.467      | -            | -                | -                | -         |   -11.36 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           27 |     2820 | 2024-04-18 | ex-Guild Eagles   | W   | 0.466      | -            | -                | -                | -         |     2.17 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           26 |     2895 | 2024-04-16 | B8                | W   | 0.452      | 0.384        | 0.170 (0.030)    | 0.912 (0.158)    | -         |     5.32 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           25 |     2947 | 2024-04-12 | Aurora            | L   | 0.427      | -            | -                | -                | -         |    -0.73 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           24 |     2984 | 2024-04-11 | BetBoom           | W   | 0.419      | 0.143        | 0.248 (0.015)    | -                | -         |    10.93 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           23 |     3016 | 2024-04-10 | Apeks             | W   | 0.414      | -            | -                | -                | -         |     3.20 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           22 |     3030 | 2024-04-10 | Enterprise        | L   | 0.412      | -            | -                | -                | -         |    -9.96 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           21 |     3239 | 2024-04-03 | Insilio           | W   | 0.367      | -            | -                | -                | -         |     2.66 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           20 |     3250 | 2024-04-03 | ex-Guild Eagles   | W   | 0.366      | -            | -                | -                | -         |     1.66 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           19 |     3259 | 2024-04-03 | Alliance          | W   | 0.365      | -            | -                | -                | -         |     2.12 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           18 |     3288 | 2024-04-02 | PARIVISION        | W   | 0.360      | -            | -                | -                | -         |     5.53 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           17 |     3289 | 2024-04-02 | ex-Guild Eagles   | L   | 0.359      | -            | -                | -                | -         |    -9.72 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           16 |     3300 | 2024-04-02 | ALTERNATE aTTaX   | W   | 0.358      | -            | -                | -                | -         |     3.35 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           15 |     3523 | 2024-03-18 | The MongolZ       | L   | 0.259      | -            | -                | -                | -         |    -0.09 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     3540 | 2024-03-17 | Apeks             | L   | 0.254      | -            | -                | -                | -         |    -6.27 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     3550 | 2024-03-17 | GamerLegion       | L   | 0.253      | -            | -                | -                | -         |    -7.05 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     3859 | 2024-03-05 | FORZE             | L   | 0.174      | -            | -                | -                | -         |    -4.36 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     3864 | 2024-03-05 | Zero Tenacity     | W   | 0.174      | -            | -                | -                | -         |     2.44 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     3960 | 2024-03-01 | BIG               | L   | 0.145      | -            | -                | -                | -         |    -1.31 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     3978 | 2024-02-28 | Young Ninjas      | L   | 0.133      | -            | -                | -                | -         |    -3.78 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     4241 | 2024-02-17 | 9 Pandas          | W   | 0.059      | -            | -                | -                | 1 (0.059) |     0.57 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     4270 | 2024-02-16 | Falcons           | W   | 0.052      | -            | -                | -                | 1 (0.052) |     1.34 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     4294 | 2024-02-15 | fnatic            | L   | 0.046      | -            | -                | -                | -         |    -0.13 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     4328 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.040      | -            | -                | -                | 1 (0.040) |     0.02 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     4332 | 2024-02-14 | Enterprise        | L   | 0.039      | -            | -                | -                | -         |    -0.97 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     4392 | 2024-02-10 | Sashi             | L   | 0.013      | -            | -                | -                | -         |    -0.20 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     4400 | 2024-02-09 | Nemiga            | L   | 0.007      | -            | -                | -                | -         |    -0.11 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     4417 | 2024-02-08 | RUBY              | W   | 0.001      | -            | -                | -                | -         |     0.01 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($41,464.93)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-02 |      0.766 | $2,000.00      | $1,532.78       |
| 2024-05-23 |      0.699 | $12,500.00     | $8,741.32       |
| 2024-05-04 |      0.573 | $22,000.00     | $12,613.33      |
| 2024-05-02 |      0.560 | $1,500.00      | $840.00         |
| 2024-03-20 |      0.274 | $10,000.00     | $2,737.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
