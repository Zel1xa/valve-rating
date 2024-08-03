### Roster Details<br />
Team Name: fnatic<br />
Roster: afro, blameF, bodyy, KRIMZ, MATYS<br />
Global Rank: [22](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1323.0<br />
<br />
Final Rank Value (1323.0) = Starting Rank Value (1362.6) + Head To Head Adjustments (-39.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.650[<sup>1</sup>](#table2)
- Bounty Collected: 0.539[<sup>2</sup>](#table1)
- Opponent Network: 0.343[<sup>2</sup>](#table1)
- LAN Wins: 0.350[<sup>2</sup>](#table1)

The average of these factors is 0.470<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1362.6
- 400 + ( ( 0.470 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1362.6


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
|           57 |       42 | 2024-08-02 | Nemiga            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.52 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           56 |       60 | 2024-08-01 | G2 Ares           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.19 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           55 |      122 | 2024-07-31 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -21.11 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           54 |      212 | 2024-07-28 | Sangal            | L   | 1.000      | -            | -                | -                | -         |   -21.17 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           53 |      224 | 2024-07-28 | SAW               | W   | 1.000      | 0.435        | -                | 0.560 (0.243)    | 0 (0.000) |     8.67 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           52 |      240 | 2024-07-27 | MOUZ NXT          | W   | 1.000      | 0.435        | 0.139 (0.060)    | 1.000 (0.435)    | 0 (0.000) |     6.40 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           51 |      274 | 2024-07-26 | Sampi             | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     2.37 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           50 |      404 | 2024-07-22 | Passion UA        | W   | 1.000      | 0.500        | 0.172 (0.086)    | 1.000 (0.500)    | -         |     6.69 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           49 |      435 | 2024-07-21 | MOUZ NXT          | W   | 1.000      | 0.500        | 0.139 (0.070)    | 1.000 (0.500)    | -         |     6.80 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           48 |      479 | 2024-07-20 | Sangal            | W   | 1.000      | 0.500        | 0.219 (0.109)    | 0.823 (0.411)    | -         |     9.81 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           47 |      500 | 2024-07-19 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     2.81 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           46 |      552 | 2024-07-18 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -24.76 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           45 |      674 | 2024-07-16 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     2.37 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           44 |     1241 | 2024-06-07 | Ninjas in Pyjamas | L   | 0.820      | -            | -                | -                | -         |    -6.16 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           43 |     1296 | 2024-06-06 | BIG               | W   | 0.814      | 0.715        | 0.156 (0.091)    | 0.316 (0.184)    | 1 (0.814) |    12.22 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           42 |     1323 | 2024-06-06 | FURIA             | L   | 0.813      | -            | -                | -                | -         |    -5.32 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           41 |     1338 | 2024-06-06 | Complexity        | W   | 0.811      | 0.715        | 0.313 (0.182)    | 0.394 (0.228)    | 1 (0.811) |    22.14 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           40 |     1368 | 2024-06-05 | Eternal Fire      | W   | 0.807      | 0.715        | 0.746 (0.430)    | 0.474 (0.274)    | 1 (0.807) |    22.48 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           39 |     1384 | 2024-06-05 | BetBoom           | L   | 0.805      | -            | -                | -                | -         |   -10.17 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           38 |     1472 | 2024-06-02 | DMS               | L   | 0.785      | -            | -                | -                | -         |   -21.35 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           37 |     1536 | 2024-05-31 | SAW               | W   | 0.773      | -            | -                | -                | -         |     8.57 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           36 |     1537 | 2024-05-31 | Sangal            | W   | 0.772      | -            | -                | -                | -         |     5.84 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           35 |     1871 | 2024-05-18 | ENCE              | L   | 0.686      | -            | -                | -                | -         |    -9.03 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           34 |     1879 | 2024-05-18 | GamerLegion       | L   | 0.685      | -            | -                | -                | -         |   -15.54 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           33 |     1905 | 2024-05-17 | ENCE              | W   | 0.679      | 0.769        | 0.170 (0.089)    | 0.415 (0.216)    | -         |    12.22 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           32 |     2270 | 2024-05-03 | 9 Pandas          | L   | 0.587      | -            | -                | -                | -         |   -16.17 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           31 |     2298 | 2024-05-02 | Sashi             | L   | 0.580      | -            | -                | -                | -         |   -12.49 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           30 |     2326 | 2024-05-01 | AMKAL             | W   | 0.573      | -            | -                | -                | -         |     4.49 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           29 |     2339 | 2024-05-01 | PARIVISION        | W   | 0.571      | -            | -                | -                | -         |     3.53 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           28 |     2362 | 2024-04-30 | Nexus             | W   | 0.564      | -            | -                | -                | -         |     0.97 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           27 |     2421 | 2024-04-27 | Virtus.pro        | L   | 0.545      | -            | -                | -                | -         |    -2.35 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           26 |     2461 | 2024-04-25 | Eternal Fire      | L   | 0.534      | -            | -                | -                | -         |    -2.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           25 |     2485 | 2024-04-24 | 3DMAX             | L   | 0.526      | -            | -                | -                | -         |    -2.98 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           24 |     2509 | 2024-04-23 | Virtus.pro        | W   | 0.519      | 0.889        | 0.496 (0.229)    | -                | 1 (0.519) |    14.32 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           23 |     2660 | 2024-04-18 | KOI               | L   | 0.486      | -            | -                | -                | -         |   -13.84 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           22 |     2914 | 2024-04-09 | Apeks             | L   | 0.427      | -            | -                | -                | -         |   -12.39 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           21 |     2948 | 2024-04-08 | Apeks             | W   | 0.420      | -            | -                | -                | -         |     0.99 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           20 |     2954 | 2024-04-08 | KOI               | W   | 0.419      | -            | -                | -                | -         |     1.14 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           19 |     3283 | 2024-03-23 | BetBoom           | L   | 0.312      | -            | -                | -                | -         |    -4.17 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           18 |     3318 | 2024-03-21 | 3DMAX             | W   | 0.299      | -            | -                | -                | -         |     7.97 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           17 |     3669 | 2024-03-06 | BLEED             | W   | 0.200      | -            | -                | -                | -         |     0.68 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           16 |     3712 | 2024-03-05 | Young Ninjas      | W   | 0.193      | -            | -                | -                | -         |     0.22 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           15 |     3729 | 2024-03-04 | 3DMAX             | W   | 0.186      | 0.500        | 0.504 (0.047)    | -                | -         |     5.04 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           14 |     3746 | 2024-03-03 | Gaimin Gladiators | L   | 0.180      | -            | -                | -                | -         |    -5.05 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           13 |     3751 | 2024-03-03 | AURA              | W   | 0.180      | -            | -                | -                | -         |     0.05 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           12 |     3761 | 2024-03-03 | ex-Preasy         | W   | 0.179      | -            | -                | -                | -         |     0.22 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           11 |     3798 | 2024-03-01 | ALTERNATE aTTaX   | W   | 0.166      | -            | -                | -                | -         |     0.59 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           10 |     3814 | 2024-02-28 | ex-Preasy         | L   | 0.154      | -            | -                | -                | -         |    -4.66 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            9 |     3930 | 2024-02-23 | GamerLegion       | L   | 0.120      | -            | -                | -                | -         |    -3.62 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            8 |     4074 | 2024-02-17 | SAW               | L   | 0.079      | -            | -                | -                | -         |    -1.86 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            7 |     4110 | 2024-02-16 | KOI               | L   | 0.072      | -            | -                | -                | -         |    -2.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            6 |     4133 | 2024-02-15 | AMKAL             | W   | 0.065      | -            | -                | -                | 1 (0.065) |     0.48 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            5 |     4160 | 2024-02-14 | Virtus.pro        | L   | 0.061      | -            | -                | -                | -         |    -0.24 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            4 |     4170 | 2024-02-14 | BetBoom           | W   | 0.059      | -            | -                | -                | 1 (0.059) |     1.10 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            3 |     4241 | 2024-02-09 | 3DMAX             | L   | 0.027      | -            | -                | -                | -         |    -0.12 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            2 |     4244 | 2024-02-09 | ex-Sprout         | L   | 0.026      | -            | -                | -                | -         |    -0.82 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            1 |     4248 | 2024-02-09 | Endpoint          | W   | 0.026      | -            | -                | -                | -         |     0.05 | afro, bodyy, KRIMZ, kyuubii, MATYS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($94,383.40)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.29) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-07-22 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-06-09 |      0.833 | $20,000.00     | $16,656.48      |
| 2024-05-12 |      0.646 | $7,000.00      | $4,523.10       |
| 2024-05-04 |      0.593 | $2,000.00      | $1,186.20       |
| 2024-05-02 |      0.580 | $3,500.00      | $2,029.19       |
| 2024-03-06 |      0.200 | $50,000.00     | $9,988.43       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
