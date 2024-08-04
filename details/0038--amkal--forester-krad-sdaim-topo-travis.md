### Roster Details<br />
Team Name: AMKAL<br />
Roster: Forester, Krad, Sdaim, topo, TRAVIS<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1144.8<br />
<br />
Final Rank Value (1144.8) = Starting Rank Value (1146.4) + Head To Head Adjustments (-1.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.530[<sup>1</sup>](#table2)
- Bounty Collected: 0.443[<sup>2</sup>](#table1)
- Opponent Network: 0.236[<sup>2</sup>](#table1)
- LAN Wins: 0.251[<sup>2</sup>](#table1)

The average of these factors is 0.365<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1146.4
- 400 + ( ( 0.365 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1146.4


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
|           57 |       16 | 2024-08-04 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -24.08 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           56 |      105 | 2024-08-01 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -28.95 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           55 |      164 | 2024-07-31 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -10.36 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           54 |      302 | 2024-07-27 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -1.80 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           53 |      334 | 2024-07-26 | DMS               | W   | 1.000      | 0.650        | -                | 0.446 (0.290)    | 1 (1.000) |     4.97 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           52 |      369 | 2024-07-25 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -2.74 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           51 |      394 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.267 (0.174)    | 1 (1.000) |     4.24 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           50 |      404 | 2024-07-24 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -9.54 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           49 |     1208 | 2024-06-09 | Monte             | W   | 0.827      | -            | -                | -                | 0 (0.000) |     7.19 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           48 |     1237 | 2024-06-09 | B8                | W   | 0.826      | 0.143        | 0.165 (0.019)    | 0.912 (0.108)    | 0 (0.000) |    10.76 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     1295 | 2024-06-08 | Monte             | W   | 0.820      | -            | -                | -                | 0 (0.000) |     6.97 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     1299 | 2024-06-08 | 1WIN              | W   | 0.819      | -            | -                | -                | 0 (0.000) |     6.30 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     1604 | 2024-06-01 | MOUZ NXT          | L   | 0.772      | -            | -                | -                | -         |   -15.49 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     1621 | 2024-05-31 | Permitta          | W   | 0.768      | 0.435        | -                | 0.876 (0.292)    | 0 (0.000) |     4.14 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     1870 | 2024-05-21 | GamerLegion       | L   | 0.701      | -            | -                | -                | -         |   -11.85 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     1937 | 2024-05-19 | paiN              | W   | 0.687      | 0.769        | 0.327 (0.173)    | 0.867 (0.457)    | -         |    15.98 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     1941 | 2024-05-19 | Liquid            | L   | 0.686      | -            | -                | -                | -         |    -2.11 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     1962 | 2024-05-18 | paiN              | W   | 0.681      | 0.769        | 0.327 (0.171)    | 0.867 (0.453)    | -         |    16.45 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2359 | 2024-05-04 | BetBoom           | W   | 0.587      | 0.435        | 0.251 (0.064)    | 0.541 (0.138)    | -         |    14.72 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     2369 | 2024-05-04 | Metizport         | W   | 0.585      | -            | -                | -                | -         |     3.66 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     2379 | 2024-05-03 | Gaimin Gladiators | W   | 0.580      | 0.435        | 0.038 (0.010)    | -                | -         |     5.45 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     2394 | 2024-05-02 | BLEED             | W   | 0.574      | 0.435        | 0.091 (0.023)    | 0.396 (0.099)    | -         |     7.20 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     2427 | 2024-05-01 | fnatic            | L   | 0.566      | -            | -                | -                | -         |    -1.96 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     2445 | 2024-04-30 | Gaimin Gladiators | W   | 0.561      | -            | -                | -                | -         |     5.31 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     2470 | 2024-04-29 | Permitta          | W   | 0.553      | 0.384        | -                | 0.876 (0.186)    | -         |     4.57 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     2595 | 2024-04-24 | Nexus             | W   | 0.519      | -            | -                | -                | -         |     2.63 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     2642 | 2024-04-21 | Gaimin Gladiators | L   | 0.500      | -            | -                | -                | -         |   -10.22 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     2717 | 2024-04-19 | ENCE              | W   | 0.486      | 0.384        | 0.169 (0.032)    | -                | -         |    12.78 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     2761 | 2024-04-18 | Apeks             | L   | 0.480      | -            | -                | -                | -         |   -11.59 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     2770 | 2024-04-18 | ex-Guild Eagles   | W   | 0.479      | -            | -                | -                | -         |     2.23 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           27 |     2845 | 2024-04-16 | B8                | W   | 0.465      | 0.384        | 0.165 (0.030)    | 0.912 (0.163)    | -         |     5.43 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           26 |     2897 | 2024-04-12 | Aurora            | L   | 0.441      | -            | -                | -                | -         |    -0.80 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           25 |     2934 | 2024-04-11 | BetBoom           | W   | 0.432      | 0.143        | 0.251 (0.015)    | -                | -         |    11.35 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           24 |     2966 | 2024-04-10 | Apeks             | W   | 0.427      | -            | -                | -                | -         |     3.40 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           23 |     2980 | 2024-04-10 | Enterprise        | L   | 0.425      | -            | -                | -                | -         |   -10.29 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           22 |     3189 | 2024-04-03 | Insilio           | W   | 0.381      | -            | -                | -                | -         |     2.74 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           21 |     3200 | 2024-04-03 | ex-Guild Eagles   | W   | 0.380      | -            | -                | -                | -         |     1.73 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           20 |     3209 | 2024-04-03 | Alliance          | W   | 0.379      | -            | -                | -                | -         |     2.22 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           19 |     3238 | 2024-04-02 | PARIVISION        | W   | 0.373      | -            | -                | -                | -         |     5.61 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           18 |     3239 | 2024-04-02 | ex-Guild Eagles   | L   | 0.373      | -            | -                | -                | -         |   -10.08 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           17 |     3250 | 2024-04-02 | ALTERNATE aTTaX   | W   | 0.372      | -            | -                | -                | -         |     3.47 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           16 |     3473 | 2024-03-18 | The MongolZ       | L   | 0.273      | -            | -                | -                | -         |    -0.09 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           15 |     3490 | 2024-03-17 | Apeks             | L   | 0.268      | -            | -                | -                | -         |    -6.55 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     3500 | 2024-03-17 | GamerLegion       | L   | 0.267      | -            | -                | -                | -         |    -7.39 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     3809 | 2024-03-05 | FORZE             | L   | 0.188      | -            | -                | -                | -         |    -4.68 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     3814 | 2024-03-05 | Zero Tenacity     | W   | 0.187      | -            | -                | -                | -         |     2.60 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     3910 | 2024-03-01 | BIG               | L   | 0.159      | -            | -                | -                | -         |    -1.41 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     3928 | 2024-02-28 | Young Ninjas      | L   | 0.147      | -            | -                | -                | -         |    -4.18 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     4191 | 2024-02-17 | 9 Pandas          | W   | 0.072      | -            | -                | -                | 1 (0.072) |     0.70 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     4220 | 2024-02-16 | Falcons           | W   | 0.065      | -            | -                | -                | 1 (0.065) |     1.70 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     4244 | 2024-02-15 | fnatic            | L   | 0.059      | -            | -                | -                | -         |    -0.17 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     4278 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.054      | -            | -                | -                | 1 (0.054) |     0.03 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     4282 | 2024-02-14 | Enterprise        | L   | 0.053      | -            | -                | -                | -         |    -1.30 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     4342 | 2024-02-10 | Sashi             | L   | 0.026      | -            | -                | -                | -         |    -0.40 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     4350 | 2024-02-09 | Nemiga            | L   | 0.021      | -            | -                | -                | -         |    -0.31 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     4367 | 2024-02-08 | RUBY              | W   | 0.014      | -            | -                | -                | -         |     0.10 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     4372 | 2024-02-08 | Insilio           | W   | 0.013      | -            | -                | -                | -         |     0.08 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($42,113.82)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-02 |      0.780 | $2,000.00      | $1,559.81       |
| 2024-05-23 |      0.713 | $12,500.00     | $8,910.30       |
| 2024-05-04 |      0.587 | $22,000.00     | $12,910.74      |
| 2024-05-02 |      0.574 | $1,500.00      | $860.28         |
| 2024-03-20 |      0.287 | $10,000.00     | $2,872.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
