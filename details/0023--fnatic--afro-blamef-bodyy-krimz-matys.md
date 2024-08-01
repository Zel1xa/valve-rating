### Roster Details<br />
Team Name: fnatic<br />
Roster: afro, blameF, bodyy, KRIMZ, MATYS<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [19]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1316.9<br />
<br />
Final Rank Value (1316.9) = Starting Rank Value (1374.7) + Head To Head Adjustments (-57.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.652[<sup>1</sup>](#table2)
- Bounty Collected: 0.540[<sup>2</sup>](#table1)
- Opponent Network: 0.339[<sup>2</sup>](#table1)
- LAN Wins: 0.364[<sup>2</sup>](#table1)

The average of these factors is 0.474<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1374.7
- 400 + ( ( 0.474 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1374.7


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
|           56 |       62 | 2024-07-31 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -20.87 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           55 |      154 | 2024-07-28 | Sangal            | L   | 1.000      | -            | -                | -                | -         |   -20.92 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           54 |      166 | 2024-07-28 | SAW               | W   | 1.000      | 0.435        | -                | 0.544 (0.236)    | 0 (0.000) |     8.82 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           53 |      182 | 2024-07-27 | MOUZ NXT          | W   | 1.000      | 0.435        | 0.141 (0.061)    | 1.000 (0.435)    | 0 (0.000) |     6.74 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           52 |      216 | 2024-07-26 | Sampi             | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | 0 (0.000) |     2.36 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           51 |      347 | 2024-07-22 | Passion UA        | W   | 1.000      | 0.500        | 0.173 (0.086)    | 1.000 (0.500)    | 0 (0.000) |     7.07 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           50 |      379 | 2024-07-21 | MOUZ NXT          | W   | 1.000      | 0.500        | 0.141 (0.070)    | 1.000 (0.500)    | -         |     7.18 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           49 |      424 | 2024-07-20 | Sangal            | W   | 1.000      | 0.500        | 0.221 (0.110)    | 0.823 (0.412)    | -         |    10.14 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           48 |      447 | 2024-07-19 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     2.87 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           47 |      504 | 2024-07-18 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -25.52 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           46 |      630 | 2024-07-16 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     2.42 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           45 |     1238 | 2024-06-07 | Ninjas in Pyjamas | L   | 0.834      | -            | -                | -                | -         |    -8.14 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           44 |     1296 | 2024-06-06 | BIG               | W   | 0.827      | 0.715        | 0.132 (0.078)    | 0.299 (0.177)    | 1 (0.827) |    10.26 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           43 |     1322 | 2024-06-06 | FURIA             | L   | 0.826      | -            | -                | -                | -         |    -5.30 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           42 |     1338 | 2024-06-06 | Complexity        | W   | 0.825      | 0.715        | 0.318 (0.187)    | 0.366 (0.216)    | 1 (0.825) |    22.33 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           41 |     1369 | 2024-06-05 | Eternal Fire      | W   | 0.820      | 0.715        | 0.757 (0.444)    | 0.461 (0.270)    | 1 (0.820) |    22.97 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           40 |     1386 | 2024-06-05 | BetBoom           | L   | 0.819      | -            | -                | -                | -         |   -10.28 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           39 |     1477 | 2024-06-02 | DMS               | L   | 0.799      | -            | -                | -                | -         |   -21.73 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           38 |     1542 | 2024-05-31 | SAW               | W   | 0.786      | -            | -                | -                | -         |     8.92 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           37 |     1543 | 2024-05-31 | Sangal            | W   | 0.786      | -            | -                | -                | -         |     5.84 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           36 |     1906 | 2024-05-18 | ENCE              | L   | 0.699      | -            | -                | -                | -         |    -9.09 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           35 |     1915 | 2024-05-18 | GamerLegion       | L   | 0.698      | -            | -                | -                | -         |   -15.79 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           34 |     1941 | 2024-05-17 | ENCE              | W   | 0.692      | 0.769        | 0.174 (0.092)    | 0.403 (0.214)    | -         |    12.56 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           33 |     2318 | 2024-05-03 | 9 Pandas          | L   | 0.600      | -            | -                | -                | -         |   -16.55 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           32 |     2347 | 2024-05-02 | Sashi             | L   | 0.593      | -            | -                | -                | -         |   -12.87 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           31 |     2376 | 2024-05-01 | AMKAL             | W   | 0.586      | -            | -                | -                | -         |     4.53 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           30 |     2390 | 2024-05-01 | PARIVISION        | W   | 0.584      | -            | -                | -                | -         |     3.58 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           29 |     2413 | 2024-04-30 | Nexus             | W   | 0.578      | -            | -                | -                | -         |     0.98 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           28 |     2473 | 2024-04-27 | Virtus.pro        | L   | 0.558      | -            | -                | -                | -         |    -2.38 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           27 |     2513 | 2024-04-25 | Eternal Fire      | L   | 0.547      | -            | -                | -                | -         |    -2.03 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           26 |     2537 | 2024-04-24 | 3DMAX             | L   | 0.539      | -            | -                | -                | -         |    -3.05 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           25 |     2563 | 2024-04-23 | Virtus.pro        | W   | 0.532      | 0.889        | 0.484 (0.229)    | -                | 1 (0.532) |    14.71 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           24 |     2720 | 2024-04-18 | KOI               | L   | 0.500      | -            | -                | -                | -         |   -14.20 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           23 |     2977 | 2024-04-09 | Apeks             | L   | 0.440      | -            | -                | -                | -         |   -12.73 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           22 |     3011 | 2024-04-08 | Apeks             | W   | 0.434      | -            | -                | -                | -         |     1.06 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           21 |     3017 | 2024-04-08 | KOI               | W   | 0.433      | -            | -                | -                | -         |     1.19 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           20 |     3363 | 2024-03-23 | BetBoom           | L   | 0.325      | -            | -                | -                | -         |    -4.28 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           19 |     3399 | 2024-03-21 | 3DMAX             | W   | 0.313      | -            | -                | -                | -         |     8.33 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           18 |     3759 | 2024-03-06 | BLEED             | W   | 0.213      | -            | -                | -                | -         |     0.72 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           17 |     3798 | 2024-03-05 | Passion UA        | L   | 0.207      | -            | -                | -                | -         |    -5.32 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           16 |     3807 | 2024-03-05 | Young Ninjas      | W   | 0.206      | -            | -                | -                | -         |     0.23 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           15 |     3824 | 2024-03-04 | 3DMAX             | W   | 0.199      | 0.500        | 0.505 (0.050)    | -                | -         |     5.40 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           14 |     3841 | 2024-03-03 | Gaimin Gladiators | L   | 0.194      | -            | -                | -                | -         |    -5.41 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           13 |     3846 | 2024-03-03 | AURA              | W   | 0.193      | -            | -                | -                | -         |     0.05 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           12 |     3856 | 2024-03-03 | ex-Preasy         | W   | 0.192      | -            | -                | -                | -         |     0.24 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           11 |     3894 | 2024-03-01 | ALTERNATE aTTaX   | W   | 0.179      | -            | -                | -                | -         |     0.63 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           10 |     3910 | 2024-02-28 | ex-Preasy         | L   | 0.167      | -            | -                | -                | -         |    -5.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            9 |     4032 | 2024-02-23 | GamerLegion       | L   | 0.133      | -            | -                | -                | -         |    -4.03 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            8 |     4179 | 2024-02-17 | SAW               | L   | 0.093      | -            | -                | -                | -         |    -2.18 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            7 |     4216 | 2024-02-16 | KOI               | L   | 0.085      | -            | -                | -                | -         |    -2.46 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            6 |     4239 | 2024-02-15 | AMKAL             | W   | 0.079      | -            | -                | -                | 1 (0.079) |     0.55 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            5 |     4266 | 2024-02-14 | Virtus.pro        | L   | 0.074      | -            | -                | -                | -         |    -0.30 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            4 |     4276 | 2024-02-14 | BetBoom           | W   | 0.073      | -            | -                | -                | 1 (0.073) |     1.35 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            3 |     4357 | 2024-02-09 | 3DMAX             | L   | 0.040      | -            | -                | -                | -         |    -0.18 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            2 |     4360 | 2024-02-09 | ex-Sprout         | L   | 0.039      | -            | -                | -                | -         |    -1.23 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            1 |     4364 | 2024-02-09 | Endpoint          | W   | 0.039      | -            | -                | -                | -         |     0.09 | afro, bodyy, KRIMZ, kyuubii, MATYS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($95,479.58)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.29) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-07-22 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-06-09 |      0.846 | $20,000.00     | $16,922.22      |
| 2024-05-12 |      0.659 | $7,000.00      | $4,616.11       |
| 2024-05-04 |      0.606 | $2,000.00      | $1,212.78       |
| 2024-05-02 |      0.593 | $3,500.00      | $2,075.69       |
| 2024-03-06 |      0.213 | $50,000.00     | $10,652.78      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
