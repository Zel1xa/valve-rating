### Roster Details<br />
Team Name: AMKAL<br />
Roster: Forester, Krad, Sdaim, topo, TRAVIS<br />
Global Rank: [37](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1144.7<br />
<br />
Final Rank Value (1144.7) = Starting Rank Value (1144.8) + Head To Head Adjustments (-0.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.530[<sup>1</sup>](#table2)
- Bounty Collected: 0.442[<sup>2</sup>](#table1)
- Opponent Network: 0.232[<sup>2</sup>](#table1)
- LAN Wins: 0.250[<sup>2</sup>](#table1)

The average of these factors is 0.363<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1144.8
- 400 + ( ( 0.363 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1144.8


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
|           57 |       42 | 2024-08-04 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -23.63 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           56 |      130 | 2024-08-01 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -28.93 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           55 |      189 | 2024-07-31 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -10.18 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           54 |      328 | 2024-07-27 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -1.77 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           53 |      360 | 2024-07-26 | DMS               | W   | 1.000      | 0.650        | -                | 0.438 (0.285)    | 1 (1.000) |     5.07 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           52 |      395 | 2024-07-25 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -2.73 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           51 |      420 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.264 (0.172)    | 1 (1.000) |     4.30 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           50 |      430 | 2024-07-24 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -9.33 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           49 |     1234 | 2024-06-09 | Monte             | W   | 0.820      | 0.143        | 0.080 (0.009)    | -                | 0 (0.000) |     7.18 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           48 |     1263 | 2024-06-09 | B8                | W   | 0.819      | 0.143        | 0.165 (0.019)    | 0.935 (0.109)    | 0 (0.000) |    10.72 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     1321 | 2024-06-08 | Monte             | W   | 0.813      | -            | -                | -                | 0 (0.000) |     6.97 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     1325 | 2024-06-08 | 1WIN              | W   | 0.812      | -            | -                | -                | 0 (0.000) |     6.42 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     1630 | 2024-06-01 | MOUZ NXT          | L   | 0.765      | -            | -                | -                | -         |   -15.20 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     1647 | 2024-05-31 | Permitta          | W   | 0.760      | 0.435        | -                | 0.863 (0.285)    | 0 (0.000) |     4.16 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     1896 | 2024-05-21 | GamerLegion       | L   | 0.694      | -            | -                | -                | -         |   -11.69 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     1963 | 2024-05-19 | paiN              | W   | 0.680      | 0.769        | 0.325 (0.170)    | 0.856 (0.447)    | -         |    15.77 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     1967 | 2024-05-19 | Liquid            | L   | 0.679      | -            | -                | -                | -         |    -2.07 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     1988 | 2024-05-18 | paiN              | W   | 0.673      | 0.769        | 0.325 (0.168)    | 0.856 (0.443)    | -         |    16.23 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2385 | 2024-05-04 | BetBoom           | W   | 0.580      | 0.435        | 0.249 (0.063)    | 0.529 (0.133)    | -         |    14.54 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     2395 | 2024-05-04 | Metizport         | W   | 0.578      | -            | -                | -                | -         |     3.61 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     2405 | 2024-05-03 | Gaimin Gladiators | W   | 0.573      | -            | -                | -                | -         |     5.34 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     2420 | 2024-05-02 | BLEED             | W   | 0.567      | 0.435        | 0.090 (0.022)    | 0.387 (0.095)    | -         |     7.08 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     2453 | 2024-05-01 | fnatic            | L   | 0.559      | -            | -                | -                | -         |    -1.93 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     2471 | 2024-04-30 | Gaimin Gladiators | W   | 0.553      | -            | -                | -                | -         |     5.19 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     2496 | 2024-04-29 | Permitta          | W   | 0.546      | 0.384        | -                | 0.863 (0.181)    | -         |     4.56 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     2621 | 2024-04-24 | Nexus             | W   | 0.511      | -            | -                | -                | -         |     2.62 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     2668 | 2024-04-21 | Gaimin Gladiators | L   | 0.492      | -            | -                | -                | -         |   -10.15 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     2743 | 2024-04-19 | ENCE              | W   | 0.479      | 0.384        | 0.174 (0.032)    | -                | -         |    12.72 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     2787 | 2024-04-18 | Apeks             | L   | 0.473      | -            | -                | -                | -         |   -11.45 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     2796 | 2024-04-18 | ex-Guild Eagles   | W   | 0.472      | -            | -                | -                | -         |     2.20 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           27 |     2871 | 2024-04-16 | B8                | W   | 0.458      | 0.384        | 0.165 (0.029)    | 0.935 (0.165)    | -         |     5.37 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           26 |     2923 | 2024-04-12 | Aurora            | L   | 0.434      | -            | -                | -                | -         |    -0.76 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           25 |     2960 | 2024-04-11 | BetBoom           | W   | 0.425      | 0.143        | 0.249 (0.015)    | -                | -         |    11.15 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           24 |     2992 | 2024-04-10 | Apeks             | W   | 0.420      | -            | -                | -                | -         |     3.31 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           23 |     3006 | 2024-04-10 | Enterprise        | L   | 0.418      | -            | -                | -                | -         |   -10.12 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           22 |     3215 | 2024-04-03 | Insilio           | W   | 0.374      | -            | -                | -                | -         |     2.70 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           21 |     3226 | 2024-04-03 | ex-Guild Eagles   | W   | 0.373      | -            | -                | -                | -         |     1.69 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           20 |     3235 | 2024-04-03 | Alliance          | W   | 0.372      | -            | -                | -                | -         |     2.18 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           19 |     3264 | 2024-04-02 | PARIVISION        | W   | 0.366      | -            | -                | -                | -         |     5.61 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           18 |     3265 | 2024-04-02 | ex-Guild Eagles   | L   | 0.366      | -            | -                | -                | -         |    -9.89 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           17 |     3276 | 2024-04-02 | ALTERNATE aTTaX   | W   | 0.365      | -            | -                | -                | -         |     3.41 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           16 |     3499 | 2024-03-18 | The MongolZ       | L   | 0.266      | -            | -                | -                | -         |    -0.09 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           15 |     3516 | 2024-03-17 | Apeks             | L   | 0.261      | -            | -                | -                | -         |    -6.39 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     3526 | 2024-03-17 | GamerLegion       | L   | 0.259      | -            | -                | -                | -         |    -7.21 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     3835 | 2024-03-05 | FORZE             | L   | 0.180      | -            | -                | -                | -         |    -4.50 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     3840 | 2024-03-05 | Zero Tenacity     | W   | 0.180      | -            | -                | -                | -         |     2.55 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     3936 | 2024-03-01 | BIG               | L   | 0.151      | -            | -                | -                | -         |    -1.34 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     3954 | 2024-02-28 | Young Ninjas      | L   | 0.140      | -            | -                | -                | -         |    -3.95 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     4217 | 2024-02-17 | 9 Pandas          | W   | 0.065      | -            | -                | -                | 1 (0.065) |     0.63 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     4246 | 2024-02-16 | Falcons           | W   | 0.058      | -            | -                | -                | 1 (0.058) |     1.51 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     4270 | 2024-02-15 | fnatic            | L   | 0.052      | -            | -                | -                | -         |    -0.15 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     4304 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.046      | -            | -                | -                | 1 (0.046) |     0.02 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     4308 | 2024-02-14 | Enterprise        | L   | 0.046      | -            | -                | -                | -         |    -1.12 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     4368 | 2024-02-10 | Sashi             | L   | 0.019      | -            | -                | -                | -         |    -0.29 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     4376 | 2024-02-09 | Nemiga            | L   | 0.014      | -            | -                | -                | -         |    -0.20 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     4393 | 2024-02-08 | RUBY              | W   | 0.007      | -            | -                | -                | -         |     0.05 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     4398 | 2024-02-08 | Insilio           | W   | 0.006      | -            | -                | -                | -         |     0.04 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($41,771.60)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-02 |      0.773 | $2,000.00      | $1,545.56       |
| 2024-05-23 |      0.706 | $12,500.00     | $8,821.18       |
| 2024-05-04 |      0.580 | $22,000.00     | $12,753.89      |
| 2024-05-02 |      0.566 | $1,500.00      | $849.58         |
| 2024-03-20 |      0.280 | $10,000.00     | $2,801.39       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
