### Roster Details<br />
Team Name: fnatic<br />
Roster: afro, blameF, bodyy, KRIMZ, MATYS<br />
Global Rank: [22](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1403.8<br />
<br />
Final Rank Value (1403.8) = Starting Rank Value (1559.5) + Head To Head Adjustments (-155.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.699[<sup>1</sup>](#table2)
- Bounty Collected: 0.549[<sup>2</sup>](#table1)
- Opponent Network: 0.374[<sup>2</sup>](#table1)
- LAN Wins: 0.643[<sup>2</sup>](#table1)

The average of these factors is 0.566<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1559.5
- 400 + ( ( 0.566 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1559.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           63 |       49 | 2024-08-03 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -14.31 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           62 |      100 | 2024-08-02 | Nemiga            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.91 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           61 |      131 | 2024-08-01 | G2 Ares           | W   | 1.000      | -            | -                | -                | -         |     0.11 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           60 |      196 | 2024-07-31 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -24.31 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           59 |      287 | 2024-07-28 | Sangal            | L   | 1.000      | -            | -                | -                | -         |   -23.70 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           58 |      299 | 2024-07-28 | SAW               | W   | 1.000      | 0.435        | -                | 0.537 (0.233)    | -         |     5.75 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           57 |      315 | 2024-07-27 | MOUZ NXT          | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     4.13 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           56 |      349 | 2024-07-26 | Sampi             | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     1.33 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           55 |      479 | 2024-07-22 | Passion UA        | W   | 1.000      | 0.500        | 0.173 (0.086)    | 1.000 (0.500)    | -         |     4.42 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           54 |      510 | 2024-07-21 | MOUZ NXT          | W   | 1.000      | 0.500        | 0.139 (0.069)    | 1.000 (0.500)    | -         |     4.25 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           53 |      554 | 2024-07-20 | Sangal            | W   | 1.000      | 0.500        | 0.219 (0.109)    | 0.877 (0.438)    | -         |     6.96 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           52 |      575 | 2024-07-19 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.55 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           51 |      627 | 2024-07-18 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -27.23 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           50 |      752 | 2024-07-16 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.26 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           49 |     1004 | 2024-06-16 | 9z                | L   | 0.870      | -            | -                | -                | -         |   -13.59 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           48 |     1008 | 2024-06-16 | Ninjas in Pyjamas | W   | 0.868      | 0.548        | 0.254 (0.121)    | 0.551 (0.262)    | 1 (0.868) |    19.08 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           47 |     1032 | 2024-06-15 | RED Canids        | W   | 0.863      | 0.548        | -                | 0.757 (0.358)    | 1 (0.863) |     4.45 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           46 |     1046 | 2024-06-15 | Imperial          | W   | 0.861      | 0.548        | 0.235 (0.111)    | 0.683 (0.322)    | 1 (0.861) |     7.42 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           45 |     1071 | 2024-06-14 | RED Canids        | L   | 0.856      | -            | -                | -                | -         |   -22.52 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           44 |     1354 | 2024-06-07 | Ninjas in Pyjamas | L   | 0.808      | -            | -                | -                | -         |    -8.51 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           43 |     1410 | 2024-06-06 | BIG               | W   | 0.802      | 0.715        | 0.155 (0.089)    | -                | 1 (0.802) |     7.59 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           42 |     1436 | 2024-06-06 | FURIA             | L   | 0.800      | -            | -                | -                | -         |    -8.71 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           41 |     1451 | 2024-06-06 | Complexity        | W   | 0.799      | 0.715        | 0.342 (0.195)    | -                | 1 (0.799) |    19.02 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           40 |     1481 | 2024-06-05 | Eternal Fire      | W   | 0.794      | 0.715        | 0.740 (0.421)    | 0.455 (0.259)    | 1 (0.794) |    19.49 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           39 |     1497 | 2024-06-05 | BetBoom           | L   | 0.793      | -            | -                | -                | -         |   -15.04 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           38 |     1587 | 2024-06-02 | DMS               | L   | 0.773      | -            | -                | -                | -         |   -22.77 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           37 |     1652 | 2024-05-31 | SAW               | W   | 0.760      | -            | -                | -                | -         |     4.46 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           36 |     1653 | 2024-05-31 | Sangal            | W   | 0.760      | -            | -                | -                | -         |     3.19 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           35 |     1989 | 2024-05-18 | ENCE              | L   | 0.673      | -            | -                | -                | -         |   -13.09 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           34 |     1997 | 2024-05-18 | GamerLegion       | L   | 0.672      | -            | -                | -                | -         |   -18.32 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           33 |     2023 | 2024-05-17 | ENCE              | W   | 0.667      | 0.769        | 0.168 (0.086)    | -                | -         |     7.51 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           32 |     2389 | 2024-05-03 | 9 Pandas          | L   | 0.575      | -            | -                | -                | -         |   -17.18 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           31 |     2417 | 2024-05-02 | Sashi             | L   | 0.568      | -            | -                | -                | -         |   -15.26 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           30 |     2445 | 2024-05-01 | AMKAL             | W   | 0.560      | -            | -                | -                | -         |     1.93 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           29 |     2458 | 2024-05-01 | PARIVISION        | W   | 0.559      | -            | -                | -                | -         |     1.49 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           28 |     2481 | 2024-04-30 | Nexus             | W   | 0.552      | -            | -                | -                | -         |     0.36 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           27 |     2540 | 2024-04-27 | Virtus.pro        | L   | 0.533      | -            | -                | -                | -         |    -5.02 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           26 |     2581 | 2024-04-25 | Eternal Fire      | L   | 0.521      | -            | -                | -                | -         |    -4.64 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           25 |     2605 | 2024-04-24 | 3DMAX             | L   | 0.514      | -            | -                | -                | -         |    -5.99 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           24 |     2629 | 2024-04-23 | Virtus.pro        | W   | 0.506      | 0.889        | 0.498 (0.224)    | -                | 1 (0.506) |    11.37 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           23 |     2780 | 2024-04-18 | KOI               | L   | 0.474      | -            | -                | -                | -         |   -13.86 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           22 |     3034 | 2024-04-09 | Apeks             | L   | 0.415      | -            | -                | -                | -         |   -12.70 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           21 |     3068 | 2024-04-08 | Apeks             | W   | 0.408      | -            | -                | -                | -         |     0.34 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           20 |     3074 | 2024-04-08 | KOI               | W   | 0.407      | -            | -                | -                | -         |     0.85 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           19 |     3407 | 2024-03-23 | BetBoom           | L   | 0.299      | -            | -                | -                | -         |    -6.50 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           18 |     3443 | 2024-03-21 | 3DMAX             | W   | 0.287      | -            | -                | -                | -         |     5.93 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           17 |     3797 | 2024-03-06 | BLEED             | W   | 0.188      | -            | -                | -                | -         |     0.22 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           16 |     3840 | 2024-03-05 | Young Ninjas      | W   | 0.181      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           15 |     3857 | 2024-03-04 | 3DMAX             | W   | 0.173      | -            | -                | -                | -         |     3.72 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           14 |     3874 | 2024-03-03 | Gaimin Gladiators | L   | 0.168      | -            | -                | -                | -         |    -5.09 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           13 |     3879 | 2024-03-03 | AURA              | W   | 0.168      | -            | -                | -                | -         |     0.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           12 |     3889 | 2024-03-03 | ex-Preasy         | W   | 0.167      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           11 |     3926 | 2024-03-01 | ALTERNATE aTTaX   | W   | 0.153      | -            | -                | -                | -         |     0.19 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           10 |     3942 | 2024-02-28 | ex-Preasy         | L   | 0.142      | -            | -                | -                | -         |    -4.41 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            9 |     4058 | 2024-02-23 | GamerLegion       | L   | 0.107      | -            | -                | -                | -         |    -3.34 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            8 |     4203 | 2024-02-17 | SAW               | L   | 0.067      | -            | -                | -                | -         |    -1.90 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            7 |     4239 | 2024-02-16 | KOI               | L   | 0.059      | -            | -                | -                | -         |    -1.75 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            6 |     4262 | 2024-02-15 | AMKAL             | W   | 0.053      | -            | -                | -                | 1 (0.053) |     0.15 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            5 |     4289 | 2024-02-14 | Virtus.pro        | L   | 0.048      | -            | -                | -                | -         |    -0.47 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            4 |     4299 | 2024-02-14 | BetBoom           | W   | 0.047      | -            | -                | -                | 1 (0.047) |     0.47 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            3 |     4370 | 2024-02-09 | 3DMAX             | L   | 0.015      | -            | -                | -                | -         |    -0.15 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            2 |     4373 | 2024-02-09 | ex-Sprout         | L   | 0.014      | -            | -                | -                | -         |    -0.44 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            1 |     4377 | 2024-02-09 | Endpoint          | W   | 0.013      | -            | -                | -                | -         |     0.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($119,460.14)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.37) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-07-22 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-06-16 |      0.870 | $30,000.00     | $26,088.89      |
| 2024-06-09 |      0.821 | $20,000.00     | $16,411.11      |
| 2024-05-12 |      0.634 | $7,000.00      | $4,437.22       |
| 2024-05-04 |      0.581 | $2,000.00      | $1,161.67       |
| 2024-05-02 |      0.568 | $3,500.00      | $1,986.25       |
| 2024-03-06 |      0.188 | $50,000.00     | $9,375.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
