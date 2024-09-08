### Roster Details<br />
Team Name: BetBoom<br />
Roster: KaiR0N-, Magnojez, nafany, s1ren, zorte<br />
Global Rank: [24](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1244.3<br />
<br />
Final Rank Value (1244.3) = Starting Rank Value (1224.9) + Head To Head Adjustments (19.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.610[<sup>1</sup>](#table2)
- Bounty Collected: 0.504[<sup>2</sup>](#table1)
- Opponent Network: 0.262[<sup>2</sup>](#table1)
- LAN Wins: 0.329[<sup>2</sup>](#table1)

The average of these factors is 0.426<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1224.9
- 400 + ( ( 0.426 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 1224.9


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
|           61 |       49 | 2024-09-06 | Cloud9            | L   | 1.000      | -            | -                | -                | -         |   -20.95 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           60 |       57 | 2024-09-06 | CYBERSHOKE        | L   | 1.000      | -            | -                | -                | -         |   -26.25 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           59 |       88 | 2024-09-05 | Gaimin Gladiators | W   | 1.000      | 0.384        | -                | 0.495 (0.190)    | 0 (0.000) |     4.40 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           58 |      180 | 2024-09-02 | Monte             | W   | 1.000      | 0.384        | -                | 0.697 (0.268)    | 0 (0.000) |     6.91 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           57 |      452 | 2024-08-26 | LEON              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.85 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           56 |      514 | 2024-08-25 | Falcons           | L   | 1.000      | -            | -                | -                | -         |    -7.53 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           55 |      529 | 2024-08-24 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -5.50 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           54 |      740 | 2024-08-18 | SINNERS           | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     7.26 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           53 |      744 | 2024-08-18 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.723 (0.314)    | -         |     4.89 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           52 |      759 | 2024-08-17 | Young Ninjas      | W   | 1.000      | 0.435        | -                | 0.423 (0.184)    | -         |     3.56 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           51 |      789 | 2024-08-16 | DMS               | W   | 1.000      | 0.435        | -                | 0.486 (0.211)    | -         |     2.69 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           50 |     2523 | 2024-06-07 | Astralis          | L   | 0.580      | -            | -                | -                | -         |    -3.38 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           49 |     2578 | 2024-06-06 | Eternal Fire      | W   | 0.574      | 0.715        | 0.972 (0.399)    | 0.700 (0.288)    | 1 (0.574) |    17.20 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           48 |     2589 | 2024-06-06 | Complexity        | W   | 0.573      | 0.715        | 0.337 (0.138)    | -                | 1 (0.573) |    14.87 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           47 |     2623 | 2024-06-05 | BIG               | W   | 0.568      | 0.715        | 0.146 (0.059)    | -                | 1 (0.568) |     8.44 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           46 |     2638 | 2024-06-05 | FURIA             | L   | 0.567      | -            | -                | -                | -         |    -2.71 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           45 |     2647 | 2024-06-05 | fnatic            | W   | 0.567      | 0.715        | 0.294 (0.119)    | 0.679 (0.275)    | 1 (0.567) |    10.37 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           44 |     2930 | 2024-05-25 | B8                | L   | 0.494      | -            | -                | -                | -         |   -10.51 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           43 |     2955 | 2024-05-24 | DMS               | W   | 0.485      | -            | -                | -                | -         |     1.85 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           42 |     3045 | 2024-05-21 | Eternal Fire      | L   | 0.467      | -            | -                | -                | -         |    -0.48 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           41 |     3073 | 2024-05-20 | MIBR              | W   | 0.462      | 0.769        | 0.156 (0.055)    | 0.644 (0.229)    | -         |    10.33 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           40 |     3079 | 2024-05-20 | Astralis          | L   | 0.461      | -            | -                | -                | -         |    -2.11 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           39 |     3093 | 2024-05-20 | MIBR              | W   | 0.459      | 0.769        | 0.156 (0.055)    | 0.644 (0.227)    | -         |    10.51 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           38 |     3255 | 2024-05-15 | Falcons           | L   | 0.428      | -            | -                | -                | -         |    -2.36 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           37 |     3320 | 2024-05-14 | MOUZ              | L   | 0.420      | -            | -                | -                | -         |    -0.33 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           36 |     3362 | 2024-05-12 | B8                | L   | 0.408      | -            | -                | -                | -         |    -9.29 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           35 |     3366 | 2024-05-12 | 9 Pandas          | W   | 0.407      | -            | -                | -                | -         |     3.09 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           34 |     3399 | 2024-05-11 | Metizport         | W   | 0.400      | -            | -                | -                | -         |     1.73 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           33 |     3416 | 2024-05-10 | Enterprise        | W   | 0.393      | -            | -                | -                | -         |     1.45 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           32 |     3476 | 2024-05-07 | FlyQuest          | L   | 0.374      | -            | -                | -                | -         |    -8.64 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           31 |     3527 | 2024-05-04 | AMKAL             | L   | 0.354      | -            | -                | -                | -         |    -7.59 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           30 |     3532 | 2024-05-04 | 9 Pandas          | W   | 0.353      | -            | -                | -                | -         |     2.49 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           29 |     3555 | 2024-05-03 | Insilio           | W   | 0.345      | -            | -                | -                | -         |     1.52 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           28 |     3596 | 2024-05-01 | EYEBALLERS        | W   | 0.334      | -            | -                | -                | -         |     0.89 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           27 |     3626 | 2024-04-30 | 3DMAX             | L   | 0.326      | -            | -                | -                | -         |    -0.71 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           26 |     3700 | 2024-04-26 | M80               | W   | 0.302      | 0.889        | 0.169 (0.045)    | -                | 1 (0.302) |     3.09 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           25 |     3714 | 2024-04-26 | Falcons           | W   | 0.300      | 0.889        | 0.297 (0.079)    | -                | 1 (0.300) |     7.84 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           24 |     3737 | 2024-04-25 | Vitality          | L   | 0.294      | -            | -                | -                | -         |    -0.20 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           23 |     3769 | 2024-04-23 | M80               | W   | 0.281      | 0.889        | 0.169 (0.042)    | -                | 1 (0.281) |     2.91 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           22 |     3878 | 2024-04-19 | Cloud9            | L   | 0.255      | -            | -                | -                | -         |    -7.38 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           21 |     3889 | 2024-04-19 | Eternal Fire      | L   | 0.253      | -            | -                | -                | -         |    -0.22 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           20 |     3913 | 2024-04-18 | Apeks             | W   | 0.248      | -            | -                | -                | -         |     0.58 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           19 |     3917 | 2024-04-18 | Apogee            | W   | 0.248      | -            | -                | -                | -         |     0.50 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           18 |     3924 | 2024-04-18 | Partizan          | W   | 0.247      | -            | -                | -                | -         |     0.49 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           17 |     4043 | 2024-04-14 | 3DMAX             | W   | 0.220      | 0.358        | 0.509 (0.040)    | -                | -         |     6.50 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           16 |     4049 | 2024-04-13 | OG                | L   | 0.215      | -            | -                | -                | -         |    -5.50 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           15 |     4053 | 2024-04-13 | Aurora            | L   | 0.214      | -            | -                | -                | -         |    -1.83 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           14 |     4061 | 2024-04-13 | Sampi             | W   | 0.212      | -            | -                | -                | -         |     0.95 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           13 |     4088 | 2024-04-11 | Aurora            | L   | 0.202      | -            | -                | -                | -         |    -1.75 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           12 |     4096 | 2024-04-11 | Ninjas in Pyjamas | W   | 0.201      | -            | -                | -                | -         |     4.84 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           11 |     4102 | 2024-04-11 | AMKAL             | L   | 0.200      | -            | -                | -                | -         |    -4.30 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           10 |     4141 | 2024-04-10 | Aurora            | W   | 0.194      | -            | -                | -                | -         |     4.47 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|            9 |     4200 | 2024-04-09 | BIG               | W   | 0.187      | -            | -                | -                | -         |     2.74 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|            8 |     4272 | 2024-04-06 | Alliance          | W   | 0.167      | -            | -                | -                | -         |     0.52 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|            7 |     4286 | 2024-04-05 | BLEED             | W   | 0.161      | -            | -                | -                | -         |     0.54 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|            6 |     4322 | 2024-04-04 | Alliance          | W   | 0.155      | -            | -                | -                | -         |     0.50 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|            5 |     4335 | 2024-04-04 | BLEED             | W   | 0.153      | -            | -                | -                | -         |     0.51 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|            4 |     4505 | 2024-03-27 | FAVBET            | L   | 0.101      | -            | -                | -                | -         |    -2.94 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|            3 |     4543 | 2024-03-24 | FORZE             | L   | 0.079      | -            | -                | -                | -         |    -2.30 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|            2 |     4557 | 2024-03-23 | fnatic            | W   | 0.073      | -            | -                | -                | -         |     1.46 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|            1 |     4599 | 2024-03-21 | B8                | W   | 0.059      | -            | -                | -                | -         |     0.54 | KaiR0N-, Magnojez, nafany, s1ren, zorte |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($69,519.03)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.23) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-18 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-06-09 |      0.594 | $20,000.00     | $11,877.78      |
| 2024-05-26 |      0.501 | $2,000.00      | $1,001.67       |
| 2024-05-23 |      0.480 | $12,500.00     | $6,001.74       |
| 2024-05-12 |      0.408 | $10,000.00     | $4,077.08       |
| 2024-05-12 |      0.407 | $17,500.00     | $7,126.39       |
| 2024-05-04 |      0.354 | $10,000.00     | $3,541.67       |
| 2024-05-02 |      0.341 | $1,000.00      | $340.83         |
| 2024-04-14 |      0.220 | $52,500.00     | $11,571.88      |
| 2024-04-14 |      0.220 | $9,000.00      | $1,980.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
