### Roster Details<br />
Team Name: fnatic<br />
Roster: afro, blameF, bodyy, KRIMZ, MATYS<br />
Global Rank: [22](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1402.9<br />
<br />
Final Rank Value (1402.9) = Starting Rank Value (1560.7) + Head To Head Adjustments (-157.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.699[<sup>1</sup>](#table2)
- Bounty Collected: 0.550[<sup>2</sup>](#table1)
- Opponent Network: 0.375[<sup>2</sup>](#table1)
- LAN Wins: 0.646[<sup>2</sup>](#table1)

The average of these factors is 0.568<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1560.7
- 400 + ( ( 0.568 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1560.7


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
|           63 |       31 | 2024-08-03 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -14.41 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           62 |       81 | 2024-08-02 | Nemiga            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.92 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           61 |      112 | 2024-08-01 | G2 Ares           | W   | 1.000      | -            | -                | -                | -         |     0.11 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           60 |      177 | 2024-07-31 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -24.32 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           59 |      269 | 2024-07-28 | Sangal            | L   | 1.000      | -            | -                | -                | -         |   -23.72 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           58 |      281 | 2024-07-28 | SAW               | W   | 1.000      | 0.435        | -                | 0.540 (0.235)    | -         |     5.79 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           57 |      297 | 2024-07-27 | MOUZ NXT          | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     4.10 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           56 |      331 | 2024-07-26 | Sampi             | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     1.32 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           55 |      461 | 2024-07-22 | Passion UA        | W   | 1.000      | 0.500        | 0.172 (0.086)    | 1.000 (0.500)    | -         |     4.38 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           54 |      492 | 2024-07-21 | MOUZ NXT          | W   | 1.000      | 0.500        | 0.139 (0.070)    | 1.000 (0.500)    | -         |     4.22 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           53 |      536 | 2024-07-20 | Sangal            | W   | 1.000      | 0.500        | 0.219 (0.109)    | 0.861 (0.431)    | -         |     6.92 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           52 |      557 | 2024-07-19 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.55 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           51 |      609 | 2024-07-18 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -27.24 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           50 |      734 | 2024-07-16 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.26 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           49 |      986 | 2024-06-16 | 9z                | L   | 0.876      | -            | -                | -                | -         |   -13.62 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           48 |      990 | 2024-06-16 | Ninjas in Pyjamas | W   | 0.874      | 0.548        | 0.255 (0.122)    | 0.553 (0.265)    | 1 (0.874) |    19.19 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           47 |     1014 | 2024-06-15 | RED Canids        | W   | 0.869      | 0.548        | -                | 0.758 (0.361)    | 1 (0.869) |     4.53 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           46 |     1028 | 2024-06-15 | Imperial          | W   | 0.867      | 0.548        | 0.236 (0.112)    | 0.685 (0.326)    | 1 (0.867) |     7.56 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           45 |     1053 | 2024-06-14 | RED Canids        | L   | 0.862      | -            | -                | -                | -         |   -22.62 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           44 |     1336 | 2024-06-07 | Ninjas in Pyjamas | L   | 0.814      | -            | -                | -                | -         |    -8.60 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           43 |     1392 | 2024-06-06 | BIG               | W   | 0.808      | 0.715        | 0.155 (0.090)    | -                | 1 (0.808) |     7.69 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           42 |     1418 | 2024-06-06 | FURIA             | L   | 0.806      | -            | -                | -                | -         |    -8.84 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           41 |     1433 | 2024-06-06 | Complexity        | W   | 0.805      | 0.715        | 0.342 (0.197)    | -                | 1 (0.805) |    19.22 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           40 |     1463 | 2024-06-05 | Eternal Fire      | W   | 0.801      | 0.715        | 0.742 (0.425)    | 0.458 (0.262)    | 1 (0.801) |    19.70 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           39 |     1479 | 2024-06-05 | BetBoom           | L   | 0.799      | -            | -                | -                | -         |   -15.08 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           38 |     1569 | 2024-06-02 | DMS               | L   | 0.779      | -            | -                | -                | -         |   -22.95 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           37 |     1634 | 2024-05-31 | SAW               | W   | 0.766      | -            | -                | -                | -         |     4.56 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           36 |     1635 | 2024-05-31 | Sangal            | W   | 0.766      | -            | -                | -                | -         |     3.17 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           35 |     1971 | 2024-05-18 | ENCE              | L   | 0.679      | -            | -                | -                | -         |   -13.36 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           34 |     1979 | 2024-05-18 | GamerLegion       | L   | 0.678      | -            | -                | -                | -         |   -18.47 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           33 |     2005 | 2024-05-17 | ENCE              | W   | 0.673      | 0.769        | 0.169 (0.087)    | -                | -         |     7.42 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           32 |     2371 | 2024-05-03 | 9 Pandas          | L   | 0.581      | -            | -                | -                | -         |   -17.35 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           31 |     2399 | 2024-05-02 | Sashi             | L   | 0.574      | -            | -                | -                | -         |   -15.41 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           30 |     2427 | 2024-05-01 | AMKAL             | W   | 0.566      | -            | -                | -                | -         |     1.96 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           29 |     2440 | 2024-05-01 | PARIVISION        | W   | 0.565      | -            | -                | -                | -         |     1.48 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           28 |     2463 | 2024-04-30 | Nexus             | W   | 0.558      | -            | -                | -                | -         |     0.36 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           27 |     2522 | 2024-04-27 | Virtus.pro        | L   | 0.539      | -            | -                | -                | -         |    -5.04 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           26 |     2563 | 2024-04-25 | Eternal Fire      | L   | 0.527      | -            | -                | -                | -         |    -4.66 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           25 |     2587 | 2024-04-24 | 3DMAX             | L   | 0.520      | -            | -                | -                | -         |    -6.13 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           24 |     2611 | 2024-04-23 | Virtus.pro        | W   | 0.512      | 0.889        | 0.497 (0.226)    | -                | 1 (0.512) |    11.53 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           23 |     2762 | 2024-04-18 | KOI               | L   | 0.480      | -            | -                | -                | -         |   -14.03 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           22 |     3016 | 2024-04-09 | Apeks             | L   | 0.421      | -            | -                | -                | -         |   -12.87 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           21 |     3050 | 2024-04-08 | Apeks             | W   | 0.414      | -            | -                | -                | -         |     0.35 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           20 |     3056 | 2024-04-08 | KOI               | W   | 0.413      | -            | -                | -                | -         |     0.87 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           19 |     3389 | 2024-03-23 | BetBoom           | L   | 0.305      | -            | -                | -                | -         |    -6.61 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           18 |     3425 | 2024-03-21 | 3DMAX             | W   | 0.293      | -            | -                | -                | -         |     6.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           17 |     3779 | 2024-03-06 | BLEED             | W   | 0.194      | -            | -                | -                | -         |     0.23 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           16 |     3822 | 2024-03-05 | Young Ninjas      | W   | 0.187      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           15 |     3839 | 2024-03-04 | 3DMAX             | W   | 0.179      | -            | -                | -                | -         |     3.83 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           14 |     3856 | 2024-03-03 | Gaimin Gladiators | L   | 0.174      | -            | -                | -                | -         |    -5.27 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           13 |     3861 | 2024-03-03 | AURA              | W   | 0.174      | -            | -                | -                | -         |     0.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           12 |     3871 | 2024-03-03 | ex-Preasy         | W   | 0.173      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           11 |     3908 | 2024-03-01 | ALTERNATE aTTaX   | W   | 0.159      | -            | -                | -                | -         |     0.20 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           10 |     3924 | 2024-02-28 | ex-Preasy         | L   | 0.148      | -            | -                | -                | -         |    -4.59 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            9 |     4040 | 2024-02-23 | GamerLegion       | L   | 0.113      | -            | -                | -                | -         |    -3.52 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            8 |     4185 | 2024-02-17 | SAW               | L   | 0.073      | -            | -                | -                | -         |    -2.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            7 |     4221 | 2024-02-16 | KOI               | L   | 0.065      | -            | -                | -                | -         |    -1.93 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            6 |     4244 | 2024-02-15 | AMKAL             | W   | 0.059      | -            | -                | -                | 1 (0.059) |     0.17 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            5 |     4271 | 2024-02-14 | Virtus.pro        | L   | 0.054      | -            | -                | -                | -         |    -0.53 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            4 |     4281 | 2024-02-14 | BetBoom           | W   | 0.053      | -            | -                | -                | 1 (0.053) |     0.53 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            3 |     4352 | 2024-02-09 | 3DMAX             | L   | 0.021      | -            | -                | -                | -         |    -0.22 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            2 |     4355 | 2024-02-09 | ex-Sprout         | L   | 0.020      | -            | -                | -                | -         |    -0.63 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            1 |     4359 | 2024-02-09 | Endpoint          | W   | 0.019      | -            | -                | -                | -         |     0.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($120,137.22)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.37) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-07-22 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-06-16 |      0.876 | $30,000.00     | $26,269.44      |
| 2024-06-09 |      0.827 | $20,000.00     | $16,531.48      |
| 2024-05-12 |      0.640 | $7,000.00      | $4,479.35       |
| 2024-05-04 |      0.587 | $2,000.00      | $1,173.70       |
| 2024-05-02 |      0.574 | $3,500.00      | $2,007.31       |
| 2024-03-06 |      0.194 | $50,000.00     | $9,675.93       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
