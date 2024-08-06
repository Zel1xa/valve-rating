### Roster Details<br />
Team Name: fnatic<br />
Roster: afro, blameF, bodyy, KRIMZ, MATYS<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1404.2<br />
<br />
Final Rank Value (1404.2) = Starting Rank Value (1557.4) + Head To Head Adjustments (-153.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.699[<sup>1</sup>](#table2)
- Bounty Collected: 0.548[<sup>2</sup>](#table1)
- Opponent Network: 0.369[<sup>2</sup>](#table1)
- LAN Wins: 0.639[<sup>2</sup>](#table1)

The average of these factors is 0.564<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1557.4
- 400 + ( ( 0.564 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1557.4


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
|           63 |       64 | 2024-08-03 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -14.15 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           62 |      115 | 2024-08-02 | Nemiga            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.93 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           61 |      145 | 2024-08-01 | G2 Ares           | W   | 1.000      | -            | -                | -                | -         |     0.11 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           60 |      210 | 2024-07-31 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -24.29 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           59 |      302 | 2024-07-28 | Sangal            | L   | 1.000      | -            | -                | -                | -         |   -23.64 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           58 |      314 | 2024-07-28 | SAW               | W   | 1.000      | 0.435        | -                | 0.528 (0.230)    | -         |     5.74 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           57 |      330 | 2024-07-27 | MOUZ NXT          | W   | 1.000      | 0.435        | -                | 0.984 (0.428)    | -         |     4.17 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           56 |      364 | 2024-07-26 | Sampi             | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     1.39 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           55 |      494 | 2024-07-22 | Passion UA        | W   | 1.000      | 0.500        | 0.173 (0.087)    | 1.000 (0.500)    | -         |     4.46 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           54 |      525 | 2024-07-21 | MOUZ NXT          | W   | 1.000      | 0.500        | 0.139 (0.069)    | 0.984 (0.492)    | -         |     4.28 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           53 |      569 | 2024-07-20 | Sangal            | W   | 1.000      | 0.500        | 0.219 (0.109)    | 0.865 (0.432)    | -         |     7.01 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           52 |      590 | 2024-07-19 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.56 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           51 |      642 | 2024-07-18 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -27.16 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           50 |      767 | 2024-07-16 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.27 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           49 |     1019 | 2024-06-16 | 9z                | L   | 0.864      | -            | -                | -                | -         |   -13.54 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           48 |     1023 | 2024-06-16 | Ninjas in Pyjamas | W   | 0.863      | 0.548        | 0.254 (0.120)    | 0.543 (0.257)    | 1 (0.863) |    18.95 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           47 |     1047 | 2024-06-15 | RED Canids        | W   | 0.857      | 0.548        | -                | 0.748 (0.352)    | 1 (0.857) |     4.38 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           46 |     1061 | 2024-06-15 | Imperial          | W   | 0.855      | 0.548        | 0.233 (0.109)    | 0.673 (0.316)    | 1 (0.855) |     7.29 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           45 |     1086 | 2024-06-14 | RED Canids        | L   | 0.850      | -            | -                | -                | -         |   -22.41 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           44 |     1369 | 2024-06-07 | Ninjas in Pyjamas | L   | 0.802      | -            | -                | -                | -         |    -8.45 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           43 |     1425 | 2024-06-06 | BIG               | W   | 0.796      | 0.715        | 0.154 (0.088)    | -                | 1 (0.796) |     7.50 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           42 |     1451 | 2024-06-06 | FURIA             | L   | 0.794      | -            | -                | -                | -         |    -8.63 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           41 |     1466 | 2024-06-06 | Complexity        | W   | 0.793      | 0.715        | 0.341 (0.194)    | -                | 1 (0.793) |    18.84 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           40 |     1496 | 2024-06-05 | Eternal Fire      | W   | 0.789      | 0.715        | 0.739 (0.417)    | 0.448 (0.253)    | 1 (0.789) |    19.33 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           39 |     1512 | 2024-06-05 | BetBoom           | L   | 0.787      | -            | -                | -                | -         |   -14.96 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           38 |     1602 | 2024-06-02 | DMS               | L   | 0.767      | -            | -                | -                | -         |   -22.60 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           37 |     1667 | 2024-05-31 | SAW               | W   | 0.755      | -            | -                | -                | -         |     4.36 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           36 |     1668 | 2024-05-31 | Sangal            | W   | 0.754      | -            | -                | -                | -         |     3.21 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           35 |     2004 | 2024-05-18 | ENCE              | L   | 0.668      | -            | -                | -                | -         |   -12.87 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           34 |     2012 | 2024-05-18 | GamerLegion       | L   | 0.667      | -            | -                | -                | -         |   -18.18 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           33 |     2038 | 2024-05-17 | ENCE              | W   | 0.661      | 0.769        | 0.173 (0.088)    | -                | -         |     7.57 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           32 |     2404 | 2024-05-03 | 9 Pandas          | L   | 0.569      | -            | -                | -                | -         |   -17.00 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           31 |     2432 | 2024-05-02 | Sashi             | L   | 0.562      | -            | -                | -                | -         |   -15.10 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           30 |     2460 | 2024-05-01 | AMKAL             | W   | 0.555      | -            | -                | -                | -         |     1.93 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           29 |     2473 | 2024-05-01 | PARIVISION        | W   | 0.553      | -            | -                | -                | -         |     1.51 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           28 |     2496 | 2024-04-30 | Nexus             | W   | 0.546      | -            | -                | -                | -         |     0.36 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           27 |     2555 | 2024-04-27 | Virtus.pro        | L   | 0.527      | -            | -                | -                | -         |    -4.99 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           26 |     2596 | 2024-04-25 | Eternal Fire      | L   | 0.516      | -            | -                | -                | -         |    -4.59 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           25 |     2620 | 2024-04-24 | 3DMAX             | L   | 0.508      | -            | -                | -                | -         |    -5.81 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           24 |     2644 | 2024-04-23 | Virtus.pro        | W   | 0.500      | 0.889        | 0.498 (0.222)    | -                | 1 (0.500) |    11.22 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           23 |     2795 | 2024-04-18 | KOI               | L   | 0.468      | -            | -                | -                | -         |   -13.70 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           22 |     3049 | 2024-04-09 | Apeks             | L   | 0.409      | -            | -                | -                | -         |   -12.52 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           21 |     3083 | 2024-04-08 | Apeks             | W   | 0.402      | -            | -                | -                | -         |     0.34 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           20 |     3089 | 2024-04-08 | KOI               | W   | 0.401      | -            | -                | -                | -         |     0.83 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           19 |     3422 | 2024-03-23 | BetBoom           | L   | 0.294      | -            | -                | -                | -         |    -6.39 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           18 |     3458 | 2024-03-21 | 3DMAX             | W   | 0.281      | -            | -                | -                | -         |     5.86 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           17 |     3812 | 2024-03-06 | BLEED             | W   | 0.182      | -            | -                | -                | -         |     0.22 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           16 |     3855 | 2024-03-05 | Young Ninjas      | W   | 0.175      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           15 |     3872 | 2024-03-04 | 3DMAX             | W   | 0.168      | -            | -                | -                | -         |     3.63 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           14 |     3889 | 2024-03-03 | Gaimin Gladiators | L   | 0.162      | -            | -                | -                | -         |    -4.92 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           13 |     3894 | 2024-03-03 | AURA              | W   | 0.162      | -            | -                | -                | -         |     0.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           12 |     3904 | 2024-03-03 | ex-Preasy         | W   | 0.161      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           11 |     3941 | 2024-03-01 | ALTERNATE aTTaX   | W   | 0.147      | -            | -                | -                | -         |     0.19 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           10 |     3957 | 2024-02-28 | ex-Preasy         | L   | 0.136      | -            | -                | -                | -         |    -4.22 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            9 |     4073 | 2024-02-23 | GamerLegion       | L   | 0.101      | -            | -                | -                | -         |    -3.16 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            8 |     4218 | 2024-02-17 | SAW               | L   | 0.061      | -            | -                | -                | -         |    -1.74 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            7 |     4254 | 2024-02-16 | KOI               | L   | 0.054      | -            | -                | -                | -         |    -1.58 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            6 |     4277 | 2024-02-15 | AMKAL             | W   | 0.047      | -            | -                | -                | 1 (0.047) |     0.14 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            5 |     4304 | 2024-02-14 | Virtus.pro        | L   | 0.043      | -            | -                | -                | -         |    -0.42 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            4 |     4314 | 2024-02-14 | BetBoom           | W   | 0.041      | -            | -                | -                | 1 (0.041) |     0.41 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            3 |     4385 | 2024-02-09 | 3DMAX             | L   | 0.009      | -            | -                | -                | -         |    -0.09 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            2 |     4388 | 2024-02-09 | ex-Sprout         | L   | 0.008      | -            | -                | -                | -         |    -0.25 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            1 |     4392 | 2024-02-09 | Endpoint          | W   | 0.007      | -            | -                | -                | -         |     0.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($118,803.89)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.37) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-07-22 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-06-16 |      0.864 | $30,000.00     | $25,913.89      |
| 2024-06-09 |      0.815 | $20,000.00     | $16,294.44      |
| 2024-05-12 |      0.628 | $7,000.00      | $4,396.39       |
| 2024-05-04 |      0.575 | $2,000.00      | $1,150.00       |
| 2024-05-02 |      0.562 | $3,500.00      | $1,965.83       |
| 2024-03-06 |      0.182 | $50,000.00     | $9,083.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
