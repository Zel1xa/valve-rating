### Roster Details<br />
Team Name: AMKAL<br />
Roster: Forester, Krad, Sdaim, topo, TRAVIS<br />
Global Rank: [31](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [23]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1208.0<br />
<br />
Final Rank Value (1208.0) = Starting Rank Value (1158.3) + Head To Head Adjustments (49.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.531[<sup>1</sup>](#table2)
- Bounty Collected: 0.448[<sup>2</sup>](#table1)
- Opponent Network: 0.232[<sup>2</sup>](#table1)
- LAN Wins: 0.261[<sup>2</sup>](#table1)

The average of these factors is 0.368<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1158.3
- 400 + ( ( 0.368 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1158.3


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
|           55 |       16 | 2024-07-31 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -10.53 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           54 |      154 | 2024-07-27 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -1.85 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           53 |      186 | 2024-07-26 | DMS               | W   | 1.000      | 0.650        | -                | 0.447 (0.291)    | 1 (1.000) |     4.80 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           52 |      221 | 2024-07-25 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -2.64 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           51 |      246 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | 0.027 (0.017)    | 0.262 (0.170)    | 1 (1.000) |     4.07 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           50 |      256 | 2024-07-24 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -9.94 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           49 |     1060 | 2024-06-09 | Monte             | W   | 0.853      | -            | -                | -                | 0 (0.000) |     7.29 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           48 |     1089 | 2024-06-09 | B8                | W   | 0.851      | 0.143        | 0.167 (0.020)    | 0.879 (0.107)    | 0 (0.000) |    10.91 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     1147 | 2024-06-08 | Monte             | W   | 0.845      | -            | -                | -                | 0 (0.000) |     7.09 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     1151 | 2024-06-08 | 1WIN              | W   | 0.845      | -            | -                | -                | 0 (0.000) |     5.77 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     1456 | 2024-06-01 | MOUZ NXT          | L   | 0.798      | -            | -                | -                | -         |   -16.25 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     1473 | 2024-05-31 | Permitta          | W   | 0.793      | 0.435        | -                | 0.799 (0.275)    | 0 (0.000) |     3.92 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     1722 | 2024-05-21 | GamerLegion       | L   | 0.726      | -            | -                | -                | -         |   -12.15 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     1789 | 2024-05-19 | paiN              | W   | 0.712      | 0.769        | 0.333 (0.182)    | 0.797 (0.436)    | -         |    16.64 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     1793 | 2024-05-19 | Liquid            | L   | 0.711      | -            | -                | -                | -         |    -3.73 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     1814 | 2024-05-18 | paiN              | W   | 0.706      | 0.769        | 0.333 (0.181)    | 0.797 (0.432)    | -         |    17.12 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2211 | 2024-05-04 | BetBoom           | W   | 0.612      | 0.435        | 0.256 (0.068)    | 0.554 (0.147)    | -         |    15.45 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     2221 | 2024-05-04 | Metizport         | W   | 0.610      | 0.435        | -                | 0.427 (0.113)    | -         |     4.69 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     2231 | 2024-05-03 | Gaimin Gladiators | W   | 0.605      | 0.435        | 0.040 (0.010)    | -                | -         |     5.78 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     2246 | 2024-05-02 | BLEED             | W   | 0.599      | 0.435        | 0.095 (0.025)    | -                | -         |     7.55 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     2279 | 2024-05-01 | fnatic            | L   | 0.592      | -            | -                | -                | -         |    -1.95 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     2297 | 2024-04-30 | Gaimin Gladiators | W   | 0.586      | -            | -                | -                | -         |     5.71 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     2322 | 2024-04-29 | Permitta          | W   | 0.578      | 0.384        | -                | 0.799 (0.178)    | -         |     4.43 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     2447 | 2024-04-24 | Nexus             | W   | 0.544      | -            | -                | -                | -         |     2.69 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     2494 | 2024-04-21 | Gaimin Gladiators | L   | 0.525      | -            | -                | -                | -         |   -10.51 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     2569 | 2024-04-19 | ENCE              | W   | 0.512      | 0.384        | 0.173 (0.034)    | -                | -         |    13.55 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     2613 | 2024-04-18 | Apeks             | L   | 0.505      | -            | -                | -                | -         |   -11.99 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     2622 | 2024-04-18 | ex-Guild Eagles   | W   | 0.504      | -            | -                | -                | -         |     2.41 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           27 |     2697 | 2024-04-16 | B8                | W   | 0.490      | 0.384        | 0.167 (0.031)    | 0.879 (0.166)    | -         |     5.70 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           26 |     2749 | 2024-04-12 | Aurora            | L   | 0.466      | -            | -                | -                | -         |    -0.82 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           25 |     2786 | 2024-04-11 | BetBoom           | W   | 0.458      | 0.143        | 0.256 (0.017)    | -                | -         |    12.13 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           24 |     2818 | 2024-04-10 | Apeks             | W   | 0.453      | -            | -                | -                | -         |     3.82 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           23 |     2832 | 2024-04-10 | Enterprise        | L   | 0.450      | -            | -                | -                | -         |   -10.95 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           22 |     3041 | 2024-04-03 | Insilio           | W   | 0.406      | -            | -                | -                | -         |     2.88 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           21 |     3052 | 2024-04-03 | ex-Guild Eagles   | W   | 0.405      | -            | -                | -                | -         |     1.88 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           20 |     3061 | 2024-04-03 | Alliance          | W   | 0.404      | -            | -                | -                | -         |     2.28 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           19 |     3090 | 2024-04-02 | PARIVISION        | W   | 0.399      | -            | -                | -                | -         |     5.75 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           18 |     3091 | 2024-04-02 | ex-Guild Eagles   | L   | 0.398      | -            | -                | -                | -         |   -10.73 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           17 |     3102 | 2024-04-02 | ALTERNATE aTTaX   | W   | 0.397      | -            | -                | -                | -         |     3.69 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           16 |     3325 | 2024-03-18 | The MongolZ       | L   | 0.298      | -            | -                | -                | -         |    -0.10 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           15 |     3342 | 2024-03-17 | Apeks             | L   | 0.293      | -            | -                | -                | -         |    -7.04 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     3352 | 2024-03-17 | GamerLegion       | L   | 0.292      | -            | -                | -                | -         |    -8.01 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     3661 | 2024-03-05 | FORZE             | L   | 0.213      | -            | -                | -                | -         |    -5.28 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     3666 | 2024-03-05 | Zero Tenacity     | W   | 0.212      | -            | -                | -                | -         |     2.91 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     3762 | 2024-03-01 | BIG               | L   | 0.184      | -            | -                | -                | -         |    -2.13 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     3780 | 2024-02-28 | Young Ninjas      | L   | 0.172      | -            | -                | -                | -         |    -4.89 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     4043 | 2024-02-17 | 9 Pandas          | W   | 0.097      | -            | -                | -                | 1 (0.097) |     0.94 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     4072 | 2024-02-16 | Falcons           | W   | 0.091      | -            | -                | -                | 1 (0.091) |     2.41 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     4096 | 2024-02-15 | fnatic            | L   | 0.084      | -            | -                | -                | -         |    -0.22 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     4130 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.079      | -            | -                | -                | 1 (0.079) |     0.04 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     4134 | 2024-02-14 | Enterprise        | L   | 0.078      | -            | -                | -                | -         |    -1.93 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     4194 | 2024-02-10 | Sashi             | L   | 0.052      | -            | -                | -                | -         |    -0.78 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     4202 | 2024-02-09 | Nemiga            | L   | 0.046      | -            | -                | -                | -         |    -0.71 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     4219 | 2024-02-08 | RUBY              | W   | 0.039      | -            | -                | -                | -         |     0.28 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     4224 | 2024-02-08 | Insilio           | W   | 0.038      | -            | -                | -                | -         |     0.23 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($43,326.49)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-02 |      0.805 | $2,000.00      | $1,610.34       |
| 2024-05-23 |      0.738 | $12,500.00     | $9,226.10       |
| 2024-05-04 |      0.612 | $22,000.00     | $13,466.55      |
| 2024-05-02 |      0.599 | $1,500.00      | $898.17         |
| 2024-03-20 |      0.313 | $10,000.00     | $3,125.32       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
