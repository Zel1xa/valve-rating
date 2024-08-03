### Roster Details<br />
Team Name: AMKAL<br />
Roster: Forester, Krad, Sdaim, topo, TRAVIS<br />
Global Rank: [34](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [25]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1166.9<br />
<br />
Final Rank Value (1166.9) = Starting Rank Value (1150.7) + Head To Head Adjustments (16.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.530[<sup>1</sup>](#table2)
- Bounty Collected: 0.444[<sup>2</sup>](#table1)
- Opponent Network: 0.242[<sup>2</sup>](#table1)
- LAN Wins: 0.252[<sup>2</sup>](#table1)

The average of these factors is 0.367<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1150.7
- 400 + ( ( 0.367 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1150.7


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
|           56 |       54 | 2024-08-01 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -28.92 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           55 |      108 | 2024-07-31 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -10.33 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           54 |      245 | 2024-07-27 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -1.81 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           53 |      277 | 2024-07-26 | DMS               | W   | 1.000      | 0.650        | -                | 0.462 (0.300)    | 1 (1.000) |     5.10 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           52 |      312 | 2024-07-25 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -2.80 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           51 |      337 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.275 (0.179)    | 1 (1.000) |     4.14 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           50 |      347 | 2024-07-24 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -9.76 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           49 |     1118 | 2024-06-09 | Monte             | W   | 0.834      | -            | -                | -                | 0 (0.000) |     7.05 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           48 |     1147 | 2024-06-09 | B8                | W   | 0.832      | 0.143        | 0.166 (0.020)    | 0.945 (0.112)    | 0 (0.000) |    10.82 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     1201 | 2024-06-08 | Monte             | W   | 0.826      | -            | -                | -                | 0 (0.000) |     6.81 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     1204 | 2024-06-08 | 1WIN              | W   | 0.826      | -            | -                | -                | 0 (0.000) |     5.93 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     1506 | 2024-06-01 | MOUZ NXT          | L   | 0.779      | -            | -                | -                | -         |   -15.67 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     1523 | 2024-05-31 | Permitta          | W   | 0.774      | 0.435        | -                | 0.887 (0.298)    | 0 (0.000) |     4.19 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     1771 | 2024-05-21 | GamerLegion       | L   | 0.707      | -            | -                | -                | -         |   -12.01 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     1837 | 2024-05-19 | paiN              | W   | 0.693      | 0.769        | 0.324 (0.173)    | 0.859 (0.458)    | -         |    15.15 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     1841 | 2024-05-19 | Liquid            | L   | 0.692      | -            | -                | -                | -         |    -3.12 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     1862 | 2024-05-18 | paiN              | W   | 0.687      | 0.769        | 0.324 (0.171)    | 0.859 (0.454)    | -         |    15.63 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2258 | 2024-05-04 | BetBoom           | W   | 0.593      | 0.435        | 0.252 (0.065)    | 0.563 (0.145)    | -         |    14.84 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     2268 | 2024-05-04 | Metizport         | W   | 0.591      | 0.435        | -                | 0.433 (0.111)    | -         |     4.57 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     2278 | 2024-05-03 | Gaimin Gladiators | W   | 0.586      | 0.435        | 0.038 (0.010)    | -                | -         |     5.53 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     2293 | 2024-05-02 | BLEED             | W   | 0.580      | 0.435        | 0.092 (0.023)    | -                | -         |     7.26 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     2326 | 2024-05-01 | fnatic            | L   | 0.573      | -            | -                | -                | -         |    -4.49 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     2344 | 2024-04-30 | Gaimin Gladiators | W   | 0.567      | -            | -                | -                | -         |     5.36 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     2369 | 2024-04-29 | Permitta          | W   | 0.559      | 0.384        | -                | 0.887 (0.191)    | -         |     4.57 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     2493 | 2024-04-24 | Nexus             | W   | 0.525      | -            | -                | -                | -         |     2.66 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     2540 | 2024-04-21 | Gaimin Gladiators | L   | 0.506      | -            | -                | -                | -         |   -10.35 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     2615 | 2024-04-19 | ENCE              | W   | 0.492      | 0.384        | 0.170 (0.032)    | -                | -         |    12.88 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     2659 | 2024-04-18 | Apeks             | L   | 0.486      | -            | -                | -                | -         |   -11.82 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     2668 | 2024-04-18 | ex-Guild Eagles   | W   | 0.485      | -            | -                | -                | -         |     2.27 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           27 |     2743 | 2024-04-16 | B8                | W   | 0.471      | 0.384        | 0.166 (0.030)    | 0.945 (0.171)    | -         |     5.47 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           26 |     2795 | 2024-04-12 | Aurora            | L   | 0.447      | -            | -                | -                | -         |    -0.81 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           25 |     2832 | 2024-04-11 | BetBoom           | W   | 0.439      | 0.143        | 0.252 (0.016)    | -                | -         |    11.48 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           24 |     2864 | 2024-04-10 | Apeks             | W   | 0.434      | -            | -                | -                | -         |     3.38 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           23 |     2878 | 2024-04-10 | Enterprise        | L   | 0.431      | -            | -                | -                | -         |   -10.46 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           22 |     3087 | 2024-04-03 | Insilio           | W   | 0.387      | -            | -                | -                | -         |     2.77 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           21 |     3098 | 2024-04-03 | ex-Guild Eagles   | W   | 0.386      | -            | -                | -                | -         |     1.76 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           20 |     3107 | 2024-04-03 | Alliance          | W   | 0.385      | -            | -                | -                | -         |     2.24 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           19 |     3136 | 2024-04-02 | PARIVISION        | W   | 0.380      | -            | -                | -                | -         |     5.70 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           18 |     3137 | 2024-04-02 | ex-Guild Eagles   | L   | 0.379      | -            | -                | -                | -         |   -10.25 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           17 |     3148 | 2024-04-02 | ALTERNATE aTTaX   | W   | 0.378      | -            | -                | -                | -         |     3.50 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           16 |     3366 | 2024-03-18 | The MongolZ       | L   | 0.279      | -            | -                | -                | -         |    -0.09 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           15 |     3383 | 2024-03-17 | Apeks             | L   | 0.274      | -            | -                | -                | -         |    -6.72 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     3393 | 2024-03-17 | GamerLegion       | L   | 0.273      | -            | -                | -                | -         |    -7.55 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     3699 | 2024-03-05 | FORZE             | L   | 0.194      | -            | -                | -                | -         |    -4.84 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     3704 | 2024-03-05 | Zero Tenacity     | W   | 0.193      | -            | -                | -                | -         |     2.66 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     3800 | 2024-03-01 | BIG               | L   | 0.165      | -            | -                | -                | -         |    -1.46 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     3818 | 2024-02-28 | Young Ninjas      | L   | 0.153      | -            | -                | -                | -         |    -4.36 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     4080 | 2024-02-17 | 9 Pandas          | W   | 0.078      | -            | -                | -                | 1 (0.078) |     0.74 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     4109 | 2024-02-16 | Falcons           | W   | 0.072      | -            | -                | -                | 1 (0.072) |     1.87 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     4133 | 2024-02-15 | fnatic            | L   | 0.065      | -            | -                | -                | -         |    -0.48 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     4167 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.060      | -            | -                | -                | 1 (0.060) |     0.03 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     4171 | 2024-02-14 | Enterprise        | L   | 0.059      | -            | -                | -                | -         |    -1.46 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     4231 | 2024-02-10 | Sashi             | L   | 0.033      | -            | -                | -                | -         |    -0.50 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     4238 | 2024-02-09 | Nemiga            | L   | 0.027      | -            | -                | -                | -         |    -0.42 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     4256 | 2024-02-08 | RUBY              | W   | 0.020      | -            | -                | -                | -         |     0.15 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     4261 | 2024-02-08 | Insilio           | W   | 0.019      | -            | -                | -                | -         |     0.12 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($42,413.82)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-02 |      0.786 | $2,000.00      | $1,572.31       |
| 2024-05-23 |      0.719 | $12,500.00     | $8,988.43       |
| 2024-05-04 |      0.593 | $22,000.00     | $13,048.24      |
| 2024-05-02 |      0.580 | $1,500.00      | $869.65         |
| 2024-03-20 |      0.294 | $10,000.00     | $2,935.19       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
