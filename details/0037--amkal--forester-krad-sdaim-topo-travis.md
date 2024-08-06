### Roster Details<br />
Team Name: AMKAL<br />
Roster: Forester, Krad, Sdaim, topo, TRAVIS<br />
Global Rank: [37](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1144.9<br />
<br />
Final Rank Value (1144.9) = Starting Rank Value (1145.4) + Head To Head Adjustments (-0.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.530[<sup>1</sup>](#table2)
- Bounty Collected: 0.441[<sup>2</sup>](#table1)
- Opponent Network: 0.233[<sup>2</sup>](#table1)
- LAN Wins: 0.249[<sup>2</sup>](#table1)

The average of these factors is 0.363<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1145.4
- 400 + ( ( 0.363 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1145.4


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
|           57 |       45 | 2024-08-04 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -23.64 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           56 |      133 | 2024-08-01 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -28.93 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           55 |      192 | 2024-07-31 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -10.18 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           54 |      331 | 2024-07-27 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -1.77 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           53 |      363 | 2024-07-26 | DMS               | W   | 1.000      | 0.650        | -                | 0.438 (0.285)    | 1 (1.000) |     5.06 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           52 |      398 | 2024-07-25 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -2.74 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           51 |      423 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.265 (0.172)    | 1 (1.000) |     4.29 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           50 |      433 | 2024-07-24 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -9.28 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           49 |     1237 | 2024-06-09 | Monte             | W   | 0.818      | 0.143        | 0.080 (0.009)    | -                | 0 (0.000) |     7.15 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           48 |     1266 | 2024-06-09 | B8                | W   | 0.816      | 0.143        | 0.164 (0.019)    | 0.934 (0.109)    | 0 (0.000) |    10.68 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     1324 | 2024-06-08 | Monte             | W   | 0.810      | -            | -                | -                | 0 (0.000) |     6.94 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     1328 | 2024-06-08 | 1WIN              | W   | 0.810      | -            | -                | -                | 0 (0.000) |     6.41 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     1633 | 2024-06-01 | MOUZ NXT          | L   | 0.763      | -            | -                | -                | -         |   -15.16 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     1650 | 2024-05-31 | Permitta          | W   | 0.758      | 0.435        | -                | 0.901 (0.297)    | 0 (0.000) |     4.25 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     1899 | 2024-05-21 | GamerLegion       | L   | 0.692      | -            | -                | -                | -         |   -11.69 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     1966 | 2024-05-19 | paiN              | W   | 0.677      | 0.769        | 0.325 (0.169)    | 0.857 (0.446)    | -         |    15.70 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     1970 | 2024-05-19 | Liquid            | L   | 0.677      | -            | -                | -                | -         |    -2.07 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     1991 | 2024-05-18 | paiN              | W   | 0.671      | 0.769        | 0.325 (0.167)    | 0.857 (0.442)    | -         |    16.16 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2388 | 2024-05-04 | BetBoom           | W   | 0.578      | 0.435        | 0.249 (0.062)    | 0.527 (0.132)    | -         |    14.46 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     2398 | 2024-05-04 | Metizport         | W   | 0.576      | -            | -                | -                | -         |     3.58 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     2408 | 2024-05-03 | Gaimin Gladiators | W   | 0.570      | -            | -                | -                | -         |     5.29 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     2423 | 2024-05-02 | BLEED             | W   | 0.565      | 0.435        | 0.090 (0.022)    | 0.385 (0.095)    | -         |     7.04 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     2456 | 2024-05-01 | fnatic            | L   | 0.557      | -            | -                | -                | -         |    -1.93 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     2474 | 2024-04-30 | Gaimin Gladiators | W   | 0.551      | -            | -                | -                | -         |     5.14 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     2499 | 2024-04-29 | Permitta          | W   | 0.544      | 0.384        | -                | 0.901 (0.188)    | -         |     4.69 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     2624 | 2024-04-24 | Nexus             | W   | 0.509      | -            | -                | -                | -         |     2.60 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     2671 | 2024-04-21 | Gaimin Gladiators | L   | 0.490      | -            | -                | -                | -         |   -10.13 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     2746 | 2024-04-19 | ENCE              | W   | 0.477      | 0.384        | 0.174 (0.032)    | -                | -         |    12.65 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     2790 | 2024-04-18 | Apeks             | L   | 0.471      | -            | -                | -                | -         |   -11.42 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     2799 | 2024-04-18 | ex-Guild Eagles   | W   | 0.470      | -            | -                | -                | -         |     2.17 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           27 |     2874 | 2024-04-16 | B8                | W   | 0.456      | 0.384        | 0.164 (0.029)    | 0.934 (0.164)    | -         |     5.33 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           26 |     2926 | 2024-04-12 | Aurora            | L   | 0.431      | -            | -                | -                | -         |    -0.75 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           25 |     2963 | 2024-04-11 | BetBoom           | W   | 0.423      | 0.143        | 0.249 (0.015)    | -                | -         |    11.07 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           24 |     2995 | 2024-04-10 | Apeks             | W   | 0.418      | -            | -                | -                | -         |     3.27 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           23 |     3009 | 2024-04-10 | Enterprise        | L   | 0.416      | -            | -                | -                | -         |   -10.06 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           22 |     3218 | 2024-04-03 | Insilio           | W   | 0.372      | -            | -                | -                | -         |     2.69 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           21 |     3229 | 2024-04-03 | ex-Guild Eagles   | W   | 0.370      | -            | -                | -                | -         |     1.67 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           20 |     3238 | 2024-04-03 | Alliance          | W   | 0.369      | -            | -                | -                | -         |     2.16 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           19 |     3267 | 2024-04-02 | PARIVISION        | W   | 0.364      | -            | -                | -                | -         |     5.56 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           18 |     3268 | 2024-04-02 | ex-Guild Eagles   | L   | 0.364      | -            | -                | -                | -         |    -9.84 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           17 |     3279 | 2024-04-02 | ALTERNATE aTTaX   | W   | 0.362      | -            | -                | -                | -         |     3.38 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           16 |     3502 | 2024-03-18 | The MongolZ       | L   | 0.264      | -            | -                | -                | -         |    -0.09 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           15 |     3519 | 2024-03-17 | Apeks             | L   | 0.258      | -            | -                | -                | -         |    -6.35 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     3529 | 2024-03-17 | GamerLegion       | L   | 0.257      | -            | -                | -                | -         |    -7.16 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     3838 | 2024-03-05 | FORZE             | L   | 0.178      | -            | -                | -                | -         |    -4.45 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     3843 | 2024-03-05 | Zero Tenacity     | W   | 0.178      | -            | -                | -                | -         |     2.51 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     3939 | 2024-03-01 | BIG               | L   | 0.149      | -            | -                | -                | -         |    -1.33 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     3957 | 2024-02-28 | Young Ninjas      | L   | 0.138      | -            | -                | -                | -         |    -3.89 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     4220 | 2024-02-17 | 9 Pandas          | W   | 0.063      | -            | -                | -                | 1 (0.063) |     0.60 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     4249 | 2024-02-16 | Falcons           | W   | 0.056      | -            | -                | -                | 1 (0.056) |     1.46 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     4273 | 2024-02-15 | fnatic            | L   | 0.050      | -            | -                | -                | -         |    -0.14 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     4307 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.044      | -            | -                | -                | 1 (0.044) |     0.02 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     4311 | 2024-02-14 | Enterprise        | L   | 0.043      | -            | -                | -                | -         |    -1.07 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     4371 | 2024-02-10 | Sashi             | L   | 0.017      | -            | -                | -                | -         |    -0.26 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     4379 | 2024-02-09 | Nemiga            | L   | 0.012      | -            | -                | -                | -         |    -0.17 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     4396 | 2024-02-08 | RUBY              | W   | 0.005      | -            | -                | -                | -         |     0.04 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     4401 | 2024-02-08 | Insilio           | W   | 0.004      | -            | -                | -                | -         |     0.02 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($41,664.93)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-02 |      0.771 | $2,000.00      | $1,541.11       |
| 2024-05-23 |      0.703 | $12,500.00     | $8,793.40       |
| 2024-05-04 |      0.578 | $22,000.00     | $12,705.00      |
| 2024-05-02 |      0.564 | $1,500.00      | $846.25         |
| 2024-03-20 |      0.278 | $10,000.00     | $2,779.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
