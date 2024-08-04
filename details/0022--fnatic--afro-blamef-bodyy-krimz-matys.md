### Roster Details<br />
Team Name: fnatic<br />
Roster: afro, blameF, bodyy, KRIMZ, MATYS<br />
Global Rank: [22](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1401.6<br />
<br />
Final Rank Value (1401.6) = Starting Rank Value (1559.8) + Head To Head Adjustments (-158.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.699[<sup>1</sup>](#table2)
- Bounty Collected: 0.549[<sup>2</sup>](#table1)
- Opponent Network: 0.374[<sup>2</sup>](#table1)
- LAN Wins: 0.647[<sup>2</sup>](#table1)

The average of these factors is 0.567<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1559.8
- 400 + ( ( 0.567 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1559.8


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
|           63 |       10 | 2024-08-03 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -14.40 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           62 |       60 | 2024-08-02 | Nemiga            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.70 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           61 |       91 | 2024-08-01 | G2 Ares           | W   | 1.000      | -            | -                | -                | -         |     0.11 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           60 |      155 | 2024-07-31 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -24.44 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           59 |      246 | 2024-07-28 | Sangal            | L   | 1.000      | -            | -                | -                | -         |   -23.75 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           58 |      258 | 2024-07-28 | SAW               | W   | 1.000      | 0.435        | -                | 0.540 (0.235)    | -         |     5.78 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           57 |      274 | 2024-07-27 | MOUZ NXT          | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     4.11 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           56 |      308 | 2024-07-26 | Sampi             | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     1.35 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           55 |      438 | 2024-07-22 | Passion UA        | W   | 1.000      | 0.500        | 0.172 (0.086)    | 1.000 (0.500)    | -         |     4.36 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           54 |      469 | 2024-07-21 | MOUZ NXT          | W   | 1.000      | 0.500        | 0.139 (0.070)    | 1.000 (0.500)    | -         |     4.22 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           53 |      513 | 2024-07-20 | Sangal            | W   | 1.000      | 0.500        | 0.219 (0.109)    | 0.861 (0.431)    | -         |     6.89 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           52 |      534 | 2024-07-19 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.55 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           51 |      587 | 2024-07-18 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -27.22 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           50 |      711 | 2024-07-16 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.27 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           49 |      963 | 2024-06-16 | 9z                | L   | 0.876      | -            | -                | -                | -         |   -13.60 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           48 |      967 | 2024-06-16 | Ninjas in Pyjamas | W   | 0.875      | 0.548        | 0.255 (0.122)    | 0.553 (0.265)    | 1 (0.875) |    19.24 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           47 |      991 | 2024-06-15 | RED Canids        | W   | 0.870      | 0.548        | -                | 0.743 (0.355)    | 1 (0.870) |     4.55 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           46 |     1005 | 2024-06-15 | Imperial          | W   | 0.868      | 0.548        | 0.237 (0.113)    | 0.685 (0.326)    | 1 (0.868) |     7.61 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           45 |     1030 | 2024-06-14 | RED Canids        | L   | 0.862      | -            | -                | -                | -         |   -22.61 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           44 |     1313 | 2024-06-07 | Ninjas in Pyjamas | L   | 0.815      | -            | -                | -                | -         |    -8.56 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           43 |     1369 | 2024-06-06 | BIG               | W   | 0.808      | 0.715        | 0.155 (0.090)    | -                | 1 (0.808) |     7.73 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           42 |     1395 | 2024-06-06 | FURIA             | L   | 0.807      | -            | -                | -                | -         |    -8.83 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           41 |     1410 | 2024-06-06 | Complexity        | W   | 0.806      | 0.715        | 0.310 (0.179)    | -                | 1 (0.806) |    19.05 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           40 |     1440 | 2024-06-05 | Eternal Fire      | W   | 0.801      | 0.715        | 0.742 (0.425)    | 0.458 (0.262)    | 1 (0.801) |    19.73 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           39 |     1456 | 2024-06-05 | BetBoom           | L   | 0.800      | -            | -                | -                | -         |   -15.04 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           38 |     1546 | 2024-06-02 | DMS               | L   | 0.780      | -            | -                | -                | -         |   -22.97 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           37 |     1611 | 2024-05-31 | SAW               | W   | 0.767      | -            | -                | -                | -         |     4.58 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           36 |     1612 | 2024-05-31 | Sangal            | W   | 0.767      | -            | -                | -                | -         |     3.17 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           35 |     1948 | 2024-05-18 | ENCE              | L   | 0.680      | -            | -                | -                | -         |   -13.37 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           34 |     1956 | 2024-05-18 | GamerLegion       | L   | 0.679      | -            | -                | -                | -         |   -18.47 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           33 |     1982 | 2024-05-17 | ENCE              | W   | 0.674      | 0.769        | 0.169 (0.087)    | -                | -         |     7.43 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           32 |     2348 | 2024-05-03 | 9 Pandas          | L   | 0.582      | -            | -                | -                | -         |   -17.37 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           31 |     2376 | 2024-05-02 | Sashi             | L   | 0.574      | -            | -                | -                | -         |   -15.43 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           30 |     2404 | 2024-05-01 | AMKAL             | W   | 0.567      | -            | -                | -                | -         |     1.97 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           29 |     2417 | 2024-05-01 | PARIVISION        | W   | 0.565      | -            | -                | -                | -         |     1.48 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           28 |     2440 | 2024-04-30 | Nexus             | W   | 0.559      | -            | -                | -                | -         |     0.37 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           27 |     2499 | 2024-04-27 | Virtus.pro        | L   | 0.540      | -            | -                | -                | -         |    -5.05 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           26 |     2540 | 2024-04-25 | Eternal Fire      | L   | 0.528      | -            | -                | -                | -         |    -4.64 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           25 |     2564 | 2024-04-24 | 3DMAX             | L   | 0.521      | -            | -                | -                | -         |    -6.13 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           24 |     2588 | 2024-04-23 | Virtus.pro        | W   | 0.513      | 0.889        | 0.497 (0.227)    | -                | 1 (0.513) |    11.55 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           23 |     2739 | 2024-04-18 | KOI               | L   | 0.481      | -            | -                | -                | -         |   -14.05 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           22 |     2993 | 2024-04-09 | Apeks             | L   | 0.422      | -            | -                | -                | -         |   -12.89 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           21 |     3027 | 2024-04-08 | Apeks             | W   | 0.415      | -            | -                | -                | -         |     0.35 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           20 |     3033 | 2024-04-08 | KOI               | W   | 0.414      | -            | -                | -                | -         |     0.87 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           19 |     3366 | 2024-03-23 | BetBoom           | L   | 0.306      | -            | -                | -                | -         |    -6.62 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           18 |     3402 | 2024-03-21 | 3DMAX             | W   | 0.294      | -            | -                | -                | -         |     6.03 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           17 |     3756 | 2024-03-06 | BLEED             | W   | 0.194      | -            | -                | -                | -         |     0.23 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           16 |     3799 | 2024-03-05 | Young Ninjas      | W   | 0.188      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           15 |     3816 | 2024-03-04 | 3DMAX             | W   | 0.180      | -            | -                | -                | -         |     3.85 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           14 |     3833 | 2024-03-03 | Gaimin Gladiators | L   | 0.175      | -            | -                | -                | -         |    -5.29 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           13 |     3838 | 2024-03-03 | AURA              | W   | 0.175      | -            | -                | -                | -         |     0.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           12 |     3848 | 2024-03-03 | ex-Preasy         | W   | 0.173      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           11 |     3885 | 2024-03-01 | ALTERNATE aTTaX   | W   | 0.160      | -            | -                | -                | -         |     0.20 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           10 |     3901 | 2024-02-28 | ex-Preasy         | L   | 0.148      | -            | -                | -                | -         |    -4.62 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            9 |     4017 | 2024-02-23 | GamerLegion       | L   | 0.114      | -            | -                | -                | -         |    -3.55 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            8 |     4162 | 2024-02-17 | SAW               | L   | 0.074      | -            | -                | -                | -         |    -2.09 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            7 |     4198 | 2024-02-16 | KOI               | L   | 0.066      | -            | -                | -                | -         |    -1.95 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            6 |     4221 | 2024-02-15 | AMKAL             | W   | 0.060      | -            | -                | -                | 1 (0.060) |     0.17 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            5 |     4248 | 2024-02-14 | Virtus.pro        | L   | 0.055      | -            | -                | -                | -         |    -0.54 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            4 |     4258 | 2024-02-14 | BetBoom           | W   | 0.054      | -            | -                | -                | 1 (0.054) |     0.54 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            3 |     4329 | 2024-02-09 | 3DMAX             | L   | 0.021      | -            | -                | -                | -         |    -0.23 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            2 |     4332 | 2024-02-09 | ex-Sprout         | L   | 0.021      | -            | -                | -                | -         |    -0.65 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            1 |     4336 | 2024-02-09 | Endpoint          | W   | 0.020      | -            | -                | -                | -         |     0.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($120,223.16)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.37) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-07-22 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-06-16 |      0.876 | $30,000.00     | $26,292.36      |
| 2024-06-09 |      0.827 | $20,000.00     | $16,546.76      |
| 2024-05-12 |      0.641 | $7,000.00      | $4,484.70       |
| 2024-05-04 |      0.588 | $2,000.00      | $1,175.23       |
| 2024-05-02 |      0.574 | $3,500.00      | $2,009.99       |
| 2024-03-06 |      0.194 | $50,000.00     | $9,714.12       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
