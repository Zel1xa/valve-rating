### Roster Details<br />
Team Name: fnatic<br />
Roster: afro, blameF, bodyy, KRIMZ, MATYS<br />
Global Rank: [22](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1403.1<br />
<br />
Final Rank Value (1403.1) = Starting Rank Value (1559.9) + Head To Head Adjustments (-156.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.699[<sup>1</sup>](#table2)
- Bounty Collected: 0.550[<sup>2</sup>](#table1)
- Opponent Network: 0.374[<sup>2</sup>](#table1)
- LAN Wins: 0.645[<sup>2</sup>](#table1)

The average of these factors is 0.567<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1559.9
- 400 + ( ( 0.567 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1559.9


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
|           63 |       36 | 2024-08-03 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -14.37 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           62 |       86 | 2024-08-02 | Nemiga            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.91 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           61 |      117 | 2024-08-01 | G2 Ares           | W   | 1.000      | -            | -                | -                | -         |     0.11 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           60 |      182 | 2024-07-31 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -24.33 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           59 |      274 | 2024-07-28 | Sangal            | L   | 1.000      | -            | -                | -                | -         |   -23.71 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           58 |      286 | 2024-07-28 | SAW               | W   | 1.000      | 0.435        | -                | 0.539 (0.234)    | -         |     5.77 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           57 |      302 | 2024-07-27 | MOUZ NXT          | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     4.10 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           56 |      336 | 2024-07-26 | Sampi             | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     1.32 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           55 |      466 | 2024-07-22 | Passion UA        | W   | 1.000      | 0.500        | 0.172 (0.086)    | 1.000 (0.500)    | -         |     4.38 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           54 |      497 | 2024-07-21 | MOUZ NXT          | W   | 1.000      | 0.500        | 0.139 (0.069)    | 1.000 (0.500)    | -         |     4.21 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           53 |      541 | 2024-07-20 | Sangal            | W   | 1.000      | 0.500        | 0.219 (0.109)    | 0.861 (0.431)    | -         |     6.93 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           52 |      562 | 2024-07-19 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.55 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           51 |      614 | 2024-07-18 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -27.24 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           50 |      739 | 2024-07-16 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.26 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           49 |      991 | 2024-06-16 | 9z                | L   | 0.873      | -            | -                | -                | -         |   -13.60 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           48 |      995 | 2024-06-16 | Ninjas in Pyjamas | W   | 0.872      | 0.548        | 0.254 (0.122)    | 0.553 (0.264)    | 1 (0.872) |    19.14 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           47 |     1019 | 2024-06-15 | RED Canids        | W   | 0.866      | 0.548        | -                | 0.758 (0.360)    | 1 (0.866) |     4.49 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           46 |     1033 | 2024-06-15 | Imperial          | W   | 0.864      | 0.548        | 0.236 (0.112)    | 0.685 (0.325)    | 1 (0.864) |     7.50 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           45 |     1058 | 2024-06-14 | RED Canids        | L   | 0.859      | -            | -                | -                | -         |   -22.57 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           44 |     1341 | 2024-06-07 | Ninjas in Pyjamas | L   | 0.811      | -            | -                | -                | -         |    -8.55 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           43 |     1397 | 2024-06-06 | BIG               | W   | 0.805      | 0.715        | 0.155 (0.089)    | -                | 1 (0.805) |     7.64 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           42 |     1423 | 2024-06-06 | FURIA             | L   | 0.804      | -            | -                | -                | -         |    -8.79 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           41 |     1438 | 2024-06-06 | Complexity        | W   | 0.802      | 0.715        | 0.342 (0.196)    | -                | 1 (0.802) |    19.13 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           40 |     1468 | 2024-06-05 | Eternal Fire      | W   | 0.798      | 0.715        | 0.741 (0.423)    | 0.457 (0.261)    | 1 (0.798) |    19.61 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           39 |     1484 | 2024-06-05 | BetBoom           | L   | 0.797      | -            | -                | -                | -         |   -15.06 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           38 |     1574 | 2024-06-02 | DMS               | L   | 0.776      | -            | -                | -                | -         |   -22.88 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           37 |     1639 | 2024-05-31 | SAW               | W   | 0.764      | -            | -                | -                | -         |     4.51 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           36 |     1640 | 2024-05-31 | Sangal            | W   | 0.763      | -            | -                | -                | -         |     3.17 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           35 |     1976 | 2024-05-18 | ENCE              | L   | 0.677      | -            | -                | -                | -         |   -13.16 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           34 |     1984 | 2024-05-18 | GamerLegion       | L   | 0.676      | -            | -                | -                | -         |   -18.39 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           33 |     2010 | 2024-05-17 | ENCE              | W   | 0.670      | 0.769        | 0.168 (0.087)    | -                | -         |     7.54 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           32 |     2376 | 2024-05-03 | 9 Pandas          | L   | 0.578      | -            | -                | -                | -         |   -17.27 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           31 |     2404 | 2024-05-02 | Sashi             | L   | 0.571      | -            | -                | -                | -         |   -15.34 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           30 |     2432 | 2024-05-01 | AMKAL             | W   | 0.564      | -            | -                | -                | -         |     1.95 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           29 |     2445 | 2024-05-01 | PARIVISION        | W   | 0.562      | -            | -                | -                | -         |     1.48 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           28 |     2468 | 2024-04-30 | Nexus             | W   | 0.555      | -            | -                | -                | -         |     0.36 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           27 |     2527 | 2024-04-27 | Virtus.pro        | L   | 0.536      | -            | -                | -                | -         |    -5.03 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           26 |     2568 | 2024-04-25 | Eternal Fire      | L   | 0.525      | -            | -                | -                | -         |    -4.65 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           25 |     2592 | 2024-04-24 | 3DMAX             | L   | 0.517      | -            | -                | -                | -         |    -6.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           24 |     2616 | 2024-04-23 | Virtus.pro        | W   | 0.510      | 0.889        | 0.497 (0.225)    | -                | 1 (0.510) |    11.46 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           23 |     2767 | 2024-04-18 | KOI               | L   | 0.477      | -            | -                | -                | -         |   -13.95 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           22 |     3021 | 2024-04-09 | Apeks             | L   | 0.418      | -            | -                | -                | -         |   -12.79 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           21 |     3055 | 2024-04-08 | Apeks             | W   | 0.411      | -            | -                | -                | -         |     0.35 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           20 |     3061 | 2024-04-08 | KOI               | W   | 0.410      | -            | -                | -                | -         |     0.86 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           19 |     3394 | 2024-03-23 | BetBoom           | L   | 0.303      | -            | -                | -                | -         |    -6.56 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           18 |     3430 | 2024-03-21 | 3DMAX             | W   | 0.290      | -            | -                | -                | -         |     5.97 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           17 |     3784 | 2024-03-06 | BLEED             | W   | 0.191      | -            | -                | -                | -         |     0.23 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           16 |     3827 | 2024-03-05 | Young Ninjas      | W   | 0.184      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           15 |     3844 | 2024-03-04 | 3DMAX             | W   | 0.177      | -            | -                | -                | -         |     3.78 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           14 |     3861 | 2024-03-03 | Gaimin Gladiators | L   | 0.171      | -            | -                | -                | -         |    -5.19 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           13 |     3866 | 2024-03-03 | AURA              | W   | 0.171      | -            | -                | -                | -         |     0.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           12 |     3876 | 2024-03-03 | ex-Preasy         | W   | 0.170      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           11 |     3913 | 2024-03-01 | ALTERNATE aTTaX   | W   | 0.157      | -            | -                | -                | -         |     0.20 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           10 |     3929 | 2024-02-28 | ex-Preasy         | L   | 0.145      | -            | -                | -                | -         |    -4.51 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            9 |     4045 | 2024-02-23 | GamerLegion       | L   | 0.111      | -            | -                | -                | -         |    -3.44 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            8 |     4190 | 2024-02-17 | SAW               | L   | 0.070      | -            | -                | -                | -         |    -2.00 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            7 |     4226 | 2024-02-16 | KOI               | L   | 0.063      | -            | -                | -                | -         |    -1.85 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            6 |     4249 | 2024-02-15 | AMKAL             | W   | 0.056      | -            | -                | -                | 1 (0.056) |     0.16 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            5 |     4276 | 2024-02-14 | Virtus.pro        | L   | 0.052      | -            | -                | -                | -         |    -0.50 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            4 |     4286 | 2024-02-14 | BetBoom           | W   | 0.050      | -            | -                | -                | 1 (0.050) |     0.50 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            3 |     4357 | 2024-02-09 | 3DMAX             | L   | 0.018      | -            | -                | -                | -         |    -0.19 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            2 |     4360 | 2024-02-09 | ex-Sprout         | L   | 0.017      | -            | -                | -                | -         |    -0.54 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            1 |     4364 | 2024-02-09 | Endpoint          | W   | 0.017      | -            | -                | -                | -         |     0.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($119,835.14)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.37) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-07-22 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-06-16 |      0.873 | $30,000.00     | $26,188.89      |
| 2024-06-09 |      0.824 | $20,000.00     | $16,477.78      |
| 2024-05-12 |      0.637 | $7,000.00      | $4,460.56       |
| 2024-05-04 |      0.584 | $2,000.00      | $1,168.33       |
| 2024-05-02 |      0.571 | $3,500.00      | $1,997.92       |
| 2024-03-06 |      0.191 | $50,000.00     | $9,541.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
