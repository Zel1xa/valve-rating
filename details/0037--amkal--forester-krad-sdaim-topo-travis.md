### Roster Details<br />
Team Name: AMKAL<br />
Roster: Forester, Krad, Sdaim, topo, TRAVIS<br />
Global Rank: [37](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1145.0<br />
<br />
Final Rank Value (1145.0) = Starting Rank Value (1145.8) + Head To Head Adjustments (-0.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.530[<sup>1</sup>](#table2)
- Bounty Collected: 0.441[<sup>2</sup>](#table1)
- Opponent Network: 0.234[<sup>2</sup>](#table1)
- LAN Wins: 0.249[<sup>2</sup>](#table1)

The average of these factors is 0.363<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1145.8
- 400 + ( ( 0.363 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1145.8


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
|           57 |       49 | 2024-08-04 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -23.64 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           56 |      137 | 2024-08-01 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -28.93 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           55 |      196 | 2024-07-31 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -10.17 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           54 |      335 | 2024-07-27 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -1.76 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           53 |      367 | 2024-07-26 | DMS               | W   | 1.000      | 0.650        | -                | 0.437 (0.284)    | 1 (1.000) |     5.06 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           52 |      402 | 2024-07-25 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -2.75 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           51 |      427 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.265 (0.172)    | 1 (1.000) |     4.29 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           50 |      437 | 2024-07-24 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -9.23 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           49 |     1241 | 2024-06-09 | Monte             | W   | 0.816      | 0.143        | 0.080 (0.009)    | -                | 0 (0.000) |     7.16 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           48 |     1270 | 2024-06-09 | B8                | W   | 0.814      | 0.143        | 0.164 (0.019)    | 0.933 (0.108)    | 0 (0.000) |    10.64 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     1328 | 2024-06-08 | Monte             | W   | 0.808      | -            | -                | -                | 0 (0.000) |     6.94 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     1332 | 2024-06-08 | 1WIN              | W   | 0.808      | -            | -                | -                | 0 (0.000) |     6.41 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     1637 | 2024-06-01 | MOUZ NXT          | L   | 0.761      | -            | -                | -                | -         |   -15.11 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     1654 | 2024-05-31 | Permitta          | W   | 0.756      | 0.435        | -                | 0.940 (0.309)    | 0 (0.000) |     4.24 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     1903 | 2024-05-21 | GamerLegion       | L   | 0.689      | -            | -                | -                | -         |   -11.67 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     1970 | 2024-05-19 | paiN              | W   | 0.675      | 0.769        | 0.324 (0.168)    | 0.857 (0.445)    | -         |    15.61 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     1974 | 2024-05-19 | Liquid            | L   | 0.674      | -            | -                | -                | -         |    -2.07 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     1995 | 2024-05-18 | paiN              | W   | 0.669      | 0.769        | 0.324 (0.167)    | 0.857 (0.440)    | -         |    16.07 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2392 | 2024-05-04 | BetBoom           | W   | 0.575      | 0.435        | 0.248 (0.062)    | 0.526 (0.131)    | -         |    14.38 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     2402 | 2024-05-04 | Metizport         | W   | 0.573      | -            | -                | -                | -         |     3.54 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     2412 | 2024-05-03 | Gaimin Gladiators | W   | 0.568      | -            | -                | -                | -         |     5.24 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     2427 | 2024-05-02 | BLEED             | W   | 0.562      | 0.435        | 0.090 (0.022)    | 0.384 (0.094)    | -         |     6.99 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     2460 | 2024-05-01 | fnatic            | L   | 0.555      | -            | -                | -                | -         |    -1.92 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     2478 | 2024-04-30 | Gaimin Gladiators | W   | 0.549      | -            | -                | -                | -         |     5.09 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     2503 | 2024-04-29 | Permitta          | W   | 0.541      | 0.384        | -                | 0.940 (0.195)    | -         |     4.66 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     2628 | 2024-04-24 | Nexus             | W   | 0.507      | -            | -                | -                | -         |     2.59 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     2675 | 2024-04-21 | Gaimin Gladiators | L   | 0.488      | -            | -                | -                | -         |   -10.11 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     2750 | 2024-04-19 | ENCE              | W   | 0.474      | 0.384        | 0.173 (0.032)    | -                | -         |    12.59 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     2794 | 2024-04-18 | Apeks             | L   | 0.468      | -            | -                | -                | -         |   -11.39 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     2803 | 2024-04-18 | ex-Guild Eagles   | W   | 0.467      | -            | -                | -                | -         |     2.15 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           27 |     2878 | 2024-04-16 | B8                | W   | 0.453      | 0.384        | 0.164 (0.029)    | 0.933 (0.163)    | -         |     5.29 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           26 |     2930 | 2024-04-12 | Aurora            | L   | 0.429      | -            | -                | -                | -         |    -0.75 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           25 |     2967 | 2024-04-11 | BetBoom           | W   | 0.421      | 0.143        | 0.248 (0.015)    | -                | -         |    10.99 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           24 |     2999 | 2024-04-10 | Apeks             | W   | 0.416      | -            | -                | -                | -         |     3.22 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           23 |     3013 | 2024-04-10 | Enterprise        | L   | 0.413      | -            | -                | -                | -         |   -10.00 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           22 |     3222 | 2024-04-03 | Insilio           | W   | 0.369      | -            | -                | -                | -         |     2.67 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           21 |     3233 | 2024-04-03 | ex-Guild Eagles   | W   | 0.368      | -            | -                | -                | -         |     1.65 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           20 |     3242 | 2024-04-03 | Alliance          | W   | 0.367      | -            | -                | -                | -         |     2.13 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           19 |     3271 | 2024-04-02 | PARIVISION        | W   | 0.361      | -            | -                | -                | -         |     5.53 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           18 |     3272 | 2024-04-02 | ex-Guild Eagles   | L   | 0.361      | -            | -                | -                | -         |    -9.78 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           17 |     3283 | 2024-04-02 | ALTERNATE aTTaX   | W   | 0.360      | -            | -                | -                | -         |     3.34 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           16 |     3506 | 2024-03-18 | The MongolZ       | L   | 0.261      | -            | -                | -                | -         |    -0.09 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           15 |     3523 | 2024-03-17 | Apeks             | L   | 0.256      | -            | -                | -                | -         |    -6.30 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     3533 | 2024-03-17 | GamerLegion       | L   | 0.255      | -            | -                | -                | -         |    -7.09 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     3842 | 2024-03-05 | FORZE             | L   | 0.176      | -            | -                | -                | -         |    -4.39 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     3847 | 2024-03-05 | Zero Tenacity     | W   | 0.175      | -            | -                | -                | -         |     2.47 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     3943 | 2024-03-01 | BIG               | L   | 0.147      | -            | -                | -                | -         |    -1.31 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     3961 | 2024-02-28 | Young Ninjas      | L   | 0.135      | -            | -                | -                | -         |    -3.83 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     4224 | 2024-02-17 | 9 Pandas          | W   | 0.060      | -            | -                | -                | 1 (0.060) |     0.57 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     4253 | 2024-02-16 | Falcons           | W   | 0.054      | -            | -                | -                | 1 (0.054) |     1.39 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     4277 | 2024-02-15 | fnatic            | L   | 0.047      | -            | -                | -                | -         |    -0.13 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     4311 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.042      | -            | -                | -                | 1 (0.042) |     0.02 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     4315 | 2024-02-14 | Enterprise        | L   | 0.041      | -            | -                | -                | -         |    -1.00 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     4375 | 2024-02-10 | Sashi             | L   | 0.015      | -            | -                | -                | -         |    -0.22 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     4383 | 2024-02-09 | Nemiga            | L   | 0.009      | -            | -                | -                | -         |    -0.13 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     4400 | 2024-02-08 | RUBY              | W   | 0.002      | -            | -                | -                | -         |     0.02 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     4405 | 2024-02-08 | Insilio           | W   | 0.001      | -            | -                | -                | -         |     0.01 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($41,544.93)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-02 |      0.768 | $2,000.00      | $1,536.11       |
| 2024-05-23 |      0.701 | $12,500.00     | $8,762.15       |
| 2024-05-04 |      0.575 | $22,000.00     | $12,650.00      |
| 2024-05-02 |      0.562 | $1,500.00      | $842.50         |
| 2024-03-20 |      0.275 | $10,000.00     | $2,754.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
