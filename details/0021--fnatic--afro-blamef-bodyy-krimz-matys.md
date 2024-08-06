### Roster Details<br />
Team Name: fnatic<br />
Roster: afro, blameF, bodyy, KRIMZ, MATYS<br />
Global Rank: [21](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1403.9<br />
<br />
Final Rank Value (1403.9) = Starting Rank Value (1558.2) + Head To Head Adjustments (-154.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.699[<sup>1</sup>](#table2)
- Bounty Collected: 0.549[<sup>2</sup>](#table1)
- Opponent Network: 0.370[<sup>2</sup>](#table1)
- LAN Wins: 0.641[<sup>2</sup>](#table1)

The average of these factors is 0.565<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1558.2
- 400 + ( ( 0.565 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1558.2


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
|           63 |       60 | 2024-08-03 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -14.21 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           62 |      111 | 2024-08-02 | Nemiga            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.93 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           61 |      141 | 2024-08-01 | G2 Ares           | W   | 1.000      | -            | -                | -                | -         |     0.11 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           60 |      206 | 2024-07-31 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -24.31 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           59 |      298 | 2024-07-28 | Sangal            | L   | 1.000      | -            | -                | -                | -         |   -23.67 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           58 |      310 | 2024-07-28 | SAW               | W   | 1.000      | 0.435        | -                | 0.529 (0.230)    | -         |     5.75 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           57 |      326 | 2024-07-27 | MOUZ NXT          | W   | 1.000      | 0.435        | -                | 0.986 (0.428)    | -         |     4.16 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           56 |      360 | 2024-07-26 | Sampi             | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | -         |     1.34 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           55 |      490 | 2024-07-22 | Passion UA        | W   | 1.000      | 0.500        | 0.173 (0.086)    | 1.000 (0.500)    | -         |     4.43 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           54 |      521 | 2024-07-21 | MOUZ NXT          | W   | 1.000      | 0.500        | 0.139 (0.069)    | 0.986 (0.493)    | -         |     4.27 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           53 |      565 | 2024-07-20 | Sangal            | W   | 1.000      | 0.500        | 0.219 (0.109)    | 0.866 (0.433)    | -         |     6.99 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           52 |      586 | 2024-07-19 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.56 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           51 |      638 | 2024-07-18 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -27.21 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           50 |      763 | 2024-07-16 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | -         |     1.27 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           49 |     1015 | 2024-06-16 | 9z                | L   | 0.866      | -            | -                | -                | -         |   -13.56 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           48 |     1019 | 2024-06-16 | Ninjas in Pyjamas | W   | 0.865      | 0.548        | 0.254 (0.120)    | 0.544 (0.258)    | 1 (0.865) |    19.00 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           47 |     1043 | 2024-06-15 | RED Canids        | W   | 0.860      | 0.548        | -                | 0.748 (0.353)    | 1 (0.860) |     4.40 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           46 |     1057 | 2024-06-15 | Imperial          | W   | 0.858      | 0.548        | 0.234 (0.110)    | 0.674 (0.317)    | 1 (0.858) |     7.33 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           45 |     1082 | 2024-06-14 | RED Canids        | L   | 0.852      | -            | -                | -                | -         |   -22.46 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           44 |     1365 | 2024-06-07 | Ninjas in Pyjamas | L   | 0.805      | -            | -                | -                | -         |    -8.48 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           43 |     1421 | 2024-06-06 | BIG               | W   | 0.798      | 0.715        | 0.154 (0.088)    | -                | 1 (0.798) |     7.54 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           42 |     1447 | 2024-06-06 | FURIA             | L   | 0.797      | -            | -                | -                | -         |    -8.67 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           41 |     1462 | 2024-06-06 | Complexity        | W   | 0.796      | 0.715        | 0.342 (0.194)    | -                | 1 (0.796) |    18.92 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           40 |     1492 | 2024-06-05 | Eternal Fire      | W   | 0.791      | 0.715        | 0.739 (0.419)    | 0.449 (0.254)    | 1 (0.791) |    19.41 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           39 |     1508 | 2024-06-05 | BetBoom           | L   | 0.790      | -            | -                | -                | -         |   -15.01 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           38 |     1598 | 2024-06-02 | DMS               | L   | 0.770      | -            | -                | -                | -         |   -22.67 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           37 |     1663 | 2024-05-31 | SAW               | W   | 0.757      | -            | -                | -                | -         |     4.41 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           36 |     1664 | 2024-05-31 | Sangal            | W   | 0.757      | -            | -                | -                | -         |     3.19 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           35 |     2000 | 2024-05-18 | ENCE              | L   | 0.670      | -            | -                | -                | -         |   -12.95 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           34 |     2008 | 2024-05-18 | GamerLegion       | L   | 0.669      | -            | -                | -                | -         |   -18.24 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           33 |     2034 | 2024-05-17 | ENCE              | W   | 0.663      | 0.769        | 0.174 (0.089)    | -                | -         |     7.56 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           32 |     2400 | 2024-05-03 | 9 Pandas          | L   | 0.571      | -            | -                | -                | -         |   -17.08 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           31 |     2428 | 2024-05-02 | Sashi             | L   | 0.564      | -            | -                | -                | -         |   -15.16 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           30 |     2456 | 2024-05-01 | AMKAL             | W   | 0.557      | -            | -                | -                | -         |     1.93 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           29 |     2469 | 2024-05-01 | PARIVISION        | W   | 0.555      | -            | -                | -                | -         |     1.50 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           28 |     2492 | 2024-04-30 | Nexus             | W   | 0.549      | -            | -                | -                | -         |     0.36 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           27 |     2551 | 2024-04-27 | Virtus.pro        | L   | 0.530      | -            | -                | -                | -         |    -5.00 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           26 |     2592 | 2024-04-25 | Eternal Fire      | L   | 0.518      | -            | -                | -                | -         |    -4.60 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           25 |     2616 | 2024-04-24 | 3DMAX             | L   | 0.511      | -            | -                | -                | -         |    -5.89 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           24 |     2640 | 2024-04-23 | Virtus.pro        | W   | 0.503      | 0.889        | 0.498 (0.223)    | -                | 1 (0.503) |    11.28 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           23 |     2791 | 2024-04-18 | KOI               | L   | 0.471      | -            | -                | -                | -         |   -13.77 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           22 |     3045 | 2024-04-09 | Apeks             | L   | 0.412      | -            | -                | -                | -         |   -12.59 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           21 |     3079 | 2024-04-08 | Apeks             | W   | 0.405      | -            | -                | -                | -         |     0.34 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           20 |     3085 | 2024-04-08 | KOI               | W   | 0.404      | -            | -                | -                | -         |     0.84 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           19 |     3418 | 2024-03-23 | BetBoom           | L   | 0.296      | -            | -                | -                | -         |    -6.44 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           18 |     3454 | 2024-03-21 | 3DMAX             | W   | 0.284      | -            | -                | -                | -         |     5.89 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           17 |     3808 | 2024-03-06 | BLEED             | W   | 0.184      | -            | -                | -                | -         |     0.22 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           16 |     3851 | 2024-03-05 | Young Ninjas      | W   | 0.177      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           15 |     3868 | 2024-03-04 | 3DMAX             | W   | 0.170      | -            | -                | -                | -         |     3.67 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           14 |     3885 | 2024-03-03 | Gaimin Gladiators | L   | 0.165      | -            | -                | -                | -         |    -4.99 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           13 |     3890 | 2024-03-03 | AURA              | W   | 0.164      | -            | -                | -                | -         |     0.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           12 |     3900 | 2024-03-03 | ex-Preasy         | W   | 0.163      | -            | -                | -                | -         |     0.07 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           11 |     3937 | 2024-03-01 | ALTERNATE aTTaX   | W   | 0.150      | -            | -                | -                | -         |     0.19 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           10 |     3953 | 2024-02-28 | ex-Preasy         | L   | 0.138      | -            | -                | -                | -         |    -4.30 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            9 |     4069 | 2024-02-23 | GamerLegion       | L   | 0.104      | -            | -                | -                | -         |    -3.23 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            8 |     4214 | 2024-02-17 | SAW               | L   | 0.064      | -            | -                | -                | -         |    -1.81 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            7 |     4250 | 2024-02-16 | KOI               | L   | 0.056      | -            | -                | -                | -         |    -1.65 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            6 |     4273 | 2024-02-15 | AMKAL             | W   | 0.050      | -            | -                | -                | 1 (0.050) |     0.14 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            5 |     4300 | 2024-02-14 | Virtus.pro        | L   | 0.045      | -            | -                | -                | -         |    -0.44 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            4 |     4310 | 2024-02-14 | BetBoom           | W   | 0.044      | -            | -                | -                | 1 (0.044) |     0.43 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            3 |     4381 | 2024-02-09 | 3DMAX             | L   | 0.011      | -            | -                | -                | -         |    -0.12 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            2 |     4384 | 2024-02-09 | ex-Sprout         | L   | 0.011      | -            | -                | -                | -         |    -0.33 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            1 |     4388 | 2024-02-09 | Endpoint          | W   | 0.010      | -            | -                | -                | -         |     0.01 | afro, bodyy, KRIMZ, kyuubii, MATYS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($119,085.14)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.37) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-07-22 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-06-16 |      0.866 | $30,000.00     | $25,988.89      |
| 2024-06-09 |      0.817 | $20,000.00     | $16,344.44      |
| 2024-05-12 |      0.631 | $7,000.00      | $4,413.89       |
| 2024-05-04 |      0.578 | $2,000.00      | $1,155.00       |
| 2024-05-02 |      0.564 | $3,500.00      | $1,974.58       |
| 2024-03-06 |      0.184 | $50,000.00     | $9,208.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
