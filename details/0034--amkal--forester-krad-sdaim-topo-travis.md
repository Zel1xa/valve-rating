### Roster Details<br />
Team Name: AMKAL<br />
Roster: Forester, Krad, Sdaim, topo, TRAVIS<br />
Global Rank: [34](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [25]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1168.8<br />
<br />
Final Rank Value (1168.8) = Starting Rank Value (1147.8) + Head To Head Adjustments (21.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.530[<sup>1</sup>](#table2)
- Bounty Collected: 0.444[<sup>2</sup>](#table1)
- Opponent Network: 0.238[<sup>2</sup>](#table1)
- LAN Wins: 0.252[<sup>2</sup>](#table1)

The average of these factors is 0.366<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1147.8
- 400 + ( ( 0.366 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1147.8


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
|           56 |       73 | 2024-08-01 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -28.96 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           55 |      130 | 2024-07-31 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -10.48 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           54 |      268 | 2024-07-27 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -1.84 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           53 |      300 | 2024-07-26 | DMS               | W   | 1.000      | 0.650        | -                | 0.446 (0.290)    | 1 (1.000) |     4.93 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           52 |      335 | 2024-07-25 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -2.79 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           51 |      360 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.266 (0.173)    | 1 (1.000) |     4.21 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           50 |      370 | 2024-07-24 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -9.70 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           49 |     1173 | 2024-06-09 | Monte             | W   | 0.832      | -            | -                | -                | 0 (0.000) |     7.20 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           48 |     1202 | 2024-06-09 | B8                | W   | 0.830      | 0.143        | 0.165 (0.020)    | 0.913 (0.108)    | 0 (0.000) |    10.77 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     1260 | 2024-06-08 | Monte             | W   | 0.824      | -            | -                | -                | 0 (0.000) |     7.00 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     1264 | 2024-06-08 | 1WIN              | W   | 0.824      | -            | -                | -                | 0 (0.000) |     5.81 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     1569 | 2024-06-01 | MOUZ NXT          | L   | 0.777      | -            | -                | -                | -         |   -15.63 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     1586 | 2024-05-31 | Permitta          | W   | 0.772      | 0.435        | -                | 0.876 (0.294)    | 0 (0.000) |     4.12 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     1835 | 2024-05-21 | GamerLegion       | L   | 0.705      | -            | -                | -                | -         |   -11.91 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     1902 | 2024-05-19 | paiN              | W   | 0.691      | 0.769        | 0.328 (0.174)    | 0.865 (0.459)    | -         |    16.09 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     1906 | 2024-05-19 | Liquid            | L   | 0.691      | -            | -                | -                | -         |    -3.18 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     1927 | 2024-05-18 | paiN              | W   | 0.685      | 0.769        | 0.328 (0.173)    | 0.865 (0.455)    | -         |    16.55 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2324 | 2024-05-04 | BetBoom           | W   | 0.591      | 0.435        | 0.252 (0.065)    | 0.543 (0.140)    | -         |    14.81 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     2334 | 2024-05-04 | Metizport         | W   | 0.590      | 0.435        | -                | 0.418 (0.107)    | -         |     4.54 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     2344 | 2024-05-03 | Gaimin Gladiators | W   | 0.584      | 0.435        | 0.038 (0.010)    | -                | -         |     5.45 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     2359 | 2024-05-02 | BLEED             | W   | 0.579      | 0.435        | 0.092 (0.023)    | -                | -         |     7.25 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     2392 | 2024-05-01 | fnatic            | L   | 0.571      | -            | -                | -                | -         |    -2.00 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     2410 | 2024-04-30 | Gaimin Gladiators | W   | 0.565      | -            | -                | -                | -         |     5.33 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     2435 | 2024-04-29 | Permitta          | W   | 0.557      | 0.384        | -                | 0.876 (0.188)    | -         |     4.57 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     2559 | 2024-04-24 | Nexus             | W   | 0.523      | -            | -                | -                | -         |     2.64 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     2606 | 2024-04-21 | Gaimin Gladiators | L   | 0.504      | -            | -                | -                | -         |   -10.33 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     2681 | 2024-04-19 | ENCE              | W   | 0.491      | 0.384        | 0.170 (0.032)    | -                | -         |    12.87 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     2725 | 2024-04-18 | Apeks             | L   | 0.485      | -            | -                | -                | -         |   -11.67 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     2734 | 2024-04-18 | ex-Guild Eagles   | W   | 0.484      | -            | -                | -                | -         |     2.28 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           27 |     2809 | 2024-04-16 | B8                | W   | 0.470      | 0.384        | 0.165 (0.030)    | 0.913 (0.165)    | -         |     5.47 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           26 |     2861 | 2024-04-12 | Aurora            | L   | 0.445      | -            | -                | -                | -         |    -0.81 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           25 |     2898 | 2024-04-11 | BetBoom           | W   | 0.437      | 0.143        | 0.252 (0.016)    | -                | -         |    11.47 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           24 |     2930 | 2024-04-10 | Apeks             | W   | 0.432      | -            | -                | -                | -         |     3.47 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           23 |     2944 | 2024-04-10 | Enterprise        | L   | 0.430      | -            | -                | -                | -         |   -10.42 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           22 |     3153 | 2024-04-03 | Insilio           | W   | 0.385      | -            | -                | -                | -         |     2.75 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           21 |     3164 | 2024-04-03 | ex-Guild Eagles   | W   | 0.384      | -            | -                | -                | -         |     1.76 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           20 |     3173 | 2024-04-03 | Alliance          | W   | 0.383      | -            | -                | -                | -         |     2.23 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           19 |     3202 | 2024-04-02 | PARIVISION        | W   | 0.378      | -            | -                | -                | -         |     5.66 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           18 |     3203 | 2024-04-02 | ex-Guild Eagles   | L   | 0.378      | -            | -                | -                | -         |   -10.19 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           17 |     3214 | 2024-04-02 | ALTERNATE aTTaX   | W   | 0.376      | -            | -                | -                | -         |     3.50 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           16 |     3437 | 2024-03-18 | The MongolZ       | L   | 0.277      | -            | -                | -                | -         |    -0.09 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           15 |     3454 | 2024-03-17 | Apeks             | L   | 0.272      | -            | -                | -                | -         |    -6.64 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     3464 | 2024-03-17 | GamerLegion       | L   | 0.271      | -            | -                | -                | -         |    -7.49 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     3772 | 2024-03-05 | FORZE             | L   | 0.192      | -            | -                | -                | -         |    -4.79 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     3777 | 2024-03-05 | Zero Tenacity     | W   | 0.192      | -            | -                | -                | -         |     2.66 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     3873 | 2024-03-01 | BIG               | L   | 0.163      | -            | -                | -                | -         |    -1.45 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     3891 | 2024-02-28 | Young Ninjas      | L   | 0.151      | -            | -                | -                | -         |    -4.30 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     4153 | 2024-02-17 | 9 Pandas          | W   | 0.077      | -            | -                | -                | 1 (0.077) |     0.74 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     4182 | 2024-02-16 | Falcons           | W   | 0.070      | -            | -                | -                | 1 (0.070) |     1.82 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     4206 | 2024-02-15 | fnatic            | L   | 0.064      | -            | -                | -                | -         |    -0.18 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     4240 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.058      | -            | -                | -                | 1 (0.058) |     0.03 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     4244 | 2024-02-14 | Enterprise        | L   | 0.057      | -            | -                | -                | -         |    -1.41 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     4304 | 2024-02-10 | Sashi             | L   | 0.031      | -            | -                | -                | -         |    -0.47 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     4312 | 2024-02-09 | Nemiga            | L   | 0.025      | -            | -                | -                | -         |    -0.40 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     4329 | 2024-02-08 | RUBY              | W   | 0.019      | -            | -                | -                | -         |     0.14 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     4334 | 2024-02-08 | Insilio           | W   | 0.018      | -            | -                | -                | -         |     0.11 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($42,331.60)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-02 |      0.784 | $2,000.00      | $1,568.89       |
| 2024-05-23 |      0.717 | $12,500.00     | $8,967.01       |
| 2024-05-04 |      0.591 | $22,000.00     | $13,010.56      |
| 2024-05-02 |      0.578 | $1,500.00      | $867.08         |
| 2024-03-20 |      0.292 | $10,000.00     | $2,918.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
