### Roster Details<br />
Team Name: AMKAL<br />
Roster: Forester, Krad, Sdaim, topo, TRAVIS<br />
Global Rank: [31](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [23]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1197.8<br />
<br />
Final Rank Value (1197.8) = Starting Rank Value (1154.1) + Head To Head Adjustments (43.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.532[<sup>1</sup>](#table2)
- Bounty Collected: 0.442[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
- LAN Wins: 0.260[<sup>2</sup>](#table1)

The average of these factors is 0.366<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1154.1
- 400 + ( ( 0.366 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1154.1


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
|           55 |       43 | 2024-07-31 | BLEED             | L   | 1.000      | -            | -                | -                | -         |   -10.19 | Forester, Krad, Sdaim, topo, TRAVIS     |
|           54 |      183 | 2024-07-27 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -1.85 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           53 |      215 | 2024-07-26 | DMS               | W   | 1.000      | 0.650        | -                | 0.447 (0.291)    | 1 (1.000) |     4.56 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           52 |      250 | 2024-07-25 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -2.70 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           51 |      275 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | 0.027 (0.018)    | 0.263 (0.171)    | 1 (1.000) |     3.73 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           50 |      285 | 2024-07-24 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -9.78 | Forester, Krad, Sdaim, shady, TRAVIS    |
|           49 |     1097 | 2024-06-09 | Monte             | W   | 0.848      | -            | -                | -                | 0 (0.000) |     7.25 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           48 |     1126 | 2024-06-09 | B8                | W   | 0.847      | 0.143        | 0.168 (0.020)    | 0.878 (0.106)    | 0 (0.000) |    10.62 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     1186 | 2024-06-08 | Monte             | W   | 0.841      | -            | -                | -                | 0 (0.000) |     7.00 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     1190 | 2024-06-08 | 1WIN              | W   | 0.840      | -            | -                | -                | 0 (0.000) |     6.03 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     1508 | 2024-06-01 | MOUZ NXT          | L   | 0.793      | -            | -                | -                | -         |   -15.95 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     1525 | 2024-05-31 | Permitta          | W   | 0.788      | 0.435        | -                | 0.801 (0.275)    | 0 (0.000) |     4.17 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     1790 | 2024-05-21 | GamerLegion       | L   | 0.722      | -            | -                | -                | -         |   -12.07 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     1868 | 2024-05-19 | paiN              | W   | 0.708      | 0.769        | 0.300 (0.163)    | 0.801 (0.436)    | -         |    14.85 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     1872 | 2024-05-19 | Liquid            | L   | 0.707      | -            | -                | -                | -         |    -3.95 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     1893 | 2024-05-18 | paiN              | W   | 0.701      | 0.769        | 0.300 (0.162)    | 0.801 (0.432)    | -         |    15.33 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2302 | 2024-05-04 | BetBoom           | W   | 0.608      | 0.435        | 0.257 (0.068)    | 0.551 (0.146)    | -         |    15.29 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     2312 | 2024-05-04 | Metizport         | W   | 0.606      | 0.435        | -                | 0.425 (0.112)    | -         |     4.67 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     2322 | 2024-05-03 | Gaimin Gladiators | W   | 0.601      | 0.435        | 0.040 (0.010)    | -                | -         |     5.86 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     2337 | 2024-05-02 | BLEED             | W   | 0.595      | 0.435        | 0.095 (0.025)    | -                | -         |     7.35 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     2372 | 2024-05-01 | fnatic            | L   | 0.587      | -            | -                | -                | -         |    -4.53 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     2391 | 2024-04-30 | Gaimin Gladiators | W   | 0.581      | -            | -                | -                | -         |     5.71 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     2416 | 2024-04-29 | Permitta          | W   | 0.574      | 0.384        | -                | 0.801 (0.177)    | -         |     4.59 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     2541 | 2024-04-24 | Nexus             | W   | 0.539      | -            | -                | -                | -         |     2.73 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     2592 | 2024-04-21 | Gaimin Gladiators | L   | 0.521      | -            | -                | -                | -         |   -10.38 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     2670 | 2024-04-19 | ENCE              | W   | 0.507      | 0.384        | 0.174 (0.034)    | -                | -         |    13.37 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     2715 | 2024-04-18 | Apeks             | L   | 0.501      | -            | -                | -                | -         |   -11.98 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     2724 | 2024-04-18 | ex-Guild Eagles   | W   | 0.500      | -            | -                | -                | -         |     2.41 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           27 |     2801 | 2024-04-16 | B8                | W   | 0.486      | 0.384        | 0.168 (0.031)    | 0.878 (0.164)    | -         |     5.73 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           26 |     2853 | 2024-04-12 | Aurora            | L   | 0.462      | -            | -                | -                | -         |    -0.82 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           25 |     2891 | 2024-04-11 | BetBoom           | W   | 0.453      | 0.143        | 0.257 (0.017)    | -                | -         |    11.97 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           24 |     2923 | 2024-04-10 | Apeks             | W   | 0.448      | -            | -                | -                | -         |     3.69 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           23 |     2937 | 2024-04-10 | Enterprise        | L   | 0.446      | -            | -                | -                | -         |   -10.78 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           22 |     3148 | 2024-04-03 | Insilio           | W   | 0.402      | -            | -                | -                | -         |     2.90 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           21 |     3159 | 2024-04-03 | ex-Guild Eagles   | W   | 0.401      | -            | -                | -                | -         |     1.88 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           20 |     3172 | 2024-04-03 | Alliance          | W   | 0.400      | -            | -                | -                | -         |     2.34 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           19 |     3203 | 2024-04-02 | PARIVISION        | W   | 0.394      | -            | -                | -                | -         |     5.82 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           18 |     3204 | 2024-04-02 | ex-Guild Eagles   | L   | 0.394      | -            | -                | -                | -         |   -10.59 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           17 |     3215 | 2024-04-02 | ALTERNATE aTTaX   | W   | 0.393      | -            | -                | -                | -         |     3.65 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           16 |     3443 | 2024-03-18 | The MongolZ       | L   | 0.294      | -            | -                | -                | -         |    -0.10 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           15 |     3460 | 2024-03-17 | Apeks             | L   | 0.289      | -            | -                | -                | -         |    -6.96 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     3470 | 2024-03-17 | GamerLegion       | L   | 0.288      | -            | -                | -                | -         |    -7.89 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     3785 | 2024-03-05 | FORZE             | L   | 0.209      | -            | -                | -                | -         |    -5.15 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     3795 | 2024-03-05 | Zero Tenacity     | W   | 0.208      | -            | -                | -                | -         |     2.84 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     3892 | 2024-03-01 | BIG               | L   | 0.179      | -            | -                | -                | -         |    -2.16 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     3911 | 2024-02-28 | Young Ninjas      | L   | 0.168      | -            | -                | -                | -         |    -4.76 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     4181 | 2024-02-17 | 9 Pandas          | W   | 0.093      | -            | -                | -                | 1 (0.093) |     0.90 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     4211 | 2024-02-16 | Falcons           | W   | 0.086      | -            | -                | -                | 1 (0.086) |     2.28 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     4235 | 2024-02-15 | fnatic            | L   | 0.080      | -            | -                | -                | -         |    -0.56 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     4269 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.074      | -            | -                | -                | 1 (0.074) |     0.03 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     4273 | 2024-02-14 | Enterprise        | L   | 0.074      | -            | -                | -                | -         |    -1.81 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     4342 | 2024-02-10 | Sashi             | L   | 0.047      | -            | -                | -                | -         |    -0.71 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     4350 | 2024-02-09 | Nemiga            | L   | 0.042      | -            | -                | -                | -         |    -0.64 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     4368 | 2024-02-08 | RUBY              | W   | 0.035      | -            | -                | -                | -         |     0.26 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     4373 | 2024-02-08 | Insilio           | W   | 0.034      | -            | -                | -                | -         |     0.20 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($43,118.26)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-06-02 |      0.801 | $2,000.00      | $1,601.67       |
| 2024-05-23 |      0.734 | $12,500.00     | $9,171.88       |
| 2024-05-04 |      0.608 | $22,000.00     | $13,371.11      |
| 2024-05-02 |      0.594 | $1,500.00      | $891.67         |
| 2024-03-20 |      0.308 | $10,000.00     | $3,081.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
