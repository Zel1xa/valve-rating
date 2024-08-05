### Roster Details<br />
Team Name: fnatic<br />
Roster: afro, blameF, bodyy, KRIMZ, MATYS<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1404.0<br />
<br />
Final Rank Value (1404.0) = Starting Rank Value (1558.8) + Head To Head Adjustments (-154.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.699[<sup>1</sup>](#table2)
- Bounty Collected: 0.549[<sup>2</sup>](#table1)
- Opponent Network: 0.370[<sup>2</sup>](#table1)
- LAN Wins: 0.642[<sup>2</sup>](#table1)

The average of these factors is 0.565<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1558.8
- 400 + ( ( 0.565 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1558.8


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
|           63 |       58 | 2024-08-03 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -14.24 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           62 |      109 | 2024-08-02 | Nemiga            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.94 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           61 |      139 | 2024-08-01 | G2 Ares           | W   | 1.000      | -            | -                | -                | -         |     0.11 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           60 |      204 | 2024-07-31 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -24.31 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           59 |      296 | 2024-07-28 | Sangal            | L   | 1.000      | -            | -                | -                | -         |   -23.66 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           58 |      308 | 2024-07-28 | SAW               | W   | 1.000      | 0.435        | -                | 0.530 (0.230)    | -         |     5.76 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           57 |      324 | 2024-07-27 | MOUZ NXT          | W   | 1.000      | 0.435        | -                | 0.987 (0.429)    | -         |     4.16 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           56 |      358 | 2024-07-26 | Sampi             | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     1.35 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           55 |      488 | 2024-07-22 | Passion UA        | W   | 1.000      | 0.500        | 0.173 (0.086)    | 1.000 (0.500)    | -         |     4.43 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           54 |      519 | 2024-07-21 | MOUZ NXT          | W   | 1.000      | 0.500        | 0.139 (0.069)    | 0.987 (0.494)    | -         |     4.28 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           53 |      563 | 2024-07-20 | Sangal            | W   | 1.000      | 0.500        | 0.219 (0.109)    | 0.866 (0.433)    | -         |     6.99 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           52 |      584 | 2024-07-19 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.56 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           51 |      636 | 2024-07-18 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -27.21 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           50 |      761 | 2024-07-16 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.27 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           49 |     1013 | 2024-06-16 | 9z                | L   | 0.868      | -            | -                | -                | -         |   -13.58 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           48 |     1017 | 2024-06-16 | Ninjas in Pyjamas | W   | 0.867      | 0.548        | 0.254 (0.121)    | 0.544 (0.259)    | 1 (0.867) |    19.04 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           47 |     1041 | 2024-06-15 | RED Canids        | W   | 0.861      | 0.548        | -                | 0.748 (0.353)    | 1 (0.861) |     4.42 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           46 |     1055 | 2024-06-15 | Imperial          | W   | 0.859      | 0.548        | 0.234 (0.110)    | 0.674 (0.318)    | 1 (0.859) |     7.37 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           45 |     1080 | 2024-06-14 | RED Canids        | L   | 0.854      | -            | -                | -                | -         |   -22.50 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           44 |     1363 | 2024-06-07 | Ninjas in Pyjamas | L   | 0.806      | -            | -                | -                | -         |    -8.50 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           43 |     1419 | 2024-06-06 | BIG               | W   | 0.800      | 0.715        | 0.154 (0.088)    | -                | 1 (0.800) |     7.57 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           42 |     1445 | 2024-06-06 | FURIA             | L   | 0.799      | -            | -                | -                | -         |    -8.69 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           41 |     1460 | 2024-06-06 | Complexity        | W   | 0.798      | 0.715        | 0.342 (0.195)    | -                | 1 (0.798) |    18.97 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           40 |     1490 | 2024-06-05 | Eternal Fire      | W   | 0.793      | 0.715        | 0.740 (0.420)    | 0.449 (0.255)    | 1 (0.793) |    19.46 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           39 |     1506 | 2024-06-05 | BetBoom           | L   | 0.792      | -            | -                | -                | -         |   -15.03 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           38 |     1596 | 2024-06-02 | DMS               | L   | 0.772      | -            | -                | -                | -         |   -22.72 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           37 |     1661 | 2024-05-31 | SAW               | W   | 0.759      | -            | -                | -                | -         |     4.43 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           36 |     1662 | 2024-05-31 | Sangal            | W   | 0.759      | -            | -                | -                | -         |     3.20 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           35 |     1998 | 2024-05-18 | ENCE              | L   | 0.672      | -            | -                | -                | -         |   -12.98 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           34 |     2006 | 2024-05-18 | GamerLegion       | L   | 0.671      | -            | -                | -                | -         |   -18.28 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           33 |     2032 | 2024-05-17 | ENCE              | W   | 0.665      | 0.769        | 0.174 (0.089)    | -                | -         |     7.58 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           32 |     2398 | 2024-05-03 | 9 Pandas          | L   | 0.573      | -            | -                | -                | -         |   -17.13 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           31 |     2426 | 2024-05-02 | Sashi             | L   | 0.566      | -            | -                | -                | -         |   -15.21 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           30 |     2454 | 2024-05-01 | AMKAL             | W   | 0.559      | -            | -                | -                | -         |     1.93 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           29 |     2467 | 2024-05-01 | PARIVISION        | W   | 0.557      | -            | -                | -                | -         |     1.50 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           28 |     2490 | 2024-04-30 | Nexus             | W   | 0.550      | -            | -                | -                | -         |     0.36 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           27 |     2549 | 2024-04-27 | Virtus.pro        | L   | 0.531      | -            | -                | -                | -         |    -5.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           26 |     2590 | 2024-04-25 | Eternal Fire      | L   | 0.520      | -            | -                | -                | -         |    -4.61 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           25 |     2614 | 2024-04-24 | 3DMAX             | L   | 0.512      | -            | -                | -                | -         |    -5.93 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           24 |     2638 | 2024-04-23 | Virtus.pro        | W   | 0.505      | 0.889        | 0.498 (0.223)    | -                | 1 (0.505) |    11.33 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           23 |     2789 | 2024-04-18 | KOI               | L   | 0.473      | -            | -                | -                | -         |   -13.82 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           22 |     3043 | 2024-04-09 | Apeks             | L   | 0.413      | -            | -                | -                | -         |   -12.65 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           21 |     3077 | 2024-04-08 | Apeks             | W   | 0.407      | -            | -                | -                | -         |     0.34 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           20 |     3083 | 2024-04-08 | KOI               | W   | 0.406      | -            | -                | -                | -         |     0.85 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           19 |     3416 | 2024-03-23 | BetBoom           | L   | 0.298      | -            | -                | -                | -         |    -6.47 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           18 |     3452 | 2024-03-21 | 3DMAX             | W   | 0.286      | -            | -                | -                | -         |     5.92 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           17 |     3806 | 2024-03-06 | BLEED             | W   | 0.186      | -            | -                | -                | -         |     0.22 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           16 |     3849 | 2024-03-05 | Young Ninjas      | W   | 0.179      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           15 |     3866 | 2024-03-04 | 3DMAX             | W   | 0.172      | -            | -                | -                | -         |     3.70 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           14 |     3883 | 2024-03-03 | Gaimin Gladiators | L   | 0.167      | -            | -                | -                | -         |    -5.05 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           13 |     3888 | 2024-03-03 | AURA              | W   | 0.166      | -            | -                | -                | -         |     0.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           12 |     3898 | 2024-03-03 | ex-Preasy         | W   | 0.165      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           11 |     3935 | 2024-03-01 | ALTERNATE aTTaX   | W   | 0.152      | -            | -                | -                | -         |     0.19 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           10 |     3951 | 2024-02-28 | ex-Preasy         | L   | 0.140      | -            | -                | -                | -         |    -4.36 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            9 |     4067 | 2024-02-23 | GamerLegion       | L   | 0.106      | -            | -                | -                | -         |    -3.29 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            8 |     4212 | 2024-02-17 | SAW               | L   | 0.066      | -            | -                | -                | -         |    -1.86 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            7 |     4248 | 2024-02-16 | KOI               | L   | 0.058      | -            | -                | -                | -         |    -1.70 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            6 |     4271 | 2024-02-15 | AMKAL             | W   | 0.052      | -            | -                | -                | 1 (0.052) |     0.14 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            5 |     4298 | 2024-02-14 | Virtus.pro        | L   | 0.047      | -            | -                | -                | -         |    -0.46 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            4 |     4308 | 2024-02-14 | BetBoom           | W   | 0.046      | -            | -                | -                | 1 (0.046) |     0.45 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            3 |     4379 | 2024-02-09 | 3DMAX             | L   | 0.013      | -            | -                | -                | -         |    -0.14 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            2 |     4382 | 2024-02-09 | ex-Sprout         | L   | 0.012      | -            | -                | -                | -         |    -0.39 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            1 |     4386 | 2024-02-09 | Endpoint          | W   | 0.012      | -            | -                | -                | -         |     0.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($119,288.26)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.37) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-07-22 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-06-16 |      0.868 | $30,000.00     | $26,043.06      |
| 2024-06-09 |      0.819 | $20,000.00     | $16,380.56      |
| 2024-05-12 |      0.632 | $7,000.00      | $4,426.53       |
| 2024-05-04 |      0.579 | $2,000.00      | $1,158.61       |
| 2024-05-02 |      0.566 | $3,500.00      | $1,980.90       |
| 2024-03-06 |      0.186 | $50,000.00     | $9,298.61       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
