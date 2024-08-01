### Roster Details<br />
Team Name: AMKAL<br />
Roster: Forester, Krad, Sdaim, topo, TRAVIS<br />
Global Rank: [31](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [23]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1197.3<br />
<br />
Final Rank Value (1197.3) = Starting Rank Value (1152.8) + Head To Head Adjustments (44.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.532[<sup>1</sup>](#table2)
- Bounty Collected: 0.442[<sup>2</sup>](#table1)
- Opponent Network: 0.230[<sup>2</sup>](#table1)
- LAN Wins: 0.260[<sup>2</sup>](#table1)

The average of these factors is 0.366<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1152.8
- 400 + ( ( 0.366 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1152.8


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
|           55 |       47 | 2024-07-31 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -10.21 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           54 |      187 | 2024-07-27 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -1.83 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           53 |      219 | 2024-07-26 | DMS               | W   | 1.000      | 0.650        | -                | 0.447 (0.291)    | 1 (1.000) |     4.55 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           52 |      254 | 2024-07-25 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -2.68 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           51 |      279 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.263 (0.171)    | 1 (1.000) |     3.73 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           50 |      289 | 2024-07-24 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -9.78 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           49 |     1101 | 2024-06-09 | Monte             | W   | 0.847      | -            | -                | -                | 0 (0.000) |     7.23 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           48 |     1130 | 2024-06-09 | B8                | W   | 0.845      | 0.143        | 0.168 (0.020)    | 0.878 (0.106)    | 0 (0.000) |    10.59 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     1190 | 2024-06-08 | Monte             | W   | 0.839      | -            | -                | -                | 0 (0.000) |     6.98 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     1194 | 2024-06-08 | 1WIN              | W   | 0.839      | -            | -                | -                | 0 (0.000) |     6.03 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     1512 | 2024-06-01 | MOUZ NXT          | L   | 0.792      | -            | -                | -                | -         |   -15.94 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     1529 | 2024-05-31 | Permitta          | W   | 0.787      | 0.435        | -                | 0.801 (0.274)    | 0 (0.000) |     4.16 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     1794 | 2024-05-21 | GamerLegion       | L   | 0.720      | -            | -                | -                | -         |   -12.08 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     1872 | 2024-05-19 | paiN              | W   | 0.706      | 0.769        | 0.300 (0.163)    | 0.801 (0.435)    | -         |    14.79 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     1876 | 2024-05-19 | Liquid            | L   | 0.706      | -            | -                | -                | -         |    -2.95 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     1897 | 2024-05-18 | paiN              | W   | 0.700      | 0.769        | 0.300 (0.161)    | 0.801 (0.431)    | -         |    15.29 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2306 | 2024-05-04 | BetBoom           | W   | 0.606      | 0.435        | 0.257 (0.068)    | 0.551 (0.145)    | -         |    15.26 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     2316 | 2024-05-04 | Metizport         | W   | 0.605      | 0.435        | -                | 0.425 (0.112)    | -         |     4.67 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     2326 | 2024-05-03 | Gaimin Gladiators | W   | 0.599      | 0.435        | 0.040 (0.010)    | -                | -         |     5.84 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     2341 | 2024-05-02 | BLEED             | W   | 0.594      | 0.435        | 0.095 (0.024)    | -                | -         |     7.33 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     2376 | 2024-05-01 | fnatic            | L   | 0.586      | -            | -                | -                | -         |    -4.53 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     2395 | 2024-04-30 | Gaimin Gladiators | W   | 0.580      | -            | -                | -                | -         |     5.69 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     2420 | 2024-04-29 | Permitta          | W   | 0.573      | 0.384        | -                | 0.801 (0.176)    | -         |     4.59 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     2545 | 2024-04-24 | Nexus             | W   | 0.538      | -            | -                | -                | -         |     2.73 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     2596 | 2024-04-21 | Gaimin Gladiators | L   | 0.519      | -            | -                | -                | -         |   -10.37 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     2674 | 2024-04-19 | ENCE              | W   | 0.506      | 0.384        | 0.174 (0.034)    | -                | -         |    13.32 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     2719 | 2024-04-18 | Apeks             | L   | 0.500      | -            | -                | -                | -         |   -11.95 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     2728 | 2024-04-18 | ex-Guild Eagles   | W   | 0.499      | -            | -                | -                | -         |     2.41 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           27 |     2805 | 2024-04-16 | B8                | W   | 0.485      | 0.384        | 0.168 (0.031)    | 0.878 (0.163)    | -         |     5.72 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           26 |     2857 | 2024-04-12 | Aurora            | L   | 0.460      | -            | -                | -                | -         |    -0.82 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           25 |     2895 | 2024-04-11 | BetBoom           | W   | 0.452      | 0.143        | 0.257 (0.017)    | -                | -         |    11.92 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           24 |     2927 | 2024-04-10 | Apeks             | W   | 0.447      | -            | -                | -                | -         |     3.68 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           23 |     2941 | 2024-04-10 | Enterprise        | L   | 0.445      | -            | -                | -                | -         |   -10.74 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           22 |     3152 | 2024-04-03 | Insilio           | W   | 0.400      | -            | -                | -                | -         |     2.89 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           21 |     3163 | 2024-04-03 | ex-Guild Eagles   | W   | 0.399      | -            | -                | -                | -         |     1.88 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           20 |     3176 | 2024-04-03 | Alliance          | W   | 0.398      | -            | -                | -                | -         |     2.33 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           19 |     3207 | 2024-04-02 | PARIVISION        | W   | 0.393      | -            | -                | -                | -         |     5.80 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           18 |     3208 | 2024-04-02 | ex-Guild Eagles   | L   | 0.393      | -            | -                | -                | -         |   -10.54 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           17 |     3219 | 2024-04-02 | ALTERNATE aTTaX   | W   | 0.391      | -            | -                | -                | -         |     3.64 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           16 |     3447 | 2024-03-18 | The MongolZ       | L   | 0.292      | -            | -                | -                | -         |    -0.10 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           15 |     3464 | 2024-03-17 | Apeks             | L   | 0.287      | -            | -                | -                | -         |    -6.92 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     3474 | 2024-03-17 | GamerLegion       | L   | 0.286      | -            | -                | -                | -         |    -7.86 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     3789 | 2024-03-05 | FORZE             | L   | 0.207      | -            | -                | -                | -         |    -5.12 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     3799 | 2024-03-05 | Zero Tenacity     | W   | 0.207      | -            | -                | -                | -         |     2.82 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     3896 | 2024-03-01 | BIG               | L   | 0.178      | -            | -                | -                | -         |    -2.15 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     3915 | 2024-02-28 | Young Ninjas      | L   | 0.166      | -            | -                | -                | -         |    -4.72 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     4185 | 2024-02-17 | 9 Pandas          | W   | 0.092      | -            | -                | -                | 1 (0.092) |     0.88 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     4215 | 2024-02-16 | Falcons           | W   | 0.085      | -            | -                | -                | 1 (0.085) |     2.24 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     4239 | 2024-02-15 | fnatic            | L   | 0.079      | -            | -                | -                | -         |    -0.55 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     4273 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.073      | -            | -                | -                | 1 (0.073) |     0.03 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     4277 | 2024-02-14 | Enterprise        | L   | 0.072      | -            | -                | -                | -         |    -1.78 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     4346 | 2024-02-10 | Sashi             | L   | 0.046      | -            | -                | -                | -         |    -0.69 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     4354 | 2024-02-09 | Nemiga            | L   | 0.040      | -            | -                | -                | -         |    -0.62 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     4372 | 2024-02-08 | RUBY              | W   | 0.034      | -            | -                | -                | -         |     0.25 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     4377 | 2024-02-08 | Insilio           | W   | 0.033      | -            | -                | -                | -         |     0.20 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($43,051.60)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-02 |      0.799 | $2,000.00      | $1,598.89       |
| 2024-05-23 |      0.732 | $12,500.00     | $9,154.51       |
| 2024-05-04 |      0.606 | $22,000.00     | $13,340.56      |
| 2024-05-02 |      0.593 | $1,500.00      | $889.58         |
| 2024-03-20 |      0.307 | $10,000.00     | $3,068.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
