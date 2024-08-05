### Roster Details<br />
Team Name: AMKAL<br />
Roster: Forester, Krad, Sdaim, topo, TRAVIS<br />
Global Rank: [37](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1145.4<br />
<br />
Final Rank Value (1145.4) = Starting Rank Value (1145.8) + Head To Head Adjustments (-0.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.530[<sup>1</sup>](#table2)
- Bounty Collected: 0.442[<sup>2</sup>](#table1)
- Opponent Network: 0.234[<sup>2</sup>](#table1)
- LAN Wins: 0.249[<sup>2</sup>](#table1)

The average of these factors is 0.364<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1145.8
- 400 + ( ( 0.364 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1145.8


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
|           57 |       43 | 2024-08-04 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -23.65 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           56 |      131 | 2024-08-01 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -28.94 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           55 |      190 | 2024-07-31 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -10.20 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           54 |      329 | 2024-07-27 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -1.77 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           53 |      361 | 2024-07-26 | DMS               | W   | 1.000      | 0.650        | -                | 0.438 (0.285)    | 1 (1.000) |     5.06 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           52 |      396 | 2024-07-25 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -2.74 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           51 |      421 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.264 (0.172)    | 1 (1.000) |     4.28 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           50 |      431 | 2024-07-24 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -9.33 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           49 |     1235 | 2024-06-09 | Monte             | W   | 0.820      | 0.143        | 0.080 (0.009)    | -                | 0 (0.000) |     7.16 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           48 |     1264 | 2024-06-09 | B8                | W   | 0.818      | 0.143        | 0.165 (0.019)    | 0.935 (0.109)    | 0 (0.000) |    10.70 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     1322 | 2024-06-08 | Monte             | W   | 0.812      | -            | -                | -                | 0 (0.000) |     6.94 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     1326 | 2024-06-08 | 1WIN              | W   | 0.812      | -            | -                | -                | 0 (0.000) |     6.42 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     1631 | 2024-06-01 | MOUZ NXT          | L   | 0.765      | -            | -                | -                | -         |   -15.21 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     1648 | 2024-05-31 | Permitta          | W   | 0.760      | 0.435        | -                | 0.902 (0.298)    | 0 (0.000) |     4.25 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     1897 | 2024-05-21 | GamerLegion       | L   | 0.693      | -            | -                | -                | -         |   -11.71 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     1964 | 2024-05-19 | paiN              | W   | 0.679      | 0.769        | 0.325 (0.170)    | 0.856 (0.447)    | -         |    15.74 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     1968 | 2024-05-19 | Liquid            | L   | 0.678      | -            | -                | -                | -         |    -2.08 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     1989 | 2024-05-18 | paiN              | W   | 0.673      | 0.769        | 0.325 (0.168)    | 0.856 (0.443)    | -         |    16.20 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2386 | 2024-05-04 | BetBoom           | W   | 0.579      | 0.435        | 0.249 (0.063)    | 0.529 (0.133)    | -         |    14.51 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     2396 | 2024-05-04 | Metizport         | W   | 0.578      | -            | -                | -                | -         |     3.59 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     2406 | 2024-05-03 | Gaimin Gladiators | W   | 0.572      | -            | -                | -                | -         |     5.32 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     2421 | 2024-05-02 | BLEED             | W   | 0.567      | 0.435        | 0.090 (0.022)    | 0.386 (0.095)    | -         |     7.08 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     2454 | 2024-05-01 | fnatic            | L   | 0.559      | -            | -                | -                | -         |    -1.93 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     2472 | 2024-04-30 | Gaimin Gladiators | W   | 0.553      | -            | -                | -                | -         |     5.17 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     2497 | 2024-04-29 | Permitta          | W   | 0.545      | 0.384        | -                | 0.902 (0.189)    | -         |     4.70 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     2622 | 2024-04-24 | Nexus             | W   | 0.511      | -            | -                | -                | -         |     2.61 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     2669 | 2024-04-21 | Gaimin Gladiators | L   | 0.492      | -            | -                | -                | -         |   -10.15 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     2744 | 2024-04-19 | ENCE              | W   | 0.479      | 0.384        | 0.174 (0.032)    | -                | -         |    12.70 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     2788 | 2024-04-18 | Apeks             | L   | 0.473      | -            | -                | -                | -         |   -11.46 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     2797 | 2024-04-18 | ex-Guild Eagles   | W   | 0.472      | -            | -                | -                | -         |     2.19 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           27 |     2872 | 2024-04-16 | B8                | W   | 0.458      | 0.384        | 0.165 (0.029)    | 0.935 (0.164)    | -         |     5.35 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           26 |     2924 | 2024-04-12 | Aurora            | L   | 0.433      | -            | -                | -                | -         |    -0.76 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           25 |     2961 | 2024-04-11 | BetBoom           | W   | 0.425      | 0.143        | 0.249 (0.015)    | -                | -         |    11.13 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           24 |     2993 | 2024-04-10 | Apeks             | W   | 0.420      | -            | -                | -                | -         |     3.29 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           23 |     3007 | 2024-04-10 | Enterprise        | L   | 0.418      | -            | -                | -                | -         |   -10.10 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           22 |     3216 | 2024-04-03 | Insilio           | W   | 0.373      | -            | -                | -                | -         |     2.70 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           21 |     3227 | 2024-04-03 | ex-Guild Eagles   | W   | 0.372      | -            | -                | -                | -         |     1.68 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           20 |     3236 | 2024-04-03 | Alliance          | W   | 0.371      | -            | -                | -                | -         |     2.17 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           19 |     3265 | 2024-04-02 | PARIVISION        | W   | 0.366      | -            | -                | -                | -         |     5.58 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           18 |     3266 | 2024-04-02 | ex-Guild Eagles   | L   | 0.365      | -            | -                | -                | -         |    -9.88 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           17 |     3277 | 2024-04-02 | ALTERNATE aTTaX   | W   | 0.364      | -            | -                | -                | -         |     3.39 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           16 |     3500 | 2024-03-18 | The MongolZ       | L   | 0.265      | -            | -                | -                | -         |    -0.09 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           15 |     3517 | 2024-03-17 | Apeks             | L   | 0.260      | -            | -                | -                | -         |    -6.39 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     3527 | 2024-03-17 | GamerLegion       | L   | 0.259      | -            | -                | -                | -         |    -7.20 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     3836 | 2024-03-05 | FORZE             | L   | 0.180      | -            | -                | -                | -         |    -4.49 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     3841 | 2024-03-05 | Zero Tenacity     | W   | 0.180      | -            | -                | -                | -         |     2.54 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     3937 | 2024-03-01 | BIG               | L   | 0.151      | -            | -                | -                | -         |    -1.35 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     3955 | 2024-02-28 | Young Ninjas      | L   | 0.139      | -            | -                | -                | -         |    -3.94 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     4218 | 2024-02-17 | 9 Pandas          | W   | 0.065      | -            | -                | -                | 1 (0.065) |     0.62 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     4247 | 2024-02-16 | Falcons           | W   | 0.058      | -            | -                | -                | 1 (0.058) |     1.50 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     4271 | 2024-02-15 | fnatic            | L   | 0.052      | -            | -                | -                | -         |    -0.14 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     4305 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.046      | -            | -                | -                | 1 (0.046) |     0.02 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     4309 | 2024-02-14 | Enterprise        | L   | 0.045      | -            | -                | -                | -         |    -1.11 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     4369 | 2024-02-10 | Sashi             | L   | 0.019      | -            | -                | -                | -         |    -0.28 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     4377 | 2024-02-09 | Nemiga            | L   | 0.013      | -            | -                | -                | -         |    -0.20 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     4394 | 2024-02-08 | RUBY              | W   | 0.007      | -            | -                | -                | -         |     0.05 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     4399 | 2024-02-08 | Insilio           | W   | 0.006      | -            | -                | -                | -         |     0.03 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($41,751.60)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-02 |      0.772 | $2,000.00      | $1,544.72       |
| 2024-05-23 |      0.705 | $12,500.00     | $8,815.97       |
| 2024-05-04 |      0.579 | $22,000.00     | $12,744.72      |
| 2024-05-02 |      0.566 | $1,500.00      | $848.96         |
| 2024-03-20 |      0.280 | $10,000.00     | $2,797.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
