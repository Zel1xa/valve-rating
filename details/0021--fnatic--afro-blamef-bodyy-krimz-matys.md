### Roster Details<br />
Team Name: fnatic<br />
Roster: afro, blameF, bodyy, KRIMZ, MATYS<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1406.3<br />
<br />
Final Rank Value (1406.3) = Starting Rank Value (1558.1) + Head To Head Adjustments (-151.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.699[<sup>1</sup>](#table2)
- Bounty Collected: 0.551[<sup>2</sup>](#table1)
- Opponent Network: 0.363[<sup>2</sup>](#table1)
- LAN Wins: 0.638[<sup>2</sup>](#table1)

The average of these factors is 0.563<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1558.1
- 400 + ( ( 0.563 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1558.1


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
|           63 |       82 | 2024-08-03 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -14.14 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           62 |      133 | 2024-08-02 | Nemiga            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.94 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           61 |      163 | 2024-08-01 | G2 Ares           | W   | 1.000      | -            | -                | -                | -         |     0.11 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           60 |      228 | 2024-07-31 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -24.28 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           59 |      320 | 2024-07-28 | Sangal            | L   | 1.000      | -            | -                | -                | -         |   -23.31 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           58 |      332 | 2024-07-28 | SAW               | W   | 1.000      | 0.435        | -                | 0.516 (0.224)    | -         |     5.78 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           57 |      348 | 2024-07-27 | MOUZ NXT          | W   | 1.000      | 0.435        | -                | 0.961 (0.418)    | -         |     4.24 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           56 |      382 | 2024-07-26 | Sampi             | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     1.41 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           55 |      512 | 2024-07-22 | Passion UA        | W   | 1.000      | 0.500        | 0.173 (0.087)    | 1.000 (0.500)    | -         |     4.51 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           54 |      543 | 2024-07-21 | MOUZ NXT          | W   | 1.000      | 0.500        | 0.139 (0.069)    | 0.961 (0.481)    | -         |     4.35 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           53 |      587 | 2024-07-20 | Sangal            | W   | 1.000      | 0.500        | 0.288 (0.144)    | 0.858 (0.429)    | -         |     7.38 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           52 |      608 | 2024-07-19 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.56 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           51 |      660 | 2024-07-18 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -27.11 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           50 |      785 | 2024-07-16 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.27 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           49 |     1037 | 2024-06-16 | 9z                | L   | 0.862      | -            | -                | -                | -         |   -13.58 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           48 |     1041 | 2024-06-16 | Ninjas in Pyjamas | W   | 0.861      | 0.548        | 0.253 (0.120)    | 0.531 (0.251)    | 1 (0.861) |    18.86 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           47 |     1065 | 2024-06-15 | RED Canids        | W   | 0.855      | 0.548        | -                | 0.732 (0.343)    | 1 (0.855) |     4.31 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           46 |     1079 | 2024-06-15 | Imperial          | W   | 0.853      | 0.548        | 0.233 (0.109)    | 0.658 (0.308)    | 1 (0.853) |     7.19 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           45 |     1104 | 2024-06-14 | RED Canids        | L   | 0.848      | -            | -                | -                | -         |   -22.43 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           44 |     1387 | 2024-06-07 | Ninjas in Pyjamas | L   | 0.800      | -            | -                | -                | -         |    -8.49 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           43 |     1443 | 2024-06-06 | BIG               | W   | 0.794      | 0.715        | 0.154 (0.087)    | -                | 1 (0.794) |     7.44 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           42 |     1469 | 2024-06-06 | FURIA             | L   | 0.793      | -            | -                | -                | -         |    -8.67 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           41 |     1484 | 2024-06-06 | Complexity        | W   | 0.791      | 0.715        | 0.341 (0.193)    | -                | 1 (0.791) |    18.74 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           40 |     1514 | 2024-06-05 | Eternal Fire      | W   | 0.787      | 0.715        | 0.738 (0.416)    | 0.438 (0.246)    | 1 (0.787) |    19.26 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           39 |     1530 | 2024-06-05 | BetBoom           | L   | 0.786      | -            | -                | -                | -         |   -15.00 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           38 |     1620 | 2024-06-02 | DMS               | L   | 0.765      | -            | -                | -                | -         |   -22.54 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           37 |     1685 | 2024-05-31 | SAW               | W   | 0.753      | -            | -                | -                | -         |     4.34 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           36 |     1686 | 2024-05-31 | Sangal            | W   | 0.752      | -            | -                | -                | -         |     3.46 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           35 |     2022 | 2024-05-18 | ENCE              | L   | 0.666      | -            | -                | -                | -         |   -12.81 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           34 |     2030 | 2024-05-18 | GamerLegion       | L   | 0.665      | -            | -                | -                | -         |   -18.16 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           33 |     2056 | 2024-05-17 | ENCE              | W   | 0.659      | 0.769        | 0.173 (0.088)    | -                | -         |     7.57 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           32 |     2422 | 2024-05-03 | 9 Pandas          | L   | 0.567      | -            | -                | -                | -         |   -16.92 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           31 |     2450 | 2024-05-02 | Sashi             | L   | 0.560      | -            | -                | -                | -         |   -15.05 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           30 |     2478 | 2024-05-01 | AMKAL             | W   | 0.553      | -            | -                | -                | -         |     1.92 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           29 |     2491 | 2024-05-01 | PARIVISION        | W   | 0.551      | -            | -                | -                | -         |     1.74 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           28 |     2514 | 2024-04-30 | Nexus             | W   | 0.544      | -            | -                | -                | -         |     0.37 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           27 |     2573 | 2024-04-27 | Virtus.pro        | L   | 0.525      | -            | -                | -                | -         |    -5.00 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           26 |     2614 | 2024-04-25 | Eternal Fire      | L   | 0.514      | -            | -                | -                | -         |    -4.58 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           25 |     2638 | 2024-04-24 | 3DMAX             | L   | 0.506      | -            | -                | -                | -         |    -5.80 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           24 |     2662 | 2024-04-23 | Virtus.pro        | W   | 0.499      | 0.889        | 0.499 (0.221)    | -                | 1 (0.499) |    11.15 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           23 |     2813 | 2024-04-18 | KOI               | L   | 0.467      | -            | -                | -                | -         |   -13.65 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           22 |     3067 | 2024-04-09 | Apeks             | L   | 0.407      | -            | -                | -                | -         |   -12.46 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           21 |     3101 | 2024-04-08 | Apeks             | W   | 0.400      | -            | -                | -                | -         |     0.33 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           20 |     3107 | 2024-04-08 | KOI               | W   | 0.399      | -            | -                | -                | -         |     0.82 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           19 |     3440 | 2024-03-23 | BetBoom           | L   | 0.292      | -            | -                | -                | -         |    -6.38 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           18 |     3476 | 2024-03-21 | 3DMAX             | W   | 0.279      | -            | -                | -                | -         |     5.82 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           17 |     3830 | 2024-03-06 | BLEED             | W   | 0.180      | -            | -                | -                | -         |     0.22 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           16 |     3873 | 2024-03-05 | Young Ninjas      | W   | 0.173      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           15 |     3890 | 2024-03-04 | 3DMAX             | W   | 0.166      | -            | -                | -                | -         |     3.58 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           14 |     3907 | 2024-03-03 | Gaimin Gladiators | L   | 0.160      | -            | -                | -                | -         |    -4.86 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           13 |     3912 | 2024-03-03 | AURA              | W   | 0.160      | -            | -                | -                | -         |     0.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           12 |     3922 | 2024-03-03 | ex-Preasy         | W   | 0.159      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           11 |     3959 | 2024-03-01 | ALTERNATE aTTaX   | W   | 0.146      | -            | -                | -                | -         |     0.19 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           10 |     3975 | 2024-02-28 | ex-Preasy         | L   | 0.134      | -            | -                | -                | -         |    -4.17 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            9 |     4091 | 2024-02-23 | GamerLegion       | L   | 0.100      | -            | -                | -                | -         |    -3.10 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            8 |     4236 | 2024-02-17 | SAW               | L   | 0.059      | -            | -                | -                | -         |    -1.69 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            7 |     4272 | 2024-02-16 | KOI               | L   | 0.052      | -            | -                | -                | -         |    -1.52 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            6 |     4295 | 2024-02-15 | AMKAL             | W   | 0.045      | -            | -                | -                | 1 (0.045) |     0.13 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            5 |     4322 | 2024-02-14 | Virtus.pro        | L   | 0.041      | -            | -                | -                | -         |    -0.40 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            4 |     4332 | 2024-02-14 | BetBoom           | W   | 0.039      | -            | -                | -                | 1 (0.039) |     0.39 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            3 |     4403 | 2024-02-09 | 3DMAX             | L   | 0.007      | -            | -                | -                | -         |    -0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            2 |     4406 | 2024-02-09 | ex-Sprout         | L   | 0.006      | -            | -                | -                | -         |    -0.20 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            1 |     4410 | 2024-02-09 | Endpoint          | W   | 0.006      | -            | -                | -                | -         |     0.00 | afro, bodyy, KRIMZ, kyuubii, MATYS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($118,600.76)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.37) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-07-22 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-06-16 |      0.862 | $30,000.00     | $25,859.72      |
| 2024-06-09 |      0.813 | $20,000.00     | $16,258.33      |
| 2024-05-12 |      0.626 | $7,000.00      | $4,383.75       |
| 2024-05-04 |      0.573 | $2,000.00      | $1,146.39       |
| 2024-05-02 |      0.560 | $3,500.00      | $1,959.51       |
| 2024-03-06 |      0.180 | $50,000.00     | $8,993.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
