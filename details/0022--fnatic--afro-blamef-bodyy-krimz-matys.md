### Roster Details<br />
Team Name: fnatic<br />
Roster: afro, blameF, bodyy, KRIMZ, MATYS<br />
Global Rank: [22](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1414.6<br />
<br />
Final Rank Value (1414.6) = Starting Rank Value (1560.2) + Head To Head Adjustments (-145.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.699[<sup>1</sup>](#table2)
- Bounty Collected: 0.548[<sup>2</sup>](#table1)
- Opponent Network: 0.375[<sup>2</sup>](#table1)
- LAN Wins: 0.649[<sup>2</sup>](#table1)

The average of these factors is 0.568<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1560.2
- 400 + ( ( 0.568 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1560.2


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
|           62 |       50 | 2024-08-02 | Nemiga            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.73 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           61 |       80 | 2024-08-01 | G2 Ares           | W   | 1.000      | -            | -                | -                | -         |     0.11 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           60 |      144 | 2024-07-31 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -24.41 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           59 |      235 | 2024-07-28 | Sangal            | L   | 1.000      | -            | -                | -                | -         |   -23.72 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           58 |      247 | 2024-07-28 | SAW               | W   | 1.000      | 0.435        | -                | 0.541 (0.235)    | -         |     5.72 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           57 |      263 | 2024-07-27 | MOUZ NXT          | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     4.12 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           56 |      297 | 2024-07-26 | Sampi             | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     1.36 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           55 |      427 | 2024-07-22 | Passion UA        | W   | 1.000      | 0.500        | 0.172 (0.086)    | 1.000 (0.500)    | -         |     4.24 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           54 |      458 | 2024-07-21 | MOUZ NXT          | W   | 1.000      | 0.500        | 0.139 (0.070)    | 1.000 (0.500)    | -         |     4.24 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           53 |      502 | 2024-07-20 | Sangal            | W   | 1.000      | 0.500        | 0.219 (0.109)    | 0.862 (0.431)    | -         |     6.91 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           52 |      523 | 2024-07-19 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.56 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           51 |      576 | 2024-07-18 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -27.21 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           50 |      700 | 2024-07-16 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.27 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           49 |      951 | 2024-06-16 | 9z                | L   | 0.880      | -            | -                | -                | -         |   -13.70 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           48 |      955 | 2024-06-16 | Ninjas in Pyjamas | W   | 0.879      | 0.548        | 0.223 (0.107)    | 0.553 (0.267)    | 1 (0.879) |    19.03 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           47 |      979 | 2024-06-15 | RED Canids        | W   | 0.873      | 0.548        | -                | 0.743 (0.356)    | 1 (0.873) |     4.61 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           46 |      993 | 2024-06-15 | Imperial          | W   | 0.871      | 0.548        | 0.238 (0.113)    | 0.685 (0.327)    | 1 (0.871) |     7.72 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           45 |     1018 | 2024-06-14 | RED Canids        | L   | 0.866      | -            | -                | -                | -         |   -22.67 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           44 |     1301 | 2024-06-07 | Ninjas in Pyjamas | L   | 0.819      | -            | -                | -                | -         |    -8.93 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           43 |     1357 | 2024-06-06 | BIG               | W   | 0.812      | 0.715        | 0.155 (0.090)    | -                | 1 (0.812) |     7.79 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           42 |     1383 | 2024-06-06 | FURIA             | L   | 0.811      | -            | -                | -                | -         |    -8.95 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           41 |     1398 | 2024-06-06 | Complexity        | W   | 0.810      | 0.715        | 0.311 (0.180)    | -                | 1 (0.810) |    19.11 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           40 |     1428 | 2024-06-05 | Eternal Fire      | W   | 0.805      | 0.715        | 0.743 (0.428)    | 0.458 (0.264)    | 1 (0.805) |    19.76 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           39 |     1444 | 2024-06-05 | BetBoom           | L   | 0.804      | -            | -                | -                | -         |   -15.07 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           38 |     1534 | 2024-06-02 | DMS               | L   | 0.784      | -            | -                | -                | -         |   -23.07 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           37 |     1599 | 2024-05-31 | SAW               | W   | 0.771      | -            | -                | -                | -         |     4.63 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           36 |     1600 | 2024-05-31 | Sangal            | W   | 0.771      | -            | -                | -                | -         |     3.18 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           35 |     1936 | 2024-05-18 | ENCE              | L   | 0.684      | -            | -                | -                | -         |   -13.46 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           34 |     1944 | 2024-05-18 | GamerLegion       | L   | 0.683      | -            | -                | -                | -         |   -18.55 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           33 |     1970 | 2024-05-17 | ENCE              | W   | 0.677      | 0.769        | 0.170 (0.088)    | -                | -         |     7.46 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           32 |     2336 | 2024-05-03 | 9 Pandas          | L   | 0.585      | -            | -                | -                | -         |   -17.45 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           31 |     2364 | 2024-05-02 | Sashi             | L   | 0.578      | -            | -                | -                | -         |   -15.54 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           30 |     2392 | 2024-05-01 | AMKAL             | W   | 0.571      | -            | -                | -                | -         |     2.00 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           29 |     2405 | 2024-05-01 | PARIVISION        | W   | 0.569      | -            | -                | -                | -         |     1.49 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           28 |     2428 | 2024-04-30 | Nexus             | W   | 0.563      | -            | -                | -                | -         |     0.37 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           27 |     2487 | 2024-04-27 | Virtus.pro        | L   | 0.543      | -            | -                | -                | -         |    -5.11 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           26 |     2527 | 2024-04-25 | Eternal Fire      | L   | 0.532      | -            | -                | -                | -         |    -4.69 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           25 |     2551 | 2024-04-24 | 3DMAX             | L   | 0.524      | -            | -                | -                | -         |    -6.21 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           24 |     2575 | 2024-04-23 | Virtus.pro        | W   | 0.517      | 0.889        | 0.496 (0.228)    | -                | 1 (0.517) |    11.61 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           23 |     2726 | 2024-04-18 | KOI               | L   | 0.485      | -            | -                | -                | -         |   -14.15 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           22 |     2980 | 2024-04-09 | Apeks             | L   | 0.425      | -            | -                | -                | -         |   -13.00 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           21 |     3014 | 2024-04-08 | Apeks             | W   | 0.419      | -            | -                | -                | -         |     0.36 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           20 |     3020 | 2024-04-08 | KOI               | W   | 0.418      | -            | -                | -                | -         |     0.89 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           19 |     3353 | 2024-03-23 | BetBoom           | L   | 0.310      | -            | -                | -                | -         |    -6.68 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           18 |     3389 | 2024-03-21 | 3DMAX             | W   | 0.298      | -            | -                | -                | -         |     6.09 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           17 |     3742 | 2024-03-06 | BLEED             | W   | 0.198      | -            | -                | -                | -         |     0.24 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           16 |     3785 | 2024-03-05 | Young Ninjas      | W   | 0.191      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           15 |     3802 | 2024-03-04 | 3DMAX             | W   | 0.184      | -            | -                | -                | -         |     3.93 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           14 |     3819 | 2024-03-03 | Gaimin Gladiators | L   | 0.179      | -            | -                | -                | -         |    -5.41 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           13 |     3824 | 2024-03-03 | AURA              | W   | 0.178      | -            | -                | -                | -         |     0.02 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           12 |     3834 | 2024-03-03 | ex-Preasy         | W   | 0.177      | -            | -                | -                | -         |     0.08 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           11 |     3871 | 2024-03-01 | ALTERNATE aTTaX   | W   | 0.164      | -            | -                | -                | -         |     0.21 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           10 |     3887 | 2024-02-28 | ex-Preasy         | L   | 0.152      | -            | -                | -                | -         |    -4.73 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            9 |     4003 | 2024-02-23 | GamerLegion       | L   | 0.118      | -            | -                | -                | -         |    -3.66 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            8 |     4147 | 2024-02-17 | SAW               | L   | 0.078      | -            | -                | -                | -         |    -2.20 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            7 |     4183 | 2024-02-16 | KOI               | L   | 0.070      | -            | -                | -                | -         |    -2.06 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            6 |     4206 | 2024-02-15 | AMKAL             | W   | 0.064      | -            | -                | -                | 1 (0.064) |     0.18 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            5 |     4233 | 2024-02-14 | Virtus.pro        | L   | 0.059      | -            | -                | -                | -         |    -0.58 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            4 |     4243 | 2024-02-14 | BetBoom           | W   | 0.058      | -            | -                | -                | 1 (0.058) |     0.58 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            3 |     4314 | 2024-02-09 | 3DMAX             | L   | 0.025      | -            | -                | -                | -         |    -0.27 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            2 |     4317 | 2024-02-09 | ex-Sprout         | L   | 0.024      | -            | -                | -                | -         |    -0.77 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            1 |     4321 | 2024-02-09 | Endpoint          | W   | 0.024      | -            | -                | -                | -         |     0.02 | afro, bodyy, KRIMZ, kyuubii, MATYS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($120,647.64)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.37) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-07-22 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-06-16 |      0.880 | $30,000.00     | $26,405.56      |
| 2024-06-09 |      0.831 | $20,000.00     | $16,622.22      |
| 2024-05-12 |      0.644 | $7,000.00      | $4,511.11       |
| 2024-05-04 |      0.591 | $2,000.00      | $1,182.78       |
| 2024-05-02 |      0.578 | $3,500.00      | $2,023.19       |
| 2024-03-06 |      0.198 | $50,000.00     | $9,902.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
