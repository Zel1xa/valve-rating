### Roster Details<br />
Team Name: AMKAL<br />
Roster: Forester, Krad, Sdaim, topo, TRAVIS<br />
Global Rank: [34](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [25]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1168.3<br />
<br />
Final Rank Value (1168.3) = Starting Rank Value (1152.7) + Head To Head Adjustments (15.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.532[<sup>1</sup>](#table2)
- Bounty Collected: 0.442[<sup>2</sup>](#table1)
- Opponent Network: 0.230[<sup>2</sup>](#table1)
- LAN Wins: 0.260[<sup>2</sup>](#table1)

The average of these factors is 0.366<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1152.7
- 400 + ( ( 0.366 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1152.7


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
|           56 |        1 | 2024-08-01 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -29.12 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           55 |       51 | 2024-07-31 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -10.20 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           54 |      189 | 2024-07-27 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -1.83 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           53 |      221 | 2024-07-26 | DMS               | W   | 1.000      | 0.650        | -                | 0.447 (0.291)    | 1 (1.000) |     4.55 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           52 |      256 | 2024-07-25 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -2.67 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           51 |      281 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.263 (0.171)    | 1 (1.000) |     3.73 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           50 |      291 | 2024-07-24 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -9.77 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           49 |     1103 | 2024-06-09 | Monte             | W   | 0.847      | -            | -                | -                | 0 (0.000) |     7.24 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           48 |     1132 | 2024-06-09 | B8                | W   | 0.845      | 0.143        | 0.168 (0.020)    | 0.878 (0.106)    | 0 (0.000) |    10.59 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     1192 | 2024-06-08 | Monte             | W   | 0.839      | -            | -                | -                | 0 (0.000) |     6.98 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     1196 | 2024-06-08 | 1WIN              | W   | 0.839      | -            | -                | -                | 0 (0.000) |     6.03 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     1514 | 2024-06-01 | MOUZ NXT          | L   | 0.792      | -            | -                | -                | -         |   -15.94 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     1531 | 2024-05-31 | Permitta          | W   | 0.787      | 0.435        | -                | 0.801 (0.274)    | 0 (0.000) |     4.13 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     1796 | 2024-05-21 | GamerLegion       | L   | 0.720      | -            | -                | -                | -         |   -12.06 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     1874 | 2024-05-19 | paiN              | W   | 0.706      | 0.769        | 0.300 (0.163)    | 0.801 (0.435)    | -         |    14.78 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     1878 | 2024-05-19 | Liquid            | L   | 0.705      | -            | -                | -                | -         |    -2.95 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     1899 | 2024-05-18 | paiN              | W   | 0.700      | 0.769        | 0.300 (0.161)    | 0.801 (0.431)    | -         |    15.28 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2308 | 2024-05-04 | BetBoom           | W   | 0.606      | 0.435        | 0.257 (0.068)    | 0.551 (0.145)    | -         |    15.26 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     2318 | 2024-05-04 | Metizport         | W   | 0.604      | 0.435        | -                | 0.424 (0.112)    | -         |     4.67 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     2328 | 2024-05-03 | Gaimin Gladiators | W   | 0.599      | 0.435        | 0.040 (0.010)    | -                | -         |     5.83 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     2343 | 2024-05-02 | BLEED             | W   | 0.593      | 0.435        | 0.095 (0.024)    | -                | -         |     7.32 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     2378 | 2024-05-01 | fnatic            | L   | 0.586      | -            | -                | -                | -         |    -4.52 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     2397 | 2024-04-30 | Gaimin Gladiators | W   | 0.580      | -            | -                | -                | -         |     5.68 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     2422 | 2024-04-29 | Permitta          | W   | 0.572      | 0.384        | -                | 0.801 (0.176)    | -         |     4.55 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     2547 | 2024-04-24 | Nexus             | W   | 0.538      | -            | -                | -                | -         |     2.73 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     2598 | 2024-04-21 | Gaimin Gladiators | L   | 0.519      | -            | -                | -                | -         |   -10.37 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     2676 | 2024-04-19 | ENCE              | W   | 0.506      | 0.384        | 0.173 (0.034)    | -                | -         |    13.33 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     2721 | 2024-04-18 | Apeks             | L   | 0.499      | -            | -                | -                | -         |   -11.94 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     2730 | 2024-04-18 | ex-Guild Eagles   | W   | 0.498      | -            | -                | -                | -         |     2.41 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           27 |     2807 | 2024-04-16 | B8                | W   | 0.484      | 0.384        | 0.168 (0.031)    | 0.878 (0.163)    | -         |     5.71 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           26 |     2859 | 2024-04-12 | Aurora            | L   | 0.460      | -            | -                | -                | -         |    -0.81 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           25 |     2897 | 2024-04-11 | BetBoom           | W   | 0.452      | 0.143        | 0.257 (0.017)    | -                | -         |    11.93 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           24 |     2929 | 2024-04-10 | Apeks             | W   | 0.447      | -            | -                | -                | -         |     3.67 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           23 |     2943 | 2024-04-10 | Enterprise        | L   | 0.444      | -            | -                | -                | -         |   -10.74 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           22 |     3154 | 2024-04-03 | Insilio           | W   | 0.400      | -            | -                | -                | -         |     2.89 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           21 |     3165 | 2024-04-03 | ex-Guild Eagles   | W   | 0.399      | -            | -                | -                | -         |     1.88 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           20 |     3178 | 2024-04-03 | Alliance          | W   | 0.398      | -            | -                | -                | -         |     2.33 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           19 |     3209 | 2024-04-02 | PARIVISION        | W   | 0.393      | -            | -                | -                | -         |     5.95 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           18 |     3210 | 2024-04-02 | ex-Guild Eagles   | L   | 0.392      | -            | -                | -                | -         |   -10.54 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           17 |     3221 | 2024-04-02 | ALTERNATE aTTaX   | W   | 0.391      | -            | -                | -                | -         |     3.64 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           16 |     3449 | 2024-03-18 | The MongolZ       | L   | 0.292      | -            | -                | -                | -         |    -0.10 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           15 |     3466 | 2024-03-17 | Apeks             | L   | 0.287      | -            | -                | -                | -         |    -6.92 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     3476 | 2024-03-17 | GamerLegion       | L   | 0.286      | -            | -                | -                | -         |    -7.85 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     3791 | 2024-03-05 | FORZE             | L   | 0.207      | -            | -                | -                | -         |    -5.11 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     3801 | 2024-03-05 | Zero Tenacity     | W   | 0.206      | -            | -                | -                | -         |     2.83 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     3898 | 2024-03-01 | BIG               | L   | 0.178      | -            | -                | -                | -         |    -2.14 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     3917 | 2024-02-28 | Young Ninjas      | L   | 0.166      | -            | -                | -                | -         |    -4.71 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     4187 | 2024-02-17 | 9 Pandas          | W   | 0.091      | -            | -                | -                | 1 (0.091) |     0.88 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     4217 | 2024-02-16 | Falcons           | W   | 0.085      | -            | -                | -                | 1 (0.085) |     2.23 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     4241 | 2024-02-15 | fnatic            | L   | 0.078      | -            | -                | -                | -         |    -0.55 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     4275 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.073      | -            | -                | -                | 1 (0.073) |     0.03 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     4279 | 2024-02-14 | Enterprise        | L   | 0.072      | -            | -                | -                | -         |    -1.77 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     4348 | 2024-02-10 | Sashi             | L   | 0.046      | -            | -                | -                | -         |    -0.69 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     4356 | 2024-02-09 | Nemiga            | L   | 0.040      | -            | -                | -                | -         |    -0.61 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     4374 | 2024-02-08 | RUBY              | W   | 0.033      | -            | -                | -                | -         |     0.25 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     4379 | 2024-02-08 | Insilio           | W   | 0.032      | -            | -                | -                | -         |     0.19 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($43,038.26)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-02 |      0.799 | $2,000.00      | $1,598.33       |
| 2024-05-23 |      0.732 | $12,500.00     | $9,151.04       |
| 2024-05-04 |      0.606 | $22,000.00     | $13,334.44      |
| 2024-05-02 |      0.593 | $1,500.00      | $889.17         |
| 2024-03-20 |      0.307 | $10,000.00     | $3,065.28       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
