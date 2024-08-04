### Roster Details<br />
Team Name: AMKAL<br />
Roster: Forester, Krad, Sdaim, topo, TRAVIS<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1145.1<br />
<br />
Final Rank Value (1145.1) = Starting Rank Value (1146.9) + Head To Head Adjustments (-1.9)<br />

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
- 400 + ( ( 0.365 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1146.9


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
|           57 |       17 | 2024-08-04 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -24.08 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           56 |      106 | 2024-08-01 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -28.95 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           55 |      165 | 2024-07-31 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -10.37 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           54 |      303 | 2024-07-27 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -1.80 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           53 |      335 | 2024-07-26 | DMS               | W   | 1.000      | 0.650        | -                | 0.446 (0.290)    | 1 (1.000) |     4.96 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           52 |      370 | 2024-07-25 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -2.74 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           51 |      395 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.267 (0.174)    | 1 (1.000) |     4.23 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           50 |      405 | 2024-07-24 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -9.55 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           49 |     1209 | 2024-06-09 | Monte             | W   | 0.827      | -            | -                | -                | 0 (0.000) |     7.18 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           48 |     1238 | 2024-06-09 | B8                | W   | 0.825      | 0.143        | 0.165 (0.019)    | 0.951 (0.112)    | 0 (0.000) |    10.75 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     1296 | 2024-06-08 | Monte             | W   | 0.819      | -            | -                | -                | 0 (0.000) |     6.96 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     1300 | 2024-06-08 | 1WIN              | W   | 0.819      | -            | -                | -                | 0 (0.000) |     6.29 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     1605 | 2024-06-01 | MOUZ NXT          | L   | 0.772      | -            | -                | -                | -         |   -15.49 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     1622 | 2024-05-31 | Permitta          | W   | 0.767      | 0.435        | -                | 0.876 (0.292)    | 0 (0.000) |     4.14 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     1871 | 2024-05-21 | GamerLegion       | L   | 0.701      | -            | -                | -                | -         |   -11.86 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     1938 | 2024-05-19 | paiN              | W   | 0.686      | 0.769        | 0.327 (0.172)    | 0.867 (0.457)    | -         |    15.96 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     1942 | 2024-05-19 | Liquid            | L   | 0.686      | -            | -                | -                | -         |    -2.12 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     1963 | 2024-05-18 | paiN              | W   | 0.680      | 0.769        | 0.327 (0.171)    | 0.867 (0.453)    | -         |    16.43 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2360 | 2024-05-04 | BetBoom           | W   | 0.587      | 0.435        | 0.251 (0.064)    | 0.541 (0.138)    | -         |    14.71 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     2370 | 2024-05-04 | Metizport         | W   | 0.585      | -            | -                | -                | -         |     3.66 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     2380 | 2024-05-03 | Gaimin Gladiators | W   | 0.579      | 0.435        | 0.038 (0.010)    | -                | -         |     5.44 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     2395 | 2024-05-02 | BLEED             | W   | 0.574      | 0.435        | 0.091 (0.023)    | 0.396 (0.099)    | -         |     7.20 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     2428 | 2024-05-01 | fnatic            | L   | 0.566      | -            | -                | -                | -         |    -1.96 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     2446 | 2024-04-30 | Gaimin Gladiators | W   | 0.560      | -            | -                | -                | -         |     5.30 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     2471 | 2024-04-29 | Permitta          | W   | 0.553      | 0.384        | -                | 0.876 (0.186)    | -         |     4.56 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     2596 | 2024-04-24 | Nexus             | W   | 0.518      | -            | -                | -                | -         |     2.63 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     2643 | 2024-04-21 | Gaimin Gladiators | L   | 0.499      | -            | -                | -                | -         |   -10.22 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     2718 | 2024-04-19 | ENCE              | W   | 0.486      | 0.384        | 0.169 (0.032)    | -                | -         |    12.77 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     2762 | 2024-04-18 | Apeks             | L   | 0.480      | -            | -                | -                | -         |   -11.59 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     2771 | 2024-04-18 | ex-Guild Eagles   | W   | 0.479      | -            | -                | -                | -         |     2.22 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           27 |     2846 | 2024-04-16 | B8                | W   | 0.465      | 0.384        | 0.165 (0.029)    | 0.951 (0.170)    | -         |     5.42 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           26 |     2898 | 2024-04-12 | Aurora            | L   | 0.440      | -            | -                | -                | -         |    -0.79 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           25 |     2935 | 2024-04-11 | BetBoom           | W   | 0.432      | 0.143        | 0.251 (0.015)    | -                | -         |    11.34 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           24 |     2967 | 2024-04-10 | Apeks             | W   | 0.427      | -            | -                | -                | -         |     3.39 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           23 |     2981 | 2024-04-10 | Enterprise        | L   | 0.425      | -            | -                | -                | -         |   -10.29 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           22 |     3190 | 2024-04-03 | Insilio           | W   | 0.381      | -            | -                | -                | -         |     2.73 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           21 |     3201 | 2024-04-03 | ex-Guild Eagles   | W   | 0.379      | -            | -                | -                | -         |     1.72 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           20 |     3210 | 2024-04-03 | Alliance          | W   | 0.378      | -            | -                | -                | -         |     2.21 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           19 |     3239 | 2024-04-02 | PARIVISION        | W   | 0.373      | -            | -                | -                | -         |     5.61 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           18 |     3240 | 2024-04-02 | ex-Guild Eagles   | L   | 0.373      | -            | -                | -                | -         |   -10.08 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           17 |     3251 | 2024-04-02 | ALTERNATE aTTaX   | W   | 0.371      | -            | -                | -                | -         |     3.46 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           16 |     3474 | 2024-03-18 | The MongolZ       | L   | 0.273      | -            | -                | -                | -         |    -0.09 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           15 |     3491 | 2024-03-17 | Apeks             | L   | 0.267      | -            | -                | -                | -         |    -6.55 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     3501 | 2024-03-17 | GamerLegion       | L   | 0.266      | -            | -                | -                | -         |    -7.39 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     3810 | 2024-03-05 | FORZE             | L   | 0.187      | -            | -                | -                | -         |    -4.67 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     3815 | 2024-03-05 | Zero Tenacity     | W   | 0.187      | -            | -                | -                | -         |     2.61 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     3911 | 2024-03-01 | BIG               | L   | 0.158      | -            | -                | -                | -         |    -1.41 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     3929 | 2024-02-28 | Young Ninjas      | L   | 0.147      | -            | -                | -                | -         |    -4.17 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     4192 | 2024-02-17 | 9 Pandas          | W   | 0.072      | -            | -                | -                | 1 (0.072) |     0.69 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     4221 | 2024-02-16 | Falcons           | W   | 0.065      | -            | -                | -                | 1 (0.065) |     1.69 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     4245 | 2024-02-15 | fnatic            | L   | 0.059      | -            | -                | -                | -         |    -0.17 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     4279 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.053      | -            | -                | -                | 1 (0.053) |     0.03 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     4283 | 2024-02-14 | Enterprise        | L   | 0.052      | -            | -                | -                | -         |    -1.29 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     4343 | 2024-02-10 | Sashi             | L   | 0.026      | -            | -                | -                | -         |    -0.40 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     4351 | 2024-02-09 | Nemiga            | L   | 0.021      | -            | -                | -                | -         |    -0.30 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     4368 | 2024-02-08 | RUBY              | W   | 0.014      | -            | -                | -                | -         |     0.10 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     4373 | 2024-02-08 | Insilio           | W   | 0.013      | -            | -                | -                | -         |     0.08 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($42,099.38)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-02 |      0.780 | $2,000.00      | $1,559.21       |
| 2024-05-23 |      0.713 | $12,500.00     | $8,906.54       |
| 2024-05-04 |      0.587 | $22,000.00     | $12,904.12      |
| 2024-05-02 |      0.573 | $1,500.00      | $859.83         |
| 2024-03-20 |      0.287 | $10,000.00     | $2,869.68       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
