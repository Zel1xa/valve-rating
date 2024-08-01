### Roster Details<br />
Team Name: fnatic<br />
Roster: afro, blameF, bodyy, KRIMZ, MATYS<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [19]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1317.3<br />
<br />
Final Rank Value (1317.3) = Starting Rank Value (1374.7) + Head To Head Adjustments (-57.3)<br />

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
|           57 |        5 | 2024-08-01 | G2 Ares           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.18 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           56 |       65 | 2024-07-31 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -20.88 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           55 |      156 | 2024-07-28 | Sangal            | L   | 1.000      | -            | -                | -                | -         |   -20.92 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           54 |      168 | 2024-07-28 | SAW               | W   | 1.000      | 0.435        | -                | 0.544 (0.236)    | 0 (0.000) |     8.81 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           53 |      184 | 2024-07-27 | MOUZ NXT          | W   | 1.000      | 0.435        | 0.141 (0.061)    | 1.000 (0.435)    | 0 (0.000) |     6.74 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           52 |      218 | 2024-07-26 | Sampi             | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | 0 (0.000) |     2.36 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           51 |      349 | 2024-07-22 | Passion UA        | W   | 1.000      | 0.500        | 0.173 (0.086)    | 1.000 (0.500)    | -         |     7.06 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           50 |      381 | 2024-07-21 | MOUZ NXT          | W   | 1.000      | 0.500        | 0.141 (0.070)    | 1.000 (0.500)    | -         |     7.18 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           49 |      426 | 2024-07-20 | Sangal            | W   | 1.000      | 0.500        | 0.221 (0.110)    | 0.823 (0.412)    | -         |    10.14 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           48 |      449 | 2024-07-19 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     2.87 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           47 |      505 | 2024-07-18 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -25.52 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           46 |      632 | 2024-07-16 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     2.41 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           45 |     1240 | 2024-06-07 | Ninjas in Pyjamas | L   | 0.833      | -            | -                | -                | -         |    -8.12 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           44 |     1298 | 2024-06-06 | BIG               | W   | 0.827      | 0.715        | 0.132 (0.078)    | 0.299 (0.177)    | 1 (0.827) |    10.25 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           43 |     1324 | 2024-06-06 | FURIA             | L   | 0.826      | -            | -                | -                | -         |    -5.28 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           42 |     1340 | 2024-06-06 | Complexity        | W   | 0.824      | 0.715        | 0.318 (0.187)    | 0.366 (0.216)    | 1 (0.824) |    22.31 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           41 |     1371 | 2024-06-05 | Eternal Fire      | W   | 0.820      | 0.715        | 0.757 (0.444)    | 0.461 (0.270)    | 1 (0.820) |    22.97 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           40 |     1388 | 2024-06-05 | BetBoom           | L   | 0.818      | -            | -                | -                | -         |   -10.26 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           39 |     1479 | 2024-06-02 | DMS               | L   | 0.798      | -            | -                | -                | -         |   -21.72 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           38 |     1544 | 2024-05-31 | SAW               | W   | 0.786      | -            | -                | -                | -         |     8.91 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           37 |     1545 | 2024-05-31 | Sangal            | W   | 0.785      | -            | -                | -                | -         |     5.84 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           36 |     1908 | 2024-05-18 | ENCE              | L   | 0.699      | -            | -                | -                | -         |    -9.06 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           35 |     1917 | 2024-05-18 | GamerLegion       | L   | 0.698      | -            | -                | -                | -         |   -15.76 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           34 |     1943 | 2024-05-17 | ENCE              | W   | 0.692      | 0.769        | 0.173 (0.092)    | 0.403 (0.214)    | -         |    12.59 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           33 |     2320 | 2024-05-03 | 9 Pandas          | L   | 0.600      | -            | -                | -                | -         |   -16.54 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           32 |     2349 | 2024-05-02 | Sashi             | L   | 0.593      | -            | -                | -                | -         |   -12.86 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           31 |     2378 | 2024-05-01 | AMKAL             | W   | 0.586      | -            | -                | -                | -         |     4.52 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           30 |     2392 | 2024-05-01 | PARIVISION        | W   | 0.584      | -            | -                | -                | -         |     3.68 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           29 |     2415 | 2024-04-30 | Nexus             | W   | 0.577      | -            | -                | -                | -         |     0.98 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           28 |     2475 | 2024-04-27 | Virtus.pro        | L   | 0.558      | -            | -                | -                | -         |    -2.37 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           27 |     2515 | 2024-04-25 | Eternal Fire      | L   | 0.547      | -            | -                | -                | -         |    -2.02 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           26 |     2539 | 2024-04-24 | 3DMAX             | L   | 0.539      | -            | -                | -                | -         |    -3.05 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           25 |     2565 | 2024-04-23 | Virtus.pro        | W   | 0.532      | 0.889        | 0.484 (0.228)    | -                | 1 (0.532) |    14.71 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           24 |     2722 | 2024-04-18 | KOI               | L   | 0.499      | -            | -                | -                | -         |   -14.20 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           23 |     2979 | 2024-04-09 | Apeks             | L   | 0.440      | -            | -                | -                | -         |   -12.73 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           22 |     3013 | 2024-04-08 | Apeks             | W   | 0.433      | -            | -                | -                | -         |     1.06 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           21 |     3019 | 2024-04-08 | KOI               | W   | 0.432      | -            | -                | -                | -         |     1.19 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           20 |     3365 | 2024-03-23 | BetBoom           | L   | 0.325      | -            | -                | -                | -         |    -4.26 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           19 |     3401 | 2024-03-21 | 3DMAX             | W   | 0.312      | -            | -                | -                | -         |     8.32 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           18 |     3761 | 2024-03-06 | BLEED             | W   | 0.213      | -            | -                | -                | -         |     0.72 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           17 |     3800 | 2024-03-05 | Passion UA        | L   | 0.207      | -            | -                | -                | -         |    -5.31 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           16 |     3809 | 2024-03-05 | Young Ninjas      | W   | 0.206      | -            | -                | -                | -         |     0.23 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           15 |     3826 | 2024-03-04 | 3DMAX             | W   | 0.199      | 0.500        | 0.505 (0.050)    | -                | -         |     5.39 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           14 |     3843 | 2024-03-03 | Gaimin Gladiators | L   | 0.193      | -            | -                | -                | -         |    -5.40 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           13 |     3848 | 2024-03-03 | AURA              | W   | 0.193      | -            | -                | -                | -         |     0.05 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           12 |     3858 | 2024-03-03 | ex-Preasy         | W   | 0.192      | -            | -                | -                | -         |     0.24 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           11 |     3896 | 2024-03-01 | ALTERNATE aTTaX   | W   | 0.179      | -            | -                | -                | -         |     0.63 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           10 |     3912 | 2024-02-28 | ex-Preasy         | L   | 0.167      | -            | -                | -                | -         |    -5.06 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            9 |     4034 | 2024-02-23 | GamerLegion       | L   | 0.133      | -            | -                | -                | -         |    -4.02 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            8 |     4181 | 2024-02-17 | SAW               | L   | 0.092      | -            | -                | -                | -         |    -2.17 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            7 |     4218 | 2024-02-16 | KOI               | L   | 0.085      | -            | -                | -                | -         |    -2.46 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            6 |     4241 | 2024-02-15 | AMKAL             | W   | 0.078      | -            | -                | -                | 1 (0.078) |     0.55 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            5 |     4268 | 2024-02-14 | Virtus.pro        | L   | 0.074      | -            | -                | -                | -         |    -0.30 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            4 |     4278 | 2024-02-14 | BetBoom           | W   | 0.072      | -            | -                | -                | 1 (0.072) |     1.35 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            3 |     4359 | 2024-02-09 | 3DMAX             | L   | 0.040      | -            | -                | -                | -         |    -0.18 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            2 |     4362 | 2024-02-09 | ex-Sprout         | L   | 0.039      | -            | -                | -                | -         |    -1.22 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            1 |     4366 | 2024-02-09 | Endpoint          | W   | 0.039      | -            | -                | -                | -         |     0.09 | afro, bodyy, KRIMZ, kyuubii, MATYS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($95,456.67)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.29) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-07-22 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-06-09 |      0.846 | $20,000.00     | $16,916.67      |
| 2024-05-12 |      0.659 | $7,000.00      | $4,614.17       |
| 2024-05-04 |      0.606 | $2,000.00      | $1,212.22       |
| 2024-05-02 |      0.593 | $3,500.00      | $2,074.72       |
| 2024-03-06 |      0.213 | $50,000.00     | $10,638.89      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
