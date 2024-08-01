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
Final Rank Value (1316.9) = Starting Rank Value (1376.3) + Head To Head Adjustments (-59.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.652[<sup>1</sup>](#table2)
- Bounty Collected: 0.540[<sup>2</sup>](#table1)
- Opponent Network: 0.340[<sup>2</sup>](#table1)
- LAN Wins: 0.365[<sup>2</sup>](#table1)

The average of these factors is 0.474<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1376.3
- 400 + ( ( 0.474 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1376.3


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
|           56 |       58 | 2024-07-31 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -20.83 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           55 |      150 | 2024-07-28 | Sangal            | L   | 1.000      | -            | -                | -                | -         |   -20.91 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           54 |      162 | 2024-07-28 | SAW               | W   | 1.000      | 0.435        | -                | 0.544 (0.236)    | 0 (0.000) |     8.85 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           53 |      178 | 2024-07-27 | MOUZ NXT          | W   | 1.000      | 0.435        | 0.141 (0.061)    | 1.000 (0.435)    | 0 (0.000) |     6.75 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           52 |      212 | 2024-07-26 | Sampi             | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | 0 (0.000) |     2.37 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           51 |      343 | 2024-07-22 | Passion UA        | W   | 1.000      | 0.500        | 0.172 (0.086)    | 1.000 (0.500)    | 0 (0.000) |     7.06 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           50 |      375 | 2024-07-21 | MOUZ NXT          | W   | 1.000      | 0.500        | 0.141 (0.070)    | 1.000 (0.500)    | -         |     7.20 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           49 |      420 | 2024-07-20 | Sangal            | W   | 1.000      | 0.500        | 0.221 (0.111)    | 0.823 (0.412)    | -         |    10.16 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           48 |      443 | 2024-07-19 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     2.88 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           47 |      500 | 2024-07-18 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -25.50 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           46 |      626 | 2024-07-16 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     2.43 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           45 |     1234 | 2024-06-07 | Ninjas in Pyjamas | L   | 0.835      | -            | -                | -                | -         |    -9.56 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           44 |     1292 | 2024-06-06 | BIG               | W   | 0.829      | 0.715        | 0.132 (0.078)    | 0.299 (0.177)    | 1 (0.829) |    10.28 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           43 |     1318 | 2024-06-06 | FURIA             | L   | 0.827      | -            | -                | -                | -         |    -5.34 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           42 |     1334 | 2024-06-06 | Complexity        | W   | 0.826      | 0.715        | 0.318 (0.188)    | 0.366 (0.216)    | 1 (0.826) |    22.34 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           41 |     1365 | 2024-06-05 | Eternal Fire      | W   | 0.821      | 0.715        | 0.757 (0.445)    | 0.461 (0.271)    | 1 (0.821) |    22.98 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           40 |     1382 | 2024-06-05 | BetBoom           | L   | 0.820      | -            | -                | -                | -         |   -10.31 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           39 |     1473 | 2024-06-02 | DMS               | L   | 0.800      | -            | -                | -                | -         |   -21.77 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           38 |     1538 | 2024-05-31 | SAW               | W   | 0.787      | -            | -                | -                | -         |     8.94 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           37 |     1539 | 2024-05-31 | Sangal            | W   | 0.787      | -            | -                | -                | -         |     5.81 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           36 |     1902 | 2024-05-18 | ENCE              | L   | 0.700      | -            | -                | -                | -         |    -9.10 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           35 |     1911 | 2024-05-18 | GamerLegion       | L   | 0.699      | -            | -                | -                | -         |   -15.81 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           34 |     1937 | 2024-05-17 | ENCE              | W   | 0.694      | 0.769        | 0.174 (0.093)    | 0.403 (0.215)    | -         |    12.59 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           33 |     2314 | 2024-05-03 | 9 Pandas          | L   | 0.602      | -            | -                | -                | -         |   -16.59 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           32 |     2343 | 2024-05-02 | Sashi             | L   | 0.594      | -            | -                | -                | -         |   -12.90 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           31 |     2372 | 2024-05-01 | AMKAL             | W   | 0.587      | -            | -                | -                | -         |     4.53 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           30 |     2386 | 2024-05-01 | PARIVISION        | W   | 0.586      | -            | -                | -                | -         |     3.58 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           29 |     2409 | 2024-04-30 | Nexus             | W   | 0.579      | -            | -                | -                | -         |     0.98 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           28 |     2469 | 2024-04-27 | Virtus.pro        | L   | 0.560      | -            | -                | -                | -         |    -2.38 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           27 |     2509 | 2024-04-25 | Eternal Fire      | L   | 0.548      | -            | -                | -                | -         |    -2.04 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           26 |     2533 | 2024-04-24 | 3DMAX             | L   | 0.541      | -            | -                | -                | -         |    -3.06 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           25 |     2559 | 2024-04-23 | Virtus.pro        | W   | 0.533      | 0.889        | 0.483 (0.229)    | -                | 1 (0.533) |    14.76 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           24 |     2716 | 2024-04-18 | KOI               | L   | 0.501      | -            | -                | -                | -         |   -14.24 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           23 |     2973 | 2024-04-09 | Apeks             | L   | 0.442      | -            | -                | -                | -         |   -12.78 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           22 |     3007 | 2024-04-08 | Apeks             | W   | 0.435      | -            | -                | -                | -         |     1.06 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           21 |     3013 | 2024-04-08 | KOI               | W   | 0.434      | -            | -                | -                | -         |     1.19 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           20 |     3359 | 2024-03-23 | BetBoom           | L   | 0.326      | -            | -                | -                | -         |    -4.29 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           19 |     3395 | 2024-03-21 | 3DMAX             | W   | 0.314      | -            | -                | -                | -         |     8.37 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           18 |     3755 | 2024-03-06 | BLEED             | W   | 0.214      | -            | -                | -                | -         |     0.73 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           17 |     3794 | 2024-03-05 | Passion UA        | L   | 0.208      | -            | -                | -                | -         |    -5.35 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           16 |     3803 | 2024-03-05 | Young Ninjas      | W   | 0.208      | -            | -                | -                | -         |     0.23 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           15 |     3820 | 2024-03-04 | 3DMAX             | W   | 0.200      | 0.500        | 0.505 (0.051)    | -                | -         |     5.43 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           14 |     3837 | 2024-03-03 | Gaimin Gladiators | L   | 0.195      | -            | -                | -                | -         |    -5.45 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           13 |     3842 | 2024-03-03 | AURA              | W   | 0.195      | -            | -                | -                | -         |     0.05 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           12 |     3852 | 2024-03-03 | ex-Preasy         | W   | 0.194      | -            | -                | -                | -         |     0.24 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           11 |     3890 | 2024-03-01 | ALTERNATE aTTaX   | W   | 0.180      | -            | -                | -                | -         |     0.63 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           10 |     3906 | 2024-02-28 | ex-Preasy         | L   | 0.169      | -            | -                | -                | -         |    -5.11 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            9 |     4028 | 2024-02-23 | GamerLegion       | L   | 0.134      | -            | -                | -                | -         |    -4.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            8 |     4175 | 2024-02-17 | SAW               | L   | 0.094      | -            | -                | -                | -         |    -2.21 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            7 |     4212 | 2024-02-16 | KOI               | L   | 0.086      | -            | -                | -                | -         |    -2.51 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            6 |     4235 | 2024-02-15 | AMKAL             | W   | 0.080      | -            | -                | -                | 1 (0.080) |     0.56 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            5 |     4262 | 2024-02-14 | Virtus.pro        | L   | 0.075      | -            | -                | -                | -         |    -0.31 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            4 |     4272 | 2024-02-14 | BetBoom           | W   | 0.074      | -            | -                | -                | 1 (0.074) |     1.38 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            3 |     4353 | 2024-02-09 | 3DMAX             | L   | 0.042      | -            | -                | -                | -         |    -0.19 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            2 |     4356 | 2024-02-09 | ex-Sprout         | L   | 0.041      | -            | -                | -                | -         |    -1.28 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            1 |     4360 | 2024-02-09 | Endpoint          | W   | 0.040      | -            | -                | -                | -         |     0.09 | afro, bodyy, KRIMZ, kyuubii, MATYS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($95,594.17)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.29) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-07-22 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-06-09 |      0.848 | $20,000.00     | $16,950.00      |
| 2024-05-12 |      0.661 | $7,000.00      | $4,625.83       |
| 2024-05-04 |      0.608 | $2,000.00      | $1,215.56       |
| 2024-05-02 |      0.594 | $3,500.00      | $2,080.56       |
| 2024-03-06 |      0.214 | $50,000.00     | $10,722.22      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
