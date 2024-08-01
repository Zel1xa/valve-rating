### Roster Details<br />
Team Name: BetBoom<br />
Roster: KaiR0N-, Magnojez, nafany, s1ren, zorte<br />
Global Rank: [18](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1419.4<br />
<br />
Final Rank Value (1419.4) = Starting Rank Value (1442.4) + Head To Head Adjustments (-23.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.629[<sup>1</sup>](#table2)
- Bounty Collected: 0.546[<sup>2</sup>](#table1)
- Opponent Network: 0.266[<sup>2</sup>](#table1)
- LAN Wins: 0.586[<sup>2</sup>](#table1)

The average of these factors is 0.507<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1442.4
- 400 + ( ( 0.507 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1442.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           64 |     1259 | 2024-06-07 | Astralis          | L   | 0.832      | -            | -                | -                | -         |    -4.67 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           63 |     1316 | 2024-06-06 | Eternal Fire      | W   | 0.826      | 0.715        | 0.757 (0.447)    | 0.461 (0.272)    | 1 (0.826) |    20.37 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           62 |     1327 | 2024-06-06 | Complexity        | W   | 0.825      | 0.715        | 0.318 (0.188)    | 0.366 (0.216)    | 1 (0.825) |    20.54 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           61 |     1363 | 2024-06-05 | BIG               | W   | 0.820      | 0.715        | 0.132 (0.078)    | 0.299 (0.175)    | 1 (0.820) |     9.28 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           60 |     1379 | 2024-06-05 | FURIA             | L   | 0.819      | -            | -                | -                | -         |    -6.84 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           59 |     1388 | 2024-06-05 | fnatic            | W   | 0.818      | 0.715        | 0.292 (0.171)    | 0.568 (0.332)    | 1 (0.818) |    10.26 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           58 |     1674 | 2024-05-25 | B8                | L   | 0.746      | -            | -                | -                | -         |   -18.45 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           57 |     1699 | 2024-05-24 | DMS               | W   | 0.737      | -            | -                | -                | 0 (0.000) |     1.65 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           56 |     1804 | 2024-05-21 | Eternal Fire      | L   | 0.719      | -            | -                | -                | -         |    -3.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           55 |     1834 | 2024-05-20 | MIBR              | W   | 0.714      | 0.769        | 0.201 (0.110)    | 0.637 (0.349)    | -         |    12.81 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           54 |     1840 | 2024-05-20 | Astralis          | L   | 0.713      | -            | -                | -                | -         |    -2.99 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           53 |     1857 | 2024-05-20 | MIBR              | W   | 0.711      | 0.769        | 0.201 (0.110)    | 0.637 (0.348)    | -         |    13.31 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           52 |     2025 | 2024-05-15 | Falcons           | L   | 0.680      | -            | -                | -                | -         |    -9.29 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           51 |     2096 | 2024-05-14 | MOUZ              | L   | 0.672      | -            | -                | -                | -         |    -1.05 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           50 |     2141 | 2024-05-12 | B8                | L   | 0.660      | -            | -                | -                | -         |   -17.65 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           49 |     2145 | 2024-05-12 | 9 Pandas          | W   | 0.659      | -            | -                | -                | -         |     2.26 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           48 |     2178 | 2024-05-11 | Metizport         | W   | 0.652      | -            | -                | -                | -         |     1.72 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           47 |     2195 | 2024-05-10 | Enterprise        | W   | 0.645      | 0.435        | -                | 0.622 (0.174)    | -         |     1.16 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           46 |     2257 | 2024-05-07 | FlyQuest          | L   | 0.626      | -            | -                | -                | -         |   -14.51 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           45 |     2308 | 2024-05-04 | AMKAL             | L   | 0.606      | -            | -                | -                | -         |   -15.26 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           44 |     2313 | 2024-05-04 | 9 Pandas          | W   | 0.605      | -            | -                | -                | -         |     1.66 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           43 |     2336 | 2024-05-03 | Insilio           | W   | 0.597      | -            | -                | -                | -         |     1.24 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           42 |     2379 | 2024-05-01 | EYEBALLERS        | W   | 0.586      | -            | -                | -                | -         |     0.96 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           41 |     2410 | 2024-04-30 | 3DMAX             | L   | 0.578      | -            | -                | -                | -         |    -4.47 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           40 |     2485 | 2024-04-26 | M80               | W   | 0.554      | 0.889        | 0.190 (0.094)    | 0.641 (0.316)    | 1 (0.554) |     5.18 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           39 |     2498 | 2024-04-26 | Falcons           | W   | 0.552      | 0.889        | 0.205 (0.101)    | -                | 1 (0.552) |     9.18 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           38 |     2521 | 2024-04-25 | Vitality          | L   | 0.546      | -            | -                | -                | -         |    -1.43 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           37 |     2554 | 2024-04-23 | M80               | W   | 0.533      | 0.889        | 0.190 (0.090)    | 0.641 (0.304)    | 1 (0.533) |     4.98 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           36 |     2669 | 2024-04-19 | Cloud9            | L   | 0.506      | -            | -                | -                | -         |   -13.74 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           35 |     2680 | 2024-04-19 | Eternal Fire      | L   | 0.505      | -            | -                | -                | -         |    -2.38 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           34 |     2705 | 2024-04-18 | Apeks             | W   | 0.500      | -            | -                | -                | -         |     1.09 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           33 |     2709 | 2024-04-18 | brazylijski luz   | W   | 0.500      | -            | -                | -                | -         |     0.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           32 |     2716 | 2024-04-18 | Serbia            | W   | 0.499      | -            | -                | -                | -         |     0.40 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           31 |     2837 | 2024-04-14 | 3DMAX             | W   | 0.472      | 0.358        | 0.505 (0.085)    | 1.000 (0.169)    | -         |    11.51 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           30 |     2843 | 2024-04-13 | OG                | L   | 0.467      | -            | -                | -                | -         |   -13.05 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           29 |     2847 | 2024-04-13 | Aurora            | L   | 0.466      | -            | -                | -                | -         |    -3.26 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           28 |     2855 | 2024-04-13 | Sampi             | W   | 0.464      | -            | -                | -                | -         |     0.86 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           27 |     2883 | 2024-04-11 | Aurora            | L   | 0.453      | -            | -                | -                | -         |    -3.27 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           26 |     2891 | 2024-04-11 | Ninjas in Pyjamas | W   | 0.453      | -            | -                | -                | -         |     9.44 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           25 |     2897 | 2024-04-11 | AMKAL             | L   | 0.452      | -            | -                | -                | -         |   -11.93 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           24 |     2936 | 2024-04-10 | Aurora            | W   | 0.446      | -            | -                | -                | -         |    10.99 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           23 |     2995 | 2024-04-09 | BIG               | W   | 0.439      | -            | -                | -                | -         |     3.66 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           22 |     3067 | 2024-04-06 | Alliance          | W   | 0.419      | -            | -                | -                | -         |     0.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           21 |     3081 | 2024-04-05 | BLEED             | W   | 0.413      | -            | -                | -                | -         |     1.13 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           20 |     3117 | 2024-04-04 | Alliance          | W   | 0.407      | -            | -                | -                | -         |     0.57 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           19 |     3131 | 2024-04-04 | BLEED             | W   | 0.405      | -            | -                | -                | -         |     1.10 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           18 |     3309 | 2024-03-27 | FAVBET            | L   | 0.353      | -            | -                | -                | -         |   -10.87 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           17 |     3351 | 2024-03-24 | FORZE             | L   | 0.331      | -            | -                | -                | -         |    -9.84 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           16 |     3365 | 2024-03-23 | fnatic            | W   | 0.325      | -            | -                | -                | -         |     4.26 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           15 |     3407 | 2024-03-21 | B8                | W   | 0.311      | -            | -                | -                | -         |     1.36 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           14 |     3812 | 2024-03-05 | BLEED             | L   | 0.205      | -            | -                | -                | -         |    -6.00 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           13 |     3830 | 2024-03-04 | Gaimin Gladiators | W   | 0.198      | -            | -                | -                | -         |     0.50 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           12 |     3842 | 2024-03-03 | ex-Preasy         | L   | 0.193      | -            | -                | -                | -         |    -5.93 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           11 |     3847 | 2024-03-03 | ex-Sprout         | W   | 0.193      | -            | -                | -                | -         |     0.04 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           10 |     3890 | 2024-03-01 | ex-Preasy         | W   | 0.180      | -            | -                | -                | -         |     0.15 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            9 |     3923 | 2024-02-28 | ALTERNATE aTTaX   | W   | 0.165      | -            | -                | -                | -         |     0.40 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            8 |     4035 | 2024-02-23 | ex-Guild Eagles   | L   | 0.132      | -            | -                | -                | -         |    -4.03 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            7 |     4178 | 2024-02-17 | Eternal Fire      | L   | 0.093      | -            | -                | -                | -         |    -0.52 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            6 |     4207 | 2024-02-16 | Natus Vincere     | L   | 0.086      | -            | -                | -                | -         |    -0.12 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            5 |     4240 | 2024-02-15 | Enterprise        | W   | 0.078      | -            | -                | -                | 1 (0.078) |     0.13 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            4 |     4274 | 2024-02-14 | Into the Breach   | W   | 0.073      | -            | -                | -                | 1 (0.073) |     0.02 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            3 |     4278 | 2024-02-14 | fnatic            | L   | 0.072      | -            | -                | -                | -         |    -1.35 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            2 |     4371 | 2024-02-08 | FORZE             | L   | 0.033      | -            | -                | -                | -         |    -1.01 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            1 |     4378 | 2024-02-08 | Nemiga            | L   | 0.032      | -            | -                | -                | -         |    -0.84 | danistzz, KaiR0N-, nafany, s1ren, zorte |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($84,065.28)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.26) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.846 | $20,000.00     | $16,916.67      |
| 2024-05-26 |      0.753 | $2,000.00      | $1,505.56       |
| 2024-05-23 |      0.732 | $12,500.00     | $9,151.04       |
| 2024-05-12 |      0.660 | $10,000.00     | $6,596.53       |
| 2024-05-12 |      0.659 | $17,500.00     | $11,535.42      |
| 2024-05-04 |      0.606 | $10,000.00     | $6,061.11       |
| 2024-05-02 |      0.593 | $1,000.00      | $592.78         |
| 2024-04-14 |      0.472 | $52,500.00     | $24,798.96      |
| 2024-04-14 |      0.472 | $9,000.00      | $4,247.50       |
| 2024-03-06 |      0.213 | $12,500.00     | $2,659.72       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
