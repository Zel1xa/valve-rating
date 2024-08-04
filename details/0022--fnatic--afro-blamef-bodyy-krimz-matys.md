### Roster Details<br />
Team Name: fnatic<br />
Roster: afro, blameF, bodyy, KRIMZ, MATYS<br />
Global Rank: [22](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1400.0<br />
<br />
Final Rank Value (1400.0) = Starting Rank Value (1559.3) + Head To Head Adjustments (-159.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.699[<sup>1</sup>](#table2)
- Bounty Collected: 0.548[<sup>2</sup>](#table1)
- Opponent Network: 0.374[<sup>2</sup>](#table1)
- LAN Wins: 0.647[<sup>2</sup>](#table1)

The average of these factors is 0.567<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1559.3
- 400 + ( ( 0.567 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1559.3


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
|           63 |        4 | 2024-08-03 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -14.40 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           62 |       53 | 2024-08-02 | Nemiga            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.72 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           61 |       83 | 2024-08-01 | G2 Ares           | W   | 1.000      | -            | -                | -                | -         |     0.11 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           60 |      147 | 2024-07-31 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -24.40 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           59 |      238 | 2024-07-28 | Sangal            | L   | 1.000      | -            | -                | -                | -         |   -23.73 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           58 |      250 | 2024-07-28 | SAW               | W   | 1.000      | 0.435        | -                | 0.540 (0.235)    | -         |     5.70 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           57 |      266 | 2024-07-27 | MOUZ NXT          | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     4.11 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           56 |      300 | 2024-07-26 | Sampi             | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     1.35 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           55 |      430 | 2024-07-22 | Passion UA        | W   | 1.000      | 0.500        | 0.172 (0.086)    | 1.000 (0.500)    | -         |     4.28 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           54 |      461 | 2024-07-21 | MOUZ NXT          | W   | 1.000      | 0.500        | 0.139 (0.070)    | 1.000 (0.500)    | -         |     4.23 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           53 |      505 | 2024-07-20 | Sangal            | W   | 1.000      | 0.500        | 0.219 (0.109)    | 0.862 (0.431)    | -         |     6.90 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           52 |      526 | 2024-07-19 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.56 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           51 |      579 | 2024-07-18 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -27.21 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           50 |      703 | 2024-07-16 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.27 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           49 |      955 | 2024-06-16 | 9z                | L   | 0.877      | -            | -                | -                | -         |   -13.66 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           48 |      959 | 2024-06-16 | Ninjas in Pyjamas | W   | 0.876      | 0.548        | 0.222 (0.107)    | 0.553 (0.266)    | 1 (0.876) |    18.96 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           47 |      983 | 2024-06-15 | RED Canids        | W   | 0.870      | 0.548        | -                | 0.743 (0.355)    | 1 (0.870) |     4.58 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           46 |      997 | 2024-06-15 | Imperial          | W   | 0.868      | 0.548        | 0.237 (0.113)    | 0.685 (0.326)    | 1 (0.868) |     7.66 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           45 |     1022 | 2024-06-14 | RED Canids        | L   | 0.863      | -            | -                | -                | -         |   -22.61 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           44 |     1305 | 2024-06-07 | Ninjas in Pyjamas | L   | 0.815      | -            | -                | -                | -         |    -8.90 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           43 |     1361 | 2024-06-06 | BIG               | W   | 0.809      | 0.715        | 0.155 (0.090)    | -                | 1 (0.809) |     7.75 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           42 |     1387 | 2024-06-06 | FURIA             | L   | 0.808      | -            | -                | -                | -         |    -8.90 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           41 |     1402 | 2024-06-06 | Complexity        | W   | 0.807      | 0.715        | 0.310 (0.179)    | -                | 1 (0.807) |    19.01 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           40 |     1432 | 2024-06-05 | Eternal Fire      | W   | 0.802      | 0.715        | 0.743 (0.426)    | 0.458 (0.263)    | 1 (0.802) |    19.67 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           39 |     1448 | 2024-06-05 | BetBoom           | L   | 0.801      | -            | -                | -                | -         |   -15.05 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           38 |     1538 | 2024-06-02 | DMS               | L   | 0.781      | -            | -                | -                | -         |   -22.98 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           37 |     1603 | 2024-05-31 | SAW               | W   | 0.768      | -            | -                | -                | -         |     4.58 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           36 |     1604 | 2024-05-31 | Sangal            | W   | 0.768      | -            | -                | -                | -         |     3.16 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           35 |     1940 | 2024-05-18 | ENCE              | L   | 0.681      | -            | -                | -                | -         |   -13.40 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           34 |     1948 | 2024-05-18 | GamerLegion       | L   | 0.680      | -            | -                | -                | -         |   -18.48 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           33 |     1974 | 2024-05-17 | ENCE              | W   | 0.674      | 0.769        | 0.169 (0.088)    | -                | -         |     7.42 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           32 |     2340 | 2024-05-03 | 9 Pandas          | L   | 0.582      | -            | -                | -                | -         |   -17.39 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           31 |     2368 | 2024-05-02 | Sashi             | L   | 0.575      | -            | -                | -                | -         |   -15.46 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           30 |     2396 | 2024-05-01 | AMKAL             | W   | 0.568      | -            | -                | -                | -         |     1.98 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           29 |     2409 | 2024-05-01 | PARIVISION        | W   | 0.566      | -            | -                | -                | -         |     1.49 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           28 |     2432 | 2024-04-30 | Nexus             | W   | 0.559      | -            | -                | -                | -         |     0.37 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           27 |     2491 | 2024-04-27 | Virtus.pro        | L   | 0.540      | -            | -                | -                | -         |    -5.09 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           26 |     2532 | 2024-04-25 | Eternal Fire      | L   | 0.529      | -            | -                | -                | -         |    -4.68 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           25 |     2556 | 2024-04-24 | 3DMAX             | L   | 0.521      | -            | -                | -                | -         |    -6.13 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           24 |     2580 | 2024-04-23 | Virtus.pro        | W   | 0.514      | 0.889        | 0.497 (0.227)    | -                | 1 (0.514) |    11.53 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           23 |     2731 | 2024-04-18 | KOI               | L   | 0.482      | -            | -                | -                | -         |   -14.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           22 |     2985 | 2024-04-09 | Apeks             | L   | 0.422      | -            | -                | -                | -         |   -12.91 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           21 |     3019 | 2024-04-08 | Apeks             | W   | 0.416      | -            | -                | -                | -         |     0.36 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           20 |     3025 | 2024-04-08 | KOI               | W   | 0.415      | -            | -                | -                | -         |     0.88 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           19 |     3358 | 2024-03-23 | BetBoom           | L   | 0.307      | -            | -                | -                | -         |    -6.63 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           18 |     3394 | 2024-03-21 | 3DMAX             | W   | 0.295      | -            | -                | -                | -         |     6.05 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           17 |     3748 | 2024-03-06 | BLEED             | W   | 0.195      | -            | -                | -                | -         |     0.24 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           16 |     3791 | 2024-03-05 | Young Ninjas      | W   | 0.188      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           15 |     3808 | 2024-03-04 | 3DMAX             | W   | 0.181      | -            | -                | -                | -         |     3.87 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           14 |     3825 | 2024-03-03 | Gaimin Gladiators | L   | 0.176      | -            | -                | -                | -         |    -5.31 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           13 |     3830 | 2024-03-03 | AURA              | W   | 0.175      | -            | -                | -                | -         |     0.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           12 |     3840 | 2024-03-03 | ex-Preasy         | W   | 0.174      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           11 |     3877 | 2024-03-01 | ALTERNATE aTTaX   | W   | 0.161      | -            | -                | -                | -         |     0.21 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           10 |     3893 | 2024-02-28 | ex-Preasy         | L   | 0.149      | -            | -                | -                | -         |    -4.64 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            9 |     4009 | 2024-02-23 | GamerLegion       | L   | 0.115      | -            | -                | -                | -         |    -3.57 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            8 |     4154 | 2024-02-17 | SAW               | L   | 0.075      | -            | -                | -                | -         |    -2.12 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            7 |     4190 | 2024-02-16 | KOI               | L   | 0.067      | -            | -                | -                | -         |    -1.97 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            6 |     4213 | 2024-02-15 | AMKAL             | W   | 0.061      | -            | -                | -                | 1 (0.061) |     0.17 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            5 |     4240 | 2024-02-14 | Virtus.pro        | L   | 0.056      | -            | -                | -                | -         |    -0.55 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            4 |     4250 | 2024-02-14 | BetBoom           | W   | 0.055      | -            | -                | -                | 1 (0.055) |     0.55 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            3 |     4321 | 2024-02-09 | 3DMAX             | L   | 0.022      | -            | -                | -                | -         |    -0.23 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            2 |     4324 | 2024-02-09 | ex-Sprout         | L   | 0.021      | -            | -                | -                | -         |    -0.67 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            1 |     4328 | 2024-02-09 | Endpoint          | W   | 0.021      | -            | -                | -                | -         |     0.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($120,303.89)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.37) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-07-22 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-06-16 |      0.877 | $30,000.00     | $26,313.89      |
| 2024-06-09 |      0.828 | $20,000.00     | $16,561.11      |
| 2024-05-12 |      0.641 | $7,000.00      | $4,489.72       |
| 2024-05-04 |      0.588 | $2,000.00      | $1,176.67       |
| 2024-05-02 |      0.575 | $3,500.00      | $2,012.50       |
| 2024-03-06 |      0.195 | $50,000.00     | $9,750.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
