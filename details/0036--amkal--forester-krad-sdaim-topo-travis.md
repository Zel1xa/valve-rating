### Roster Details<br />
Team Name: AMKAL<br />
Roster: Forester, Krad, Sdaim, topo, TRAVIS<br />
Global Rank: [36](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [27]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1148.0<br />
<br />
Final Rank Value (1148.0) = Starting Rank Value (1146.7) + Head To Head Adjustments (1.3)<br />

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
|           56 |       68 | 2024-08-04 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -23.04 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           55 |      156 | 2024-08-01 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -28.95 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           54 |      215 | 2024-07-31 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -10.12 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           53 |      354 | 2024-07-27 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -1.79 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           52 |      386 | 2024-07-26 | DMS               | W   | 1.000      | 0.650        | -                | 0.428 (0.278)    | 1 (1.000) |     5.08 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           51 |      421 | 2024-07-25 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -2.77 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           50 |      446 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.259 (0.169)    | 1 (1.000) |     4.27 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           49 |      456 | 2024-07-24 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -9.22 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           48 |     1260 | 2024-06-09 | Monte             | W   | 0.814      | -            | -                | -                | 0 (0.000) |     7.14 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     1289 | 2024-06-09 | B8                | W   | 0.812      | 0.143        | 0.170 (0.020)    | 0.912 (0.106)    | 0 (0.000) |    10.67 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     1347 | 2024-06-08 | Monte             | W   | 0.806      | -            | -                | -                | 0 (0.000) |     6.90 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     1351 | 2024-06-08 | 1WIN              | W   | 0.806      | -            | -                | -                | 0 (0.000) |     6.38 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     1656 | 2024-06-01 | MOUZ NXT          | L   | 0.759      | -            | -                | -                | -         |   -15.04 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     1673 | 2024-05-31 | Permitta          | W   | 0.754      | 0.435        | 0.039 (0.013)    | 0.919 (0.301)    | 0 (0.000) |     4.43 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     1922 | 2024-05-21 | GamerLegion       | L   | 0.687      | -            | -                | -                | -         |   -11.72 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     1989 | 2024-05-19 | paiN              | W   | 0.673      | 0.769        | 0.324 (0.167)    | 0.839 (0.434)    | -         |    15.48 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     1993 | 2024-05-19 | Liquid            | L   | 0.672      | -            | -                | -                | -         |    -2.09 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2014 | 2024-05-18 | paiN              | W   | 0.667      | 0.769        | 0.324 (0.166)    | 0.839 (0.430)    | -         |    15.93 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     2411 | 2024-05-04 | BetBoom           | W   | 0.573      | 0.435        | 0.248 (0.062)    | 0.513 (0.128)    | -         |    14.28 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     2421 | 2024-05-04 | Metizport         | W   | 0.572      | 0.435        | -                | 0.510 (0.127)    | -         |     4.45 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     2431 | 2024-05-03 | Gaimin Gladiators | W   | 0.566      | -            | -                | -                | -         |     5.19 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     2446 | 2024-05-02 | BLEED             | W   | 0.560      | 0.435        | 0.089 (0.022)    | -                | -         |     6.98 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     2479 | 2024-05-01 | fnatic            | L   | 0.553      | -            | -                | -                | -         |    -1.92 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     2497 | 2024-04-30 | Gaimin Gladiators | W   | 0.547      | -            | -                | -                | -         |     5.04 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     2522 | 2024-04-29 | Permitta          | W   | 0.539      | 0.384        | -                | 0.919 (0.190)    | -         |     4.85 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     2647 | 2024-04-24 | Nexus             | W   | 0.505      | -            | -                | -                | -         |     2.61 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     2694 | 2024-04-21 | Gaimin Gladiators | L   | 0.486      | -            | -                | -                | -         |   -10.12 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     2769 | 2024-04-19 | ENCE              | W   | 0.473      | 0.384        | 0.173 (0.031)    | -                | -         |    12.55 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     2813 | 2024-04-18 | Apeks             | L   | 0.467      | -            | -                | -                | -         |   -11.36 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           27 |     2822 | 2024-04-18 | ex-Guild Eagles   | W   | 0.466      | -            | -                | -                | -         |     2.19 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           26 |     2897 | 2024-04-16 | B8                | W   | 0.452      | 0.384        | 0.170 (0.030)    | 0.912 (0.158)    | -         |     5.32 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           25 |     2949 | 2024-04-12 | Aurora            | L   | 0.427      | -            | -                | -                | -         |    -0.74 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           24 |     2986 | 2024-04-11 | BetBoom           | W   | 0.419      | 0.143        | 0.248 (0.015)    | -                | -         |    10.92 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           23 |     3018 | 2024-04-10 | Apeks             | W   | 0.414      | -            | -                | -                | -         |     3.19 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           22 |     3032 | 2024-04-10 | Enterprise        | L   | 0.412      | -            | -                | -                | -         |    -9.97 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           21 |     3241 | 2024-04-03 | Insilio           | W   | 0.367      | -            | -                | -                | -         |     2.66 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           20 |     3252 | 2024-04-03 | ex-Guild Eagles   | W   | 0.366      | -            | -                | -                | -         |     1.67 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           19 |     3261 | 2024-04-03 | Alliance          | W   | 0.365      | -            | -                | -                | -         |     2.12 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           18 |     3290 | 2024-04-02 | PARIVISION        | W   | 0.360      | -            | -                | -                | -         |     6.08 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           17 |     3291 | 2024-04-02 | ex-Guild Eagles   | L   | 0.359      | -            | -                | -                | -         |    -9.70 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           16 |     3302 | 2024-04-02 | ALTERNATE aTTaX   | W   | 0.358      | -            | -                | -                | -         |     3.38 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           15 |     3525 | 2024-03-18 | The MongolZ       | L   | 0.259      | -            | -                | -                | -         |    -0.09 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     3542 | 2024-03-17 | Apeks             | L   | 0.254      | -            | -                | -                | -         |    -6.26 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     3552 | 2024-03-17 | GamerLegion       | L   | 0.253      | -            | -                | -                | -         |    -7.05 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     3861 | 2024-03-05 | FORZE             | L   | 0.174      | -            | -                | -                | -         |    -4.35 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     3866 | 2024-03-05 | Zero Tenacity     | W   | 0.173      | -            | -                | -                | -         |     2.43 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     3962 | 2024-03-01 | BIG               | L   | 0.145      | -            | -                | -                | -         |    -1.30 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     3980 | 2024-02-28 | Young Ninjas      | L   | 0.133      | -            | -                | -                | -         |    -3.78 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     4243 | 2024-02-17 | 9 Pandas          | W   | 0.058      | -            | -                | -                | 1 (0.058) |     0.58 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     4272 | 2024-02-16 | Falcons           | W   | 0.052      | -            | -                | -                | 1 (0.052) |     1.34 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     4296 | 2024-02-15 | fnatic            | L   | 0.045      | -            | -                | -                | -         |    -0.13 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     4330 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.040      | -            | -                | -                | 1 (0.040) |     0.02 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     4334 | 2024-02-14 | Enterprise        | L   | 0.039      | -            | -                | -                | -         |    -0.96 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     4394 | 2024-02-10 | Sashi             | L   | 0.013      | -            | -                | -                | -         |    -0.19 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     4402 | 2024-02-09 | Nemiga            | L   | 0.007      | -            | -                | -                | -         |    -0.11 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     4419 | 2024-02-08 | RUBY              | W   | 0.001      | -            | -                | -                | -         |     0.00 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($41,458.26)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-02 |      0.766 | $2,000.00      | $1,532.50       |
| 2024-05-23 |      0.699 | $12,500.00     | $8,739.58       |
| 2024-05-04 |      0.573 | $22,000.00     | $12,610.28      |
| 2024-05-02 |      0.560 | $1,500.00      | $839.79         |
| 2024-03-20 |      0.274 | $10,000.00     | $2,736.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
