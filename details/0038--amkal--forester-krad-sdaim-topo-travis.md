### Roster Details<br />
Team Name: AMKAL<br />
Roster: Forester, Krad, Sdaim, topo, TRAVIS<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1144.6<br />
<br />
Final Rank Value (1144.6) = Starting Rank Value (1146.4) + Head To Head Adjustments (-1.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.530[<sup>1</sup>](#table2)
- Bounty Collected: 0.443[<sup>2</sup>](#table1)
- Opponent Network: 0.236[<sup>2</sup>](#table1)
- LAN Wins: 0.250[<sup>2</sup>](#table1)

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
|           57 |       21 | 2024-08-04 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -24.07 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           56 |      109 | 2024-08-01 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -28.95 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           55 |      168 | 2024-07-31 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -10.33 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           54 |      307 | 2024-07-27 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -1.78 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           53 |      339 | 2024-07-26 | DMS               | W   | 1.000      | 0.650        | -                | 0.446 (0.290)    | 1 (1.000) |     4.98 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           52 |      374 | 2024-07-25 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -2.74 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           51 |      399 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.268 (0.174)    | 1 (1.000) |     4.25 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           50 |      409 | 2024-07-24 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -9.49 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           49 |     1213 | 2024-06-09 | Monte             | W   | 0.825      | 0.143        | 0.080 (0.009)    | -                | 0 (0.000) |     7.17 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           48 |     1242 | 2024-06-09 | B8                | W   | 0.823      | 0.143        | 0.165 (0.019)    | 0.951 (0.112)    | 0 (0.000) |    10.73 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     1300 | 2024-06-08 | Monte             | W   | 0.817      | -            | -                | -                | 0 (0.000) |     6.95 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     1304 | 2024-06-08 | 1WIN              | W   | 0.817      | -            | -                | -                | 0 (0.000) |     6.28 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     1609 | 2024-06-01 | MOUZ NXT          | L   | 0.770      | -            | -                | -                | -         |   -15.44 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     1626 | 2024-05-31 | Permitta          | W   | 0.765      | 0.435        | -                | 0.876 (0.291)    | 0 (0.000) |     4.13 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     1875 | 2024-05-21 | GamerLegion       | L   | 0.698      | -            | -                | -                | -         |   -11.77 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     1942 | 2024-05-19 | paiN              | W   | 0.684      | 0.769        | 0.326 (0.171)    | 0.868 (0.456)    | -         |    15.90 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     1946 | 2024-05-19 | Liquid            | L   | 0.683      | -            | -                | -                | -         |    -2.10 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     1967 | 2024-05-18 | paiN              | W   | 0.678      | 0.769        | 0.326 (0.170)    | 0.868 (0.452)    | -         |    16.37 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2364 | 2024-05-04 | BetBoom           | W   | 0.584      | 0.435        | 0.250 (0.063)    | 0.540 (0.137)    | -         |    14.64 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     2374 | 2024-05-04 | Metizport         | W   | 0.583      | -            | -                | -                | -         |     3.63 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     2384 | 2024-05-03 | Gaimin Gladiators | W   | 0.577      | -            | -                | -                | -         |     5.39 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     2399 | 2024-05-02 | BLEED             | W   | 0.571      | 0.435        | 0.091 (0.023)    | 0.395 (0.098)    | -         |     7.15 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     2432 | 2024-05-01 | fnatic            | L   | 0.564      | -            | -                | -                | -         |    -1.95 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     2450 | 2024-04-30 | Gaimin Gladiators | W   | 0.558      | -            | -                | -                | -         |     5.25 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     2475 | 2024-04-29 | Permitta          | W   | 0.550      | 0.384        | -                | 0.876 (0.185)    | -         |     4.54 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     2600 | 2024-04-24 | Nexus             | W   | 0.516      | -            | -                | -                | -         |     2.62 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     2647 | 2024-04-21 | Gaimin Gladiators | L   | 0.497      | -            | -                | -                | -         |   -10.20 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     2722 | 2024-04-19 | ENCE              | W   | 0.484      | 0.384        | 0.168 (0.031)    | -                | -         |    12.78 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     2766 | 2024-04-18 | Apeks             | L   | 0.477      | -            | -                | -                | -         |   -11.55 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     2775 | 2024-04-18 | ex-Guild Eagles   | W   | 0.477      | -            | -                | -                | -         |     2.21 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           27 |     2850 | 2024-04-16 | B8                | W   | 0.463      | 0.384        | 0.165 (0.029)    | 0.951 (0.169)    | -         |     5.39 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           26 |     2902 | 2024-04-12 | Aurora            | L   | 0.438      | -            | -                | -                | -         |    -0.78 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           25 |     2939 | 2024-04-11 | BetBoom           | W   | 0.430      | 0.143        | 0.250 (0.015)    | -                | -         |    11.27 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           24 |     2971 | 2024-04-10 | Apeks             | W   | 0.425      | -            | -                | -                | -         |     3.36 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           23 |     2985 | 2024-04-10 | Enterprise        | L   | 0.422      | -            | -                | -                | -         |   -10.24 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           22 |     3194 | 2024-04-03 | Insilio           | W   | 0.378      | -            | -                | -                | -         |     2.71 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           21 |     3205 | 2024-04-03 | ex-Guild Eagles   | W   | 0.377      | -            | -                | -                | -         |     1.71 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           20 |     3214 | 2024-04-03 | Alliance          | W   | 0.376      | -            | -                | -                | -         |     2.20 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           19 |     3243 | 2024-04-02 | PARIVISION        | W   | 0.371      | -            | -                | -                | -         |     5.58 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           18 |     3244 | 2024-04-02 | ex-Guild Eagles   | L   | 0.370      | -            | -                | -                | -         |   -10.02 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           17 |     3255 | 2024-04-02 | ALTERNATE aTTaX   | W   | 0.369      | -            | -                | -                | -         |     3.43 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           16 |     3478 | 2024-03-18 | The MongolZ       | L   | 0.270      | -            | -                | -                | -         |    -0.09 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           15 |     3495 | 2024-03-17 | Apeks             | L   | 0.265      | -            | -                | -                | -         |    -6.50 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     3505 | 2024-03-17 | GamerLegion       | L   | 0.264      | -            | -                | -                | -         |    -7.33 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     3814 | 2024-03-05 | FORZE             | L   | 0.185      | -            | -                | -                | -         |    -4.61 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     3819 | 2024-03-05 | Zero Tenacity     | W   | 0.184      | -            | -                | -                | -         |     2.58 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     3915 | 2024-03-01 | BIG               | L   | 0.156      | -            | -                | -                | -         |    -1.39 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     3933 | 2024-02-28 | Young Ninjas      | L   | 0.144      | -            | -                | -                | -         |    -4.10 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     4196 | 2024-02-17 | 9 Pandas          | W   | 0.069      | -            | -                | -                | 1 (0.069) |     0.67 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     4225 | 2024-02-16 | Falcons           | W   | 0.063      | -            | -                | -                | 1 (0.063) |     1.63 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     4249 | 2024-02-15 | fnatic            | L   | 0.056      | -            | -                | -                | -         |    -0.16 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     4283 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.051      | -            | -                | -                | 1 (0.051) |     0.02 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     4287 | 2024-02-14 | Enterprise        | L   | 0.050      | -            | -                | -                | -         |    -1.23 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     4347 | 2024-02-10 | Sashi             | L   | 0.024      | -            | -                | -                | -         |    -0.36 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     4355 | 2024-02-09 | Nemiga            | L   | 0.018      | -            | -                | -                | -         |    -0.27 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     4372 | 2024-02-08 | RUBY              | W   | 0.012      | -            | -                | -                | -         |     0.08 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     4377 | 2024-02-08 | Insilio           | W   | 0.010      | -            | -                | -                | -         |     0.06 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($41,984.93)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-02 |      0.777 | $2,000.00      | $1,554.44       |
| 2024-05-23 |      0.710 | $12,500.00     | $8,876.74       |
| 2024-05-04 |      0.584 | $22,000.00     | $12,851.67      |
| 2024-05-02 |      0.571 | $1,500.00      | $856.25         |
| 2024-03-20 |      0.285 | $10,000.00     | $2,845.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
