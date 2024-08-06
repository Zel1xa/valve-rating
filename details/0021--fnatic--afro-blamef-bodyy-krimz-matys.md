### Roster Details<br />
Team Name: fnatic<br />
Roster: afro, blameF, bodyy, KRIMZ, MATYS<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1404.3<br />
<br />
Final Rank Value (1404.3) = Starting Rank Value (1556.4) + Head To Head Adjustments (-152.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.699[<sup>1</sup>](#table2)
- Bounty Collected: 0.548[<sup>2</sup>](#table1)
- Opponent Network: 0.363[<sup>2</sup>](#table1)
- LAN Wins: 0.639[<sup>2</sup>](#table1)

The average of these factors is 0.562<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1556.4
- 400 + ( ( 0.562 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1556.4


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
|           63 |       77 | 2024-08-03 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -14.11 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           62 |      128 | 2024-08-02 | Nemiga            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.96 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           61 |      158 | 2024-08-01 | G2 Ares           | W   | 1.000      | -            | -                | -                | -         |     0.11 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           60 |      223 | 2024-07-31 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -24.23 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           59 |      315 | 2024-07-28 | Sangal            | L   | 1.000      | -            | -                | -                | -         |   -23.56 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           58 |      327 | 2024-07-28 | SAW               | W   | 1.000      | 0.435        | -                | 0.516 (0.224)    | -         |     5.74 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           57 |      343 | 2024-07-27 | MOUZ NXT          | W   | 1.000      | 0.435        | -                | 0.962 (0.418)    | -         |     4.24 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           56 |      377 | 2024-07-26 | Sampi             | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     1.42 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           55 |      507 | 2024-07-22 | Passion UA        | W   | 1.000      | 0.500        | 0.173 (0.087)    | 1.000 (0.500)    | -         |     4.52 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           54 |      538 | 2024-07-21 | MOUZ NXT          | W   | 1.000      | 0.500        | 0.139 (0.069)    | 0.962 (0.481)    | -         |     4.35 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           53 |      582 | 2024-07-20 | Sangal            | W   | 1.000      | 0.500        | 0.219 (0.109)    | 0.846 (0.423)    | -         |     7.10 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           52 |      603 | 2024-07-19 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.57 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           51 |      655 | 2024-07-18 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -27.12 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           50 |      780 | 2024-07-16 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.28 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           49 |     1032 | 2024-06-16 | 9z                | L   | 0.862      | -            | -                | -                | -         |   -13.53 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           48 |     1036 | 2024-06-16 | Ninjas in Pyjamas | W   | 0.861      | 0.548        | 0.253 (0.120)    | 0.531 (0.251)    | 1 (0.861) |    18.91 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           47 |     1060 | 2024-06-15 | RED Canids        | W   | 0.856      | 0.548        | -                | 0.732 (0.343)    | 1 (0.856) |     4.35 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           46 |     1074 | 2024-06-15 | Imperial          | W   | 0.854      | 0.548        | 0.233 (0.109)    | 0.658 (0.308)    | 1 (0.854) |     7.25 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           45 |     1099 | 2024-06-14 | RED Canids        | L   | 0.848      | -            | -                | -                | -         |   -22.40 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           44 |     1382 | 2024-06-07 | Ninjas in Pyjamas | L   | 0.801      | -            | -                | -                | -         |    -8.45 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           43 |     1438 | 2024-06-06 | BIG               | W   | 0.794      | 0.715        | 0.154 (0.087)    | -                | 1 (0.794) |     7.49 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           42 |     1464 | 2024-06-06 | FURIA             | L   | 0.793      | -            | -                | -                | -         |    -8.62 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           41 |     1479 | 2024-06-06 | Complexity        | W   | 0.792      | 0.715        | 0.341 (0.193)    | -                | 1 (0.792) |    18.80 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           40 |     1509 | 2024-06-05 | Eternal Fire      | W   | 0.787      | 0.715        | 0.738 (0.416)    | 0.438 (0.246)    | 1 (0.787) |    19.32 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           39 |     1525 | 2024-06-05 | BetBoom           | L   | 0.786      | -            | -                | -                | -         |   -14.94 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           38 |     1615 | 2024-06-02 | DMS               | L   | 0.766      | -            | -                | -                | -         |   -22.56 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           37 |     1680 | 2024-05-31 | SAW               | W   | 0.753      | -            | -                | -                | -         |     4.34 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           36 |     1681 | 2024-05-31 | Sangal            | W   | 0.753      | -            | -                | -                | -         |     3.26 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           35 |     2017 | 2024-05-18 | ENCE              | L   | 0.666      | -            | -                | -                | -         |   -12.81 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           34 |     2025 | 2024-05-18 | GamerLegion       | L   | 0.665      | -            | -                | -                | -         |   -18.14 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           33 |     2051 | 2024-05-17 | ENCE              | W   | 0.660      | 0.769        | 0.173 (0.088)    | -                | -         |     7.59 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           32 |     2417 | 2024-05-03 | 9 Pandas          | L   | 0.568      | -            | -                | -                | -         |   -16.96 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           31 |     2445 | 2024-05-02 | Sashi             | L   | 0.560      | -            | -                | -                | -         |   -15.04 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           30 |     2473 | 2024-05-01 | AMKAL             | W   | 0.553      | -            | -                | -                | -         |     1.94 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           29 |     2486 | 2024-05-01 | PARIVISION        | W   | 0.551      | -            | -                | -                | -         |     1.52 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           28 |     2509 | 2024-04-30 | Nexus             | W   | 0.545      | -            | -                | -                | -         |     0.37 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           27 |     2568 | 2024-04-27 | Virtus.pro        | L   | 0.526      | -            | -                | -                | -         |    -4.97 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           26 |     2609 | 2024-04-25 | Eternal Fire      | L   | 0.514      | -            | -                | -                | -         |    -4.56 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           25 |     2633 | 2024-04-24 | 3DMAX             | L   | 0.507      | -            | -                | -                | -         |    -5.77 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           24 |     2657 | 2024-04-23 | Virtus.pro        | W   | 0.499      | 0.889        | 0.499 (0.221)    | -                | 1 (0.499) |    11.19 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           23 |     2808 | 2024-04-18 | KOI               | L   | 0.467      | -            | -                | -                | -         |   -13.66 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           22 |     3062 | 2024-04-09 | Apeks             | L   | 0.408      | -            | -                | -                | -         |   -12.47 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           21 |     3096 | 2024-04-08 | Apeks             | W   | 0.401      | -            | -                | -                | -         |     0.34 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           20 |     3102 | 2024-04-08 | KOI               | W   | 0.400      | -            | -                | -                | -         |     0.83 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           19 |     3435 | 2024-03-23 | BetBoom           | L   | 0.292      | -            | -                | -                | -         |    -6.37 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           18 |     3471 | 2024-03-21 | 3DMAX             | W   | 0.280      | -            | -                | -                | -         |     5.85 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           17 |     3825 | 2024-03-06 | BLEED             | W   | 0.180      | -            | -                | -                | -         |     0.22 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           16 |     3868 | 2024-03-05 | Young Ninjas      | W   | 0.174      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           15 |     3885 | 2024-03-04 | 3DMAX             | W   | 0.166      | -            | -                | -                | -         |     3.60 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           14 |     3902 | 2024-03-03 | Gaimin Gladiators | L   | 0.161      | -            | -                | -                | -         |    -4.88 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           13 |     3907 | 2024-03-03 | AURA              | W   | 0.161      | -            | -                | -                | -         |     0.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           12 |     3917 | 2024-03-03 | ex-Preasy         | W   | 0.159      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           11 |     3954 | 2024-03-01 | ALTERNATE aTTaX   | W   | 0.146      | -            | -                | -                | -         |     0.19 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           10 |     3970 | 2024-02-28 | ex-Preasy         | L   | 0.134      | -            | -                | -                | -         |    -4.18 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            9 |     4086 | 2024-02-23 | GamerLegion       | L   | 0.100      | -            | -                | -                | -         |    -3.11 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            8 |     4231 | 2024-02-17 | SAW               | L   | 0.060      | -            | -                | -                | -         |    -1.70 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            7 |     4267 | 2024-02-16 | KOI               | L   | 0.052      | -            | -                | -                | -         |    -1.54 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            6 |     4290 | 2024-02-15 | AMKAL             | W   | 0.046      | -            | -                | -                | 1 (0.046) |     0.13 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            5 |     4317 | 2024-02-14 | Virtus.pro        | L   | 0.041      | -            | -                | -                | -         |    -0.40 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            4 |     4327 | 2024-02-14 | BetBoom           | W   | 0.040      | -            | -                | -                | 1 (0.040) |     0.39 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            3 |     4398 | 2024-02-09 | 3DMAX             | L   | 0.007      | -            | -                | -                | -         |    -0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            2 |     4401 | 2024-02-09 | ex-Sprout         | L   | 0.007      | -            | -                | -                | -         |    -0.21 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            1 |     4405 | 2024-02-09 | Endpoint          | W   | 0.006      | -            | -                | -                | -         |     0.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($118,647.64)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.37) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-07-22 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-06-16 |      0.862 | $30,000.00     | $25,872.22      |
| 2024-06-09 |      0.813 | $20,000.00     | $16,266.67      |
| 2024-05-12 |      0.627 | $7,000.00      | $4,386.67       |
| 2024-05-04 |      0.574 | $2,000.00      | $1,147.22       |
| 2024-05-02 |      0.560 | $3,500.00      | $1,960.97       |
| 2024-03-06 |      0.180 | $50,000.00     | $9,013.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
