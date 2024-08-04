### Roster Details<br />
Team Name: AMKAL<br />
Roster: Forester, Krad, Sdaim, topo, TRAVIS<br />
Global Rank: [34](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [25]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1168.1<br />
<br />
Final Rank Value (1168.1) = Starting Rank Value (1147.1) + Head To Head Adjustments (21.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.530[<sup>1</sup>](#table2)
- Bounty Collected: 0.443[<sup>2</sup>](#table1)
- Opponent Network: 0.237[<sup>2</sup>](#table1)
- LAN Wins: 0.251[<sup>2</sup>](#table1)

The average of these factors is 0.365<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1147.1
- 400 + ( ( 0.365 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1147.1


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
|           56 |       76 | 2024-08-01 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -28.94 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           55 |      133 | 2024-07-31 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -10.45 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           54 |      271 | 2024-07-27 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -1.83 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           53 |      303 | 2024-07-26 | DMS               | W   | 1.000      | 0.650        | -                | 0.446 (0.290)    | 1 (1.000) |     4.95 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           52 |      338 | 2024-07-25 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -2.79 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           51 |      363 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.267 (0.173)    | 1 (1.000) |     4.23 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           50 |      373 | 2024-07-24 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -9.62 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           49 |     1177 | 2024-06-09 | Monte             | W   | 0.829      | -            | -                | -                | 0 (0.000) |     7.18 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           48 |     1206 | 2024-06-09 | B8                | W   | 0.827      | 0.143        | 0.165 (0.020)    | 0.912 (0.108)    | 0 (0.000) |    10.74 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     1264 | 2024-06-08 | Monte             | W   | 0.821      | -            | -                | -                | 0 (0.000) |     6.99 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     1268 | 2024-06-08 | 1WIN              | W   | 0.821      | -            | -                | -                | 0 (0.000) |     5.79 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     1573 | 2024-06-01 | MOUZ NXT          | L   | 0.774      | -            | -                | -                | -         |   -15.57 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     1590 | 2024-05-31 | Permitta          | W   | 0.769      | 0.435        | -                | 0.876 (0.293)    | 0 (0.000) |     4.12 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     1839 | 2024-05-21 | GamerLegion       | L   | 0.702      | -            | -                | -                | -         |   -11.87 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     1906 | 2024-05-19 | paiN              | W   | 0.688      | 0.769        | 0.327 (0.173)    | 0.866 (0.458)    | -         |    16.02 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     1910 | 2024-05-19 | Liquid            | L   | 0.688      | -            | -                | -                | -         |    -3.17 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     1931 | 2024-05-18 | paiN              | W   | 0.682      | 0.769        | 0.327 (0.172)    | 0.866 (0.454)    | -         |    16.47 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2328 | 2024-05-04 | BetBoom           | W   | 0.588      | 0.435        | 0.251 (0.064)    | 0.542 (0.139)    | -         |    14.73 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     2338 | 2024-05-04 | Metizport         | W   | 0.587      | 0.435        | -                | 0.417 (0.106)    | -         |     4.51 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     2348 | 2024-05-03 | Gaimin Gladiators | W   | 0.581      | 0.435        | 0.038 (0.010)    | -                | -         |     5.39 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     2363 | 2024-05-02 | BLEED             | W   | 0.576      | 0.435        | 0.091 (0.023)    | -                | -         |     7.19 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     2396 | 2024-05-01 | fnatic            | L   | 0.568      | -            | -                | -                | -         |    -1.98 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     2414 | 2024-04-30 | Gaimin Gladiators | W   | 0.562      | -            | -                | -                | -         |     5.27 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     2439 | 2024-04-29 | Permitta          | W   | 0.554      | 0.384        | -                | 0.876 (0.187)    | -         |     4.55 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     2564 | 2024-04-24 | Nexus             | W   | 0.520      | -            | -                | -                | -         |     2.63 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     2611 | 2024-04-21 | Gaimin Gladiators | L   | 0.501      | -            | -                | -                | -         |   -10.30 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     2686 | 2024-04-19 | ENCE              | W   | 0.488      | 0.384        | 0.169 (0.032)    | -                | -         |    12.79 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     2730 | 2024-04-18 | Apeks             | L   | 0.482      | -            | -                | -                | -         |   -11.62 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     2739 | 2024-04-18 | ex-Guild Eagles   | W   | 0.481      | -            | -                | -                | -         |     2.26 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           27 |     2814 | 2024-04-16 | B8                | W   | 0.467      | 0.384        | 0.165 (0.030)    | 0.912 (0.164)    | -         |     5.44 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           26 |     2866 | 2024-04-12 | Aurora            | L   | 0.442      | -            | -                | -                | -         |    -0.80 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           25 |     2903 | 2024-04-11 | BetBoom           | W   | 0.434      | 0.143        | 0.251 (0.016)    | -                | -         |    11.38 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           24 |     2935 | 2024-04-10 | Apeks             | W   | 0.429      | -            | -                | -                | -         |     3.42 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           23 |     2949 | 2024-04-10 | Enterprise        | L   | 0.427      | -            | -                | -                | -         |   -10.35 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           22 |     3158 | 2024-04-03 | Insilio           | W   | 0.382      | -            | -                | -                | -         |     2.73 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           21 |     3169 | 2024-04-03 | ex-Guild Eagles   | W   | 0.381      | -            | -                | -                | -         |     1.74 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           20 |     3178 | 2024-04-03 | Alliance          | W   | 0.380      | -            | -                | -                | -         |     2.21 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           19 |     3207 | 2024-04-02 | PARIVISION        | W   | 0.375      | -            | -                | -                | -         |     5.62 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           18 |     3208 | 2024-04-02 | ex-Guild Eagles   | L   | 0.374      | -            | -                | -                | -         |   -10.11 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           17 |     3219 | 2024-04-02 | ALTERNATE aTTaX   | W   | 0.373      | -            | -                | -                | -         |     3.48 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           16 |     3442 | 2024-03-18 | The MongolZ       | L   | 0.274      | -            | -                | -                | -         |    -0.09 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           15 |     3459 | 2024-03-17 | Apeks             | L   | 0.269      | -            | -                | -                | -         |    -6.58 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     3469 | 2024-03-17 | GamerLegion       | L   | 0.268      | -            | -                | -                | -         |    -7.42 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     3778 | 2024-03-05 | FORZE             | L   | 0.189      | -            | -                | -                | -         |    -4.71 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     3783 | 2024-03-05 | Zero Tenacity     | W   | 0.189      | -            | -                | -                | -         |     2.62 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     3879 | 2024-03-01 | BIG               | L   | 0.160      | -            | -                | -                | -         |    -1.43 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     3897 | 2024-02-28 | Young Ninjas      | L   | 0.148      | -            | -                | -                | -         |    -4.22 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     4160 | 2024-02-17 | 9 Pandas          | W   | 0.074      | -            | -                | -                | 1 (0.074) |     0.71 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     4189 | 2024-02-16 | Falcons           | W   | 0.067      | -            | -                | -                | 1 (0.067) |     1.74 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     4213 | 2024-02-15 | fnatic            | L   | 0.061      | -            | -                | -                | -         |    -0.17 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     4247 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.055      | -            | -                | -                | 1 (0.055) |     0.03 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     4251 | 2024-02-14 | Enterprise        | L   | 0.054      | -            | -                | -                | -         |    -1.34 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     4311 | 2024-02-10 | Sashi             | L   | 0.028      | -            | -                | -                | -         |    -0.43 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     4319 | 2024-02-09 | Nemiga            | L   | 0.022      | -            | -                | -                | -         |    -0.35 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     4336 | 2024-02-08 | RUBY              | W   | 0.016      | -            | -                | -                | -         |     0.11 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     4341 | 2024-02-08 | Insilio           | W   | 0.015      | -            | -                | -                | -         |     0.09 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($42,184.93)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-02 |      0.781 | $2,000.00      | $1,562.78       |
| 2024-05-23 |      0.714 | $12,500.00     | $8,928.82       |
| 2024-05-04 |      0.588 | $22,000.00     | $12,943.33      |
| 2024-05-02 |      0.575 | $1,500.00      | $862.50         |
| 2024-03-20 |      0.289 | $10,000.00     | $2,887.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
