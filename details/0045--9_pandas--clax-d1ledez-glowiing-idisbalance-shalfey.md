### Roster Details<br />
Team Name: 9 Pandas<br />
Roster: clax, d1Ledez, glowiing, iDISBALANCE, shalfey<br />
Global Rank: [45](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1100.0<br />
<br />
Final Rank Value (1100.0) = Starting Rank Value (995.8) + Head To Head Adjustments (104.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.478[<sup>1</sup>](#table2)
- Bounty Collected: 0.412[<sup>2</sup>](#table1)
- Opponent Network: 0.236[<sup>2</sup>](#table1)
- LAN Wins: 0.036[<sup>2</sup>](#table1)

The average of these factors is 0.290<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 995.8
- 400 + ( ( 0.290 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 995.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           62 |       17 | 2024-08-05 | Johnny Speeds     | W   | 1.000      | 0.143        | 0.122 (0.017)    | -                | 0 (0.000) |    22.35 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           61 |       44 | 2024-08-04 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.57 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           60 |       72 | 2024-08-03 | GUN5              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.43 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           59 |      100 | 2024-08-02 | 9INE              | W   | 1.000      | 0.426        | -                | 0.533 (0.227)    | 0 (0.000) |    10.53 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           58 |      114 | 2024-08-02 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.94 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           57 |      134 | 2024-08-01 | PARIVISION        | L   | 1.000      | -            | -                | -                | -         |   -13.21 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           56 |      226 | 2024-07-30 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -19.00 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           55 |      236 | 2024-07-30 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.07 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           54 |      295 | 2024-07-28 | QUAZAR            | W   | 1.000      | -            | -                | -                | -         |     0.77 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           53 |      460 | 2024-07-23 | Betera            | W   | 1.000      | -            | -                | -                | -         |     2.33 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           52 |      700 | 2024-07-17 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |    -5.01 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           51 |     1214 | 2024-06-10 | Aurora            | L   | 0.823      | -            | -                | -                | -         |    -3.35 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           50 |     1217 | 2024-06-10 | SINNERS           | W   | 0.823      | -            | -                | -                | -         |    12.90 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           49 |     1222 | 2024-06-10 | 3DMAX             | L   | 0.823      | -            | -                | -                | -         |    -2.98 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           48 |     1254 | 2024-06-09 | RUSH B            | L   | 0.817      | -            | -                | -                | -         |   -17.75 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           47 |     1261 | 2024-06-09 | PARIVISION        | L   | 0.817      | -            | -                | -                | -         |   -12.38 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           46 |     1269 | 2024-06-09 | SAW               | W   | 0.816      | 0.143        | 0.104 (0.012)    | -                | -         |    16.00 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           45 |     1280 | 2024-06-09 | Monte             | W   | 0.816      | -            | -                | -                | -         |    11.23 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           44 |     1544 | 2024-06-04 | Sangal            | L   | 0.784      | -            | -                | -                | -         |   -10.17 | clax, d1Ledez, glowiing, iDISBALANCE, shalfey |
|           43 |     1768 | 2024-05-26 | MOUZ NXT          | W   | 0.724      | 0.435        | 0.139 (0.044)    | 0.986 (0.310)    | -         |    11.75 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           42 |     1772 | 2024-05-26 | 1WIN              | W   | 0.723      | 0.435        | -                | 0.696 (0.219)    | -         |    10.78 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           41 |     1786 | 2024-05-25 | Space             | W   | 0.718      | -            | -                | -                | -         |     6.16 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           40 |     1812 | 2024-05-24 | SINNERS           | W   | 0.709      | 0.435        | 0.037 (0.011)    | 0.808 (0.249)    | -         |    12.47 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           39 |     1941 | 2024-05-20 | BLEED             | L   | 0.684      | -            | -                | -                | -         |    -2.59 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           38 |     1996 | 2024-05-18 | Passion UA        | W   | 0.671      | 0.500        | 0.173 (0.058)    | 1.000 (0.335)    | -         |    10.87 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           37 |     2067 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.657      | 0.500        | -                | 0.550 (0.181)    | -         |     8.81 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           36 |     2227 | 2024-05-12 | BetBoom           | L   | 0.630      | -            | -                | -                | -         |    -2.19 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           35 |     2253 | 2024-05-11 | RUBY              | W   | 0.624      | 0.435        | 0.095 (0.026)    | -                | -         |     8.15 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           34 |     2300 | 2024-05-09 | Zero Tenacity     | W   | 0.610      | 0.435        | 0.143 (0.038)    | 1.000 (0.265)    | -         |    11.11 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           33 |     2340 | 2024-05-07 | Sashi             | L   | 0.597      | -            | -                | -                | -         |    -4.46 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           32 |     2385 | 2024-05-05 | ARCRED            | W   | 0.582      | -            | -                | -                | -         |     7.37 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           31 |     2393 | 2024-05-04 | BetBoom           | L   | 0.577      | -            | -                | -                | -         |    -1.60 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           30 |     2400 | 2024-05-03 | fnatic            | W   | 0.571      | 0.435        | 0.371 (0.092)    | 0.696 (0.173)    | -         |    17.08 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           29 |     2444 | 2024-05-02 | MOUZ NXT          | W   | 0.562      | 0.435        | 0.139 (0.034)    | 0.986 (0.241)    | -         |    11.07 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           28 |     2490 | 2024-04-30 | Passion UA        | L   | 0.549      | -            | -                | -                | -         |    -7.29 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           27 |     2529 | 2024-04-28 | Gaimin Gladiators | W   | 0.536      | -            | -                | -                | -         |     9.48 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           26 |     2567 | 2024-04-26 | Passion UA        | L   | 0.524      | -            | -                | -                | -         |    -7.15 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           25 |     2568 | 2024-04-26 | Passion UA        | L   | 0.524      | -            | -                | -                | -         |    -6.83 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           24 |     2758 | 2024-04-19 | Alliance          | L   | 0.476      | -            | -                | -                | -         |   -10.08 | clax, d1Ledez, glowiing, iDISBALANCE, Xoma    |
|           23 |     2851 | 2024-04-17 | Sangal            | L   | 0.462      | -            | -                | -                | -         |    -4.36 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           22 |     2991 | 2024-04-10 | SAW               | L   | 0.418      | -            | -                | -                | -         |    -3.49 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           21 |     3047 | 2024-04-09 | SINNERS           | L   | 0.411      | -            | -                | -                | -         |    -3.75 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           20 |     3067 | 2024-04-09 | Aurora            | L   | 0.409      | -            | -                | -                | -         |    -0.31 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           19 |     3080 | 2024-04-08 | 1WIN              | L   | 0.404      | -            | -                | -                | -         |    -7.50 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           18 |     3088 | 2024-04-08 | Metizport         | W   | 0.404      | -            | -                | -                | -         |     4.53 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           17 |     3151 | 2024-04-05 | Secret            | L   | 0.383      | -            | -                | -                | -         |   -11.27 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           16 |     3181 | 2024-04-04 | TSM               | W   | 0.378      | -            | -                | -                | -         |     1.59 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           15 |     3227 | 2024-04-03 | EYEBALLERS        | W   | 0.371      | -            | -                | -                | -         |     4.19 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           14 |     3234 | 2024-04-03 | 9INE              | W   | 0.370      | -            | -                | -                | -         |     0.73 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           13 |     3265 | 2024-04-02 | Sangal            | W   | 0.364      | 0.500        | 0.219 (0.040)    | 0.866 (0.158)    | -         |     7.89 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           12 |     3797 | 2024-03-06 | KOI               | L   | 0.185      | -            | -                | -                | -         |    -2.22 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           11 |     3936 | 2024-03-01 | Aurora            | L   | 0.150      | -            | -                | -                | -         |    -0.11 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|           10 |     3943 | 2024-02-29 | FORZE             | L   | 0.145      | -            | -                | -                | -         |    -2.94 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            9 |     3956 | 2024-02-28 | Spirit Academy    | W   | 0.138      | -            | -                | -                | -         |     0.32 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            8 |     3961 | 2024-02-28 | Croatia           | W   | 0.137      | -            | -                | -                | -         |     0.24 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            7 |     4054 | 2024-02-24 | GamerLegion       | W   | 0.110      | -            | -                | -                | 1 (0.110) |     0.77 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            6 |     4071 | 2024-02-23 | Astralis          | W   | 0.103      | -            | -                | -                | 1 (0.103) |     3.18 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            5 |     4220 | 2024-02-17 | AMKAL             | L   | 0.063      | -            | -                | -                | -         |    -0.60 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            4 |     4243 | 2024-02-16 | 3DMAX             | W   | 0.057      | -            | -                | -                | 1 (0.057) |     1.76 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            3 |     4274 | 2024-02-15 | KOI               | L   | 0.049      | -            | -                | -                | -         |    -0.59 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            2 |     4308 | 2024-02-14 | SAW               | W   | 0.044      | -            | -                | -                | 1 (0.044) |     1.00 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |
|            1 |     4320 | 2024-02-14 | FaZe              | L   | 0.043      | -            | -                | -                | -         |    -0.03 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($26,061.53)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.817 | $5,000.00      | $4,087.15       |
| 2024-05-26 |      0.724 | $22,000.00     | $15,931.67      |
| 2024-05-12 |      0.631 | $5,000.00      | $3,155.21       |
| 2024-05-04 |      0.578 | $5,000.00      | $2,887.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
