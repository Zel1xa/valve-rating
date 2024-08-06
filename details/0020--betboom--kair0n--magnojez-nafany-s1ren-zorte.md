### Roster Details<br />
Team Name: BetBoom<br />
Roster: KaiR0N-, Magnojez, nafany, s1ren, zorte<br />
Global Rank: [20](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [15]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1417.2<br />
<br />
Final Rank Value (1417.2) = Starting Rank Value (1416.2) + Head To Head Adjustments (0.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.623[<sup>1</sup>](#table2)
- Bounty Collected: 0.546[<sup>2</sup>](#table1)
- Opponent Network: 0.254[<sup>2</sup>](#table1)
- LAN Wins: 0.553[<sup>2</sup>](#table1)

The average of these factors is 0.494<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1416.2
- 400 + ( ( 0.494 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1416.2


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
|           63 |     1403 | 2024-06-07 | Astralis          | L   | 0.799      | -            | -                | -                | -         |    -3.81 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           62 |     1458 | 2024-06-06 | Eternal Fire      | W   | 0.793      | 0.715        | 0.738 (0.419)    | 0.438 (0.248)    | 1 (0.793) |    19.49 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           61 |     1469 | 2024-06-06 | Complexity        | W   | 0.792      | 0.715        | 0.341 (0.193)    | 0.364 (0.206)    | 1 (0.792) |    20.07 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           60 |     1503 | 2024-06-05 | BIG               | W   | 0.787      | 0.715        | 0.154 (0.087)    | -                | 1 (0.787) |    10.77 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           59 |     1518 | 2024-06-05 | FURIA             | L   | 0.787      | -            | -                | -                | -         |    -6.46 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           58 |     1527 | 2024-06-05 | fnatic            | W   | 0.786      | 0.715        | 0.371 (0.208)    | 0.680 (0.382)    | 1 (0.786) |    14.94 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           57 |     1810 | 2024-05-25 | B8                | L   | 0.713      | -            | -                | -                | -         |   -17.15 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           56 |     1835 | 2024-05-24 | DMS               | W   | 0.704      | -            | -                | -                | 0 (0.000) |     1.66 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           55 |     1925 | 2024-05-21 | Eternal Fire      | L   | 0.687      | -            | -                | -                | -         |    -3.48 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           54 |     1953 | 2024-05-20 | MIBR              | W   | 0.681      | 0.769        | 0.207 (0.109)    | 0.633 (0.331)    | -         |    12.54 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           53 |     1959 | 2024-05-20 | Astralis          | L   | 0.680      | -            | -                | -                | -         |    -2.33 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           52 |     1973 | 2024-05-20 | MIBR              | W   | 0.678      | 0.769        | 0.207 (0.108)    | 0.633 (0.330)    | -         |    12.96 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           51 |     2135 | 2024-05-15 | Falcons           | L   | 0.647      | -            | -                | -                | -         |    -9.17 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           50 |     2200 | 2024-05-14 | MOUZ              | L   | 0.639      | -            | -                | -                | -         |    -1.08 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           49 |     2242 | 2024-05-12 | B8                | L   | 0.627      | -            | -                | -                | -         |   -16.52 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           48 |     2246 | 2024-05-12 | 9 Pandas          | W   | 0.626      | 0.435        | -                | 0.700 (0.190)    | -         |     2.25 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           47 |     2279 | 2024-05-11 | Metizport         | W   | 0.619      | -            | -                | -                | -         |     1.70 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           46 |     2296 | 2024-05-10 | Enterprise        | W   | 0.612      | 0.435        | -                | 0.641 (0.170)    | -         |     1.22 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           45 |     2356 | 2024-05-07 | FlyQuest          | L   | 0.593      | -            | -                | -                | -         |   -13.99 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           44 |     2407 | 2024-05-04 | AMKAL             | L   | 0.573      | -            | -                | -                | -         |   -14.29 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           43 |     2412 | 2024-05-04 | 9 Pandas          | W   | 0.573      | 0.435        | -                | 0.700 (0.174)    | -         |     1.65 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           42 |     2435 | 2024-05-03 | Insilio           | W   | 0.564      | -            | -                | -                | -         |     1.24 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           41 |     2476 | 2024-05-01 | EYEBALLERS        | W   | 0.553      | -            | -                | -                | -         |     0.95 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           40 |     2506 | 2024-04-30 | 3DMAX             | L   | 0.545      | -            | -                | -                | -         |    -3.81 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           39 |     2580 | 2024-04-26 | M80               | W   | 0.521      | 0.889        | 0.188 (0.087)    | 0.563 (0.261)    | 1 (0.521) |     4.76 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           38 |     2594 | 2024-04-26 | Falcons           | W   | 0.519      | 0.889        | 0.219 (0.101)    | -                | 1 (0.519) |     8.42 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           37 |     2617 | 2024-04-25 | Vitality          | L   | 0.513      | -            | -                | -                | -         |    -1.21 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           36 |     2649 | 2024-04-23 | M80               | W   | 0.500      | 0.889        | 0.188 (0.084)    | 0.563 (0.250)    | 1 (0.500) |     4.56 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           35 |     2758 | 2024-04-19 | Cloud9            | L   | 0.474      | -            | -                | -                | -         |   -13.00 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           34 |     2769 | 2024-04-19 | Eternal Fire      | L   | 0.473      | -            | -                | -                | -         |    -2.32 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           33 |     2793 | 2024-04-18 | Apeks             | W   | 0.467      | -            | -                | -                | -         |     1.00 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           32 |     2797 | 2024-04-18 | brazylijski luz   | W   | 0.467      | -            | -                | -                | -         |     0.53 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           31 |     2804 | 2024-04-18 | Serbia            | W   | 0.467      | -            | -                | -                | -         |     0.40 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           30 |     2923 | 2024-04-14 | 3DMAX             | W   | 0.439      | 0.358        | 0.510 (0.080)    | -                | -         |    10.97 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           29 |     2929 | 2024-04-13 | OG                | L   | 0.434      | -            | -                | -                | -         |   -12.09 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           28 |     2933 | 2024-04-13 | Aurora            | L   | 0.433      | -            | -                | -                | -         |    -2.84 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           27 |     2941 | 2024-04-13 | Sampi             | W   | 0.432      | -            | -                | -                | -         |     0.83 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           26 |     2968 | 2024-04-11 | Aurora            | L   | 0.421      | -            | -                | -                | -         |    -2.83 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           25 |     2976 | 2024-04-11 | Ninjas in Pyjamas | W   | 0.420      | -            | -                | -                | -         |    10.74 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           24 |     2982 | 2024-04-11 | AMKAL             | L   | 0.419      | -            | -                | -                | -         |   -10.93 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           23 |     3021 | 2024-04-10 | Aurora            | W   | 0.413      | -            | -                | -                | -         |    10.40 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           22 |     3080 | 2024-04-09 | BIG               | W   | 0.406      | -            | -                | -                | -         |     4.76 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           21 |     3152 | 2024-04-06 | Alliance          | W   | 0.386      | -            | -                | -                | -         |     0.56 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           20 |     3166 | 2024-04-05 | BLEED             | W   | 0.380      | -            | -                | -                | -         |     1.07 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           19 |     3202 | 2024-04-04 | Alliance          | W   | 0.374      | -            | -                | -                | -         |     0.56 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           18 |     3215 | 2024-04-04 | BLEED             | W   | 0.372      | -            | -                | -                | -         |     1.04 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           17 |     3385 | 2024-03-27 | FAVBET            | L   | 0.321      | -            | -                | -                | -         |    -9.83 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           16 |     3423 | 2024-03-24 | FORZE             | L   | 0.299      | -            | -                | -                | -         |    -8.86 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           15 |     3437 | 2024-03-23 | fnatic            | W   | 0.292      | -            | -                | -                | -         |     6.36 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           14 |     3479 | 2024-03-21 | B8                | W   | 0.279      | -            | -                | -                | -         |     1.29 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           13 |     3873 | 2024-03-05 | BLEED             | L   | 0.172      | -            | -                | -                | -         |    -5.02 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           12 |     3891 | 2024-03-04 | Gaimin Gladiators | W   | 0.165      | -            | -                | -                | -         |     0.41 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           11 |     3903 | 2024-03-03 | ex-Preasy         | L   | 0.161      | -            | -                | -                | -         |    -4.92 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           10 |     3908 | 2024-03-03 | ex-Sprout         | W   | 0.160      | -            | -                | -                | -         |     0.03 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            9 |     3950 | 2024-03-01 | ex-Preasy         | W   | 0.147      | -            | -                | -                | -         |     0.13 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            8 |     3982 | 2024-02-28 | ALTERNATE aTTaX   | W   | 0.133      | -            | -                | -                | -         |     0.34 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            7 |     4089 | 2024-02-23 | ex-Guild Eagles   | L   | 0.099      | -            | -                | -                | -         |    -3.02 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            6 |     4230 | 2024-02-17 | Eternal Fire      | L   | 0.060      | -            | -                | -                | -         |    -0.33 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            5 |     4258 | 2024-02-16 | Natus Vincere     | L   | 0.053      | -            | -                | -                | -         |    -0.07 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            4 |     4291 | 2024-02-15 | Enterprise        | W   | 0.046      | -            | -                | -                | 1 (0.046) |     0.08 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            3 |     4325 | 2024-02-14 | Into the Breach   | W   | 0.040      | -            | -                | -                | 1 (0.040) |     0.00 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            2 |     4329 | 2024-02-14 | fnatic            | L   | 0.040      | -            | -                | -                | -         |    -0.39 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            1 |     4412 | 2024-02-08 | FORZE             | L   | 0.001      | -            | -                | -                | -         |    -0.02 | danistzz, KaiR0N-, nafany, s1ren, zorte |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($79,246.94)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.813 | $20,000.00     | $16,261.11      |
| 2024-05-26 |      0.720 | $2,000.00      | $1,440.00       |
| 2024-05-23 |      0.699 | $12,500.00     | $8,741.32       |
| 2024-05-12 |      0.627 | $10,000.00     | $6,268.75       |
| 2024-05-12 |      0.626 | $17,500.00     | $10,961.81      |
| 2024-05-04 |      0.573 | $10,000.00     | $5,733.33       |
| 2024-05-02 |      0.560 | $1,000.00      | $560.00         |
| 2024-04-14 |      0.440 | $52,500.00     | $23,078.13      |
| 2024-04-14 |      0.439 | $9,000.00      | $3,952.50       |
| 2024-03-06 |      0.180 | $12,500.00     | $2,250.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
